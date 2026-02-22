# C-LiveLearn: Media Pembelajaran Algoritma Pemrograman C

Repositori ini berisi rancangan awal media pembelajaran interaktif untuk materi algoritma dan pemrograman bahasa C.

## Tujuan
- Membantu pemula belajar C secara bertahap dari konsep paling dasar.
- Menyediakan jalur belajar berbasis materi, tantangan live coding, dan latihan adaptif ala Duolingo.
- Menyediakan latihan evaluasi untuk mengukur penguasaan setiap topik.

## Komponen Produk
1. **Materi Inti**
   - Algoritma dan logika dasar.
   - Struktur bahasa C.
   - Sintaks dasar C.
   - Input-output (`printf`, `scanf`).
   - Percabangan (`if-else`, `switch-case`).
   - Perulangan (`for`, `while`, `do-while`).
   - Array.
   - Fungsi.

2. **Kartu Tantangan Live Coding**
   - Tantangan bertingkat dari level paling mudah ke paling sulit.
   - Setiap kartu memiliki tujuan, batasan, contoh input/output, dan kriteria lulus.

3. **Latihan Struktur Kode (Duolingo Mode)**
   - Drag-and-order potongan kode.
   - Fill-in-the-blank sintaks.
   - Tebak output program.
   - Perbaiki bug singkat.

4. **Latihan Soal Evaluasi**
   - Soal pilihan ganda per materi.
   - Soal coding singkat otomatis.
   - Penilaian berbasis tingkat akurasi dan waktu.

## Struktur Konten
- `content/curriculum.md`: urutan materi dan learning outcome.
- `content/challenge_cards.md`: katalog kartu tantangan live coding.
- `content/duolingo_mode.md`: desain latihan struktur kode.
- `content/assessment_bank.md`: bank soal evaluasi kemampuan.

## Langkah Selanjutnya
1. Bangun MVP berbasis web (frontend + engine evaluasi sederhana).
2. Simpan soal dan tantangan dalam format JSON agar mudah diperluas.
3. Integrasikan auto-check output untuk latihan coding.
4. Tambahkan dashboard progres belajar pengguna.
