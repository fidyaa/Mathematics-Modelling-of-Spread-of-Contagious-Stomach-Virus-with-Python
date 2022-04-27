#### Mathematics-Modelling-of-Spread-of-Contagious-Stomach-Virus-with-Python

##### Asumsi
1. Individu hidup dalam suatu array 2 dimensi yang diwakilkan oleh grid berukuran 25x25
2. Individu berada di setiap sel
3. Inisialisasi grid menggunakan probSusceptible dan probInfectious yang digunakan untuk simulasi
4. Jumlah dari probSusceptible dan probInfectious lebih dari 0 dan kurang dari 1
5. Individu yang telah terinfeksi selama 2 hari akan menjadi kebal dan kekebalan tersebut berlangsung selama 5 hari
6. Terdapat aturan transisi yang menentukan bagaimana sel berubah dari keadaan yang satu ke keadaan yang lain

#### Aturan Transisi
1. Jika individu yang ditinjau adalah SUSCEPTIBLE dan tetangganya INFECTIOUS, maka individu tersebut menjadi INFECTIOUS juga.
2. Individu yang INFECTIOUS akan terinfeksi virus selama 2 hari.
3. Individu yang IMMUNE akan memiliki kekebalan yang berlangsung selama 5 hari, setelah itu individu tersebut kembali menjadi SUSCEPTIBLE.


