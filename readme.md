# A/B Testing & Experimentation

## Latar Belakang
Perusahaan ingin meningkatkan performa bisnis pada produk berbasis langganan dengan mengoptimalkan proses trial dan konversi ke pelanggan berbayar. Untuk itu, dilakukan eksperimen A/B testing pada dua variant (A dan B) guna mengetahui apakah perubahan yang diterapkan pada variant B dapat meningkatkan jumlah trial start, conversion rate dari trial ke paid, serta revenue dalam 30 hari.

## Tujuan
1. Mengetahui apakah variant B dapat meningkatkan jumlah pengguna yang memulai trial dibandingkan variant A.
2. Mengukur apakah variant B mampu meningkatkan conversion rate dari trial ke paid user.
3. Membandingkan total dan rata-rata revenue 30 hari antara variant A dan B.

## Hipotesis
- **H0 (Hipotesis Nol):** Tidak terdapat perbedaan signifikan antara variant A dan B terhadap jumlah trial start, conversion rate, dan revenue 30 hari.
- **H1 (Hipotesis Alternatif):** Variant B memberikan peningkatan signifikan pada jumlah trial start, conversion rate, dan revenue 30 hari dibandingkan variant A.

## Metrik yang Digunakan
1. **Jumlah Trial Start:** Banyaknya user yang memulai trial pada masing-masing variant.
2. **Conversion Rate Trial → Paid:** Persentase user yang memulai trial dan kemudian menjadi pelanggan berbayar.
3. **Revenue 30 Hari:** Total dan rata-rata pendapatan yang dihasilkan dalam 30 hari pertama setelah trial.

## Metodologi
- Data difilter untuk hanya menggunakan user yang memulai trial pada periode eksperimen.
- Analisis dilakukan dengan visualisasi (barplot, histogram) dan uji statistik (Shapiro-Wilk, Levene, Mann-Whitney) untuk membandingkan performa kedua variant.
- Uplift absolut dan persentase dihitung untuk mengukur besarnya peningkatan pada variant B.

## Kesimpulan
Variant B menunjukkan peningkatan pada metrik-metrik utama dibandingkan variant A, baik dari sisi jumlah trial start, conversion rate, maupun revenue 30 hari. Hasil uji statistik mendukung bahwa perbedaan tersebut signifikan, sehingga variant B direkomendasikan untuk diimplementasikan.