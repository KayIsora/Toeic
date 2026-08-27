# TOEIC 4-Skill Study Project

Kho lưu trữ lộ trình, phiên học, kết quả làm bài, lỗi sai và từ vựng phục vụ mục tiêu TOEIC 4 kỹ năng.

## 1. Mục tiêu

- Chuẩn tham chiếu: UIT hệ chính quy, khóa tuyển sinh 2022–2023, chương trình đại trà.
- Chuẩn đầu ra của trường:
  - TOEIC Listening + Reading: **từ 450 điểm**.
  - TOEIC Speaking–Writing: **từ 185 điểm theo cách ghi của UIT**.
  - Đồng thời hoàn thành các môn Anh văn trong chương trình đào tạo.
- Mục tiêu luyện có dự phòng:
  - Listening + Reading: hướng tới **500+**.
  - Speaking + Writing: theo dõi hai điểm riêng của ETS và hướng tới tổng quy ước nội bộ **210+**.

> ETS trả điểm Speaking và Writing riêng biệt. Tổng Speaking + Writing trong repo chỉ là quy ước theo dõi nội bộ để bám chuẩn UIT, không phải một điểm tổng chính thức do ETS phát hành.

## 2. Mốc thời gian

- Bắt đầu: **27/08/2026**.
- Thi TOEIC Speaking & Writing: **16/09/2026**.
- Có 20 ngày chuẩn bị trọn vẹn từ 27/08 đến hết 15/09.
- Giai đoạn Listening & Reading: 15 ngày sau kỳ thi Speaking & Writing; lịch tạm tính **17/09–01/10/2026**, sẽ điều chỉnh khi có ngày thi chính thức.

### Lộ trình Speaking & Writing

| Ngày | Thời gian | Nội dung cốt lõi |
|---|---|---|
| D01 | 27/08 | Diagnostic đúng cấu trúc Speaking & Writing |
| D02 | 28/08 | Speaking Q1–2: Read a Text Aloud |
| D03 | 29/08 | Writing Q1–5: Write a Sentence Based on a Picture |
| D04 | 30/08 | Speaking Q3–4: Describe a Picture |
| D05 | 31/08 | Writing Q6–7: Respond to a Written Request |
| D06 | 01/09 | Speaking Q5–7: Respond to Questions |
| D07 | 02/09 | Writing Q8: Opinion Essay |
| D08 | 03/09 | Speaking Q8–10: Use Information Provided |
| D09 | 04/09 | Speaking Q11: Express an Opinion |
| D10 | 05/09 | Speaking mixed timed drill |
| D11 | 06/09 | Writing mixed timed drill |
| D12 | 07/09 | Speaking full mini-mock |
| D13 | 08/09 | Writing full mini-mock |
| D14 | 09/09 | Full Speaking & Writing Mock 1 |
| D15 | 10/09 | Ngân hàng cấu trúc, từ nối, phát âm và lỗi ngữ pháp thường gặp |
| D16 | 11/09 | Full Speaking & Writing Mock 2 |
| D17 | 12/09 | Timed repair toàn bộ dạng câu hỏi |
| D18 | 13/09 | Full Speaking & Writing Mock 3 |
| D19 | 14/09 | Chữa mock cuối, làm lại câu sai và chốt chiến thuật |
| D20 | 15/09 | Ôn nhẹ, giao diện thi, thiết bị và tâm lý phòng thi |
| Thi | 16/09 | TOEIC Speaking & Writing |

## 3. Nguyên tắc học

### Lộ trình cốt lõi

- Thực hiện đúng thứ tự D01–D20.
- Không thay bài chính bằng bài chữa lỗi phát sinh.
- Mỗi ngày hoàn thành nhiệm vụ chính trước khi làm phần bổ sung.

### Phần bổ sung theo lỗi thật

- Được ghi riêng dưới mục `Bài bổ sung theo lỗi` trong README của phiên học.
- Chiếm khoảng 15–25% khối lượng học trong ngày.
- Dùng để sửa lỗi lặp lại nhưng không làm thay đổi trật tự của lộ trình cốt lõi.

## 4. Cấu trúc kho lưu trữ

```text
Toeic/
├── README.md
├── RESOURCES.md
├── SESSION_TEMPLATE.md
├── Vocabulary.xlsx
├── .gitignore
└── SW_Sxx_YYYY-MM-DD_Topic/
    └── README.md
```

- `README.md`: bảng điều khiển và quy ước chung.
- `RESOURCES.md`: tài liệu chính thức, đề mô phỏng và video chữa bài.
- `SESSION_TEMPLATE.md`: mẫu README dùng cho mỗi phiên.
- `Vocabulary.xlsx`: bảng 3 cột gồm English, loại từ/cụm từ và nghĩa tiếng Việt.
- Mỗi thư mục `SW_...` hoặc `LR_...` là một phiên học, một part đủ lớn hoặc một bộ đề.

## 5. Quy trình một phiên học

1. Mở nguồn đề/tài liệu được chỉ định.
2. Làm bài đúng thời gian và giữ nguyên câu trả lời đầu tiên.
3. Tự ghi kết quả trực tiếp vào README của phiên.
4. Dùng ChatGPT Web/Voice để chấm, giải thích và luyện lại.
5. Người học tự cập nhật README; ChatGPT không tự ghi đè phần nhật ký học.
6. Sau một test hoặc một part đủ lớn, chọn từ cần học và bổ sung vào `Vocabulary.xlsx`.
7. Commit kết quả lên GitHub.

## 6. Quy tắc riêng tư và bản quyền

- Repo được giữ ở chế độ public.
- Không commit file ghi âm, video chia sẻ màn hình, giấy tờ, mã dự thi hoặc thông tin cá nhân.
- Không tải lại nguyên bộ đề/audio có bản quyền khi chưa được phép.
- Ưu tiên lưu đường dẫn nguồn, đáp án cá nhân, ghi chú và phân tích lỗi.

## 7. Quy ước tên phiên

```text
SW_S01_2026-08-27_Diagnostic
SW_S02_2026-08-28_Read_Aloud
LR_S01_YYYY-MM-DD_Diagnostic
```

## 8. Trạng thái hiện tại

| Hạng mục | Trạng thái |
|---|---|
| Kết nối GitHub | Hoàn tất |
| Khung repo | Hoàn tất |
| Phiên SW_S01 | Đã tạo, chưa làm |
| Diagnostic Speaking & Writing | Chưa làm |
| Điểm nền | Chưa xác định |
| Ngày thi Speaking & Writing | 16/09/2026 |
| Ngày thi Listening & Reading | Chưa đăng ký |
