# Segmentasi Siluet Manusia Menggunakan Convolutional Neural Network (CNN)

Proyek ini bertujuan untuk melakukan segmentasi siluet manusia dari latar belakang pada dataset gambar menggunakan Convolutional Neural Network (CNN). Segmentasi siluet manusia adalah proses memisahkan gambar individu manusia dari latar belakangnya, sehingga memungkinkan untuk memanipulasi atau menganalisis bagian manusia secara terpisah.

## Langkah-langkah Pengerjaan

1. **Persiapan Dataset**: 
    - Pilih atau dapatkan dataset yang berisi gambar individu dengan siluet manusia dan latar belakang yang berbeda.
    - Pisahkan dataset menjadi set pelatihan (train set), set validasi (validation set), dan set pengujian (test set).
    - Lakukan praproses data jika diperlukan, seperti normalisasi, resizing, atau augmentasi data.

2. **Pembangunan Model CNN**: 
    - Desain arsitektur CNN yang cocok untuk tugas segmentasi siluet manusia. Contoh arsitektur yang dapat digunakan adalah U-Net.
    - Didefinisikan metrik evaluasi seperti IoU (Intersection over Union) untuk mengukur performa segmentasi.
    - Lakukan pelatihan model CNN dengan menggunakan set pelatihan sebagai input. 
    - Definisikan fungsi kerugian (loss function) seperti categorical cross-entropy atau binary cross-entropy.
    - Evaluasi model menggunakan set validasi untuk menganalisis performa segmentasi.
    - Lakukan koreksi hyperparameter jika diperlukan untuk meningkatkan performa model.

3. **Pengujian dan Evaluasi**: 
    - Uji model yang telah dilatih pada set pengujian yang tidak pernah dilihat oleh model sebelumnya.
    - Hitung metrik evaluasi seperti IoU untuk mengevaluasi sejauh mana model dapat menghasilkan segmentasi yang akurat.

4. **Analisis dan Pelaporan**: 
    - Tinjau hasil segmentasi untuk memahami di mana model berkinerja baik dan di mana ada kekurangan.
    - Buat laporan tentang hasil, dan rekomendasi untuk peningkatan di masa depan.

## Penggunaan

Pastikan untuk memiliki lingkungan Python yang sesuai dengan dependensi yang diperlukan, kemudian jalankan notebook atau script yang terkait untuk melatih dan menguji model segmentasi siluet manusia.

## Dependensi

- TensorFlow
- OpenCV
- Matplotlib
- NumPy

## KrsNovita2717
