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

Hệ thống Phân tích cơ cấu chi phí và đề xuất tối ưu hóa giá thành sản phẩm được xây dựng nhằm hỗ trợ các doanh nghiệp, nhà quản lý hoặc sinh viên hiểu rõ cấu trúc chi phí sản xuất, từ đó tìm ra giải pháp giảm giá thành và nâng cao hiệu quả kinh tế.

Ứng dụng cho phép người dùng nhập dữ liệu chi phí, phân tích tỷ trọng các yếu tố chi phí, và đề xuất các hướng tối ưu hóa dựa trên kết quả phân tích thống kê và mô hình hóa dữ liệu.

Hệ thống được thiết kế gồm hai phần chính:

🔹 Backend:
Xây dựng bằng Python (sử dụng các thư viện như Pandas, NumPy, Matplotlib), chịu trách nhiệm xử lý dữ liệu chi phí, tính toán tỷ trọng, vẽ biểu đồ, và gợi ý các phương án tối ưu chi phí.
Dữ liệu đầu vào có thể là file Excel, CSV hoặc nhập trực tiếp qua giao diện web.
Các kết quả phân tích được lưu vào hệ thống để dễ dàng so sánh và theo dõi.

🔹 Frontend:
Giao diện đơn giản, thân thiện (phát triển bằng HTML/CSS/JavaScript hoặc Streamlit) cho phép người dùng:

Tải dữ liệu chi phí lên hệ thống

Xem bảng cơ cấu chi phí theo từng yếu tố

Quan sát biểu đồ trực quan (biểu đồ tròn, cột, Pareto, v.v.)

Xem các đề xuất tối ưu hóa tự động được hệ thống sinh ra

🎯 Mục tiêu:
Xây dựng một công cụ trực quan và dễ sử dụng giúp:

Phân tích nhanh cơ cấu chi phí của sản phẩm

Phát hiện các yếu tố chi phí bất hợp lý

Đưa ra đề xuất tối ưu giúp giảm giá thành, tăng lợi nhuận, và nâng cao năng lực cạnh tranh

Ứng dụng cho nghiên cứu học tập, doanh nghiệp nhỏ, hoặc đồ án thực hành kinh tế - công nghệ thông tin

🔧 2. Công nghệ sử dụng

Đề tài được triển khai dựa trên các công nghệ và công cụ phổ biến trong lĩnh vực phân tích dữ liệu (Data Analysis) và trực quan hóa (Data Visualization).
Hệ thống được phát triển với mục tiêu dễ cài đặt, dễ sử dụng và có thể mở rộng cho các bài toán tương tự trong quản trị chi phí.

🧠 Ngôn ngữ & Nền tảng

Python 3.10+ – ngôn ngữ chính dùng cho xử lý, tính toán và trực quan hóa dữ liệu.

Jupyter Notebook / Streamlit – nền tảng phân tích tương tác và hiển thị kết quả trực quan.

Excel / CSV – nguồn dữ liệu đầu vào linh hoạt cho việc nhập chi phí sản xuất.

🧩 Thư viện Python chính
Nhóm chức năng	Thư viện sử dụng	Mô tả
Xử lý dữ liệu	pandas, numpy	Đọc, tổng hợp và tính toán dữ liệu chi phí
Trực quan hóa	matplotlib, seaborn, plotly	Biểu đồ tròn, cột, Pareto, xu hướng chi phí
Phân tích tối ưu	scikit-learn, statsmodels (tùy chọn)	Hỗ trợ mô hình hồi quy hoặc dự báo chi phí
Giao diện người dùng	streamlit hoặc dash	Hiển thị dữ liệu và biểu đồ trên trình duyệt
Báo cáo	openpyxl, fpdf (tùy chọn)	Xuất file Excel, PDF hoặc hình ảnh báo cáo
🗃️ Cấu trúc cơ sở dữ liệu (tùy chọn)

Nếu sử dụng lưu trữ dữ liệu, hệ thống có thể tích hợp:

SQLite / MongoDB: lưu thông tin chi phí, phân tích và kết quả đề xuất tối ưu.

⚙️ Công cụ hỗ trợ phát triển

VS Code / PyCharm – môi trường lập trình chính

Git & GitHub – quản lý mã nguồn và phiên bản

Excel – dùng để nhập và kiểm chứng dữ liệu mẫu

4.1. Yêu cầu hệ thống

Python 3.8 trở lên

Hệ điều hành: Windows, macOS hoặc Linux

Có kết nối Internet để tải các thư viện cần thiết

4.2. Cài đặt môi trường

Tạo môi trường ảo (khuyến nghị):

python -m venv env


Kích hoạt môi trường ảo:

Trên Windows:

.\env\Scripts\activate


Trên macOS/Linux:

source env/bin/activate


Cài đặt các thư viện cần thiết:

pip install -r requirements.txt


Lưu ý:
Bạn cần chuẩn bị file requirements.txt với các thư viện đã dùng như pandas, numpy, matplotlib, seaborn, streamlit,...

Ví dụ nội dung requirements.txt:

pandas
numpy
matplotlib
seaborn
streamlit

4.3. Cách chạy chương trình

Nếu dùng Jupyter Notebook:
Mở file analysis.ipynb và chạy từng cell để thực hiện phân tích và trực quan hóa.

Nếu dùng Streamlit:
Chạy lệnh sau để khởi động ứng dụng web:

streamlit run app.py


Sau đó mở trình duyệt truy cập địa chỉ: http://localhost:8501 để xem giao diện và sử dụng chức năng phân tích chi phí.

4.4. Hướng dẫn sử dụng cơ bản

Nhập dữ liệu
Chuẩn bị file dữ liệu chi phí (Excel/CSV) theo định dạng mẫu. Upload hoặc đọc file trong giao diện.

Xem phân tích
Hệ thống sẽ tính toán cơ cấu chi phí, hiển thị biểu đồ trực quan như biểu đồ tròn, cột, biểu đồ Pareto...

Đề xuất tối ưu
Dựa trên kết quả phân tích, chương trình sẽ gợi ý các biện pháp giảm chi phí hoặc tối ưu giá thành sản phẩm.

Xuất báo cáo
Người dùng có thể tải file báo cáo phân tích ở định dạng Excel hoặc PDF để lưu trữ, chia sẻ.

4.5. Lưu ý

Đảm bảo dữ liệu đầu vào đầy đủ và chính xác để kết quả phân tích phản ánh đúng thực tế.

Nếu gặp lỗi trong quá trình cài đặt hoặc chạy chương trình, vui lòng kiểm tra lại các phiên bản Python và thư viện đã cài.
