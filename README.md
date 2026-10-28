# Studi Ablasi RNN, LSTM, GRU vs ANN untuk Prediksi Trafik Seluler Milan

Tugas Workshop Deep Learning — Teknik Telekomunikasi, Institut Teknologi Sumatera (ITERA).

## Identitas Penulis

| Keterangan | Informasi |
|---|---|
| Nama | Vaulina Fatrisia Siburian |
| NIM | 124400011 |
| Kelas | RA |
| Kode Lokasi | 1 — Navigli (Darsena) |

## Deskripsi Proyek

Proyek ini membahas perbandingan model Artificial Neural Network (ANN), Recurrent Neural Network (RNN), Long Short-Term Memory (LSTM), dan Gated Recurrent Unit (GRU) untuk prediksi trafik seluler di Kota Milan. Pengujian dilakukan melalui eksperimen ablasi untuk melihat pengaruh perubahan konfigurasi model terhadap kinerja prediksi.

## Cara Menjalankan

1. Siapkan Python dan pustaka yang diperlukan oleh notebook.
2. Buka `tugas_ablasi.ipynb` menggunakan Jupyter Notebook atau JupyterLab.
3. Isi konfigurasi lokasi sesuai ketentuan tugas.
4. Jalankan sel notebook secara berurutan untuk melakukan eksperimen dan melihat hasilnya.

Jika proyek menggunakan `uv`, lingkungan dapat disiapkan menggunakan perintah:

```bash
uv sync
uv run jupyter lab
```

## Perangkat dan Perangkat Lunak

- Bahasa pemrograman: Python
- Lingkungan eksperimen: Jupyter Notebook
- Penulisan laporan: LaTeX melalui Overleaf
- Perangkat keras: [Isi sesuai perangkat yang digunakan]
- Waktu training: [Isi jika diketahui]

## Ringkasan Hasil

Eksperimen membandingkan kinerja ANN, RNN, LSTM, dan GRU menggunakan metrik test Mean Absolute Error (MAE). Hasil pengujian setiap model, eksperimen ablasi, serta visualisasi digunakan untuk menganalisis pengaruh konfigurasi terhadap akurasi prediksi. Nilai akhir akan disesuaikan dengan hasil eksperimen yang tersimpan pada berkas CSV.

## Struktur Proyek

- `tugas_ablasi.ipynb`: notebook eksperimen beserta output.
- `hasil/`: CSV seluruh eksperimen, tabel, dan grafik.
- `main.tex` atau folder sumber LaTeX: sumber laporan.
- File PDF: laporan akhir.
- File pendukung lainnya: aset yang diperlukan untuk eksperimen dan penyusunan laporan.

## Data

Data trafik seluler berasal dari dataset Telecom Italia Big Data Challenge dan data olahan yang digunakan dalam workshop. Rincian sumber data dan referensi dijelaskan dalam laporan.

## Kontribusi Penulis

Penulis mengerjakan persiapan data, implementasi model, eksperimen ablasi, evaluasi, analisis hasil, penyusunan visualisasi, dan penulisan laporan secara mandiri.

## Pernyataan Penggunaan AI

ChatGPT digunakan untuk membantu memperbaiki penulisan laporan dan format LaTeX. Hasil eksperimen dan angka yang dilaporkan mengacu pada pengujian yang dilakukan penulis.
