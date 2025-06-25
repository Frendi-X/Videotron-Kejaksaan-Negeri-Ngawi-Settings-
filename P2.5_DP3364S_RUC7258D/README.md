# Videotron Kejaksaan Negeri Ngawi - Settings

Dokumentasi ini menjelaskan chip yang digunakan serta fungsi dan kegunaan file dalam pemrograman videotron di lingkungan Kejaksaan Negeri Ngawi.

---

## 🔧 Spesifikasi Chip yang Digunakan

### 1. **DP3364S**
- **Jenis:** Driver Chip LED Display  
- **Fungsi:** Mengatur sinyal tampilan piksel dan sinkronisasi data antar panel LED.  
- **Keterangan Tambahan:**  
  Chip ini umum digunakan untuk kebutuhan refresh rate tinggi dan mendukung tampilan warna yang stabil, terutama pada videotron luar ruang (_outdoor display_).

### 2. **RUC7258D**
- **Jenis:** Receiver Card / Decoder Chip  
- **Fungsi:** Menerima dan mendekode data dari pengontrol utama (_sending card_) ke panel videotron.  
- **Keterangan Tambahan:**  
  Berperan dalam menyusun ulang data tampilan secara _real-time_ agar sesuai dengan tata letak panel videotron.

---

## 📁 Kegunaan File

File ini digunakan untuk memprogram pengaturan tampilan videotron, termasuk:

- Konfigurasi modul LED  
- Mapping pixel  
- Pengaturan refresh rate  
- Komunikasi antar panel menggunakan kombinasi chip **DP3364S** dan **RUC7258D**

File mencakup parameter teknis, skrip konfigurasi, serta firmware yang kompatibel dengan kontroler LED yang digunakan pada videotron Kejaksaan Negeri Ngawi.

---

## 📝 Catatan

> Setiap update konfigurasi harus disesuaikan dengan layout fisik panel dan jenis kontroler LED.  
> Backup file konfigurasi disimpan untuk keperluan pemeliharaan atau jika terjadi reset sistem.

---

📦 **Struktur Folder**
