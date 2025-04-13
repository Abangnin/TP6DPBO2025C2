# Bismillahirrahmanirrahim

## Janji
Saya Muhammad Naufal Arbanin dengan NIM 2310850 mengerjakan soal Tugas Praktikum 6 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain GUI (Start Game)
![Image](https://github.com/user-attachments/assets/e6bdec45-e634-4e9c-b9dd-69d028affb1f)

## Penjelasan Alur

1. App.java dijalankan ➝ buka StartMenu

2. Pemain klik "START GAME" ➝ buka JFrame baru dengan FlappyBird sebagai panel

3. FlappyBird.startGame() dipanggil:

  - Reset player, pipa, dan skor

  - Timer jalan terus untuk move() dan placePipes()

4. Setiap frame (move() dipanggil 60x/detik):

  - Burung jatuh karena gravitasi

  - Pipa bergerak ke kiri

  - Cek collision dengan pipa/batas bawah

  - Cek apakah burung melewati pipa → tambah skor

5. Jika tabrakan terjadi → gameOver()

6. Jika pemain tekan R → restart startGame()

## Dokumentasi
![Image](https://github.com/user-attachments/assets/2483a55e-fa09-44b7-948b-9eb065fd660e)

![Image](https://github.com/user-attachments/assets/3aa1a1de-31cd-4cf7-b621-28ea21fc1998)
