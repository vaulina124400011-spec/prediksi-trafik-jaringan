# Studi Ablasi RNN, LSTM, GRU vs ANN untuk Prediksi Trafik Seluler Milan

Tugas Workshop Deep Learning — Teknik Telekomunikasi ITERA.

## Data Pribadi

| Peran | Nama | NIM |
|---|---|---|
| Penulis | Vaulina Fatrisia Siburian | 124400011 |

- **Kelas:** RA
- **Lokasi:** Kode 1 — Navigli (Darsena)
- **Laporan:** PDF laporan tersedia di repositori GitHub.

## Cara Menjalankan

Pastikan Python dan `uv` sudah terpasang. Jalankan perintah berikut di terminal pada folder proyek:

```bash
uv sync
uv run jupyter lab
```

Buka `tugas_ablasi.ipynb`, sesuaikan variabel `LOKASI_KELOMPOK`, lalu jalankan sel-sel notebook sesuai urutan.

## Perangkat yang Digunakan

- **Perangkat keras:** Laptop dengan RAM 4 GB dan prosesor Intel.
- **Perangkat lunak:** Windows dan Python, dengan lingkungan proyek yang dikelola menggunakan `uv`.

## Ringkasan Hasil

Eksperimen membandingkan ANN, RNN, LSTM, dan GRU untuk prediksi trafik seluler. Berdasarkan hasil pengujian awal, nilai test MAE terbaik yang tercatat adalah ANN 270,7; RNN 224,5; LSTM 245,6; dan GRU 220,3. Hasil ini merupakan hasil eksperimen yang telah dijalankan dan perlu ditafsirkan sesuai konfigurasi serta jumlah pengulangan yang digunakan.

## Struktur Repositori

```text
tugas_ablasi.ipynb   Notebook eksperimen beserta output
data/                Data trafik
hasil/               CSV, tabel, dan grafik eksperimen
main.tex             Sumber laporan LaTeX
references.bib       Referensi laporan
PDF laporan          Laporan akhir dalam format PDF
README.md            Petunjuk dan ringkasan proyek
```

## Data

Data berasal dari Telecom Italia Big Data Challenge (Barlacchi dkk., 2015, *Scientific Data*, lisensi ODbL), menggunakan versi per jam yang dirujuk dari Zhang dkk. (INFOCOM 2021). Data disiapkan oleh pengajar melalui repositori [mctosima/dl-workshop](https://github.com/mctosima/dl-workshop).

## Penggunaan AI

AI digunakan sebagai alat bantu dalam proses pembelajaran, penjelasan kode, dan penyusunan laporan. Pelaksanaan eksperimen dan hasil yang dilaporkan harus sesuai dengan kode serta hasil yang benar-benar dijalankan.
