# Bài 10: Đánh Giá Đa Giải Pháp Quy Trình Khắc Phục Sự Cố Kỹ Thuật
## Phần 1:
**Bảng so sánh hỗ trợ cảm tính và Troubleshooting 4 chặng:**

| Tiêu chí đánh giá | Hỗ trợ cảm tính | Troubleshooting 4 chặng |
| :--- | :--- | :---|
| Thời gian xử lý sự cố | Phụ thuộc vào việc Senior Dev có rảnh để trả lời hay không | Tự giải quyết tại chỗ trong 5-10 phút đầu tiên |
| Áp lực và chi phí cho Senior Devs | Senior Dev bị phân tâm liên tục bởi các câu hỏi lỗi cơ bản lặp đi lặp lại, làm tiêu tốn nhiều thời gian | Senior Dev chỉ tiếp nhận xử lý các lỗi phức tạp Bug Report chuẩn |
| Năng lực và tính tự chủ của KTV | Sợ các lỗi tiếng Anh, không nâng cao được tay nghề | Rèn được tư duy logic, làm chủ hoàn toàn thiết bị và tự tin giải quyết sự cố |
| Khả năng lưu vết tri thức | Bị trôi đi trong nhóm và những người sau sẽ lặp lại lỗi cũ | Dữ liệu lỗi và cách xử lý được cất vào tài liệu và được lưu trữ lại để sử dụng |

**Ban Giám đốc VoltCharge bắt buộc phải chọn Phương án 2 nếu muốn mở rộng quy mô lên 1,000 trạm sạc vì:**
1. Nó giúp khắc phục tình trạng chờ Senior Devs trả lời xử lí lỗi của trạm sạc giúp giảm thiệt hại cho công ty.
2. Giúp các kỹ thuật viên mới vào nghề có thể hiểu và xử lí được một số lỗi đã từng xảy ra từ đó có thêm thời gian để phát triển các mảng khác.

## Phần 2:
**Chặng 1:** 
- Tập trung tìm và tách các mã lỗi quan trọng.
- Sử dụng các toán tử để tra cứu trên Google.(`site:`, `" "`, `-`)

**Chặng 2:**
- Chú tâm đọc phần bên dưới vì ở đó sẽ có các nhận xét và giải pháp khắc phục mà những người dùng khác đưa ra.
- Nên chọn các nội dung có nhiều vote, có tích xanh.
- Ta cũng nên để ý đến thời gian đăng bài vì những bài đã đăng từ nhiều năm trước rất có thể không thể hoạt động như xưa.

**Chặng 3:**
- Gửi Prompt cho AI:
1. Nêu bối cảnh hiện tại của bạn.
2. Gửi nguyên đoạn mã lỗi cho AI.
3. Yêu cầu nó dịch đoạn code lỗi và đưa ra giải pháp để khắc phục trong 3 bước bằng tiếng Việt.

**Chặng 4:**
- Viết phiếu Bug Report:
1. Mô tả những gì đã xảy ra ở trạm nào.
2. Toàn bộ đoạn code lỗi.
3. Các bước xử lí khi gặp.
4. Phân tích thiệt hại mà nó đã gây ra và xếp loại mức độ khẩn cấp.