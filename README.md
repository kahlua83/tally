# VEDC Caster Tally Signal System

Hệ thống tín hiệu Tally không dây chuyên nghiệp dành cho bàn bình luận (Caster Desk) và Đạo diễn (Director) tại các giải đấu Esports và sự kiện trực tiếp của **VEDC**.

## 🌟 Tính năng nổi bật

- **Đồng bộ thời gian thực (Real-time):** Sử dụng Firebase Realtime Database giúp truyền tải tín hiệu gần như không có độ trễ giữa Đạo diễn và các màn hình Caster.
- **Phân vai trò trực quan:** Giao diện truy cập phân tách rõ ràng giữa **Đạo diễn (Director)** và **Màn hình Caster (Screen)** ngay khi vào trang.
- **Quản lý đa sự kiện (Multi-Job):** Hỗ trợ phân loại hệ thống tín hiệu theo từng sự kiện/giải đấu riêng biệt (`job1`, `job2`, `job3` hoặc tùy chỉnh linh hoạt).
- **Giao diện điều khiển chuẩn lưới 2x4:** 8 nút chức năng được sắp xếp cân đối, trực quan:
  - `STREAM ON AIR` (Đang lên sóng)
  - `CASTER LÊN HÌNH` (On Camera)
  - `CASTER XUỐNG HÌNH` (Off Cam)
  - `PREVIEW` (Chuẩn bị / Standby)
  - `CÂU GIỜ` (Hold Time kèm bộ đếm ngược giây tùy chỉnh)
  - `CHUYỂN VỀ MC` (Back to Host / MC)
  - `CASTER OUT` (Bình luận xong)
  - `BREAK` (Nghỉ giải lao)
- **Hệ thống cảnh báo khẩn cấp:** Đạo diễn có thể gửi dòng chữ chú ý/lời nhắc trực tiếp lên màn hình của từng bàn bình luận kèm hiệu ứng nhấp nháy cảnh báo.
- **Chống tắt màn hình tự động (Screen Wake Lock):** Giữ cho màn hình thiết bị máy tính bảng/điện thoại của Caster luôn sáng trong suốt quá trình diễn ra sự kiện.

---

## 🚀 Hướng dẫn sử dụng

1. Truy cập đường dẫn: `https://kahlua83.github.io/tally/`
2. **Chọn vai trò:**
   - Chọn **ĐẠO DIỄN (DIRECTOR)** để mở bảng điều khiển gửi tín hiệu.
   - Chọn **MÀN HÌNH CASTER (SCREEN)** để mở màn hình hiển thị cho các bàn bình luận.
3. **Chọn Job (Sự kiện):** Chọn sẵn job có sẵn hoặc nhập tên job tùy chỉnh cho sự kiện.
4. **Chọn Bàn (Dành riêng cho Caster):** Chọn chính xác **Bàn 1 (Main Caster)** hoặc **Bàn 2 (Analyst Desk)** để đồng bộ tín hiệu tương ứng.

---

## 🛠️ Công nghệ sử dụng

- **Frontend:** HTML5, Tailwind CSS (CDN), JavaScript (ES Modules).
- **Backend / Real-time Database:** Firebase Realtime Database.
- **Hosting:** GitHub Pages.

---

## 📄 Bản quyền và Sở hữu

- **Tác giả / Chủ sở hữu:** `kahlua83`
- **Đơn vị phát triển:** VEDC Studio
- Toàn bộ mã nguồn và thiết kế thuộc quyền sở hữu của tác giả `kahlua83`, được sử dụng phục vụ cho công tác vận hành sản xuất sự kiện và giải đấu.
