# Assignment 1

Muhammad Rifa Al Rizqul Aulia (10241050)

## Problem 1
Manakah pernyataan berikut yang merupakan proposisi?
Berikan juga alasannya
1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika
  diskrit?
3. $3 + y = 14$ 
4. $34 \equiv 1 \quad (\text{mod } 11)$
5. Anita dan Bayu saling berteman.

### Answer
1. **Bukan proposisi**. Ini adalah kalimat perintah, bukan pernyataan proposisi yang mengandung nilai benar atau salah.
2. **Bukan proposisi**. Ini adalah kalimat pertanyaan yang tidak bisa dinilai benar atau salah.
3. **Bukan proposisi**. Ini adalah pernyataan yang mengandung variabel *y* yang harus diketahui terlebih dahulu nilainya agar bisa dinilai benar atau salah.
4. **Proposisi**. Ini adalah pernyataan matematika yang bisa dinilai benar atau salah, dan pernyataan ini adalah benar, karena $34 (\text{mod }11) \equiv 1$.
5. **Proposisi**. Ini adalah pernyataan yang bisa bernilai benar atau salah, tergantung dari apakah Anita dan Bayu berteman atau tidak.

## Problem 2
Secara lengkap ada 16 logika operator yang dapat digunakan untuk dua buah
proposisi $A$ dan $B$.
- konjungsi ($\operatorname{AND}$)
- disjungsi ($\operatorname{OR}$)
- eksklusif OR ($\operatorname{XOR}$)
- pernyataan bersyarat / implikasi ($\rightarrow$)
- bi-implikasi ($\leftrightarrow$)

Carilah sisa 11 operator logika yang lain dan berikan tabel kebenarannya. Mengapa ada beberapa operator logika yang tidak 
populer digunakan?

### Answer
Berikut adalah sisa 11 operator logika selain yang telah disebutkan di soal:
- $ \operatorname{A} $
- $ \operatorname{B} $
- negasi A ($ \operatorname{NOT \; A} $)
- negasi B ($ \operatorname{NOT \; B} $)
- negasi AND ($ \operatorname{NAND} $)
- negasi OR ($ \operatorname{NOR} $)
- negasi eksklusif OR ($ \operatorname{XNOR} $)
- converse ($B \rightarrow A$)
- contrapositive ($\neg B \rightarrow \neg A$)
- inverse ($\neg A \rightarrow \neg B$)
- negasi bi-implikasi ($\neg A \leftrightarrow \neg B$)

Berikut adalah tabel kebenaran dari 16 operator logika tersebut:
|$A$ | $B$ | $\neg A$  | $\neg B$ |$A \wedge B$|$A\vee B$|$A\oplus B$|$A\rightarrow B$|$B\rightarrow A$|$A\uparrow B$|$A\downarrow B$|$A\odot B$|$A\leftrightarrow B$|$\neg A \rightarrow \neg B$|$\neg B \rightarrow \neg A$|$\neg A \leftrightarrow \neg B$|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
|T|T|F|F|T|T|F|T|T|F|F|T|T|T|T|T
|T|F|F|T|F|T|T|F|T|T|F|F|F|T|F|F
|F|T|T|F|F|T|T|T|F|T|F|F|F|F|T|F
|F|F|T|T|F|F|F|T|T|T|T|T|T|T|T|T

Alasan mengapa beberapa operator logika yang tidak populer digunakan adalah dikarenakan beberapa operator logika seperti AND, OR, NOT merupakan dasar fundamental dalam logika dan sering digunakan dalam berbagai konteks, baik dalam matematika, ilmu komputer, atau kehidupan sehari-hari. Sedangkan, operator logika seperti NAND, NOR, XOR, atau semacamnya memiliki definisi yang lebih rumit dan jarang digunakan. Operator-operator seperti ini mungkin hanya relevan di bidang tertentu dan kurang dikenal di bidang lainnya.

## Problem 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut:
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$

### Answer
1. |$p$|$q$|$(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$|
    |-|-|-|
    |F|F|T
    |F|T|F
    |T|F|T
    |T|T|T
2. |$p$|$q$|$r$|$(p \leftrightarrow \neg q)$|$((p \leftrightarrow \neg q)\oplus r)$|$((p \leftrightarrow \neg q)\oplus r)\vee r$|
    |-|-|-|-|-|-
    |T|T|T|F|T|T
    |T|T|F|F|F|F
    |T|F|T|T|T|T
    |T|F|F|T|F|T
    |F|T|T|T|T|T
    |F|F|T|F|T|T
    |F|F|F|T|F|F

## Problem 4
Tentukan konvers, kontrapositive, dan invers dari
pernyataan kondisional berikut
1. Jika hari ini hujan, maka saya tidak akan datang ke
   kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika
   hari kemarin saya lupa untuk belajar.

### Answer
1. - Konvers: "Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini hujan."
    - Kontrapositive: "Jika saya datang ke kuliah matematika diskrit, maka hari ini tidak hujan."
    - Invers: "Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit."
2. - Konvers: "Jika saya akan belajar hingga jam dua dini hari, maka hari kemarin saya lupa untuk belajar."
    - Kontrapositive: "Jika saya tidak belajar hingga jam dua dini hari, maka hari kemarin saya tidak lupa untuk belajar."
    - Invers: "Jika hari kemarin saya tidak lupa untuk belajar, maka saya tidak akan belajar hingga jam dua dini hari."

## Problem 5
Sebagai imbalan karena menyelamatkan putri seorang
raja, seorang pemuda diberi kesempatan untuk
memperoleh sejumlah koin emas yang tersimpan
di salah satu tiga kotak yang ditawarkan oleh raja.
Dua kotak diantara tiga kotak merupakan kotak kosong.
Agar pemuda tersebut memperoleh koin emas, dia harus memilih
kotak yang tepat. Di setiap kotak tertulis ukiran berikut:
- Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
- Kotak 3: "Koin emas berada di kotak 1".  

Permaisuri yang tidak pernah berbohong membantu pemuda 
tersebut dengan mengatakan bahwa hanya ada satu ukiran
yang sesuai dengan isi kotak, dan dua sisanya adalah palsu.
Kotak manakah yang harus dipilih oleh pemuda tersebut?

### Answer
- Jika kotak 1 yang benar:
    - Ukiran pada Kotak 1 (benar) menyatakan bahwa Kotak 1 kosong.
    - Ukiran pada Kotak 2 (palsu) menyatakan bahwa Kotak 2 kosong, yang mungkin benar, tetapi tidak mungkin keduanya kosong jika Kotak 1 benar.
    - Ukiran pada Kotak 3 (palsu) menyatakan bahwa Koin emas berada di Kotak 1, yang bertentangan dengan asumsi bahwa Kotak 1 berisi koin emas.

    **Ini kontradiksi.**
- Jika kotak 2 yang benar:
    - Ukiran pada Kotak 1 (palsu) menyatakan bahwa Kotak 1 kosong, padahal bisa jadi Kotak 1 berisi koin emas.
    - Ukiran pada Kotak 2 (benar) menyatakan bahwa Kotak 2 kosong.
    - Ukiran pada Kotak 3 (palsu) menyatakan bahwa Koin emas berada di Kotak 1, yang tidak bisa terjadi karena Kotak 2 kosong.

    **Ini kontradiksi.**
- Jika kotak 3 yang benar:
    - Ukiran pada Kotak 1 (palsu) menyatakan bahwa Kotak 1 kosong, yang bisa saja benar atau salah.
    - Ukiran pada Kotak 2 (palsu) menyatakan bahwa Kotak 2 kosong, yang bisa juga benar atau salah.
    - Ukiran pada Kotak 3 (benar) menyatakan bahwa Koin emas berada di Kotak 1. Ini bisa jadi tidak benar, tetapi jika Kotak 3 adalah yang benar, maka ada kemungkinan Koin emas berada di Kotak 2.

    **Tidak ada kontradiksi.**

Dapat disimpulkan, satu-satunya situasi yang tidak mengandung kontradiksi adalah jika ukiran pada Kotak 3 yang benar. Jadi, pemuda tersebut seharusnya **memilih Kotak 3 untuk mendapatkan koin emas**.