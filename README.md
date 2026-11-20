# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v1.3` (`v1.3-b40`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `21b1660b4b18a91c4af26472cb92cb533938549f71ecab7163099a47cf987457`
### Gói cài đặt TRỌN BỘ LẦN ĐẦU cho PC mới (kèm sẵn Client Zephira World 1.2.0):
- **File `.RAR` trọn bộ:** [`ZephiraClientAuto_v1.3_Full_CaiLanDau.rar`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/download/v1.3-b40/ZephiraClientAuto_v1.3_Full_CaiLanDau.rar) (121.8 MB — 127684601 bytes)
- **SHA-256 (RAR):** `e1b9e4b2b86690b75140086768c57e952f008558bab568371cc3044b5b2bacd6`
- *Chỉ cần giải nén và chạy `ZephiraClientAuto_Setup_1Click.exe` bên trong, tự cài cả Client game lẫn Auto.*
- **Ghi chú:** v1.3 (Build 40): Vá triệt để lỗi lưu/khôi phục FPS tùy biến trên các đường ẩn/hiện cửa sổ (HideTabWindow, ShowTabWindow, RestoreTabWindowTo800x600, SetWindowHidden, ApplyGlobalSettingsToAppConfigInMemory, GetAuthoritativeUserTargetFps) và đồng bộ hàng đợi FIFO ShowWindowAsync sau xung đánh thức ẩn — kiểm duyệt PASS bởi Claude Opus 5.5 High.