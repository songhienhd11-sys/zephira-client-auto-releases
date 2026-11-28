# ZephiraClientAuto - `stable` (`v4.0.8 • Build 320`)

- **Product ID:** `zephira-client-auto`
- **Channel:** `stable` (prerelease=`False`)
- **Tag Release:** `v4.0.8-b320`
- **Asset Setup 1-Click (1.83 MB):** `ZephiraClientAuto_Setup_1Click.exe` ([Tai ban v4.0.8-b320](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/download/v4.0.8-b320/ZephiraClientAuto_Setup_1Click.exe))
- **Size Setup:** 1918976 bytes
- **SHA-256 Setup:** `1d5dbeab221b9ef4528c647cf4e283fa08ad8497f0a434851bf629b6b9accc4c`

## Noi dung cap nhat
v4.0.8 (Build 320): Hop nhat 3 cum va triet de tren nen sach v4.0.7: (1) FieldTrash nghi man ca tab An SW_HIDE & Khong An Visible (tach pt-resting, giu toast, TryExitGameRestModeTrustedAsync + hit-test tai 4 diem vao, WM_POWERBROADCAST Display-Off + danh thuc mem khong den/chop man, chan nhip quet 90-150s, OPEN_AUCTION_FAIL lan 1 45s); (2) Chong chua day hom van ve & bay di bay lai (chan ESCAPE_TO_FARM khi ItemDus>=265 hoac tui>=60 con do ban kem tran 3 chu ky/10 phut, va T02 Navisko troi sang, siet R5_EXCESS_CORES); (3) Chong trung dang nhap 'may chu khac / another server' tren JS+C#, dong WebSocket + cho settle 1.5s truoc moi reload, va Watchdog Guard 2 + WebGL 15s grace + SilentWS 45s.