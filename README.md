# 🧱 Stack Overflown

**Stack Overflown** adalah sebuah game puzzle bertema developer yang terinspirasi dari Tetris klasik dengan twist unik. Alih-alih menghapus baris penuh, pemain harus membentuk pola error coding tertentu untuk mendapatkan poin!

## 📖 Tentang Game

Stack Overflown adalah puzzle game berbasis web yang menggabungkan mekanika jatuhnya blok seperti Tetris dengan tantangan pattern-matching. Setiap level menampilkan pola error coding yang berbeda seperti "Null Pointer", "Memory Leak", atau "Infinite Loop" yang harus dibentuk pemain menggunakan blok-blok yang jatuh.

### ✨ Fitur Utama

- 🎮 **Gameplay Klasik dengan Twist Modern**: Mekanika Tetris yang familiar dengan tujuan pattern-matching yang unik
- 🐛 **7 Pola Error Coding**: Termasuk Null Pointer, Memory Leak, Off By One, Race Condition, Infinite Loop, Syntax Error, dan Type Mismatch
- 🎨 **Desain Bertema Developer**: Warna dan tema terinspirasi dari VS Code dan tools development modern
- 📊 **Sistem Scoring**: Dapatkan poin dengan mencocokkan pola target
- ⏸️ **Pause dan Resume**: Kontrol penuh atas permainan Anda

### 🎯 Cara Bermain

1. Blok-blok dengan berbagai bentuk akan jatuh dari atas
2. Atur posisi blok menggunakan tombol arrow keys
3. Tujuan: Bentuk pola error coding yang ditampilkan di panel samping
4. Ketika pola terbentuk, board akan dibersihkan dan skor bertambah
5. Game berakhir ketika stack mencapai bagian atas layar

### 🎮 Kontrol

| Tombol | Aksi |
|--------|------|
| `←` / `→` | Gerakkan blok ke kiri/kanan |
| `↑` | Rotasi blok |
| `↓` | Soft drop (jatuh lebih cepat) |
| `Space` | Hard drop (langsung ke bawah) |
| `P` | Pause/Resume game |

## 🛠️ Teknologi

Game ini dibangun menggunakan teknologi web standar:

- **HTML5**: Struktur halaman
- **CSS3**: Styling dengan gradien modern dan responsive design
- **JavaScript (Vanilla)**: Game logic dan rendering menggunakan Canvas API
- **Canvas API**: Rendering grafis game real-time

## 🚀 Cara Menjalankan

1. **Clone repository ini**:
   ```bash
   git clone https://github.com/ZekkCode/skills-introduction-to-git.git
   cd skills-introduction-to-git
   ```

2. **Buka game di browser**:
   - Buka file `src/index.html` langsung di browser Anda
   - Atau gunakan local server (misalnya dengan Python):
     ```bash
     cd src
     python -m http.server 8000
     ```
     Kemudian buka `http://localhost:8000` di browser

3. **Mulai bermain!**

## 📁 Struktur Proyek

```
skills-introduction-to-git/
├── src/
│   ├── index.html      # File HTML utama
│   ├── index.js        # Game logic utama
│   ├── patterns.js     # Definisi pola error coding
│   └── style.css       # Styling game
├── LICENSE             # MIT License
└── README.md          # File ini
```

## 🎓 Tentang GitHub Skills Exercise

Repository ini juga merupakan bagian dari GitHub Skills learning exercise untuk mempelajari Git version control.

<details>
<summary>📚 Klik untuk informasi lengkap tentang exercise</summary>

### Introduction to Git Exercise

_Use Git version control to work on a game using command line (CLI) and VS Code._

**Who is this for**: Beginner developers who want to learn Git version control

**What you'll learn**: Fundamental Git concepts including commits, branches, history, and collaboration basics

**Prerequisites**:
- No prior Git or version control experience required
- Recommended: Basic familiarity with Command Line Interfaces (CLI)
- Recommended: Basic familiarity with Visual Studio Code

**How long**: This exercise takes less than 60 minutes to complete.

In this exercise, you will:
1. Understand what version control is and why developers use it
2. Configure your Git identity
3. Create your first repository and make commits
4. View project history and compare file changes
5. Work with branches to experiment safely
6. Learn about Git collaboration concepts

</details>

## 📝 License

Proyek ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail lengkap.

## 🤝 Kontribusi

Kontribusi, issues, dan feature requests sangat diterima! Jangan ragu untuk check [issues page](../../issues).

---

**Happy Coding & Happy Gaming!** 🎮✨

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
