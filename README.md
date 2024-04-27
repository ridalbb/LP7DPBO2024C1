# LP7DPBO2024C1
# Janji
Saya Ridwan Albana NIM 2105745 mengerjakan Latihan Praktikum 7 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan Aamiin.
# Soal
Lanjutkan program Flappy Bird di atas dan tambahkan fitur-fitur berikut:

    1. Hentikan permainan saat player menabrak/menyentuh pipa atau terjatuh ke batas bawah JFrame (Game Over);
    2. Setelah Game Over, tambahkan fungsionalitas untuk restart permainan dengan menekan tombol “R” pada keyboard.
    3. Buat sebuah JLabel untuk menampilkan skor;
    4. Tambah skor (+1) setiap kali player melewati pipa;
# Alur
- Saat permainan dimulai, objek FlappyBird dibuat dan inisialisasi dilakukan. Ini melibatkan pengaturan parameter awal seperti lebar dan tinggi layar, gambar latar belakang, gambar karakter burung, gambar pipa atas dan bawah, serta parameter lainnya seperti posisi awal pemain dan pipa, serta pengaturan timer untuk pergerakan dan penempatan pipa.
    
- Setelah inisialisasi, pergerakan pemain dan pipa dimulai. Pemain (burung) dapat melompat dengan menekan tombol spasi, yang mengubah kecepatan vertikal pemain. Selain itu, pipa akan terus bergerak dari kanan ke kiri untuk memberikan tantangan bagi pemain.
    
- Setiap kali siklus pergerakan pemain dan pipa dilakukan, program akan memeriksa apakah ada tabrakan antara pemain dan pipa. Jika pemain menyentuh pipa atau jatuh ke bawah layar, permainan akan berakhir.

- Ketika pemain berhasil melewati pipa tanpa menabraknya, skor akan ditingkatkan. Hal ini dilakukan dengan memantau posisi pipa dan pemain, dan meningkatkan skor setiap kali pipa melewati pemain.
    
- Jika ada tabrakan antara pemain dan pipa, atau pemain jatuh ke bawah layar, permainan akan berakhir. Program akan menghentikan pergerakan dan menampilkan pesan "Game Over" bersama dengan skor akhir.  Selain itu, pemain diberi opsi untuk me-restart permainan dengan menekan tombol "R" pada keyboard.
