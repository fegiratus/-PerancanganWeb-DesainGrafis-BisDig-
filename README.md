# -PerancanganWeb-DesainGrafis-BisDig-

file:///C:/xampp/htdocs/xampp/fegi%202.html

# PerancanganWeb-DesainGrafis-BisDig

Repository ini berisi contoh implementasi responsive design untuk portofolio mahasiswa, dengan fokus pada penyesuaian tampilan agar terlihat rapi dan optimal di berbagai perangkat, khususnya smartphone dan desktop.

## Konsep

Proyek ini mendemonstrasikan bagaimana **responsive design** dapat diterapkan menggunakan **media queries** di CSS. Tujuannya adalah untuk memastikan bahwa konten portofolio, terutama gambar dan teks, dapat menyesuaikan diri dengan ukuran layar perangkat tanpa meluber atau terpotong, sehingga memberikan pengalaman pengguna yang baik.

### Responsive Design

**Responsive design** adalah pendekatan dalam desain web yang memungkinkan tata letak dan konten sebuah situs web untuk beradaptasi secara fleksibel terhadap berbagai ukuran layar dan perangkat. Ini berarti bahwa situs web akan terlihat dan berfungsi dengan baik di desktop, laptop, tablet, dan smartphone, tanpa perlu membuat versi terpisah untuk setiap perangkat.

### Media Queries

**Media queries** adalah bagian penting dari CSS3 yang memungkinkan penerapan gaya CSS yang berbeda berdasarkan karakteristik media (misalnya, lebar layar, tinggi layar, orientasi perangkat, dll.). Dengan menggunakan media queries, kita dapat mendefinisikan "breakpoint" di mana tata letak situs akan berubah untuk mengoptimalkan tampilan pada ukuran layar tertentu.

Contoh penggunaan media query:

```css
@media screen and (max-width: 768px) {
  /* Aturan CSS yang berlaku ketika lebar layar kurang dari atau sama dengan 768px (misalnya, smartphone) */
}

@media screen and (min-width: 769px) {
  /* Aturan CSS yang berlaku ketika lebar layar lebih dari atau sama dengan 769px (misalnya, tablet dan desktop) */
}
