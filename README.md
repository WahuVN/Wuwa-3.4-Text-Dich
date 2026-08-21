# 🌸 Wuthering Waves — Toàn Bộ Dữ Liệu Text Dịch Việt Hóa & Đối Chiếu Đa Ngôn Ngữ

Kho lưu trữ chính thức toàn bộ cơ sở dữ liệu bản dịch tiếng Việt, text gốc đối chiếu 4 ngôn ngữ (**Trung 🇨🇳 - Anh 🇬🇧 - Nhật 🇯🇵 - Việt 🇻🇳**), từ điển thuật ngữ chuẩn hóa và hệ thống báo cáo kiểm soát chất lượng (QC) của dự án **WAHU Localization (WuwaVH)** cho tựa game **Wuthering Waves** (hỗ trợ các phiên bản **3.4**, **3.5**, **3.6** và cập nhật tiếp theo).

---

## 📊 THỐNG KÊ DỮ LIỆU TỔNG HỢP

| Phân loại | Số lượng | Chi tiết nội dung | Trạng thái & Định dạng |
| :--- | :---: | :--- | :--- |
| **Bản dịch 3.4** | **309.391 câu** | Cốt truyện, hội thoại, nhiệm vụ, hệ thống, UI, kỹ năng, vật phẩm | Đầy đủ 11 Part, File gộp Full & Tách VI/HV |
| **Bản dịch 3.5** | **23.804 câu** | Text mới & cập nhật của phiên bản 3.5 | Đầy đủ 10 Part, File gộp Full & Tách VI/HV |
| **Bản dịch 3.6** | **17.935 câu** | Text phiên bản 3.6 (Cốt truyện mới, sự kiện, kỹ năng) | Đầy đủ 10 Part, File gộp Full & Tách VI/HV |
| **Đối chiếu 44 Phân khu** | **44 Bảng TSV** | Phân loại theo cốt truyện chính/phụ, NPC, quái, phụ bản, UI... | Song ngữ 4 thứ tiếng (CN - EN - JP - VI) |
| **Thuật ngữ (Glossary)** | **7.163 mục** | Khóa tên nhân vật, NPC, quái vật, địa danh, chiêu thức, hệ thống | Chuẩn hóa song song bản VI & Hán Việt |
| **Báo cáo QC & Xưng hô** | **10+ Báo cáo** | Rà soát ngữ cảnh xưng hô Rover, timeline soát lỗi dịch thuật | Log chi tiết & danh sách key cần sửa |

---

## 🗂 CẤU TRÚC KHO LƯU TRỮ

```text
Wuwa-Text-Dich/
├── 01_BanDich_3.4/                      # Dữ liệu bản dịch phiên bản 3.4 (Tổng thể nền tảng)
│   ├── 01_BanDich_Chinh_VI_HV/          # 11 Part bản dịch chính (chuẩn hóa đầy đủ)
│   ├── 02_BanDich_Full_Gop/             # File gộp toàn bộ 11 Part (104 MB)
│   ├── 03_BanDich_Tach_VI_va_HV/        # 22 File tách riêng tiếng Việt thuần & Hán Việt
│   └── 04_Text_Goc_3.4/                 # 11 Part text gốc từ game
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

## 📌 QUY CHUẨN CẤU TRÚC ĐỊNH DẠNG TEXT DỊCH

Mỗi mục text được định danh duy nhất bằng cặp định danh database `@@ <dbfile>||<Bảng>||<key>` và đi kèm các dòng đối chiếu đa ngôn ngữ:

```text
@@ lang_multi_text.db||MultiText||Side_ZZDATE_1_33
CN: 借了一下黎叔的炉子，来尝尝吧。
EN: I borrowed Uncle Li's stove. Come on, give it a try.
JP: 黎おじさんのかまどを借りて作った。食べてみて。
VI: Mượn tạm bếp của chú Li, lại nếm thử xem.
HV: Mượn tạm bếp của chú Li, lại nếm thử xem.
```

- **CN:** Tiếng Trung gốc của game (*Source of Truth* cho câu thoại & ngữ nghĩa).
- **EN:** Tiếng Anh chính thức của game (Tham chiếu cấu trúc câu & thuật ngữ quốc tế).
- **JP:** Tiếng Nhật chính thức của game (Tham chiếu sắc thái biểu cảm & kính ngữ).
- **VI (Bản Tiếng Việt hiện đại):** Giữ nguyên tên nhân vật/địa danh theo chuẩn tiếng Anh/Quốc tế (*Rover*, *Jiyan*, *Jinhsi*, *Changli*, *Camellya*...).
- **HV (Bản Tiếng Việt Hán Việt):** Tên nhân vật/địa danh được chuyển âm Hán Việt chuẩn xác (*Lữ Khách*, *Kỵ Viêm*, *Kim Tịch*, *Trường Ly*, *Sơn Hoa*...).

---

## 🔍 HƯỚNG DẪN TRA CỨU VÀ KHAI THÁC

1. **Sử dụng cho công cụ dịch thuật WAHU Studio / Community:**
   - Dữ liệu tương thích hoàn toàn để import vào hệ cơ sở dữ liệu `project.db`.
   - Hỗ trợ lọc theo từng phiên bản (`3.4`, `3.5`, `3.6`) và 5 Phân loại Macro:
     - 📖 **Cốt truyện & Nhiệm vụ**
     - 👤 **Nhân vật & Hội thoại**
     - 🗺️ **Thế giới & Địa danh**
     - ⚔️ **Kỹ năng & Vũ khí / Vật phẩm**
     - ⚙️ **Giao diện người dùng (UI / Hệ thống)**

2. **Tra cứu thủ công qua bảng TSV / Excel:**
   - Sử dụng thư mục `04_DoiChieu_Va_TraCuu/01_DoiChieu_4Ngu_TSV/` để mở trực tiếp bằng Excel, Google Sheets, hoặc Notepad++ để đối chiếu song song 4 ngôn ngữ theo từng chủ đề.

3. **Quy chuẩn từ điển thuật ngữ:**
   - Tra cứu file `05_BaoCao_QC_Va_XungHo/04_Khoa_Ten_ThuatNgu/WuwaVH_Glossary.csv` (hoặc `.tsv`) để đảm bảo tính nhất quán thuật ngữ cho toàn bộ dự án.

---

## 🔗 HỆ SINH THÁI DỰ ÁN WAHU LOCALIZATION

- **Launcher cài đặt tự động:** [VHWuWa Launcher Releases](https://github.com/WahuVN/wuwa-vietnamese-launcher/releases/latest)
- **Repository Tool & Source Code:** [WuwaVH GitHub](https://github.com/WahuVN/WuwaVH)
- **Kho dữ liệu Text Dịch:** [Wuwa-Text-Dich GitHub](https://github.com/WahuVN/Wuwa-Text-Dich)

