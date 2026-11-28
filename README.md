# ZephiraClientAuto Releases (Doc lap voi Chrome `zephirav1`)

Kho phat hanh **chi chua bo cai 1-Click (`.exe`), goi cai lan dau (`.rar`) va manifest (`version.json`)** danh rieng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyet doi **khong chua ma nguon**.
- Tuyet doi **tach biet 100%** khoi nhanh phat hanh trinh duyet Chrome (`productId: "zephira-client-auto"`).

## Phien ban hien tai (`stable`): `v4.0.12-b324`
- **Tai truc tiep 1-Click Setup (1.87 MB):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `2a1e4748f4778d1ebf8650bf9d3538f411eb06fac3c86086ded78bc0847d55dd`
- **Ghi chu:** v4.0.12 (Build 324): Sua triet de loi mat ket noi Proxy khi cap nhat ban moi & khi them Proxy moi (strict bridge port bind + retry 8x150ms, 0-WMI warm cache + 2-pass parallel startup bridge, Gate #0 giu bridge tab mo, ThinFleetBrain epoch breaker reset + re-elect leader, HTTP/2 probe + auto reset/reload tab chrome-error khi doi Proxy).