# RocketFlow — Downloads

Kho tải bản cài RocketFlow. Repository này chỉ chứa hướng dẫn và bản phát hành; không chứa mã nguồn phát triển.

## Tải và cài

1. Mở [Releases](https://github.com/hoanghd218/rocketflow-downloads/releases).
2. Tải **rocketflow-1.0.3-protected.zip** trong mục Assets. Không tải các file “Source code” GitHub tự tạo: chúng chỉ chứa README này.
3. Giải nén vào thư mục cố định.
4. Mở `chrome://extensions`, bật **Developer mode**, chọn **Load unpacked** và chọn thư mục có `manifest.json`.
5. Mở RocketFlow, đăng nhập Google. Storyboard và Workflow nằm trong thanh tab.

Đây là bản cài thủ công, chưa phải bản trên Chrome Web Store. Phiên bản này hết hạn sau ngày 31/12/2026 (giờ Việt Nam). Quyền sử dụng theo tài khoản Free/Pro hiện có.

## Thiết lập dành cho chủ ứng dụng

ID cố định của bản chia sẻ: `jggnkaimejhobflkgiggahkpcichiclj`.

Trước khi phát cho người dùng, thêm Authorized redirect URI sau vào OAuth Web client hiện tại, giữ các URI cũ:

```
https://jggnkaimejhobflkgiggahkpcichiclj.chromiumapp.org/
```

Nếu backend đang giới hạn extension origin, thêm `chrome-extension://jggnkaimejhobflkgiggahkpcichiclj` vào danh sách cho phép. Không gửi client secret hoặc khóa riêng cho người cài.

## Về bản đóng gói

JavaScript do dự án viết đã được làm rối; không kèm source map, thư mục test, công cụ build, backend hoặc khóa riêng. Thư viện bên thứ ba và thông báo giấy phép được giữ nguyên. Làm rối mã chỉ tăng độ khó đọc/sao chép, không phải mã hóa bảo mật và không thể bảo đảm chống trích xuất mã chạy trên máy người dùng.

Bản này không dùng để nộp Chrome Web Store vì Store không cho phép obfuscation. [Chính sách code readability](https://developer.chrome.com/docs/webstore/program-policies/code-readability).

Muse là tích hợp thử nghiệm. Kiểm tra tự động dùng trang/dữ liệu giả lập; không phải chứng nhận tạo video AI trực tiếp trên mọi tài khoản.
