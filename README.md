# Phân tích Mối quan hệ giữa các Yếu tố Thời tiết và Xây dựng Mô hình Dự đoán Mưa

Đồ án này tập trung vào việc phân tích mối quan hệ giữa các yếu tố thời tiết (nhiệt độ, độ ẩm, lượng mưa,...) và xây dựng mô hình dự đoán mưa dựa trên dữ liệu từ Kaggle.

# Mục lục
1. ### *Giới thiệu*

Thời tiết là một yếu tố quan trọng ảnh hưởng đến nhiều khía cạnh của cuộc sống. Việc dự đoán mưa có vai trò quan trọng trong nông nghiệp, giao thông, và nhiều lĩnh vực khác. Đồ án này sử dụng dữ liệu thời tiết từ Kaggle để phân tích mối quan hệ giữa các yếu tố thời tiết và xây dựng mô hình dự đoán mưa, từ đó cung cấp thông tin hữu ích cho người dùng.

2. ### *Dữ liệu*

Tập dữ liệu được sử dụng trong đồ án này được lấy từ Kaggle: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package. Dữ liệu bao gồm các yếu tố thời tiết như nhiệt độ, độ ẩm, lượng mưa, tốc độ gió, và các thông tin khác.

3. ### *Phương pháp*
  - 3.1 Làm sạch dữ liệu: Dữ liệu thô từ Kaggle thường chứa nhiều giá trị thiếu, dữ liệu không nhất quán, và các vấn đề khác. Quá trình làm sạch dữ liệu bao gồm xử lý giá trị thiếu, loại bỏ dữ liệu nhiễu, và chuyển đổi dữ liệu về định dạng phù hợp cho việc phân tích.
  - 3.2 Phân tích đơn biến: Phân tích đơn biến được thực hiện để hiểu rõ hơn về từng yếu tố thời tiết riêng lẻ. Các thống kê mô tả (trung bình, phương sai,...) và biểu đồ (histogram, boxplot,...) được sử dụng để khám phá đặc điểm của từng biến.
  - 3.3 Phân tích đa biến: Phân tích đa biến giúp tìm hiểu mối quan hệ giữa các yếu tố thời tiết khác nhau. Ma trận tương quan, biểu đồ phân tán, và các phương pháp thống kê khác được sử dụng để xác định các mối tương quan và xu hướng giữa các biến.
  - 3.4 Luật kết hợp: Luật kết hợp được sử dụng để tìm ra các tập hợp các yếu tố thời tiết thường xuyên xuất hiện cùng nhau. Ví dụ, chúng ta có thể tìm ra các quy tắc như "Nếu nhiệt độ cao và độ ẩm thấp, thì có khả năng có mưa".
  - 3.5 Xây dựng mô hình: Mô hình học máy (ví dụ: Random Forest, SVM, Logistic Regression) được sử dụng để xây dựng mô hình dự đoán mưa dựa trên các yếu tố thời tiết. Quá trình huấn luyện và đánh giá mô hình được thực hiện để đảm bảo mô hình có độ chính xác cao.

4. ### *Công nghệ sử dụng*
*   Ngôn ngữ lập trình: Python
*   Thư viện: Pandas, NumPy, Matplotlib, Scikit-learn, ...

