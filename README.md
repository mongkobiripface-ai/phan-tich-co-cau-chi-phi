<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
    🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>
<h2 align="center">
    Phân tích cơ cấu chi phí và đề xuất tối ưu hóa giá thành sản phẩm
</h2>
<div align="center">
    <p align="center">
        <img alt="AIoTLab Logo" width="170" src="https://github.com/user-attachments/assets/711a2cd8-7eb4-4dae-9d90-12c0a0a208a2" />
        <img alt="AIoTLab Logo" width="180" src="https://github.com/user-attachments/assets/dc2ef2b8-9a70-4cfa-9b4b-f6c2f25f1660" />
        <img alt="DaiNam University Logo" width="200" src="https://github.com/user-attachments/assets/77fe0fd1-2e55-4032-be3c-b1a705a1b574" />
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>
📖 1. Giới thiệu hệ thống

Hệ thống Phân tích cơ cấu chi phí và đề xuất tối ưu hóa giá thành sản phẩm giúp các doanh nghiệp và nhà quản lý:

Hiểu rõ cơ cấu chi phí sản xuất

Phát hiện chi phí bất hợp lý

Tối ưu giá thành sản phẩm để tăng lợi nhuận

🔹 Thành phần hệ thống

Backend: Xử lý dữ liệu chi phí, tính toán tỷ trọng, vẽ biểu đồ, đề xuất phương án tối ưu.

Frontend: Giao diện Streamlit/HTML/CSS/JS, cho phép:

Upload dữ liệu chi phí

Xem bảng cơ cấu chi phí

Quan sát biểu đồ trực quan

Nhận đề xuất tối ưu

🎯 Mục tiêu: Hỗ trợ phân tích chi phí, tối ưu hóa giá thành, phục vụ nghiên cứu, doanh nghiệp nhỏ hoặc đồ án thực hành.

🔧 2. Công nghệ sử dụng
🧠 Ngôn ngữ & Nền tảng

Python 3.10+

Jupyter Notebook / Streamlit

Excel / CSV làm nguồn dữ liệu

🧩 Thư viện Python
Nhóm chức năng	Thư viện	Mô tả
Xử lý dữ liệu	pandas, numpy	Đọc, tổng hợp, tính toán chi phí
Trực quan hóa	matplotlib, seaborn, plotly	Biểu đồ tròn, cột, Pareto
Phân tích tối ưu	scikit-learn, statsmodels (tùy chọn)	Mô hình dự báo chi phí, hồi quy
Giao diện	streamlit / dash	Hiển thị dữ liệu và biểu đồ trực quan
Báo cáo	openpyxl, fpdf (tùy chọn)	Xuất Excel/PDF
⚙️ Công cụ hỗ trợ

VS Code / PyCharm

Git & GitHub

Excel để kiểm chứng dữ liệu

🖼 3. Hình ảnh minh họa chức năng
### 🖼️ Hình 1 – Giao diện mục tiêu và quy trình phân tích chi phí
**Mô tả:** Giao diện giới thiệu **mục tiêu và quy trình thực hiện** của dự án phân tích cơ cấu chi phí, giúp người dùng nắm rõ phạm vi và phương pháp tiến hành.

<img width="1874" height="927" alt="image" src="https://github.com/user-attachments/assets/dfa5bd77-e30f-4c1c-870a-2b8a9424e897" />


### 🖼️ Hình 2 – Dashboard kết nối Power BI
**Mô tả:** Màn hình hiển thị **kết nối Power BI** dùng để trực quan hóa và xử lý dữ liệu phục vụ quá trình phân tích chi phí chi tiết.

<img width="1859" height="923" alt="image" src="https://github.com/user-attachments/assets/65f9a480-f2fe-4d2d-92d9-b24c4c710d69" />


### 🖼️ Hình 3 – Biểu đồ cơ cấu chi phí sản phẩm
**Mô tả:** Biểu đồ tròn thể hiện **tỷ lệ phân bổ các loại chi phí** trong tổng giá thành sản phẩm, giúp xác định yếu tố chi phí chiếm tỷ trọng lớn nhất.

<img width="1859" height="919" alt="image" src="https://github.com/user-attachments/assets/2a636323-b498-48b7-b142-766b7571741b" />


### 🖼️ Hình 4 – Kết quả và nhận xét sau phân tích
**Mô tả:** Giao diện **tổng hợp kết quả và nhận xét** cuối cùng, đưa ra đánh giá và đề xuất nhằm **tối ưu hóa chi phí sản xuất**.

<img width="1873" height="930" alt="image" src="https://github.com/user-attachments/assets/72c5c8ee-8182-48a6-883a-f205fbda2308" />
	
	



📝 4. Hướng dẫn cài đặt và sử dụng
1️⃣ Yêu cầu hệ thống

Python 3.8+

Windows, macOS hoặc Linux

Internet để tải thư viện

2️⃣ Cài đặt môi trường
# Bước 2.1: Tạo môi trường ảo
python -m venv env

# Bước 2.2: Kích hoạt môi trường ảo
# Windows
.\env\Scripts\activate
# macOS/Linux
source env/bin/activate

# Bước 2.3: Cài thư viện
pip install -r requirements.txt


💡 Note: requirements.txt chứa các thư viện cơ bản:

pandas
numpy
matplotlib
seaborn
streamlit

3️⃣ Cách chạy chương trình

Jupyter Notebook: mở analysis.ipynb, chạy từng cell.

Streamlit: chạy lệnh sau:

streamlit run app.py


Truy cập http://localhost:8501 trên trình duyệt.

4️⃣ Hướng dẫn sử dụng cơ bản

Nhập dữ liệu: Chuẩn bị file Excel/CSV, upload vào hệ thống.

Xem phân tích: Biểu đồ cơ cấu chi phí, Pareto, cột, tròn.

Đề xuất tối ưu: Hệ thống gợi ý giảm chi phí, tối ưu giá thành.

Xuất báo cáo: Lưu file Excel/PDF để lưu trữ hoặc chia sẻ.

✅ Tip: Dữ liệu phải đầy đủ và chính xác để kết quả phản ánh đúng thực tế.

5️⃣ Lưu ý

Kiểm tra phiên bản Python và các thư viện trước khi chạy.

Hệ thống hoạt động tốt nhất với dữ liệu chi phí đầy đủ, có cấu trúc chuẩn.

Nếu gặp lỗi, đọc log trên console hoặc Streamlit để xác định nguyên nhân.


5.👤Thông tin liên hệ
Họ tên: Nguyễn Trung Hiếu.
Lớp: CNTT 16-01.
Email: mongkobiripface@gmail.com.

© 2025 AIoTLab, Faculty of Information Technology, DaiNam University. All rights reserved.
