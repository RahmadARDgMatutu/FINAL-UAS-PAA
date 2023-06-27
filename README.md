#Analisis Final Project PAA

ALGORITMA BUBBLE SORT & INSERTION SORT
1. Worst Case:
Bubble Sort: Pada worst case, Bubble Sort memiliki kompleksitas waktu O(n^2), di mana n adalah jumlah elemen dalam array. Worst case terjadi ketika array terurut secara terbalik atau hampir terbalik, sehingga setiap elemen harus melakukan pertukaran dengan setiap elemen lainnya.
Insertion Sort: Pada worst case, Insertion Sort memiliki kompleksitas waktu O(n^2). Worst case terjadi ketika array terurut secara terbalik atau hampir terbalik, sehingga setiap elemen harus digeser ke posisi yang benar.
2. Best Case:
Bubble Sort: Pada best case, Bubble Sort memiliki kompleksitas waktu O(n), di mana n adalah jumlah elemen dalam array. Best case terjadi ketika array sudah terurut secara ascending, sehingga tidak ada pertukaran yang perlu dilakukan.
Insertion Sort: Pada best case, Insertion Sort memiliki kompleksitas waktu O(n), di mana n adalah jumlah elemen dalam array. Best case terjadi ketika array sudah terurut secara ascending, sehingga tidak ada pergeseran yang perlu dilakukan.
3. Average Case:
Bubble Sort: Pada average case, Bubble Sort memiliki kompleksitas waktu O(n^2), di mana n adalah jumlah elemen dalam array. Average case terjadi ketika array memiliki elemen-elemen acak yang tidak terurut secara terbalik maupun terurut.
Insertion Sort: Pada average case, Insertion Sort memiliki kompleksitas waktu O(n^2), di mana n adalah jumlah elemen dalam array. Average case terjadi ketika array memiliki elemen-elemen acak yang tidak terurut secara terbalik maupun terurut.

ALGORITMA TSP & DJIKSTRA

1. Travelling Salesman Problem (TSP):
Worst Case: Pada kasus terburuk, kompleksitas waktu TSP dengan pendekatan brute force adalah O(n!), di mana n adalah jumlah titik dalam graf. Hal ini disebabkan oleh jumlah kemungkinan permutasi yang harus dijelajahi untuk mencari rute terpendek.
Best Case: Tidak ada best case yang signifikan untuk TSP menggunakan pendekatan brute force, karena semua kemungkinan perlu dieksplorasi untuk menemukan solusi optimal.
Average Case: TSP menggunakan pendekatan brute force memiliki kompleksitas waktu rata-rata yang sangat tinggi dan sulit untuk dihitung secara pasti. Namun, dengan menggunakan algoritma heuristik atau pendekatan yang lebih efisien, kompleksitas waktu rata-rata dapat diperbaiki.

2. Dijkstra's Algorithm:
Worst Case: Pada kasus terburuk, kompleksitas waktu Dijkstra's Algorithm adalah O((V + E) log V), di mana V adalah jumlah titik (vertex) dalam graf dan E adalah jumlah tepi (edge). Hal ini terjadi ketika ada banyak jalur alternatif yang harus dieksplorasi dalam graf.
Best Case: Dalam kasus terbaik, di mana titik awal dan titik tujuan adalah tetangga langsung, kompleksitas waktu Dijkstra's Algorithm dapat mencapai O(V).
Average Case: Dalam kasus rata-rata, kompleksitas waktu Dijkstra's Algorithm dapat dianggap sebagai O((V + E) log V), di mana jumlah tepi (E) yang harus dieksplorasi cenderung seimbang dengan jumlah titik (V).
