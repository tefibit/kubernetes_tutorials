# kubernetes_tutorials
🔥 1–10: Basic Kubernetes
1. Kubernetes là gì?

👉 Là hệ thống orchestration để quản lý container (deploy, scale, maintain)


Kubernetes (thường được viết tắt là K8s) là một nền tảng mã nguồn mở dùng để quản lý, triển khai và vận hành các ứng dụng dạng container (như Docker) một cách tự động.

🔹 Hiểu đơn giản

Hãy tưởng tượng bạn có nhiều ứng dụng chạy trong các container. Kubernetes giúp bạn:

🚀 Tự động chạy ứng dụng
🔄 Tự động khởi động lại khi lỗi
📦 Phân bổ tài nguyên hợp lý
⚖️ Cân bằng tải (load balancing)
🔧 Cập nhật ứng dụng mà không bị gián đoạn
🔹 Kubernetes dùng để làm gì?
Quản lý hàng trăm / hàng nghìn container
Tự động scale (tăng/giảm số lượng container khi cần)
Đảm bảo ứng dụng luôn hoạt động (high availability)
Triển khai ứng dụng theo mô hình microservices
🔹 Thành phần chính

Một hệ thống Kubernetes thường gồm:

Cluster: toàn bộ hệ thống
Node: máy chủ (có thể là VM hoặc server thật)
Pod: đơn vị nhỏ nhất (chứa container)
Deployment: quản lý việc chạy và cập nhật Pod
Service: giúp các Pod giao tiếp với nhau
🔹 Kubernetes liên quan gì đến Docker?
Docker 👉 tạo container
Kubernetes 👉 quản lý container ở quy mô lớn
🔹 Ví dụ thực tế

Bạn có một website:

Bình thường cần 2 server
Khi nhiều người truy cập → cần 10 server

👉 Kubernetes sẽ tự động tăng số container lên 10
👉 Khi ít người → giảm lại → tiết kiệm tài nguyên

🔹 Ai phát triển?

Kubernetes ban đầu được phát triển bởi Google, sau đó được quản lý bởi Cloud Native Computing Foundation.

🔹 Tóm lại

👉 Kubernetes = "hệ điều hành cho container"
👉 Giúp bạn chạy ứng dụng ổn định, linh hoạt và tự động