# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v1.2` (`v1.2-b30`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `4c2d6e168a7666ab2ba3d078317b20ff68b0b492eed3e4d268efc3108dcc8a87`
### Gói cài đặt TRỌN BỘ LẦN ĐẦU cho PC mới (kèm sẵn Client Zephira World 1.2.0):
- **File `.RAR` trọn bộ:** [`ZephiraClientAuto_v1.2_Full_CaiLanDau.rar`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/download/v1.2-b30/ZephiraClientAuto_v1.2_Full_CaiLanDau.rar) (121.8 MB — 127683937 bytes)
- **SHA-256 (RAR):** `05fe09af2f3c53d0c0825046e0b66b2174c9e4fa49a8ca098b5ae1d6eff9b531`
- *Chỉ cần giải nén và chạy `ZephiraClientAuto_Setup_1Click.exe` bên trong, tự cài cả Client game lẫn Auto.*
- **Ghi chú:** v1.2 (Build 30): Tối ưu Chế độ Ẩn chạy lâu dài (mặc định Eco 15 FPS, dải cấu hình 10-15 FPS, nâng toàn bộ ngưỡng khôi phục FPS > 15, keep-alive CDP đơn luồng 45s dùng đồng hồ đơn điệu, reset focus/lifecycle trên phiên CDP mới, thăm dò native RAF thụ động & tự đánh thức cửa sổ bất đồng bộ chống race hiện tab tối đa 3 lần/10 phút).