# Praktikum_AI_Sistem_Pakar
Untuk menyelesaikan tugas praktikum Kecerdasan Buatan

dalam tugas ini saya mengerjakan 6 modul fungsi yang dimana fungsinya berbeda beda dan metode yang digunakan juga berbeda.
diawali degan enginstal sebuah package experta sebagai pengatur dependency. Terkadang pada saat install library, library tersebut membutuhkan library lain untuk dapat bekerja.
kemudian saya juga menginstal mengimplementasikan koleksi beku (dict, list dan set) yang dapat di-hash, diberi petunjuk tipe dan akan membekukan data yang diberikan.


# 1. Diagnosa Penyakit Menggunakan Forward Chaining
dalam kode ini saya mengimplementasikan metode forward chaining pada diagnosa penyakit dimana kode ini akan berjalan dimulai dengan menanyakan gejala yang muncul dari aturan yang ada kemudian akan disimpulkan bahwa penyakit uang dideritanya akan sesuai dengan gejala yang dialaminya, lalu sistem akan menulis penyakit yang mungkin diderita oleh user.
# 2.Sistem Pakar Backward Chaining
pada kode  ini merupakan sebuah imlementasi dari backward chaining, dimana aturan dari penyakit dimasukan di kodingan, kemudian gejala yang dialami juga akan dimasukan pada kodingan, sehingga untuk menamilkan penyakitnya akan sesuai dengan gejala yang dimasukan pada kode.
# 3. Forward chaining 
dalam kode ke tiga ini merupakan implementasi metode forward chaining tanpa menggunakan liblary experta, dimana dalam kodenya bisa menentukan hewan apa yang dimaksud dalam kode
# 4. Forward chaining 
dalam kode ke empat ini merupakan implementasi metode Backward chaining tanpa menggunakan liblary experta, padakode ini bisa memvalidasi bahwa orang yang dimaksud memiliki software engineer dalam komputer atau tidak.
# 5. Latihan Forward Chaining
Kode ini mengimplementasikan metode *forward chaining* (penalaran maju) dalam sistem pakar. Forward chaining bekerja dengan *mengambil sejumlah fakta awal*, lalu menerapkan aturan-aturan yang tersedia untuk menyimpulkan fakta baru secara bertahap. Dalam contoh ini, fakta awalnya adalah bahwa objek memiliki roda, mesin, dan empat roda. Aturan-aturan menentukan bahwa jika suatu objek memiliki roda dan mesin, maka itu adalah kendaraan. Kemudian, jika objek adalah kendaraan dan memiliki empat roda, maka itu adalah mobil. Fungsi `forward_chaining` akan terus memeriksa dan menerapkan aturan-aturan ini sampai tidak ada fakta baru yang bisa disimpulkan. Hasil akhirnya adalah sekumpulan fakta baru yang berhasil disimpulkan berdasarkan aturan dan fakta awal tersebut, yang kemudian dicetak.
# 6. Latihan Backward Chaining
Kode ini mengimplementasikan metode backward chaining (penalaran mundur), yaitu proses penalaran dari tujuan akhir (goal) ke fakta-fakta yang mendukungnya. Dalam program ini, sistem ingin mengetahui apakah suatu kesimpulan (dalam hal ini `"is_penguin"`) dapat dibuktikan berdasarkan fakta awal dan aturan yang tersedia. Fungsi `backward_chaining` akan memeriksa apakah goal sudah ada dalam fakta — jika ya, langsung dikembalikan sebagai benar. Jika belum, ia akan mencari aturan yang bisa menghasilkan goal tersebut, lalu mencoba membuktikan semua kondisi yang dibutuhkan aturan itu secara rekursif. Dalam contoh ini, sistem akan mencari tahu apakah "is_penguin" bisa dibuktikan. Untuk itu, ia butuh "is_bird" dan "cannot_fly". Lalu sistem mencari apakah dua syarat itu bisa dibuktikan dari fakta yang ada, dan ternyata bisa. Hasil akhirnya adalah True, yang berarti kesimpulan bahwa objek tersebut "is_penguin" dapat dibuktikan berdasarkan fakta dan aturan yang ada.
