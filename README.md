# AI Automation – Quy trình tạo đề thi tự động

Repository này chứa mã nguồn (workflow n8n) của một hệ thống tự động hóa
ứng dụng trí tuệ nhân tạo trong việc hỗ trợ giáo viên biên soạn đề kiểm tra môn Toán
theo ma trận kiến thức và các mức độ nhận thức.

## 1. Mục tiêu của sản phẩm
Sản phẩm được xây dựng nhằm:
- Hỗ trợ giáo viên tạo đề thi nhanh chóng từ đề mẫu hoặc tài liệu đầu vào
- Đảm bảo đề thi được xây dựng theo ma trận kiến thức (biết – hiểu – vận dụng)
- Chuẩn hóa cấu trúc đề thi theo yêu cầu kiểm tra, đánh giá
- Giảm tải thời gian và công sức cho giáo viên trong khâu ra đề

## 2. Bối cảnh giáo dục
Quy trình được thiết kế phù hợp với hoạt động kiểm tra, đánh giá trong giáo dục phổ thông,
đặc biệt là môn Toán.
AI trong hệ thống đóng vai trò hỗ trợ giáo viên trong việc tổ chức và biên soạn đề thi,
không thay thế vai trò chuyên môn và trách nhiệm đánh giá của giáo viên.

## 3. Công nghệ sử dụng
- n8n: Nền tảng tự động hóa quy trình
- OpenAI: Mô hình ngôn ngữ hỗ trợ phân tích và tạo nội dung đề thi
- Form Trigger: Thu thập đề mẫu hoặc tài liệu đầu vào
- Google Drive: Lưu trữ đề thi hoàn chỉnh dưới dạng văn bản

## 4. Mô tả quy trình hoạt động
Quy trình tạo đề thi bao gồm các bước chính:
1. Kích hoạt workflow khi giáo viên gửi đề mẫu thông qua biểu mẫu
2. AI phân tích nội dung đề mẫu và lập dàn ý theo ma trận kiến thức
3. Bóc tách nội dung câu hỏi thành dữ liệu có cấu trúc
4. Tạo đề thi hoàn chỉnh theo định dạng chuẩn
5. Tổng hợp dữ liệu và xuất đề thi ra Google Drive

## 5. Mã nguồn
Mã nguồn của sản phẩm được cung cấp dưới dạng workflow n8n trong tệp JSON:
- Quy trình tạo đề thi.json

Tệp này có thể được import trực tiếp vào n8n để tái sử dụng hoặc mở rộng hệ thống.

## 6. Ngữ cảnh học phần
Sản phẩm được xây dựng trong khuôn khổ học phần:
Trí tuệ nhân tạo trong Giáo dục  
Sinh viên ngành Sư phạm Toán – Trường Đại học Sư phạm TP. Hồ Chí Minh.

## 7. Ghi chú
Sản phẩm mang tính học thuật và thực nghiệm,
phục vụ mục đích học tập và nghiên cứu trong giáo dục.
AI được sử dụng như một công cụ hỗ trợ nhằm nâng cao hiệu quả công tác ra đề của giáo viên.
