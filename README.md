# 🎵 Initial Test - Lumen Choir 🇻🇳

Ứng dụng web trắc nghiệm trực tuyến dành cho việc khảo sát, sát hạch và nâng cao năng lực Nhạc lý & Phụng vụ dành riêng cho các ca viên thuộc **Lumen Choir**.

🌐 **Địa chỉ trang web chính thức:** [initialtest.lumenchoir.com](https://initialtest.lumenchoir.com)

---

## 📌 Tính Năng Chính
* **Ngân hàng câu hỏi chuẩn hóa:** Tập hợp bộ câu hỏi trích xuất từ tài liệu đào tạo nội bộ của Lumen Choir.
* **Cơ chế đảo đề thông minh (Randomized Test):** Mỗi lượt làm bài, hệ thống sẽ tự động bốc ngẫu nhiên **30 câu hỏi** từ ngân hàng dữ liệu và tự động đảo thứ tự các đáp án (A, B, C, D) để đảm bảo tính khách quan.
* **Phản hồi tức thì (Instant Feedback):** Hiển thị ngay đáp án đúng/sai kèm theo phần **Giải thích từ Hội đồng Nghệ thuật** ngay sau khi ca viên bấm chọn câu trả lời.
* **Phân loại năng lực tự động:** Đưa ra đánh giá và định hướng học tập/trau dồi dựa trên số điểm đạt được (Xuất sắc - Rất tốt - Đạt - Cần củng cố).
* **Giao diện tối ưu:** Thiết kế trực quan, hiển thị mượt mà trên cả máy tính (Desktop) và điện thoại di động (Mobile).

---

## 📂 Cấu Trúc Dự Án
Dự án được xây dựng theo mô hình **Single Page Application (SPA)** tối giản, chạy hoàn toàn ở Client-side và được deploy trực tiếp qua hệ thống **Netlify**.

* `index.html`: File duy nhất chứa toàn bộ mã nguồn của ứng dụng bao gồm:
  * **HTML5:** Khung cấu trúc giao diện làm bài, màn hình kết quả.
  * **CSS3:** Định dạng giao diện theo hệ màu nhận diện thương hiệu của ca đoàn, sử dụng Flexbox/Grid responsive.
  * **JavaScript (Vanilla JS):** Xử lý logic đảo câu hỏi, chấm điểm, hiển thị giải thích và quản lý trạng thái bài thi.

---

## 📊 Các Hạng Mục Khảo Sát (Categories)
Bộ câu hỏi bao quát trọn vẹn các kỹ năng cần thiết của một ca viên hợp xướng phụng vụ:
1. **Diction (Phát âm & Nhả chữ):** Các quy tắc mở khẩu hình, phát âm Latin Phụng vụ và tiếng Anh.
2. **Note Reading (Đọc nốt):** Kỹ năng đọc cao độ trên khuông nhạc khóa Sol, khóa Fa, hóa biểu và các dấu hóa.
3. **Rhythm & Meter (Nhịp điệu & Tiết tấu):** Đọc trường độ nốt nhạc, dấu lặng, số chỉ nhịp và các thuật ngữ thay đổi tốc độ (Tempo).
4. **Dynamics & Tempo (Sắc thái cường độ & Nhịp độ):** Các thuật ngữ âm nhạc quốc tế (Italian terms) thông dụng.
5. **Ear Training & Sight-reading (Thẩm âm & Xướng âm):** Nhận biết quãng, cấu trúc hợp âm và kỹ năng xử lý bản nhạc mới.
6. **Liturgical Literacy (Kiến thức Phụng vụ):** Vai trò của Thánh nhạc, vị trí các bài hát và tinh thần Phụng vụ theo hướng dẫn của Giáo hội.

---

## 🛠️ Hướng Dẫn Cập Nhật Dữ Liệu Câu Hỏi
Khi Hội đồng Nghệ thuật có nhu cầu chỉnh sửa, thêm hoặc bớt câu hỏi, anh/chị chỉnh sửa trực tiếp trong file `index.html
