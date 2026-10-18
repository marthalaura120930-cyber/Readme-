# Pemesanan Tiket Konser

Program ini adalah aplikasi basis terminal (CLI) sederhana yang saya buat menggunakan bahasa pemrograman **Pascal**[span_0](start_span)[span_0](end_span). Dibuat buat latihan logika pemrograman dasar, terutama penerapan array, validasi input, dan perulangan lewat studi kasus pemesanan tiket konser[span_1](start_span)[span_1](end_span).

---

## 📌 Fitur Utama

Meskipun cuma berbasis teks, fitur dasarnya sudah lumayan lengkap[span_2](start_span)[span_2](end_span):

* **Daftar Konser**: Bisa ngeliat katalog konser yang tersedia lengkap dengan harganya[span_3](start_span)[span_3](end_span).
* **Pemesanan Tiket**:
  * Tinggal pilih nomor konser dan isi berapa tiket yang mau dibeli[span_4](start_span)[span_4](end_span).
  * Ada opsi batal kalau misal salah pencet[span_5](start_span)[span_5](end_span).
  * Ada *input validation*—kalau masukin angka negatif atau nomor di luar menu, program bakal minta input ulang[span_6](start_span)[span_6](end_span).
* **Diskon Otomatis**: Pembelian **4 tiket atau lebih** langsung dapat potongan **10%**[span_7](start_span)[span_7](end_span).
* **Cek Pesanan Terakhir**: Fitur simpel buat ngeliat rincian transaksi terakhir yang berhasil dibuat[span_8](start_span)[span_8](end_span).

---

## 🎤 Konser & Harga Tiket

Data konser dan harganya masih di-hardcode langsung di dalam kodenya[span_9](start_span)[span_9](end_span):

1. **LANY** — Rp 1.500.000 / tiket[span_10](start_span)[span_10](end_span)
2. **Tulus** — Rp 500.000 / tiket[span_11](start_span)[span_11](end_span)
3. **Bernadya** — Rp 250.000 / tiket[span_12](start_span)[span_12](end_span)

*(Note: Beli 4 tiket atau lebih otomatis dapat diskon 10%[span_13](start_span)[span_13](end_span))*

---

## 🛠️ Cara Menjalankan Program

1. Copy atau unduh file `program_TIXORA.pas`[span_14](start_span)[span_14](end_span).
2. Buka aplikasi editor Pascal yang kamu pakai (misalnya **Dev-Pascal**, **Free Pascal**, atau **Turbo Pascal**)[span_15](start_span)[span_15](end_span).
3. Open/paste file kodenya di dalam editor[span_16](start_span)[span_16](end_span).
4. Tinggal klik **Compile** terus **Run** (atau tekan `F9` / `Ctrl + F9`).

---

## 🖥️ Alur Penggunaan

Begitu program jalan, kamu bakal lihat menu utama[span_17](start_span)[span_17](end_span):
* Angka `1` — Lihat daftar konser[span_18](start_span)[span_18](end_span)
* Angka `2` — Pesan tiket (pilih konser & jumlah tiket)[span_19](start_span)[span_19](end_span)
* Angka `3` — Cek pesanan terakhir[span_20](start_span)[span_20](end_span)
* Angka `4` — Keluar dari program[span_21](start_span)[span_21](end_span)

---

## 📝 Catatan Tambahan

* Pakai unit `crt` biar tampilan terminalnya bisa dibersihkan pakai `clrscr` setiap ganti menu[span_22](start_span)[span_22](end_span).
* Variabel harga dan total pembayaran pakai tipe `longint` supaya menampung angka nominal yang besar[span_23](start_span)[span_23](end_span).
* Silakan kalau mau dipakai buat bahan belajar, dimodifikasi, atau dikembangkan lagi!
* 
