---
title: "Chia sẻ & Phản hồi"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 7. </b> "
---

### Đánh giá tổng quan

**1. Môi trường làm việc**  
Môi trường làm việc của chương trình FCAJ rất thân thiện, cởi mở và được tổ chức tốt. Tất cả tài liệu dự án, template và hướng dẫn đều được cấu trúc rõ ràng, dễ tiếp cận, giúp tôi bắt đầu nhanh chóng mà không bị bối rối. Các thành viên FCAJ luôn sẵn sàng hỗ trợ khi tôi gặp khó khăn, kể cả ngoài giờ làm việc. Chương trình cũng khuyến khích thảo luận và chia sẻ kiến thức, tạo không khí thoải mái để tôi đặt câu hỏi và học hỏi từ mọi người.

**2. Sự hỗ trợ từ Mentor / Quản trị nhóm**  
Mentor của tôi đã hướng dẫn rất chi tiết và thực tế trong suốt dự án. Thay vì đưa ra câu trả lời trực tiếp, mentor định hướng tôi phân tích vấn đề từng bước và khuyến khích tự nghiên cứu tài liệu AWS — điều này giúp tôi thực sự hiểu cách kiến trúc hoạt động thay vì chỉ làm theo hướng dẫn. Ban quản trị xử lý các thủ tục hành chính mượt mà, cung cấp đầy đủ tài nguyên và quyền truy cập AWS cần thiết, tạo điều kiện thuận lợi để tôi hoàn thành workshop và báo cáo đúng hạn.

**3. Mức độ phù hợp của công việc với chuyên ngành học tập**  
Dự án — xây dựng **hệ thống AWS CloudHop RAG (Retrieval-Augmented Generation)** — rất phù hợp với nền tảng học thuật của tôi trong lĩnh vực Khoa học Máy tính và Trí tuệ Nhân tạo. Kiến trúc full-stack bao phủ nhiều lĩnh vực tôi đã học tại trường: điện toán đám mây (S3, EC2, API Gateway), cơ sở dữ liệu (vector storage), AI/ML (embedding models, LLM, RAG pipeline) và bảo mật (VPC endpoints, IAM policies). Đồng thời, dự án cũng giới thiệu những thực tiễn kỹ thuật đám mây thực tế mà trường lớp ít dạy chuyên sâu, như offline artifact pipelines, cấu hình VPC endpoint và tối ưu chi phí/bảo mật.

**4. Cơ hội học tập và phát triển kỹ năng**  
Kỳ thực tập này đã cải thiện đáng kể cả kỹ năng chuyên môn lẫn kỹ năng mềm của tôi. Về mặt kỹ thuật, tôi học được cách thiết kế và triển khai hệ thống RAG hoàn chỉnh trên AWS, bao gồm:
- Xây dựng **offline pipeline**: xử lý tài liệu, chunking, tạo embedding và lưu trữ vector trên Amazon S3.
- Thiết lập **online query pipeline**: backend trên EC2, RESTful API qua API Gateway và frontend triển khai trên AWS Amplify.
- Cấu hình **VPC endpoints và S3 bucket policies** để giao tiếp bảo mật giữa môi trường on-premises và AWS.
- Kiểm thử, xác thực, đánh giá hiệu năng hệ thống, sau đó xử lý **vận hành, giám sát, bảo mật và quản lý chi phí**.

Ngoài kỹ năng kỹ thuật, tôi còn rèn luyện công cụ quản lý dự án, giao tiếp viết chuyên nghiệp (worklog hàng tuần, báo cáo) và trình bày nội dung kỹ thuật rõ ràng.

**5. Văn hóa công ty và tinh thần đồng đội**  
Văn hóa chương trình rất tích cực và chuyên nghiệp. Mọi người tôn trọng thời gian và ý tưởng của nhau, đồng thời vẫn duy trì bầu không khí thân thiện, hỗ trợ. Khi tôi gặp khó khăn trong các lab workshop, các thành viên và mentor tích cực giúp tôi debug và gỡ bế tắc. Tinh thần hợp tác này khiến tôi cảm thấy mình là thành viên thực sự của đội, không chỉ là thực tập sinh, và thúc đẩy tôi hoàn thành dự án với chất lượng cao.

**6. Chính sách / Phúc lợi thực tập**  
Chương trình cung cấp AWS credits và môi trường sandbox cần thiết, cho phép tôi thử nghiệm tự do mà không lo về chi phí. Lịch làm việc linh hoạt — với các mốc hàng tuần rõ ràng trong template worklog — giúp tôi cân bằng lịch học đại học mà vẫn hoàn thành dự án đúng hạn. Các template có sẵn (worklog, báo cáo, blog) cực kỳ hữu ích để giữ mọi thứ nhất quán và chuyên nghiệp.

---

### Câu hỏi bổ sung
- **Điều gì khiến bạn hài lòng nhất trong kỳ thực tập?**  
  Khoảnh khắc hài lòng nhất là khi **hệ thống RAG hoạt động end-to-end**: tài liệu được xử lý offline thành vector, và online query pipeline truy xuất thành công ngữ cảnh liên quan từ Amazon S3, trả về câu trả lời chính xác từ LLM. Nhìn thấy tất cả dịch vụ AWS (S3, EC2, API Gateway, Amplify) kết nối với nhau đúng như thiết kế là một thành tựu lớn.

- **Theo bạn, công ty nên cải thiện điều gì cho thực tập sinh tương lai?**  
  Chương trình có thể cung cấp thêm **video hướng dẫn ghi sẵn** cho các lab phức tạp nhất (ví dụ: cấu hình VPC endpoint, IAM policies) và một **buổi giới thiệu kiến trúc tổng thể** trước khi bắt đầu workshop, để thực tập sinh hình dung toàn bộ hệ thống trước khi triển khai. Thêm ví dụ cấp mã nguồn cho phần tích hợp backend và frontend cũng sẽ giảm bớt sự bối rối ban đầu.

- **Nếu giới thiệu cho bạn bè, bạn có đề xuất họ thực tập tại đây không? Vì sao?**  
  Có, tôi chắc chắn sẽ giới thiệu chương trình này cho bạn bè. Chương trình mang lại trải nghiệm thực hành với **dịch vụ AWS thực tế** và **công nghệ AI hiện đại (RAG, LLM)** — những chủ đề rất giá trị trên thị trường việc làm hiện nay. Sự kết hợp giữa workshop có hướng dẫn, tự nghiên cứu và phản hồi rõ ràng từ mentor khiến đây là một trong những trải nghiệm thực tập thực tế nhất mà tôi từng có.

---

### Góp ý và kỳ vọng
- **Góp ý cải thiện trải nghiệm thực tập:**  
  - Thêm **sơ đồ kiến trúc tổng thể** với ánh xạ từng bước đến từng phần workshop ngay từ đầu, để thực tập sinh theo dõi vị trí của mình trong bức tranh toàn cảnh.  
  - Cung cấp **gợi ý xử lý sự cố** hoặc mục FAQ trong mỗi lab cho các lỗi phổ biến (ví dụ: lỗi quyền S3 bucket, timeout API Gateway).  
  - Tổ chức **buổi chia sẻ kiến thức ngắn hàng tuần** nơi thực tập sinh trình bày những gì đã học để tăng khả năng ghi nhớ.

- **Bạn có muốn tiếp tục tham gia chương trình trong tương lai không?**  
  Có, tôi rất muốn tiếp tục hoặc tham gia phiên bản nâng cao — ví dụ: mở rộng hệ thống RAG với các kỹ thuật tiên tiến hơn như reranking, hybrid search với OpenSearch, hoặc RAG đa phương thức (multi-modal).

- **Ý kiến khác (chia sẻ tự do):**  
  Nhìn chung, đây là một chương trình xuất sắc. Nó tạo cầu nối hoàn hảo giữa kiến thức học thuật và kỹ thuật đám mây thực tế. Tôi đặc biệt trân trọng sự tự do khám phá và tự debug với sự hỗ trợ của mentor — đó là cách tôi học được nhiều nhất. Cảm ơn tất cả thành viên FCAJ và mentor của tôi vì trải nghiệm quý giá này!
