Nama : Prawira Setia Ramdhani <br> 
Kelas : INF – A2 <br>
NPM : 41155050210062 <br>
TUGAS 5 

A. K-Nearest Neighbours (KNN).Lakukan praktik dari https://youtu.be/4zARMcgc7hA?si=x6RoHQXFF4NY76X8, 
buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini: 
1. Persiapan Sample Dataset 
![Persiapan sample dataset sensus](https://github.com/user-attachments/assets/93441ab9-6ba6-491e-9aca-3468c20257af)
 

 

 

 

 

 

 

 

 

 

 

 

 

2. Visualisasi Dataset 
![Visualisasi Data sensus](https://github.com/user-attachments/assets/8a2e57a5-fbb8-4801-b035-fbe4e5f615fc)

 

 

 

3. Pengantar classification dengan K-Nearest Neighbours | KNN Algoritma K-Nearest Neighbor (KNN) adalah algoritma machine learning yang bersifat non-parametric dan lazy learning. 
   Metode yang bersifat non-parametric memiliki makna bahwa metode tersebut tidak membuat asumsi apa pun tentang distribusi data yang mendasarinya. Dengan kata lain, tidak ada jumlah parameter atau estimasi parameter yang tetap dalam model,
   terlepas data tersebut berukuran kecil ataupun besar. Algoritma non-parametric seperti KNN menggunakan sejumlah parameter yang fleksibel, dan jumlah parameter seringkali bertambah seiring data yang semakin banyak. Algoritma non-parametric secara komputasi lebih lambat,
   tetapi membuat lebih sedikit asumsi tentang data. Algoritma KNN juga bersifat lazy learning, yang artinya tidak menggunakan titik data training untuk membuat model. Singkatnya pada algoritma KNN tidak ada fase training, kalaupun ada juga sangat minim. 

 

 

 

 

 

 

 

 

 

 

4. Preprocessing dataset dengan Label Binarizer 
![Preprocessing Dataset sensus](https://github.com/user-attachments/assets/af9582e9-5163-43cf-b097-4f1d4813705b)
![Preprocessing Dataset sensus 2](https://github.com/user-attachments/assets/f94774dc-62b6-4428-bbb0-9bcbc1e3734d)
![Preprocessing Dataset sensus 3](https://github.com/user-attachments/assets/65db7ad8-790a-4b3c-af8e-0a78ca971f58)

 

 

 

 

 

 

5. Training KNN Classification Model 
![Training KNN Classification Model sensus](https://github.com/user-attachments/assets/9d11502c-64f6-4896-8042-8f88f8b85a27)

 

 

 

 

 

6. Prediksi dengan KNN Classification Model 
![Prediksi dengan KNN Classification Model sensus 1](https://github.com/user-attachments/assets/49cde7bf-46e9-434f-bec7-b6ed2bd03be6)
![Prediksi dengan KNN Classification Model sensus 2](https://github.com/user-attachments/assets/d8e83115-ae08-4eed-8d18-def2b6261f3b)

 

 

7. Visualisasi Nearest Neighbours 
![Visualisasi Nearest Neighbours sensus](https://github.com/user-attachments/assets/43fd58ce-92cf-41f2-bf2c-2f70f693a3d2)

 

 

 

 

 

 

 

 

 

 

8. Kalkulasi jarak dengan Euclidean Distance 
![Kalkulasi jarak dengan euclidean distance sensus 1](https://github.com/user-attachments/assets/2cfd8827-8740-4dea-adc3-bb5658aac2a1)
![Kalkulasi jarak dengan euclidean distance sensus 2](https://github.com/user-attachments/assets/28f83e64-566e-41f5-a880-615b360e17a6)

 

 

9. Evaluasi KNN Classification Model | Persiapan testing set 
![Evaluasi KNN Classification Model atau persiapan testing set](https://github.com/user-attachments/assets/fb7fb1f5-a6b6-402d-925f-e96865cae328)

 

 

 

 

 

 

10. Evaluasi model dengan accuracy score 
![Evaluasi model dengan accuracy score](https://github.com/user-attachments/assets/ce327efc-583a-411d-870a-42d8cbba2aa8)

 

11. Evaluasi model dengan precision score 
![Evaluasi model dengan precision score sensus](https://github.com/user-attachments/assets/7ad06ea1-1a9a-4558-a4be-4c3e402511a1)

 

12. Evaluasi model dengan recall score 
![Evaluasi model dengan recall score sensus](https://github.com/user-attachments/assets/4087f480-5fac-4be6-9798-e2a23d0ea660)

 

13. Evaluasi model dengan F1 score 
![Evaluasi model dengan F1 score sensus](https://github.com/user-attachments/assets/8e29ac1a-54c3-40ad-8c68-fb9646d7f15c)
14. Evaluasi model dengan classification report 
![Evaluasi model dengan classification report sensus](https://github.com/user-attachments/assets/98af5f5e-e90a-47c9-939d-c940fa65da61)

 

 

 

15. Evaluasi model dengan Mathews Correlation Coefficient 
![Evaluasi model dengan Mathews Correlation Coefficient](https://github.com/user-attachments/assets/547558b1-7dda-4e6c-bd74-84bafe6039c8)

 

 

B. Support Vector Machine (SVM). Lakukan praktik dari https://youtu.be/z69XYXpvVrE?si=KR_hDSlwjGIMcT0w ,
   buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini: 
   1. Pengenalan Decision Boundary & Hyperplane 
   ![WhatsApp Image 2024-11-12 at 22 13 45](https://github.com/user-attachments/assets/645d74f4-92a5-4a5d-8750-5fab251f5d40)
      

   Decision boundary adalah garis yang membagi jalan atau margin menjadi 2 bagian yang sama besar. Hyperplane adalah bidang yang memisahkan kedua kelas,
   sedangkan margin adalah lebar 'jalan' yang membagi kedua kelas. 

   2. Pengenalan Support Vector & Maximum Margin  
   ![WhatsApp Image 2024-11-12 at 22 13 46](https://github.com/user-attachments/assets/4b5188e5-c603-418c-b3fb-974448aa302a)

    

   Maximum margin adalah model linier yang memisahkan kelas dalam satu set data dengan jarak yang paling jauh dari cangkang cembung kelas. 
   Pemisahan ini juga harus tegak lurus terhadap garis terpendek yang menghubungkan kelas tersebut. 

   3. Pengenalan kondisi Linearly Inseperable dan Kernel Tricks 
   ![WhatsApp Image 2024-11-12 at 22 13 46 (1)](https://github.com/user-attachments/assets/650e94d2-f57a-4288-9afc-48d5c1e3e73d)
     

   Dua set titik data dalam ruang dua dimensi dikatakan dapat dipisahkan secara linear jika keduanya dapat dipisahkan sepenuhnya oleh satu garis lurus.
   Secara umum, dua kelompok titik data dapat dipisahkan dalam ruang n-dimensi jika keduanya dapat dipisahkan oleh bidang hiper n-1 dimensi. 
   Trik kernel adalah teknik hebat yang memungkinkan SVM memecahkan masalah klasifikasi non-linier dengan memetakan data input secara implisit ke ruang fitur berdimensi lebih tinggi.
   Dengan demikian, kita dapat menemukan hiperbidang yang memisahkan kelas data yang berbeda. 

   4. Pengenalan MNIST Handwritten Digits Dataset 
   ![Pengenalan MNIST Handwritten Digits Dataset](https://github.com/user-attachments/assets/30247bd1-09df-4375-89e8-c3fbb6b9c2e1)
   ![Pengenalan MNIST Handwritten Digits Dataset 2](https://github.com/user-attachments/assets/20796973-75ae-43b7-b00c-173e73a8486f)
   ![Pengenalan MNIST Handwritten Digits Dataset 3](https://github.com/user-attachments/assets/73e17e91-2a51-4bd7-81f9-c27eafd48706)
   ![Pengenalan MNIST Handwritten Digits Dataset 4](https://github.com/user-attachments/assets/62f100e2-2ea7-4610-86c2-b9b26faaca1e)
      

 

 

 

 

    5. Klasifikasi dengan Support Vector Classifier | SVC 
    ![klasifikasi dengan support vector classifier SVC 1](https://github.com/user-attachments/assets/8643c96e-0288-4faa-b139-5094c773ef9d)
    ![klasifikasi dengan support vector classifier SVC 2](https://github.com/user-attachments/assets/f63320ab-d455-47e9-bb89-631bdf8ccf7f)


 

 

    6. Hyperparameter Tuning dengan Grid Search 
    ![Hyperparameter tuning dengan Grid Search 1](https://github.com/user-attachments/assets/2cf99175-b867-4385-8dc5-50e35bbc78d1)
    ![Hyperparameter tuning dengan Grid Search 2](https://github.com/user-attachments/assets/6b17abd4-06a9-4682-a865-f9d78c651893)

       

 

 

 

 

 

 

 

 

 

 

 

 

    7. Evaluasi Model 
    ![evaluasi model](https://github.com/user-attachments/assets/9a897df8-e96d-45c9-aaa4-d71ed71425d5)

       

 

 

 
