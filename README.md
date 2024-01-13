# Capstone-project-2-Andi-M.-Al-Fayed
project ini mengambil data fiksi dari Perusahaan SaaS yang kemudian menggunakan data fiksi tersebut untuk membuat ranking berdasarakan


- Profitability : Profit yang dibawa oleh produk dan menunjukkan seberapa menguntungkan suatu produk untuk sebuah perusahaan.
- Sales Revenue : Jumlah produk yang sudah terjual menunjukkan popularitas suatu produk dan seberapa penting produk tersebut dan permintaan.
- Geography     : Menunjukkan persebaran produk dan kuantitas produk. 
- Evergreen     : Menunjukkan kapabilitas produk secara sales dalam rentang waktu.

kemudian menggunakan metode composite rank untuk membuat rank keseluruhan untuk menentukan produk terbaik dari kumpulan produk.

Penentuan weight dari setiap aspek dibuat berdasarkan asumsi perusahaan. Untuk analisis data kali ini, penentuan weight adalah:

- Profitability    : 0.4
- Sales Performance: 0.3
- Geography        : 0.2
- Evergreen        : 0.1
  
Profitability merupakan aspek terpenting untuk dari setiap performa produk oleh karena itu aspek ini mendapatkan weight terbesar. Untuk Sales performance mendapatkan weight kedua terbesar karena menunjukkan popularitas dari produkd dan kontribusi kepada revenue. Geography menunjukkan persebaran produk dan kuantitas produk sehingga mendapatkan weight ketiga terbesar. Dan evergreen mendapatkan rangking terakhir karena dengan adanya perkembangan teknologi, produk bisa berubah dari digunakan menjadi ditinggalkan. Inilah aspek beserta weight yang digunakan untuk analisis ini.

Metode ini membuat profit sebagai weight terbesar dan seterusnya hingga evergreen sebagai weight terkecil. Sehingga bisa dibilan analisis ini digunakan untuk mencari
produk terbaik dengan profit sebagai konsiderasi utama
