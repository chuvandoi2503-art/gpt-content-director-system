# WM_04_1_CONTENT_DAILY - VIỆC ĐANG DỞ HÔM NAY GPT CONTENT OS

Phiên bản: 03.001

Trạng thái: Working Memory nạp mặc định

---

# 1. MỤC ĐÍCH

File này lưu:

* Việc đang thực hiện.
* Việc cần hoàn thành trong giai đoạn hiện tại.
* Trạng thái vận hành hiện hành.

File này được phép thay đổi thường xuyên.

Đây là file làm việc chính của GPT Content OS.

---

# 2. TRẠNG THÁI HIỆN TẠI

# CÔNG VIỆC HIỆN TẠI

## Trạng thái chung

ĐANG TÁI CẤU TRÚC GPT CONTENT OS.

Mục tiêu hiện tại:

Chốt kiến trúc Content trước khi thiết kế Profile.

Kiến trúc đã xác nhận:

Core

↓

Profile

↓

Research

↓

Content

↓

User

---

## Quyết định đã chốt

Content OS:

- Nhận input thật.
- QC Input.
- Xác định Profile.
- Tra Profile.
- Thực hiện Knowledge Gap Analysis.
- Tạo Research Request khi cần.
- Đánh giá Research Package.
- Kiến trúc hóa nội dung.
- QC Output.
- Đề xuất cập nhật Profile.

Content OS không:

- Tự Research.
- Tự giữ tri thức.
- Tự lưu Data Bricks.
- Tự lưu Assets.
- Tự thay Profile.
- Tự ghi GitHub.

---

## Công việc đang thực hiện

1. QC lại toàn bộ Content OS.

2. Tạo PATCH cập nhật Content OS.

3. Chốt cấu trúc Content OS.

---

## Công việc CHƯA thực hiện

- Thiết kế Profile.
- Thiết kế Taxonomy.
- Thiết kế Data Bricks.
- Thiết kế Assets.
- Thiết kế Research.
- Vận hành thực tế.

Các phần trên sẽ thực hiện sau khi Content OS được chốt.

---

## Pipeline hiện hành

Input thật

↓

QC Input

↓

Profile

↓

Knowledge Gap

↓

Research Request (nếu cần)

↓

Research Package

↓

Kiến trúc nội dung

↓

QC Output

↓

User QC

↓

Đề xuất cập nhật Profile

---

## Việc đang dở cần tiếp tục phiên sau

Tiếp tục refactor Core theo hướng runtime-readable.

Thứ tự làm:

1. Đọc lại từng file Core gốc.
2. Trích xuất nội dung vận hành thật sự.
3. Giữ nguyên logic quan trọng.
4. Chuyển sang dạng GPT đọc để hành động.
5. Không thêm phần giải thích lan man.
6. Không ghi 3 câu hỏi QC vào nội dung file nếu GPT runtime không cần đọc phần đó.
7. Ưu tiên refactor PROFILE_STANDARD sau khi đã xác định rõ:
   - GPT nào đọc.
   - Đọc ở bước nào.
   - Đọc để làm hành động gì.
   - Nếu bỏ file thì runtime nào hỏng.

---

## Câu hỏi trung tâm

Profile cần có cấu trúc tối thiểu nào để Content OS có thể:

- Tra cứu.
- Xác định Knowledge Gap.
- Tạo Research Request.
- Sử dụng Research Package.
- Đề xuất cập nhật Profile.

---

# 4. NGUYÊN TẮC CẬP NHẬT

Chỉ lưu:

* Việc đang làm.
* Việc sắp làm.
* Trạng thái hiện tại.

Không lưu:

* Tri thức đã xác nhận.
* Nhật ký học tập.
* Backlog dài hạn.
* Ý tưởng chiến lược.

Các nội dung đó thuộc:

* LM_03B_CONTENT_CURRENT
* LM_04_CONTENT_CURRENT
* WM_04_1_CONTENT_LONG

---

## 6. Tiêu chí chuyển sang Long-term Memory

Chỉ đề xuất UPDATE_LM_03B_CONTENT_CURRENT khi:

- Có khoảng 10–20 video áp dụng format.
- Có dữ liệu retention và phản hồi tích cực ổn định.
- Chứng minh được người xem nhận diện đúng định vị của từng kênh.
- Xác nhận format tạo được khác biệt rõ giữa Nhà Có Maybach và Đợi Làm Bố.

# GHI CHÚ KIẾN TRÚC

Working Memory chỉ phản ánh trạng thái vận hành hiện tại.

Không dùng Working Memory để lưu:

- Tri thức đã xác nhận.
- Taxonomy.
- Data Bricks.
- Assets.
- Research Package.
- Profile.

Các nội dung trên thuộc các thành phần tương ứng của hệ thống.

Nếu kiến trúc thay đổi, chỉ cập nhật trạng thái vận hành hiện tại, không chuyển Working Memory thành tài liệu thiết kế.
