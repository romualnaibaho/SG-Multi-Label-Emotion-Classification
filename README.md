# SG-Multi-Label-Emotion-Classification

<p style="color: blue;"> Kelompok Squid Game </p>
<ol>
  <li>11S18001 Efrica Cahyani Situmeang</li>
  <li>11S18007 Aldi Irvan Siagian</li>
  <li>11S18013 Grace Noelia Simorangkir</li>
  <li>11S18040 Anjel Riska Pardede</li>
  <li>11S18041 Grace Widya Simanjuntak</li>
  <li>11S18048 Romual Naibaho</li>
</ol>

<h1 style="font-weight: bold">Daftar Isi</h1>
<ol>
  <li><a href="#pendahuluan">Pendahuluan</a></li>
  <ul>
    <li><a href="#lb">Latar Belakang</a></li>
    <li><a href="#rm">Rumusan Masalah</a></li>
    <li><a href="#tp">Tujuan Penelitian</a></li>
    <li><a href="#mp">Manfaat Penelitian</a></li>
    <li><a href="#rlp">Ruang Lingkup Penelitian</a></li>
    <li><a href="#hp">Hasil Penelitian</a></li>
  </ul>
  <li>Hasil</li>
  <ul>
    <li>Model</li>
  </ul>
</ol>

<hr/>

<h2 id="pendahuluan">Pendahuluan</h2>
<h4 id="lb" style="font-weight: bold">Latar Belakang</h4>
<p>
Emosi adalah pola reaksi yang kompleks, yang melibatkan pengalaman, perilaku, dan fisiologis, di mana seorang individu mencoba untuk menangani masalah atau peristiwa yang signifikan secara pribadi. Dalam kehidupan sehari-hari, penyampaian emosi dapat disampaikan secara non-verbal menggunakan ekspresi wajah maupun verbal berupa tingkah laku. Emosi bersifat subjektif dan temporer yang muncul atau dipicu oleh stimulus seperti perlakuan dari orang sekitar atau lingkungannya.
</p>
<p>
Deteksi emosi dilakukan dengan pendekatan klasifikasi emosi. Klasifikasi adalah proses dengan menggabungkan atau mengelompokkan dua atau lebih data yang memiliki kesamaan pada suatu kriterianya. Terdapat beberapa metode yang dapat digunakan untuk melakukan klasifikasi pada teks, diantaranya Support Vector Machine, Naïve Bayes, K-Nearest Neighbor, Multinomial Naïve Bayes, Multi Task Regression, Algoritma Incremental Regression, dan lain-lain. Sedangkan untuk metode fitur ekstraksi juga terdapat beberapa yang sering digunakan, diantaranya TF-IDF, N-Gram, Word Embedding, dan lain-lain. Namun pada penelitian ini beberapa pendekatan atau metode yang akan digunakan dalam melakukan fitur ekstraksi yaitu TF-IDF yang kemudian diklasifikasikan dengan metode Naïve Bayes. Berdasarkan penelitian sebelumnya fitur TF-IDF memberikan hasil yang lebih baik sekitar 3% - 4% jika dibandingkan dengan fitur N-Gram (Ahuja et al., 2019). TF-IDF merupakan teknik yang paling sederhana sehingga mudah untuk melakukan pengecekan corpus yang besar dan juga dapat menghitung banyak istilah yang ada dalam sebuah dokumen. Algoritma pengklasifikasian Naive Bayes adalah salah satu pengklasifikasian statistik, pengklasifikasian ini dapat memprediksi probabilitas anggota kelas data yang akan masuk ke kelas tertentu, menurut perhitungan probabilitas. Klasifikasi ini menunjukkan akurasi dan kecepatan yang tinggi bila diterapkan kedalam database yang besar. Metode ini sering digunakan untuk memecahkan masalah di bidang Machine Learning karena metode ini memiliki tingkat akurasi yang tinggi dengan perhitungan sederhana.
</p>
<br/>
<h4 id="rm" style="font-weight: bold">Rumusan Masalah</h4>
<ul>
  <li>Bagaimana mengklasifikasikan emosi berdasarkan data komentar menggunakan algoritma Naive Bayes.</li>
</ul>
<br/>
<h4 id="tp" style="font-weight: bold">Tujuan Penelitian</h4>
<ul>
  <li>Melakukan implementasi Naive Bayes dalam mengklasifikasikan emosi berdasarkan data komentar.</li>
</ul>
<br/>
<h4 id="mp" style="font-weight: bold">Manfaat Penelitian</h4>
<ul>
  <li>Penelitian ini diharapkan mampu melakukan klasifikasi emosi berdasarkan kalimat yang diberikan dengan memberi label pada setiap kelas emosi sesuai dengan dataset yang diberikan.</li>
</ul>
<br/>
<h4 id="rlp" style="font-weight: bold">Ruang Lingkup Penelitian</h4>
<ul>
  <li>Data yang diolah dikumpulkan dari website reddit.</li>
  <li>Penelitian ini melakukan normalisasi hanya dalam bentuk huruf.</li>
  <li>Penelitian ini menerima inputan dalam bentuk kalimat yang mempunyai kata singkatan bahasa Inggris.</li>
  <li>Penelitian ini akan melakukan normalisasi kata singkatan yang di-input oleh user.</li>
</ul>
<br/>
<h4 id="hp" style="font-weight: bold">Hasil Penelitian</h4>
<ul>
  <li>Nanti dibuat.</li>
</ul>
