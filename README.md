📊 Crypto Market Analysis Workflow
Đây là một workflow dành cho n8n sử dụng node LangChain để phân tích thị trường Bitcoin theo thời gian thực, bao gồm giá, khối lượng và các chỉ báo kỹ thuật như RSI, MACD, Stochastic, Bollinger Bands...
(Lưu ý : sử dụng api free của twele data nên dữ liệu chỉ có thể hỏi được 100 lần một ngày mỗi lần cách 1 phút để tránh trường hợp không gọi được do giới hạn gọi api )

🧠 Mục tiêu
Phản hồi các tin nhắn gửi đến bằng một phân tích chuyên sâu về thị trường crypto, mô phỏng một chuyên gia đầu tư với 20 năm kinh nghiệm.

⚙️ Hướng dẫn cài đặt
Yêu cầu:

n8n đã được cài đặt và hoạt động.

Đã bật Webhook cho chatTrigger.

Cài đặt:

Tải file JSON workflow.

Vào n8n > "Import workflow" > Dán hoặc chọn file JSON.

Bấm Activate để kích hoạt workflow.

Cấu hình thêm (nếu cần):

Cập nhật các API Key trong các node lấy dữ liệu thị trường (nếu dùng các API yêu cầu xác thực).

Kiểm tra timezone hiển thị (UTC+7) để phù hợp với nhu cầu.

💬 Cách sử dụng
Khi người dùng gửi tin nhắn đến webhook, workflow sẽ:

Lấy dữ liệu giá và chỉ số kỹ thuật từ các API.

Phân tích toàn diện với LangChain.

Trả về câu trả lời như một chuyên gia tài chính thực thụ.

📌 Ghi chú
Workflow này lý tưởng cho chatbot đầu tư, trợ lý phân tích thị trường hoặc bot dự báo xu hướng.

Có thể mở rộng để hỗ trợ thêm altcoins, các phân tích nâng cao khác như xu hướng, kháng cự/hỗ trợ, v.v.
