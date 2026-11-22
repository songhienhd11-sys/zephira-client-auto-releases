# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `ver1` (`v3.3-b240`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `898313d3f432e5dbc98e8e17204c19d8b932335e4501a5e2d429ace9c269cdcd`
### Gói cài đặt TRỌN BỘ LẦN ĐẦU cho PC mới (kèm sẵn Client Zephira World 1.2.0):
- **File `.RAR` trọn bộ:** [`ZephiraClientAuto_ver1_Full_CaiLanDau.rar`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/download/v3.3-b240/ZephiraClientAuto_ver1_Full_CaiLanDau.rar) (121.8 MB — 127678269 bytes)
- **SHA-256 (RAR):** `aa876b424cc3e41b2d732f88829bee692bdda81e6c35dfd2acfbe7ac5a77623f`
- *Chỉ cần giải nén và chạy `ZephiraClientAuto_Setup_1Click.exe` bên trong, tự cài cả Client game lẫn Auto.*
- **Ghi chú:** v3.3 (Build 240): Field Auction Priority #1 (Auto-Hunt ON + pause stray-panel/AutoParty + hide 'v' bag), 20-tab 1-2 concurrent FIFO queues for Auction/Town-VeChai/Timed-Sell, calm pacing + .auc-change recovery + post-listing verification & bag sort, lag/disconnect/power-loss resilience (.tmp/.bak ledger + fail-closed mine reconciliation + <=25/tab cap), wrong-bag tooltip guard, audit & live Tab 1 hardening.