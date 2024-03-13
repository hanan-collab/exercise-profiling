# Before Refactoring
## all-student
<img width="583" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/bc2205af-3792-4ad9-bc3d-eb79a4439a8e">

## all-student-name
<img width="793" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/625773a4-97f5-464d-9fc7-3733294adb17">

## highest-gpa
<img width="796" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/e7744361-f5be-417f-b1cd-8091499b05a9">

## testresults1.jtl
<img width="960" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/a609a78d-940f-483b-bbbb-512a0dbdea1c">

# After Refactoring
## all-student
<img width="582" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/60268c9e-356e-4711-b477-bf54f0622fc9">

## all-student-name
<img width="797" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/12bd2c09-b611-4fdc-b386-777b8cf199ce">

## highest-gpa
<img width="799" alt="image" src="https://github.com/hanan-collab/exercise-profiling/assets/63461469/8a36eb67-da5c-484a-8742-9152687df220">

# Reflection 5
Name: Hanan Adipratama
NPM : 2206081824
Kelas : B

## 1. Optimasi Performance Aplikasi JMeter vs Intellij Profiler
JMeter berperan sebagai alat untuk mengukur dan menganalisis kinerja aplikasi secara keseluruhan, termasuk respons time, throughput, dan sebagainya. Namun, JMeter tidak memberikan informasi mendalam tentang bagian internal dari aplikasi atau penyebab spesifik performa yang kurang optimal.

Di sisi lain, profiling adalah pendekatan yang lebih mendalam dalam menganalisis kinerja aplikasi. dengan IntelliJ Profiling kita dapat menganalisis penggunaan sumber daya (seperti CPU, memori, dan I/O) dan secara spesifik di mana waktu eksekusi lebih banyak dihabiskan untuk menentukan bagian-bagian kode membutuhkan optimasi.

## 2. Profiling Process
Dengan menganalisis dan melacak secara spesifik penggunaan sumber daya dan waktu eksekusi dari kode yang ada. Dengan begitu kita dapat menentukan bagian-bagian kode yang membutuhkan optimisasi.

## 3. Efektifitas Intellij Profiler
Setuju, dengan IntelliJ Profiler saya dapat mengetahui method yang penggunaan sumber daya dan waktu eksekusinya lebih lama. Dengan begitu, saya dapat mengoptimisasi kode-kode yang performanya masih kurang. Contohnya ketika mengoptimisasi method getAllStudentWithCourses.

## 4. Tantangan ketika Profiling
Saya sendiri belum terbiasa dari membaca hasil performance testingnya, padahal hal tersebut adalah poin penting untuk melacak method yang perlu dioptimisasi. Lebih dari itu menentukan cara mengoptimisasi menjadi tantangan tersendiri.

## 5. Keuntungan menggunakan IntelliJ Profiler
Dapat mengukur durasi eksekusi dari suatu metode, frekuensi pemanggilannya, serta sumber daya yang dipakai. Dengan data tersebut dapat dilacak permasalahan atau bagian kode yang perlu dioptimalkan.

## 6. Solusi ketika Hasil Tidak Konsitenan antara IntelliJ Profiler dan JMeter
Pertama memastikan konfigurasi pengujian sama, kemudian mematikan metrik yang dianalisa tidak bermasalah. Lebih dari itu bisa dinalisa lewat menambahkan think time pada JMeter atau IntelliJ Profiler, yakni  waktu yang dihabiskan oleh pengguna antara dua tindakan dalam suatu aplikasi, untuk pencerminan behaviour yang lebih akurat.

## 7. Strategi implementasi Optimasi
Saya perlu menemukan bagian kode yang memakan waktu atau sumber daya berlebih. Caranya dengan fokus pada metode yang sering dipanggil dan alokasi memori yang tinggi. Kemudian memperbaiki kode yang kompleks atau tidak efisien dengan memilih algoritma yang lebih cepat dan hemat memori. Setelah dilakukan perubahan, perlu dilakukan pengujian kinerja ulang untuk memastikan fungsionalitas tetap terjaga. Hal ini perlu dimonitor ditiap perubahan yang dilakukan.
