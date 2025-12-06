- Nama Mahasiswi: Shofi Dzaliha
- NPM: 14022300035
- Mata Kuliah: Pemrograman Mobile

---
Nama Aplikasi = Aplikasi To-Do List Sederhana

Deskripsi Singkat = To-Do List adalah aplikasi pencatatan tugas sederhana berbasis Flutter yang dirancang dengan gaya UI Neubrutalism yang unik dan modern.
Aplikasi ini membantu pengguna mengelola daftar tugas mereka dengan mudah, cepat, dan interaktif melalui fitur tambah, lihat detail, tandai selesai, serta hapus tugas.
Semua state dikelola secara efisien dengan ChangeNotifier sehingga aplikasi tetap ringan dan responsif.

Fitur-Fitur :
1. Tambah Tugas
Pengguna dapat menambahkan tugas baru melalui halaman khusus dengan form input.
2. Daftar Tugas (Home Page)
Menampilkan semua tugas yang telah dibuat, Tampilan menggunakan desain Neubrutalism (kotak tebal, warna terang, shadow kasar), Fitur tugas pencarian berdasarkan kata kunci.
3. Detail Tugas
Menampilkan informasi lengkap seperti judul dan tanggal pembuatan, Tombol untuk menandai tugas selesai / belum selesai .
4. Hapus Tugas
Dapat menghapus tugas secara permanen dari halaman detail.
5. Manajemen Status Otomatis
Gunakan TaskManager + InheritedNotifier untuk manajemen status yang bersih dan ringan.
6. UI Antimainstream & Modern
Desain Neubrutalisme yang tegas dan ceria, Warna cerah, garis tebal, shadow offset khas.

Cara Menjalankan = Pastikan Flutter SDK sudah terinstal. Buka folder project menggunakan VS Code. Jalankan perintah "flutter run" di terminal. Lalu biarkan sistem berjalan dan jikalau ada pilihan, pilihlah nomer 2 atau 3 untuk output di chrome atau di edge.

Screenshoot Halaman :
Halaman Awal
<img width="1911" height="931" alt="image" src="https://github.com/user-attachments/assets/4f2f7f84-72e0-4e0f-bf08-e5e009b4bb65" />
Menu Filter
<img width="1910" height="937" alt="image" src="https://github.com/user-attachments/assets/9ad39666-46fd-4f78-8224-d9b4caf1def3" />
Menu Tambah Tugas
<img width="1918" height="938" alt="image" src="https://github.com/user-attachments/assets/c3454fbd-daac-4fd8-b61c-2be2dbdf61e4" />
Menu Edit Tugas
<img width="1919" height="936" alt="image" src="https://github.com/user-attachments/assets/26e55c37-0819-4aa2-8e17-8c4771d4705d" />
Menu Pengaturan
<img width="1915" height="928" alt="image" src="https://github.com/user-attachments/assets/6db360ac-c627-4712-8077-dbe9f1564112" />
Menu Detail Tugas
<img width="1917" height="932" alt="image" src="https://github.com/user-attachments/assets/b62d7b28-05de-4811-8153-9b57f65efa92" />

Rencana Pengembangan Fitur :
1️⃣ Penyimpanan Data (Penyimpanan Lokal)
Agar data tugas tidak hilang ketika aplikasi ditutup; SharedPreferences → untuk penyimpanan sederhana; Hive Database → untuk penyimpanan cepat & ramah offline; SQLite (sqflite) → jika membutuhkan relasi & query lebih kompleks
2️⃣ Kategori / Label Tugas
Pengguna dapat memberi label pada tugas, seperti: Pekerjaan, Pribadi, Kuliah, Belanja, Prioritas, UI dapat menggunakan kategori chip.
3️⃣ Prioritas Tugas
Tugas bisa memiliki tingkat: Tinggi, Sedang, Rendah. Digunakan untuk penyortiran atau highlight warna.
4️⃣ Tema sistem ikuti otomatis
5️⃣ Notifikasi Pengingat (Notifikasi Lokal)
Pengguna bisa mengatur: Pengingat, Notifikasi harian, Peringatan batas waktu, Menggunakan: flutter_local_notifications
6️⃣ Sinkronisasi Cloud (Opsional)
Agar tugas data tersimpan di server & bisa digunakan multi-perangkat: Firebase Firestore, MongoDB Atlas melalui API, Supabase
7️⃣ Fitur Drag & Drop Untuk Urutan Tugas
Agar pengguna dapat mengurutkan tugas secara manual.
8️⃣ Animasi yang Lebih Halus
Menggunakan: AnimatedContainer, Hero animations, Lottie animations, Agar aplikasi terasa lebih modern.
9️⃣ Filter & Sortir
Tombol filter seperti: Hanya Selesai, Hanya Tertunda, Berdasarkan Prioritas, Berdasarkan Kategori. Sorting seperti: Bahasa A–Z, Z–A, Tanggal pembuatan
🔟 Dashboard Produktivitas
Statistik berbentuk grafik: Jumlah tugas yang diselesaikan per hari/minggu/bulan, Kemajuan total. Menggunakan: fl_chart, charts_flutter
1️⃣1️⃣ Kalender Sinkronisasi
Tugas bisa langsung masuk ke: Kalender Google, iCal
1️⃣2️⃣ Pengaturan Halaman
Pengaturan: Tema, Cadangan, Notifikasi, Setel Ulang Data


