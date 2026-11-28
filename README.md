# ZephiraClientAuto Releases (Doc lap voi Chrome `zephirav1`)

Kho phat hanh **chi chua bo cai 1-Click (`.exe`), goi cai lan dau (`.rar`) va manifest (`version.json`)** danh rieng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyet doi **khong chua ma nguon**.
- Tuyet doi **tach biet 100%** khoi nhanh phat hanh trinh duyet Chrome (`productId: "zephira-client-auto"`).

## Phien ban hien tai (`stable`): `v4.0.6-b316`
- **Tai truc tiep 1-Click Setup (1.82 MB):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `477081621b1b1cfb59a1e186145d782222daf1594c7d75d718b90f9d64f6b0a8`
- **Ghi chu:** v4.0.6 (Build 316): Va triet de 4 lo hong Stealth / Anti-Detection tren nen on dinh man hinh v4.0.5: chuyen __zca* vao Vault WeakMap/Symbol, dong bo 100% localStorage['pt.device'] <-> cookie pt_did, bu vien Win32 >= 818x642 + jitter xac dinh theo tung tab, va canh bao do [PROXY_IP_OVERLOAD] khi > 3 tab dung chung 1 Host IP Proxy ke ca khac port.