# Kinematika pada 2/3 Dimensi
Pada materi ini, tujuan pembelajaran sama dengan materi ![kinematika pada 1 dimensi](Kinematika_1D.md) namun gerakan benda atau partikel terjadi pada 2 atau 3 dimensi. 

Contoh gerak pada 2 dimensi adalah lemparan bola basket menuju ring yang bergerak maju dan keatas (sumbu horizontal dan vertikal) yang 2 dimensi. Pilot mendaratkan pesawat, mnendaki gunung, mobil yang belok, dan lain lain.

> [!WARNING]
> Sebelum memelajari materi ini, disarankan untuk menyelesaikan materi vektor terlebih dahulu. Materi dapat diakses melalui ![link disini](Vektor.md)

## Posisi dan Perpindahan
Salah satu cara umum melokasikan partikel dengan **vektor posisi** $\vec{r}$, dimana vektor memanjang dari titik referensi (biasanya *point of origin*) dari suatu partikel. Notasi vektor dapat ditulis sebagai,

$$\begin{align}
\vec{r}=x\hat{{i}}+y\hat{{j}}+z\hat{{k}}
\end{align}$$

Dimana, $x\hat{{i}},y\hat{{j}},z\hat{{k}}$ adalah vektor komponen dari $\vec{r}$ dan koefisien $x,y,z$ adalah komponen skalar.

> [!NOTE]
> Opini saya pribadi saya lebih menyukai notasi $\vec{r}=a\hat{x}+b\hat{y}+c\hat{z}$
> Dimana $a,b,c$ adalah komponen skalar dan $\hat{x},\hat{y},\hat{z}$ adalah unit vektornya.

Ketika, suatu partikel bergerak atau berpindah dari posisinya. Partikel akan mengalami perpindahan.

$$\begin{align}
\Delta\vec{r}=\vec{r_2}-\vec{r_1}
\end{align}$$

> [!WARNING]
> Semua properti diatas dapat disamakan dengan kinematika 1 dimensi namun, perlu merubah properti vektor 1 dimensi menjadi 2-3 dimensi. Materi yang telah anda pelajari pada materi vektor. Maka saya tidak akan mengulangi lagi dan akan langsung menuju materi kinematika lain.

## Gerak Proyektil
Gerak proyektil atau parabola ada gerak sebuah partikel pada sumbu vertikal dan horizontal. Namun, sumbu vertikal memiliki percepatan konstan yang dihasilkan atau disebabkan oleh gravitasi $\vec{g}$.

Tujuan materi ini untuk memelajari, gerak proyektil dengan properti vektor 2 dimensi.

Dalam gerak proyektil, sebuah partikel ditembakan dengan kecepatan awal $\vec{v_0}$ yang memiliki properti vektor

$$\begin{align}
\vec{v_0}=v_{0x}\hat{x}+v_{0y}\hat{y}
\end{align}$$

Tiap komponen vektor dapat ditemukan jika mengetahui sudut $\theta$ antara $\vec{v_0}$ dengan sumbu vertikal ataupun horizontal. Menggunakan properti trigonometri, jika $theta$ terhadap sumbu horizontal.

$$\begin{align}
v_{0x} = v_0 \cos (\theta) \text{ and } v_{0y} = v_0 \sin (\theta)
\end{align}$$

> [!IMPORTANT]
> Pada gerak proyektil, gerak vertikal dan horizontal indepeden terhadap satu sama lain. Sehingga tidak dapat memengaruhi gerak satu sama lain.

### Gerak pada Sumbu Horizontal

Gerak pada sumbu horizontal tidak dipengaruhi oleh percepatan apapun (karena umumnya hambatan udara diabaikan). Maka perpindahan gerak proyektil (dari ditembakan hingga mendarat) partikel adalah

$$\begin{align}
x-x_0&=v_{0x}  t = v_0 \cos (\theta) t
\end{align}$$

Dengan $t$ adalah waktu dari ditembakan hingga mendarat.

### Gerak pada Sumbu Vertikal

Gerak pada sumbu horizontal dipengaruhi oleh percepatan konstan yaitu gravitasi. Sehingga, perpindahan pada sumbu vertikal dapat diekspresikan dengan

$$\begin{align}
y-y_0&=v_{0y}T+\frac{1}{2}aT^2\\
&=v_0 \sin (\theta) T + \frac{1}{2}aT^2 \\
&=v_0 \sin (\theta) T + \frac{1}{2}(-g)T^2 \\
&=v_0 \sin (\theta) T - \frac{1}{2}gT^2
\end{align}$$

Dengan $T$ adalah waktu dari ditembakan hingga mendarat. Maka, dapat menemukan $T$ dengan pencarian akar yang memenuhi ketika $\Delta y = 0$. Namun, dapat juga dengan pendekatan yang jauh lebih sederhana yaitu


$$\begin{align}
v_y &= v_{0y} - gt \\
0 &= v_{0y} - gt \\
v_{0y} &= gt
\end{align}$$

Maka, $t$ adalah ketika partikel mencapai puncak ketinggian dari gerak proyektil. Hal ini dikarenakan ketika partikel berada di puncak ketinggian, partikel tidak lagi memiliki $v$ untuk gerak ke-atas atau $v_y = 0$ sehingga percepatan gravitasi menarik partikel kebawah. Maka bisa dilakukan perhitungan 

$$\begin{align}
Y_{\max } &= v_{0y} t - \frac{1}{2} gt^2 \\ 
Y_{\max } &= \frac{v_{0y}^2}{g} - \frac{1}{2} \frac{v_{0y}^2}{g} \\
Y_{\max } &= \frac{v_{0y}^2}{2g}
\end{align}$$

Setelah menemukan $Y_{\max}$, maka hanya memerlukan mengobservasi gerak proyektil pada sumbu vertikal dari puncak hingga sama seperti semula ketitka ditembakan.


$$\begin{align}
v_y &= v_0+2gt \\
v_y &= 0 + gt
\end{align}$$

> [!WARNING]
> Perhatikan bahwa kali ini kecepatan searah dengan percepatan sehingga berubah menjadi +

Karena ketika berada di puncak partikel tidak memilih kecepatan di sumbu Y. Maka $v_0$ dapat diisi dengan $0$ sehingga menemukan hasil berikut. Dapat diobservasi bahwa $v$ mendarat bernilai sama dengan $v_0$ (hanya berbalik arah). Maka, $t$ yang ditempuh juga sama dengan $T$ waktu yang diperlukan mencapai puncak. Maka, bisa disimpulkan bahwa

$$\begin{align}
t_{tempuh} =  2T
\end{align}$$

Sehingga, jarak horizontal maksimum adalah

$$\begin{align}
x-x_0 =v_{0x}  t &= v_0 \cos (\theta) t\\
\Delta x_{\max}&= v_{0x}  2T \\
&= v_{0x} 2\frac{v_{0y}}{g} \\
&= \frac{2 v_{0x} v_{0y}}{g} \\
&= \frac{v_0^2\sin(2\theta)}{g}
\end{align}$$

Untuk menemukan kemungkinan $x_{terjauh}$ dengan merubah sudut proyektil. Maka,

$$\begin{align}
\frac{dR}{d\theta} &=\frac{2V_0}{g}2(\cos(2\theta)) \\
0 &= \cos(2\theta)\\
2\theta &= 90 \deg + K \pi , K \in \mathbb{Z}
\end{align}$$

Pada gerak proyektil dapat dilakukan pendekatan lain tanpa perlu melakukan pendekatan dengan waktu yaitu bisa melakukan pendekatan dengan $x$


$$\begin{align}
y &= v_{0} \sin(\theta) t - \frac{1}{2} g t^2 \\
&= \tan(\theta) x - \frac{gx^2}{(v_{0} \cos(\theta))^2}
\end{align}$$

Maka, bisa disimpulkan bahwa persamaan tersebut adalah persamaan lintasan gerak proyektil.

## Gerak Melingkar
