# 📊 İstatistik ve Örnekleme Uygulaması

Bu proje; temel ve ileri düzey istatistiksel hesaplamaları gerçekleştiren, akademik standartlara uygun olarak geliştirilmiş web tabanlı bir araçtır. Kullanıcıların veri setleri üzerinde merkezi eğilim, dağılım ölçüleri ve çeşitli örnekleme yöntemlerini simüle etmelerine olanak tanır.

---

## 🚀 Öne Çıkan Özellikler

Uygulama iki ana modülden oluşmaktadır:

### 1. Örnekleme Yöntemleri
*   **Basit Rastgele Örnekleme:** Evren büyüklüğünden bağımsız seçim yapabilir. Örnek sayısı evrenden büyükse otomatik olarak **iadeli (tekrarlı)** seçime geçer.
*   **Sistematik Örnekleme:** Belirlenen $k = N / n$ aralığına göre sistematik seçim yapar.
*   **Tabakalı Örnekleme:** Evreni kullanıcı tarafından belirlenen özel yüzdelere göre tabakalara ayırır ve orantılı örneklem seçer.

### 2. İstatistiksel Hesaplamalar
Veri girişine göre otomatik olarak **Basit Seri**, **Frekans Serisi** ve **Gruplandırılmış Frekans Tablosu** oluşturur.

*   **Merkezi Eğilim:** Aritmetik, Geometrik ve Harmonik Ortalama, Medyan, Mod.
*   **Dağılım Ölçüleri:** Varyans ve Standart Sapma ($n-1$ düzeltmesi ile), Ortalama Mutlak Sapma (OMS), Varyasyon Katsayısı.
*   **Gelişmiş Analiz:**
    *   Gruplandırılmış seriler için interpolasyon yöntemiyle **Alt ve Üst Çeyreklik ($Q_1, Q_3$)** hesabı.
    *   Standartlaştırılmış **Çarpıklık** ve **Basıklık (Kurtosis)** ölçütleri.
    *   Ondalık hassasiyete duyarlı sınıf sınırları ve limitleri hesabı.

---

## 📐 Kullanılan Akademik Formüller

Uygulama, üniversite düzeyindeki istatistik müfredatına sadık kalınarak geliştirilmiştir:

**Gruplandırılmış Çeyreklikler:**
$$Q_1 = L_1 + \frac{J_1 \cdot h}{f_{Q_1}}$$

**Basıklık Ölçütü (Kurtosis):**
$$K = \left( \frac{m_4}{S^4} \right) - 3$$

---

## 🛠️ Teknolojiler

*   **HTML5** - Yapısal kurgu
*   **CSS3** - Kullanıcı dostu arayüz
*   **JavaScript (ES6+)** - Matematiksel motor

---

## 📖 Nasıl Çalıştırılır?

1.  Dosyaları indirin.
2.  `index.html` dosyasını herhangi bir modern tarayıcıda açın.

---

## 📝 Notlar
Bu uygulama, özellikle gruplandırılmış serilerdeki hassas hesaplama hatalarını gidermek amacıyla açık kaynaklı bir araç olarak geliştirilmiştir.
