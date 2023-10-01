# House Pricing Prediction
<p align='justify'>Real Estate adalah industri yang mengacu pada properti atau aset yang berwujud, seperti tanah, bangunan, atau struktur lainnya yang terletak di atas atau di dalam tanah. Di sebuah bisnis, real estate dapat menjadi objek investasi atau sumber pendapatan, seperti sewa atau penjualan properti. Machine Learning dapat berperan penting di industri real estate sepert memprediksi harga properti berdasarkan faktor-faktor seperti lokasi, ukuran, fasilitas, dan kondisi properti. Hal ini dapat membantu agen real estate, investor, dan penjual untuk menentukan harga yang tepat untuk properti mereka.</p>

## Tujuan
<p align='justify'>Model diharapkan memiliki akurasi yang baik dan sudah teruji. Dan dapat memberikan insight bisnis kepada user</p>

## Pembahasan
<p align="justify">Terdiri dari <b>1460 Baris</b> dan <b>81 Kolom</b></p>
<br>
<img height="100" width="auto" alt="Missing Value Comparison" src="https://github.com/AptaArkana/House_Pricing_Prediction_Ames/assets/79633073/55c8499d-e94a-4173-be95-a91903361016">
<p align="justify">kolom data yang memiliki missing value tertinggi <b>PoolQC, MiscFeature, Alley, Fence, FireplaceQU </b> sehingga kolom - kolom tersebut bisa kita hilangkan</p>
<br>
<img height="100" width="auto" alt="Distribusi Data LotFrontage, GarageYrBlt, MasVnrArea" src="https://github.com/AptaArkana/House_Pricing_Prediction_Ames/assets/79633073/f594d12f-8a3c-4c1f-be93-dffc77579ebd">
<p align="justify">Untuk LotFrontage dan MasVnrArea <b>terindikasi Skewness Positif </b> karena itu untuk penanganan missing value menggunakan <b>median </b>, sedangkan GarageYrBlt bisa dibilang <b>distribusi normal</b> jadi bisa menggunakan <b>mean </b>. Dan untuk kolom yang mempunyai tipe data kategori untuk penanganan missing value bisa menggunakan <b>modus </b>b</p>


