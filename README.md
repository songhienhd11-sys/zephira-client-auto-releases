# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v1.7` (`v1.7-b80`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `b04b991bdf3f7614a17cef33eb4c58623dd56a9dd63ac544c3e431e0069d76ec`
- **Ghi chú:** v1.7 (Build 80): Pha 2 Toi uu Kien truc Da Tab 24/7 - Chuyen PtmLocalProxyBridge sang 100% True Async (bo thread accept chan, tai su dung buffer 32KB cho ca header, huy tunnel ngay khi Stop), tach orchestrator.RunTick() khoi UI thread (Single-Flight Coalescing + Render UI 0-lock), va khoa don luong ProbeAllTabs + giam quet thread Windows khi chuyen cua so.