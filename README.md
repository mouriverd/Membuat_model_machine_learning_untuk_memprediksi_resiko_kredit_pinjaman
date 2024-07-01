# Membuat model machine learning untuk memprediksi resiko kredit pinjaman

## Overview
Di dalam project ini akan dilatih 2 model machine learning  yaitu logistic regression & random forest untuk memprediksi resiko pinjaman, serta feature apa yang paling berpengaruh terhadap resiko pembayaran kredit, sehingga dapat digunakan oleh stake-holder untuk menyetujui atau menolak pengajuan pinjaman.

## Dataset
Nama Dataset yang digunakan adalah " loan_data_2007_2014.csv", terdiri atas 466285 baris & 75 kolom.

## Metodologi
Analisis dalam project ini melibatkan beberapa langkah utama, yaitu:
1. Data Understanding.
2. EDA | Data Cleaning.
3. EDA | Data manipulation.
4. Feature Engineering.
5. Build Machine Learning & Model Evaluation.
6. Penilaian Resiko Kredit.
7. Insight & Recommandation.

## Visualisasi
Berikut visualisasi yang di tampilkan dalam project ini:
![alt text](https://github.com/mouriverd/Membuat_model_machine_learning_untuk_memprediksi_resiko_kredit_pinjaman/blob/main/Visualisasi.png?raw=true)

## Kesimpulan
 - Semakin besar jumlah pinjaman, maka akan semakin besar pula grade resikonya.
 - Dari model logistic regression yang sudah coba dilatih, di temukan bahwa fitur yang paling berpengaruh terhadap resiko peminjaman adalah “Collection Recovery Fee” dan “Installment”. Hal ini dikarenakan varibel tersebut berkaitan langsung dengan jumlah yang harus di bayar oleh peminjam , baik sebagai biaya tambahan/denda karena gagal/telat bayar, maupun sebagai komponen utama dari pembayaran pinjaman.<br>
 ![alt text](https://github.com/mouriverd/Membuat_model_machine_learning_untuk_memprediksi_resiko_kredit_pinjaman/blob/main/Model%20Coefficient.png?raw=true)<br>
 - Dari 2 Model klasifikasi yang sudah bangun, yaitu Logistic Regression dan Random Forest. Yang memiliki performa terbaik  adalah Random forest setelah di lakukan oversampling dengan SMOTE. karena memiliki performance keseluruhan yang lebih baik, walaupun untuk menangkap kasus “Bad”, logistic regression memiliki Recall yang lebih tinggi.<br>
 ![alt text](https://github.com/mouriverd/Membuat_model_machine_learning_untuk_memprediksi_resiko_kredit_pinjaman/blob/main/classification%20report_v1.png?raw=true)<br>.
 - Berdasarkan penilaian resiko kredit, maka dapat dilihat bahwa High risk dan Medium Risk lebih banyak di tangkap oleh Model Logistic Regression dibandingkan dengan random Forest.

## Rekomendasi
Untuk mengurangi resiko pinjaman karena gagal bayar, sebaiknya perlu mengidentifikasi peminjam beresiko tinggi sejak awal dan mengambil Langkah-Langkah preventif, seperti penawaran program bantuan keuangan atau penyesuaian persyaratan pinjaman.







