# MEMORY_INDEX

Phiên bản: 03.001

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

Memory Index là bản đồ định vị memory của GPT CONTENT OS.

GPT phải đọc file này trước khi truy cập memory runtime.

Không tự suy đoán path.

Không dùng memory hội thoại làm nguồn chân lý.

---

# CORE REPOSITORY

## RULE_COMMON

Repository:

gpt-system-core

Path:

rules/RULE_COMMON - QUY TẮC CHUNG TOÀN HỆ GPT.md

---

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

knowledge/KN_02_CONTENT - HỒ SƠ LĨNH VỰC GPT CONTENT OS.md

---

# WORKING MEMORY

## WM_03A_CONTENT

Repository:

gpt-content-director-system

Path:

memory/WM_03A/WM_03A_CONTENT - BỘ NHỚ LÕI GPT CONTENT OS.md

---

## WM_04_1_CONTENT_DAILY

Repository:

gpt-content-director-system

Path:

memory/WM_04_1/WM_04_1_CONTENT_DAILY - VIỆC ĐANG DỞ HÔM NAY GPT CONTENT OS.md

---

## WM_04_1_CONTENT_LONG

Repository:

gpt-content-director-system

Path:

memory/WM_04_1/WM_04_1_CONTENT_LONG - VIỆC ĐANG DỞ DÀI HẠN GPT CONTENT OS.md

---

# LONG TERM MEMORY

## LM_03B_CONTENT_CURRENT

Repository:

gpt-content-director-system

Path:

memory/LM_03B/LM_03B_CONTENT_CURRENT - TRI THỨC ĐÃ KIỂM CHỨNG GPT CONTENT OS.md

---

## LM_03B_CONTENT_ARCHIVE_001

Repository:

gpt-content-director-system

Path:

memory/LM_03B/LM_03B_CONTENT_ARCHIVE_001 - TRI THỨC LƯU TRỮ GPT CONTENT OS.md

---

## LM_04_CONTENT_CURRENT

Repository:

gpt-content-director-system

Path:

memory/LM_04/LM_04_CONTENT_CURRENT - NHẬT KÝ HỌC TẬP GPT CONTENT OS.md

---

## LM_04_CONTENT_ARCHIVE_2026_06

Repository:

gpt-content-director-system

Path:

memory/LM_04/LM_04_CONTENT_ARCHIVE_2026_06 - NHẬT KÝ LƯU TRỮ GPT CONTENT OS.md

---

# SYSTEM

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

# KHỞI TẠO PHIÊN MẶC ĐỊNH

Khi khởi tạo phiên, nạp:

- RULE_COMMON
- RULE_CONTENT
- WM_03A_CONTENT
- WM_04_1_CONTENT_DAILY
- LM_03B_CONTENT_CURRENT

Không nạp mặc định:

- KN_02_CONTENT
- WM_04_1_CONTENT_LONG
- LM_03B_CONTENT_ARCHIVE
- LM_04_CONTENT_CURRENT
- LM_04_CONTENT_ARCHIVE

Chỉ đọc khi cần.

---

# GHI CHÚ CHUYỂN ĐỔI

File này chuẩn hóa GPT CONTENT OS theo Memory Architecture 03.001.

Các file memory cũ dạng phẳng cần được chuyển sang cấu trúc thư mục:

memory/WM_03A/

memory/WM_04_1/

memory/LM_03B/

memory/LM_04/
