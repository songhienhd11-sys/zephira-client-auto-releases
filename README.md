# ZephiraClientAuto Releases (Độc lập với Chrome `zephirav1`)

Kho phát hành **chỉ chứa bộ cài 1-Click (`.exe`), gói cài lần đầu (`.rar`) và manifest (`version.json`)** dành riêng cho **ZephiraClientAuto** (Auto Client `Zephira World 1.2.0`).

- Tuyệt đối **không chứa mã nguồn**.
- Tuyệt đối **tách biệt 100%** khỏi nhánh Chrome `zephirav1-releases` (`productId: "zephira-client-auto"`).

## Phiên bản hiện tại: `v3.5.2` (`v3.5.2-b262`)
- **Tải trực tiếp 1-Click Setup (nhẹ — cho Auto-Update / máy đã có client game):** [`ZephiraClientAuto_Setup_1Click.exe`](https://github.com/songhienhd11-sys/zephira-client-auto-releases/releases/latest/download/ZephiraClientAuto_Setup_1Click.exe)
- **SHA-256 (Setup):** `a10a3c5bb82cce104d56fd5d496797aff25a54076b4f2671b5f3abab85dcacd8`
- **Ghi chú:** v3.5.2 (Build 262): Chống lỗi Tài khoản đăng nhập ở nơi khác (chống mở 2 tab trùng, cooldown sau F5, ngắt vòng lặp tự kick 3 lần, chặn nhập trùng tài khoản giữa các tab) + chống lỗi cách xa khi Gom Gold/Auction (kiểm tra khoảng cách <=120u, tiếp cận sát mục tiêu gom Gold, xử lý thông báo quá xa ở Gold Gather & Auction).