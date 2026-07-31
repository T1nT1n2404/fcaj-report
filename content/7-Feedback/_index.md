---
title: "Sharing and Feedback"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 7. </b> "
includeInReport: false
---


### Overall Evaluation

**1. Working Environment**  
The working environment of the FCAJ program is very friendly, open, and well-organized. All project documents, templates, and instructions are clearly structured and easy to access, which helped me get started quickly without confusion. The FCAJ members are always willing to support me whenever I encounter difficulties, even outside working hours. The program also encourages discussion and knowledge sharing, creating a comfortable atmosphere for me to ask questions and learn from others.

**2. Support from Mentor / Team Admin**  
My mentor provided very detailed and practical guidance throughout the project. Instead of directly giving me the answer, the mentor guided me to analyze problems step by step and encouraged me to research AWS documentation myself — this helped me truly understand how the architecture worked rather than just following instructions. The admin team handled administrative tasks smoothly, provided all necessary AWS resources and access, and created favorable conditions for me to complete the workshop and report on time.

**3. Relevance of Work to Academic Major**  
The project — building an **AWS CloudHop RAG (Retrieval-Augmented Generation) system** — is highly relevant to my academic background in Computer Science and Artificial Intelligence. The full-stack architecture covered many areas I studied at university: cloud computing (S3, EC2, API Gateway), databases (vector storage), AI/ML (embedding models, LLM, RAG pipeline), and security (VPC endpoints, IAM policies). At the same time, it introduced me to real-world cloud engineering practices that are rarely taught in depth at school, such as offline artifact pipelines, VPC endpoint configuration, and cost/security optimization.

**4. Learning & Skill Development Opportunities**  
This internship greatly improved my technical and soft skills. On the technical side, I learned how to design and deploy a production-like RAG system on AWS, including:
- Building the **offline pipeline**: processing documents, chunking, generating embeddings, and storing vectors in Amazon S3.
- Setting up the **online query pipeline**: backend on EC2, RESTful APIs via API Gateway, and a frontend deployed on AWS Amplify.
- Configuring **VPC endpoints and S3 bucket policies** for secure communication between on-premises and AWS services.
- Testing, validating, and evaluating the system's performance, then handling **operations, monitoring, security, and cost management**.

Beyond technical skills, I also practiced project management tools, professional written communication (weekly worklogs, reports), and presenting technical content clearly.

**5. Company Culture & Team Spirit**  
The program culture is very positive and professional. Everyone respects each other's time and ideas, while still maintaining a friendly and supportive atmosphere. When I got stuck on the workshop labs, the team members and mentor actively helped me debug and unblock. This collaborative spirit made me feel like a real member of the team, not just an intern, and motivated me to complete the project with high quality.

**6. Internship Policies / Benefits**  
The program provides the necessary AWS credits and sandbox environment, which allowed me to experiment freely without worrying about costs. The flexible working schedule — with clear weekly milestones in the worklog template — helped me balance my university schedule while still delivering the project in time. The pre-built templates (worklog, report, blogs) were extremely useful for keeping everything consistent and professional.

---

### Additional Questions
- **What did you find most satisfying during your internship?**  
  The most satisfying moment was when the **full RAG system worked end-to-end**: documents were processed offline into vectors, and the online query pipeline successfully retrieved relevant context from Amazon S3 and returned accurate, grounded answers from the LLM. Seeing all the AWS services (S3, EC2, API Gateway, Amplify) connect together exactly as designed was a huge achievement.

- **What do you think the company should improve for future interns?**  
  The program could provide more **pre-recorded video tutorials** for the most complex labs (e.g., VPC endpoint configuration, IAM policies), and perhaps an **architecture walkthrough session** before starting the actual workshop, so interns can visualize the whole system before diving into implementation. More code-level examples for the backend and frontend integrations would also reduce initial confusion.

- **If recommending to a friend, would you suggest they intern here? Why or why not?**  
  Yes, I would definitely recommend this internship to a friend. It offers hands-on experience with **real AWS cloud services** and **modern AI technology (RAG, LLMs)** — topics that are highly valuable in today's job market. The combination of guided workshops, self-paced research, and clear feedback from mentors makes it one of the most practical internship experiences I've had.

---

### Suggestions & Expectations
- **Suggestions to improve the internship experience:**  
  - Add a **high-level architecture diagram** with step-by-step mapping to each workshop section at the beginning, so interns can track where they are in the whole picture.  
  - Provide **troubleshooting hints** or a FAQ section within each lab for common errors (e.g., S3 bucket permission issues, API Gateway timeouts).  
  - Organize a weekly short **knowledge-sharing session** where interns present what they learned, to strengthen learning retention.

- **Would you like to continue this program in the future?**  
  Yes, I would love to continue or join an advanced version of the program — for example, extending the RAG system with more advanced techniques like reranking, hybrid search with OpenSearch, or multi-modal RAG.

- **Any other comments (free sharing):**  
  Overall, this was an excellent program. It gave me the perfect bridge between academic knowledge and real-world cloud engineering. I especially appreciate the freedom to explore and debug on my own with mentor support — that's how I learned the most. Thank you to all the FCAJ members and my mentor for this valuable experience!