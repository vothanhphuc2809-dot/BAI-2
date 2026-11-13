1. Tạo tập tin server.js
Tạo tập tin server.js trong thư mục BAI2 để xây dựng một HTTP Server bằng Node.js.

<img width="288" height="34" alt="image" src="https://github.com/user-attachments/assets/d8686a85-d77d-4e36-a919-e5cfc57988fa" />


3. Nhập đoạn code trong file server.js
Sử dụng require('http') để gọi thư viện HTTP có sẵn của Node.js.
Sử dụng http.createServer() để tạo máy chủ HTTP.
Sử dụng res.writeHead() để thiết lập mã trạng thái 200 và kiểu nội dung HTML.
Sử dụng res.write() để hiển thị thông tin cá nhân trên trình duyệt:
Họ và tên: VÕ THÀNH PHÚC.
Lớp: CNTT18A.
Sử dụng res.end() để kết thúc phản hồi gửi đến trình duyệt.
Sử dụng server.listen(3000) để khởi chạy máy chủ tại cổng 3000.
Sử dụng console.log() để thông báo địa chỉ máy chủ đang chạy.
4. Chạy chương trình
Mở Terminal trong Visual Studio Code, di chuyển vào thư mục BAI2 và nhập lệnh:


bash
<img width="311" height="34" alt="image" src="https://github.com/user-attachments/assets/d60d9c88-680e-4824-8406-8eefc34077d7" />

Sau khi chạy thành công, Terminal hiển thị thông báo:


<img width="381" height="23" alt="image" src="https://github.com/user-attachments/assets/12fe79dc-4dda-460a-8f03-0e7a1ebd3938" />

4. Kết quả
Máy chủ HTTP được khởi chạy thành công trên cổng 3000.
Trình duyệt truy cập được địa chỉ http://localhost:3000.
Trang web hiển thị thông tin:

<img width="235" height="110" alt="image" src="https://github.com/user-attachments/assets/51c81e62-9390-48ea-95c6-8c8558aad932" />

5. Kết luận
Hoàn thành bài thực hành tạo HTTP Server bằng Node.js. Qua bài tập, em hiểu cách tạo máy chủ, xử lý yêu cầu từ trình duyệt và gửi nội dung HTML về cho người dùng thông qua cổng 3000.
