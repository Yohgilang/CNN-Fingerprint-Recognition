# CNN-Fingerprint-Recognation

[100 0 0 1]

- 100 --> subject ID
- 0 --> gender (male 0, female 1)
- 0 --> left_or_right_hand (left 0, right 1)
- 1 --> finger index (0-4)


Pengambilan data user secara acak dari datasets yang dimasukkan. Ditampilkan output berupa gambar kiri input user, tengah hasil yang sesuai, kanan hasil yang tidak sesuai.  Menerapkan beberapa augmentasi (gaussian blur, zoom, translation, rotation) ke input random image. Gambar tengah adalah jawabannya sehingga memiliki akurasi hingga 99%, sebaliknya gambar kanan salah sehingga memiliki akurasi 0%.  Berdasarkan salah satu hasil di atas, gambar kiri sama dengan gambar tengah sehingga hasil match (cocok/sama) dengan code [425 1 0 3] dan akurasi 99.61862%.


Dataset:
https://www.kaggle.com/ruizgara/socofing/home
