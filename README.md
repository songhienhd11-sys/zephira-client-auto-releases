# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v2.4` (`v2.4-b150`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `01dc7e7b62c11b7f6adc009ff0f16f3a070d50837124de9dd3f30f32345c9b1a`
- **Ghi chú:** v2.4 (Build 150): Khoa chuan 30 FPS ngay ca khi an SW_HIDE (Bresenham phase-accumulator + watchdog 16ms + cache pt-settings 1s chan 100 FPS/parse spam), mo rong RAM modelCacheMB 2048 MB (2 GB) & Electron cache toi uu cho moi PC, du UI Video/Audio trong Game + sua triet de dong bo modal .stx qua onmousedown/aria-checked (tat Fog/Shadows/Water dung theo Tab 1).