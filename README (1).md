
# 🎮 Karpuz Kesme Oyunu (Görsel Programlama Ödevi)

## 👤 Öğrenci Bilgileri

- **Ad Soyad:** [Adınız Soyadınız]
- **Öğrenci No:** 23100011009
- **Ders:** 2024-2025 Bahar Yarıyılı - Görsel Programlama
- **Ödev:** 1. Laboratuvar Uygulaması

---

## 📌 Oyun Açıklaması

Bu proje, *Fruit Ninja* oyunundan esinlenilerek oluşturulmuş bir **karpuz kesme oyunudur**. Amaç, 30 saniyelik süre içerisinde mümkün olduğunca çok karpuzu keserek yüksek skor elde etmektir.

---

## 🚀 Özellikler

- ✅ Qt 5/6 ile GUI geliştirme
- ✅ `QMainWindow` tabanlı tam ekran arayüz
- ✅ `konumlar.txt` dosyasından konum okuma
- ✅ `QTimer` ile zamanlama ve süre takibi
- ✅ `QPixmap` ve `QLabel` ile karpuz görselleri
- ✅ Mouse ile tıklama ile kesme animasyonu
- ✅ Kesilen/kaçırılan karpuz sayısı ve kalan süre üst panelde
- ✅ `skorlar.txt` dosyasına skor kaydı
- ✅ Maksimum skor kontrolü ve kullanıcıya gösterimi
- ✅ Qt kaynak sistemi (`kaynaklarim.qrc`) üzerinden görsel yönetimi

---

## 📂 Proje Yapısı

```
23100011009_Odev1/
├── main.cpp
├── mainwindow.cpp
├── mainwindow.h
├── mainwindow.ui
├── ui_mainwindow.h
├── kaynaklarim.qrc
├── konumlar.txt
├── skorlar.txt
├── images/               # Karpuz ve kesilmiş karpuz resimleri
├── 23100011009_dialog.cpp  # Gereken ayrı kopya
└── README.md             # Bu dosya
```

---

## 🛠 Kurulum & Çalıştırma

1. **Qt Creator** ile `23100011009_Odev1.pro` dosyasını açın.
2. Gerekli kaynakların (resimler, `konumlar.txt`) proje dizininde olduğundan emin olun.
3. Projeyi derleyin ve çalıştırın.
4. Oyun başladığında 30 saniye süresince karpuzlara tıklayarak en yüksek skoru yapmaya çalışın.

---

## ⏳ Oyun Süreci

- Oyun başladığında 30 saniyelik sayaç devreye girer.
- `konumlar.txt`'den alınan konumlara göre karpuzlar belirir.
- Tıklanan karpuzlar kesilmiş karpuza dönüşür ve kısa süre sonra kaybolur.
- Her kaçırılan karpuz istatistiklere yansır.
- Süre bittiğinde oyun sona erer ve skor `skorlar.txt` dosyasına kaydedilir.

---

## 📽️ Ekran Kaydı

Oyun içi deneyimi görmek için aşağıdaki videoyu izleyebilirsiniz:

🎥 [Karpuz Kesme Oyunu Tanıtım Videosu](https://www.youtube.com/watch?v=IJ7QwbOhyuI)

---

## 📝 Proje Hakkında Medium Yazısı

Bu proje hakkında yazdığım detaylı yazıya aşağıdaki bağlantıdan ulaşabilirsiniz:

👉 [Medium yazısını buraya sen ekleyeceksin](Medium yazı linki buraya)

---

## 📤 Teslim Formatı

- ✅ Proje dosyaları `.zip` halinde yüklendi
- ✅ `23100011009_dialog.cpp` ayrı dosya olarak yüklendi
- ✅ Video kaydı yüklendi
- ✅ Son teslim tarihi olan **6 Nisan 2025 23:55**’ten önce gönderildi

---

## ⚠️ Notlar

- Kodda açıklayıcı yorum satırları mevcuttur.
- Tüm işlevler Qt standartlarına uygun olarak yazılmıştır.
- Proje, özgün olarak tarafımdan geliştirilmiştir ve benzerlik kontrolüne uygundur.

---

## ✉️ İletişim

Herhangi bir geri bildirim ya da geliştirme önerisi için iletişime geçebilirsiniz.  
📧 E-posta: [e-posta adresin]
