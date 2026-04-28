# 🎲 Random Dice Ultra - Phiên bản Mobile V8.5

**Random Dice Ultra** là một trò chơi thủ thành (Tower Defense) chiến thuật được xây dựng trên nền tảng Web (HTML5/Canvas), tối ưu hóa hoàn hảo cho trải nghiệm trên thiết bị di động. Người chơi phải triệu hồi, nâng cấp và kết hợp các loại xúc xắc để ngăn chặn làn sóng kẻ thù ngày càng mạnh mẽ.

---

## 🌟 Tính năng chính (V8.5)

### ⚔️ Hệ thống 30 Loại Xúc Xắc
Trò chơi sở hữu kho xúc xắc đồ sộ được chia thành nhiều cấp độ:
* **Cơ bản & Khá:** Lửa, Băng, Gió, Sét, Sắt, Độc...
* **VIP Pro (Màu Cam):** `PLASMA VIP` (Laser liên tục), `TITAN VIP` (Sát thương khổng lồ).
* **Siêu Ultra (Màu Đỏ):** `GOD ULTRA` (Nổ lan diện rộng), `HỦY DIỆT` (Trừ % máu Boss).
* **Huyền Thoại:** `CHAOS` và `ETERNAL` với tốc độ bắn nhanh nhất hệ thống.

### 💾 Hệ thống Lưu Game (Save/Load)
* Tự động lưu trạng thái (SP, HP, Wave, Bàn cờ) vào **LocalStorage** sau mỗi đợt Boss.
* Menu khởi động cho phép **Chơi mới** hoặc **Tiếp tục** từ bản lưu trước đó.

### 🛠 Tool GM (Game Master)
* Tích hợp bảng điều khiển bí mật để thử nghiệm và gỡ lỗi.
* **Key kích hoạt:** `********`
* Tính năng: Cộng 5000 SP, Diệt sạch quái, Hồi HP và Nâng cấp giới hạn HP tối đa.

### 💡 Gợi ý Chiến thuật (Hint System)
* Nút triệu hồi sẽ tự động **nhấp nháy (Pulse Effect)** khi bạn có đủ SP và bàn cờ còn chỗ trống.
* Hệ thống tự động ưu tiên mục tiêu (Targeting) là kẻ địch đi xa nhất để bảo vệ HP.

---

## 🎮 Cách chơi

1.  **Triệu hồi:** Nhấn nút **TRIỆU HỒI** (tốn 50 SP) để nhận một xúc xắc ngẫu nhiên.
2.  **Ghép (Merge):** Kéo một viên xúc xắc đè lên viên khác **cùng loại** và **cùng số sao** để nâng cấp lên cấp sao cao hơn (Tối đa 7 sao).
3.  **Mua trực tiếp:** Vào **SHOP** để chọn mua chính xác loại xúc xắc bạn muốn bằng SP tích lũy.
4.  **Phòng thủ:** Mỗi kẻ địch thoát khỏi màn hình sẽ trừ **1 HP**. Nếu HP về 0, trò chơi kết thúc.

---

## 🛠 Cấu trúc Kỹ thuật

* **Language:** JavaScript (ES6+), HTML5 Canvas, CSS3.
* **Game Loop:** Sử dụng `requestAnimationFrame` để đảm bảo tốc độ 60 FPS mượt mà.
* **Data Structure:** Toàn bộ thông số xúc xắc được quản lý tập trung trong mảng `diceData`, dễ dàng tùy chỉnh sát thương (`dmg`) và tốc độ bắn (`spd`).

---

## 📝 Nhật ký cập nhật

* **V8.0:** Thêm Menu chính và hệ thống Lưu/Tải game.
* **V8.3:** Fix lỗi 30 loại xúc xắc không bắn địch.
* **V8.4:** Sửa lỗi đứng yên của xúc xắc `CHAOS` và `ETERNAL`.
* **V8.5:** Cập nhật hiệu ứng gợi ý triệu hồi và tối ưu hóa UI.

---
**Phát triển bởi:** Khangpanh68 (Mobile Developer)

**Dành cho:** Khangpanh68 (Mobile Developer)
