# Proyek Submission MPK 

**Hasil Review**<br>
5 soal wajib dan 3 soal opsional sukses dijalankan.<br>
Masih ada 2 soal opsional yang belum terpenuhi.<br>

- Latihan opsional 3 belum memenuhi skenario pengujian berikut:
  - Jika argumennya adalah dicoding0101 dan 19, fungsi manipulateString() seharusnya mengembalikkan nilai dicoding1919.
- Latihan Opsional 5 belum memenuhi skenario pengujian berikut:
  - concatString() tidak boleh mengandung karakter {.


**Build**<br>
1. Folder lokal
Siapkan folder lokal di dalam laptop anda untuk menampung project ini
2. Git bash
Klik kanan pada folder tadi, kemudian pilih git bash here
3. Clone Project
Masukkan perintah di bawah ini ke dalam git bash
```
git clone https://github.com/adisputraa/sub-kotlin.git
```
4. Buka Intellij IDEA
5. Open folder yang sudah dibuat tadi melalui Intellij IDEA

**Cek**<br>
Untuk memerika hasil pengerjaan, buka terminal pada Intellij IDEA, lalu masukkan perintah berikut:
- Soal wajib
  ```
  gradle test --tests ExamTestMain -q
  ```
  atau
  ```
  ./gradlew test --tests ExamTestMain -q
  ```
- Soal opsional
  ```
  gradle test --tests ExamTestOptional -q
  ```
  atau
  ```
  ./gradlew test --tests ExamTestOptional -q
  ```
