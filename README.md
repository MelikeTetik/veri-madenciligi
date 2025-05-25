Otomatik Haber Kategorizasyonu (Automatic News Categorization)
Proje Hakkında
Bu proje, farklı haber kaynaklarından (NTV, TRT Haber, Habertürk) toplanan haber içeriklerinin makine öğrenmesi teknikleriyle otomatik olarak kategorize edilmesini amaçlamaktadır. Python programlama dili ve çeşitli doğal dil işleme (NLP) kütüphaneleri kullanılarak geliştirilmiştir. Haberlerin içeriklerine göre doğru kategoriye atanması, büyük haber veri havuzlarının analizini kolaylaştırmak ve içerik tabanlı uygulamalar geliştirmek için tasarlanmıştır.

Özellikler
Çoklu haber kaynağından veri toplama ve temizleme

Türkçe metinlerde kök indirgeme (stemming) uygulama

TF-IDF vektörleştirme yöntemiyle haber metinlerini sayısal verilere dönüştürme

Naive Bayes, Logistic Regression, SVM, Random Forest ve Gradient Boosting algoritmaları ile model eğitimi

En iyi model seçimi ve kaydedilmesi

Yeni haberler üzerinde sınıflandırma ve tahmin

Kullanılan Teknolojiler
Python 3

pandas

scikit-learn

nltk

TurkishStemmer

re (RegEx)

pickle

Google Colab (geliştirme ortamı)
Sonuçlar
En iyi model: Logistic Regression

Doğruluk: %91.01

Model, spor, siyaset, ekonomi gibi kategorileri başarıyla ayırt edebilmektedir.

