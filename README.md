# Penggunaan grafik dengan Python: Cara terbaik python adalah visualisasi.

## LINE CHART (GRAFIK GARIS)
Line chart paling tepat digunakan untuk menunjukkan tren dari waktu ke waktu. Sumbu X biasanya mewakili periode waktu, sumbu Y menggambarkan nilai/kuantitas. Contohnya jumlah penjualan/ penggunaan dari pekan ke pekan selama satu tahun.Grafik ini dapat memuat banyak titik data yang dapat diatur saling berdekatan sesuai kerapatan periode waktu. Karena visualnya yang simpel, bisa menggunakan banyak garis sekaligus dalam satu tampilan. Ini memudahkan penggambaran data tren dari beragam kategori.

| Dokumentasi Kode | Dokumentasi Luaran |
| ----------- | ----------- |
| ![Dokumentasi Kode](<img width="429" alt="image" src="https://github.com/suryaningsih608/uas_pbo/assets/136007421/9f179514-42d1-40b3-be1f-3cc7603bd627">) | ![Dokumentasi Luaran](![image](https://github.com/suryaningsih608/uas_pbo/assets/136007421/13e1f487-8ccb-4f66-ab7b-f0bdb5c39bb7)) |


#### PENJELASAN 
Source Code diatas adalah sebuah script dalam bahasa Python yang menggunakan pustaka Matplotlib untuk membuat diagram garis (line chart) yang menggambarkan persentase pengguna berbagai bahasa pemrograman yang sedang popular pada tahun 2023. Fungsi tight_layout() digunakan agar elemen-elemen plot tidak tumpang tindih. Fungsi show() menampilkan plot secara keseluruhan.




## BAR CHART (GRAFIK BATANG)
Bar Chart paling cocok untuk komparasi data dengan banyak kategori atau rangkaian data (data series). Untuk kemudahan membaca data, dapat mengurutkan kategori berdasarkan besar nilainya, misal dari nilai tertinggi hingga terendah. Lain halnya dengan data series, di mana data didistribusikan berdasarkan kategori berjenjang, misalnya populasi penduduk berdasarkan rentang usia atau tingkat pendidikan dan penggunaan bahasa pemograman.

| Dokumentasi Kode | Dokumentasi Luaran |
| --- | --- |
| ![Dokumentasi Kode](<img width="407" alt="image" src="https://github.com/suryaningsih608/uas_pbo/assets/136007421/f5b9619b-3253-4aa6-b531-c40d537b9fcb">) | ![Dokumentasi Luaran](![image](https://github.com/suryaningsih608/uas_pbo/assets/136007421/e19c7daf-4152-42e2-b9f2-5fb8003e7944)) |


#### PENJELASAN
Source Code diatas adalah sebuah script dalam bahasa Python yang menggunakan pustaka Matplotlib untuk membuat diagram batang (Bar Chart) yang menggambarkan persentase pengguna berbagai bahasa pemrograman pada tahun 2023. Kode ini kurang lebih sama dengan kode sebelumnya dimana Kode ini mengimpor dua modul dari pustaka Matplotlib, yaitu pyplot untuk membuat plot dan style untuk mengatur gaya plot dan  10 mengatur gaya plot menggunakan gaya ggplot dari Matplotlib. 


## PIE CHART (GRAFIK/DIAGRAM LINGKARAN)
Pie Chart digunakan untuk menggambarkan komposisi antarbagian pada suatu kesatuan utuh. Bagian ini biasanya direpresentasikan dalam satuan persen sehingga jika seluruh bagian dijumlahkan, hasilnya sama dengan seratus persen. Jenis grafik ini akan mudah dipahami jika kategori yang ditampilkan tidak banyak, misal 5 bagian. Semakin banyak bagiannya, apalagi jika proposinya sangat kecil, akan kian sulit membacanya

| Dokumentasi Kode | Dokumentasi Luaran |
| --- | --- |
| ![Dokumentasi Kode](<img width="437" alt="image" src="https://github.com/suryaningsih608/uas_pbo/assets/136007421/90353566-e6be-4867-bdbc-4eebf7ea544f">) | ![Dokumentasi Luaran](![image](https://github.com/suryaningsih608/uas_pbo/assets/136007421/1966d651-5c51-44de-b802-fcce793b4866)) |


#### PENJELASAN
Source Code diatas adalah script dalam bahasa Python yang menggunakan pustaka Matplotlib untuk membuat diagram lingkaran (pie chart) yang menggambarkan persentase pengguna berbagai bahasa pemrograman pada tahun 2023.Kodenya pun kurang lebih sama dengan kode sebelumnya seperti Kode ini mengimpor dua modul dari pustaka Matplotlib, yaitu pyplot untuk membuat plot dan style untuk mengatur gaya plot dan Mengatur gaya plot menggunakan gaya 'ggplot' dari Matplotlib. Kemudian Menyediakan data yang akan digunakan untuk membuat plot.

## GELOMBANG SINUS
Gelombang sinusoidal adalah salah satu dari bentuk gelombang yang penting di Teknik Elektro. Gelombang sinus sangat penting dalam bidang fisika karena gelombang ini 13 mempertahankan bentuknya ketika ditambahkan kepada gelombang sinus berfrekuensi sama yang lain walaupun fasenya berbeda. Gelombang ini merupakan satu-satunya fungsi periodik yang memiliki sifat ini, menjadikan gelombang ini bagian penting dalam Analisis Fourier.

| Dokumentasi Kode | Dokumentasi Luaran |
| --- | --- |
| ![Dokumentasi Kode](<img width="423" alt="image" src="https://github.com/suryaningsih608/uas_pbo/assets/136007421/143342d7-bc79-42ab-8a59-de8b02111619">) | ![Dokumentasi Luaran](![image](https://github.com/suryaningsih608/uas_pbo/assets/136007421/fd1b9af4-c795-42e4-9e02-8ac604e2d284)) |


#### PENJELASAN
Source Code diatas adalah membuat plot gabungan yang menggambarkan persentase pengguna bahasa pemrograman pada tahun 2023 dan contoh 15 gelombang sinus. Kode ini mengimpor modul NumPy untuk manipulasi array, dan modul Matplotlib untuk membuat plot dan mengatur gaya plot menggunakan gaya 'ggplot' dari Matplotlib.


## GRAFIK (SEMUA GRAFIK DIDALAM SATU KODE)
| Dokumentasi Kode | Dokumentasi Luaran |
| --- | --- |
| <img width="353" alt="image" src="https://github.com/suryaningsih608/uas_pbo/assets/136007421/be3c31e9-c709-4344-b16a-303b4f33963e"> | ![Dokumentasi Luaran](![image](https://github.com/suryaningsih608/uas_pbo/assets/136007421/a5cd6774-070e-457f-afb3-6ab70625a7a6)) |


#### PENJELASAN
Source Code diatas adalah membuat empat subplot yang menampilkan berbagai jenis plot berbeda, termasuk line chart, pie chart, Bar Chart, dan plot gelombang sinus. Kode ini mengimpor modul NumPy untuk manipulasi array, dan modul Matplotlib untuk membuat plot dan mengatur gaya plot menggunakan gaya 'ggplot' dari Matplotlib juga menyediakan data yang akan digunakan untuk membuat plot persentase pengguna bahasa pemrograman. Selanjutnya kits dapat membuat data untuk contoh gelombang sinus dengan menggunakan NumPy dan Membuat subplot untuk Line chart yang menampilkan persentase pengguna bahasa pemrograman. Dan selanjutnya kita dapat membuat subplot untuk Pie Chart yang menampilkan persentase pengguna bahasa pemrograman dan kemudian membuat subplot untuk Bar Chart yang menampilkan persentase pengguna bahasa pemrograman dan membuat subplot untuk plot gelombang sinus. Dan selanjutnya yang terakhir Menampilkan semua subplot secara bersamaan. Fungsi tight_layout() digunakan agar elemen-elemen plot tidak tumpang tindih. Fungsi show() menampilkan plot secara keseluruhan.




# KESIMPULAN 
Dengan menggunakan Python kita dapat membuat grafik apapun dengan mudah, dan untuk membuatnya Library/pustaka Python, dalam membuat penggunaan grafik pada Python, dalam membuat grafik ada beberapa ada tahapan Library yang dapat digunakan misalnya Matplotlib, Visualisasi Panda, Seaborn, ggplot dan Plotly dll. Disini kami menggunakan Matplotlib untuk penggunaakn pustakanya. Dan menambahkan kode kode perintah seperti diatas pada pembahasan.

# SARAN
Pada pembuatan tugas ini kami menyarankan sebelum menggunakan kode pada pyhton dalam oop sangat harus memahaminya terlebih dahulu karena jika tidak paham ap aitu pyhton dalam oop maka pada saat proses pembuatan akan terjadi error atau tidak bisa di jalankan.
