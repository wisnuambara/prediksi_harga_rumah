# Analisis Prediksi Harga Rumah di Tebet, Jakarta Selatan

Proyek ini bertujuan untuk membangun model *Machine Learning* menggunakan algoritma **Multiple Linear Regression** untuk memprediksi harga jual properti di wilayah Tebet, Jakarta Selatan, berdasarkan fitur-fitur fisik bangunan.

## 📌 Deskripsi Proyek
Penentuan harga rumah di Jakarta seringkali sangat fluktuatif. Dengan menggunakan dataset yang berisi 1.010 data properti, proyek ini menganalisis hubungan antara Luas Tanah (LT), Luas Bangunan (LB), jumlah Kamar Tidur (KT), Kamar Mandi (KM), dan Garasi (GRS) terhadap harga jual.

**Hasil Utama:**
- Model berhasil mencapai nilai **R-Squared (R2) sebesar 0.77 (77%)**.
- Fitur Luas Bangunan dan Luas Tanah ditemukan sebagai faktor paling dominan dalam menentukan harga.

## 📂 Struktur Repository
- `UAS_2301020085.ipynb`: Notebook utama berisi proses pembersihan data, EDA, dan pemodelan.
- `data_harga_rumah_tebet.csv`: Dataset yang digunakan (pastikan nama file sesuai dengan yang Anda upload).
- `requirements.txt`: Daftar library Python yang dibutuhkan.
- `README.md`: Instruksi proyek (file ini).

## 🛠️ Instalasi & Persiapan
Ikuti langkah-langkah di bawah ini untuk menjalankan proyek ini di komputer lokal Anda:

1. **Clone Repository:**
   ```bash
   git clone [https://github.com/USERNAME_ANDA/NAMA_REPO_ANDA.git](https://github.com/USERNAME_ANDA/NAMA_REPO_ANDA.git)
   cd NAMA_REPO_ANDA
   
2.  Buat Virtual Environment (Opsional tapi disarankan):
    Bash
    python -m venv venv
    source venv/bin/activate  # Untuk Linux/Mac
    # atau
    venv\Scripts\activate     # Untuk Windows
    
3. Instal Library yang Dibutuhkan:
  Bash
  pip install -r requirements.txt


### Cara Menjalankan ###
1. Jalankan aplikasi Jupyter Notebook atau VS Code.

2. Buka file UAS_2301020085.ipynb.

3. Pastikan file dataset berada di folder yang sama dengan notebook.

4. Jalankan seluruh sel (Run All Cells) untuk melihat hasil analisis dan visualisasi.

### Ringkasan Metrik Model ###
- Algorithm: Multiple Linear Regression

- R-Squared: 0.7713

- MAE: Rp 1.980.345.761

- RMSE: Rp 3.267.373.421

### Penulis ###
Nama: I Komang Wisnu Ambara
NIM: 2301020085
Instansi: Informatika - Universitas Primakara
