# 🛡️ NERV TACTICAL INTERFACE — EVANGELION CINEMATIC REDESIGN

> *"GOD'S IN HIS HEAVEN. ALL'S RIGHT WITH THE WORLD."*  
> **特務機関 NERV // TOKYO-3 GEOFRONT CENTRAL DOGMA**

Dự án giao diện điện ảnh phong cách **NERV (Neon Genesis Evangelion)**, nâng cấp toàn diện website từ repository `vintagechoi00/NERV`.

---

## 🌟 TÍNH NĂNG NỔI BẬT (CINEMATIC FEATURES)

### 1. Huy hiệu NERV Vector & Trích dẫn Robert Browning
- Logo NERV chuẩn tỉ lệ hình học với lá vả nửa vầng (fig leaf) đỏ cam.
- Câu châm ngôn huyền thoại vòng cung: *"GOD'S IN HIS HEAVEN. ALL'S RIGHT WITH THE WORLD."*
- Tích hợp kho tư liệu NERV Archive hiển thị đầy đủ các thời kỳ (1995 Original TV, Rebuild 1.0/2.0/3.0, WILLE).

### 2. Hệ thống Evangelion Units 00, 01, 02 (Interactive Hangar)
- **EVA-01 TEST TYPE (初号機)**: Tông màu tím & xanh neon dạ quang (Toxic Green), Pilot Shinji Ikari, Sync Rate 91.4%.
- **EVA-02 PRODUCTION MODEL (弐号機)**: Tông màu đỏ thắm (Crimson Blood Red) & vàng cam, Pilot Asuka Langley, Sync Rate 84.8%.
- **EVA-00 PROTO TYPE (零号機)**: Tông màu vàng cam an toàn (Hazard Gold) & xanh lam, Pilot Rei Ayanami, Sync Rate 72.3%.
- **Đổi theme động (Dynamic Theme Switching)**: Bấm chọn bất kỳ Eva Unit nào để chuyển đổi toàn bộ màu sắc, ánh sáng và hiệu ứng của trang web.

### 3. Tương tác màn chắn AT-Field (Interactive Absolute Terror Field)
- Nền Canvas đa tầng kết xuất các khối bát giác năng lượng màu vàng kim.
- Khi người dùng click chuột hoặc chạm màn hình, các vòng sóng AT-Field chấn động phát tán chân thực.

### 4. Thanh Tác chiến Tokyo-3 GeoFront & Hệ thống MAGI
- Đồng hồ quân sự thời gian thực: `TOKYO-3: HH:MM:SS JST`.
- Tình trạng siêu máy tính MAGI 3/3 (MELCHIOR-1, BALTHASAR-2, CASPER-3 đồng thuận).
- Nút kích hoạt báo động khẩn cấp **"EMERGENCY DRILL"** (Phát hiện Angel, Blood Type Blue).

### 5. Bộ tổng hợp âm thanh Synth SFX (Web Audio API)
- 100% âm thanh điện tử sci-fi nguyên bản không cần tải file MP3 ngoài.
- Hiệu ứng tiếng chip phím NERV terminal, tiếng chuông xác nhận MAGI, tiếng rung tần số AT-Field và còi báo động khẩn cấp.
- Có nút bật/tắt âm thanh (SFX Mute/Unmute).

---

## 📁 CẤU TRÚC FILE

```
nerv-web/
├── index.html                                                                 # Toàn bộ mã nguồn trang web cinematic
├── nerv-logos.webp                                                            # Ảnh tư liệu logo NERV
├── i-love-these-logos-spoilers-for-both-original-and-rebuilds-v0-eftjy5swogq71.webp # Bản sao tương thích với repo GitHub
└── README.md                                                                  # Tài liệu dự án
```

---

## 🚀 HƯỚNG DẪN CẬP NHẬT LÊN GITHUB

Để đưa giao diện mới này lên repository `https://github.com/vintagechoi00/NERV`:

1. **Cách 1: Tải trực tiếp qua trình duyệt web trên GitHub**
   - Vào [https://github.com/vintagechoi00/NERV](https://github.com/vintagechoi00/NERV).
   - Chọn file `index.html`, bấm biểu tượng chiếc bút **Edit this file** (hoặc chọn **Add file -> Upload files**).
   - Dán toàn bộ nội dung file [index.html](file:///C:/Users/huynh/.gemini/antigravity/scratch/nerv-web/index.html) mới này vào và bấm **Commit changes**.

2. **Cách 2: Sử dụng Git trên máy tính**
   ```bash
   cd "C:\Users\huynh\.gemini\antigravity\scratch\nerv-web"
   git init
   git remote add origin https://github.com/vintagechoi00/NERV.git
   git add index.html
   git commit -m "feat: cinematic NERV overhaul with EVA 00, 01, 02 and AT-Field engine"
   git push -u origin main
   ```
