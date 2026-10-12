# MathEnglish Pro 🧮

Ứng dụng web học Toán bằng Tiếng Anh (Math English) trực quan, cá nhân hóa và tương tác cao dành cho mọi lứa tuổi từ cơ bản đến nâng cao.

## ✨ Tính năng nổi bật & Cải tiến mới

1. **📚 Kho từ vựng toán học phong phú (60+ từ)**:
   - Phép tính & Số học (Plus, Minus, Times, Divided by, Remainder, Odd/Even, Prime number, Exponent...)
   - Hình học 2D & 3D (Triangle, Square, Rectangle, Circle, Cube, Cylinder, Sphere, Perimeter, Area, Volume...)
   - Phân số, Tỉ số & Đại số (Half, Quarter, Fraction, Numerator, Denominator, Percentage, Variable, Equation...)
   - Đo lường & Đại lượng (Length, Width, Height, Weight, Capacity, Temperature, Millimeter, Kilometer...)
   - Từ khóa giải toán (In total, Remaining/Left, More than, Fewer than, Difference, Product, Quotient, Share equally...)
   - Toán nâng cao & Logic (Probability, Sequence, Mean, Parallel, Perpendicular, Speed, Discount...)
   - Tích hợp tìm kiếm nhanh, lọc theo trạng thái Đã thuộc / Cần học và audio phát âm bản xứ kèm phiên âm IPA & phiên âm bồi.

2. **🎴 Thẻ Flashcard 3D thông minh**:
   - Giao diện thẻ xoay 3D trực quan, âm thanh tương tác sống động.
   - Chế độ lọc linh hoạt: **Tất cả thẻ**, **Chỉ thẻ chưa thuộc**, hoặc **⚠️ Từ hay làm sai cần ôn tập**.
   - Nút đánh dấu đã thuộc đồng bộ tức thì vào `localStorage`.

3. **🔊 Bàn tính đọc câu toán tiếng Anh chuẩn xác**:
   - Hỗ trợ số thập phân (dấu chấm `.`), phím xóa lùi `⌫` (Backspace) và xóa toàn bộ `C`.
   - Phép chia chính xác số thập phân (ví dụ: `7 ÷ 2 = 3.5`), không còn bị làm tròn xuống.
   - Bắt lỗi chia cho 0 an toàn theo chuẩn toán học (`Error: Cannot divide by zero`).
   - Bấm số mới sau phép tính tự động bắt đầu phép tính mới tinh.
   - Phím `C` lập tức xóa sạch câu phát âm và ngắt âm thanh đang đọc.

4. **📖 Kho bài toán đố song ngữ thực tế (15 bài đa cấp độ)**:
   - Phân cấp độ từ Cơ bản (Cộng, trừ, so sánh) đến Nâng cao (Vận tốc, trung bình cộng, xác suất, quy luật).
   - Đầy đủ nút nghe audio đề bài tiếng Anh, dịch nghĩa tiếng Việt, phân tích từ khóa chỉ điểm (Keywords), phép tính và đáp án hoàn chỉnh.

5. **🎮 Thử thách trắc nghiệm Quiz & Theo dõi sai lầm**:
   - Bộ 20 câu hỏi chất lượng cao, mỗi phiên chọn ngẫu nhiên 10 câu để người học luôn được thử thách mới.
   - Tự động phát hiện lỗi sai và đưa khái niệm vào danh sách **Từ cần ôn tập**.
   - Giải thích chi tiết cho từng đáp án đúng/sai, hiệu ứng pháo hoa Confetti và lưu kỷ lục điểm cao nhất.

6. **📊 Hệ thống học tập cá nhân hóa & Lưu trữ lâu dài (P0 & P1)**:
   - **Lưu trữ lâu dài (`localStorage`)**: Ghi nhớ toàn bộ từ đã thuộc, điểm số, chuỗi ngày học ngay cả khi tắt trình duyệt hay tải lại trang.
   - **Mục tiêu học mỗi ngày (Daily Goal)**: Thiết lập mục tiêu 5, 10, 15, 20 từ mỗi ngày kèm thanh đo tiến độ thời gian thực.
   - **Chuỗi ngày học liên tục (Daily Streak)**: Duy trì thói quen học tập mỗi ngày (🔥).
   - **Thống kê độ chính xác**: Theo dõi tỷ lệ % trả lời đúng và tổng số câu đã làm.
   - **Bộ lọc từ yếu / cần ôn**: Giúp người học củng cố nhanh các kiến thức hay nhầm lẫn.

7. **🗣️ Kiểm soát phát âm đa giọng & Tốc độ linh hoạt (TTS Controller)**:
   - Tự động nhận diện danh sách giọng tiếng Anh trên trình duyệt (giọng Mỹ US, giọng Anh UK,...).
   - Điều chỉnh tốc độ đọc phù hợp với từng giai đoạn học: **0.75x (Chậm)**, **1.0x (Chuẩn)**, **1.25x (Nhanh)**.
   - Lưu cấu hình phát âm vào bộ nhớ thiết bị.

---

## 🚀 Hướng dẫn chạy ứng dụng

### Cách 1: Chạy trực tiếp trong trình duyệt
Mở file `index.html` bằng trình duyệt web bất kỳ (Google Chrome, Microsoft Edge, Firefox, Brave...).

### Cách 2: Chạy qua Node.js server
```bash
node server.js
```
Truy cập: [http://localhost:3000](http://localhost:3000)
