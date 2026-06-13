# Happy Birthday GF

Đây là một website tĩnh thuần HTML, CSS và JavaScript, nên có thể deploy miễn phí rất dễ.

## Chạy local
Chỉ cần mở file `index.html` bằng trình duyệt, hoặc dùng VS Code Live Server để xem trước.

## Deploy miễn phí

### Cách 1: GitHub Pages
1. Đẩy toàn bộ code lên GitHub.
2. Vào repo trên GitHub.
3. Mở `Settings` > `Pages`.
4. Ở mục `Build and deployment`, chọn `Deploy from a branch`.
5. Chọn branch `main` và folder `/ (root)`.
6. Nhấn `Save`.

Sau vài phút, GitHub sẽ tạo link public miễn phí cho website.

### Cách 2: Netlify
1. Truy cập Netlify.
2. Chọn `Add new site` > `Deploy manually`.
3. Kéo thả toàn bộ thư mục dự án lên.
4. Netlify sẽ tạo một link public miễn phí ngay.

### Cách 3: Cloudflare Pages
1. Đăng nhập Cloudflare Pages.
2. Kết nối repo GitHub.
3. Chọn branch `main`.
4. Deploy trực tiếp, không cần build command cho project này.

## Lưu ý
- File trang chính phải là `index.html`.
- Không cần backend hay database.
- Nếu sửa nội dung, chỉ cần commit rồi push lại lên GitHub Pages sẽ tự cập nhật.