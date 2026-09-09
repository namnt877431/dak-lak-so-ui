# Đắk Lắk Số — Trình bày phương án giao diện

Bộ nguyên mẫu giao diện (HTML tĩnh) cho ứng dụng công dân số **Đắk Lắk Số**, kèm trang tổng hợp để truy cập nhanh tất cả tài liệu.

🔗 **Xem trực tuyến:** https://namnt877431.github.io/dak-lak-so-ui/

## Nội dung

| Tài liệu | Tệp | Mô tả |
| --- | --- | --- |
| Trang tổng hợp | [`index.html`](index.html) | Đầu mối truy cập cả 5 tài liệu, có xem trước trực tiếp từng nguyên mẫu |
| Bản trình chiếu | [`DakLakSo-trinhchieu.html`](DakLakSo-trinhchieu.html) | So sánh Lựa chọn 01 và 02 theo từng màn, kèm thuyết minh (~5 MB) |
| Lựa chọn 01 · Glass airy | [`dak-lak-so-lc1-glass.html`](dak-lak-so-lc1-glass.html) | Cấu trúc theo lĩnh vực — hướng thị giác thoáng, bo góc lớn |
| Lựa chọn 01 · Warm paper | [`dak-lak-so-lc1-warm.html`](dak-lak-so-lc1-warm.html) | Cấu trúc theo lĩnh vực — nền giấy ấm, tương phản chắc |
| Lựa chọn 02 · Glass airy | [`dak-lak-so-lc2-glass.html`](dak-lak-so-lc2-glass.html) | Cấu trúc theo nhóm chức năng — hướng thị giác thoáng |
| Lựa chọn 02 · Warm paper | [`dak-lak-so-lc2-warm.html`](dak-lak-so-lc2-warm.html) | Cấu trúc theo nhóm chức năng — nền giấy ấm |

## Hai phương án cấu trúc

- **Lựa chọn 01 — gom theo lĩnh vực quản lý:** Y tế, Giáo dục, Du lịch, Cơ quan nhà nước, An ninh & Trật tự, Truyền thông, Tiện ích. Bám theo ngành, thuận cho quản lý nội dung và mở rộng dịch vụ.
- **Lựa chọn 02 — gom theo việc người dân cần làm:** Tiện ích đời sống, Phản ánh – Kiến nghị, Dịch vụ công, Truyền thông – Tin tức. Người dân tìm theo mục đích sử dụng.

Mỗi phương án có hai hướng thị giác: **Glass airy** (nền sáng ngả peach, bo góc lớn) và **Warm paper** (nền giấy ấm, đường nét chắc).

## Chạy tại máy

Các tệp đều là HTML tĩnh, mở trực tiếp bằng trình duyệt là được. Nếu muốn phần xem trước trong `index.html` hiển thị đúng, nên chạy qua một máy chủ tĩnh:

```bash
python -m http.server 8080
# rồi mở http://localhost:8080
```

## Ghi chú kỹ thuật

- Font **Be Vietnam Pro** (Google Fonts) và bộ biểu tượng **Phosphor Icons** tải từ CDN — cần kết nối mạng.
- Nguyên mẫu thiết kế cho khung điện thoại; trên màn hình rộng sẽ hiển thị trong khung thiết bị giả lập, dưới 520px thì tràn toàn màn hình.
