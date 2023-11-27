# sentimen-analysis
Membuat sistem yang dapat memfilter komentar negatif dan positif dan mengkalkulasinya serta melihat kata yang sering digunakan, sistem ini dibuat dengan _machine learning_ dengan menggunakan algoritma _K-Nearest Neighbors_, SVM, _Naive Bayes_ dengan menggunakan metode ensemble learning dengan teknik *Voting Classifier* algoritma tersebut aka dipadukan sehingga mendapat _base majority_ yang terbaik. Dari teknik *ensemble learning* didapatkan F1 _score_ 87 % dengan **akurasi 89 %** dan hasilnya sistem dapat mendeteksi kalimat positif dan negatif.

---
### Evaluasi
Hasil Pengujian dengan Ratio 80:20

Algorithm| Models	| Accuracy	Recall|	Precision|	F1 Score
**SVM**	|91.18 % |94.12 %	| 88.89 % |	91.43 %
**KNN**	|85.29 %| 80.39 %	| 89.13 %| 84.54%
**Naive Bayes**| 89.22 %| 84.31 % |	93.38 % |	88.66 %
**Voting Classifier** |	89.22 % |	86.27 %	91.67 | %	88.89 %
