# Bot Đào Gem — Rise of Kingdoms

App tự đào mỏ gem cho Rise of Kingdoms chạy trên giả lập **LDPlayer 9** (Windows 10/11, 64-bit).

App đã có sẵn mọi thứ cần thiết (Python, thư viện, mô hình nhận gem). Máy mới **không cần cài thêm gì**, chỉ cần LDPlayer 9 và tài khoản game.

## Tải về

👉 **[Trang tải bản mới nhất](https://github.com/VnNo01/BotDaoGem/releases/latest)**

| File | Dùng khi |
|---|---|
| `BotDaoGem-Setup-….exe` | **Nên dùng.** Bấm đúp → Next → Install. Không cần quyền admin, tự tạo biểu tượng ngoài Desktop. Cài bản mới đè bản cũ vẫn giữ tài khoản và vùng đã đặt. |
| `BotDaoGem-….zip` | Bản giải nén chạy luôn: giải nén vào Documents hoặc Desktop (không để trong Program Files), rồi mở `BotDaoGem.exe`. |

Lần đầu mở, Windows có thể báo *"Windows protected your PC"*: bấm **More info → Run anyway**.

## Cài đặt LDPlayer (mỗi máy ảo)

1. Settings → Advanced: độ phân giải **1280 × 720**, **DPI 240**.
2. Settings → Other settings: **ADB debugging = Open local connection**.
3. Lưu rồi khởi động lại máy ảo, cài Rise of Kingdoms và đăng nhập.
4. Trong game: Cài đặt → Ngôn ngữ → **Tiếng Việt**.

## Dùng

1. Mở các máy ảo LDPlayer, rồi mở **Tự kiểm** (trong Start menu, hoặc `Tu kiem.bat` trong thư mục app). Tất cả các dòng `[OK]` là sẵn sàng; dòng `[CẦN LÀM]` cho biết còn thiếu gì phía LDPlayer.
2. Mở **Bot Đào Gem** → **+ Thêm** tài khoản: đặt tên, chọn máy ảo (bấm **Dò máy** nếu danh sách trống).
3. Đặt vùng luân phiên cho từng tài khoản (nút trên thẻ tài khoản), bật công tắc của tài khoản muốn chạy.
4. Bấm **Kiểm tra** (chỉ xem màn hình, không bấm gì), rồi bấm **▶ Chạy**. Muốn dừng thì bấm **■ Dừng**.

Lưu ý:
- Đừng thu nhỏ cửa sổ LDPlayer (để nằm sau cửa sổ khác thì được).
- Tắt chế độ ngủ của máy khi đang chạy bot.
- Mỗi tài khoản cần khoảng 3 GB RAM.

Hướng dẫn đầy đủ nằm trong file `HUONG_DAN.txt` kèm theo app.

## Gỡ cài

Settings → Apps → **Bot Dao Gem** → Uninstall. Cài đặt tài khoản và nhật ký được giữ lại, để cài lại không phải đặt lại từ đầu.
