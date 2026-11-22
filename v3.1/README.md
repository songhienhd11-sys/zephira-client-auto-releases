# ZephiraClientAuto — `v3.1` (`v3.1 • Build 220`)

- **Product ID:** `zephira-client-auto`
- **Tag Release:** `v3.1-b220`
- **Asset Setup 1-Click (nhẹ cho Auto-Update):** `ZephiraClientAuto_Setup_1Click.exe` ([Tải bản v3.1-b220](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/download/v3.1-b220/ZephiraClientAuto_Setup_1Click.exe))
- **Size Setup:** 1491456 bytes
- **SHA-256 Setup:** `04913c3bcd53cdfeda1da0f21ecde0d2eb48fa1871d5279a2fbd08cb0a1ce14a`

## Yêu cầu trên PC mới
- **Cách 1 (Khuyên dùng cho PC trắng chưa cài game):** Tải file `.RAR` trọn bộ, giải nén rồi bấm đúp `ZephiraClientAuto_Setup_1Click.exe` -> tự cài trọn bộ `ZephiraClientAuto` + Client game `Zephira World 1.2.0`.
- **Cách 2 (Máy đã có sẵn `Zephira World.exe`):** Chạy trực tiếp `ZephiraClientAuto_Setup_1Click.exe` (1.37 MB).
- Sau lần đầu, mở app sẽ tự kiểm tra & cập nhật bản nhẹ từ `songhienhd11-sys/zephira-client-auto-releases`.

## Nội dung cập nhật
v3.1 (Build 220): Sua triet de loi Tab 1 bi kick 'tai khoan dang nhap o noi khac' va dung thanh khong di farm — khoa LaunchTabBrowserProcess theo TabIndex + MarkTabLaunchPending + giu bootingPid trong CloneProbeWithLiveOverlay + nang cua so boot 25s; bo sung regex 'dang nhap o noi khac / logged in elsewhere' vao 4 bo do JS & giu PiP .msgbox/.uk-ask-box + cooldown dang nhap 5.5s + chan reload khi da vao game; KICK_MODAL/WATCHDOG_RELOAD xoa LastSteadyFarmMap tranh false DeathCircuitOpen, chi pin GoldGather Tab 1 khi sender duoc tich Selected, va khop cooldown PREFLIGHT_CORE_MISSING_SAFE_HOLD 60s.