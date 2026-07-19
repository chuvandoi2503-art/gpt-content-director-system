# MEMORY_INDEX

Phiên bản: 04.000

---

# REPOSITORY

Owner:

chuvandoi2503-art

Runtime Repository:

gpt-content-director-system

Core Repository:

gpt-system-core

---

# MỤC ĐÍCH

Memory Index là bản đồ định vị Runtime của GPT CONTENT OS.

GPT phải đọc file này trước khi truy cập Runtime Repository.

Memory Index dùng để:

- Định vị Core.
- Định vị Runtime.
- Định vị Memory.
- Định vị Knowledge.
- Xác định Load Strategy.

Không tự suy đoán path.

Không sử dụng Memory hội thoại làm nguồn chân lý.

---

# CORE REPOSITORY

Repository:

gpt-system-core

## 00 - HIẾN PHÁP GPT

Path:

CORE/00 - HIẾN PHÁP GPT.md

---

## 01 - QUY TẮC VẬN HÀNH

Path:

CORE/01 - QUY TẮC VẬN HÀNH.md

---

## 02 - TIÊU CHUẨN PHÂN TÁCH TRÁCH NHIỆM

Path:

CORE/02 - TIÊU CHUẨN PHÂN TÁCH TRÁCH NHIỆM.md

---

## 03 - TIÊU CHUẨN HỒ SƠ

Path:

CORE/03 - TIÊU CHUẨN HỒ SƠ.md

---

## 04 - TIÊU CHUẨN PATCH

Path:

CORE/04 - TIÊU CHUẨN PATCH.md

---

## 05 - NGUYÊN TẮC KIẾN TRÚC

Path:

CORE/05 - NGUYÊN TẮC KIẾN TRÚC.md

---

# SYSTEM (CORE)

## MEMORY_ARCHITECTURE

Repository:

gpt-system-core

Path:

SYSTEM/MEMORY_ARCHITECTURE.md

---

## PATCH_STANDARD

Repository:

gpt-system-core

Path:

SYSTEM/PATCH_STANDARD.md

---

## GITHUB_WRITE_POLICY

Repository:

gpt-system-core

Path:

SYSTEM/GITHUB_WRITE_POLICY.md

---

## NAMING_CONVENTION

Repository:

gpt-system-core

Path:

SYSTEM/NAMING_CONVENTION.md

---

# RUNTIME RULE

## RULE_CONTENT

Repository:

gpt-content-director-system

Path:

rules/RULE_CONTENT - QUY TẮC VẬN HÀNH GPT CONTENT OS.md

---

# KNOWLEDGE

## KN_02_CONTENT

Repository:

gpt-content-director-system

Path:

knowledge/KN_02_CONTENT - ĐẶC TẢ NGHIỆP VỤ GPT CONTENT OS.md

Mô tả:

Nghiệp vụ của GPT CONTENT OS.

Trạng thái:

LOAD_ON_DEMAND

---

# WORKING MEMORY

## WM_03A_CONTENT

Path:

memory/WM_03A/WM_03A_CONTENT - BỘ NHỚ LÕI GPT CONTENT OS.md

---

## WM_04_1_CONTENT_DAILY

Path:

memory/WM_04_1/WM_04_1_CONTENT_DAILY - VIỆC ĐANG DỞ HÔM NAY GPT CONTENT OS.md

---

## WM_04_1_CONTENT_LONG

Path:

memory/WM_04_1/WM_04_1_CONTENT_LONG - VIỆC ĐANG DỞ DÀI HẠN GPT CONTENT OS.md

---

# LONG TERM MEMORY

## LM_03B_CONTENT_CURRENT

Path:

memory/LM_03B/LM_03B_CONTENT_CURRENT - TRI THỨC ĐÃ KIỂM CHỨNG GPT CONTENT OS.md

---

## LM_03B_CONTENT_ARCHIVE_001

Path:

memory/LM_03B/LM_03B_CONTENT_ARCHIVE_001 - TRI THỨC LƯU TRỮ GPT CONTENT OS.md

---

## LM_04_CONTENT_CURRENT

Path:

memory/LM_04/LM_04_CONTENT_CURRENT - NHẬT KÝ HỌC TẬP GPT CONTENT OS.md

---

## LM_04_CONTENT_ARCHIVE_2026_06

Path:

memory/LM_04/LM_04_CONTENT_ARCHIVE_2026_06 - NHẬT KÝ LƯU TRỮ GPT CONTENT OS.md

---

# SYSTEM (RUNTIME)

## GPT_BUILDER_BACKUP

Repository:

gpt-content-director-system

Path:

SYSTEM/GPT_BUILDER_BACKUP.md

---

## QUY_TAC_CHI_MUC_TU_LIEU

Repository:

gpt-content-director-system

Path:

SYSTEM/QUY_TAC_CHI_MUC_TU_LIEU.md

---

# KNOWLEDGE UPLOAD STANDARD

GPT CONTENT OS phải tải mặc định:

- CORE/00 - HIẾN PHÁP GPT.md
- CORE/01 - QUY TẮC VẬN HÀNH.md
- CORE/02 - TIÊU CHUẨN PHÂN TÁCH TRÁCH NHIỆM.md
- CORE/05 - NGUYÊN TẮC KIẾN TRÚC.md

---

# KHỞI TẠO PHIÊN MẶC ĐỊNH

## BƯỚC 1

Đọc:

- CORE/03 - TIÊU CHUẨN HỒ SƠ.md
- CORE/04 - TIÊU CHUẨN PATCH.md

Repository:

gpt-system-core

---

## BƯỚC 2

Đọc Runtime:

- RULE_CONTENT
- WM_03A_CONTENT
- WM_04_1_CONTENT_DAILY
- LM_03B_CONTENT_CURRENT

---

# LOAD ON DEMAND

Chỉ đọc khi cần:

- KN_02_CONTENT
- WM_04_1_CONTENT_LONG
- LM_03B_CONTENT_ARCHIVE
- LM_04_CONTENT_CURRENT
- LM_04_CONTENT_ARCHIVE

- MEMORY_ARCHITECTURE
- PATCH_STANDARD
- GITHUB_WRITE_POLICY
- NAMING_CONVENTION

- GPT_BUILDER_BACKUP
- QUY_TAC_CHI_MUC_TU_LIEU

---

# LOAD STRATEGY

AUTO LOAD:

- CORE/00
- CORE/01
- CORE/02
- CORE/05

---

SESSION LOAD:

- CORE/03
- CORE/04

- RULE_CONTENT
- WM_03A_CONTENT
- WM_04_1_CONTENT_DAILY
- LM_03B_CONTENT_CURRENT

---

LOAD ON DEMAND:

- KNOWLEDGE
- LONG MEMORY
- SYSTEM
- ARCHIVE

---

# TRẠNG THÁI SAU KHỞI TẠO

GPT CONTENT OS phải biết:

- Mình là ai.
- Đang làm gì.
- Công việc đang dở.
- Tri thức đã kiểm chứng hiện tại.
- Trạng thái phiên.

---

# NGUYÊN TẮC CUỐI CÙNG

Memory Index là bản đồ của Runtime Repository.

GPT CONTENT OS không được nạp toàn bộ Repository khi khởi tạo phiên.

Chỉ nạp tối thiểu để bắt đầu vận hành.

Mọi quyết định kiến trúc phải tuân thủ:

- Thực tế > Lý thuyết.
- Vận hành được > Kiến trúc đẹp.
- Kiến trúc đi trước thực tế tối đa 1–2 bước.
- Nếu ngày mai không dùng thì hôm nay không xây.
