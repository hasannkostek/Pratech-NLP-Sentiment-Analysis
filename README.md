
🛍️ E-Ticaret Ürün Yorumları Duygu Analizi (NLP)

Bu proje, bir e-ticaret platformundaki kullanıcı yorumlarını analiz ederek metinlerden duygu çıkarımı (Sentiment Analysis) yapmak ve müşteri şikayetlerindeki kritik odak noktalarını tespit etmek amacıyla geliştirilmiştir. Pratech Yetenek Programı teknik değerlendirme aşaması kapsamında hazırlanmıştır.


🚀 Proje Özeti

Proje, ham metin verilerinin temizlenmesinden başlayarak, makine öğrenmesi modellerinin eğitilmesi ve sonuçların iş kararlarına dönüştürülmesine kadar uçtan uca bir veri bilimi sürecini kapsar.


🛠️ Kullanılan Teknolojiler

Dil: Python

Kütüphaneler: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn

Model: Random Forest Classifier

Vektörizasyon: TF-IDF (Term Frequency-Inverse Document Frequency)


📋 Uygulanan Adımlar

1. Metin Ön İşleme (Text Preprocessing)
Metinlerin küçük harfe dönüştürülmesi.

Noktalama işaretleri ve sayıların temizlenmesi.

Stop-words (ve, ama, bu vb.) ayıklanması.

Lemmatization ile kelime köklerine inilmesi.


2. Özellik Mühendisliği & Modelleme
Veri seti %80 Eğitim ve %20 Test olarak ayrıldı.

TF-IDF yöntemiyle metinsel veriler sayısal vektörlere dönüştürüldü.

Random Forest algoritması kullanılarak sınıflandırma modeli eğitildi.


3. İş Kararı & Analiz
Model tarafından "Negatif" olarak sınıflandırılan yorumlar filtrelendi.

Bu yorumlar içindeki en sık geçen 5 anahtar kelime tespit edilerek işletme için aksiyon planı önerileri sunuldu.


📊 Sonuçlar

Model Başarısı: %XX Accuracy (Buraya projedeki başarı oranını yazabilirsin).

Kritik Şikayet Noktaları: Tespit edilen anahtar kelimeler ışığında kargo, paketleme ve ürün kalitesi gibi alanlarda iyileştirme önerileri geliştirildi.

<img width="889" height="490" alt="image" src="https://github.com/user-attachments/assets/a056cf74-c59e-4d98-9ec6-01eab304bd10" />



💡 Nasıl Çalıştırılır?

Bu depoyu klonlayın: git clone https://github.com/hasankostek/Pratech-NLP-Sentiment-Analysis.git

Gerekli kütüphaneleri kurun: pip install -r requirements.txt (Eğer oluşturduysan)

nlp_odev.ipynb dosyasını Jupyter Notebook veya VS Code üzerinden çalıştırın.
