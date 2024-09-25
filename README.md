# 09011182328008_TugasPraktikum5SistemOperasi_ArsenyiusMastryNaibaho

## 1. Eksekusi seluruh profile yang ada :
### a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : echo “Profile dari /etc/profile”
![Screenshot from 2024-09-24 20-18-09](https://github.com/user-attachments/assets/12e2b445-3a21-438a-88be-754565d9fd0e)
![Screenshot from 2024-09-24 20-13-03](https://github.com/user-attachments/assets/5b7409c5-6744-4807-8380-f922b2f75687)


### b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu: /home/stD02001/.bash_profile, /home/. stD02001/.bash_login, /home/mahasiswa/.profile, /home/mahasiswa/.bashrc .Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : echo “Profile dari .bash_profile” Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.
![Screenshot from 2024-09-24 20-39-59](https://github.com/user-attachments/assets/e0c7223d-9cfb-4061-9d28-c2d90dd24366)
![Screenshot from 2024-09-24 20-37-41](https://github.com/user-attachments/assets/305ec04b-9d39-4325-b43b-7b9b40018095)
![Screenshot from 2024-09-24 20-46-25](https://github.com/user-attachments/assets/f860a5f8-3793-46bf-8f06-019262d9aebe)
![Screenshot from 2024-09-24 20-43-37](https://github.com/user-attachments/assets/f3e8633c-633a-4621-9d5a-80b2e99e8538)
![Screenshot from 2024-09-24 20-52-39](https://github.com/user-attachments/assets/50c8f724-8766-491a-8c59-8859840e4c14)
![Screenshot from 2024-09-24 20-52-03](https://github.com/user-attachments/assets/673a4f2c-3e11-477e-8c0f-3bdcb83c061d)
![Screenshot from 2024-09-24 20-54-35](https://github.com/user-attachments/assets/ce6078d9-9168-4d6f-985c-8ff0a3ad6114)
![Screenshot from 2024-09-24 20-56-03](https://github.com/user-attachments/assets/ea3957ed-a40b-453e-b21f-9abaf6094082)

### c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: $ su mahasiswa, $ exit kemudian gunakan opsi – sebagai berikut : $ su – mahasiswa $ exit Jelaskan perbedaan kedua utilitas tersebut.
![Screenshot from 2024-09-24 21-10-55](https://github.com/user-attachments/assets/3f1d96e3-510d-4ed4-8bf6-8dea803c1506)
![Screenshot from 2024-09-24 21-12-49](https://github.com/user-attachments/assets/ee1c676f-e066-4080-8893-d65f1e7b2488)

## 2. Prompt String (PS)
### a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell
![Screenshot from 2024-09-24 21-26-22](https://github.com/user-attachments/assets/b010f9e8-eeb5-48d6-b558-78a38e7ceae1)
![Screenshot from 2024-09-24 21-26-01](https://github.com/user-attachments/assets/98d3809e-9f99-4477-baa5-660ffcce9748)
![Screenshot from 2024-09-24 21-31-18](https://github.com/user-attachments/assets/cd1b3304-bd03-45ef-b220-31143f1a52a6)

### b. Eksperimen hasil PS1 :
![Screenshot from 2024-09-24 22-13-01](https://github.com/user-attachments/assets/6ae1682d-18a2-4bd0-85a1-7956cbecb3ae)

## 3. Logout
### Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout .Echo “Terima kasih atas sesi yang diberikan”  Sleep 5  clear
![Screenshot from 2024-09-24 22-31-11](https://github.com/user-attachments/assets/01bce0a0-c59c-4822-bc9c-a0471f9d3c43)
![Screenshot from 2024-09-24 22-24-10](https://github.com/user-attachments/assets/c6cb2746-6a46-4b23-9e35-2e7224957336)

## 4. Bash script
### a. uat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing : 
```
p1.sh 
#! /bin/bash
echo “Program p1”
ls –l
```
![Screenshot from 2024-09-24 22-46-48](https://github.com/user-attachments/assets/a361e249-a70b-44a4-bcde-f337cddb36f2)
![Screenshot from 2024-09-24 22-46-32](https://github.com/user-attachments/assets/c73227a8-172b-426f-b7d3-9b1ca4f86809)

```
p2.sh
#! /bin/bash
echo “Program p2”
who
```
![Screenshot from 2024-09-24 22-50-08](https://github.com/user-attachments/assets/1428eca4-fea2-4f3b-81e7-3881730957bd)
![Screenshot from 2024-09-24 22-49-32](https://github.com/user-attachments/assets/919b3ff8-b327-4962-a299-c7d50930e8c2)

```
p3.sh
#! /bin/bash
echo “Program p3”
ps x
```
![Screenshot from 2024-09-24 22-52-00](https://github.com/user-attachments/assets/596ca918-9785-4a97-9a56-220856ab8b26)
![Screenshot from 2024-09-24 22-52-53](https://github.com/user-attachments/assets/bee47bf7-4ddf-47fa-b249-e75abdcd5889)

### b. jalankan script tersebut sebagai berikut :
![Screenshot from 2024-09-24 22-56-59](https://github.com/user-attachments/assets/7a6a0e6f-0ed6-4833-b02c-f713554a4743)

$ ./p1.sh ; ./p3.sh ; ./p2.sh
![Screenshot from 2024-09-24 23-05-49](https://github.com/user-attachments/assets/df3b8864-987e-4fe1-9907-52b4fe98db01)
![Screenshot from 2024-09-24 23-07-20](https://github.com/user-attachments/assets/994b80a2-57ce-4c21-b635-29a2d9911ed2)

$ ./p1.sh &
![Screenshot from 2024-09-24 23-08-33](https://github.com/user-attachments/assets/3784662e-2b51-4c5e-87e3-8b8af8e78929)

$ ./p1.sh $ ./p2.sh & ./p3.sh &
![Screenshot from 2024-09-24 23-10-42](https://github.com/user-attachments/assets/2c10ad17-d102-42e0-81de-d2a889593583)

$ ( ./p1.sh ; ./p3.sh ) &
![Screenshot from 2024-09-24 23-15-11](https://github.com/user-attachments/assets/0e47b0a0-afcc-4e78-96f8-cd72b5abe326)

## 5. Jobs
### a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
```
#!/bin/bash
while [ true ]
do
date >> hasil
sleep 10
done
```
![Screenshot from 2024-09-25 07-53-41](https://github.com/user-attachments/assets/e67bc67d-6ae4-45b7-89db-877bbb891108)
![Screenshot from 2024-09-25 07-51-06](https://github.com/user-attachments/assets/684a7d9d-7e06-42c8-b4e4-042077e19066)
![Screenshot from 2024-09-25 07-56-47](https://github.com/user-attachments/assets/12e20bc8-c2dc-4f0e-835e-7e0d48701784)

### b. jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :
```
$ jobs
$ find / -print > files 2>/dev/null &
$ jobs
```
![Screenshot from 2024-09-25 08-01-09](https://github.com/user-attachments/assets/b49812ad-6e8f-4d94-8802-67107db72ccc)
![Screenshot from 2024-09-25 08-07-05](https://github.com/user-attachments/assets/0fd641d7-5302-46ce-abb4-2f1bd4e2fa7d)

### c. jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background
```
$ fg %1
$ bg
```
![Screenshot from 2024-09-25 08-10-52](https://github.com/user-attachments/assets/5eb7a9b5-8da6-41a0-9f08-668d56828d71)
![Screenshot from 2024-09-25 08-16-40](https://github.com/user-attachments/assets/d8a0e60a-4c7b-41a1-80af-942762ccb908)

### stop program background dengan utilitas kill
```
$ ps x
$ kill [Nomor PID]
```
![Screenshot from 2024-09-25 08-30-04](https://github.com/user-attachments/assets/c965ca64-a9e2-4faa-92e3-0a783c90de6f)
![Screenshot from 2024-09-25 08-30-32](https://github.com/user-attachments/assets/617a2622-adc4-4311-a32f-a6339d32bde0)
![Screenshot from 2024-09-25 08-31-02](https://github.com/user-attachments/assets/1e6f9ac5-f80d-4d58-b11b-4bce357e4440)
![Screenshot from 2024-09-25 08-31-24](https://github.com/user-attachments/assets/0199807d-44dc-4ca8-bd8e-c1e01dd708df)


## 6. History
### a. Ganti nilai HISTSIZE dari 1000 menjadi 20
```
$ HISTSIZE=20
$ h
```
![Screenshot from 2024-09-25 08-37-56](https://github.com/user-attachments/assets/09d66ab0-d7c0-45d6-b2bc-901dfa5cb026)

### b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan
$ !-5
![Screenshot from 2024-09-25 08-40-21](https://github.com/user-attachments/assets/62e9a59a-9c80-4988-91a5-3ab3e4a79e62)

### c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer
$ !!
![Screenshot from 2024-09-25 08-44-25](https://github.com/user-attachments/assets/93208fc1-e3ea-4034-a5f3-6156ef00997a)

### d. Ulangi instruksi pada history bufer nomor 150
$ !150
![Screenshot from 2024-09-25 08-45-54](https://github.com/user-attachments/assets/50801963-8571-4dc4-b74b-f165e2ca4b93)

### e. ulangi instruksi dengan prefix “ls”
$ !ls
![Screenshot from 2024-09-25 08-47-01](https://github.com/user-attachments/assets/bc658028-addf-4d55-810a-a9dba62c6bc8)
