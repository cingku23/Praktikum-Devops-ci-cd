# 📋 Laporan Praktikum Pertemuan 01
## DevOps Culture & Principles

---

## 👤 Identitas Mahasiswa

| Item | Keterangan |
|------|------------|
| **Nama** | ANDI NAIVA NOOR ARUUMANNEESHA |
| **NIM** | 105841122223 |
| **Kelas** | 5B |
| **Tanggal** | 2026-02-25 |

---

## 📚 Pemahaman DevOps

### Apa itu DevOps?

DevOps adalah pendekatan dalam pengembangan software yang menggabungkan tim development (pengembang) dan operations (operasional) agar dapat bekerja lebih terkoordinasi. Sebelumnya, kedua tim ini sering bekerja secara terpisah sehingga proses pembuatan dan deployment aplikasi menjadi lebih lama dan kadang menimbulkan kesalahpahaman. DevOps hadir untuk menyatukan proses tersebut melalui kolaborasi dan otomatisasi.

Dalam DevOps terdapat beberapa konsep penting seperti Continuous Integration (CI) dan Continuous Delivery/Deployment (CD). CI memungkinkan kode yang dibuat oleh developer langsung diuji secara otomatis setiap kali ada perubahan. Sedangkan CD membantu proses pengiriman aplikasi ke server agar lebih cepat dan konsisten. Selain itu, DevOps juga menggunakan tools seperti Docker untuk membuat aplikasi dapat dijalankan di berbagai lingkungan dengan konfigurasi yang sama.

Tujuan utama DevOps adalah mempercepat proses pengembangan aplikasi tanpa mengurangi kualitasnya. Dengan adanya otomatisasi, kesalahan dapat terdeteksi lebih awal dan proses deployment menjadi lebih stabil. Manfaat lainnya adalah meningkatkan kerja sama antar tim dan membuat proses pengembangan menjadi lebih efisien. Secara umum, DevOps membantu perusahaan menghasilkan software yang lebih cepat, stabil, dan sesuai kebutuhan pengguna.

### Mengapa DevOps Penting?

DevOps menjadi penting karena perkembangan teknologi yang sangat cepat membuat perusahaan harus mampu beradaptasi dengan perubahan. Saat ini, pengguna menginginkan aplikasi yang selalu diperbarui, bebas dari bug, dan memiliki performa yang baik. Jika proses pengembangan masih dilakukan secara manual dan terpisah, maka pembaruan aplikasi bisa memakan waktu lama dan berisiko terjadi kesalahan saat deployment.

Dengan DevOps, proses integrasi dan deployment dilakukan secara otomatis menggunakan CI/CD pipeline. Hal ini membuat setiap perubahan kode dapat langsung diuji dan dipastikan berjalan dengan baik sebelum digunakan oleh pengguna. Selain itu, penggunaan container seperti Docker membuat aplikasi lebih mudah dijalankan di berbagai lingkungan tanpa perbedaan konfigurasi.

Sebagai contoh, perusahaan yang memiliki aplikasi online dapat memperbarui fitur tanpa harus menghentikan layanan secara lama. Dengan monitoring yang baik, jika terjadi error maka tim dapat segera mengetahuinya dan memperbaikinya. Oleh karena itu, DevOps membantu perusahaan menjadi lebih cepat, efisien, dan mampu bersaing di industri software modern.

### Contoh Perusahaan yang Menerapkan DevOps

Salah satu contoh perusahaan yang berhasil menerapkan DevOps adalah Netflix. Netflix menggunakan otomatisasi dalam proses deployment sehingga dapat memperbarui sistem secara berkala tanpa mengganggu pengguna. Mereka juga menggunakan arsitektur berbasis layanan (microservices) agar sistem lebih fleksibel dan mudah dikembangkan.

Contoh lainnya adalah Amazon. Amazon menerapkan CI/CD untuk mempercepat proses rilis fitur baru. Dengan otomatisasi tersebut, Amazon dapat melakukan banyak deployment dalam satu hari dengan risiko kesalahan yang lebih kecil. Penerapan DevOps membantu Amazon menjaga stabilitas sistem sekaligus terus berinovasi.

Keberhasilan perusahaan-perusahaan tersebut menunjukkan bahwa DevOps sangat berperan dalam meningkatkan kualitas dan kecepatan pengembangan software.

---

## 🎯 Pemahaman Prinsip CALMS

C - Culture

Culture dalam DevOps berarti membangun budaya kerja yang kolaboratif antara tim development dan operations. Kedua tim tidak lagi bekerja terpisah, tetapi saling bekerja sama untuk mencapai tujuan yang sama. Budaya ini juga menekankan komunikasi terbuka dan saling percaya.

Contoh penerapan:
Developer dan tim operasi rutin melakukan meeting bersama untuk membahas update sistem dan perbaikan bug. Jika terjadi error saat deployment, tim tidak saling menyalahkan, tetapi mencari solusi bersama.

A - Automation

Automation berarti mengotomatisasi proses yang sebelumnya dilakukan secara manual, seperti testing, build, dan deployment. Dengan otomatisasi, proses menjadi lebih cepat, konsisten, dan mengurangi kesalahan manusia.

Contoh penerapan:
Menggunakan CI/CD pipeline untuk menjalankan testing otomatis setiap kali ada perubahan kode di GitHub. Selain itu, penggunaan Docker untuk menjalankan aplikasi dengan konfigurasi yang sama di berbagai lingkungan juga termasuk bentuk automation.

L - Lean

Lean berarti mengurangi pemborosan dan meningkatkan efisiensi dalam proses pengembangan software. Fokusnya adalah membuat proses lebih sederhana dan cepat tanpa langkah yang tidak perlu.

Contoh penerapan:
Melakukan deployment dalam skala kecil namun sering (small and frequent releases) agar jika terjadi kesalahan lebih mudah diperbaiki dibanding menunggu rilis besar.

M - Measurement

Measurement berarti mengukur performa sistem dan proses pengembangan agar dapat diketahui apa yang perlu diperbaiki. Pengukuran membantu tim dalam mengambil keputusan berdasarkan data.

Contoh penerapan:
Mengukur waktu deployment, jumlah bug, dan waktu perbaikan error (mean time to recovery). Data tersebut digunakan untuk meningkatkan kualitas sistem.

S - Sharing

Sharing berarti berbagi pengetahuan, pengalaman, dan informasi antar anggota tim agar semua memiliki pemahaman yang sama.

Contoh penerapan:
Tim melakukan dokumentasi proyek dan berbagi knowledge melalui diskusi rutin atau platform kolaborasi seperti GitHub dan Slack. Dengan berbagi informasi, tim dapat bekerja lebih efektif.

---

## 🔧 Setup Development Environment

### Versi Software

| Software | Versi |
|----------|-------|
| Git | git version 2.52.0.windows.1 |
| Docker | Docker version 29.2.1 |

### Konfigurasi Git

```
user.name=ANDI NAIVA NOOR ARRUUMANNEESHA
user.email=105841122223@student.unismuh.ac.id
```

### VS Code Extensions

1. Docker 
2. GitLens 
3. YAML 
4. Remote 

### GitHub Account

- Username: cingku23

---

## 📸 Screenshots

| No | Screenshot | Keterangan |
|----|------------|------------|
| 1 | ![Git Version](screenshots/01-git-version.png) | Output git --version |
| 2 | ![Git Config](screenshots/02-git-config.png) | Output git config --list |
| 3 | ![Docker Version](screenshots/03-docker-version.png) | Output docker --version |
| 4 | ![Docker Hello World](screenshots/04-docker-hello-world.png) | Output docker run hello-world |
| 5 | ![VS Code](screenshots/05-vscode-extensions.png) | VS Code dengan extensions |

---

## 💭 Refleksi Pribadi

### Harapan dari Praktikum Ini

Harapan saya dari praktikum DevOps ini adalah dapat memahami konsep DevOps tidak hanya secara teori, tetapi juga secara praktik. Saya ingin mengetahui bagaimana proses integrasi, testing, dan deployment dilakukan secara nyata menggunakan tools seperti GitHub, Docker, dan CI/CD pipeline. Selain itu, saya berharap praktikum ini dapat membantu saya memahami alur kerja pengembangan software modern yang digunakan di industri saat ini.

Saya juga berharap dapat lebih terbiasa menghadapi error dan memahami cara menyelesaikannya secara mandiri. Dengan mengikuti praktikum ini, saya ingin meningkatkan kemampuan problem solving serta lebih percaya diri dalam menggunakan teknologi berbasis cloud dan automation. Secara keseluruhan, saya berharap praktikum ini dapat menjadi bekal untuk menghadapi dunia kerja di bidang teknologi informasi.

### Skill yang Ingin Dikuasai

Di akhir semester, saya ingin menguasai dasar-dasar penggunaan Docker, memahami cara kerja container, serta mampu membuat dan menjalankan aplikasi di dalam container. Saya juga ingin memahami konsep dan implementasi CI/CD pipeline, mulai dari proses build, testing otomatis, hingga deployment.

Selain itu, saya ingin meningkatkan kemampuan menggunakan Git dan GitHub secara lebih terstruktur, termasuk dalam mengelola repository dan workflow kolaborasi. Saya juga ingin lebih memahami konsep cloud computing dan bagaimana aplikasi dapat dijalankan secara scalable.

Tidak hanya skill teknis, saya juga ingin melatih kemampuan troubleshooting ketika menghadapi error saat instalasi atau deployment.

### Tantangan yang Dihadapi

Tantangan yang saya hadapi saat mengerjakan praktikum ini adalah proses instalasi dan konfigurasi awal, terutama saat menjalankan Docker dan WSL. Beberapa error sempat muncul dan membuat saya bingung karena belum terbiasa dengan sistem berbasis command line. Selain itu, memahami konsep CI/CD dan alur kerja DevOps juga membutuhkan waktu karena cukup berbeda dengan cara pengembangan software tradisional.

Untuk mengatasi hal tersebut, saya mencoba mencari referensi dari dokumentasi resmi, membaca pesan error dengan lebih teliti, serta mencoba kembali langkah-langkah instalasi secara bertahap. Saya juga belajar untuk tidak langsung panik ketika muncul error, tetapi menganalisis penyebabnya terlebih dahulu.

Dari tantangan tersebut, saya belajar bahwa dalam DevOps ketelitian dan kesabaran sangat penting, terutama dalam proses konfigurasi dan troubleshooting.

---

## ✅ Checklist

- [x] Git terinstall dan terkonfigurasi dengan benar
- [x] Docker dapat menjalankan container hello-world
- [x] VS Code terinstall dengan semua extensions yang diminta
- [x] Laporan ditulis dengan bahasa yang baik dan benar
- [x] Semua screenshot jelas dan terbaca

---

*Laporan ini dibuat pada Rabu, 25 Februari 2026*
