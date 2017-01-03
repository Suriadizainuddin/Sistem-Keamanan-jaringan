**Centos**

 <p align="center"> <img src="https://github.com/Suriadizainuddin/Sistem-Keamanan-jaringan/blob/master/img/images.jpg" width="400px"> </p>  
 
1. Jelaskan yang dimaksud dengan Centos
2. Sebutkan Kekurangan Centos
3. Sebutkan Kelebihan Centos
4. Cara install Centos

Penjelasan

1. CentOS adalah distribusi Linux yang mencoba untuk memberikan gratis, kelas enterprise, komunitas yang didukung platform komputasi fungsional kompatibel dengan sumber hulu, Red Hat Enterprise Linux (RHEL). Pada bulan Januari 2014, CentOS mengumumkan resmi bergabung dengan Red Hat sementara tinggal independen dari RHEL, di bawah CentOS yang mengatur dewan baru.
2. Kekurangan CentOS

1. Tergantung pada distro Red Hat. Karena itu CentOS selalu keluar setelah Red Hat.
2. Kata &quot;Enterprise&quot; membuat pemula takut dan memilih Fedora.
3. Penampilan website CentOS yang kurang menarik (CentOS Indonesia sedang mengupayakan untuk mengupdate website CentOS.org agar tampil menarik).
4. Kurangnya dokumentasi mengenai CentOS secara khusus.

1. Kelebihan CentOS

1. CentOS sangat kompatibel dengan Red Hat.
2. Merupakan OS Freeware yang sangat handal untuk skala Enterpise.
3. Merupakan satu-satunya OS Freeware yang didukung resmi oleh CPanel.
4. CentOS kompatibel dengan RHEL sehingga drivers RHEL dapat dipakai oleh CentOS.

1. Instalasi dari Source

Menyiapkan Snort dari kode sumber terdiri dari beberapa langkah: download kode, mengkonfigurasi, kompilasi kode dan terakhir menginstal itu. Pertama membuat folder download sementara untuk direktori home Anda dan kemudian bergerak ke dalamnya dengan perintah ini

mkdir ~/snort\_src
cd ~/snort\_src

Download paket terbaru sumber DAQ dari website Snort dengan perintah wget bawah, ganti nomor versi jika ada sumber yang lebih baru yang tersedia

wget https://www.snort.org/downloads/snort/daq-2.0.6.tar.gz

Download hanya akan memakan waktu beberapa detik, ekstrak setelah selesai kode sumber dan melompat ke dalam direktori baru dengan perintah berikut

tar -xvzf daq-2.0.6.tar.gz
cd daq-2.0.6

Jalankan script konfigurasi dengan default, kemudian gunakan membuat untuk mengkompilasi program dan kemudian akhirnya memasang DAQ

./configure
make
sudo make install

Dengan DAQ yang diinstal Anda bisa memulai dengan Snort, mengubah kembali ke folder download

cd ~/snort\_src

Kemudian download kode sumber Snort dengan wget, memeriksa nomor versi terbaru dari situs Snort dan menggantinya di perintah berikut jika diperlukan.

wget https://www.snort.org/downloads/snort/snort-2.9.8.0.tar.gz

Setelah download selesai, ekstrak sumber dan mengubah ke dalam direktori baru dengan perintah ini

tar -xvzf snort-2.9.8.0.tar.gz
cd snort-2.9.8.0

Kemudian mengkonfigurasi instalasi dengan modus Sourcefire diaktifkan, jalankan make dan make install.

./configure --enable-sourcefire
make
sudo make install

Penutup

Kesimpulan

        Meskipun Snort mampu lebih dari sekedar jaringan pemantauan, panduan ini menunjukkan bagaimana untuk mengkonfigurasi dan menjalankan Snort dalam mode NIDS dengan setup dasar yang nanti dapat memperluas.

Saran

Selanjutnya untuk mendalami materi Snort dengan membaca sumber-sumber yang tersedia di buku maupun internet , dan         melakukan praktikum mandiri.