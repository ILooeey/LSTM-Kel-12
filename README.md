# LSTM-Kel-12
Proyek ini menggunakan model Long Short-Term Memory (LSTM) untuk memprediksi harga saham berdasarkan data historis yang diambil dari Yahoo Finance. Data saham diambil dari Yahoo Finance tersebut menggunakan pustaka yfinance dan fitur yang digunakan untuk prediksi: 
Close — Harga penutupan saham
Volume — Jumlah volume transaksi pada hari tersebut

LSTM merupakan jenis Recurrent Neural Network (RNN) yang sangat efektif untuk memodelkan data time series seperti harga saham yaitu saham PT. Telkom tbk. Proyek ini terdiri dari 

2 lapisan LSTM dengan 50 unit
Dropout (0.2) setelah masing-masing lapisan LSTM (untuk mengurangi overfitting)
1 lapisan Dense output (neuron tunggal untuk prediksi harga)
Optimizer: Adam
Loss Function: Mean Squared Error (MSE)

