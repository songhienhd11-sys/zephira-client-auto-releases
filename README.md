# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v3.1` (`v3.1-b220`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `04913c3bcd53cdfeda1da0f21ecde0d2eb48fa1871d5279a2fbd08cb0a1ce14a`
- **Ghi chú:** v3.1 (Build 220): Sua triet de loi Tab 1 bi kick 'tai khoan dang nhap o noi khac' va dung thanh khong di farm — khoa LaunchTabBrowserProcess theo TabIndex + MarkTabLaunchPending + giu bootingPid trong CloneProbeWithLiveOverlay + nang cua so boot 25s; bo sung regex 'dang nhap o noi khac / logged in elsewhere' vao 4 bo do JS & giu PiP .msgbox/.uk-ask-box + cooldown dang nhap 5.5s + chan reload khi da vao game; KICK_MODAL/WATCHDOG_RELOAD xoa LastSteadyFarmMap tranh false DeathCircuitOpen, chi pin GoldGather Tab 1 khi sender duoc tich Selected, va khop cooldown PREFLIGHT_CORE_MISSING_SAFE_HOLD 60s.