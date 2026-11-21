# Simulasi CAT TPP 2027

Website latihan mandiri berbasis HTML statis. Tidak memerlukan login, backend, database, atau dashboard admin.

## Isi repositori

- `index.html` — aplikasi CAT lengkap beserta bank soal yang tertanam.
- `.nojekyll` — menonaktifkan pemrosesan Jekyll pada GitHub Pages.

## Fitur

- Pilih kategori soal dan tingkat kesulitan.
- Pilih 10, 20, 50, atau seluruh soal yang tersedia.
- Timer 30, 60, 90 menit, atau tanpa batas waktu.
- Navigasi soal dan pemeriksaan jawaban.
- Hasil latihan serta pembahasan dan referensi yang tercantum di bank soal.
- Tidak ada akun peserta atau sistem admin.

## Cara menerbitkan melalui GitHub Pages

1. Masuk ke GitHub dan buat repositori baru, misalnya `simulasi-cat-tpp-2027`.
2. Pilih **Public** agar dapat diakses umum.
3. Unggah `index.html` dan `.nojekyll` dari paket ini ke direktori utama repositori (root).
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
7. Tunggu proses publikasi selesai. GitHub akan menampilkan alamat website pada bagian Pages.

Alamat biasanya berbentuk:
`https://USERNAME.github.io/simulasi-cat-tpp-2027/`

Ganti `USERNAME` dengan nama akun GitHub pemilik repositori.

## Catatan penting

- Paket ini adalah prototipe latihan, bukan sistem seleksi resmi.
- Bank soal yang tertanam saat paket dibuat berjumlah 152 butir.
- Sejumlah soal masih berstatus REVIEW dan wajib diverifikasi terhadap regulasi serta kisi-kisi resmi sebelum dipromosikan sebagai materi tervalidasi.
- Tidak ada jawaban peserta yang dikirim ke server. Hasil hanya dihitung di browser selama sesi berjalan.
- Untuk memperbarui soal, perbarui file Excel sumber, lalu bangun ulang `index.html` dengan format data aplikasi yang sama.
