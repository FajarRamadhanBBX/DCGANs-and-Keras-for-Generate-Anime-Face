<div align="center"><h1>DCGANs and Keras for Generate Anime Face</h1></div>

## 👨‍🔧 Project Overview
Projek ini merupakan tugas dari study independen IBM Academy: Advanced AI serta pengerjaan modul cognitive skill AI.
Pada projek ini, dataset yang digunakan berisi gambar muka kartun anime yang nantinya akan dipelajari oleh model untuk
men-*generate* gambar baru.

## 🌏 Environment
Google Colab and Skills Network Cloud IDE (IBM)

## 🛠 Tech Stack 🛠
<div align="center">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras" />
    <img src="https://img.shields.io/badge/DCGAN-000000?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="DCGAN" />
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
    <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
</div>

## ⚙ Installation & usage Instructions
1. Install berbagai library pandas, numpy, seaborn, matplotlib, scikit-learn <br>
```!pip install pandas==1.3.4 numpy==1.21.4 seaborn==0.9.0 matplotlib==3.5.0 scikit-learn==0.20.1```
2. Install juga tqdm untuk melihat progress training dan skillsnetwork <br>
```!pip install tqdm skillsnetwork```
3. Terakhir, upgrade Tensorflow <br>
```!pip3 install  --upgrade tensorflow```
4. Restart kernell
5. Jalankan semua kode

## 🕵️‍♀️ Analysis
Pada projek ini, DCGANs (Deep Convolutional Generative Adversatial Networks) dan Keras bekerja sama untuk membuat model untuk men-*generate* gambar baru.
DCGANs sangat menarik karena memiliki konsep yang unik dalam men-*generate* gambar baru, yaitu dengan Generator dan Discriminator. Generator bekerja dengan cara
menghasilkan gambar yang dilatih, lalu gambar tersebut diberikan ke Discriminator untuk ditentukan apakah gambar yang dihasilkan merupakan gambar hasil *generate* atau
gambar asli. Generator akan berusaha untuk mengelabui Discriminator agar discriminator memprediksi gambar tersebut merupakan bukan gambar hasil *generate*.
<br>
Lalu, dari segi teknis, dari pelatihan yang dilakukan, diketahui bahwa semakin besar *epochs* yang digunakan, maka semakin baik gambar yang di-*generate*.
Hal ini dapat dilihat dari hasil *generate* dari masing-masing *epoch*, dimana semakin besar *epochs*, maka semakin jelas juga gambar yang dihasilkan.
