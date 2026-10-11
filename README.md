# Grokking Deep Learning

## Daftar notebook

| Chapter | Materi utama | Notebook |
| --- | --- | --- |
| 1 | Introducing Deep Learning | [Chapter 01 Introducing Deep Learning](01_Introducing_Deep_Learning.ipynb) |
| 2 | Fundamental Concepts | [Chapter 02 Fundamental Concepts](02_Fundamental_Concepts.ipynb) |
| 3 | Forward Propagation | [Chapter 03 Forward Propagation](03_Forward_Propagation.ipynb) |
| 4 | Gradient Descent | [Chapter 04 Gradient Descent](04_Gradient_Descent.ipynb) |
| 5 | Generalizing Gradient Descent | [Chapter_05_Generalizing_Gradient Descent](05_Generalizing_Gradient_Descent.ipynb) |
| 6 | Backpropagation | [Chapter 06 Backpropagation](06_Backpropagation.ipynb) |
| 7 | Visualizing Neural Networks | [Chapter 07 Picture Neural Networks](07_Picture_Neural_Networks.ipynb) |
| 8 | Regularization and Batching | [Chapter 08 Regularization and Batching](08_Regularization_and_Batching.ipynb) |
| 9 | Activation Functions | [Chapter 09 Activation Functions](09_Activation_Functions.ipynb) |
| 10 | Convolutional Neural Networks | [Chapter 10 Convolutional Neural Networks](10_Convolutional_Neural_Networks.ipynb) |

## Ringkasan setiap chapter

### Chapter 1 — Introducing Deep Learning: Why You Should Learn It

Bab ini memperkenalkan alasan mempelajari deep learning, potensi penerapannya, dan pendekatan belajar dalam buku. Notebook membahas persiapan Python, NumPy, matematika dasar, serta pentingnya memahami mekanisme model melalui latihan bertahap. Karena bab ini tidak memuat kode, isinya berfokus pada ringkasan konsep dan refleksi pembelajaran.

### Chapter 2 — Fundamental Concepts: How Do Machines Learn?

Bab ini membahas hubungan artificial intelligence, machine learning, dan deep learning. Pembahasan mencakup supervised dan unsupervised learning, parametric dan nonparametric learning, serta alur **predict, compare, learn**. Contoh konseptual dan perhitungan manual digunakan untuk menjelaskan bagaimana data, target, prediksi, dan parameter berhubungan dalam proses pembelajaran.

### Chapter 3 — Introduction to Neural Prediction: Forward Propagation

Bab ini menjelaskan cara jaringan menghasilkan prediksi dari input dan bobot yang tersedia. Reproduksi mencakup satu input, banyak input, banyak output, serta jaringan berlapis. Operasi vektor, dot product, dan perkalian matriks diperlihatkan melalui Python dan NumPy. Bobot pada contoh belum dilatih; fokusnya adalah memahami alur perhitungan prediksi.

### Chapter 4 — Introduction to Neural Learning: Gradient Descent

Bab ini melanjutkan proses prediksi ke pengukuran error dan pembaruan bobot. Notebook mereproduksi hot and cold learning, kemudian menghubungkannya dengan turunan dan gradient descent. Penjelasan serta grafik memperlihatkan pengaruh learning rate, arah perubahan bobot, konvergensi, dan divergence ketika langkah pembelajaran terlalu besar.

### Chapter 5 — Learning Multiple Weights at a Time: Generalizing Gradient Descent

Bab ini memperluas gradient descent untuk jaringan dengan banyak bobot, input, dan output. Notebook membahas gradien tiap bobot, pembekuan satu bobot, orientasi matriks, serta outer product untuk pembaruan parameter. Bagian akhir memperkenalkan representasi citra MNIST dan visualisasi bobot sebagai pengantar menuju eksperimen klasifikasi pada bab berikutnya.

### Chapter 6 — Building Your First Deep Neural Network: Introduction to Backpropagation

Bab ini memperkenalkan pembelajaran pada seluruh dataset dan propagasi gradien melalui hidden layer. Contoh lampu lalu lintas dan XOR digunakan untuk menjelaskan keterbatasan model linear, peran ReLU, dan aturan rantai. Notebook memperlihatkan forward propagation, backward propagation, serta pembaruan bobot jaringan dengan dua lapisan bobot.

### Chapter 7 — How to Picture Neural Networks: In Your Head and on Paper

Bab ini menghubungkan diagram neuron dan koneksi dengan vektor, matriks, serta kode. Notebook mereproduksi listing inti forward propagation dan menambahkan ilustrasi numerik untuk membaca shape, posisi ReLU, dan aliran sinyal gradien. Bobot untuk melengkapi diagram buku dijelaskan sebagai contoh tambahan yang disusun agar konsisten dengan angka pada ilustrasi.

### Chapter 8 — Learning Signal and Ignoring Noise: Introduction to Regularization and Batching

Bab ini membahas perbedaan memorization dan generalization melalui klasifikasi digit MNIST. Notebook mereproduksi eksperimen tanpa dropout, dengan dropout, dan dengan batch. Penjelasan mencakup overfitting, early stopping, pemantauan validation, serta rata-rata gradien batch. Implementasi pendalaman membantu memeriksa mask aktivasi, scaling dropout, dan posisi pembaruan bobot.

### Chapter 9 — Modeling Probabilities and Nonlinearities: Activation Functions

Bab ini membahas sigmoid, tanh, ReLU, dan softmax, termasuk turunan serta pemilihan fungsi output sesuai jenis target. Eksperimen utama mereproduksi jaringan MNIST dengan tanh, dropout, dan softmax selama 300 epoch. Pendalaman mencakup stabilitas softmax, cross-entropy, saturation, serta pemeriksaan numerik gradien untuk memahami aturan rantai.

### Chapter 10 — Neural Learning about Edges and Corners: Intro to Convolutional Neural Networks

Bab ini memperkenalkan local connectivity, weight sharing, kernel, dan feature map. Notebook mereproduksi CNN MNIST dengan 16 kernel berukuran 3 × 3 selama 300 epoch. Pembahasan meliputi ekstraksi patch, jumlah parameter, konsep pooling, serta backpropagation pada kernel bersama. Perilaku listing sumber dan implementasi pendalaman dijelaskan secara terpisah.

## Referensi

1. [Repository pendamping buku oleh Andrew W. Trask](https://github.com/iamtrask/Grokking-Deep-Learning).
