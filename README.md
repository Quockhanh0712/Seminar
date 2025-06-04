# Seminar
## Reinforcement Prompting Tạo Dữ liệu Tổng hợp trong Lĩnh vực Tài chính

**Nhóm thực hiện:** Nhóm 2
*   Trần Quốc Khánh - 23020387
*   Hoàng Ngọc Nam - 23020403
*   Nguyễn Văn Linh - 23020395
*   Nguyễn Hữu Hoàng Nam - 23020405

## Giới thiệu

Báo cáo này trình bày phương pháp **"Reinforcement Prompting"** - một cách tiếp cận mới để tạo dữ liệu tổng hợp chất lượng cao trong lĩnh vực tài chính. Mục tiêu chính là giải quyết các thách thức về khan hiếm dữ liệu được gán nhãn và các yêu cầu bảo mật dữ liệu, đặc biệt trong các tác vụ như phân tích cảm xúc tài chính.

Nội dung báo cáo gồm có :
- Báo cáo về nội dung tìm hiểu trình bày theo mẫu khóa luận : baocaokhoaluan.pdf

  Báo cáo theo nội dung format bài báo khoa học : reportpaper.pdf 
## Đóng góp chính

*   Giới thiệu phương pháp luận mới **"Reinforcement Prompting"** kết hợp học tăng cường (RL) với Mô hình Ngôn ngữ Lớn (LLM).
*   Sử dụng kiến trúc **Selector-Executor**: một tác nhân Selector (mạng chính sách) để tối ưu hóa việc tạo prompt và một LLM Executor để sinh dữ liệu.
*   Tạo ra dữ liệu tổng hợp giúp **bảo vệ quyền riêng tư** và **giảm phụ thuộc** vào dữ liệu thực tế.
*   Chứng minh hiệu suất cạnh tranh của các mô hình huấn luyện trên dữ liệu tổng hợp so với dữ liệu thực.

## Cách thức hoạt động 

1.  **Selector Agent** (dựa trên RL) chọn các từ khóa từ bộ từ vựng tài chính.
2.  Các từ khóa được điền vào **Prompt Template** để tạo prompt hoàn chỉnh.
3.  **Executor LLM** (ví dụ: GPT-3.5-turbo) nhận prompt và sinh dữ liệu tài chính tổng hợp.
4.  Chất lượng dữ liệu được đánh giá, phần thưởng được dùng để cập nhật chính sách của Selector Agent, cải thiện việc chọn từ khóa qua các vòng lặp.

## Từ khóa

Reinforcement prompting; Reinforcement learning; Synthetic data; Large language model; Financial sentiment analysis; Machine learning.
