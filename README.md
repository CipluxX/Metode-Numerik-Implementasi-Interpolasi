# Metode-Numerik-Implementasi-Interpolasi


**Interpolasi Lagrange dan Newton**

Kode ini merupakan implementasi dari dua metode interpolasi yang umum digunakan dalam analisis numerik, yaitu interpolasi Lagrange dan interpolasi Newton. Dalam kedua metode ini, data titik-titik yang diberikan digunakan untuk menghitung nilai interpolasi pada titik-titik di antara data tersebut.

**Fungsi Interpolasi Lagrange**
- `lagrange_interpolation(x, x_points, y_points)`: Fungsi ini menghitung nilai interpolasi menggunakan metode Lagrange berdasarkan titik-titik yang diberikan. Metode ini menghasilkan polinomial interpolasi dengan akurasi tinggi.

**Fungsi Interpolasi Newton**
- `newton_interpolation(x, x_points, y_points)`: Fungsi ini menggunakan metode interpolasi Newton untuk menghitung nilai interpolasi. Koefisien polinomial Newton dihitung berdasarkan perbedaan terbagi dari titik-titik data.

*Keterangan Tambahan*
- File ini membutuhkan pustaka `numpy` dan `matplotlib.pyplot`.
- Data titik-titik yang digunakan disimpan dalam array `x_values` dan `y_values`.
- Untuk menghasilkan hasil interpolasi, panggil salah satu fungsi interpolasi dengan memberikan nilai `x` yang ingin diinterpolasi serta data titik-titik `x_points` dan `y_points`.
