# PTM4C Landing Page

Website landing page untuk Paguyuban Tamiya Mini 4WD Cibinong (PTM4C).

## Fitur Website

### 🎯 Hero Section
- Background gambar dari `images/background.webp`
- Animasi AOS (Animate On Scroll)
- Call-to-action buttons yang menarik

### 📋 Tentang Komunitas
- Informasi lengkap tentang PTM4C
- Counter animasi untuk statistik
- Responsive design

### 🏆 Kompetisi
- **IDC (Indonesia Damper Class)** - Kompetisi dengan damper
- **STB (Standard Tamiya Box)** - Kompetisi parts standar
- Info jadwal dan cara daftar

### 📍 Lokasi
- Vivo Mall Sentul
- Link ke Google Maps: https://maps.app.goo.gl/q3gqGkXvxEMQkZBA8
- Informasi jam operasional dan fasilitas

### 📞 Kontak
- WhatsApp, Instagram, dan Email
- Panduan cara bergabung
- Form kontak interaktif

## Teknologi yang Digunakan

- **Bootstrap 5.3.2** - Framework CSS
- **Bootstrap Icons** - Icon library
- **AOS (Animate On Scroll)** - Scroll animations
- **Vanilla JavaScript** - Interaktivity
- **Progressive Web App** - Manifest.json support

## File Structure

```
public/
├── index.html              # Main landing page
├── favicon/               
│   ├── *.png             # Various favicon sizes
│   ├── manifest.json     # PWA manifest
│   └── browserconfig.xml # IE/Edge config
└── images/
    └── background.webp   # Hero background image
```

## Features

### 🎨 Design
- Modern gradient design dengan warna PTM4C (orange #ff6b00)
- Responsive untuk semua device
- Smooth scrolling dan hover effects
- Loading animations

### 🚀 Performance
- Optimized images (WebP format)
- CDN untuk Bootstrap dan icons
- Minimal JavaScript untuk fast loading
- Progressive Web App ready

### 📱 Mobile Friendly
- Fully responsive design
- Touch-friendly buttons
- Mobile-first approach
- Fast loading on mobile networks

## Cara Menggunakan

1. **Local Development**:
   - Buka file `index.html` di browser
   - Atau gunakan local server untuk development

2. **Production Deployment**:
   - Upload semua file ke web hosting
   - Pastikan struktur folder tetap sama
   - Website siap diakses

## Customization

### Mengubah Warna
Edit CSS variables di bagian `:root`:
```css
:root {
    --primary-color: #ff6b00;    /* Warna utama PTM4C */
    --secondary-color: #1a1a1a;  /* Warna sekunder */
    --accent-color: #ffd700;     /* Warna aksen */
}
```

### Mengubah Konten
- Edit teks langsung di file `index.html`
- Ganti gambar background di folder `images/`
- Update informasi kontak sesuai kebutuhan

### Menambah Section
1. Tambah section baru di HTML
2. Update navigation menu
3. Tambah smooth scroll untuk anchor link

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Contact Information

Untuk info lebih lanjut tentang PTM4C:
- 📍 **Lokasi**: Vivo Mall Sentul
- 📱 **WhatsApp**: +62 812-3456-7890
- 📧 **Email**: info@ptm4c.com
- 📷 **Instagram**: @ptm4c_official

---

**PTM4C** - Paguyuban Tamiya Mini 4WD Cibinong
*Built with ❤️ for Mini 4WD Community*