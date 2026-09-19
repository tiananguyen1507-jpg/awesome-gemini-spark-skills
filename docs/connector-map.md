# Bản Đồ Liên Kết Ứng Dụng (Gemini Spark Connector Map)

Sử dụng bản đồ này để quyết định kỹ năng nào cần bật những ứng dụng liên kết (Connectors) nào.

| Ứng Dụng (Connector) | Nhóm Kỹ Năng Phù Hợp Nhất | Lưu Ý Về Phê Duyệt & An Toàn |
|---|---|---|
| Gmail | Tóm tắt hòm thư, soạn nháp trả lời, nhắc việc, tiếp nhận khách, hóa đơn | Gửi email, trả lời, chuyển tiếp, lưu trữ (archive), xóa thư |
| Google Calendar | Lên kế hoạch ngày, chuẩn bị họp, lập lịch trình, time blocking | Tạo mới, sửa, xóa hoặc dời lịch các sự kiện |
| Google Drive | Tìm kiếm tệp, dọn dẹp tổ chức, cấu trúc thư mục, tổng hợp tài liệu | Di chuyển, xóa, chia sẻ hoặc thay đổi quyền truy cập tệp |
| Google Docs | Viết SOP, cẩm nang, ghi chép, tóm tắt, báo cáo | Tạo mới hoặc sửa đổi tài liệu; chia sẻ ra bên ngoài |
| Google Sheets | Bảng theo dõi số liệu, dashboard, sổ nhật ký, báo cáo | Sửa đổi dòng dữ liệu, chỉnh công thức, chia sẻ bảng tính |
| Google Slides | Dàn ý thuyết trình, kịch bản slide, chuẩn bị slide | Tạo mới hoặc sửa đổi bài thuyết trình; chia sẻ ra ngoài |
| Google Keep | Thu thập ý tưởng nhanh, dọn dẹp ghi chú, trích xuất đầu việc | Sửa đổi hoặc xóa ghi chú |
| Google Tasks | Tạo nhiệm vụ, sắp xếp ưu tiên, nhắc nhở hạn chót | Tạo mới, đánh dấu hoàn thành hoặc xóa nhiệm vụ |
| YouTube | Nghiên cứu video, phân tích xu hướng, tìm cảm hứng | Tránh sao chép nguyên văn kịch bản có bản quyền |
| Google Maps | Lịch trình di chuyển, nghiên cứu địa điểm, kế hoạch địa phương | Đặt chỗ, cam kết lịch trình di chuyển thực tế |
| Canva | Viết brief thiết kế, ý tưởng bài đăng, chỉ dẫn đồ họa | Xuất bản, chia sẻ hoặc chỉnh sửa tệp thiết kế chính thức |
| Google Photos | Tìm tài nguyên ảnh, tổ chức thư viện hình ảnh | Quyền riêng tư về hình ảnh và chia sẻ ảnh ra ngoài |
| GitHub | Tóm tắt kho mã nguồn, viết docs, lập kế hoạch issue, giải thích code | Thay đổi mã nguồn, tạo pull request, issue, lộ lọt mã khóa bảo mật (keys/secrets) |

## Nguyên Tắc Kết Nối Tinh Gọn (Simple Connector Rule)

Chỉ kết nối đúng những ứng dụng thực sự cần thiết cho công việc đó.

*Ví dụ:* Báo cáo ngày mới (**Daily Brief**) có thể cần Calendar, Gmail, Tasks và Drive. Nhưng viết Brief thiết kế Canva (**Canva Creative Brief**) thì thường chỉ cần Docs và Canva là đủ.
