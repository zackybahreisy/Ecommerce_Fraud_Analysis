# **Ecommerce Fraud Analysis (Shopee)**

## 📌 **Overview**

Project ini bertujuan untuk menganalisis indikasi fraud (kecurangan) pada ekosistem e-commerce, khususnya pada fitur Flash Sale, penggunaan Voucher, dan Shopee Coins.

Shopee mengalami lonjakan traffic tinggi akibat strategi marketing seperti kampanye tanggal kembar (11.11, 12.12) dan program Flash Sale. Namun, ditemukan bahwa sebagian besar produk Flash Sale habis dalam waktu kurang dari 1 detik — indikasi kuat adanya bot/scalper.

Selain itu, terdapat anomali pada:
- Penggunaan voucher tanpa memenuhi minimum spend
- Penyalahgunaan Shopee Coins
- Ketidakkonsistenan data perangkat (Device OS)

Analisis ini dilakukan untuk membantu tim Anti-Fraud dalam mengidentifikasi pola kecurangan serta mengoptimalkan penggunaan budget promosi.

## 🎯 **Objectives**

Project ini memiliki beberapa tujuan utama:

🔍 **Bot Detection** : Mengidentifikasi transaksi dengan durasi checkout tidak wajar (indikasi bot)

💸 **Voucher Abuse Analysis** : Menghitung kerugian akibat penggunaan voucher yang tidak sesuai syarat

📱 **Device Analysis** : Mengidentifikasi device yang digunakan oleh banyak akun (indikasi farm account)

🧹 **Data Cleaning** : Standarisasi data Device OS yang tidak konsisten

🪙 **Coins Anomaly Detection** : Mendeteksi penggunaan koin yang tidak wajar (negatif / melebihi saldo)

💳 **Payment Method** : Analisis hubungan metode pembayaran dengan aktivitas bot

## 🚀 Business Impact

Jika solusi diimplementasikan:
- ✅ Mengurangi kerugian akibat fraud
- ✅ Meningkatkan fairness Flash Sale
- ✅ Meningkatkan kepercayaan user
- ✅ Optimasi budget marketing (voucher & coins)
