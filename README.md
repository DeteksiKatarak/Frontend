# React + Vite

# Klasifikasi Penyakit Mata Katarak Berdasarkan Citra Retina Menggunakan PCA Dan K-NN Berbasis Web

# Deskripsi : 
- Proyek ini mengimplementasikan sistem klasifikasi penyakit mata katarak berbasis web yang menggunakan citra retina (fundus) sebagai input. Fitur inti menggunakan Principal Component Analysis (PCA) untuk ekstraksi/reduksi fitur dan K-Nearest Neighbors (K-NN) sebagai algoritma klasifikasi. Aplikasi ini menyediakan antarmuka web sederhana untuk mengunggah citra retina, menampilkan hasil preprocessing, dan menampilkan prediksi apakah citra menunjukkan tanda katarak atau tidak.

# Fitur : 
- Unggah citra retina melalui antarmuka web.
- Tekan Button Untuk Prediksi Katarak
- Model Melakukan Proses
- Output / Hasil :  Mata normal / Katarak dan nilai Confidence

# Teknologi : 
- Backend : Menggunakan Python (Flask)
- Frontend : Menggunakan Javascript (React JS) dan CSS
- Deployment : Menggunakan Vercel

# Dataset : 
- https://www.kaggle.com/datasets/nandanp6/cataract-image-dataset

# Cara Instal Dan Gunakan Di localhost :
- git clone https://github.com/DeteksiKatarak/Frontend.git
- New Terminal Pada vscode anda
- cd Website_CekKatarak / Projek_Katarak
- cd Frontend
- ketik npm install
- setelah itu ketik "npm run dev" Untuk menjalankan react js di localhost
- maka akan mendapatkan link " http://localhost:5173/"
- buka browser untuk melihat tampilan dari web nya


# Link akses online
- https://deteksi-katarak-astra.vercel.app


# Diagram Flowchart
![Flowchart](flowchart_Katarak.png)