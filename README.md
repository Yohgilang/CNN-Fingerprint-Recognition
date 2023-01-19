# CNN-Fingerprint-Recognation

- Convolutional Neural Network (CNN) merupakan salah satu jenis neural network yang biasa digunakan pada data image. CNN bisa digunakan untuk mendeteksi dan mengenali object pada sebuah image. Secara garis besarnya, CNN memanfaatkan proses konvolusi dengan menggerakan sebuah kernel konvolusi (filter) berukuran tertentu ke sebuah gambar, komputer mendapatkan informasi representatif baru dari hasil perkalian bagian gambar tersebut dengan filter yang digunakan.
- Pengenalan sidik jari merupakan bagian dari teknologi biometrik yang masih digunakan sampai saat ini untuk mengidentifikasi karakteristik unik pada diri manusia. Sidik jari digunakan untuk keperluan pengenalan kembali identitas orang dengan cara mengamati garis yang terdapat pada guratan garis jari tangan atau telapak kaki.


![2](https://user-images.githubusercontent.com/93894711/213533761-d9b54e07-9356-43bb-bf0e-8bde52ddf710.jpg)

[100 0 0 1]

- 100 --> subject ID
- 0 --> gender (male 0, female 1)
- 0 --> left_or_right_hand (left 0, right 1)
- 1 --> finger index (0-4)


![1](https://user-images.githubusercontent.com/93894711/213533408-19de2151-9d2c-40df-bd50-4c6b5243530a.jpg)

Hasil dari proses pengenalan sidik jari yaitu pengambilan data user secara acak dari datasets yang dimasukkan. Ditampilkan output berupa gambar kiri input user, tengah hasil yang sesuai, kanan hasil yang tidak sesuai.  Menerapkan beberapa augmentasi (gaussian blur, zoom, translation, rotation) ke input random image. Gambar tengah adalah jawabannya sehingga memiliki akurasi hingga 99%, sebaliknya gambar kanan salah sehingga memiliki akurasi 0%.  Berdasarkan salah satu hasil di atas, gambar kiri sama dengan gambar tengah sehingga hasil match (cocok/sama) dengan code [425 1 0 3] dan akurasi 99.61862%.


Dataset:
https://www.kaggle.com/ruizgara/socofing/home
