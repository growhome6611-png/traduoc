# Ứng Dụng Tra Cứu Trà Dược Bảo Vệ Sức Khỏe & Phòng Chữa Bệnh (PWA)

Ứng dụng web tiến bộ (Progressive Web App) được xây dựng từ toàn bộ dữ liệu cuốn sách **Trà Dược Bảo Vệ Sức Khỏe và Phòng Chữa Bệnh** (Tác giả: Hữu Ninh – NXB Y Học, 2005), hỗ trợ cài đặt trực tiếp lên điện thoại (iOS/Android) và tra cứu **100% không cần mạng (Offline)**.

## Cấu trúc thư mục
- `index.html`: Toàn bộ giao diện, bộ máy tìm kiếm tiếng Việt không dấu/có dấu và cơ sở dữ liệu 74 nhóm bệnh (480 mục trà dược & phần lý luận dưỡng sinh).
- `manifest.json`: Cấu hình PWA để cài đặt ra màn hình chính điện thoại như ứng dụng độc lập.
- `sw.js`: Service Worker lưu trữ ngoại tuyến toàn bộ dữ liệu.
- `icon.svg`: Biểu tượng ứng dụng.
- `vercel.json`: Cấu hình header chuẩn cho Vercel.

## Cách đưa lên Vercel nhanh nhất (Không cần cài dòng lệnh)
1. Truy cập [vercel.com](https://vercel.com) và đăng nhập.
2. Tạo dự án mới (**Add New → Project**) hoặc kéo thả trực tiếp thư mục `tra-duoc-pwa` (sau khi giải nén) vào giao diện triển khai của Vercel (hoặc đẩy thư mục lên GitHub rồi kết nối với Vercel).
3. Nhấn **Deploy** — sau khoảng 10 giây bạn sẽ nhận được đường link `https://...vercel.app`.

## Cách cài lên điện thoại
- **iPhone / iPad (Safari):** Mở link Vercel → nhấn nút **Chia sẻ (Share)** → chọn **Thêm vào Màn hình chính (Add to Home Screen)**.
- **Android (Chrome):** Mở link Vercel → nhấn menu **⋮** → chọn **Cài đặt ứng dụng (Install App)**.
