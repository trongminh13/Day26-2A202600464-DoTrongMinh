# DRAFT: Lab 2 Analysis Report — Cursor vs. Antigravity

> [!NOTE]
> Đây là bản nháp nội dung cho Slide Deck của bạn. Bạn có thể dùng nội dung này để đưa vào Canva/Google Slides/PowerPoint rồi xuất ra file `analysis-report.pdf`.

---

## S1 — Product Moment
- **Sản phẩm A:** **Cursor** (The AI Code Editor)
- **Sản phẩm B:** **Antigravity** (The Agentic Coding Assistant)
- **Nhiệm vụ:** Giải thích hệ thống và Refactor code phức tạp trong một codebase thực tế.
- **Entry Point:** 
  - Cursor: Tích hợp trực tiếp vào Editor (Native).
  - Antigravity: Tích hợp qua khung Chat/Agent trong VS Code.

## S2 — Workflow Evidence
- **Cursor (Step-by-Step):** 
  1. Highlight code -> Ctrl+L (Chat) hoặc Ctrl+I (Composer).
  2. Input: "Explain and refactor".
  3. Cursor đề xuất thay đổi trực tiếp trên file (Inline Diff).
  - *Friction:* Đôi khi Composer sửa quá nhiều file cùng lúc gây khó kiểm soát nếu project lớn.
- **Antigravity (Step-by-Step):** 
  1. Gõ yêu cầu vào khung Chat.
  2. Antigravity tự thực hiện `list_dir`, `view_file` để hiểu bối cảnh toàn project trước khi trả lời.
  3. Đưa ra giải pháp và hỏi xác nhận trước khi dùng `replace_file_content`.
  - *Friction:* Phụ thuộc vào tốc độ xử lý tool-use (chậm hơn autocomplete một chút nhưng sâu hơn).

## S3 — Output & Trust
- **Cursor:** Tốc độ cực nhanh (Instant), UI/UX mượt mà với phím tắt. Độ tin cậy cao nhờ dùng model Claude 3.5 Sonnet tối ưu. Có dẫn nguồn file (`@file`).
- **Antigravity:** Khả năng suy luận (Reasoning) sâu sắc. Tin tưởng tuyệt đối vì Antigravity liệt kê rõ các bước mình sẽ làm (Thought process). Khả năng phát hiện lỗi logic xuyên suốt nhiều file tốt hơn.

## S4 — Business Signal
- **Cursor:** Gói Free giới hạn, Pro $20/tháng, Business $40/tháng. Đã đạt **$2B ARR** (đầu 2026), 7M MAU.
- **Antigravity:** Thường đi kèm với các gói AI Agent cao cấp. Tập trung vào phân khúc "Advanced Developer" cần giải quyết task lớn hơn là chỉ code block nhỏ.

## S5 — Product Judgment (8 mục con)
1. **5.1 Verdict:** 
   - **Cursor:** *Strong* (Sản phẩm quốc dân cho dev).
   - **Antigravity:** *Promising* (Tiềm năng thay thế Junior Dev nhờ khả năng tự trị - Agentic).
2. **5.2 User base + Growth:** Cursor dẫn đầu với 7M MAU, tăng trưởng gấp đôi mỗi vài tháng. Antigravity đang tăng trưởng nhanh trong cộng đồng Power Users.
3. **5.3 Doanh thu:** Cursor $2B ARR (S-11). Antigravity có Pricing Power cao nhờ tiết kiệm hàng giờ debug.
4. **5.4 Moat:** 
   - Cursor: **Switching Cost** (Native Editor feel) + **Brand**.
   - Antigravity: **Data Flywheel** (Học từ context project sâu) + **Agentic Capability** (Khó bắt chước hơn chat thông thường).
5. **5.5 Data Flywheel:** Cả hai đều dùng feedback từ việc User Accept/Reject code để train model.
6. **5.6 Niche Down:** Cursor đánh vào "Everyday Coding". Antigravity đánh vào "Complex Refactoring & System Migration".
7. **5.7 Spark → Loop → System:** Cursor đã là một **System** ổn định. Antigravity đang ở giai đoạn **Loop** hoàn thiện cực nhanh.
8. **5.8 Liên hệ Lab 1:** Giống như Google AI Overview đe dọa publishers, Cursor/Antigravity đang "squeeze" các trang như Stack Overflow. Tuy nhiên, Antigravity giúp dev "thoát" khỏi Big Squeeze bằng cách làm việc hiệu quả hơn gấp 10 lần.
