Các bước chạy:

    1. Tải NodeJS (tải bản LTS, cái này cũng sẽ có sẵn NPM)

    2. Mở VSCODE (hay sử dụng CMD cũng được) ở trong thư mục gốc (thư mục có chứa file README.md này)

    3. Gõ vào terminal: npm i

    4. Gõ vào terminal: npm run dev

    5. Ở terminal sẽ có hiện dòng Local: http://localhost:<port>/, copy đường dẫn đó

    6. Mở lệnh CMD và chạy lệnh bên dưới để mở Chrome ở chế độ tắt web security (để tránh lỗi CORS)

    7. Dán đường dẫn đó vào Chrome để đến trang web

Hiện tại, chạy trên browser sẽ bị dính lỗi CORS, nên tải Google Chrome về và chạy như sau:

"C:\Program Files\Google\Chrome\Application\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=%LOCALAPPDATA%\Google\chromeTemp

Lưu ý: cái phần trong ngoặc kép, thay bằng đường dẫn thực sự đến chrome trên máy cá nhân (nếu khác so với trên)
