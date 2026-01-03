# 🚀 Beytrium

<div align="center">

![Beytrium Banner](https://via.placeholder.com/1200x300?text=Beytrium+Banner) 
<!-- Replace with actual banner if available -->

**Beykent Üniversitesi Bilimsel Araştırma ve Teknoloji Kulübü**<br>
*Modern, Dinamik ve Yenilikçi Web Platformu*

[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)

[🌐 Canlı Demo](https://beytrium.vercel.app) · [🐛 Hata Bildir](https://github.com/yagizturkmen-ceng/beytrium-v1.4/issues) · [✨ Özellik İste](https://github.com/yagizturkmen-ceng/beytrium-v1.4/issues)

</div>

---

## 📖 Hakkında

**Beytrium**, Beykent Üniversitesi öğrencileri ve teknoloji meraklıları için geliştirilmiş modern bir topluluk platformudur. 
**Neobrutalism** tasarım anlayışıyla hazırlanan arayüzü, kullanıcı dostu deneyimi ve güçlü altyapısıyla kulüp etkinliklerini, duyurularını ve projelerini tek bir çatı altında toplar.

## ✨ Özellikler

| Özellik | Açıklama |
|---------|----------|
| 🎨 **Modern Tasarım** | Neobrutalism tarzı, canlı renkler ve cesur tipografi. |
| ⚡️ **Yüksek Performans** | Vite tabanlı build sistemi ile ışık hızında yükleme süreleri. |
| 📱 **Tam Responsive** | Mobil, tablet ve masaüstü cihazlarla %100 uyumlu. |
| 🔒 **Güvenli Altyapı** | TypeScript ile tip güvenliği ve güvenli backend yapısı. |
| 📧 **İletişim Formu** | Nodemailer entegrasyonu ile hızlı iletişim imkanı. |
| 🛠 **Kolay Yönetim** | Geliştirici dostu kod yapısı ve detaylı dokümantasyon. |

## 🛠️ Teknolojiler

### Frontend
*   **Core:** React 18, TypeScript
*   **Build Tool:** Vite
*   **Styling:** Tailwind CSS
*   **Routing:** React Router DOM
*   **Icons:** React Icons

### Backend
*   **Runtime:** Node.js
*   **Framework:** Express.js
*   **Media:** Nodemailer
*   **Security:** CORS, Dotenv

## 🚀 Kurulum & Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin.

### Ön Gereksinimler
*   Node.js (v16+)
*   npm veya yarn

### 1. Projeyi Klonlayın
```bash
git clone https://github.com/yagizturkmen-ceng/beytrium-v1.4.git
cd beytrium-v1.4
```

### 2. Bağımlılıkları Yükleyin
```bash
# Tüm proje bağımlılıklarını tek komutla yükleyin
npm run install:all
```

### 3. Çevresel Değişkenleri (Environment Variables) Ayarlayın
`server` klasörü içinde `.env` dosyası oluşturun:
```env
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-password
RECEIVER_EMAIL=receiver@example.com
PORT=3001
```

### 4. Uygulamayı Başlatın
```bash
# Frontend ve Backend'i aynı anda başlatın (Development Modu)
npm run dev:all
```
*   **Frontend:** `http://localhost:5173`
*   **Backend:** `http://localhost:3001`

## 📂 Proje Yapısı

```
beytrium/
├── 📁 src/
│   ├── 📁 _components/   # Bölümlere ayrılmış UI bileşenleri
│   ├── 📁 assets/        # Görseller, fontlar ve ikonlar
│   ├── 📁 pages/         # Sayfa düzenleri ve rotalar
│   └── 📄 main.tsx       # Uygulama giriş noktası
├── 📁 server/            # Backend API servisi
│   ├── 📄 index.js       # Server giriş noktası
│   └── 📄 .env           # (Oluşturulmalı) Environment değişkenleri
└── 📄 package.json       # Proje konfigürasyonu
```

## 🤝 Katkıda Bulunma

Açık kaynağı seviyoruz! Katkıda bulunmak için:

1.  Bu depoyu fork'layın.
2.  Yeni bir feature branch oluşturun (`git checkout -b feature/YeniOzellik`).
3.  Değişikliklerinizi commit'leyin (`git commit -m 'Yeni özellik eklendi'`).
4.  Branch'inizi push'layın (`git push origin feature/YeniOzellik`).
5.  Bir Pull Request oluşturun.

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakınız.

---

<div align="center">
  Made with ❤️ by <b>Beytrium Team</b>
</div>
