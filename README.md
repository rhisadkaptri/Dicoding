# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju adalah sebuah perusahaan multinasional yang didirikan pada tahun 2000. Perusahaan ini beroperasi di berbagai sektor dan memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri.

Meskipun telah tumbuh menjadi perusahaan yang cukup besar, Jaya Jaya Maju menghadapi tantangan signifikan dalam mengelola karyawan. Salah satu masalah utama yang mereka hadapi adalah tingginya tingkat perputaran karyawan (attrition rate), yang telah melebihi 10%. Tingkat attrition rate yang tinggi ini dapat berdampak negatif pada stabilitas organisasi serta biaya yang dikeluarkan untuk merekrut dan melatih karyawan baru.

### Permasalahan Bisnis

Tingkat perputaran karyawan yang melebihi 10% menandakan bahwa banyak karyawan yang meninggalkan perusahaan secara reguler, yang dapat mengakibatkan biaya tambahan untuk merekrut dan melatih karyawan baru. Hal ini tidak hanya mengganggu efisiensi operasional, tetapi juga berpotensi mengganggu stabilitas tim dan kontinuitas proyek. Selain itu, tingkat attrition yang tinggi juga dapat berdampak negatif pada citra perusahaan sebagai tempat kerja yang stabil dan menarik bagi bakat-bakat baru. Oleh karena itu, mengidentifikasi dan mengatasi penyebab dari tingginya attrition rate menjadi kunci bagi Jaya Jaya Maju untuk memperbaiki produktivitas, menjaga kestabilan organisasi, dan meningkatkan reputasi mereka di pasar.

### Cakupan Proyek

- Melakukan cleansing data pada data target yang NaN (tidak diketahui)
- Melakukan analisis dan penggalian informasi mengenai `Attrition` dari dataset yang disediakan
- Melakukan exploratory data analysis dan memilih feature important yang berpengaruh terhadap `Attrition`
- Membuat model machine learing untuk memprediksi apakah employee tersebut Attrition atau tidak. Model yang digunakan adalah CatBoost Classifier
- Menguji model yang telah dilatih menggunakan data dummy yang di input langsung
- Membuat dashboard dari analisis yang sudah dikerjakan

### Persiapan

Sumber data: https://raw.githubusercontent.com/rhisadkaptri/Dicoding/main/employee_data.csv

Setup environment:

```

```

## Business Dashboard

Dashboard yang saya buat berisikan analisis mengenai `Attrition Employee`

![rhisadkaptri-dashboard](https://github.com/rhisadkaptri/Dicoding/assets/76622802/7a929536-5be6-4b17-a5ae-8ecd1677aba5)
Link Dashboard: https://public.tableau.com/views/DashboardAttrition_17187789565080/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

## Conclusion

Berdasarkan analisis yang telah dilakukan, feature yang paling berpengaruh adalah:
1. `Overtime` merupakan feature yang sangat berpengaruh terhadap Employee Attrition, karena dapat dilihat di visualisasi yang telah dibuat di notebook, walaupun employee dengan overtime paling banyak berstatus No, tetapi employee yang Attrition adalah dengan overtime berstatus `Yes`.
2. `MaritalStatus` merupakan feature kedua yang berpengaruh terhadap Employee Attrition, ternyata MaritalStatus yang paling banyak mengalami Attrition adalah berstatus `Single`.
3. `TotalWorkingYears` merupakan feature ketiga yang berpengaruh terhadap Employee Attrition, employee yang paling banyak mengalami Attrition adalah employee dengan total kerja di antara 0-5 tahun, yang berarti merupakan employee baru.

### Rekomendasi Action Items (Optional)

Beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka menurut saya dari analisis tersebut adalah
- Pada employee yang mengalami poin 1, rekomendasi action yang dapat diberikan adalah berupa gaji tambahan, jika employee tersebut bekerja lembur. Selain itu, dapat memberikan makan malam gratis, jika employee tersebut bekerja sampai malam. Hal ini menandakan bahwa employee tersebut giat dalam bekerja, sehingga dapat mempertahan employee ini, dan tidak melakukan Attrition.
- Pada employee yang mengalami poin 2 dan 3, jika employee tersebut masih berstatus Single dan masih baru bekerja di perusahan tersebut, berarti rentang umur rata-rata mereka di umur 20-30 tahun, hal ini merupakan umur yang relatif masih mencari jati diri yang sesungguhnya, atau employee yang masih mengecek apakah mereka cocok di pekerjaan tersebut atau tidak. Berdasarkan pernyataan tersebut, rekomendasi action yang saya berikan adalah untuk employee yang masih baru ini memberikan training mengenai latar belakang perusahaan tersebut untuk employee yang baru. Sehingga rasa percaya terhadap perusahaan tersebut tumbuh dan menjadikan dia lebih semangat untuk bekerja di perusahaan itu.
