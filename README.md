# 🐝 BeeHero 2026 — Ice Climber Endless Mode

> **Game dành cho sinh viên FPT Polytechnic**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-2D-blue)

## 🎮 Giới thiệu

BeeHero 2026 là game **Ice Climber phiên bản Endless Mode**, được xây dựng hoàn toàn bằng **HTML5 Canvas + JavaScript** thuần — không cần framework hay cài đặt gì thêm.

Game lấy cảm hứng từ tựa game kinh điển **Ice Climber** trên NES, với chế độ chơi vô tận — leo càng cao, điểm càng nhiều!

## 🕹️ Cách chơi

| Phím | Hành động |
|------|-----------|
| `←` `→` hoặc `A` `D` | Di chuyển trái/phải |
| `X` hoặc `Space` | Nhảy |
| `Enter` | Chơi lại (khi Game Over) |

### Luật chơi
- **Phá gạch**: Nhảy lên đập đầu vào gạch phía trên để phá (gạch màu nhạt)
- **Gạch cứng**: Một số viên gạch không thể phá được (sprite riêng theo mùa)
- **Đám mây**: Một số tầng có đám mây di chuyển thay vì gạch — đứng lên để leo tiếp
- **4 mùa**: Cảnh vật thay đổi theo mùa (Xuân → Hạ → Thu → Đông) mỗi 10 tầng
- **Độ khó tăng dần**: Càng lên cao, gạch cứng và khoảng trống xuất hiện nhiều hơn

## 🚀 Chạy game

Chỉ cần mở file `index.html` trong trình duyệt — **không cần server**!

```
Mở index.html bằng Chrome / Edge / Firefox
```

Hoặc deploy lên GitHub Pages để chơi online.

## 📁 Cấu trúc dự án

```
BeeHero2026-main/
├── index.html              # Toàn bộ game (HTML + CSS + JS)
└── assets/
    ├── sprites/            # Hình ảnh sprite
    │   ├── SpriteSheetTweaked.png  # Sprite chính (nhân vật, gạch, mây)
    │   ├── bee.png         # Logo Bee Hero
    │   ├── school.png      # Hình trường
    │   ├── water_tile.png  # Ô nước
    │   └── side_wall_*.png # Tường 2 bên theo mùa
    └── audio/              # Âm thanh
        ├── Background.wav  # Nhạc nền
        ├── Jump.wav        # Hiệu ứng nhảy
        ├── BreakBrick.wav  # Hiệu ứng phá gạch
        └── ...
```

## ✨ Tính năng

- 🏔️ **Endless Mode** — chơi mãi không hết tầng
- 🌸☀️🍂❄️ **4 mùa** thay đổi cảnh vật
- ☁️ **Đám mây di chuyển** — platform động giống game gốc
- 🧱 **Gạch unbreakable** với sprite riêng theo mùa
- 🏆 **Bảng xếp hạng** và **chat nhóm** real-time
- 🎵 **Âm thanh** đầy đủ
- 📱 **Retro pixel art** phong cách NES

## 👨‍🎓 Thông tin

- **Dành cho**: Sinh viên FPT Polytechnic
- **Môn học**: Lập trình Web / Game Development
- **Công nghệ**: HTML5 Canvas, Vanilla JavaScript, CSS3
- **Năm**: 2026

---

*Made with ❤️ by FPT Polytechnic Students*
