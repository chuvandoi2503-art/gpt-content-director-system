# QUY TẮC CHỈ MỤC TƯ LIỆU

Phiên bản: 01.001
Trạng thái: Áp dụng hệ thống

---

# 1. MỤC TIÊU

Quy tắc này tồn tại để:

* Tìm lại tư liệu nhanh.
* Giảm thời gian tìm video cũ.
* Giảm thời gian quay lại cảnh đã có.
* Không làm tăng công quản lý dữ liệu.
* Không làm phình bộ nhớ GPT.

Mục tiêu cuối:

Tìm được tư liệu cần thiết trong vài phút thay vì vài giờ.

---

# 2. NGUYÊN TẮC LÕI

Không quản lý mọi asset.

Chỉ quản lý asset đáng quản lý.

Không quản lý mọi video.

Chỉ quản lý video có giá trị tái sử dụng cao.

Nguyên tắc:

Chi phí quản lý

<

Giá trị asset tạo ra

Nếu chi phí quản lý lớn hơn giá trị sử dụng lại:

Không quản lý.

---

# 3. GPT KHÔNG LƯU ASSET

GPT không nhớ:

* Video nào.
* Cảnh nào.
* File nào.
* Link Drive nào.

GPT chỉ nhớ:

* Cần loại tư liệu gì.
* Nên tìm loại tư liệu gì.
* Nên quay loại tư liệu gì.

Asset phải nằm ngoài GPT.

---

# 4. PHÂN TẦNG LƯU TRỮ

GitHub

↓

Tri thức

↓

Rule

↓

Memory

---

Google Drive

↓

Video gốc

↓

Video render

↓

Ảnh

↓

Voice

↓

Tư liệu

---

Gemini

↓

Tìm kiếm asset

↓

Tra cứu asset

↓

Tìm bằng ngôn ngữ tự nhiên

---

# 5. QUY TẮC KHÔNG HỒI TỐ

Khi thay đổi:

* Tag.
* Quy tắc.
* Chỉ mục.

Chỉ áp dụng từ hiện tại trở đi.

Không quay lại sửa dữ liệu cũ.

Không mất thời gian dọn lịch sử.

Nguyên tắc:

Tiếp tục tiến lên.

Không quay lại sửa quá khứ.

---

# 6. QUY TẮC ĐẶT TÊN FILE

Cấu trúc:

YYYY-MM-DD_NHOM_NOIDUNG_TUKHOA1_TUKHOA2_TUKHOA3

Ví dụ:

2026-06-20_BDV_HaiLa_GhepLa_DongGoi.mp4

2026-06-20_BDV_LapDat_PhongKhach.mp4

2026-06-20_DBD_DonHang_DongGoi_23h.mp4

2026-06-20_NLCD_NgamLa_Ngay10.mp4

2026-06-20_MAYBACH_DanhRang_KhongNho.mp4

2026-06-20_KPMBD_GheTreEm_KhongHopTac.mp4

2026-06-20_GOCBO_BanXe_GheTreEm.mp4

---

# 7. CÓ CẦN ID RIÊNG CHO VIDEO KHÔNG?

KHÔNG.

GPT Content OS V1 không sử dụng ID riêng cho asset.

Lý do:

* Đã có ngày quay.
* Đã có nhóm nội dung.
* Đã có từ khóa.
* Đã có tìm kiếm Drive.
* Đã có Gemini.

Ví dụ:

Đủ tốt:

2026-06-20_BDV_HaiLa_GhepLa_DongGoi.mp4

Không cần:

ASSET_000154_2026-06-20_BDV_HaiLa_GhepLa_DongGoi.mp4

Việc thêm ID sẽ:

* Tăng độ dài tên file.
* Tăng công quản lý.
* Không tạo nhiều giá trị ở V1.

Nếu tương lai có trên 50.000 asset:

Được phép đánh giá lại.

Hiện tại:

Không dùng ID cho asset.

---

# 8. MÃ NHÓM NỘI DUNG

BDV

=

Bồ Đề Việt

---

DBD

=

Đợi Bồ Đề

---

NLCD

=

Nghề Lá Của Đợi

---

MAYBACH

=

Nhà Có Maybach

---

KPMBD

=

Không Phải Maybach Đâu

---

GOCBO

=

Góc Nhìn Của Bố

---

# 9. QUY TẮC TỪ KHÓA

Tên file nên có:

3-5 từ khóa chính.

Không nhồi quá nhiều từ khóa.

Ưu tiên:

* Dễ đọc.
* Dễ hiểu.
* Dễ tìm.

Ví dụ tốt:

2026-06-20_BDV_DongGoi_BuuCuc_DonHang.mp4

Ví dụ không tốt:

2026-06-20_BDV_DongGoi_BuuCuc_DonHang_KhachNhan_CamDien_LocLa_GhepLa_XuongLa.mp4

---

# 10. ASSET ĐÁNG QUẢN LÝ

Ví dụ:

* Hái lá.
* Ngâm lá.
* Tách lá.
* Xương lá.
* Ghép lá.
* Cắm điện.
* Đóng gói.
* Bưu cục.
* Lắp đặt.
* Không gian treo tranh đẹp.
* Câu nói đặc trưng của Maybach.
* Tình huống nuôi con khó quay lại.

Những asset này có khả năng dùng nhiều lần.

---

# 11. ASSET KHÔNG CẦN QUẢN LÝ

Ví dụ:

* Clip lỗi.
* Clip hỏng.
* Clip dùng một lần.
* Nội dung thời sự trong ngày.
* Nội dung dễ quay lại.

Không cần:

* Tag.
* Note.
* Chỉ mục riêng.

---

# 12. KHI NÀO CẦN NOTE

Chỉ tạo note khi:

Asset có giá trị tái sử dụng cao.

Ví dụ:

2026-06-20_BDV_DongGoi_BuuCuc_DonHang.md

Nội dung note:

Tên file:

2026-06-20_BDV_DongGoi_BuuCuc_DonHang

Mô tả:

Đóng gói tranh.

Mang ra bưu cục.

Gửi hàng cho khách.

Có thể dùng lại cho:

* Niềm tin mua hàng.
* Hậu trường.
* Quy trình gửi tranh.
* Nội dung ads.

---

# 13. TAG CHIẾN LƯỢC BAN ĐẦU

Hệ Bồ Đề:

* #haila
* #ngamla
* #xuongla
* #ghepla
* #camdien
* #donggoi
* #buucuc
* #lapdat
* #khachhang
* #phongkhach
* #phongtho

---

Hệ Gia Đình:

* #danhrang
* #ghetreem
* #tamtienganh
* #tulap
* #khonghoptac
* #connoi
* #gocnhinbo
* #tranhluan

---

# 14. DANH SÁCH TAG ĐƯỢC PHÉP THAY ĐỔI

Danh sách tag không cố định.

Có thể:

* Thêm.
* Bớt.
* Gộp.
* Xóa.

Khi vận hành thực tế.

Mục tiêu:

Giữ số lượng tag ít nhất có thể.

---

# 15. GEMINI + GOOGLE DRIVE

Định hướng V2:

Gemini trở thành công cụ tìm asset.

Ví dụ:

"Tìm cảnh đóng gói tranh."

"Tìm cảnh ghép lá."

"Tìm cảnh Maybach không chịu ngồi ghế."

"Tìm cảnh bưu cục."

"Tìm cảnh khách nhận tranh."

Mục tiêu:

Tìm bằng ngôn ngữ tự nhiên.

Không phụ thuộc hoàn toàn vào tag.

---

# 16. QUY TẮC CUỐI CÙNG

Nếu phải lựa chọn giữa:

Quản lý dữ liệu đẹp

hoặc

Làm nội dung nhiều hơn

Luôn ưu tiên:

Làm nội dung nhiều hơn.

Hệ thống tồn tại để hỗ trợ sản xuất nội dung.

Không phải để tạo thêm công việc quản lý.

---

# 17. QUAN HỆ VỚI MEMORY

ID chỉ tồn tại trong:

* Knowledge.
* Rule.
* Memory.

Ví dụ:

* KN_02_CONTENT
* RULE_CONTENT
* WM_03A_CONTENT
* WM_04_1_CONTENT
* LM_03B_CONTENT
* LM_04_CONTENT

Các ID này phục vụ:

* GitHub.
* MEMORY_INDEX.
* GPT Builder.
* GitHub Action.

Asset video không sử dụng hệ ID này.
