<h1>LAPORAN HASIL EKSPLORASI DAN ANALISIS DATA</h1>
<h2> 1. Eksplorasi Data</h2>
Pada analsis data, data set berisikan sejumlah baris dan kolom yang menunjukkan jumlah sampel dan variabel yang tersedia. Dari dataset kita dapat menemukan jumlah dari kolom, baris, nilai yang hilang dan perlu diperhatikan, serta outliers yang dapat mempengaruhi hasil analisis
<h3>1.1. Nama Dataset</h3>
Judul Dataset : Stunting Toddler (Balita) Detection <br/>
Link : https://www.kaggle.com/datasets/rendiputra/stunting-balita-detection-121k-rows
<h3>1.2. Deskripsi Dataset</h3>
Pada deskripsi dataset dapat berupa numeric dan object.<br/>
1. Umur (Bulan): Mengindikasikan usia balita dalam bulan.<br/>
2. Jenis Kelamin: Terdapat dua kategori dalam kolom ini, 'laki-laki' dan 'perempuan'.<br/>
3. Tinggi Badan: Dicatat dalam centimeter, tinggi badan adalah indikator utama untuk menilai pertumbuhan fisik balita.<br/>
4. Status Gizi: Kolom ini dikategorikan menjadi 4 status - 'severely stunting', 'stunting', 'normal', dan 'tinggi'. 'Severely stunting' menunjukkan kondisi sangat serius, 'stunting' menunjukkan kondisi stunting, 'normal' mengindikasikan status gizi yang sehat, dan 'tinggi' menunjukkan pertumbuhan di atas rata-rata. <br/>
<h3>1.3. Identifikasi Dataset</h3>
1. Jumlah baris data set : 120999 <br/>
2. Jumlah kolom data set : 4 <br/>
3. Missing Value : 0 <br/>
4. Outliers : terdapat 38 data outliers pada data Tinggi Badan (cm)<br/>
<h2>2. Analisis Statistik Data</h2>
Statistik seperti rata-rata, median, mode, standar deviasi, variansi, skewness, dan kurtosis digunakan untuk memahami distribusi dan karakteristik data numerik dalam dataset. Ini memberikan gambaran awal tentang data yang dianalisis.
<h3>2.1 Mean</h3>
- Umur (bulan) : rata - rata umur dari sampel yang diambil adalah sekitar umur 30 bulan <br/>
-Tinggi Badan(cm) : dari rata - rata didapatkan bahwa sampel memiliki tinggi badan sekitar 88.66 cm
<h3>2.2. Median</h3>
- Umur (bulan) : dari hasil analasis didapatkan bahwa dari sampel umur setengah dari sampel memiliki umur di bawah 30 bulan dan setengahnya lagi di atas 30 bulan.<br/>
- Tinggi (cm) : dari hasil analasis didapatkan bahwa dari sampel tinggi badan  setengah dari sampel memiliki tinggi badan di bawah 89.8 cm dan setengahnya lagi di atas 89.8 cm.
<h3>2.3. Mode (modus) </h3>
- Umur (bulan) : dari hasil analisis, sampel banyak diambil dari umur 1 bulan.<br/>
- Tinggi Badan (cm) : dari hasil analisis diketahui tinggi dari kebanyakkan sampel adalah 89.8 cm
<h3>2.4. Standar Deviansi</h3>
- Umur (bulan) : besar variasi atau penyebaran umur dalam sampel adalah  umur 17.58 bulan<br/>
- Tinggi Badan (cm) : besar variasi atau penyebaran umur dalam sampel adalah 17.30 cm
<h3>2.5. Variansi</h3>
- Umur (bulan) : kuadrat dari standar deviasi dan menunjukkan variasi umur dalam sampel adalah 308.88<br/>
- Tinggi badan (cm) : kuadrat dari standar deviasi dan menunjukkan variasi tinggi badan dalam sampel adalah 299.32
<h3>2.6. Skewness </h3>
- Umur ( bulan) : dengan nilai -0.0155, kemiringan yang hampir nol ini menunjukkan bahwa distribusi umur hampir simetris, meskipun sedikit miring ke kiri.<br/>
- Tinggi badan (cm) : dengan nilai -0.2655, kemiringan mengukur asimetri distribusi data. Nilai negatif menunjukkan distribusi miring ke kiri (lebih banyak data di sisi kanan).
<h3>2.7. Kurtosis</h3>
- Umur (bulan) : Kurtosis negatif ini menunjukkan bahwa distribusi umur lebih datar dibandingkan dengan distribusi normal.<br/>
- Tinggi badan (cm) : Kurtosis untuk tinggi badan adalah -0.4005, yang menunjukkan distribusi data lebih datar dibandingkan dengan distribusi normal. Ini berarti data tinggi badan memiliki lebih sedikit nilai ekstrem.
<h2>3. Korelasi Pada Dataset</h2>
Korelasi menunjukkan hubungan antara pasangan variabel numerik. Korelasi tinggi antara dua variabel bisa menjadi indikasi hubungan yang kuat dan bisa digunakan dalam model prediktif. Pada dataset, analisa yang didapatkan adalah nilai kolerasi 0,84 yang dimana ini menunjukkan bahwa semakin bertambah umur balita,tinggi badannya cenderung meningkat.<br/><br/>
<img src ="https://github.com/user-attachments/assets/004b8916-3c85-4f0a-9554-05595fbea53c" width=500/>
<h2>4. Visualisasi Data</h2>
<h3>4.1. Histogram</h3><br/>
<img src="https://github.com/user-attachments/assets/16aa9d0b-8722-4046-880b-e337053445c3" width=500/>
<h3>4.2. Box Plot</h3>
<img src="https://github.com/user-attachments/assets/d202fef9-02d9-4eb4-a9d7-68f10513c6b1" width=500/>
<h3>4.3. Scatter Plot</h3>
<img src="https://github.com/user-attachments/assets/36dce0d6-2cf3-4892-9db0-ed3ea2be6c9c" width=500/>
<h2>5. Kesimpulan</h2>
Berdasarkan dataset tersebut didapatkan hasil analisa yaitu rata rata sampel diambil dari umur 30 bulan dan rata rata tinggi sampel adalah 88.66 cm. Umur yang terbanyak dalam data sampel adalah umur 1 bulan dan tinggi badan terbanyak terdapat pada 89.8 cm. Hasil analasis juga didapatkan bahwa dari sampel umur setengah dari sampel memiliki umur di bawah 30 bulan dan setengahnya lagi di atas 30 bulan dan ari sampel tinggi badan  setengah dari sampel memiliki tinggi badan di bawah 89.8 cm dan setengahnya lagi di atas 89.8 cm. Pada dataset ini terdapat missing value pada sampel kolom tinggi badan sebanyak 38 data.Pada datset ini juga memiliki nilai kolerasi 0,84 anatara umur dan tinggi badan, yang dimana ini menunjukkan bahwa semakin bertambah umur balita maka tinggi badannya cenderung meningkat pula. Pada dataset ini juga, dalam distribusi menunjukkan distribusi yang tidak normal dikarenakan terdapat penurunan yang tajam pada usia yang lebih tinggi sehingga tidak simetris. Sedangkan, pada distribusi data tinggi badan  menunjukkan distribusi yang hampir normal dikarenakan terlihat dari distribusinya yang tidak simetris atau condong ke kiri, yang dimana berarti sebagian anak memiliki tinggi badan yang relatif lebih rendah.

