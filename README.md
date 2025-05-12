# dubaothoitietnongnghiep 
Dự án sử dụng dữ liệu thời tiết từ năm **2009 đến 2021** tại Hà Nội để xây dựng mô hình **dự báo các yếu tố khí tượng quan trọng** như:

- Nhiệt độ cao nhất, thấp nhất
- Độ ẩm không khí
- Lượng mưa
- Tốc độ gió

Mục tiêu là **hỗ trợ người nông dân** và các tổ chức nông nghiệp đưa ra quyết định chính xác hơn trong canh tác, phòng chống thiên tai và lên kế hoạch mùa vụ.

---

## 📊 Dữ liệu sử dụng

- **Nguồn**: Tổng hợp từ [Kaggle](https://www.kaggle.com/) và dữ liệu công khai.
- **Thời gian**: Từ ngày `2009-01-01` đến `2021-06-18`.
- **Địa điểm**: Hà Nội, Việt Nam.
- **Định dạng**: CSV (`weather.csv`).

---

## 🔍 Các bước thực hiện

1. **Tiền xử lý dữ liệu**: làm sạch, chuyển đổi định dạng ngày tháng, xử lý thiếu dữ liệu.
2. **Phân tích dữ liệu khám phá (EDA)**: vẽ biểu đồ xu hướng nhiệt độ, độ ẩm, mưa...
3. **Xây dựng mô hình dự báo**:
   - Mô hình học máy: Linear Regression, Decision Tree, Random Forest
   - Mô hình học sâu (tuỳ chọn): LSTM, GRU cho dữ liệu chuỗi thời gian
4. **Đánh giá mô hình**: sử dụng MAE, RMSE để đo độ chính xác.
5. **Triển khai (tuỳ chọn)**: web app đơn giản dùng Flask/Streamlit để dự báo trực tiếp.
