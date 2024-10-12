# Diabetes-Prediction-Using-Machine-Learning
# Diabetes Prediction Model

## Proje Hakkında
Bu proje, diyabet hastalığının tespiti için bir makine öğrenimi modelinin geliştirilmesini içermektedir. Veriler üzerinde yapılan analizler ve modelleme işlemleri ile diyabet riskini tahmin eden bir sınıflandırma modeli oluşturulmuştur.

## Kullanılan Kütüphaneler
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

## Veri Seti
Diyabet veri seti, çeşitli sağlık özelliklerine dayalı olarak diyabet hastalığını tahmin etmek için kullanılmaktadır. Veri seti şu özellikleri içermektedir:
- **Pregnancies**: Hamilelik sayısı
- **Glucose**: Glukoz seviyesi
- **BloodPressure**: Kan basıncı
- **SkinThickness**: Cilt kalınlığı
- **Insulin**: İnsülin seviyesi
- **BMI**: Vücut kitle indeksi
- **DiabetesPedigreeFunction**: Diyabet soy ağacı fonksiyonu
- **Age**: Yaş
- **Outcome**: Diyabet durumu (0: Yok, 1: Var)

## Modelleme
Veri seti üzerinde **Random Forest** sınıflandırma algoritması kullanılarak bir model oluşturulmuştur. Modelin performansı aşağıdaki metriklerle değerlendirilmiştir:
- **Accuracy**: %79
- **Recall**: 0.711
- **Precision**: 0.67
- **F1 Skoru**: 0.69
- **AUC**: 0.77

## Kullanım
Projenin çalıştırılması için gerekli olan kütüphanelerin yüklenmesi gerekmektedir. Aşağıdaki komutları kullanarak kütüphaneleri yükleyebilirsiniz:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

python diabetes_prediction_model.py
