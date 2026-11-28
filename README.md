# ZephiraClientAuto Releases (Doc lap voi Chrome `zephirav1`)

Kho phat hanh **chi chua bo cai 1-Click (`.exe`), goi cai lan dau (`.rar`) va manifest (`version.json`)** danh rieng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyet doi **khong chua ma nguon**.
- Tuyet doi **tach biet 100%** khoi nhanh phat hanh trinh duyet Chrome (`productId: "zephira-client-auto"`).

## Phien ban hien tai (`stable`): `v4.0.8-b320`
- **Tai truc tiep 1-Click Setup (1.83 MB):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `1d5dbeab221b9ef4528c647cf4e283fa08ad8497f0a434851bf629b6b9accc4c`
- **Ghi chu:** v4.0.8 (Build 320): Hop nhat 3 cum va triet de tren nen sach v4.0.7: (1) FieldTrash nghi man ca tab An SW_HIDE & Khong An Visible (tach pt-resting, giu toast, TryExitGameRestModeTrustedAsync + hit-test tai 4 diem vao, WM_POWERBROADCAST Display-Off + danh thuc mem khong den/chop man, chan nhip quet 90-150s, OPEN_AUCTION_FAIL lan 1 45s); (2) Chong chua day hom van ve & bay di bay lai (chan ESCAPE_TO_FARM khi ItemDus>=265 hoac tui>=60 con do ban kem tran 3 chu ky/10 phut, va T02 Navisko troi sang, siet R5_EXCESS_CORES); (3) Chong trung dang nhap 'may chu khac / another server' tren JS+C#, dong WebSocket + cho settle 1.5s truoc moi reload, va Watchdog Guard 2 + WebGL 15s grace + SilentWS 45s.