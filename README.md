# Breast Cancer Wisconsin | Veri Madenciliği ve Sınıflandırma Analizi

Üniversitedeki **Veri Madenciliği dersi** kapsamında grup çalışması olarak hazırlanan bir makine öğrenmesi projesidir. Breast Cancer Wisconsin veri setindeki hücre çekirdeği ölçümleri kullanılarak iyi huylu (benign) ve kötü huylu (malignant) tümör sınıflarının ayrıştırılması amaçlanmıştır.

## Kullanılan yöntemler

- Python, pandas, NumPy, Matplotlib, seaborn, scikit-learn
- Keşifsel veri analizi, eksik değer kontrolü, korelasyon ısı haritası, histogram, boxplot ve pairplot
- Eğitim/test ayrımı (%80/%20) ve StandardScaler ile ölçekleme
- Logistic Regression, K-Nearest Neighbors (KNN) ve Support Vector Machine (SVM)
- Accuracy, precision, recall, F1-score ve confusion matrix ile değerlendirme

## Notebook'ta raporlanan test sonuçları

| Model | Doğruluk (Accuracy) |
| --- | ---: |
| Logistic Regression | %97,37 |
| KNN | %94,74 |
| SVM | %98,25 |

Bunlar notebook'un **kaydedilmiş çıktılarıdır**; bu pakette modeller yeniden çalıştırılarak doğrulanmamıştır.

## Dosyalar

- `BreastCancerW.ipynb` — Python analiz kodları, açıklamalar ve kaydedilmiş sonuçlar
- `BreastCancer_proje.html` — notebook'un tarayıcıda görüntülenebilen HTML raporu

## Çalıştırma

1. Veri setini [Kaggle: Breast Cancer Wisconsin Data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) sayfasından indirin.
2. İçindeki `data.csv` dosyasını `BreastCancerW.ipynb` ile aynı klasöre koyun.
3. Python ortamına bağımlılıkları yükleyin: `pip install -r requirements.txt`
4. Notebook'u Jupyter veya Google Colab üzerinde çalıştırın. Colab kullanıyorsanız `data.csv` dosyasını çalışma ortamına ayrıca yükleyin.

## Veri kaynağı

Kaggle / UCI — [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

> **Not:** Bu eğitim amaçlı bir veri madenciliği projesidir; klinik tanı aracı değildir. Herkese açık sürümde grup üyelerinin öğrenci numaraları gizlenmiştir.
