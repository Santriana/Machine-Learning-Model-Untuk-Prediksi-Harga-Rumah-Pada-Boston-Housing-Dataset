# Model-Untuk-Prediksi-Harga-Rumah-Pada-Dataset-Bouston_Housing
Dalam memprediksi harga rumah pada dataset Boston_Housing digunakan tiga buah model regresi yaitu linear regression, lasso regression, dan ridge regression.

### Justifikasi Variabel di Dataset
- CRIM - tingkat kejahatan per kapita suatu kota
- ZN - proporsi tanah perumahan dikategorikan untuk banyak lebih dari 25.000 sq.ft.
- INDUS - proporsi hektar bisnis non-ritel per kota.
- CHAS - Variabel dummy Sungai Charles (1 jika saluran membatasi sungai; 0 sebaliknya)
- NOX - konsentrasi oksida nitrat (parts per 10 juta)
- RM - rata-rata jumlah kamar per hunian
- AGE - proporsi unit yang ditempati pemilik yang dibangun sebelum tahun 1940
- DIS - jarak ke lima pusat kerja Boston
- RAD - indeks aksesibilitas ke jalan raya radial
- TAX - tarif pajak properti nilai penuh per $10.000

- PTRATIO - rasio murid-guru menurut kota
- B - 1000(Bk - 0.63)^2 di mana Bk adalah proporsi orang kulit hitam menurut kota
- LSTAT - % status penduduk yang lebih rendah
- MEDV - Nilai rata-rata rumah yang ditempati pemilik di $1000-an

Penjelasan lebih lanjut untuk dataset : http://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

### Summery Step
1. Data Visualization dan Exploratory Data Analysis
2. Data Preprocessing (Feature Selection, Removing Outlier, Scaling Data, Split Data)
3. Train Model
4. Hyperparameter Tuning
5. Test Model
6. Evaluate Model
