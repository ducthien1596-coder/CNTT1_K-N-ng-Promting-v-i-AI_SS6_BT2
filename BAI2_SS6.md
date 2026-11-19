
# So sánh Trade-off các giải pháp ra lệnh cho Ứng dụng AI trong Học tập & Nghiên cứu

## Bước 1: Đề xuất 2 Prompt mẫu

**Chủ đề chung:** Ứng dụng AI trong Học tập & Nghiên cứu - Tối ưu hóa Feynman Prompt gia sư và Rubric chấm bài tự động

### Giải pháp 1: Prompt Đơn giản, Ngắn gọn

> Hãy giải thích cho tôi về Feynman Prompt gia sư và Rubric chấm bài tự động.

### Giải pháp 2: Prompt Chi tiết, Nhiều ràng buộc

> Bạn là gia sư Socratic chuyên về Ứng dụng AI trong Học tập & Nghiên cứu.
>
> Nhiệm vụ: Giải thích 2 khái niệm:
> 1. Feynman Prompt gia sư
> 2. Rubric chấm bài tự động
>
> Ràng buộc đầu ra:
> - Định dạng: Chỉ dùng gạch đầu dòng "-"
> - Mỗi khái niệm: Tối đa 3 gạch đầu dòng, mỗi dòng tối đa 25 từ
> - Ngôn ngữ: Tiếng Việt đơn giản, dùng 1 ví dụ đời thường cho mỗi khái niệm
>
> Cấm tuyệt đối:
> - Cấm lời chào, lời kết, câu hỏi gợi mở
> - Cấm giải thích lịch sử, tiểu sử
>
> Bắt đầu trả lời ngay bằng gạch đầu dòng đầu tiên.

## Bước 2: Bảng so sánh Trade-off

| Tiêu chí | Giải pháp 1 (Đơn giản) | Giải pháp 2 (Chi tiết) |
| --- | --- | --- |
| Độ dễ hiểu | Cao | Trung bình |
| Tốn token | Ít | Nhiều hơn |
| Tốc độ viết Prompt | Rất nhanh, 5 giây | Chậm hơn, cần 2-3 phút suy nghĩ |
| Chặn lỗi biên | Trung bình | Cực tốt |
| Chất lượng đầu ra | Dài dòng, hay nịnh hót, lan man | Ngắn gọn, sạch, đúng trọng tâm |
| Tính nhất quán | Thấp, mỗi lần chạy ra 1 kiểu | Cao, chạy 10 lần giống nhau 90% |
| Phù hợp với | Hỏi nhanh, brainstorm, trò chuyện | Làm bài tập, nghiên cứu, cần nộp bài |

## Bước 3: Lựa chọn và chạy thử

**Lựa chọn của em: Giải pháp 2 - Prompt Chi tiết**

**Lý do chọn:**
Mặc dù Giải pháp 2 tốn token hơn và khó viết hơn, nhưng trong bối cảnh học tập, cái chúng ta cần là **độ chính xác và tính nhất quán**, không phải tốc độ. Giải pháp 1 tiết kiệm được 20 token nhưng lại tốn thêm 5 phút để đọc và lọc bỏ phần thừa, và dễ bị AI nịnh hót, mất điểm Rubric.

> **Nguyên tắc Trade-off:** Đổi "Tốn thêm token đầu vào" để lấy "Chất lượng đầu ra cao + Không phải sửa lại".

**Kết quả chạy thử Giải pháp 2:**

- **Feynman Prompt gia sư:** AI đóng vai gia sư, chỉ hỏi gợi mở để người học tự giải thích lại kiến thức bằng lời của mình.
- **Feynman Prompt gia sư:** Dùng ví dụ như dạy lại cho đứa trẻ 12 tuổi để kiểm tra xem đã hiểu thật hay chưa.
- **Feynman Prompt gia sư:** Nếu người học bí, AI gợi ý từng bước thay vì đưa đáp án ngay.
- **Rubric chấm bài tự động:** Là bảng tiêu chí chấm điểm có sẵn, ví dụ: Correctness 40%, Security 20%, Code Quality 20%, Documentation 20%.
- **Rubric chấm bài tự động:** Giúp AI chấm công bằng, không khen chung chung, chỉ ra đúng lỗi và cách sửa.
- **Rubric chấm bài tự động:** Người học biết trước mình sẽ bị chấm ở đâu để tự cải thiện trước khi nộp.

**Kết luận:** Với bài toán học tập & nghiên cứu cần chuẩn mực, Giải pháp 2 tối ưu hơn hẳn Giải pháp 1.
