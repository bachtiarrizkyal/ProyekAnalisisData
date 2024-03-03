# Project Data Analisis
Repository ini berisi proyek analisis data yang telah saya kerjakan, lalu saya deploy di Streamlit.
## Deskripsi
Proyek ini bertujuan untuk menganalisis data pada E-Commerce Public Dataset. Tujuan akhirnya adalah untuk menghasilkan wawasan dan informasi yang berguna dari data yang dianalisis. Hal ini dilakukan dengan memanfaatkan berbagai teknik analisis data untuk memahami tren, pola, dan hubungan di dalam dataset tersebut. Dengan demikian, proyek ini tidak hanya fokus pada pengolahan data, tetapi juga pada pemahaman mendalam tentang perilaku pelanggan, performa penjualan, serta faktor-faktor lain yang memengaruhi keberhasilan bisnis e-commerce.
## Struktur Directory
- /data: Directory ini berisi dataset yang saya gunakan dalam proyek ini, dengan format file.csv
- /dashboard: Directory ini berisi dashboard.py yang dimana berisi code untuk membuat dashbard hasil ananlisis
- Proyek_Analisis_Data.ipynb: File ini berisi code untuk melakukan analisis
## Instalasi
Clone repository ini ke Local Computer anda dengan menggunakan perintah :
```
git.cone https://github.com?bachtiarrizkyal/ProyekAnalisisData.git
```
## Setup Environtment
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel
```
## Run Steamlit App
```
streamlit run dashboard.py
```
