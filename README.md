<h2 align="center">📘 <b>Analisis Putusan Pengadilan – Dataset dan Ringkasan</b> 📘</h2>

Repositori ini berisi dataset dan ringkasan putusan pengadilan yang digunakan untuk keperluan penelitian atau pengembangan sistem berbasis analisis teks hukum, seperti Case-Based Reasoning (CBR), Text Classification, atau Information Retrieval.

---

*📂 Struktur Folder*
bash
.
├── dataset/
│   └── dataset.zip
│
└── overview/
    └── ringkasan_putusan.csv

*🧾 Penjelasan:*

- dataset/
Folder ini berisi file *dataset.zip* yang memuat data putusan pengadilan dalam bentuk teks lengkap atau format terstruktur lainnya.
Dataset ini dapat digunakan untuk pemrosesan lanjutan seperti ekstraksi fitur, text embedding, atau analisis isi.

- overview/
Folder ini berisi file *ringkasan_putusan.csv* yang merupakan hasil ringkasan dari dataset utama.
File ini berisi beberapa kolom penting:

| Kolom           | Deskripsi |
|-----------------|------------|
| *nomor_putusan* | Nomor unik setiap putusan pengadilan |
| *lembaga_putusan* | Lembaga yang mengeluarkan putusan (misalnya: Mahkamah Agung, Pengadilan Negeri, dll.) |
| *barang_bukti* | Informasi terkait barang bukti yang tercantum dalam putusan |
| *amar_putusan* | Ringkasan hasil atau keputusan akhir dari putusan tersebut |

---

*🧠 Tujuan*

Repositori ini dibuat untuk mendukung penelitian dalam bidang:
- Analisis teks hukum berbasis NLP (Natural Language Processing)
- Sistem rekomendasi kasus hukum (Case-Based Reasoning)
- Mesin Pencarian pada kasus hukum

---

*⚙ Cara Menggunakan*

1. Clone repositori ini:
bash
git clone https://github.com/username/nama-repo.git

2. Ekstrak dataset:
bash
cd dataset
unzip dataset.zip

3. Gunakan file *ringkasan_putusan.csv* sebagai data ringkasan untuk eksplorasi awal atau pelatihan model.

--- 

*📊 Format Data*

Contoh isi *ringkasan_putusan.csv*:
| Nomor Putusan | Lembaga Pengadilan | Barang Bukti | Amar Putusan |
|:--------------|:------------------:|--------------:|---------------|
| 16/Pid.Sus/2023/PN Mad | PN Kota Madiun | - 1 (satu) Unit Ponsel Merk OPPO Type A3S Warna Merah kombinasi hitam dengan nomor simcard 082139462594 | Menyatakan Terdakwa *KUNTARTO alias ANTON Bin (Alm) SAMPURNO* telah terbukti secara sah dan meyakinkan bersalah melakukan tindak pidana “tanpa hak menjadi perantara dalam jual beli Narkotika golongan I” sebagaimana dalam dakwaan tunggal Penuntut Umum;<br>Menjatuhkan pidana kepada KUNTARTO alias ANTON Bin (Alm) SAMPURNO dengan pidana penjara selama 9 (Sembilan) tahun dan denda sejumlah *Rp 800.000.000,00* (delapan ratus juta rupiah), dengan ketentuan apabila denda tersebut tidak dibayar maka diganti dengan pidana penjara selama 1 (satu) tahun;<br>Membebankan kepada Terdakwa untuk membayar biaya perkara sejumlah *Rp 5.000,00* (lima ribu rupiah). |

---

*👩‍💻 Kontributor*
- Yunita Sangadji - Mahasiswa Teknik Informatika – Universitas Muhammadiyah Malang
- Annisaa Salsabila - Mahasiswa Teknik Informatika – Universitas Muhammadiyah Malang
