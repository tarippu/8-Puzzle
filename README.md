# 8-Puzzle

#BFS Algorithm 
Breadth-first search disini melakukan pencarian secara melebar yang mengunjungi suatu simpul kemudian mengunjungi semua simpul yang bertentangga. Simpul anak yang telah dikunjungi disimpan didalam satu antrian. lalu antrian ini digunakan untuk mengacu simpul-simpul yang bertentangga dengannya yang akan dikunjungi kemudian sesuai urutan pengantriannya. Kegunaan dari BFS disini untuk memeriksa apakah graph terhubung, menghitung spanning forest graph, tiap vertex dalam graph
Pada contoh berikut menggunakan matrix 9x9, dimana start node nya dimulai dari [1,5,4, 3,7,2, 6,8,0] dan final node nya [0,1,2, 3,4,5, 6,7,8]

#DFS Algorithm
Depth First Search disini melakukan penelusuran struktur graf berdasarkan kedalaman.  penelusuran dilakukan terus melalui simpul anak pertama dari simpul anak pertama level sebelumnya hingga mencapai level terdalam. Setelah sampai di level terdalam, penelusuran akan kembali ke 1 level sebelumnya untuk menelusuri simpul anak kedua pada pohon biner [simpul sebelah kanan] lalu kembali ke langkah sebelumnya dengan menelusuri simpul anak pertama lagi sampai level terdalam dan seterusnya. Dalam implementasinya DFS dapat diselesaikan dengan cara rekursif atau dengan bantuan struktur data stack.
Pada contoh berikut menggunakan matrix 9x9, 

![](https://i.imgur.com/xmfrw19.png)
