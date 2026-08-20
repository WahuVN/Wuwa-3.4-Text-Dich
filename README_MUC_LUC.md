# 📚 TỔNG HỢP TOÀN BỘ TEXT DỊCH VIỆT HÓA WUTHERING WAVES (3.4 - 3.5 - 3.6)

Kho lưu trữ chính thức toàn bộ cơ sở dữ liệu bản dịch, text gốc, bảng tra cứu đối chiếu song ngữ 4 thứ tiếng, từ điển thuật ngữ chuẩn hóa và báo cáo kiểm soát chất lượng (QC) của dự án **WAHU Localization (WuwaVH)**.

---

## 🗂 CẤU TRÚC MỤC LỤC CHI TIẾT

```
Wuwa-Text-Dich/
├── 01_BanDich_3.4/                      # Dữ liệu bản dịch phiên bản 3.4
│   ├── 01_BanDich_Chinh_VI_HV/          # 11 Part bản dịch chính (chuẩn hóa đầy đủ)
│   ├── 02_BanDich_Full_Gop/             # File gộp toàn bộ 11 Part (104 MB)
│   ├── 03_BanDich_Tach_VI_va_HV/        # 22 File tách riêng tiếng Việt thuần & Hán Việt
│   └── 04_Text_Goc_3.4/                 # 19 Part text gốc từ game
│
├── 02_BanDich_3.5/                      # Dữ liệu bản dịch phiên bản 3.5
│   ├── 01_BanDich_Chinh_VI_HV/          # 10 Part bản dịch chính 3.5 (Part 01 -> Part 10)
│   ├── 02_BanDich_Full_Gop/             # File gộp toàn bộ 10 Part 3.5 (11.1 MB)
│   ├── 03_BanDich_Tach_VI_va_HV/        # 20 File tách riêng tiếng Việt & Hán Việt
│   ├── 04_Text_Goc_3.5/                 # 10 Part text gốc 3.5
│   └── 05_Zip_Goc_3.5/                  # File nén zip trọn bộ gốc 3.5
│
├── 03_BanDich_3.6/                      # Dữ liệu bản dịch phiên bản 3.6 (Mới nhất)
│   ├── 01_BanDich_Chinh_VI_HV/          # 10 Part bản dịch chính 3.6 (Part 01 -> Part 10)
│   ├── 02_BanDich_Full_Gop/             # File gộp toàn bộ 10 Part 3.6 (4.2 MB)
│   ├── 03_BanDich_Tach_VI_va_HV/        # 20 File tách riêng tiếng Việt & Hán Việt 3.6
│   ├── 04_ChuaDich_Va_BoSung/           # Dữ liệu quét câu thoại và text cần dịch tiếp
│   └── 05_BaoCao_SoSanh_3.6/            # Báo cáo đối soát chênh lệch gốc và VH 3.6
│
├── 04_DoiChieu_Va_TraCuu/               # Cơ sở dữ liệu đối chiếu 44 phân khu game
│   ├── 01_DoiChieu_4Ngu_TSV/            # 44 file TSV song ngữ 4 thứ tiếng (CN, VI, EN, JP)
│   ├── 02_Anh_EN_TSV/                   # 44 file TSV tiếng Anh chuẩn
│   └── 03_TongQuan_TSV/                 # Bảng tổng quan phân bổ dòng & dung lượng
│
├── 05_BaoCao_QC_Va_XungHo/              # Báo cáo chất lượng và chuẩn hóa xưng hô
│   ├── 01_BaoCao_QC_DichThuat/          # Báo cáo soát lỗi và timeline dịch thuật
│   ├── 02_RaSoat_XungHo_ChiTiet/        # Chi tiết rà soát xưng hô Rover & nhân vật
│   ├── 03_TomTat_Thoai_DaSua/           # Nhật ký tổng hợp các câu thoại đã chỉnh sửa
│   └── 04_Khoa_Ten_ThuatNgu/            # Từ điển 7.163 thuật ngữ và quy chuẩn khóa tên
│
└── 06_Text_Moi_CapNhat/                 # Text cập nhật nóng mới nhất
    └── moi_part01.txt
```

---

## 📊 THỐNG KÊ DỮ LIỆU TỪNG PHIÊN BẢN

| Phiên bản | Số lượng câu | Cốt truyện & Thoại | Hệ thống & UI | Kỹ năng & Item | Trạng thái |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Bản dịch 3.4** | **309.391 câu** | 161.428 câu | 67.210 câu | 80.753 câu | Đầy đủ 11 Part & Full gộp |
| **Bản dịch 3.5** | **23.804 câu** | 14.506 câu | 3.861 câu | 5.437 câu | Đầy đủ 10 Part & Full gộp |
| **Bản dịch 3.6** | **17.935 câu** | 8.862 câu | 3.190 câu | 5.883 câu | Đầy đủ 10 Part & Full gộp |
| **Thuật ngữ (Glossary)** | **7.163 mục** | Nhân vật & NPC | Thuật ngữ game | Địa danh & Chiêu thức | Xuất CSV & TSV chuẩn |

---

## 🔍 HƯỚNG DẪN SỬ DỤNG VÀ TRA CỨU

1. **Dùng trực tiếp cho công cụ WAHU Studio:**
   - Tất cả dữ liệu đã được index hóa sẵn trong file `project.db`.
   - Có thể lọc theo từng phiên bản (`3.4`, `3.5`, `3.6`) và 5 Macro Categories (`📖 Cốt truyện`, `👤 Nhân vật`, `🗺️ Thế giới`, `⚔️ Kỹ năng`, `⚙️ Giao diện`).
2. **Dùng tra cứu thủ công / Biên dịch ngoài:**
   - Mở file trong thư mục `04_DoiChieu_Va_TraCuu/01_DoiChieu_4Ngu_TSV` bằng Excel hoặc Notepad++ để tra cứu song song 4 ngôn ngữ (Trung 🇨🇳 - Việt 🇻🇳 - Anh 🇬🇧 - Nhật 🇯🇵).
   - Tra cứu thuật ngữ chuẩn trong `05_BaoCao_QC_Va_XungHo/04_Khoa_Ten_ThuatNgu/WuwaVH_Glossary.csv`.
