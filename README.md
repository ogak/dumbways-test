# Test Technical Online Bootcamp DumbWays.id DEVOPS ENGINEER
1. OS yang digunakan: Window 10
2. Sumber artikel
   - https://www.redhat.com/en/topics/devops/what-is-ci-cd (no.2)
   - https://vegibit.com/creating-databases-and-tables-in-mysql/ (no.3)
   - https://phoenixnap.com/kb/grep-command-linux-unix-examples (no. 4)
   - https://hibbard.eu/install-ubuntu-virtual-box/ (no.5)
   - https://silicophilic.com/virtualbox-running-slow/ (no.5)


**Jawaban soal test DevOps Engineer Dumbways**
1. DevOps adalah budaya kolaborasi antara developer dan operation yang melahirkan serangkaian praktik yang mempercepat proses development dan operasi secara otomatis, kontinyu dan terintegrasi.
![01.jpg](images/01.jpg)

2. CI/CD adalah metode delivery apps, dimana CI adalah dimana source code developer dilakukan build, unit test dan integrasi, CD adalah continuous delivery dan continuous deployment artinya code yang telah terintegrasi otomatis masuk ke repository dan deploy ke production environment.\
![02.jpg](images/02.jpg)

3. blum dikerjakan


4. Grep singkatan dari Global Regular Expression Print, adalah command-line tool yang digunakan untuk mencari string dalam sebuah file, keyword yang cocok akan ditampilkan. Perintah grep berguna saat mencari string atau kata dalam sebuah log file.\
Contoh:
  `grep -i 'error' test/file1`
  hasil `error`
  `error.text`
  `error.data` 
    - 'error' adalah string atau kata yang akan dicari
    - test adalah lokasi foldernya
    - file1 adalah filenya yang akan dicari kata 'error' di dalamnya, hasilnya menampilkan semua yang mengandung kata error

5. 1. Install kemudian buka/launch VirtualBox
   2. Klik Machine -> New
   3. Beri nama pada virtual machine dan pilih OS yang digunakan, misal type: linux, version: ubuntu (64-bit), Next
   4. Pilih ukuran memory misal 3096 Mb, klik Next
   5. Pada pilihan Hard disk pilih Create virtual hardisk now, Next
   6. Berikutnya Pilih type Hard disk misal VDI (VirtualBox Disk Image), Next
   7. Pilih Storage on physical hard disk misal dynamically allocated
   8. File location and size pilih 10 Gb, Klik Create
   9. Kemudian lakukan konfigurasi sesuai kebutuhan melalui Settings
   10. Selanjutnya memasukkan live cd ubuntu-server yang telah di download
   11. Klik settings -> Storage -> Controller IDE klik empty -> Klik icon virtual optic disk -> pilih lokasi tempat penyimpanan ubuntu-server
   12. Klik start untuk memulai virtual machine
   13. Proses selanjutnya installasi OS ubuntu pada virtual machine.
   
[![05-video](http://img.youtube.com/vi/TW9N3elJ4ks/1.jpg)](http://www.youtube.com/watch?v=TW9N3elJ4ks)
