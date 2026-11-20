# ZephiraClientAuto — `v1.7` (`v1.7 • Build 80`)

- **Product ID:** `zephira-client-auto`
- **Tag Release:** `v1.7-b80`
- **Asset Setup 1-Click (nhẹ cho Auto-Update):** `ZephiraClientAuto_Setup_1Click.exe` ([Tải bản v1.7-b80](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/download/v1.7-b80/ZephiraClientAuto_Setup_1Click.exe))
- **Size Setup:** 1398272 bytes
- **SHA-256 Setup:** `b04b991bdf3f7614a17cef33eb4c58623dd56a9dd63ac544c3e431e0069d76ec`

## Yêu cầu trên PC mới
- **Cách 1 (Khuyên dùng cho PC trắng chưa cài game):** Tải file `.RAR` trọn bộ, giải nén rồi bấm đúp `ZephiraClientAuto_Setup_1Click.exe` -> tự cài trọn bộ `ZephiraClientAuto` + Client game `Zephira World 1.2.0`.
- **Cách 2 (Máy đã có sẵn `Zephira World.exe`):** Chạy trực tiếp `ZephiraClientAuto_Setup_1Click.exe` (1.37 MB).
- Sau lần đầu, mở app sẽ tự kiểm tra & cập nhật bản nhẹ từ `songhienhd11-sys/zephira-client-auto-releases`.

## Nội dung cập nhật
v1.7 (Build 80): Pha 2 Toi uu Kien truc Da Tab 24/7 - Chuyen PtmLocalProxyBridge sang 100% True Async (bo thread accept chan, tai su dung buffer 32KB cho ca header, huy tunnel ngay khi Stop), tach orchestrator.RunTick() khoi UI thread (Single-Flight Coalescing + Render UI 0-lock), va khoa don luong ProbeAllTabs + giam quet thread Windows khi chuyen cua so.