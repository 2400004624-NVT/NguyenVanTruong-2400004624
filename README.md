markdown
   # DỰ ÁN: TỪ DỮ LIỆU ĐẾN PHÂN TÍCH VỚI PYTHON
   - **Họ và tên:** [NGUYEN VAN TRUONG]
   - **MSSV:** [2400004624]
   - **Lớp:** [24DTH2B]

   ## Trả lời câu hỏi thu hoạch
   - **Câu 1:** Ký tự tiếng Anh nằm trong bảng mã ASCII cơ bản nên chỉ tốn 1 byte/ký tự. Trong khi đó, các ký tự tiếng Việt có dấu thuộc tập mã Unicode (UTF-8) mở rộng nên cần 2 đến 3 bytes để mã hóa.
   - **Câu 2:** So sánh: CSV có cấu trúc bảng phẳng (2D), dung lượng nhẹ và dễ mở bằng Excel. JSON có cấu trúc dạng cây (Object/Array), hỗ trợ lưu trữ dữ liệu phức tạp.Dữ liệu lồng nhau: Nên dùng JSON vì nó hỗ trợ tự nhiên cấu trúc phân cấp đa tầng mà không cần trải phẳng (flatten) dữ liệu.
   - **Câu 3:** Hiện tượng: Màn hình hiển thị chuỗi ký tự rác, ô vuông và ký hiệu vô nghĩa. 
   Nguyên nhân: Notepad là trình biên tập văn bản (text editor). Khi bắt ép nó đọc dữ liệu nhị phân (binary) của file ảnh thành các ký tự chữ viết, kết quả sẽ bị lỗi hiển thị.
   - **Câu 4:** Tách folder: Giữ data/raw/ làm "nguồn sự thật" không thể bị ghi đè hay mất mát, đồng thời giúp quy trình làm sạch dữ liệu ở data/processed/ có thể tái lập (reproducible) bất kỳ lúc nào. 
   Dùng .gitignore: Tránh đẩy dữ liệu quá nặng làm chậm Git repository và ngăn lộ các thông tin riêng tư, dữ liệu nhạy cảm lên mạng.
   - **Câu 5:** Khoảng điểm (Min - Max): Chênh lệch rõ rệt giữa nhóm điểm tiệm cận 0.0 và nhóm đạt điểm tuyệt đối.
   Phân bố (Mean): Điểm trung bình tập trung chủ yếu ở mức Khá (khoảng 2.5 – 3.2 thang 4 hoặc 6.5 – 7.5 thang 10). Phân bố dạng hình chuông tiêu chuẩn với tỷ lệ sinh viên rất giỏi hoặc rất yếu chiếm số ít.