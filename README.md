# Tugas Individu: Manipulasi Citra Digital Menggunakan OpenCV

Projek ini dibuat untuk memenuhi tugas mata kuliah **Pengolahan Sinyal Digital**. Eksperimen ini berfokus pada teknik manipulasi dasar citra digital menggunakan Python dan OpenCV, serta analisis dampaknya terhadap piksel, kecerahan, kontras, dan detail citra.

## 👥 Identitas Mahasiswa
- **Nama:** [Masukkan Nama Kamu]
- **NIM:** [Masukkan NIM Kamu]
- **Mata Kuliah:** Pengolahan Sinyal Digital

## 📂 Struktur Repositori
- `image_manipulation.ipynb` : File Jupyter Notebook utama berisi seluruh code eksperimen (Bagian A - F).
- `laporan.pdf` : Laporan resmi hasil analisis eksperimen dan studi kasus HOTS.
- `README.md` : Dokumentasi utama repositori ini.

## 🛠️ Library yang Digunakan
Projek ini berjalan menggunakan platform Kaggle Notebook dengan library pendukung:
- `opencv-python` (OpenCV)
- `numpy`
- `matplotlib`

## 📈 Eksperimen yang Dilakukan
1. **Bagian A & B:** Membaca citra, konversi format warna BGR ke RGB, dan resize ukuran citra secara seragam.
2. **Bagian C:** Penggabungan dua citra (*Image Blending*) menggunakan 3 variasi kombinasi bobot berbeda.
3. **Bagian D:** Pembuatan citra negatif beserta analisis perubahan pada grafik histogramnya.
4. **Bagian E & F:** Penerapan transformasi non-linear berupa Transformasi Logaritmik dan Koreksi Gamma dengan 4 nilai parameter berbeda ($\gamma = 0.5, 1.0, 2.0, 2.5$).
5. **Bagian G & H:** Analisis tingkat tinggi (HOTS) terkait pemecahan studi kasus pencahayaan citra dan refleksi pembelajaran.