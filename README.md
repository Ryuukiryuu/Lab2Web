<img width="937" height="660" alt="Screenshot 2025-09-29 132459" src="https://github.com/user-attachments/assets/55af0005-9df8-4285-bcbd-b1b6dd7a8f60" />

**Tampilan awal**

Di tahap ini, HTML sudah dibuat tapi belum ada internal CSS.<h3><h3 style="font-size:14px; font-weight:normal; color:#0F189F;">
</h3>
Teks masih pakai default style browser:<h3>
Judul tampil besar dan tebal hitam.<h3>
Link <a> berwarna biru standar.<h3>
Paragraf <p> berwarna hitam, font default Times New Roman.<h3>
Artinya ini masih tampilan dasar HTML tanpa styling tambahan<h3>




#Tampilan Kedua#




<img width="958" height="1078" alt="Screenshot 2025-09-29 141522" src="https://github.com/user-attachments/assets/5d65b431-083f-431f-aeb3-fd8cee7d9b12" />




(setelah ditambahkan CSS internal & inline)
sudah menambahkan internal CSS di <head> dengan tag <style>.
Contohnya:
body {
  font-family: 'Open Sans', sans-serif;
}
h1 {
  font-size: 24px;
  color: #0F189F;
  text-align: center;
  padding: 20px 10px;
}
h1 i {
  color: #6d6a6b;
}


#Perubahan yang terlihat:#
-<h1> (judul) jadi biru tua dan rata tengah.
-<i> di dalam <h1> (kata Inline CSS) berubah warna abu-abu.
-Font keseluruhan berubah dari Times New Roman ke sans-serif.
-<p> sudah diberi inline CSS → style="text-align: center; color: #ccd8e4;" sehingga teks paragraf jadi rata tengah dengan warna abu-abu kebiruan.


Gambar 3

<img width="950" height="1071" alt="Screenshot 2025-09-29 142021" src="https://github.com/user-attachments/assets/f0bc0293-36fa-4ce9-a7ff-b6561ef2cefe" />


#Sebelum Styling (HTML Dasar)#
-Tampilan halaman web yang masih sangat sederhana dengan karakteristik:
-Judul "CSS Internal dan Inline CSS" di bagian atas
-Navigasi hijau dengan 3 tombol: "CSS Dasar", "CSS Eksternal", "HTML Dasar"
-Teks "Hello World" berwarna biru tua/navy
-Paragraf penjelasan dengan warna abu-abu terang (hampir tidak terlihat)
-Link "Informasi selengkapnya" berwarna biru standar
-Background putih polos
-Layout minimal tanpa styling khusus


Gambar 4

<img width="963" height="1078" alt="Screenshot 2025-09-29 142105" src="https://github.com/user-attachments/assets/4d293257-574e-4ab7-818d-502db293d64b" />



#Setelah Styling (Dengan CSS)#
Tampilan halaman web yang sudah diberi styling CSS dengan perubahan:###
-Perubahan Visual:-
-Background biru to-sca/teal menutupi sebagian besar halaman-
-Teks "Hello World" sekarang berwarna putih dan lebih kontras-
-Paragraf sekarang berwarna putih dan mudah dibaca dengan latar biru-
-Button "Informasi selengkapnya" berubah menjadi:-
-Background merah-
-Teks putih-
-Bentuk kotak dengan padding yang jelas-

#Teknik CSS yang Digunakan:#
-Kemungkinan besar menggunakan kombinasi:
-CSS Internal (di dalam tag <style> di HTML) untuk styling umum
-Inline CSS (langsung di tag HTML) untuk styling spesifik
-Perubahan warna background, font color, padding, dan styling button


