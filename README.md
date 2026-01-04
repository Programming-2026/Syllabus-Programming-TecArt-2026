# Syllabus-Divisi-Programming-Tecart

## 🔗 Situs Latihan Competitive Programming

- [Codeforces](https://codeforces.com) -> cocok untuk latihan algoritma dan contest rutin
- [AtCoder](https://atcoder.jp) -> cocok untuk contest berkualitas dan problem variatif
- [LeetCode](https://leetcode.com) -> cocok untuk latihan struktur data dan interview-style problem
- [HackerRank](https://www.hackerrank.com) -> cocok untuk latihan dasar hingga lanjutan
- [TLX TOKI](https://tlx.toki.id) -> CP versi Indonesia (IOI style)

## ⭐ Rekomendasi Latihan Competitive Programming

- ⭐ **[Codeforces](https://codeforces.com)**  
    Cocok untuk meningkatkan kecepatan dan logika problem solving.

- ⭐ **[TLX TOKI](https://tlx.toki.id)**  
    Codeforces versi indonesia (cocok untuk latihan soal soal kompetisi, seperti GEMASTIK, RECURSION (UNHAS), FIND IT (UGM), ARKAVIDIA (ITB), BNPCHS (BINUS), INC (BINUS NASIONAL), ICPC (BINUS INTERNASIONAL), SCHEMATICS (ITS), OSN, OSN-K, OSN-P)

## 🎓 Materi Pembelajaran Divisi Programming
### Data Structures and Algorithms (DSA)
Struktur data atau data structure adalah cara yang digunakan untuk menyimpan data. Dimana, struktur data ini akan memberi kemungkinan untuk mengolah data menjadi lebih efisien, tergantung bagaimana kita menyimpan data tersebut. Struktur data ini penting untuk membuat kompleksitas program berkurang, mempermudah mengelola dan mengatur data, serta meningkatkan efisiensi.

Algoritma adalah serangkaian instruksi atau langkah-langkah yang dibuat untuk menyelesaikan suatu masalah atau mencapai suatu tujuan. Pada dasarnya dalam kehidupan sehari-hari kita sering menggunakan algoritma, seperti saat memasak mie, telor, dan membuat hal lain secara sistematis dan terstrktur. Dalam programming, algoritma biasanya digunakan untuk menyelesaikan sesuatu, seperti mencari suatu data, mengurutkan data, ataupun operasi matematika.

Terdapat beberapa hal yang perlu dipelajari pada data structure. Tapi, materi yang sering bermunculan pada kompetisi adalah mengenai Array, Linked List, Stack & Queue, Hash Table, Tree, dan Graph.

#### 📦 Array
Array adalah struktur data yang digunakan untuk menyimpan banyak elemen. Pada array teradapat beberapa cara untuk pengolahan data, seperti sorting dan searching.

Pada pengurutan atau sorting terdapat bubble sort, selection sort, insertion sort, quick sort, counting sort, radix sort, dan merge sort. Rekomendasi -> Pelajari brute force (bubble sort, selection, atau insertion sort), lalu lanjut ke algoritma yang lebih efisien, seperti quick sort atau merge sort (dengan kompleksitas rata-rata O(n log n)) 

Pada pencarian atau searching terdapat linear search dan binary search. Rekomendasi -> Pelajari Konsep Linear Search, lalu lanjut ke binary search untuk pencarian lebih efisien (dengan kompleksitas rata rata O(log n)).

Materi lebih lanjut dapat diakses pada link berikut:
- [Array](https://www.w3schools.com/dsa/dsa_data_arrays.php)

Problem solving exercises:
- [Leetcode Array](https://leetcode.com/studyplan/leetcode-75/)
- [TLX Searching](https://tlx.toki.id/problems?page=1&tags=topic-searching)

#### 🧵 Linked List
Linked list pada dasarnya mirip dengan array, yang membedakan adalah linked list terdiri dari node dan merupakan struktur linear yang kita buat sendiri. Sedangkan array merupakan struktur data yang memang sudah ada dalam bahasa pemrograman yang dapat kita gunakan berulang kali.

Materi lebih lanjut dapat diakses pada link berikut:
- [Linked List](https://www.w3schools.com/dsa/dsa_theory_linkedlists.php)

Problem solving exercises:
- [Leetcode Linked List](https://leetcode.com/studyplan/leetcode-75/)

#### 📚 Stack & 🚶 Queue
Secara sederhana stack diumpamakan seperti tumpukan buku, dimana setiap kita mengambil itu dimulai dari atas. Stack menggunakan prinsip LIFO atau last in first out. Sedangkan queue diumpamakan seperti antrian saat berbelanja, dimana orang yang mengantri lebih awal akan mendapatkan gilirannya terlebih dahulu. Queue menggunakan prinsip FIFO atau first in first out.

Kompleksitas dari stack adalah O(n) untuk menyimpan n elemen, O(n) untuk pencarian, serta O(1) untuk operasi dasar (push, pop, peak, dan isEmpty).

Mirip seperti stack, queue juga memiliki kompleksitas O(n) untuk menyimpan n elemen, serta O(1) untuk operasi dasar (enqueue, dequeue, front, dan isEmpty). Tetapi, stack tidak dirancang untuk sistem pencarian.

Materi lebih lanjut dapat diakses pada link berikut:
- [Stack](https://www.w3schools.com/dsa/dsa_data_stacks.php)
- [Queue](https://www.w3schools.com/dsa/dsa_data_queues.php)

Problem solving exercises:
- [Leetcode Stack](https://leetcode.com/problems/asteroid-collision/description/?envType=study-plan-v2&envId=leetcode-75)
- [Leetcode Queue](https://leetcode.com/problems/dota2-senate/description/?envType=study-plan-v2&envId=leetcode-75)

#### 🗂️ Hash Table
Hash table adalah struktur data yang digunakan untuk menyimpan dan mengakses data dengan sangat cepat berdasarkan key. Intinya, hash table menyimpan data dalam bentuk pasangan key–value, di mana sebuah hash function digunakan untuk mengubah key menjadi index pada tabel. Dengan mekanisme ini, proses pencarian, penambahan, dan penghapusan data dapat dilakukan dengan kompleksitas waktu yang sangat rendah (rata-rata O(1)).

Materi lebih lanjut dapat diakses pada link berikut:
- [Hash Table](https://www.w3schools.com/dsa/dsa_theory_hashtables.php)

Problem solving exercise:
- [Leetcode Hash Table](https://leetcode.com/problems/equal-row-and-column-pairs/description/?envType=study-plan-v2&envId=leetcode-75)

#### 🌳 Tree
Tree merupakan data structure yang menggunakan konsep dari linked list. Dimana, tiap node memiliki data dan mereka dapat dihubungkan ke node lain. Tidak seperti array, linked list, stack, dan queue, yang dimana mereka merupakan linear data structure, yang berarti setiap elemen mengikuti elemen lain secara berurutan. Namun, tree berbeda. Dalam sebuah Tree, satu elemen dapat memiliki banyak elemen 'berikutnya', yang memungkinkan struktur data untuk bercabang ke berbagai arah atau sering disebut dengan non-linear data structutre.

Materi lebih lanjut dapat diakses pada link berikut:
- [Tree](https://www.w3schools.com/dsa/dsa_theory_trees.php)

Problem solving exercise:
- [TLX Tree](https://tlx.toki.id/problems/?page=1&tags=topic-tree)

#### 🗺️ Graph
Mirip dengan Tree, Graph juga non-linear data structure. Dimana, Graph merupakan struktur data yang terdiri dari simpul (node) dan sisi (edge). Sebuah vertex, juga disebut simpul, yang merupakan sebuah titik atau objek dalam Graph, dan sebuah sisi digunakan untuk menghubungkan dua vertex satu sama lain.

Mteri lebih lanjut dapat diakses pada link berikut:
- [Graph](https://www.w3schools.com/dsa/dsa_theory_graphs.php)

Problem solving exercise:
- [TLX Graph](https://tlx.toki.id/problems?page=1&tags=topic-graph)
- [Leetcode Graph](https://leetcode.com/studyplan/graph-theory/)

### Jenis Algoritma
#### Prefix Sum
Prefix sum adalah teknik membuat array baru di mana setiap elemen menyimpan jumlah kumulatif dari elemen-elemen sebelumnya sampai indeks itu.

Materi:
- [Prefix Sum](https://www.geeksforgeeks.org/dsa/prefix-sum-array-implementation-applications-competitive-programming/)

Latihan:
- [TLX Prefix Sum](https://tlx.toki.id/problems?page=1&tags=topic-data%20structure%3A%20prefix%20sum)

#### Sieve's Algorithm
Sieve's Algorithm adalah metode efisien menemukan semua bilangan prima ≤ n dengan menyingkirkan kelipatan dari setiap angka prima.

Materi:
- [Sieve's Algorithm](https://www.geeksforgeeks.org/dsa/sieve-of-eratosthenes/)

Latihan:
- [Leetcode Count Number](https://leetcode.com/problems/count-primes/)

#### Ternary Search
Ternary search adalah versi pencarian yang membagi ruang pencarian menjadi tiga bagian (bukan dua seperti binary search), biasanya dipakai untuk fungsi unimodal di mana ada maksimum/minimum tunggal.

Materi:
- [Ternary Search](https://www.geeksforgeeks.org/dsa/ternary-search/)

Latihan:
- [TLX Ternary Search](https://tlx.toki.id/courses/competitive-2/chapters/01/problems/C)

#### Dynamic Programming
Dynamic programming adalah teknik menyelesaikan masalah dengan memecah jadi submasalah yang tumpang tindih dan menyimpannya supaya tidak dihitung ulang (memo / tabulation).

Materi:
- [DP](https://www.geeksforgeeks.org/dsa/introduction-to-dynamic-programming-data-structures-and-algorithm-tutorials/)

Latihan:
- [Leetcode DP](https://leetcode.com/studyplan/dynamic-programming/)

#### Euclidean Algorithm
Euclidean algorithm adalah algoritma untuk mencari faktor persekutuan terbesar (GCD) dari dua bilangan, dengan mengurangi/dibagi sampai habis.

Materi:
- [Euclidean Algorithm](https://www.geeksforgeeks.org/dsa/euclidean-algorithms-basic-and-extended/)

Latihan:
- [Leetcode Euclidean](https://leetcode.com/problems/greatest-common-divisor-of-strings/)

#### Greedy Algorithm
Greedy adalah teknik memilih langkah terbaik lokal di setiap tahap agar mendapatkan solusi global yang optimal.

Materi:
- [Greedy Algorithm](https://www.geeksforgeeks.org/dsa/greedy-algorithms/)

Latihan:
- [TLX Greedy](https://tlx.toki.id/problems?page=1&tags=topic-greedy)

#### Binary Search Tree
BST adalah Struktur data pohon biner terurut di mana setiap nilai di kiri < node, dan kanan > node. Ideal untuk pencarian dan operasi dinamis.

Materi:
- [BST](https://www.geeksforgeeks.org/dsa/binary-search-tree-data-structure/)

Latihan:
- [TLX BST](https://tlx.toki.id/problems?page=1&tags=topic-data%20structure%3A%20binary%20search%20tree)

#### Binary Search
Binary search adalah metode pencarian membagi dua bagian secara rekursif/iteratif di array yang sudah terurut.

Materi:
- [Binary Search](https://www.geeksforgeeks.org/dsa/binary-search/)

Latihan:
- [TLX Binary Search](https://tlx.toki.id/problems?page=1&tags=topic-searching%3A%20binary%20search)

#### Quick Sort
Quick sort adalah algoritma Divide & Conquer untuk mengurutkan dengan memilih pivot, mempartisi, lalu mengurutkan bagian kiri & kanan.

Materi:
- [Quick Sort](https://www.geeksforgeeks.org/dsa/quick-sort-algorithm/)

Latihan:
- [Leetcode Sort Problem](https://leetcode.com/problems/sort-an-array/description/)

#### Dijkstra's Algorithm
Dijkstra adalah algoritma jalur terpendek dari satu sumber ke semua node dalam graf berbobot positif.

Materi:
- [Dijkstra](https://www.geeksforgeeks.org/dsa/dijkstras-shortest-path-algorithm-greedy-algo-7/)

Latihan:
- [Leetcode Shortest Path](https://leetcode.com/problem-list/graph/)

#### Breadth First Search (BFS)
BFS adalah algoritma pendataan graf yang menjelajah level demi level.

Materi:
- [BFS](https://www.geeksforgeeks.org/dsa/breadth-first-search-or-bfs-for-a-graph/)

Latihan:
- [Leetcode BFS](https://leetcode.com/problem-list/breadth-first-search/)

#### Depth First Search (DFS)
DFS adalah algoritma graf yang menjelajah setinggi mungkin di satu jalur sebelum mundur.

Materi:
- [DFS](https://www.geeksforgeeks.org/dsa/depth-first-search-or-dfs-for-a-graph/)

Latihan:
- [Leetcode DFS](https://leetcode.com/problem-list/depth-first-search/)
