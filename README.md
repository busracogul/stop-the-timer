# ⌛ Stop The Timer
## 🎯 Genel Bakış
React kullanılarak geliştirilmiş bir geri sayım aracı. Kullanıcılar belirledikleri süreyi başlatabilir ve (neredeyse) sıfıra ulaştığında zamanlayıcıyı manuel olarak durdurabilirler.
## 🛠️ Kullanılan Teknolojiler
- **React**
- **React DOM**
- **CSS**
## 🚀 Özellikler
- Dinamik Geri Sayım: Kullanıcının belirlediği süre boyunca milisaniye hassasiyetinde geri sayım başlatılır. 
- Manuel Durdurma: Kullanıcı, geri sayımı tam sıfır olmadan önce durdurmalı ve doğru zamanlama becerisini test etmelidir.
- Otomatik Sonlandırma: Süre sıfıra ulaştığında zamanlayıcı otomatik olarak durur ve sonuç ekranı açılır.
- Sonuç Değerlendirme: Kullanıcının zamanı ne kadar doğru durdurduğunu gösteren bir modal pencere açılır. 
- Basit ve Etkileşimli Arayüz: Kullanıcı dostu butonlar ve geri bildirim mesajları ile akıcı bir deneyim sunar. 
## 🕹️ Nasıl Kullanılır
1. Hedef Süreyi Görün: Uygulama tarafından belirlenen geri sayım süresi ekranda gösterilir. 
2. Zamanlayıcıyı Başlatın: "Start Challenge" butonuna basarak geri sayımı başlatın. 
3. Doğru Anda Durdurun: Süre sıfıra ulaşmadan hemen önce "Stop Challenge" butonuna basarak geri sayımı durdurun. 
4. Sonucu Görüntüleyin: Açılan modal penceresinde, hedef süreye ne kadar yakın durduğunuzu değerlendirin.
## 📸 Ekran Görüntüleri
- **Ana Ekran**
  ![Giriş Ekranı](https://github.com/user-attachments/assets/aab820f2-7d32-48d3-8740-e29e32e98141)
- **Sayaçlar**
  ![Sonuçlar Tablosu](https://github.com/user-attachments/assets/a8c758e0-381a-42a8-8816-c987856e6986)
- **Kaybettiğinde Açılan Modal**
  ![Sonuçlar Tablosu](https://github.com/user-attachments/assets/840e2b33-11c7-40a8-9062-df19fc47eba7)
- **Kazandığında Açılan Modal**
  ![Sonuçlar Tablosu](https://github.com/user-attachments/assets/5c2c01f0-1631-4d74-aa83-313b840e971d)
## ⚙️ Kurulum ve Çalıştırma
1. Bu projeyi klonlayın:
   ```bash
   git clone <https://github.com/busracogul/stop-the-timer.git>
   cd stop-the-timer
   ```
2. Bağımlılıkları yükleyin:
   ```bash
   npm install
   ```
3. Geliştirme sunucusunu başlatın:
   ```bash
   npm run dev
   ```
4. Uygulamayı tarayıcınızda görüntüleyin:
   ```bash
   http://localhost:5173
   ```
## Canlı Proje Linki
Projeyi canlıda görmek için [buraya tıklayın](https://stop-the-timer.vercel.app).
