# UniClass Internal App Framework (Base Template)

Đây là một Base Project (dự án gốc) được thiết kế đặc biệt để hoạt động cùng với trợ lý AI (như Antigravity, GitHub Copilot, Cursor, v.v.). 

Mục tiêu của dự án này là giúp các nhân sự **non-tech** có thể dễ dàng khởi tạo, xây dựng và triển khai một ứng dụng web nội bộ hoàn chỉnh chỉ bằng cách giao tiếp với AI, với Database là **Google Sheets** và frontend là **HTML/CSS/JS thuần**.

## 🚀 Cách sử dụng

1. **Clone/Copy** thư mục dự án này ra thành một thư mục mới cho ứng dụng của bạn (VD: `my-internal-tool`).
2. Mở thư mục mới bằng một IDE có tích hợp Agentic AI (Khuyên dùng **Antigravity**).
3. Mở khung chat với AI và gõ câu lệnh sau:
   > *"Hãy đóng vai trò là một chuyên gia hướng dẫn tạo app. Đọc kỹ file `AI_WORKFLOW_GUIDE.md` và bắt đầu dẫn dắt tôi chạy workflow tạo app."*
4. Làm theo từng bước mà AI hướng dẫn bạn. Cứ mỗi khi xong một bước, hãy báo cho AI để đi tiếp.

## 📁 Cấu trúc thư mục

- `AI_WORKFLOW_GUIDE.md`: **LINH HỒN CỦA PROJECT** - Chứa Prompt/Luồng nghiệp vụ siêu chi tiết dành riêng cho AI.
- `templates/`: Chứa các mẫu (template) tài liệu (`project-info.md`, `app-functionality.md`) và file code mẫu (`Code.gs`) để AI sử dụng trong quá trình tạo app.
- `index.html`, `style.css`, `script.js`: Mã nguồn Frontend gốc (Boilerplate) đã được thiết lập sẵn khung cơ bản.

## 🛠️ Công nghệ sử dụng
- **Frontend**: HTML5, CSS3, Vanilla JavaScript.
- **Backend/API**: Google Apps Script (Trực tiếp tương tác với Google Sheets).
- **Database**: Google Sheets.
- **Hosting**: GitHub Pages (Miễn phí, dễ cấu hình).

Chúc bạn tạo ra được những ứng dụng nội bộ tuyệt vời!
