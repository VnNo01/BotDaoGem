# Bot Đào Gem — Rise of Kingdoms

App tự đào mỏ gem cho Rise of Kingdoms chạy trên giả lập **LDPlayer 9** (Windows 10/11, 64-bit).

App đã có sẵn mọi thứ cần thiết (Python, thư viện, mô hình nhận gem). Máy mới **không cần cài thêm gì**, chỉ cần LDPlayer 9 và tài khoản game.

## Tải về

👉 **[Trang tải bản mới nhất](https://github.com/VnNo01/BotDaoGem/releases/latest)** — tải file `BotDaoGem-Setup-….exe`.

Bấm đúp file vừa tải → **nhập mã cài** được cấp (chữ HOA, có dấu gạch ngang) → Next → Install. Không cần quyền admin, tự tạo biểu tượng ngoài Desktop. Cài bản mới đè bản cũ vẫn giữ tài khoản và vùng đã đặt.

- **Cần mã mới cài được.** Mỗi lần chạy bộ cài đều hỏi mã; không có mã thì không cài và không giải nén được.
- **Dùng thử 5 ngày.** Mã cài cho dùng thử 5 ngày, tính từ lần đầu mở app trên máy. Hết 5 ngày app tự khóa và hỏi **mã vĩnh viễn**; nhập đúng một lần là máy đó dùng mãi, không hỏi lại. Gỡ rồi cài lại không được tính lại 5 ngày.
- Liên hệ người bán để nhận mã cài và mã vĩnh viễn.

Lần đầu chạy, Windows có thể báo *"Windows protected your PC"*: bấm **More info → Run anyway**.

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
