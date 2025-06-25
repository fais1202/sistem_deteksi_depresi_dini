# 🧠 MoodGuard AI - Sistem Deteksi Dini Depresi

![MoodGuard AI](https://img.shields.io/badge/MoodGuard-AI-blue?style=for-the-badge&logo=brain&logoColor=white)
![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/status-Development-yellow?style=for-the-badge)

## 📋 Deskripsi Proyek

**MoodGuard AI** adalah sistem berbasis kecerdasan buatan yang dirancang untuk mendeteksi tanda-tanda awal depresi melalui analisis pola penggunaan smartphone. Sistem ini menggunakan pembelajaran mesin untuk menganalisis berbagai metrik digital dan memberikan intervensi dini yang dapat membantu pencegahan dan penanganan masalah kesehatan mental.

### 🎯 Tujuan Utama
- Deteksi dini tanda-tanda depresi melalui pola digital
- Memberikan rekomendasi intervensi yang personal
- Meningkatkan kesadaran kesehatan mental masyarakat
- Menyediakan alat bantu untuk profesional kesehatan mental

## ✨ Fitur Utama

### 🔍 Analisis Pola Digital
- **Waktu Layar**: Monitoring durasi penggunaan smartphone harian
- **Frekuensi Aplikasi**: Analisis pola membuka dan menutup aplikasi
- **Penggunaan Malam**: Deteksi gangguan pola tidur
- **Aktivitas Sosial Media**: Evaluasi konsumsi konten digital
- **Pola Interaksi**: Klasifikasi perilaku penggunaan (normal, kompulsif, menarik diri)

### 🧠 Machine Learning Engine
- Algoritma klasifikasi berbasis risiko
- Analisis multifaktor dengan bobot dinamis
- Prediksi tingkat kepercayaan hasil
- Pembelajaran adaptif berdasarkan feedback

### 📱 Interface Pengguna
- Dashboard interaktif dan responsif
- Visualisasi data real-time
- Slider kontrol untuk input parameter
- Hasil analisis dengan coding warna
- Rekomendasi personal berbasis AI

### 🔔 Sistem Intervensi
- **Risiko Rendah**: Rekomendasi preventif
- **Risiko Sedang**: Saran konseling dan perubahan perilaku
- **Risiko Tinggi**: Rujukan profesional dan hotline krisis

## 🚀 Teknologi yang Digunakan

### Frontend
- **HTML5**: Struktur aplikasi web
- **CSS3**: Styling dengan gradient dan animasi modern
- **JavaScript ES6+**: Logika aplikasi dan interaktivitas
- **Responsive Design**: Mendukung berbagai ukuran layar

### AI/ML Framework (Rencana Pengembangan)
- **TensorFlow.js**: Machine learning di browser
- **Python**: Backend processing dengan scikit-learn
- **Node.js**: API server
- **MongoDB**: Database untuk menyimpan data pengguna

### Design Patterns
- **Progressive Web App (PWA)**: Akses offline
- **Component-Based**: Modular dan maintainable
- **Responsive First**: Mobile-friendly design

## 📊 Metodologi AI

### Data Input
```javascript
{
  smartphone_usage: {
    screen_time: Number,        // Jam per hari
    app_opens: Number,          // Frekuensi harian
    night_usage: Number,        // Jam penggunaan malam
    social_media: Number,       // Jam di sosial media
    usage_pattern: String       // normal/compulsive/withdrawn
  },
  personal_info: {
    age: Number,
    gender: String,
    stress_level: Number,       // Skala 1-10
    sleep_quality: String,      // excellent/good/fair/poor
    physical_activity: String   // active/moderate/inactive
  }
}
```

### Algoritma Scoring
1. **Analisis Multifaktor**: Setiap parameter diberi bobot berdasarkan penelitian
2. **Normalisasi**: Skor dinormalisasi ke skala 0-100
3. **Klasifikasi Risiko**: 
   - 0-30: Risiko Rendah
   - 31-60: Risiko Sedang  
   - 61-100: Risiko Tinggi
4. **Confidence Level**: Tingkat kepercayaan hasil analisis

### Indikator Kunci
- Perubahan drastis pola penggunaan
- Aktivitas kompulsif atau penarikan sosial
- Gangguan pola tidur (penggunaan malam berlebihan)
- Konsumsi konten negatif tinggi
- Penurunan aktivitas fisik dan sosial

## 🛠️ Instalasi dan Penggunaan

### Persyaratan Sistem
- Browser modern (Chrome 70+, Firefox 65+, Safari 12+)
- Koneksi internet (untuk fitur lanjutan)
- JavaScript enabled

### Quick Start
```bash
# Clone repository
git clone https://github.com/username/moodguard-ai.git

# Masuk ke direktori proyek
cd moodguard-ai

# Buka file HTML di browser
open index.html
# atau
python -m http.server 8000  # untuk development server
```

### Penggunaan Aplikasi
1. **Input Data**: Masukkan informasi penggunaan smartphone dan data personal
2. **Analisis**: Klik tombol "Analisis Kondisi Mental"
3. **Hasil**: Lihat tingkat risiko dan rekomendasi yang diberikan
4. **Tindak Lanjut**: Ikuti rekomendasi sesuai tingkat risiko

## 📈 Roadmap Pengembangan

### Version 1.0 (Current) ✅
- [x] Prototype web application
- [x] Basic AI scoring algorithm
- [x] Interactive user interface
- [x] Responsive design

### Version 1.5 (Q2 2024) 🔄
- [ ] Integration dengan API smartphone
- [ ] Historical data tracking
- [ ] Improved ML model dengan dataset real
- [ ] Push notification untuk intervensi

### Version 2.0 (Q4 2024) 📋
- [ ] Mobile app (React Native)
- [ ] Real-time monitoring
- [ ] Integration dengan wearable devices
- [ ] Telemedicine integration
- [ ] Multi-language support

### Version 2.5 (2025) 🚀
- [ ] Advanced ML dengan deep learning
- [ ] Personalized intervention AI
- [ ] Integration dengan healthcare providers
- [ ] Research collaboration features

## 🔬 Basis Ilmiah

### Penelitian Pendukung
- **Digital Phenotyping**: Insel, T. (2017). Digital medicine and new technologies for treatment of depression
- **Smartphone Behavior**: Saeb, S. et al. (2015). Mobile phone sensor correlates of depressive symptom severity
- **Circadian Rhythms**: Rohani, D. A. et al. (2018). Correlation of smartphone usage with anxiety and depression

### Validasi Klinis
- Studi korelasi dengan PHQ-9 (Patient Health Questionnaire)
- Validasi dengan Beck Depression Inventory (BDI)
- Kolaborasi dengan rumah sakit dan klinik psikologi

## ⚠️ Disclaimer dan Batasan

### Penting untuk Diperhatikan
- **Bukan Alat Diagnosis**: MoodGuard AI adalah alat screening, bukan pengganti diagnosis profesional
- **Data Privacy**: Semua data diproses secara anonim dan aman
- **Akurasi**: Tingkat akurasi bergantung pada kualitas input data
- **Konsultasi Profesional**: Selalu konsultasi dengan ahli kesehatan mental untuk kondisi serius

### Batasan Teknis
- Memerlukan input data yang akurat dari pengguna
- Algoritma masih dalam tahap pengembangan dan perbaikan
- Tidak dapat mengganti evaluasi klinis komprehensif
- Efektivitas bervariasi berdasarkan individu dan budaya

## 🔒 Keamanan dan Privasi

### Perlindungan Data
- **Tidak Ada Penyimpanan Personal**: Data tidak disimpan di server
- **Processing Lokal**: Semua kalkulasi dilakukan di browser
- **Enkripsi**: Data yang dikirim menggunakan HTTPS
- **Anonimitas**: Tidak ada identitas personal yang dikumpulkan

### Compliance
- GDPR compliant untuk pengguna Eropa
- Sesuai dengan standar keamanan data kesehatan
- Regular security audit dan penetration testing

## 🤝 Kontribusi

### Cara Berkontribusi
Kami menyambut kontribusi dari komunitas! Berikut cara untuk berkontribusi:

```bash
# Fork repository
# Clone fork Anda
git clone https://github.com/your-username/moodguard-ai.git

# Buat branch baru
git checkout -b feature/nama-fitur

# Commit changes
git commit -m "Add: deskripsi fitur baru"

# Push dan buat Pull Request
git push origin feature/nama-fitur
```

### Areas yang Membutuhkan Kontribusi
- **Machine Learning**: Improvement algoritma AI
- **UI/UX Design**: Perbaikan interface pengguna
- **Data Science**: Analisis dan validasi dataset
- **Mobile Development**: Pengembangan aplikasi mobile
- **Documentation**: Perbaikan dokumentasi dan tutorial
- **Testing**: Unit testing dan integration testing
- **Translation**: Lokalisasi ke berbagai bahasa

### Guidelines
- Ikuti coding standards yang ada
- Tulis test untuk fitur baru
- Update dokumentasi jika diperlukan
- Gunakan commit message yang jelas

## 📞 Kontak dan Dukungan

### Tim Pengembang
- **Project Lead**: [Nama Anda] - email@domain.com
- **AI/ML Engineer**: Tersedia posisi
- **Frontend Developer**: Tersedia posisi
- **UX/UI Designer**: Tersedia posisi

### Dukungan Pengguna
- **Email**: support@moodguard-ai.com
- **Issues**: [GitHub Issues](https://github.com/username/moodguard-ai/issues)
- **Documentation**: [Wiki](https://github.com/username/moodguard-ai/wiki)
- **Community**: [Discord Server](https://discord.gg/moodguard)

### Kesehatan Mental Support
Jika Anda membutuhkan bantuan segera:
- **Hotline Nasional**: 119 ext 8
- **WhatsApp Sejiwa**: 0819-1919-8000
- **Email Konseling**: curhat@sejiwa.org
- **Darurat**: 112

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE) - lihat file LICENSE untuk detail lengkap.

```
MIT License

Copyright (c) 2024 MoodGuard AI Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Acknowledgments

### Terima Kasih Kepada
- **Universitas dan Institusi Riset** yang menyediakan dataset dan penelitian
- **Komunitas Open Source** yang berkontribusi pada tools dan libraries
- **Mental Health Professionals** yang memberikan guidance klinis
- **Beta Testers** yang membantu validasi aplikasi
- **Contributors** yang telah berkontribusi pada proyek ini

### Sumber Daya dan Referensi
- [World Health Organization - Depression](https://www.who.int/news-room/fact-sheets/detail/depression)
- [American Psychological Association - Digital Health](https://www.apa.org/science/about/psa/2017/10/digital-health)
- [Journal of Medical Internet Research](https://www.jmir.org/)
- [Nature Digital Medicine](https://www.nature.com/npjdigitalmed/)

## 📊 Statistik Proyek

![GitHub stars](https://img.shields.io/github/stars/username/moodguard-ai?style=social)
![GitHub forks](https://img.shields.io/github/forks/username/moodguard-ai?style=social)
![GitHub issues](https://img.shields.io/github/issues/username/moodguard-ai)
![GitHub pull requests](https://img.shields.io/github/issues-pr/username/moodguard-ai)

### Activity
- **Total Commits**: ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/username/moodguard-ai)
- **Contributors**: ![GitHub contributors](https://img.shields.io/github/contributors/username/moodguard-ai)
- **Last Updated**: ![GitHub last commit](https://img.shields.io/github/last-commit/username/moodguard-ai)

---

<div align="center">

**🧠 MoodGuard AI - Technology for Better Mental Health**

*Dikembangkan dengan ❤️ untuk kesehatan mental yang lebih baik*

[Website](https://moodguard-ai.com) • [Documentation](https://docs.moodguard-ai.com) • [Support](mailto:support@moodguard-ai.com) • [Community](https://discord.gg/moodguard)

</div>
