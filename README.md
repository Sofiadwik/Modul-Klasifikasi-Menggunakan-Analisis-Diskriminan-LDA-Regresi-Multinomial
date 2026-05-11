# Implementasi Analisis Diskriminan dan Regresi Logistik Multinomial pada Pemeliharaan Prediktif Mesin

### Anggota Kelompok:
- Cantika Latifatul Nur Ella (24031554023)  
- Sofia Dwi Kinasih (24031554079)  
- M. Naza Firmansyah (24031554164)

### Dosen Pengampu:
Bu Dinda Galuh Guminta, M.Stat.
----- 

## Dataset
Proyek ini merupakan implementasi analisis multivariat untuk kasus **predictive maintenance** pada mesin. Analisis dilakukan menggunakan dua metode utama, yaitu **Linear Discriminant Analysis (LDA)** dan **Regresi Logistik Multinomial**, dengan tujuan untuk mengklasifikasikan jenis kegagalan mesin berdasarkan data operasional.

Dataset yang digunakan adalah **Machine Predictive Maintenance Classification** dari Kaggle yang berisi data operasional mesin seperti suhu udara, suhu proses, kecepatan rotasi, torsi, keausan alat, tipe produk, serta jenis kegagalan mesin.
🔗https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification

## Tujuan
Proyek ini bertujuan untuk:
1. Mendeskripsikan karakteristik data operasional mesin.
2. Menerapkan metode Analisis Diskriminan Linear atau LDA.
3. Menerapkan metode Regresi Logistik Multinomial.
4. Menentukan metode yang lebih sesuai untuk kasus predictive maintenance.

## Variabel yang digunakan
| Simbol | Nama Variabel |
|---|---|
| X1 | Type |
| X2 | Air temperature [K] |
| X3 | Process temperature [K] |
| X4 | Rotational speed [rpm] |
| X5 | Torque [Nm] |
| X6 | Tool wear [min] |
| Y | Failure Type |

## Metode Analisis
### 1. Linear Discriminant Analysis (LDA)
LDA digunakan untuk membentuk fungsi diskriminan yang dapat membedakan kelompok jenis kegagalan mesin berdasarkan variabel operasional. Tahapan analisis meliputi:
- Uji normalitas multivariat
- Uji homogenitas kovarians
- Pembentukan fungsi diskriminan
- Uji signifikansi fungsi diskriminan
- Evaluasi klasifikasi menggunakan confusion matrix, precision, recall, F1-score, dan APER

### 2. Regresi Logistik Multinomial
Regresi Logistik Multinomial digunakan karena variabel target memiliki lebih dari dua kategori dan bersifat nominal. Tahapan analisis meliputi:
- Uji kesesuaian model
- Uji simultan
- Uji parsial
- Interpretasi odds ratio
- Evaluasi pengaruh variabel terhadap probabilitas jenis kegagalan mesin

### Link Publikasi RPubs
🔗https://rpubs.com/sofiadwik/modul4_Klasifikasi 
