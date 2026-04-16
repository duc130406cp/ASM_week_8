# Unsupervised Machine Learning: Clustering & Customer Segmentation

## Thành viên tham gia 
| Họ và Tên | MSSV | Vai trò |
|---|---|---|
| Nguyễn Việt Đức | 24022295 | Code, Phân tích dữ liệu|

## Liên hệ
- Email sinh viên: `24022295@vnu.edu.com`

## Giới thiệu Bài toán 
Trong thực tế, phần lớn dữ liệu doanh nghiệp không được gán nhãn. Việc áp dụng **Machine Learning không giám sát ** giúp khám phá các cấu trúc ẩn, nhóm các đối tượng có đặc tính tương đồng và hỗ trợ ra quyết định chiến lược. Dự án này tập trung nghiên cứu và triển khai các thuật toán phân cụm cơ bản, sau đó ứng dụng vào bài toán **Phân khúc khách hàng ** nhằm phân nhóm khách hàng dựa trên nhân khẩu học, hành vi mua sắm và mức độ tương tác.

## Phương pháp thực hiện
Dự án được chia thành 4 nội dung chính, tương ứng với 4 notebook:
1. **K-Means Clustering:** Thuật toán phân cụm cứng dựa trên khoảng cách Euclidean, sử dụng Elbow Method và Silhouette Score để xác định số cụm `k` tối ưu.
2. **Hierarchical Clustering:** Phân cụm phân cấp (Agglomerative & Divisive), sử dụng ma trận liên kết và Dendrogram để trực quan hóa cấu trúc phân tầng, dễ dàng cắt cụm ở các ngưỡng khác nhau.
3. **Expectation-Maximization Algorithm:** Triển khai Gaussian Mixture Models (GMM) để thực hiện phân cụm mềm (soft clustering), ước lượng xác suất thuộc cụm và theo dõi sự hội tụ qua Log-Likelihood.
4. **Customer Segmentation:** Ứng dụng thực tế kết hợp xử lý dữ liệu, chuẩn hóa (Standard Scaling) và áp dụng các thuật toán trên để phân nhóm khách hàng, từ đó đề xuất chiến lược marketing phù hợp cho từng phân khúc.
