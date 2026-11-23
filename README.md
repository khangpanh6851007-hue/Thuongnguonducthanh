# THƯỢNG NGƯƠN THÁNH ĐỨC – ULTRA SUPREME 2027

Website tĩnh HTML/CSS/JavaScript, giao diện tiếng Việt, thiết kế tím huyền bí kết hợp ánh sáng vàng và xanh thiên giới.

## Tính năng chính

- Thư viện nội dung tham khảo, đọc thành tiếng bằng Text-to-Speech của trình duyệt.
- Lịch tu tập 365 ngày và các bộ đếm thực hành.
- Đại Nguyện, nhật ký công đức, hồi hướng và nhật ký cảm xúc.
- Vườn công đức, ghi nhận hoạt động thiện nguyện và ghi chú nhóm tu học.
- Đồng hồ tĩnh tâm, bài tập thở và thư giãn cơ thể.
- Kệ sách cá nhân, bộ sưu tập chủ đề, lời chúc an lành.
- Thử thách 7 ngày / 21 ngày, câu hỏi tự quán và ghi âm suy ngẫm.
- Trợ lý Phật học ngoại tuyến theo bộ nội dung tham khảo có sẵn.
- Sao lưu / nhập dữ liệu JSON, báo cáo và in thời khóa.

## Cấu trúc dự án

```text
.
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

## Chạy thử trên máy

1. Tải hoặc clone repository.
2. Mở `index.html` bằng trình duyệt hiện đại.
3. Để kiểm tra đầy đủ quyền ghi âm, nên chạy qua localhost hoặc HTTPS.

Website không cần bước build và không cần cài package.

## Đưa lên GitHub Pages

1. Tạo một repository GitHub mới.
2. Đưa `index.html`, `README.md` và thư mục `.github/workflows/` lên nhánh `main`.
3. Vào **Settings → Pages**.
4. Trong **Build and deployment**, chọn **Source: GitHub Actions**.
5. Push commit lên nhánh `main`, hoặc chạy thủ công workflow **Deploy to GitHub Pages** trong tab **Actions**.
6. Sau khi workflow thành công, mở địa chỉ Pages được hiển thị trong **Settings → Pages**.

Workflow nằm tại `.github/workflows/deploy.yml`. Nó xuất bản nội dung trong thư mục gốc repository.

## Lưu ý về dữ liệu và tính năng trực tuyến

- Dữ liệu cá nhân hiện được lưu trong `localStorage` của trình duyệt và thiết bị đang sử dụng. Xóa dữ liệu trình duyệt có thể làm mất dữ liệu; hãy xuất JSON để sao lưu.
- Ghi âm dùng microphone của trình duyệt và thường cần quyền truy cập cùng HTTPS hoặc localhost.
- Đọc thành tiếng dùng Speech Synthesis có sẵn trên thiết bị; giọng đọc phụ thuộc hệ điều hành/trình duyệt.
- Trợ lý Phật học hiện là trợ lý tham khảo ngoại tuyến, chưa kết nối mô hình AI trực tuyến.
- Tài khoản thành viên, đồng bộ đám mây, quản lý đạo tràng nhiều người và dữ liệu dùng chung cần backend, xác thực và cơ sở dữ liệu riêng.
- Khóa PIN trong giao diện không thay thế mã hóa dữ liệu. Không lưu thông tin bí mật hoặc nhạy cảm trong website hiện tại.
- Nội dung kinh/pháp thoại trong bản mẫu là nội dung giới thiệu/chiêm nghiệm; cần bổ sung nguồn kinh sách, bản dịch và thông tin bản quyền rõ ràng khi mở rộng thư viện.

## Cập nhật website

Chỉnh sửa `index.html`, commit và push lên `main`. GitHub Actions sẽ tự động triển khai lại.

## Giấy phép

Chưa chỉ định giấy phép phân phối. Nếu muốn người khác sử dụng hoặc sửa đổi mã nguồn, hãy bổ sung file `LICENSE` phù hợp.
