# 📌 Sağlık Hizmetleri Sağlayıcıları Anomali Tespit Projesi

---

## 📖 Proje Hakkında

Bu proje, sağlık hizmeti sağlayıcılarına ilişkin veriler üzerinde **anomali tespiti** uygulayarak olağan dışı durumları tespit etmeyi amaçlamaktadır. Veri seti, sağlık sektöründeki operasyonel ve finansal süreçlere dair önemli bilgiler sunmaktadır.

**Isolation Forest (IF)** algoritması kullanılarak normal ve anomalik gözlemler ayrıştırılmıştır. Proje, veri analizi ve görselleştirme adımlarını içermektedir.

---

## ⚙️ Kullanılan Teknolojiler

- **Python** 🐍: Veri analizi ve modelleme için.
- **KNIME** 🔄: Veri temizleme, dönüştürme ve iş akışları için.
- **Matplotlib** 📊 & **Seaborn** 🌈: Veri görselleştirme için.

---

## 📂 Proje İçeriği

### 1. Veri Seti Özeti
- **Adı**: Sağlık Hizmetleri Sağlayıcıları Verisi  
- **Kapsamı**: Sağlık hizmeti sağlayıcılarının operasyonel ve finansal bilgileri.  
- **Kaynak**: Kaggle  

### 2. Gerçekleştirilen İşlemler
- **Veri Ön İşleme**: Eksik değerlerin temizlenmesi ve verilerin normalize edilmesi.  
- **Anomali Tespiti**: Isolation Forest algoritması ile %5 anomali oranı belirlenmiştir.  
- **Veri Görselleştirme**:
  - Scatter plot ile normal ve anomalik veriler görselleştirilmiştir.  
  - Veri dağılımlarını analiz etmek için pairplot uygulanmıştır.  

---

## 📊 Çıktılar

### 1️⃣ Anomali Tespit Sonuçları
- **Toplam Anomalik Gözlem Sayısı**: `123`  
- **Toplam Normal Gözlem Sayısı**: `987`  

### 2️⃣ Görselleştirme
- **Scatter Plot**:
  - **Mavi Noktalar**: Normal Veriler  
  - **Kırmızı Noktalar**: Anomalik Veriler  
  - Anomaliler genellikle düşük yoğunluklu bölgelerde gözlemlenmiştir.  

---

## 📌 Kullanım

###  Proje Dosyasını Çalıştırma
- Proje Python 3.8+ ile uyumludur.  
- Gerekli bağımlılıkları yüklemek için:
  ```bash
  pip install -r requirements.txt

---


###  Görselleştirme Sonuçları
**Pairplot** ve **Scatter Plot** görselleri çalışma sonunda otomatik olarak oluşturulacaktır.
![image](https://github.com/user-attachments/assets/62de2818-0329-4769-ab28-13b689dae3af)
![image](https://github.com/user-attachments/assets/011e2a85-5401-43de-a1ca-f771f70e0c9c)

---

## 🎯 Hedefler ve Faydalar

- **Anomalilerin Belirlenmesi**: Operasyonel hataları ve finansal düzensizlikleri tespit etme.
- **Karar Destek Mekanizmaları**: Sağlık hizmeti sağlayıcılarının performansını artırma ve maliyet etkinliği sağlama.
- **Önerilen Kullanım Alanları**:
  - Siber güvenlik 🚨
  - Sağlık yönetimi 🏥
  - Finansal analiz 💰

---

## 📬 İletişim

📧 Herhangi bir sorunuz varsa bana ulaşabilirsiniz:  
`developer@example.com`

💻 **GitHub Profilim**: [https://github.com/sena1bayram]

🎉 **Projeyi Beğendiyseniz ⭐️ Bırakmayı Unutmayın!**

