# 🎹 ***Piano***

Selamat datang di dokumentasi **Piano** dari mengkiuti kelas *Responsive Web Design* oleh freeCodeCamp!  
Dalam kursus ini, saya mempelajari **CSS Advanced Properties: `::before`, `::after`,`float`, and `media-query`** untuk membuat tampilan yang menarik dan interaktif. 🚀

## 📌 Overview
Dokumen ini menjelaskan empat properti penting dalam CSS yang sering digunakan dalam pengembangan web.

|Property     | Deskripsi |
|-------------|-----------|
| `::before`  | Pseudo-element yang menambahkan konten sebelum elemen utama. |
| `::after`   | Pseudo-element yang menambahkan konten setelah elemen utama. |
| `media-query`| Digunakan untuk membuat tampilan responsif berdasarkan ukuran layar. |
| `float`     | Mengatur posisi elemen agar berada di sisi kiri atau kanan. | 

## 📝 Detail Pembelajaran

### 1️⃣ `::before` dan `::after`
- Menambahkan elemen virtual sebelum atau setelah konten asli.
- Tidak memengaruhi struktur DOM.
- Harus digunakan dengan `content`.

```css
h1::before {
  content: '🔥 ';
}

h1::after {
  content: ' 🎉';
}
```

### 2️⃣ Media Query
- Digunakan untuk menyesuaikan tampilan di berbagai ukuran layar.

```css
@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
```

### 3️⃣ Float
- Digunakan untuk membungkus teks di sekitar gambar atau elemen lainnya.

```css
img {
  float: left;
  margin-right: 10px;
}
```
---

© 2025 | **Piano Project**
