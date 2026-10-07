# Chia hóa đơn

Công cụ tính tiền tip và chia hóa đơn cho nhiều người. Toàn bộ nằm trong một file `index.html`, không cần cài đặt, không dùng thư viện ngoài, chạy được cả khi không có mạng.

## Cách mở

- Mở trực tiếp file `index.html` bằng trình duyệt (nhấp đúp vào file), hoặc
- Bật GitHub Pages cho repo (Settings → Pages → chọn nhánh chứa `index.html`) để dùng qua đường link.

## Cách dùng

1. **Tổng hóa đơn:** nhập số tiền (VNĐ). Dấu phân cách hàng nghìn tự thêm khi gõ.
2. **Tiền tip:** chọn nhanh 0%, 5%, 10%, 15%, 20%, hoặc gõ số khác vào ô "Khác" (chấp nhận số lẻ, ví dụ `12,5`). Xóa ô "Khác" sẽ quay về 10%.
3. **Làm tròn mỗi người:** không làm tròn, hoặc làm tròn lên 1.000đ / 5.000đ / 10.000đ. Phần chênh lệch so với tổng cần trả hiện ở dòng "Dư ra" (hoặc "Còn thiếu").
4. Chọn cách chia:
   - **Chia đều:** chỉnh số người bằng nút − / + hoặc gõ trực tiếp (1–100). Kết quả hiện số tiền mỗi người trả.
   - **Theo từng người:** nhập tên và tiền món riêng của từng người; bấm "+ Thêm người" để thêm, "×" để xóa. Phần còn lại của hóa đơn (món dùng chung) được chia đều cho mọi người, tip tính theo tỷ lệ phần của mỗi người. Bảng kết quả hiện phần ăn, tip và số tiền phải trả của từng người. Nếu tổng món riêng lớn hơn hóa đơn, trang sẽ cảnh báo.

Nút "Đổi giao diện" ở góc trên chuyển giữa nền sáng và nền tối; lựa chọn được nhớ trên trình duyệt đó.

## Ví dụ

| Tình huống | Kết quả |
|---|---|
| Hóa đơn 1.000.000đ, tip 10%, 3 người, làm tròn lên 1.000đ | Mỗi người 367.000đ, tổng cần trả 1.100.000đ, dư 1.000đ |
| Hóa đơn 500.000đ, tip 10%; A món riêng 100.000đ, B món riêng 200.000đ | A trả 220.000đ, B trả 330.000đ (món chung 200.000đ chia đôi) |
