# Titanic-data-EDA
Analisis Data Eksploratif: Dataset Titanic
Analisis Data Eksploratif (EDA) dan penjelasannya dilakukan pada dataset Titanic yang berisi informasi dasar penumpang seperti nama, jenis kelamin, usia, dan status keselamatan. Titanic merupakan salah satu kapal paling terkenal dalam sejarah, dan dataset ini sering digunakan sebagai pengenalan dalam analisis data.

Tujuan dari analisis ini adalah untuk memahami struktur dasar dari data serta menggali wawasan awal, seperti distribusi usia penumpang, komposisi jenis kelamin, tingkat keselamatan, dan kualitas keseluruhan dari dataset, termasuk keberadaan duplikat dan data yang hilang.

Temuan Utama:

    Dataset terdiri dari 4 kolom dan 500 baris.

    Kolom Survived berisi data biner (0 dan 1) yang menunjukkan apakah penumpang selamat atau tidak.

    Kolom Age memiliki beberapa data yang hilang.

    Kolom Name memiliki 499 nilai unik, yang berarti ada satu nama yang terduplikasi.

    Kolom Sex hanya memiliki dua nilai unik: male dan female.

    Jumlah penumpang laki-laki (288) lebih banyak dibandingkan perempuan.

    Lebih dari setengah penumpang tercatat selamat.

    Usia penumpang sangat bervariasi, mulai dari bayi hingga lanjut usia.

Saran:

    Penumpang perempuan cenderung memiliki tingkat keselamatan yang lebih tinggi — analisis lanjutan bisa dilakukan untuk mengetahui penyebabnya.

    Mengelompokkan usia (misalnya anak-anak, dewasa, lansia) dapat membantu memahami pola keselamatan.

    Mengisi nilai usia yang hilang menggunakan median sederhana bisa dilakukan, namun penggunaan median berdasarkan kelompok (misalnya berdasarkan jenis kelamin atau status keselamatan) dapat meningkatkan akurasi.

    Pastikan kolom pengenal seperti Name bersifat unik atau dilengkapi dengan kolom ID yang lebih kuat dalam dataset di masa depan.
