Jawaban Pertanyaan Analisis & Konsep

1. Challenge 2: Pertanyaan git status (Halaman 6)
   Pertanyaan: Apa arti hasil git status?
   Jawaban: git status digunakan untuk melihat kondisi working directory dan staging area. Perintah ini menampilkan branch yang sedang aktif, file mana yang telah diubah (modified), file baru yang belum dilacak (untracked), serta file yang sudah siap di-commit (staged).

2. Challenge 3: Pertanyaan Analisis (Halaman 7)  
   Pertanyaan: Mengapa setiap developer tidak langsung bekerja pada main?  
   Jawaban: Branch main harus selalu berisi kode yang stabil, bersih, dan siap rilis/diproduksi. Jika semua developer langsung mengedit main, kode bisa mengalami bentrok (conflict), berisiko membawa bug ke proyek utama, dan mengganggu pekerjaan anggota tim lainnya.

3. Challenge 5: Pertanyaan Pesan Commit (Halaman 10)  
    Pertanyaan: Apa perbedaan pesan commit git commit -m "update" dan git commit -m "Menambahkan halaman profil kelas"? Mana yang lebih baik?  
   Jawaban:Pesan "update" sangat ambigu/umum dan tidak memberikan informasi spesifik mengenai apa yang diubah.Pesan "Menambahkan halaman profil kelas" bersifat informatif, kontekstual, dan menjelaskan perubahan secara spesifik.Yang lebih baik: Pesan kedua ("Menambahkan halaman profil kelas") karena memudahkan riwayat melacak fitur atau perbaikan kode di masa mendatang.

4. Challenge 11: Pertanyaan Analisis Sinkronisasi (Halaman 14)
   Pertanyaan 1: Apa fungsi git pull? Jawaban: git pull berfungsi untuk mengambil (fetch) dan menggabungkan (merge) perubahan terbaru dari repository remote (GitHub) ke repository lokal di komputer kita.
   Pertanyaan 2: Apa yang terjadi jika programmer tidak melakukan git pull?
   Jawaban: Kode di local repository akan ketinggalan zaman (outdated). Hal ini berpotensi menyebabkan conflict saat hendak mengirim perubahan baru atau menyebabkan fitur yang dikembangkan tidak kompatibel dengan kode tim terbaru.
   Pertanyaan 3: Mengapa main harus dijaga agar tetap stabil? Jawaban: Karena branch main merupakan representasi dari produk akhir/versi produksi. Jika main rusak atau mengalami error, seluruh proyek dianggap bermasalah dan aplikasi tidak dapat digunakan atau dirilis.

5. Challenge 12: Pertanyaan Conflict (Halaman 15-16)  
   Pertanyaan 1: Mengapa conflict terjadi? Jawaban: Conflict terjadi ketika dua developer mengubah baris kode yang sama pada file yang sama secara berbeda, dan Git tidak dapat menentukan otomatis perubahan mana yang harus dipakai.
   Pertanyaan 2: Apakah conflict berarti Git rusak? Jawaban: Tidak. Conflict adalah fitur pengaman dari Git untuk mencegah penimpaan kode secara tak sengaja tanpa persetujuan developer.Pertanyaan 3: Siapa yang harus menentukan versi kode yang benar? Jawaban: Developer yang mengalami conflict bersama dengan pemilik kode terkait (atau tim/Project Manager) melalui diskusi.
   Pertanyaan 4: Mengapa komunikasi antar programmer penting? Jawaban: Agar pembagian tugas jelas, mencegah pengubahan file/baris yang sama secara bersamaan, menyamakan persepsi fitur, serta mempermudah penyelesaian conflict dan code review.

Panduan Jawaban Refleksi Individu & AkhirSection AC: Refleksi Individu (Halaman 19) (Contoh isi sesuai pengalaman praktikum)
Perbedaan bekerja sendiri vs Git/GitHub: Bekerja sendiri membuat manajemen berkas manual dan berisiko menimpa kode. Bekerja dengan Git/GitHub terstruktur, mencatat riwayat perbaikan, serta mendukung kolaborasi tim tanpa saling mengganggu.
Manfaat branch: Mengisolasi fitur/eksperimen baru agar tidak merusak kode utama (main).
Mengapa Pull Request diperlukan: Untuk memastikan kode yang dibuat ditinjau (review) terlebih dahulu sebelum digabungkan ke main.
Manfaat Code Review: Menjaga kualitas kode, menemukan bug lebih awal, dan saling belajar standar penulisan kode di dalam tim.
Error paling sulit: (Diisi sesuai pengalaman, misal: Git Push Rejected / Merge Conflict).
Cara menemukan solusi: Membaca pesan error, diskusi tim, dan mencari solusinya di dokumentasi/AI.Kontribusi terbesar: (Diisi peran masing-masing, misal: Membuat halaman profil.html dan mereview Pull Request tim).
Kebiasaan profesional yang dipertahankan: Membuat branch terpisah untuk fitur baru, menulis pesan commit yang informatif, dan melakukan code review.

Section AE: Refleksi Akhir (Halaman 21) Sebelum belajar GitHub, saya berpikir bahwa... membuat aplikasi dalam tim dilakukan dengan cara saling mengirimkan file proyek secara manual (misal lewat flashdisk atau chat).
Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa... pengembangan aplikasi tim dilakukan secara sistematis menggunakan alur kerja branch, Pull Request, dan Code Review.Kesalahan/error yang saya alami mengajarkan saya bahwa... error bukan tanda kegagalan, melainkan petunjuk untuk membaca pesan dengan cermat dan memahami alur kerja kode.Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan... selalu berkomunikasi aktif dengan tim, mengikuti alur kerja branch, serta menjaga branch main tetap bersih dan stabil.
