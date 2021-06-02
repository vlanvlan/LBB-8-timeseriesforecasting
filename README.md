# LBB 8 : TIME SERIES & FORECASTING

## Contoh analisis time series sebagai bahan referensi
- https://rpubs.com/nabiilahardini/ts-flight : Prediksi air traffic atau frekuensi penerbangan pesawat di Bandara New York
- https://rpubs.com/wahyuditr/ts : Analisis time series pada data pengunjung situs Wikipedia

## Dataset yang bisa digunakan
- Chicago Crime Dataset (https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2). Dikarenakan ukuran data yang amat besar, Bapak/Ibu dapat melakukan analisis time series untuk salah satu jenis crime saja.
- Data dari `tsdl` package (https://pkg.yangzhuoranyang.com/tsdl/) berisi banyak data time series dari beragam domain bisnis. Versi development dari package tersebut dapat diinstall dari GitHub dengan terlebih dahulu menginstall package `devtools` kemudian menggunakan `install_github()` seperti dibawah ini:
--
# install.packages("devtools")
devtools::install_github("FinYang/tsdl")
--
- Menggunakan data pilihan sendiri.

## Poin pembuatan report
- Data pre-processing berupa data cleansing dan pelengkapan data
- proses EDA berupa analisis trend dan seasonal menggunakan plot sederhana
- Penjelasan pemilihan model time series dan asumsinya.
- Evaluasi model dan pemilihan model terbaik.
