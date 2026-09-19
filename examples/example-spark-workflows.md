# Các Quy Trình Làm Việc Mẫu Cùng Gemini Spark

Những ví dụ thực tế này minh họa cách bạn kết hợp các kỹ năng trong thư viện để tự động hóa công việc hàng ngày với Gemini Spark / Gemini Ultra.

---

## 1. Báo Cáo Kinh Doanh Đầu Ngày (Daily Business Brief)

**Ứng dụng liên kết:** Gmail, Google Calendar, Google Drive, Google Tasks  
**Kỹ năng sử dụng:** `spark-daily-brief`

```text
Mỗi sáng ngày làm việc, hãy rà soát Gmail, Calendar, các tệp Drive được cập nhật gần đây và danh sách việc cần làm (Tasks) của tôi. Tạo một bản báo cáo tinh gọn đầu ngày bao gồm: các ưu tiên hàng đầu hôm nay, danh sách lịch họp, các email khẩn cấp cần trả lời và đề xuất phân bổ khung giờ làm việc tập trung. Không tự ý gửi email, dời lịch họp hay chỉnh sửa tệp tin khi chưa có sự phê duyệt của tôi.
```

---

## 2. Tự Động Chuyển Email Thành Việc Cần Làm (Inbox to Task List)

**Ứng dụng liên kết:** Gmail, Google Tasks, Google Keep  
**Kỹ năng sử dụng:** `spark-inbox-to-tasks`

```text
Hãy rà soát các email chưa đọc và email quan trọng trong vòng 48 giờ qua. Trích xuất các yêu cầu công việc thực tế, phân loại theo mức độ khẩn cấp và soạn thảo một danh sách đầu việc có thứ tự ưu tiên. Luôn hỏi ý kiến phê duyệt của tôi trước khi tạo hoặc gán bất kỳ nhiệm vụ nào vào Google Tasks.
```

---

## 3. Quy Trình Chuẩn Bị Cuộc Họp (Meeting Prep Workflow)

**Ứng dụng liên kết:** Google Calendar, Gmail, Google Docs, Google Drive  
**Kỹ năng sử dụng:** `spark-meeting-prep`

```text
Trước cuộc họp sắp tới của tôi trên Calendar, hãy rà soát sự kiện, tìm các email trao đổi gần nhất với người tham dự và các tài liệu liên quan trong Drive. Soạn cho tôi một bản tóm tắt trước cuộc họp gồm: bối cảnh làm việc trước đó, gợi ý nghị trình thảo luận (agenda), các câu hỏi quan trọng cần làm rõ và các đầu việc còn tồn đọng. Hỏi ý kiến tôi trước khi chia sẻ hay chỉnh sửa bất kỳ tài liệu nào.
```

---

## 4. Lập Lịch Xuất Bản Nội Dung Tuần (Weekly Content Calendar)

**Ứng dụng liên kết:** YouTube, Google Docs, Google Sheets, Canva  
**Kỹ năng sử dụng:** `spark-content-engine`

```text
Hãy tạo một bảng lịch nội dung cho tuần tới dựa trên các ý tưởng gần đây của tôi, các chủ đề video YouTube thịnh hành và ghi chú đã lưu. Tổ chức các ý tưởng thành: câu mở đầu (hook), định dạng bài đăng, nội dung nháp và bản brief thiết kế đồ họa cho Canva. Luôn hỏi ý kiến tôi trước khi đăng bài công khai.
```

---

## 5. Tiếp Nhận Khách Hàng Tiềm Năng (Client Intake Summary)

**Ứng dụng liên kết:** Gmail, Google Docs, Google Sheets, Google Calendar  
**Kỹ năng sử dụng:** `spark-client-intake`

```text
Hãy đọc các email yêu cầu tư vấn mới nhất từ khách hàng và sắp xếp từng khách hàng tiềm năng vào một bản tổng hợp tiếp nhận. Ghi nhận loại hình doanh nghiệp, nhu cầu, mức độ khẩn, ngân sách, soạn nháp thư phản hồi chào mừng và đề xuất bước chăm sóc tiếp theo. Hỏi ý kiến tôi trước khi gửi thư hoặc thêm lịch hẹn.
```

---

## 6. Dọn Dẹp & Sắp Xếp Google Drive (Drive Cleanup)

**Ứng dụng liên kết:** Google Drive, Google Docs, Google Sheets, Google Slides  
**Kỹ năng sử dụng:** `spark-drive-organizer`

```text
Hãy rà soát các tệp tin gần đây trên Google Drive của tôi và đề xuất một cấu trúc thư mục ngăn nắp hơn. Phát hiện các tài liệu trùng lặp, các bản nháp cũ và các tệp có thể gom nhóm theo từng dự án. Tuyệt đối không tự ý di chuyển, xóa, đổi tên hoặc chia sẻ tệp khi chưa được tôi đồng ý.
```

---

## 7. Báo Cáo Toàn Cảnh Điều Hành Hàng Tuần (Weekly CEO Dashboard)

**Ứng dụng liên kết:** Gmail, Google Calendar, Google Tasks, Google Drive, Google Sheets  
**Kỹ năng sử dụng:** `spark-weekly-ceo-dashboard`

```text
Vào sáng thứ Hai hàng tuần, hãy tổng hợp toàn bộ các email quan trọng, cuộc họp chính, nhiệm vụ đã hoàn thành, tài liệu mới và tiến độ kinh doanh của tuần qua. Tạo cho tôi một bản báo cáo điều hành kiểu CEO gồm: thành quả đạt được, rủi ro tiềm ẩn, các việc cần theo dõi và top 3 ưu tiên tuần mới.
```
