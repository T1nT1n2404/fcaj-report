# Hướng dẫn Deploy Hugo Site lên GitHub Pages

Repo: `https://github.com/T1nT1n2404/fcaj-report`  
Website đã deploy: **https://t1nt1n2404.github.io/fcaj-report/**

---

## 1. Cách hoạt động

Repo dùng **GitHub Actions** để tự động build Hugo site và deploy lên GitHub Pages mỗi khi push lên nhánh `main`.

- Workflow: `.github/workflows/hugo.yml`
- Mỗi lần `git push origin main` → GitHub Actions chạy → build site → publish lên Pages.

---

## 2. Điều kiện tiên quyết

1. Đã cài **Hugo** (để build/test local): https://gohugo.io/installation/
2. Tài khoản GitHub đã đăng nhập trên máy (git credential).

---

## 3. Bật GitHub Pages bằng GitHub Actions (chỉ làm 1 lần)

> ⚠️ **Bước này bắt buộc** nếu Page chưa được bật đúng nguồn.

1. Vào repo trên GitHub: https://github.com/T1nT1n2404/fcaj-report
2. Chọn tab **Settings** → menu trái chọn **Pages**.
3. Trong mục **Build and deployment**:
   - **Source**: chọn **GitHub Actions** (quan trọng!)
4. Không cần chọn branch nào cả (vì dùng Actions).

> Lưu ý: nếu để Source = "Deploy from a branch" (ví dụ branch `gh-pages`), workflow sẽ lỗi. Phải đổi sang **GitHub Actions**.

---

## 4. Deploy (mỗi lần cập nhật nội dung)

```bash
# Bước 1: Test build local trước (tùy chọn nhưng nên làm)
hugo

# Bước 2: Commit thay đổi
git add .
git commit -m "update content"

# Bước 3: Push lên GitHub → Actions tự build & deploy
git push origin main
```

Sau khi push, kiểm tra tiến độ tại tab **Actions** của repo.

---

## 5. Kiểm tra kết quả

- Mở website: https://t1nt1n2404.github.io/fcaj-report/
- Kiểm tra tiến độ deploy: https://github.com/T1nT1n2404/fcaj-report/actions

---

## 6. Cấu trúc quan trọng

| File | Vai trò |
|------|---------|
| `config.toml` | `baseURL = "https://t1nt1n2404.github.io/fcaj-report/"` — phải khớp tên repo |
| `.github/workflows/hugo.yml` | Workflow build + deploy bằng GitHub Actions |
| `.gitignore` | Có `gh-pages-deploy/` — thư mục build KHÔNG commit vào `main` |
| `content/` | Nội dung Markdown của website |

---

## 7. Xử lý sự cố thường gặp

| Triệu chứng | Nguyên nhân & Cách xử lý |
|-------------|--------------------------|
| Trang 404 | `baseURL` sai tên repo → sửa `config.toml`, push lại |
| Actions lỗi "Not authorized" | Settings → Pages → Source = **GitHub Actions** |
| Nội dung cũ vẫn hiện | Đợi 1-2 phút cho Actions chạy xong |
| Lỗi thiếu theme `hugo-theme-learn` | Theme là submodule — chạy `git submodule update --init --recursive` |