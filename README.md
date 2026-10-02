# 2418056DataCleansing

# Deskripsi
Project ini merupakan proses data cleansing pada dataset data karyawan perusahaan. Dataset yang digunakan merupakan data dummy sebanyak 30 data karyawan dengan beberapa informasi seperti ID Karyawan, Nama, Jenis Kelamin, Departemen, Jabatan, Kota, Status, dan Tanggal Masuk.
Data awal dibuat dalam kondisi yang memiliki beberapa ketidakkonsistenan pada penulisan dan format data. Oleh karena itu, dilakukan proses data cleansing menggunakan Python dan Pandas untuk membuat data menjadi lebih rapi, konsisten, dan siap digunakan untuk pengolahan data selanjutnya.

# Tujuan
Tujuan dari project ini adalah:
- Membersihkan dataset karyawan yang masih memiliki format tidak konsisten.
- Menyeragamkan penulisan data.
- Menyeragamkan format tanggal.
- Menghasilkan dataset yang lebih rapi dan mudah dibaca.
- Memahami proses data cleansing menggunakan Python dan Pandas.
- Membandingkan kondisi data sebelum dan sesudah dilakukan cleansing.

# Dataset
Dataset yang digunakan merupakan dataset dummy data karyawan perusahaan dengan jumlah 30 data.
Dataset memiliki beberapa kolom, yaitu:
- ID_karywan
- Nama
- Jenis_Kelamin
- Dapartemen
- Jabatan
- Kota
- Status
- Tanggal_Masuk

## Permasalahan Data
Pada dataset awal terdapat beberapa data yang belum konsisten, terutama pada penulisan nama, departemen, jabatan, kota, status, dan format tanggal masuk. Beberapa data menggunakan huruf besar dan kecil yang berbeda, 
seperti `malang`, `MALANG`, dan `Malang`,serta `aktif`, `AKTIF`, dan `Aktif`. 
Selain itu, format tanggal juga masih berbeda-beda seperti `12/01/2022`, `2022-02-15`, `15-03-2022`, dan `2022/05/10`. 
Oleh karena itu, data perlu dibersihkan dan diseragamkan agar lebih rapi, konsisten, dan mudah diolah.

## Proses Data Cleansing
Proses data cleansing dilakukan menggunakan Python dengan library Pandas melalui Google Colab.
Tahapan proses yang dilakukan meliputi:
1. Membaca dataset karyawan menggunakan Python.
2. Mengecek isi dan kondisi dataset.
3. Membersihkan spasi yang tidak diperlukan.
4. Menyeragamkan penulisan nama karyawan.
5. Menyeragamkan penulisan departemen.
6. Menyeragamkan penulisan kota.
7. Menyeragamkan penulisan status karyawan.
8. Menyeragamkan penulisan jabatan.
9. Menyeragamkan format tanggal masuk.
10. Mengecek kembali data setelah proses cleansing.
11. Menyimpan hasil akhir ke dalam file Excel.

## Hasil
Setelah dilakukan proses data cleansing, dataset menjadi lebih rapi dan konsisten.
Beberapa perubahan yang dihasilkan yaitu:
- Penulisan nama menjadi lebih seragam.
- Penulisan departemen menjadi konsisten.
- Penulisan kota menjadi seragam.
- Status karyawan menggunakan format yang sama.
- Penulisan jabatan menjadi konsisten.
- Format tanggal masuk diseragamkan.

  ## Output
  **`2418056_Datacleansing.ipynb`**
Berisi coding Python yang digunakan untuk melakukan proses data cleansing.

## Google Drive
Dataset kotor dan dataset bersih dapat dilihat melalui:
**[(https://drive.google.com/drive/folders/1ZR70wUSKzpOW70yN5oib3EeTp0AhQaJ8?usp=sharing)]**


# Google Colab
Coding proses data cleansing dapat dilihat melalui:
**[](https://colab.research.google.com/drive/1TKkzGMlGbKJ1ssA0vLnlnxmkB3pM1mn8?usp=sharing)]**


