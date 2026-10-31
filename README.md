# Fake News Detection (Model Training)

NLP ve Makine Öğrenmesi algoritmaları kullanılarak sahte (fake) ve gerçek (true) haberlerin sınıflandırılması ve model eğitimi projesi.

## 📊 Veri Seti (Dataset)

Projede kullanılan veri seti boyutu (~116 MB) nedeniyle doğrudan Git deposuna eklenmemiştir. Veri setini aşağıdaki Kaggle bağlantısından temin edebilirsiniz:

🔗 **Kaggle Veri Seti:** [Fake and Real News Dataset (by Clément Bisaillon)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

### Veri Seti Kurulumu
1. Yukarıdaki bağlantıdan `Fake.csv` ve `True.csv` dosyalarını indirin.
2. Proje ana dizininde `dataSet` adında bir klasör oluşturun ve dosyaları içine yerleştirin:
   ```text
   dataSet/
   ├── Fake.csv
   └── True.csv
   ```

## 📓 Notebook
Model eğitimi ve veri analizi adımları için [fake_real_news.ipynb](fake_real_news.ipynb) dosyasını çalıştırabilirsiniz.
