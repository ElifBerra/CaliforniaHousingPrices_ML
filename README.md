# California Housing Prices Prediction
u proje, California'daki konut piyasası verilerini kullanarak ev fiyatlarını (median_house_value) tahmin etmeye odaklanan kapsamlı bir regresyon çalışmasıdır. 
Proje, veri temizliğinden model optimizasyonuna kadar uçtan uca bir veri bilimi iş akışını içermektedir.
## 🛠️ Proje İçeriği ve Teknik SüreçVeri Hazırlığı:
total_bedrooms sütunundaki eksik değerler medyan (median) yöntemiyle doldurulmuştur.
### Özellik Mühendisliği (Feature Engineering): 
Kategorik ocean_proximity değişkeni, One-Hot Encoding yöntemiyle modele dahil edilmiştir.
### Model: RandomForestRegressor kullanılarak 0.82 $R^2$ skoru elde edilmiştir.
### Optimizasyon: GridSearchCV kullanılarak modelin hiperparametreleri (n_estimators, max_depth) optimize edilmiş, en verimli konfigürasyon doğrulanmıştır.

## 📊 Öne Çıkan Analizler
### Konut Fiyatlarını Belirleyen Faktörler
Modelin tahmin yeteneğini en çok etkileyen özellikler analiz edilmiştir. 
### Elde edilen bulgular
Medyan gelirin (median_income) konut fiyatı üzerinde en baskın belirleyici olduğunu kanıtlamıştır.

### 📈 Teknik SonuçlarModel: 
RandomForestRegressor
### Final Başarı Skoru ($R^2$): 0.82
### Optimizasyon: Modelin varsayılan hiperparametrelerle (n_estimators=200, max_depth=None) optimum seviyede çalıştığı tespit edilmiştir.
