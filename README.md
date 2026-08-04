# 🌟 Thượng Ngươn Thánh Đức - Website Tâm Linh & Kỷ Nguyên Mới

Chào mừng bạn đến với mã nguồn của dự án website **"Thượng Ngươn Thánh Đức"**. Đây là một ứng dụng web tĩnh mang đậm màu sắc tâm linh, được thiết kế với giao diện **Full HD Ultra** hiện đại, huyền ảo, tối ưu hóa cho trải nghiệm mượt mà trên cả trình duyệt máy tính lẫn các ứng dụng soạn thảo mã nguồn di động như **Acode** hoặc **Trebedit**.

---

## ✨ Tính Năng Nổi Bật

* **Giao diện Huyền ảo (Full HD Ultra):** Sử dụng tông màu hoàng đạo (vàng kim, ngọc bích, tím sẫm) kết hợp hiệu ứng kính mờ (`backdrop-filter`) và font chữ tinh tế (`Cinzel` & `Montserrat`).
* **Mô Tả Cảnh Thượng Ngươn:** Cung cấp góc nhìn chi tiết về môi trường thiên nhiên, xã hội đại đồng và đời sống tâm linh trong kỷ nguyên hoàng kim.
* **Tiêu Chuẩn Vào Thượng Ngươn:** Hướng dẫn những phẩm chất, đạo đức và cách tu dưỡng cần thiết để mỗi cá nhân chuyển hóa nghiệp lực.
* **Thời Gian Đến Thượng Ngươn:** Giải thích rõ chu kỳ vũ trụ ứng với sự thức tỉnh tâm thức của nhân loại.
* **Phật Di Lặc Giáng Thế Độ Nhân:** Nút thông tin đặc biệt lý giải ngã rẽ khi Đức Phật Di Lặc giáng thế:
  * Nếu đi tu ➔ Trở thành **Phật Vạn Thế**.
  * Nếu không đi tu ➔ Trở thành **Thánh Đức Chuyển Luân Thánh Vương**.
* **Gieo Quẻ / Rút Thẻ Thánh Đức Hằng Ngày:** Tính năng tương tác tâm linh giúp người dùng nhận thông điệp, lời khuyên phước báu ngẫu nhiên mỗi ngày.

---

## 📱 Hướng Dẫn Cài Đặt & Sử Dụng (Acode / Trebedit)

Bạn có thể chạy trực tiếp trang web này trên điện thoại Android/iOS thông qua các ứng dụng lập trình web như **Acode** hoặc **Trebedit**:

1. Tải và mở ứng dụng **Acode** hoặc **Trebedit** trên điện thoại.
2. Tạo một tệp mới hoàn toàn và lưu với tên: `index.html`.
3. Sao chép toàn bộ mã nguồn HTML/CSS/JS (được tích hợp chung trong tệp phía dưới) và dán vào tệp `index.html`.
4. Lưu lại tệp và chọn tính năng **Preview** (Xem trước) để trải nghiệm giao diện ngay lập tức mà không cần cài đặt thêm máy chủ (Server) phức tạp.

---

## 🛠️ Mã Nguồn Hoàn Chỉnh (`index.html`)

```html
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thượng Ngươn Thánh Đức - Kỷ Nguyên Tâm Linh</title>
    <!-- Google Fonts -->
    <link href="[https://fonts.googleapis.com/css2?family=Cinzel:wght@600;800&family=Montserrat:wght@400;600;700&display=swap](https://fonts.googleapis.com/css2?family=Cinzel:wght@600;800&family=Montserrat:wght@400;600;700&display=swap)" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background: radial-gradient(circle at center, #1b0c2e 0%, #080310 100%);
            color: #f3e5ab;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow-x: hidden;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 600px;
            background: rgba(20, 10, 35, 0.85);
            border: 2px solid #d4af37;
            border-radius: 20px;
            box-shadow: 0 0 30px rgba(212, 175, 55, 0.4), inset 0 0 15px rgba(212, 175, 55, 0.2);
            padding: 30px 20px;
            text-align: center;
            backdrop-filter: blur(10px);
        }

        /* Header / Tiêu đề */
        .header h1 {
            font-family: 'Cinzel', serif;
            font-size: 1.8rem;
            color: #ffd700;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.6);
            letter-spacing: 1px;
        }

        .header p {
            
