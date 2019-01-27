# algoritma A*

Algoritme A-Star (A*),(ditemukan pertama kali oleh Peter Hart, Nils Nilsson, dan Bertram Raphael pada tahun 1968) adalah algoritme pencarian rute terpendek (shortest path) yang merupakan perbaikan dari Algoritme BFS[1] dengan memodifikasi fungsi heuristiknya untuk memberikan hasil yang optimal. Dimana menggabungkan fungsi heuristik [h(n)] dan jarak sesungguhnya/cost [g(n)].

Notasi Algoritme
f(n) = g(n) + h(n)
Keterangan:

f(n) adalah jumlah dari g(n) dan h(n). ini adalah perkiraan jalur terpendek sementara. maka f(n) adalah jalur terpendek yang sebenarnya yang tidak ditelusuri sampai Algoritme A-Star (A*) diselesaikan.
g(n)/Geographical Cost adalah total jarak yang didapat dari verteks awal ke verteks sekarang (halangan).
h(n)/Heuristic Cost adalah perkiran jarak dari vertek sekarang (yang sedang dikunjungi) ke vertek tujuan. sebuah fungsi heuristic digunakan untuk membuat perkiraan seberapa jauh lintasan yang akan diamnbil ke vertek tujuan.

https://id.wikipedia.org/wiki/Algoritme_a-star
