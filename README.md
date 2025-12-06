# Module-17-3.5-Intermediate
3.5 Optimasi dan Benchmarking Inference LLM: Dari Batching hingga Kuantisasi

# Hands-on Komdigi: Modul 3.5 - High-Performance Inference dengan vLLM 🚀

Selamat datang di *repository hands-on* untuk **Modul 3.5 (Advance): Optimasi Inference**.

**Tujuan:**
Di modul ini, kita beralih dari "Pelatihan" ke "Penyajian" (*Serving*). Kita akan menggunakan *inference engine* tercepat di dunia open-source, **vLLM**, untuk membuktikan bagaimana optimasi memori bisa melipatgandakan kecepatan aplikasi Anda.

**Materi Praktik:**
1.  **Baseline Benchmark:** Mengukur kecepatan model standar.
2.  **vLLM & PagedAttention:** Menjalankan model dengan engine teroptimasi.
3.  **Quantization (AWQ):** Menjalankan model terkompresi (4-bit) untuk efisiensi maksimal.
4.  **Health Check:** Membuat skrip monitoring sederhana untuk mengukur Throughput.

**Prasyarat:**
* Akun Google Colab.
* **Wajib GPU Runtime (T4):** vLLM tidak berjalan di CPU.

---

## Cara Menjalankan Notebook

Klik *badge* di bawah untuk membuka *notebook* langsung di Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1leJJod5MdIdjMxEf33j2HyOFWQKrTqq4?usp=sharing)

**Hasil yang Diharapkan:**
Anda akan melihat perbandingan langsung di mana vLLM (terutama versi AWQ) menghasilkan teks jauh lebih cepat (Token/detik lebih tinggi) dan memakan memori lebih sedikit dibandingkan metode standar.
