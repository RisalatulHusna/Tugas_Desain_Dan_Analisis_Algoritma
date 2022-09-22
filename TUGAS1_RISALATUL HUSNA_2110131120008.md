<h1 align="center"><b>Penjelasan Sederhana Tentang Time Complexity dan Big-O Notation
</b><br></h1>

---

<p align = "justify">Kompleksitas suatu algoritma dibagi menjadi 2, yaitu Time Complexity dan Space Complexity.<br><br>Time Complexity adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan Space Complexity adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang Time Complexity.</p>

---

#
## __ALGORTMA__
<p align = "justify">Sederhananya, algoritma adalah serangkaian proses yang dilakukan secara berurutan untuk menyelesaikan sebuah permasalahan. Algoritma bisa bermacam-macam tergantung kepada siapa yang membuat algoritma tersebut. Namun permasalahannya adalah algoritma mana yang lebih efektif dan efisien?<br><br>Time Complexity Analysis adalah suatu cara sederhana untuk mengetahui berapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu (n). Biasanya lebih dikenal dengan sebutan Big-O Notation.<br><br><i>Big O Notation digunakan untuk mengukur tingkat kompleksitas suatu algoritma.</i><br><br>Big-O Notation adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk Aljabar, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.<br><br>Mari kita liat contoh dibawah ini:<br><p align = "center"><img src = "P1.PNG"></p>Sederhananya, semua contoh yang ada diatas mengatakan bahwa “kita hanya akan melihat faktor yang memiliki dampak paling besar terhadap nilai yang dihasilkan oleh algoritma tersebut”.<br><br>Terdapat beberapa macam time complexity, diantaranya:</p>


### ___O(1) — Constant Time___

<p align="justify">Constant Time artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.<p align = "center"><img src = "P2.PNG"></p>Kita bisa melihat bahwa berapapun jumlah array yang diberikan kepada fungsi tersebut, dia akan selalu melakukan 1 hal, yaitu mengambil elemen pertama. Itu artinya jumlah input yang diberikan tidak mempengaruhi waktu proses (runtime) dari algoritma tersebut.<p align = "center"><img src = "P3.PNG"></p></p>

#
### ___O(log n) — Logarithmic Time___

<p align="justify">Logarithmic Time artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor. Salah satu contohnya adalah algoritma Binary Search.<br><p align = "center"><img src = "P4.PNG"></p></p>

#
### __O(n) — Linear Time__

<p align ="justify">Linear Time adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.<br><p align = "center"><img src = "P5.PNG"></p>Kita bisa melihat bahwa semakin banyak jumlah input yang diberikan, maka waktu proses/runtime dari fungsi tersebut akan semakin besar.<br><p align = "center"><img src = "P6.PNG"></p></p>

#
### ___O(n²) — Quadratic Time___

<p align ="justify">Quadratic Time adalah ketika runtime dari fungsi kita adalah sebesar n^2, dimana n adalah jumlah input dari fungsi tersebut. Hal tersebut bisa terjadi karena kita menjalankan fungsi linear didalam fungsi linear (n*n).<br><p align = "center"><img src = "P7.PNG"></p><br><p align = "center"><img src = "P8.PNG"></p></p></p>

#
### ___O(2^n) — Exponential Time___

<p align ="justify">Exponential Time biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap kombinasi dan permutasi dari semua kemungkinan.<br><p align = "center"><img src = "P9.PNG"></p></p>

