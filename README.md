# 📊 ING Hubs Datathon Project

## 🧠 Proje Hakkında

Bu proje, ING Hubs Datathon kapsamında müşteri verileri üzerinden **churn (müşteri kaybı) tahmini** yapmak amacıyla geliştirilmiştir.

Veri seti üzerinde yapılan analizler ve feature engineering süreçleri ile model performansının artırılması hedeflenmiştir.

---

## 📁 Veri Seti

Projede kullanılan veri setleri:

* `customers.csv` → Müşteri temel bilgileri
* `customer_history.csv` → Müşteri geçmiş işlemleri
* `referance_data.csv` → Eğitim (train) etiketleri
* `referance_data_test.csv` → Test verisi
* `sample_submission.csv` → Örnek submission formatı

### ⚠️ Veri Notları

* `work_sector`:

  * Eksik değerler **bilinçli olarak bırakılmıştır**
  * Sebep: Öğrenci ve işsiz kullanıcıların sektör bilgisi yoktur
* `churn`:

  * Test setinde boş olması normaldir (label yok)

---

## ⚙️ Kullanılan Teknolojiler

* Python 🐍
* NumPy
* Pandas
* LightGBM ⚡
* Scikit-learn

---

## 🔍 Proje Adımları

1. **Veri Yükleme**
2. **Veri Analizi (EDA)**
3. **Eksik Veri İncelemesi**
4. **Feature Engineering**
5. **Model Eğitimi (LightGBM)**
6. **Cross Validation (StratifiedKFold)**
7. **Tahmin ve Submission Oluşturma**

---

## 🚀 Kurulum

Projeyi çalıştırmak için:

```bash
git clone https://github.com/kullanici-adin/proje-adi.git
cd proje-adi
pip install -r requirements.txt
```

---

## ▶️ Kullanım

Notebook çalıştırarak tüm pipeline’ı execute edebilirsin:

```bash
jupyter notebook ing-hubs-datathon.ipynb
```

---

## 📈 Model

Model olarak **LightGBM** kullanılmıştır.

Avantajları:

* Hızlı eğitim ⚡
* Yüksek performans
* Büyük veri ile uyumlu

---

## 📤 Çıktı

* Feature engineering sonrası veri:

  * `customers_with_features.csv`
* Submission dosyası:

  * `submission.csv` (oluşturulabilir)

---

## 🤝 Katkı

Katkı sağlamak istersen:

1. Fork al 🍴
2. Branch oluştur
3. Commit at
4. PR gönder 🚀

---

## 📌 Not

Bu proje eğitim ve yarışma amaçlı geliştirilmiştir.

