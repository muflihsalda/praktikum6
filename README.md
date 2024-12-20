# praktikum6
Nama: Muflih Salda Maulana

NIM: 312410527

Kelas: TI.24.A.5

# penjelasan program
Daftar Mahasiswa:

![image](https://github.com/user-attachments/assets/71125f6a-aa79-4d0b-b7e4-8fdfaa4bafd9)


Program dimulai dengan mendeklarasikan list kosong bernama mahasiswa yang akan menyimpan data mahasiswa dalam bentuk dictionary.

Fungsi tambah(nama, nilai):

![image](https://github.com/user-attachments/assets/0092a8a9-7a65-45ed-ae85-a490dce17f39)


Fungsi ini digunakan untuk menambahkan data mahasiswa ke dalam list mahasiswa. Data yang ditambahkan adalah nama dan nilai mahasiswa.
Setelah menambahkan data, fungsi ini akan mencetak pesan konfirmasi.

Fungsi tampilkan():

![image](https://github.com/user-attachments/assets/9af5c215-bdff-470f-8c03-f41fc27bb2c9)


Fungsi ini menampilkan semua data mahasiswa dalam format tabel.
Jika tidak ada data mahasiswa, fungsi ini akan mencetak pesan bahwa tidak ada data yang tersedia.
Jika ada data, fungsi ini mencetak tabel dengan nama dan nilai mahasiswa.

Fungsi hapus(nama):

![image](https://github.com/user-attachments/assets/a80d5ec1-0380-4c23-bf1b-e5e4660117f2)


Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan nama.
Fungsi ini akan menyaring list mahasiswa untuk menghapus entri yang memiliki nama yang sesuai.
Setelah menghapus data, fungsi ini mencetak pesan konfirmasi.

Fungsi ubah(nama, nilai_baru):

![5](https://github.com/user-attachments/assets/dc7ec219-31ea-43ea-b783-5cf33b1dd67b)


Fungsi ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama.
Fungsi ini mencari mahasiswa dengan nama yang diberikan dan mengubah nilai mereka jika ditemukan.
Jika nama tidak ditemukan, fungsi ini akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

Bagian if __name__ == "__main__"::

![image](https://github.com/user-attachments/assets/f78f3356-3732-4a31-a70a-d1a56aa14c26)

Bagian ini adalah loop utama yang akan terus berjalan hingga pengguna memilih untuk keluar.
Menampilkan menu pilihan kepada pengguna untuk memilih operasi yang diinginkan.
Mengambil input dari pengguna dan memanggil fungsi yang sesuai berdasarkan pilihan pengguna.

# hasil program
![hasil program1](https://github.com/user-attachments/assets/c683b8fd-1132-4d8b-b7cf-63aa7173854d)


![hasil program2](https://github.com/user-attachments/assets/34a2fae6-fb20-4ba6-8a32-61226d03adcf)

# Flowchart
Berikut adalah flowchart yang menggambarkan alur kerja program:

![flowchart](https://github.com/user-attachments/assets/b176f81d-2e09-427c-805d-1e68b71df4c1)


Penjelasan Flowchart
(Mulai Program): Titik awal dari program.

(Tampilkan Menu): Menampilkan pilihan menu kepada pengguna.

(Pilih Menu): Pengguna memilih salah satu opsi dari menu.

(Tambah Data Mahasiswa): Jika pengguna memilih untuk menambah data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Tampilkan Data Mahasiswa): Jika pengguna memilih untuk menampilkan data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Hapus Data Mahasiswa): Jika pengguna memilih untuk menghapus data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Ubah Data Mahasiswa): Jika pengguna memilih untuk mengubah data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Keluar dari Program): Jika pengguna memilih untuk keluar, program akan berhenti.

(Tidak Valid): Jika pilihan tidak valid, program akan kembali ke langkah untuk menampilkan menu.
