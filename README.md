# Vua Pháp Thuật · Desktop

Bản cài desktop (Electron + Ruffle) để chơi Vua Pháp Thuật, mỗi cửa sổ là một phiên game độc lập.

## Tải về

Vào [Releases](../../releases/latest) và chọn file theo máy:

| Máy | File |
|---|---|
| macOS Apple Silicon (M1/M2/M3…) | `VuaPhapThuat-<phiên bản>-mac-arm64.dmg` (hoặc `.zip`) |
| Windows 64-bit | `VuaPhapThuat-<phiên bản>-win-x64.zip` |

`SHA256SUMS.txt` trong mỗi release dùng để kiểm tra file tải về.

## Cài đặt

**macOS:** mở file `.dmg`, kéo app vào Applications. App chưa ký Apple Developer ID nên lần đầu cần **chuột phải → Open → Open**.

**Windows:** giải nén `.zip` ra một thư mục rồi chạy `Vua Phap Thuat.exe`. App chưa ký số nên Windows SmartScreen có thể cảnh báo: bấm **More info → Run anyway**.

## Sử dụng

- Dán link vào game (link loader) và bấm **Mở game**. App không lưu mật khẩu; link chỉ nằm trong phiên đang chạy.
- **Tệp → Cửa sổ mới** (Cmd/Ctrl+N) để chơi thêm tài khoản khác trong cửa sổ riêng.
- Cấu hình Auto được lưu chung cho mọi cửa sổ và giữ lại khi đóng app.

## Giới hạn

- macOS Intel chưa có bản riêng.
- Bản Windows là zip portable, chưa có bộ cài.
