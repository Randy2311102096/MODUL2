RANDY LAMBAS BATUBARA
2311102096
2A

Program ini berfungsi untuk mengonversi tiga input string yang dimasukkan oleh pengguna.
Program ini digunakan untuk memeriksa apakah tahun yang diinputkan oleh pengguna merupakan tahun kabisat atau bukan.
Program ini bertujuan menghitung volume dan luas permukaan sebuah bola berdasarkan jari-jari yang diberikan oleh pengguna.
Program ini berfungsi untuk mengonversi suhu Celsius yang dimasukkan oleh pengguna menjadi suhu dalam satuan Reamur, Kelvin, dan Fahrenheit.
Program ini berfungsi mengubah dua baris input pengguna; baris pertama berisi lima data integer yang akan dicetak dalam bentuk karakter, dan baris kedua berisi tiga data karakter yang akan dicetak setelah ditambahkan satu unit.
2B

Program ini bertujuan untuk memverifikasi apakah urutan empat warna yang diinputkan pengguna sudah benar atau belum, dan akan menampilkan hasil dalam bentuk boolean (true atau false).
Program ini berfungsi mencetak angka sebanyak yang dimasukkan pengguna, lalu meminta pengguna memasukkan nama bunga sebanyak n, dan nama-nama tersebut akan dirangkai dengan tanda "-" sesuai urutan input.
Program ini digunakan untuk memeriksa apakah beban belanjaan yang dibawa oleh Pak Andi akan menyebabkan motornya oleng atau tidak dengan menghitung total beban minimal serta selisih antara beban di sisi kanan dan kiri.
Program ini bertujuan menghitung akar kuadrat dari sebuah bilangan yang diinputkan oleh pengguna.
2C

Program ini digunakan untuk menghitung biaya pengiriman, dimulai dengan meminta pengguna memasukkan berat parsel dalam gram. Berat tersebut akan dikonversi ke kilogram dan sisa gram. Biaya dasar dihitung berdasarkan berat kilogram, di mana setiap kilogram dikenakan biaya sebesar Rp. 10.000.
Program ini berfungsi menghitung nilai akhir sebuah mata kuliah berdasarkan input dari pengguna dan menampilkan nilai akhir dalam bentuk huruf, seperti "A, AB, B, BC, C, D, E".
i. Jika nilai input adalah 80.1, apa keluaran dari program tersebut? Apakah eksekusi program sesuai dengan spesifikasi soal? Jawaban: Program error, karena tidak konsisten. Variabel "nam" dideklarasikan sebagai float64, tetapi di dalam blok if, program mencoba memberikan nilai string ("A", "AB", dll.) pada "nam".

ii. Apa saja kesalahan dalam program tersebut? Jelaskan alur yang seharusnya! Jawaban: Kesalahan program adalah sebagai berikut:

Program tidak konsisten. Variabel "nam" dideklarasikan sebagai float64, tetapi mencoba memasukkan string di blok if.
Kondisi if bersifat independen, sehingga jika "nam" lebih besar dari beberapa batas, beberapa blok if akan dijalankan berturut-turut dan nilai "nmk" ditimpa beberapa kali. Misalnya, jika "nam" = 80.1, beberapa kondisi akan terpenuhi, menyebabkan "nmk" menjadi "D", yang tidak sesuai spesifikasi.
Perbaikan Program:

Gantilah "nam = 'A'" dengan "nmk = 'A'", dan seterusnya.
Gunakan else if untuk memastikan hanya satu kondisi yang terpenuhi.
iii. Perbaiki program tersebut! Uji dengan masukan: 93.5; 70.6; dan 49.5. Hasil yang diharapkan adalah 'A', 'B', dan 'D'.

Program ini bertujuan membuktikan apakah suatu bilangan yang diinputkan oleh pengguna merupakan bilangan prima atau bukan dengan cara mencari faktornya.
