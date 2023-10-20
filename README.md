### A. (10%) Topik: Komunikasi dengan Manajer Produk.
1. Apakah ada batasan jumlah karakter yang diperbolehkan dalam satu baris teks sebelum dipotong menjadi 3 baris?
2. Apakah ada persyaratan desain khusus yang harus diikuti untuk mengimplementasikan "More" dan elemen-elemen lainnya?
3. Untuk logika sinkronisasi upvotes, downvotes, dan komentar dapat di implementasikan mengunakan state management redux?

### C1
1. Struktur Data:
Setiap pengguna memiliki profil yang berisi informasi pribadi dan daftar komunitas yang mereka ikuti.
Data pengguna juga harus mencakup koneksi atau hubungan dengan pengguna lain dalam sistem.
2. Jika pengguna tidak memiliki koneksi atau tidak mengikuti komunitas apa pun, dapat menggunakan algoritma rekomendasi berdasarkan profil pengguna atau aktivitas pengguna untuk memberikan rekomendasi awal.
Jika pengguna memiliki terlalu banyak koneksi atau mengikuti terlalu banyak komunitas, maka dapat mempertimbangkan untuk menyajikan rekomendasi yang lebih relevan berdasarkan sejarah interaksi mereka, seperti komunitas yang paling sering diikuti atau pengguna yang sering berinteraksi dengan mereka
3. Saya akan melakukan pengujian performance agar memastikan algoritma dapat berjalan dengan baik selain itu saya akan menguji algoritma agar memastikan apakah algoritma yang direkomendasikan pada user sudah sesuai ataukah belum

### C2- Logika
Untuk mencari saran terbaik bagi pengguna, Anda dapat mempertimbangkan faktor-faktor seperti:
1. Interaksi sebelumnya pengguna dengan item atau pengguna lain.
2. Profil dan preferensi pengguna, termasuk informasi seperti komunitas yang diikuti.
3. Popularitas dan relevansi item.
4. Faktor konteks, seperti waktu atau lokasi pengguna.
