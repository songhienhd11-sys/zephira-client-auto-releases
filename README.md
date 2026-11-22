# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v3.5` (`v3.5-b260`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `0962d46533b07f1362d3f20ce6712c36e6113a8c65778c90dd0acde1226559dd`
- **Ghi chú:** v3.5 (Build 260): Sua triet de loi kho ket noi lai sau vang game (async CDP modal click, timeout Dang ket noi lai + watchdog WebSocket/STALE_TELEMETRY leo thang restart, bo phat oan RateLimit 70-120s & Invalid session, bom lai mat khau + don PID zombie + reload ket SERVER/CHAR_SELECT), ItemDus Audit an toan, treo rac 20k -> huy vao ItemDus 300 slot, khoa Drain truoc Core Xanh F9 va khong thu vang ngoai bai.