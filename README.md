# UAS DATA MINING
Pekerjaan Ujian Akhir Data Mining

## Contributor
- [Saifullah](https://github.com/koreoxy)
- [Ujang Rahul Utama](https://github.com/rhlutm)
- [Mita Ramelia](https://github.com/mitaramelia)

## Deskripsi Data
### Content Data (Dataset Wine Quality)
Data yang digunakan didalam laporan ini adalah data Wine quality (Kualitas Wine) data ini didapatkan di website kaggle yang menyediakan opendataset. Dataset wine quality memiliki 12 kolom data yang dimana terdapat 11 atribut dan 1 class.

### List dataset Wine Quality
1. Data Atribut :
   - fixed acidity 
   - volatile acidity 
   - citric acid 
   - residual sugar 
   - chlorides 
   - free sulfur dioxide 
   - total sulfur dioxide 
   - density 
   - pH 
   - sulphates 	
   - alcohol.
2. Data Atribut :
   - quality (score between 0 and 10) 

### Data atribut dan class
![image](https://user-images.githubusercontent.com/73381115/205674744-e481d257-34bd-4ca1-8a2f-b769f772e248.png)

### Tipe data atribut dan class
Tipe data atribut dan class yang ada di dataset wine ialah, memiliki tipe data float untuk data atribut dan tipe data integer untuk data class. Dan dataset wine memiliki 1599 jumlah dari.
<br>
![image](https://user-images.githubusercontent.com/73381115/205674977-9faa8250-2864-4d83-87b0-c4c18b97e260.png)


## Metode
Metode yang akan digunakan yaitu, akan menggunakan metode klasifikasi Decision tree dan clustering K-Means. Untuk metode klasifikasi akan dilakukan perbandingan hasil antara metode decision tree dan metode random forest dan juga akan ada perbandingan dengan metode Logistic regression.


## Hasil
### Hasil dari Klasifikasi Data Wine Quality
Hasil dari klasifikasi data wine menggunakan Decision tree mendapatkan hasil sebagai berikut :
![image](https://user-images.githubusercontent.com/73381115/205676809-c3b79747-ba99-42a1-b1f3-34d59c54ff65.png)


Dengan menggunakan metode decision tree mendapatkan nilai akurasi 90% dan CV score 86% yang artinya dataset wine memiliki nilai akurasi tinggi karena nilai akurasi melebihi 70% dataset tersebut dapat digunakan. Dan kita juga bisa memandingkan antara 3 metode yang berbeda dengan memandingkan metode Decision Tree, Random Forest dan Logistic Regression. Yang dimana hasil akurasi ketiga metode tersebut dapat dilihat pada gambar dibawah ini :

### Nilai Akurasi Metode Decision Tree
![image](https://user-images.githubusercontent.com/73381115/205677082-512c2890-6227-499a-8f8e-c67eb221a660.png)

### Nilai Akurasi Metode Random Forest
![image](https://user-images.githubusercontent.com/73381115/205677137-fba06267-60d0-4577-bbcd-a10608fb7f6b.png)

### Nilai Akurasi Metode Logistic Regression
![image](https://user-images.githubusercontent.com/73381115/205677204-cf44b2f1-ed56-4823-845e-4f9b1716414b.png)

Jadi dari ketiga metode yang berbeda yang memiliki nilai akurasi paling tinggi adalah metode Random Forest dengan nilai Akurasi 93% dan CV Score 91%, jadi untuk mendapatkan nilai akurasi yang paling tinggi kita bisa menggunakan metode Random Forest.


### Hasil dari Clustering K-Means Data Wine Quality
Hasil dari Cluestering menggunakan metode K-Means mendapatkan pembagian dataset wine dan pembagian tersebut dilakukan menggunakan perulangan iterasi untuk mencari titik centroid.
<br>
![image](https://user-images.githubusercontent.com/73381115/205677369-34460c54-c9c0-4e5b-8dd6-a05c0b5b94c5.png)
