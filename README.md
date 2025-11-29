# PRAKTIKUM MOBILE FIREBASE (LIVE NOTE PROJECT)

NAMA  : MOCH FIRMAN TRISWANDA
NIM   : 362458302013
KELAS : 2B TRPL

## TUGAS
Untuk memvalidasi pemahaman Anda, kerjakan tantangan berikut di sisa waktu praktikum:

**Tugas 1**: Update Feature
Tambahkan fitur edit. Ketika ListTile ditekan (onTap), munculkan formulir yang sudah terisi data lama, dan update data tersebut di Firebase menggunakan perintah .update().
<u>DOKUMENTASI:</u>
<img width="1426" height="1274" alt="image" src="https://github.com/user-attachments/assets/3d250b30-7ad2-4928-b2fe-1227980d5201" />
<u>PENJELASAN:</u>
Atribut onTap, fungsinya untuk pemicu sentuhan. Ketika Widget disentuh, maka akan memanggil fungsi _showForm sambil membawa data lama pada document. Jadi, sebenarnya untuk menampilkan formulir pengeditan yang sudah terisi dengan data yang sudah ada, jadi pengguna dapat memperbaruinya.

<u>DOKUMENTASI:</u>
<img width="1426" height="1124" alt="image" src="https://github.com/user-attachments/assets/f700e5db-4fb7-4f9b-af67-f00cb3a91073" />
<u>PENJELASAN:</u>
Fungsi dari kode diatas, untuk memperbarui dokumen yang spesifik di Firebase Firestore. Lalu, query pada gambar itu akan mengambil catatan berdasarkan Id [doc.id], setelahnya mengganti nilai tittle lalu content lama dengan yang baru. Kode selanjutnya yaitu "timestamp": FieldValue.serverTimestamp, gunanya untuk mencatat waktu terbaru dari sisi server Firebase.

**Tugas 2**: Testing
Jalankan aplikasi di 2 device berbeda (Emulator HP Fisik atau 2 Emulator). Buktikan bahwa data tersinkronisasi secara otomatis.
<u>DOKUMENTASI:</u>
- TAMPILAN PERTAMA
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/1ed2c2fe-9ba6-45c2-b6e0-278fca676ce6" />

- INPUT FORM CATATAN
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/8ccee909-e4b3-4f01-b4a4-886063fdba1b" />

- TAMPILAN CARD
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/9901b1fc-56bf-44a1-ae3a-63e915e2451c" />

- EDIT FORM CATATAN
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/c2a24ef0-f2d2-41ec-87df-8d44db4a3950" />

- INPUT FORM CATATAN LAGI
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/0f3f04a2-066d-4c4b-9eb6-d6456af39061" />

- TAMPILAN CARD LAGI
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/f64b4b5f-b5c5-4ce6-bf43-6c7c6058d11f" />

- EDIT FORM CATATAN LAGI
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/c1a54b7c-af4b-40c6-b810-9367def64d77" />

- HAPUS CARD
<u>HASIL:</u>
<img width="576" height="1280" alt="image" src="https://github.com/user-attachments/assets/4b45c5b6-dd23-43e2-82db-db5167155fbd" />

- TAMPILAN FIRESTORE DATABASE (FIREBASE)
<u>HASIL:</u>
<img width="1600" height="860" alt="image" src="https://github.com/user-attachments/assets/fe8208f9-3ed4-4dba-a623-7f28ed62d201" />
