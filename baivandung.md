# Thiết kế giải pháp Prompting ứng dụng thực tế cho Ứng dụng AI trong Học tập & Nghiên cứu
## Bước 1
- Tự động hóa quy trình đánh giá bài và giải thích khái niệm phức tạp bằng ngôn ngữ đơn giản theo kỹ thuật Feynman, đồng thời đóng vai trò là gia sư phản hồi lỗ hổng kiến thức 
Input
- chủ đề kiến thức cần kiểm tra 
- nội dung bài và giải thích của sinh viên
- thang điểm và tiêu chí chấm bài
- đối tượng người nghe giả định ( mặc định là học sinh lớp 6)
Output
- điểm từng tiêu chí, tổng điểm và giải thích ngắn gọn
- chỉ ra thuật ngữ khó hiểu và lỗ học tư duy gợi ý câu hỏi mở để sinh viên tự sửa
- ví dụ chuẩn xác dễ hiểu
## Bước 2
Bạn là một gia sư AI chuyên sâu về phướng pháp học tập Feynman. Nhiệm vụ của bạn là chấm điểm bài làm của sinh viên theo Rubric và hướng dẫn sinh viên lấp lỗ hỏng kiến thức
- chủ đề kiến thức: kỹ năng Prompting với AI 
- đối tượng người nghe: lớp 6
- tiêu chí rubric 
- giải thích của sinh viên: Kỹ năng prompting với AI là khả năng viết câu trúc câu lệnh để hướng dẫn mô hình AI tạo ra kết quả chính xác, đúng trọng tâm mà không cần phải hỏi lại nhiều lần. Cần nói rõ ai làm, bối cảnh, yêu cầu, trình bày và đầu ra
- vd: đóng vai trò là gia sư lập trình hãy giải khái niệm đệ quy bằng ngôn ngữ dễ hiểu cho người mới bắt đầu kèm 1 ví dụ để giúp sinh viên hiểu rõ hơn 
Thực hiện kiểm tra tuần tự các điều kiện sau
- lỗi thiếu, rỗng dữ liệu 
- lạc đề, sai đề.
chỉ xuất dữ liệu hợp lệ, theo đúng cấu trúc
- chấm điểm rubric
- thuật ngữ khó chưa giải thích được
- lỗ hỏng lập luận
- câu hỏi gợi mở
## kết quả AI trả về
Chấm điểm Rubric (Thang điểm 10)
Độ chính xác kiến thức (3/3 điểm): Nắm vững bản chất của Prompting và các thành phần cốt lõi (vai trò, bối cảnh, yêu cầu, định dạng đầu ra).

Sự đơn giản hóa cho đối tượng lớp 6 (1.5/3 điểm): Còn dùng nhiều từ ngữ trừu tượng, mang tính kỹ thuật thay vì ví dụ đời thường gần gũi với học sinh 11-12 tuổi.

Cấu trúc và ví dụ minh họa (2/2 điểm): Ví dụ có đủ các yếu tố đã nêu ở phần giải thích.

Tổng điểm: 6.5/10

Thuật ngữ khó chưa giải thích được
Các từ khóa này quá trừu tượng đối với học sinh lớp 6, cần được "dịch" sang ngôn ngữ đời thường:

"Mô hình AI": Nên giải thích giống như một "bộ não máy tính thông minh" hoặc "người trợ lý robot".

"Cấu trúc câu lệnh": Nên đổi thành "cách sắp xếp lời dặn dò" hoặc "công thức đặt câu hỏi".

"Bối cảnh": Nên ví von là "hoàn cảnh lúc đó" hoặc "tình huống đang xảy ra".

"Đệ quy" (trong ví dụ): Đây là kiến thức lập trình đại học, học sinh lớp 6 không biết khái niệm này là gì nên ví dụ bị mất tác dụng minh họa.

Lỗ hổng lập luận
Mâu thuẫn giữa lý thuyết và ví dụ: Bạn xác định người nghe là học sinh lớp 6, nhưng ví dụ của bạn lại yêu cầu AI đóng vai gia sư lập trình giải thích khái niệm đệ quy cho sinh viên. Ví dụ này không phù hợp với lứa tuổi người nghe.

Thiếu sự kết nối trực quan: Bạn liệt kê 5 yếu tố (ai làm, bối cảnh, yêu cầu, trình bày, đầu ra) nhưng chưa giải thích tại sao thiếu chúng thì AI lại trả lời sai. Trẻ lớp 6 cần một phép so sánh (ví dụ: dặn AI giống như dặn một bạn cùng lớp đi mua đồ giúp, phải dặn rõ mua ở đâu, loại gì, bao nhiêu tiền).

Câu hỏi gợi mở
Nếu em phải nhờ một bạn robot làm giúp bài tập về nhà môn Lịch sử lớp 6, em sẽ thay ví dụ "đệ quy" bằng ví dụ nào để bạn lớp 6 đọc vào là hiểu ngay?

Làm thế nào để giải thích cụm từ "cấu trúc câu lệnh" và "đầu ra" bằng cách so sánh với việc gọi một món ăn ở căng-tin trường học?