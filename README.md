🧠 Proyek Deteksi Tepi pada Citra CT Paru-paru
📘 Deskripsi Proyek

Proyek ini merupakan implementasi tugas mata kuliah Pengolahan Citra Digital yang bertujuan untuk menganalisis dan membandingkan lima operator deteksi tepi klasik pada citra medis CT paru-paru.
Penelitian ini menekankan pada evaluasi hasil deteksi tepi di tiga kondisi citra berbeda, yaitu:

Citra asli (grayscale)

Citra hasil dekomposisi wavelet packet

Citra dengan penambahan Gaussian noise

Lima operator deteksi tepi yang dibandingkan adalah Roberts, Prewitt, Sobel, Laplacian of Gaussian (LOG), dan Canny.
Eksperimen dilakukan menggunakan Python (Google Colab) dan divisualisasikan dalam satu grid besar berukuran 3×6, berisi total 18 hasil deteksi tepi.

🧩 Tujuan Proyek

Mengimplementasikan dan membandingkan performa lima operator deteksi tepi pada citra CT paru-paru.

Mengkaji pengaruh preprocessing berupa dekomposisi wavelet dan penambahan noise terhadap hasil deteksi.

Menentukan operator paling optimal untuk mendeteksi struktur jaringan paru-paru berdasarkan hasil visual.

⚙️ Lingkungan Pengembangan
Komponen	Spesifikasi
Platform	Google Colab
Bahasa	Python 3.x
Library Utama	OpenCV, NumPy, Matplotlib, PyWavelets, Scikit-image
Citra Input	Lung(5).png (CT Scan paru-paru dari dataset publik)
Output	Grid 3×6 hasil deteksi tepi
