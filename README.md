# 🎮 NumShift – Sliding Puzzle Game
**Shift the Numbers. Solve the Pattern.**

NumShift adalah game puzzle sederhana namun menantang yang terinspirasi dari permainan klasik *15-puzzle*. Game ini dibangun menggunakan Godot Engine 4.4 dengan desain UI modern, clean, dan mudah dimainkan oleh semua kalangan.

---

## 🧩 Latar Belakang
Pembuatan game ini berawal dari ketertarikan terhadap puzzle yang:
- Sederhana namun menantang  
- Mudah dimainkan oleh siapa saja  
- Melatih logika dan strategi pemain  

NumShift dikembangkan untuk menghadirkan sliding puzzle modern yang intuitif dan menyenangkan.

---

## 🎮 Konsep Game
- **Genre**: Sliding Puzzle / Logic Puzzle  
- **Platform**: PC  
- **Gameplay Singkat**:
  1. Pemain menggeser tile angka untuk menyusun urutan 1–15.
  2. Pergerakan hanya bisa dilakukan ke area kosong.
  3. Puzzle selesai ketika seluruh tile tersusun rapi secara berurutan.

**Target Pemain**:
- Penggemar puzzle  
- Pemain casual  
- Semua rentang usia  

---

## ⚙️ Mekanika Utama
- Grid **4×4**  
- **15 tile** + **1 ruang kosong**  
- Satu langkah = menggeser satu tile ke ruang kosong  
- Puzzle selalu **solvable** menggunakan algoritma parity check  
- Random shuffle otomatis setiap permainan dimulai  

---

## ✨ Fitur-fitur NumShift
- Shuffle puzzle otomatis & solvable  
- Animasi pergerakan halus  
- UI minimalis dengan desain modern  
- Angka besar dan mudah dibaca  
- Layout responsif  

---

## 🎨 Desain Visual & UI/UX
- **Warna utama**: Merah gelap, oranye, putih  
- **Gaya**: Modern, flat, minimalis  
- **Fokus**: Readability, kesederhanaan, kenyamanan mata  

---

## 🛠️ Arsitektur & Tools Pengembangan
- **Engine**: Godot 4.4  
- **Bahasa**: GDScript  
- **Node utama**: GridContainer, Control UI  
- **Sistem Intern**:
  - Array untuk representasi posisi tile  
  - Fungsi legal move  
  - Solvable puzzle generation  
  - Deteksi kemenangan  
- **Build target**: Windows  

---

## 🔍 Cara Kerja Logika Puzzle
1. Papan direpresentasikan sebagai array 1D/2D  
2. Sistem mendeteksi ruang kosong  
3. Mengecek pergerakan valid ke atas, bawah, kiri, kanan  
4. Tile ditukar dengan slot kosong jika langkah valid  
5. Puzzle selesai jika array = `[1, 2, 3, ..., 15]`  

---

## 🧪 Tantangan Selama Pengembangan
- Menghasilkan puzzle acak yang benar-benar solvable  
- Implementasi animasi pergerakan yang mulus  
- UI responsif di berbagai resolusi  
- Logika grid & sistem koordinat  
- Debugging pergerakan & state puzzle  

---

## ✔️ Solusi & Implementasi
- Menggunakan algoritma solvability *15-puzzle*  
- Optimasi input (klik/drag)  
- Testing berbagai variasi shuffle  

---

## 📈 Rencana Pengembangan ke Depan
- Modifikasi Mode Permainan:
  - Time Attack  
  - Move Limit  
  - Grid lebih besar (5×5, 6×6)  
- Leaderboard  
- Penambahan tema/skin  
- Musik & sound effect  
- Daily challenge mode  

---

## 🏁 Kesimpulan
NumShift adalah puzzle modern yang:
- Sederhana namun menantang  
- Mengasah otak & strategi  
- Desain clean dan nyaman  
- Berpotensi dikembangkan menjadi game puzzle mobile  

---

## 👥 Tim Pengembang
- Ferdian  
- Handika  
- Fahmi  

---

## 📷 Preview (Opsional)
Tambahkan screenshot game di sini jika sudah ada.

---

## 📬 Kontak
Jika ingin memberi feedback atau kontribusi, silakan buat **issue** atau **pull request** di repository ini.

---

Terima kasih sudah bermain NumShift! 🎮
