# ZephiraClientAuto Releases (Doc lap voi Chrome `zephirav1`)

Kho phat hanh **chi chua bo cai 1-Click (`.exe`), goi cai lan dau (`.rar`) va manifest (`version.json`)** danh rieng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyet doi **khong chua ma nguon**.
- Tuyet doi **tach biet 100%** khoi nhanh phat hanh trinh duyet Chrome (`productId: "zephira-client-auto"`).

## Phien ban hien tai (`stable`): `v4.0-b310`
- **Tai truc tiep 1-Click Setup (1.81 MB):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `1ca7e870b2b51f1208715c45ae8fbebf8192b7588fa6fa53a6a9e5ce62663b2d`
- **Ghi chu:** v4.0 (Build 310): Sua loi man hinh den sau khi An/Hien tab tren Win 11 + RTX 5070 Ti (HAGS) va on dinh UIX: bo Pulse Win32 nhap nhay SWP_SHOWWINDOW/SW_HIDE tren tab an (thay bang WakeHiddenCompositorFrameAsync CDP khong nhap nhay), them --disable-direct-composition cho GPU roi tren Win 11 (build >= 22000), them RedrawWindow + 1px WM_SIZE SwapChain nudge + khoi phuc UIX/WebGL khi Hien tab, va sua treo ScanAllTabWindows/re-entrancy khi An/Hien All Tab.