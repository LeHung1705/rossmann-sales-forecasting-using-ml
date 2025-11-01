# Đồ án PTDLKD:	Sales Forecasting Using Machine Learning Algorithm in the Retail Sector
## Dataset: https://www.kaggle.com/c/rossmann-store-sales

- Phân tích chuỗi thời gian đơn biến, đa biến
- Kiểm tra tính dừng của dataset, chuỗi không dừng thì biến đổi thành chuỗi dừng (để dùng được ARIMA, SARIMAX)
- Lúc thuyết trình nói được các thông số khi cài đặt mô hình

---

## Model:
- ARIMA (p, d, q)
p: sử dụng PACF để xác định
d: số lần sai phần đến khi có chuỗi dừng
q: sử dụng ACF
- Linear Regression
- FB Prophet
- XGBoost
- LightGBM
- CatBoost
- SARIMAX

---

## Format for paper
Title of paper
- List of Member
- Abstract 
	- Nói về tình trạng hiện nay
	- Trong bài báo sẽ giải quyết các vấn đề gì
	- Sử dụng các model nào
	- Các chỉ số của các model, MAE, MSE, MAPE)
- Keyword
Table of Contents
I. Introduction
II. Related Work (Các bài báo trước đây đã ra tính toán về dataset này)
III. Method (Nếu chưa đủ 5 model thì phải kiếm thêm, nếu là model mới nằm ngoài chương trình học thì phải giới thiệu về pp đó)
	A. Data Overview
		- Sẽ gồm phần visualize Data, EDA và Data Preprocessing
	B. Model
		- Giới thiệu sơ về model, Usage, Form, mỗi model nên chia ra 3 tập train-test-val khác nhau (65-25-10), (70-20-10), (75-15-10) 
	C. Evaluation Methodology
		- MAE, MSE, MAPE, RMSE: các công thức, cũng như kết quả đánh giá từ mô hình đã chạy
IV. Conclusion
Reference