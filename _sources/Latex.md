## Penyelesaian Sistem Persamaan Linier

### Operasi Baris Elemneter
Operasi baris elementer (OBE) adalah operasi yang dilakukan pada baris suatu matriks untuk mengubahnya menjadi bentuk yang lebih sederhana. OBE dapat digunakan untuk menyelesaikan sistem persamaan linear (SPL) dan menentukan invers matriks
### Eliminasi Gaus
Dalam matematika, eliminasi Gauss adalah algoritma yang digunakan untuk menyelesaikan sistem persamaan linear. Algoritma ini terdiri dari serangkaian operasi yang dilakukan pada matriks koefisien dari sistem persamaan tersebut.

Contoh Soal 1

$
\begin {array}{cc}
x_1+x_2+3x_3=6\\
2x_1+4x_2+6x_3=12\\
x_2+x_3=2
\end{array}
$

Contoh soal 2

$
\begin {array}{cc}
x_1+x_2+x_3=3\\
2x_1+x_3=5\\
x_1+2x_2=3
\end{array}
$

Contoh Soal 3

$
\begin {array}{cc}
2x_1+2x_2=1\\
x_1+x_2=2
\end{array}
$

Contoh Soal 4 

$
\begin {array}{cc}
x_1+x_2=5\\
x_1+2x_3=6\\
\end{array}
$

#### Langkah-langkah Penyelesaian
Soal 1

Diketahui

$
\left [
\begin{array}{ccc|c}
1 & 1 & 3 & 6 \\
2 & 4 & 6 & 12 \\
0 & 1 & 1 & 2
\end{array}
\right]
$

Langkah 1: Buat Elemen (2,1) Menjadi 0
Kurangi 2 kali baris pertama dari baris kedua:
$
R_2 \to R_2 - 2R_1
$
Hasilnya:
$
\left[
\begin{array}{ccc|c}
1 & 1 & 3 & 6 \\
0 & 2 & 0 & 0 \\
0 & 1 & 1 & 2
\end{array}
\right]
$

Langkah 2: Buat Elemen (3,2) Menjadi 0
$
Kurangi ( \frac{1}{2} R_2) dari ( R_3):
$
$
R_3 \to R_3 - \frac{1}{2} R_2
$
Hasilnya:
$
\left[
\begin{array}{ccc|c}
1 & 1 & 3 & 6 \\
0 & 2 & 0 & 0 \\
0 & 0 & 1 & 2
\end{array}
\right]
$

Soal 2

Diketahui

$
\left[
\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
2 & 0 & 1 & 5 \\
1 & 2 & 0 & 3
\end{array}
\right]
$

Langkah 1: Membuat Elemen (2,1) dan (3,1) Menjadi 0
Gunakan operasi baris:
$
R_2 \to R_2 - 2R_1
$
$
R_3 \to R_3 - R_1
$

Sehingga diperoleh:
$
\left[
\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
0 & -2 & -1 & -1 \\
0 & 1 & -1 & 0
\end{array}
\right]
$
Langkah 2: Membuat Elemen (3,2) Menjadi 0
Gunakan operasi:

$
R_3 \to R_3 + \frac{1}{2} R_2
$
Hasilnya:

$
\left[
\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
0 & -2 & -1 & -1 \\
0 & 0 & -\frac{3}{2} & -\frac{1}{2}
\end{array}
\right]
$

Soal 3
Diketahui
$
\left[
\begin{array}{cc|c}
2 & 2 & 1 \\
0 & 1 & 2 
\end{array}
\right]
$
Langkah 1: Membuat Elemen (1,1) Menjadi 1
Bagikan baris pertama $( R_1 )$ dengan 2:

$
R_1 \to \frac{1}{2} R_1
$
Hasilnya:

$
\left[
\begin{array}{cc|c}
1 & 1 & \frac{1}{2} \\
0 & 1 & 2
\end{array}
\right]
$

Langkah 2: Eliminasi Elemen (1,2)
Gunakan operasi:

$
R_1 \to R_1 - R_2
$
Matriks menjadi:
$
\left[
\begin{array}{cc|c}
1 & 0 & -\frac{3}{2} \\
0 & 1 & 2
\end{array}
\right]
$
Langkah 3: Membaca Solusi
Dari bentuk matriks ini, kita mendapatkan:

$
x_1 = -\frac{3}{2}, \quad x_2 = 2
$
Sehingga, solusi sistem adalah:

$
(x_1, x_2) = \left( -\frac{3}{2}, 2 \right)
$
Verifikasi dengan Substitusi
Jika sistem persamaan awal adalah:
$
\begin{cases}
2x_1 + 2x_2 = 1 \\
0x_1 + 1x_2 = 2
\end{cases}
$

Diketahui $( x_2 = 2 )$, substitusi ke persamaan pertama:
$
2x_1 + 2(2) = 1
$
$
2x_1 + 4 = 1
$

$
2x_1 = -3
$

$
x_1 = -\frac{3}{2}
$

Sehingga, solusi akhirnya adalah:
$
\boxed{ \left( -\frac{3}{2}, 2 \right) }
$