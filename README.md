# Analisis Tingkat Stres Akademik Mahasiswa

## Overview
Proyek ini bertujuan untuk menganalisis faktor-faktor yang berkontribusi terhadap tingkat stres akademik pada mahasiswa menggunakan dataset yang dikumpulkan. Analisis dilakukan untuk mengidentifikasi pola, hubungan antara berbagai faktor (seperti tekanan akademik, lingkungan belajar, kebiasaan, dan strategi koping) dengan tingkat stres, serta memvisualisasikan temuan kunci.

## Dataset
Dataset yang digunakan dalam analisis ini adalah `academic Stress level - maintainance 1.csv`. Dataset ini berisi informasi tentang berbagai aspek kehidupan akademik mahasiswa dan tingkat stres mereka.
[Link Dataset (termasuk dalam repositori ini)](https://www.kaggle.com/datasets/poushal02/student-academic-stress-real-world-dataset/data)

## Insights & Findings
Berdasarkan analisis data, beberapa insight utama yang ditemukan meliputi:

- **Faktor Utama Penyebab Stres:** Tekanan akademik dari rumah dan teman sebaya, serta lingkungan belajar yang terganggu (berisik atau kacau), merupakan kontributor signifikan terhadap tingkat stres mahasiswa. Tingkat persaingan akademik yang tinggi juga berkorelasi dengan stres yang lebih tinggi.
<img width="1210" height="659" alt="image" src="https://github.com/user-attachments/assets/f640b3ac-e0b5-4293-b18f-e3d1c2f5cf66" />

- **Strategi Koping Dominan:** Strategi koping yang paling sering dilaporkan adalah 'Analyze the situation and handle it with intellect'. Dukungan sosial (teman, keluarga) juga merupakan strategi umum. 'Emotional breakdown (crying a lot)' lebih sering dilaporkan pada tingkat stres yang tinggi.
<img width="576" height="455" alt="image" src="https://github.com/user-attachments/assets/9a855acb-dbda-4120-9b26-8d6d8371697d" />

- **Hubungan Peer Pressure vs Stress:** Ada kecenderungan bahwa tekanan teman sebaya yang lebih tinggi berkorelasi dengan tingkat stres yang lebih tinggi, meskipun tidak selalu linear.
- <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/1cc999ed-7db6-4a1e-831c-64e07c8175df" />


- **Dampak Lingkungan Belajar:** Lingkungan belajar yang tenang berkorelasi dengan tingkat stres yang lebih rendah, sementara lingkungan yang berisik atau terganggu terkait dengan stres yang lebih tinggi.
- <img width="833" height="547" alt="image" src="https://github.com/user-attachments/assets/4048e622-2653-42a3-a591-e050b7c892ff" />


- **Analisis Sentimen Strategi Koping:** Strategi koping umumnya dapat dikategorikan menjadi positif (problem-solving, dukungan emosional) dan netral/negatif (menghindari, melepaskan emosi secara berlebihan).
- <img width="915" height="411" alt="image" src="https://github.com/user-attachments/assets/7ccff674-98d8-4cd6-9d13-e9cf5a6debc7" />


## AI Support
Analisis dalam proyek ini didukung oleh model bahasa besar IBM Granite (ibm-granite/granite-3.3-8b-instruct) yang diakses melalui platform Replicate dan framework Langchain. LLM digunakan untuk klasifikasi otomatis tingkat stres berdasarkan data mahasiswa dan untuk menghasilkan analisis ringkas serta kode visualisasi berdasarkan subset data yang relevan. Pendekatan ini memungkinkan eksplorasi data yang lebih cepat dan efisien.
