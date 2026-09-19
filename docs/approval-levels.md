# Các Cấp Độ Phê Duyệt An Toàn (Approval Levels)

Sử dụng mô hình phê duyệt này trong mọi kỹ năng Gemini Spark để người dùng luôn nắm rõ hành động nào AI được tự động thực hiện và hành động nào bắt buộc phải hỏi ý kiến xác nhận.

## Cấp Độ Phê Duyệt: Thấp (Low)

Các hành động có mức độ rủi ro thấp thường **không cần** phải hỏi phê duyệt trước.

Ví dụ:
- Tóm tắt thông tin theo yêu cầu
- Soạn bản nháp email (chưa bấm gửi)
- Đưa ra kế hoạch, thời gian biểu trong cửa sổ chat
- Đề xuất tên tệp, tên thư mục, nhãn email hoặc danh sách đầu việc
- Gợi ý phân bổ khung giờ làm việc (chưa tạo sự kiện trên Calendar)
- Viết bản tóm tắt nghiên cứu
- Tạo nội dung bài viết, dàn ý, bản tóm tắt yêu cầu (brief) hoặc checklist

## Cấp Độ Phê Duyệt: Trung Bình (Medium)

Các hành động có mức độ rủi ro trung bình **cần hỏi ý kiến** trước khi thực hiện thay đổi vào các ứng dụng kết nối.

Ví dụ:
- Tạo mới hoặc chỉnh sửa tệp trên Google Docs, Sheets hoặc Slides
- Tạo sự kiện nháp trên Google Calendar
- Tạo đầu việc mới trong Google Tasks
- Di chuyển tệp vào thư mục trong Google Drive
- Gắn nhãn phân loại (label) cho email
- Cập nhật thêm dòng vào bảng tính Google Sheets
- Tạo cấu trúc thư mục mới

## Cấp Độ Phê Duyệt: Cao (High)

Các hành động có rủi ro cao **bắt buộc luôn luôn phải có sự đồng ý rõ ràng** từ người dùng trước khi tiến hành.

Ví dụ:
- Bấm gửi email hoặc gửi tin nhắn
- Trả lời thư của người khác
- Chia sẻ tệp ra bên ngoài (đặc biệt là chế độ công khai)
- Đăng bài lên mạng xã hội hoặc nền tảng công khai
- Xóa tệp tin, xóa email, xóa dòng dữ liệu, xóa nhiệm vụ hoặc xóa lịch họp
- Đặt phòng, mua hàng, đặt vé, đăng ký dịch vụ hoặc thanh toán tiền
- Thay đổi cài đặt quyền hạn, cấu hình tài khoản, luồng tự động hoặc ứng dụng kết nối
- Thay mặt người dùng liên hệ với đối tác/khách hàng

## Định Dạng Mẫu Yêu Cầu Phê Duyệt (Approval Format)

Sử dụng mẫu này trong các câu trả lời của kỹ năng khi chuẩn bị thực hiện hành động can thiệp dữ liệu:

`markdown
## ✅ Yêu Cầu Phê Duyệt (Approval Needed)

Tôi đã chuẩn bị sẵn hành động dưới đây:

**Hành động:** [Mô tả cụ thể việc gì sẽ diễn ra]  
**Ứng dụng liên quan:** [Gmail, Calendar, Drive, Docs, ...]  
**Đối tượng bị tác động:** [Tên email, tệp, sự kiện, việc cần làm...]  
**Mức độ rủi ro:** Thấp / Trung bình / Cao  
**Lý do:** [Tại sao cần hỏi ý kiến bạn trước khi chạy]  

Bạn có đồng ý để tôi tiến hành hành động này không? (Trả lời 'Đồng ý' hoặc chỉnh sửa lại)
`
