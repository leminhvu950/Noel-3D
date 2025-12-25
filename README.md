🎄 Merry Christmas – Trải nghiệm cây thông 3D tương tác

Một trải nghiệm Giáng Sinh 3D tương tác được xây dựng bằng Three.js và MediaPipe, cho phép bạn:

Tạo cây thông Noel 3D lung linh

Thêm ảnh cá nhân làm vật trang trí

Điều khiển bằng cử chỉ tay (nếu có webcam)

Tương tác mượt mà với hiệu ứng ánh sáng & bloom cao cấp

📁 Cấu trúc dự án
/
├── index.html      # File chính (mở trực tiếp trên trình duyệt)
└── README.md       # Hướng dẫn sử dụng (file này)


⚠️ Dự án không cần build, không cần cài đặt – chỉ cần trình duyệt hiện đại.

🚀 Cách chạy chương trình
Cách 1: Mở trực tiếp (đơn giản nhất)

Tải file index.html

Mở bằng trình duyệt Chrome / Edge / Brave

Chờ màn hình Loading Holiday Magic hoàn tất

Cách 2: Chạy qua local server (khuyên dùng)

Do trình duyệt có thể chặn một số API khi mở file trực tiếp:

# Python
python -m http.server


Sau đó mở:

http://localhost:8000

🖼️ Thêm ảnh vào cây thông

Nhấn nút “Thêm ảnh”

Chọn 1 hoặc nhiều ảnh từ máy

Ảnh sẽ xuất hiện như vật trang trí trên cây thông Noel

📌 Ảnh được hiển thị dưới dạng:

Khung vàng

Có thể xoay, phóng to, focus

🕹️ Các chế độ hiển thị

Hệ thống có 3 chế độ chính:

Chế độ	Mô tả
🎄 TREE	Cây thông gọn gàng, xoay nhẹ
🌌 SCATTER	Các vật thể & ảnh bay tự do
🔍 FOCUS	Phóng to 1 ảnh cụ thể
Chuyển chế độ bằng cử chỉ tay (nếu có webcam)
Cử chỉ	Hành động
✋ Mở rộng bàn tay	Scatter
✊ Khép tay	Tree
🤏 Chụm ngón cái + trỏ	Focus 1 ảnh

⚠️ Nếu không có webcam, app vẫn hoạt động bình thường (chỉ không điều khiển bằng tay)

⌨️ Phím tắt
Phím	Chức năng
H	Ẩn / hiện bảng hướng dẫn & nút upload
📷 Webcam & quyền riêng tư

Webcam KHÔNG bắt buộc

Nếu cho phép:

Chỉ dùng để nhận diện cử chỉ tay

Không ghi hình

Không gửi dữ liệu ra ngoài

Nếu từ chối webcam → App vẫn chạy đầy đủ 🎄

🖥️ Yêu cầu hệ thống
Trình duyệt hỗ trợ

✅ Chrome (khuyên dùng)
✅ Edge
✅ Brave
⚠️ Firefox: có thể hạn chế MediaPipe
❌ Safari iOS: không khuyến khích

Thiết bị

PC / Laptop có GPU (khuyên dùng)

Webcam (tùy chọn)

Không hỗ trợ tốt trên điện thoại

✨ Công nghệ sử dụng

Three.js – Render 3D

Unreal Bloom Pass – Hiệu ứng ánh sáng

MediaPipe Hand Tracking – Nhận diện tay

WebGL + ES Modules

Google Fonts (Cinzel)

🎁 Gợi ý sử dụng

Làm thiệp Noel online

Trình chiếu trong sự kiện

Trang trí website cá nhân

Kỷ niệm ảnh gia đình dịp Giáng Sinh

🛠️ Lỗi thường gặp
Không thấy gì ngoài màn hình đen?

→ Dùng Chrome
→ Chạy qua local server

Không nhận tay?

→ Kiểm tra quyền camera
→ Ánh sáng đủ sáng

Lag?

→ Giảm số lượng ảnh
→ Đóng các tab khác

❤️ Lời kết

Chúc bạn có một mùa Giáng Sinh an lành & ấm áp 🎄
Nếu bạn muốn:

Thêm nhạc nền 🎵

Tự động chạy slideshow

Xuất thành website hoàn chỉnh

👉 Hãy nói mình biết, mình sẽ hỗ trợ tiếp!
