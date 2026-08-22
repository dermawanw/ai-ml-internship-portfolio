# Rencana Belajar AI/ML 52 Minggu

Mulai: 24 Agustus 2026  
Selesai: 22 Agustus 2027  
Target waktu: 8-10 jam per minggu  
Target akhir: siap melamar magang AI/ML dengan 3 proyek utama, 4 bukti lomba, dan GitHub yang mudah dinilai recruiter.

## Aturan utama

1. Level tidak naik tanpa bukti: commit GitHub, skor lomba, demo, atau hasil tes.
2. Belajar teori maksimal 40%; sisanya menulis kode, menguji, dan menjelaskan hasil.
3. Jika tertinggal, materi tidak ditumpuk. Kerjakan versi penyelamatan 10 menit.
4. Ranking lomba bukan target pertama. Target pertama adalah submission valid dan laporan yang jujur.
5. Satu spesialisasi dipilih setelah Intermediate. Jangan mempelajari semua cabang sekaligus.

## Ritme mingguan

- Senin-Jumat: 2 sesi x 25 menit per hari.
- Sabtu: 3 jam untuk proyek atau lomba.
- Minggu: 90 menit untuk review, README, dan rencana pekan berikutnya.
- Selesai berarti ada bukti, bukan hanya menonton video.

## Empat level

| Level | Tanggal | Fokus | Hasil wajib |
|---|---|---|---|
| 0 - Fondasi dari nol | 24 Agu-18 Okt 2026 | Python, terminal, Git/GitHub, NumPy, pandas, SQL, grafik | 40 latihan, 1 mini EDA, 1 submission lomba |
| 1 - Beginner | 19 Okt 2026-21 Feb 2027 | matematika intuitif, EDA, classical ML, evaluasi, pipeline, PyTorch | `tabular-baseline` dan `mnist-from-scratch-to-pytorch` |
| 2 - Intermediate terpilih | 22 Feb-13 Jun 2027 | Transformer, Hugging Face, embeddings, structured output, RAG, evaluasi, API | `indonesian-docs-rag` dengan eval, API, Docker, dan CI |
| 3 - Advanced-lite + magang | 14 Jun-22 Agu 2027 | monitoring, latency, safety, portofolio, wawancara, lamaran | deploy, 3 repo terpin, 3 mock interview, 30 lamaran |

Total rencana sekitar 450 jam. Ini bukan usaha menamatkan semua isi PDF. Bagian multi-node FSDP, full fine-tuning model besar, RLHF, custom CUDA/Triton kernel, Kubernetes tingkat lanjut, dan semua spesialisasi tambahan ditunda sampai setelah magang karena mahal dan bukan syarat utama portofolio pemula.

## Jadwal lomba yang mengikat

Status sumber diperiksa pada 23 Agustus 2026.

| Level | Lomba | Tenggat pribadi | Bukti lulus |
|---|---|---|---|
| 0 | [Kaggle Titanic](https://www.kaggle.com/competitions/titanic) | join 24 Agu; submission pertama 6 Sep; perbaikan 4 Okt; final 18 Okt 2026 | submission valid + repo + README singkat |
| 1 | [Zindi Financial Inclusion in Africa](https://zindi.world/competitions/financial-inclusion-in-africa) | join 19 Okt; baseline 8 Nov; perbaikan 10 Jan; final 21 Feb 2027 | submission valid + model mengalahkan baseline sendiri |
| 2 | [DrivenData Pump It Up](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) | join 22 Feb; baseline 21 Mar; perbaikan 2 Mei; final 13 Jun 2027 | submission valid + pipeline reproducible + error analysis |
| 3 | [DrivenData Conser-vision](https://www.drivendata.org/competitions/87/competition-conservation-imagery/) | join 14 Jun; baseline 4 Jul; perbaikan 1 Agu; final 22 Agu 2027 | submission valid + transfer learning + laporan biaya/latensi |

Titanic memakai rolling leaderboard. Zindi menyatakan lomba belajarnya aktif, tidak akan ditutup, dan terbuka untuk semua negara. Pump It Up berlabel `intermediate practice`; Conser-vision berlabel `advanced practice`. Kompetisi DrivenData dapat diperpanjang, sehingga pengingat mingguan akan memeriksa status sebelum join. Jika usia belum 18 tahun atau aturan kompetisi tidak mengizinkan, gunakan kompetisi Kaggle Getting Started yang setara. Jangan unggah data lomba ke GitHub; hanya kode, konfigurasi, skor, dan petunjuk memperoleh data.

## Peta materi per blok

### Level 0 - Minggu 1-8

1. Minggu 1-4: Python - variabel, tipe data, kondisi, loop, fungsi, file, dan error.
2. Minggu 5-6: terminal, Git/GitHub, NumPy, pandas, dan grafik.
3. Minggu 7: SQL dasar, EDA, fitur, target, dan train/test.
4. Minggu 8: rapikan mini-proyek dan submission Titanic.

Gate: 40 latihan selesai; satu repo EDA dapat dijalankan ulang; dapat membuat commit, branch, dan pull request; serta satu submission valid.

### Level 1 - Minggu 9-26

1. Minggu 9-12: vektor/matriks, turunan, probabilitas, statistik secara visual.
2. Minggu 13-16: EDA, missing value, split, leakage, preprocessing.
3. Minggu 17-20: regresi, tree, random forest, boosting, metrik, cross-validation.
4. Minggu 21-23: feature engineering dan pipeline.
5. Minggu 24-26: neural network, backprop, PyTorch, MNIST, reproducibility.

Gate: pipeline tabular punya baseline, CV, tidak leakage, dan reproducible; NumPy MLP mencapai minimal 95% serta PyTorch CNN minimal 99% di MNIST; submission lomba mengalahkan baseline sendiri.

### Level 2 - Minggu 27-42

1. Minggu 27-30: CNN, Transformer, dan attention.
2. Minggu 31-34: NLP, Hugging Face, embeddings, prompting, JSON terstruktur.
3. Minggu 35-38: RAG, retrieval, reranking, dan evaluasi.
4. Minggu 39-42: FastAPI, Docker, CI, lomba, dan demo.

Gate: dapat menjelaskan kapan memilih prompting, RAG, atau fine-tuning; RAG memiliki minimal 50 pertanyaan uji, Recall@5 minimal 0,80, cakupan sitasi minimal 95%, JSON valid 100/100, API, Docker, dan CI.

### Level 3 - Minggu 43-52

1. Minggu 43-46: logging, latency, keamanan, pengujian, dan deployment.
2. Minggu 47-49: rapikan GitHub, CV, demo, dan latihan wawancara.
3. Minggu 50-52: final lomba, 30 lamaran magang berkualitas, dan cadangan keterlambatan.

Gate: aplikasi dapat diakses, memiliki log dan ukuran latency, lolos minimal 10 uji keamanan dasar, tiga repo terpin, tiga mock interview, serta 30 lamaran magang berkualitas.

## Portofolio untuk magang

Tiga repo utama lebih kuat daripada dua puluh notebook acak:

1. `financial-inclusion-tabular-ml`: masalah nyata, EDA, leakage check, pipeline, CV, tracking eksperimen.
2. `mnist-from-scratch-to-pytorch`: NumPy manual lalu PyTorch, gradient check, dan grafik perbandingan.
3. `indonesian-docs-rag`: retrieval, citations, minimal 50 kasus eval, FastAPI, Docker, CI, dan demo.

Setiap README wajib menjawab: masalah apa, mengapa pendekatan dipilih, bagaimana cara kerja, metrik apa, hasil apa, kesalahan apa, dan cara menjalankannya dalam lima menit.

## Minggu pertama

| Hari | Tugas | Bukti |
|---|---|---|
| Senin | cek Python dan Git; jalankan `print("Halo, AI")` | keluaran terminal |
| Selasa | variabel dan tipe data | commit `day-02-types` |
| Rabu | `if`, input, dan validasi sederhana | commit `day-03-if` |
| Kamis | loop dan list | commit `day-04-loop` |
| Jumat | fungsi | commit `day-05-function` |
| Sabtu | buat program penghitung nilai sederhana | link repo/commit |
| Minggu | jelaskan program tanpa membaca kode | jawaban 5 kalimat |

## Definisi menang

- Minimum: 80% sesi selesai, empat submission valid, tiga repo rapi, satu aplikasi online, dan 30 lamaran magang yang disesuaikan.
- Bagus: ada kontribusi open source, satu write-up teknis, dan satu proyek dipakai orang lain.
- Tidak wajib: memenangkan lomba, GPU mahal, menguasai seluruh roadmap, atau menghafal semua rumus.

