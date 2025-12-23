# tubes-AI
program fuzzy dengan metode Mamdani untuk menghasilkan nilai kredit skor 

PETUNJUK MENJALANKAN PROGRAM
SISTEM FUZZY MAMDANI – PENENTUAN RISIKO KREDIT

CARA MENJALANKAN PROGRAM DI GOOGLE COLAB DAN ALUR PROSES
a. Buka Google Colab melalui https://colab.research.google.com, kemudian copy paste codingan 
b. Upload file resiko_kredit.xlsx ke dalam lingkungan Google Colab  
c. Masukkan dan jalankan kode program secara berurutan  
d. Program membaca data pengaju dari file resiko_kredit.xlsx  
e. Sistem melakukan fuzzifikasi variabel gaji ke dalam himpunan linguistik:
   - Rendah
   - Medium
   - Tinggi
   - Sangat Tinggi  
f. Sistem melakukan fuzzifikasi variabel persentase cicilan ke dalam himpunan:
   - Kecil
   - Sedang
   - Besar
   - Sangat Besar  
g. Proses inferensi Mamdani dijalankan menggunakan aturan fuzzy
   dengan operator MIN–MAX untuk menentukan tingkat risiko kredit  
h. Sistem melakukan defuzzifikasi menggunakan metode centroid
   untuk memperoleh skor risiko kredit  

5. OUTPUT PROGRAM
Program menghasilkan keluaran berupa:
- Skor risiko kredit setiap pengaju
- Tabel 10 pengaju dengan risiko kredit terendah
- Grafik fuzzifikasi variabel gaji (Model Mamdani)
- Grafik fuzzifikasi variabel persentase cicilan (Model Mamdani)

6. CATATAN
Pastikan file Excel memiliki kolom:
- Gaji
- Persentase_Cicilan

Perbedaan nama kolom dapat menyebabkan program tidak berjalan.
