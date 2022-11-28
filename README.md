## Context

Used cars adalah jenis kendaraan yang sebelumnya memiliki 1 atau lebih pemilik. Jenis mobil seperti ini sangat populer di negara berkembang seperti Saudi Arabia. Terjadi penurunan penjualan mobil baru pada tahun 2020 akibat lockdown total akibat Covid-19. Lockdown mengakibatkan orang-orang menjual mobilnya, sehingga terjadi pergeseran kepemilikan mobil. Ditambah lagi,  pemerintah memberlakukan pembatasan kegiatan masyarakatnya sehingga ekonomi mengalami kemunduran. Setelah pandemi berakhir, pasar mobil bekas lebih diminati daripada mobil baru karena orang mulai mencari mobil yang harganya terjangkau untuk perjalanan sehari-hari ataupun perjalanan jarak jauh. 

Bisnis mobil bekas merupakan salah satu bisnis yang sedang berkembang dan memiliki pasar yang kompetitif. Menjual dan membeli mobil bekas bisa menjadi hal yang sulit saat menentukan harga yang tepat. Jika harga mobil yang dijual terlalu mahal dibanding platform lain dengan fitur sejenis di wilayah sekitar tentu akan sulit menjual mobil tersebut. Sebaliknya,  jika harga mobil terlalu murah, tentu penjual mobil (host) tidak akan mendapatkan profit yang sepadan. Banyak faktor yang memengaruhi nilai dari suatu mobil bekas. Hal ini perlu dipahami oleh penjual karena berhubungan dengan profit yang akan didapat. 

syarah.com merupakan sebuah platform yang menyediakan dan menjual lebih  dari 50 merk mobil dan tersebar di lebih dari 20 Kota di Saudi Arabia. Platform ini hanya sebagai pihak ketiga antara pemilik mobil (host) dan calon pembeli mobil. model bisnis ini membebaskan host untuk menentukan harga jual mobilnya, hal ini menyulitkan host. Dataset yang digunakan ini berisi 5624 record mobil bekas yang dikumpulkan dari syarah.com. Setiap baris mewakili mobil bekas dengan informasi nama merk, model, tipe transmisi atau gear type, tahun pembuatan, asal, opsi, kapasitas mesin, jarak yang ditempuh mobil, status negosiasi, dan harga mobil.

## Problem Statement

Salah satu tantangan terbesar bagi perusahaan yang menjual mobil bekas adalah pemecehan masalah untuk dapat memiliki model bisnis yang menguntungkan secara finansial bagi pemilik/penjual (host) mobil dengan menjual mobil dengan harga yang sesuai, serta dapat memberikan pengalaman yang baik bagi pelanggan. Harga yang terlalu tinggi akan membuat pelanggan tidak tertarik untuk membeli dan memilih platform lain, namun harga yang terlalu rendah akan membuat pemilik rugi atau tidak mendapat profit yang sepadan.

## Goals

Berdasarkan permasalahan tersebut, perusahaan platform tentu perlu memiliki alat atau 'tool' yang dapat memprediksi serta membantu klien (pemilik mobil) untuk menentukan harga yang tepat untuk tiap mobil bekas yang akan dijual. Adanya perbedaan merk, model, tipe transmisi, jarak tempuh dan sebagainya dapat menambah keakuratan prediksi harga mobil bekas, yang mana dapat memberikan harga yang kompetitif di pasaran namun tetap mendatangkan profit bagi pemilik mobil juga harga yang masih terjangkau bagi pelanggan.

Bagi perusahaan 'tool' ini dapat meningkatkan jumlah host dan listing, dengan kata lain, semakin banyak pemilik mobil yang ingin menjual mobilnya di platform ini dan pembeli yang membeli mobil di platform ini berarti dapat meningkatkan revenue perusahaan platform yang didapat dari 'fee charge' baik dari pemilik mobil maupun pembeli mobil.

## Analytic Approach

Jadi, yang perlu kita lakukan adalah menganalisis data untuk dapat menemukan pola dari fitur-fitur yang ada, yang membedakan suatu mobil dengan yang lainnya. Selanjutnya, kita akan membangun suatu model regresi yang akan membantu perusahaan untuk dapat menyediakan 'tool' atau alat prediksi harga mobil bekas yang baru masuk dalam daftar, yang mana akan berguna bagi perusahaan dalam menentukan harga mobil bekas yang tepat agar terhindar dari underprice atau overprice.

