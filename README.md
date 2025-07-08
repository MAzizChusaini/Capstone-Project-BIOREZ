# 🌱 BioRez – Sustainable Environment Web App

## 🧭 Deskripsi Proyek

**BioRez** adalah aplikasi berbasis web yang mendukung keberlanjutan lingkungan, terinspirasi oleh filosofi Jepang *Mottainai* — rasa sayang membuang sesuatu yang masih bernilai.

Di Indonesia, sistem pemilahan sampah masih belum berjalan secara optimal. Banyak masyarakat yang belum teredukasi mengenai pentingnya memilah sampah, dan meskipun sudah ada edukasi, kenyataannya di Tempat Pembuangan Akhir (TPA) sampah sering kali kembali disatukan.

Selain itu, penggunaan furnitur berbahan dasar kayu seperti meja dan lemari masih sangat tinggi. Hal ini secara tidak langsung mendorong peningkatan angka deforestasi.

Aplikasi ini menyediakan fitur **scan sampah** menggunakan **machine learning image classification** untuk membantu pengguna memilah sampah menjadi **organik** atau **anorganik**. Melalui edukasi dan teknologi pemilahan sampah berbasis machine learning, kami berharap dapat meningkatkan kesadaran dan partisipasi masyarakat dalam menjaga lingkungan.

🔗 [💻 Mockup](https://www.figma.com/design/WhxG5zMhnpfMxSx0YHkPa1/Capstone-Project---BIOREZ-Web-Design?m=auto&t=DHiCmUHAHSncy1EA-6)  
🔗 [🎥 Demo Video](https://youtu.be/uIWUPzV0mys)  
🔗 [🚀 Live Website](https://biorez.netlify.app/)

---

## 🖼️ Fitur Utama

- 🌳 Edukasi pemilahan sampah
- 📷 Deteksi sampah organik/anorganik dengan kamera & AI
- 🛒 Fitur toko untuk jual beli barang layak pakai
- 📱 Dapat diakses di desktop & mobile (responsive)

---

## 🏗️ Struktur Folder
```
CAPSTONEFINAL/
├── frontend/
│ └── src/
│ ├── pages/
│ ├── routes/
│ ├── utils/
│ └── styles/
├── ML/
│ ├── dataset/
│ ├── models/
│ └── notebook/
├── public/
├── README.md
└── requirements.txt
```
---
## 🛠️ Teknologi yang Digunakan
### Frontend
- JavaScript
- Webpack
- HTML, CSS

### Backend
- Node.js
- Hapi.js
- Postman

### Machine Learning
- TensorFlow
- Python
- Jupyter Notebook

---

## 📦 Instalasi
```
pip install -r requirements.txt
npm install
npm install onnxruntime-web
npm run start
```
---
## 📁 Dataset
https://www.kaggle.com/datasets/techsash/waste-classification-data

Rincian Dataset:

Total gambar: 25.000++ 

Format: .jpg

Data telah di-convert ke format .tfrecord secara mandiri untuk efisiensi training TensorFlow.

---
## 🧪 Model AI

Model klasifikasi gambar dibangun menggunakan:

✅ CNN berbasis MobileNet

✅ Dataset organik vs anorganik

✅ Konversi model: .h5 → .tflite → .tfjs untuk digunakan di web

---
## 🧠 Kesimpulan
Proyek ini menunjukkan bahwa teknologi machine learning dapat diintegrasikan ke dalam aplikasi web untuk meningkatkan kesadaran masyarakat akan pentingnya memilah sampah dan menjaga lingkungan.

---
## 👨‍💻 Kontributor
### M. Aziz Chusaini
Mahasiswa Universitas Indraprasta PGRI, fokus di bidang Data Science dengan spesialisasi di Machine Learning.

🔗 [GitHub](https://github.com/MAzizChusaini)

🔗 [LinkedIn](https://www.linkedin.com/in/m-aziz-chusaini-56187331a/)

### Muhammad Fadhli Al Hafizh
Mahasiswa Universitas Indraprasta PGRI, fokus di bidang Front-End & Back-End Developer

🔗 [GitHub](https://github.com/MFadhliAlHafizh)

🔗 [LinkedIn](https://www.linkedin.com/in/mfadhlialhafizh)


### Andi Hariyanto
Mahasiswa Universitas Indraprasta PGRI, fokus di bidang Front-End & Back-End Developer

🔗 [GitHub](https://github.com/Andyy-Code-Hub)

🔗 [LinkedIn](www.linkedin.com/in/andi-hariyanto-0b3289236 )

### Raffi Arya Putra Prabowo
Mahasiswa Universitas Indraprasta PGRI, fokus di bidang Machine Learning dan Web Development

🔗 [GitHub](https://github.com/Medolsky)

🔗 [LinkedIn](https://www.linkedin.com/in/raffi-arya-putra-prabowo-649663231/)
