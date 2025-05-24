# PerancanganWeb-DesainGrafis-BisDig

1. Promo.html
Menggunakan div sebagai canvas yang berisi image yang diambil secara online dengan memasukan link gambar kedalam src, container div berisi judul (h2) dan deskripsi (p), lalu container div yang berisi komponen tombol (button) berisikan tulisan "Daftar Sekarang"

2. Tampilan_komentar.html
Menggunakan div sebagai canvas yang berisikan komponen profil (img, nama, dan keterangan waktu) dan paragraf (p) yang berisikan tema artikel.
lalu dibawah nya ada tombol yang dapat digunakan untuk menampilkan/menyembunyikan bagian komentar dengan memanggil fungsi javascript. fungsi tersebut akan terpanggil apabila tombol di klik oleh pengguna. isi dari fungsi tersebut ada 2 kemungkinan:
- jika komponen tombol mempunyai kelas "hidden", maka itu akan dihilangkan, dengan begitu komponen komentar akan tampil
- jika komponen tombol tidak mempunyai kelas "hidden", maka akan ditambahkan kedalam kelas, dengan begitu komponen komentar akan disembunyikan.
fungsi ini dapat meng-edit kelas yang ada di komponen ini:
<div id="commentSection" class="mt-4 hidden">
sebenarnya, komponen komentar itu ada secara eksplisit, tapi disembunyikan karena instruksi "hidden"

3. Situs_portofolio.html
Portfolio tersebut dibungkus dengan canvas div yang mempunyai batas lebar maksimal 800 pixel, jadi komponen akan menyesuaikan layar dibawah 800 pixel. 
Media query pada styling CSS digunakan untuk mengadakan pembatas perubahan style pada komponen profile, berikut kemungkinannya:
- Apabila dimensi perangkat diatas 768 pixel (Laptop, PC) maka foto akan berada di samping nama dan profesi
- Apabila dimensi perangkat dibawah 768 pixel (Smartphone) maka foto akan berada di atas nama dan profesi, dan juga layout tulisan yang berada di tengah

4. Fotographer.html
Dalam halaman ini ada header yang berisi nama dan role. lalu ada main yang berisi 3 section yang berisi biodata, portfolio, dan contact section. lalu ada footer yang menampilkan hak cipta

5. Konsultasi.html
Halaman ini dibuat dengan hirarki yang berisi komponen nya masing masing dan diperlukan. warna yang dipakai oleh halaman ini juga dibuat konsisten agar memenuhi kebutuhan pengalaman user (User Experience). selain user, pengembang juga dapat mengimplementasikan dengan lebih mudah karena kode dibuat tersusun hierarki nya.

