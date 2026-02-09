# 🚲 MinhLuaStudio Script - Bike Of Hell (V9)

> **Phiên bản:** V9 (Final Fix)  
> **Tác giả:** MinhLuaStudio  
> **Game hỗ trợ:** Bike Of Hell & Các game Obby xe đạp khác  
> **Trạng thái:** ✅ Hoạt động (Undetected)

---

## 📖 Giới thiệu
Đây là Script hỗ trợ leo rank chuyên dụng cho tựa game **Bike Of Hell** trên Roblox. Script được thiết kế bởi **MinhLuaStudio** với thuật toán vật lý mới, giúp người chơi thực hiện các cú nhảy xa (Long Jump) và nhảy cao ngay cả khi game đã chặn nút Space (Nhảy) mặc định.

Đặc biệt, phiên bản V9 đã được cân chỉnh lực đẩy ở mức **250**, giúp những cú bay trở nên "đầm" hơn, dễ kiểm soát và không bị văng quá xa khỏi map.

## ✨ Tính năng nổi bật (Features)

* **🎨 Giao diện RGB Chroma:** Menu được thiết kế hiện đại với viền và chữ đổi màu cầu vồng (Rainbow Loop) cực ngầu, mang đậm phong cách Gaming.
* **🔓 Bypass System:** Khắc phục hoàn toàn lỗi không nhảy được khi ngồi trên xe. Sử dụng nút bấm ảo trên màn hình để kích hoạt lực đẩy.
* **🚀 Balanced Long Jump (Lực 250):** * Tự động tính toán hướng Camera của người chơi.
    * Đẩy nhân vật bay về phía trước với lực 250 (Vừa phải, chuẩn xác).
    * Kết hợp lực nâng độ cao giúp vượt qua mọi chướng ngại vật.
* **📱 Hỗ trợ đa nền tảng:** Hoạt động tốt trên cả PC và Mobile (Fluxus, Delta, Hydrogen, Arceus X...).
* **🛡️ An toàn:** Code sạch, không gây crash game, có nút **X** để tắt/xóa GUI khi cần thiết.

## 🛠️ Hướng dẫn sử dụng

1. **Bước 1:** Copy toàn bộ đoạn code Script V9.
2. **Bước 2:** Vào game **Bike Of Hell**.
3. **Bước 3:** Mở Executor của bạn lên và dán code vào -> Nhấn **Execute**.
4. **Bước 4:** Menu **MinhLuaStudio** hiện ra.
    * Bấm nút **Status: OFF** để chuyển sang **ON**.
    * Xoay Camera về hướng bạn muốn bay tới.
    * Bấm nút to **"BAY LÊN NÀO!"** trên màn hình để thực hiện cú nhảy.

## ⚙️ Cấu hình kỹ thuật (Dành cho Dev)

* **Method:** `AssemblyLinearVelocity` (Ghi đè vận tốc vật lý).
* **Vector Calculation:** `LookVector * 250 (Forward) + Vector3(0, 110, 0) (Up)`.
* **GUI Library:** Custom CoreGui/PlayerGui implementation.

---

## ⚠️ Lưu ý
* Script này giúp bạn chơi game dễ hơn, hãy sử dụng văn minh.
* Nếu muốn bay xa hơn hoặc thấp hơn, bạn có thể chỉnh sửa thông số `FORWARD_FORCE` trong code.

---

**Copyright © 2024 MinhLuaStudio. All rights reserved.**
