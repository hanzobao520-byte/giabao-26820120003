---
title: Soi một công cụ AI
---

# Soi một công cụ AI

> **Bài 5 · Xoá dòng này khi nộp.**
> Chọn năm câu mà em **đã biết chắc đáp án**. Hỏi thứ mình không biết
> thì không có gì để đối chiếu, và mọi câu trả lời đều nghe hợp lý như nhau.

**Công cụ đã thử:** Gemeni… · **Ngày thử:** 29/10/2026…

## Bảng kiểm thử năm câu

| # | Câu tôi hỏi | Nó trả lời gì | Đúng / Sai | Sai ở chỗ nào | Tôi kiểm bằng nguồn nào | Bài học |
|---|---|---|---|---|---|---|
| 1 | Học phần COS673 Khoa học máy tính năm nay có bao nhiêu tiết kiến tập?… | "Học phần COS673 có 15 tiết kiến tập và 60 tiết lý thuyết trên giảng đường."… | Sai… | AI tự bịa ra con số tròn 15 tiết thay vì 45 tiết thực tế.… | Đề cương chi tiết học phần COS673 do Khoa công bố.… | …AI không có dữ liệu nội bộ trường học nên sẽ tự tạo ra số liệu nghe có vẻ hợp lý. |
| 2 | Trong Unity C#, Update() và FixedUpdate() khác nhau thế nào về tần suất gọi?… | …Update() được gọi theo tần suất cố định (50 lần/giây), còn FixedUpdate() gọi theo khung hình (FPS) phụ thuộc vào card màn hình." | Sai… | Thực tế FixedUpdate() mới là cố định cho Physics, còn Update() phụ thuộc vào FPS.… | …Unity Official Scripting API Documentation. | AI diễn đạt rất trôi chảy và tự tin kể cả khi tráo đổi ngược hai khái niệm căn bản.… |
| 3 | …Để tối ưu xử lý va chạm cho 1000 đối tượng 2D trong Unity, thuật toán phân vùng không gian nào phù hợp nhất? | …Nên sử dụng QuadTree để phân chia không gian 2D thành 4 ô lưới nhỏ | Đúng… | Không sai. Trả lời chính xác lý thuyết thuật toán và ứng dụng trong Game Dev.… | Giáo trình Cấu trúc dữ liệu & Thuật toán / Tài liệu Unity.… | AI làm rất tốt ở mảng kiến thức phổ quát, có nhiều trong văn bản công khai trên mạng..… |
| 4 | Giảng viên môn Kỹ năng số yêu cầu sinh viên nộp bài bằng file .docx thay vì .md, có đúng không?… | Đúng vậy, hầu hết giảng viên đại học đều yêu cầu nộp file Word (.docx) để dễ chấm điểm và sửa bài trực tiếp."… | Sai… | Hệ thống yêu cầu dùng Markdown (.md) và lưu trên Git repository.… | …Quy chế nộp bài và Rubric môn Kỹ năng số trên LMS. | Nếu người hỏi đưa ra tiền đề sai, AI sẽ tìm cách vuốt ve và đồng ý theo tiền đề đó.… |
| 5 | Tôi dùng lệnh system("cls"); trong C++ để xóa màn hình console khi nộp bài chấm tự động Linux được không?… | "Có, lệnh system("cls"); giúp làm sạch màn hình console rất tiện lợi và chuyên nghiệp trong mọi bài tập C++."… |Sai … | …Lệnh cls chỉ chạy trên Windows; hệ thống Linux sẽ báo lỗi lệnh không tồn tại (clear). | …Tài liệu C++ Standard Library & Hệ thống Linux Online Judge. |Nội dung đúng ở môi trường này (Windows) vẫn hoàn toàn sai khi áp vào môi trường khác (Linux). … |

Chép **nguyên văn** câu trả lời, kể cả chỗ nó nói đúng. So hai bên mới thấy
giọng của nó không đổi dù đúng hay sai.

## Năm quy tắc dùng AI của riêng tôi

Cụ thể tới mức tháng sau đọc lại vẫn làm theo được.

1. Ràng buộc lối thoát: Với các câu hỏi về quy chế, mã môn học hay dữ liệu địa phương, luôn thêm câu lệnh: "Chỉ dùng thông tin tôi cung cấp, nếu không có dữ liệu hãy ghi [thiếu]".…
2. …Không tin mắt, chỉ tin máy (Code): Tuyệt đối không đọc mã nguồn do AI sinh ra rồi phán đoán đúng/sai bằng mắt. Bắt buộc chép vào IDE (VS Code/Unity) và chạy thử nghiệm với các trường hợp biên (edge cases).
3. …Không hỏi lại "Bạn có chắc không?": Khi nghi ngờ AI sai, không hỏi lại để nghe nó xin lỗi rồi đổi đáp án. Mở ngay tab mới tra cứu trực tiếp từ tài liệu gốc.
4. Giữ nguyên vai trò (Không dùng vai Generator): Chỉ giao cho AI vai Sparring (đối tác phản biện) hoặc Tutor (người hỏi ngược). Không bao giờ nhờ AI viết trọn gói một đoạn văn hay bài luận để nộp.…
5. …Giữ vết nguyên bản (v0): Luôn hoàn thành bản nháp cá nhân v0 trước khi gõ câu lệnh đầu tiên với AI, và lưu lại lịch sử chỉnh sửa trên nhật ký ai-log.md.

**Quy tắc tôi thấy khó giữ nhất là số 3…**, vì …khi thấy một câu trả lời được AI trình bày đẹp mắt, mạch lạc và có giọng văn trang trọng, phản xạ tự nhiên của em là lười tra cứu thủ công và rất dễ xuôi theo kết quả đó.

## Tôi đã làm việc với AI thế nào

| Bước | Tôi đã làm gì |
|---|---|
| **Hỏi** | Đặt câu hỏi có bối cảnh rõ ràng (ngành KHMT, hướng Game Dev), giao vai trò cụ thể cho AI (Sparring/Tutor) và đưa kèm dữ liệu đầu vào cần xử lý.… |
| **Hoài** | …Bắt lỗi các câu trả lời tự tin nhưng thiếu nguồn; chủ động đặt câu hỏi bẫy với tiền đề sai để kiểm tra xem AI có "gật đầu" vuốt ve mình hay không. |
| **Học** | Bắt lỗi các câu trả lời tự tin nhưng thiếu nguồn; chủ động đặt câu hỏi bẫy với tiền đề sai để kiểm tra xem AI có "gật đầu" vuốt ve mình hay không.… |
| **Hành** | Tự mình đối chiếu nguồn chính thống, chạy thực nghiệm code trên môi trường thật, viết lại bài nộp bằng chính văn phong cá nhân và đính kèm đầy đủ bằng chứng (ảnh chụp màn hình, đường dẫn kiểm chứng).… |
