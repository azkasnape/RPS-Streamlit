![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Logo_umm.png)

# **ROCK PAPER SCISSORS PREDICTION on STREAMLIT**
##### _by AZKA FAZA DZULQARNAIN - 202010370311154_

### Overview
Project ini adalah Project Machine Learning untuk memprediksi gambar. Gambar yang diprediksi yaitu Gunting Batu Kertas.

### Reuqirement on This Project
- os
- time
- cv2
- numpy
- tensorflow
- streamlit
- PIL

### Dataset
Dataset yang digunakan dalam project ini yaitu ada 2520 gambar yang terbagi menjadi Data Training, Data Validation, dan Data Testing.
![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Dataset.png)

### Preprocessing
Rescale: Mengubah nilai piksel menjadi rentang 0 hingga 1.
Rotation Range: Rentang rotasi gambar sebanyak 40 derajat.
Width Shift Range: Rentang pergeseran horizontal gambar sebanyak 20% dari lebar gambar.
Shear Range: Rentang pemiringan gambar sebanyak 20%.
Zoom Range: Rentang zoom gambar sebanyak 20%.
Horizontal Flip: Melakukan flipping horizontal pada gambar.
Fill Mode: Mode pengisian untuk area yang baru muncul setelah augmentasi, menggunakan metode terdekat.
Validation Split: Memisahkan sebagian data untuk validasi (20%).

### Deep Learning Model
Model deep learning yang digunakan dalam project ini yaitu InceptionV3. Inception-V3 adalah sebuah arsitektur deep convolutional yang merupakan hasil dari pengembangan model GoogleNet atau Inception-v1 yang dikembangkan dari penelitian (Szegedy et al., 2015)
![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Architecture.png)

### Model Summary
Model Summary:
![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Model.png)
Total Trainable Parameters: 21,802,784 + 262,272 + 387 = 22,065,443

### Training Result
Model mencapai akurasi tinggi pada data pelatihan dan validasi.
Tidak terlihat tanda-tanda overfitting atau underfitting yang signifikan.
Model dapat digunakan untuk klasifikasi gambar rock, paper, dan scissors dengan performa yang baik pada dataset yang digunakan.
![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Training.png)

### Prediction and Deployment on Streamlit
![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Prediction Result Model.png)
![alt text](https://github.com/azkasnape/RPS-Streamlit/blob/main/screenshots/Streamlit.png)
