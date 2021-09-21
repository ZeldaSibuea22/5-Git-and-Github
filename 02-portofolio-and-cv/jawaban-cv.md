# 02-portofolio-and-cv #

1. membuat sebuah folder kosong dengan namamu sendiri <br>
`mkdir zelda-sibuea`

2. membuat sebuah file dengan nama ```README.md```, isi file tersebut dengan kalimat ```"Halo perkenalkan aku halaman utama"``` <br>
 `touch Readme.md`
 
3. insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan ```commit``` dengan pesan ```"Inisialisasi Git Repository"``` <br>
  ```git init``` <br>
  ```git add README.md``` <br>
  ```git commit -m "Inisialisasi Git Repository"``` <br>
 4. buat ```branch``` baru dengan nama ```cv```, hal ini berguna agar histori kita tidak tercampur <br>
```git branch cv```

5. pindah ```branch``` kedalam ```cv```, kemudian buat file dengan nama ```cv.txt``` dan isi file tersebut dengan kalimat: ```"Ini adalah file CV"``` <br>
```git checkout cv``` <br>
```touch cv.txt```

6. kemudian dokumentasikan menggunakan commit dengan pesan : ```"Inisialisasi CV"``` <br>
`git add .`
`git commit -m "inisialisasi cv"`

7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan ```commit``` <br>
```
echo "Perusahaan 1" >> cv.txt
git add .
git commit -m "perusahaan 1"

echo "Perusahaan 2" >> cv.txt
git add .
git commit -m "perusahaan 2"

echo "Perusahaan 2" >> cv.txt
git add .
git commit -m "perusahaan 3" 

```

8. kembali ke branch ```master``` <br>
```git checkout master```

9. ubah file ```README.md``` menjadi <br>
```
Halo perkenalkan aku halaman utama

Ini adalah update pertama pada branch master
``` 

```echo "Ini adalah update pertama pada branch master" >> README.md```


10. jangan lupa untuk mendokumentasikannya menggunakan commit dengan pesan
     "update master pertama"
    `git add .`
   `git commit -m "update master pertama"`

11. gabungkan ```branch cv``` kedalam ```branch master``` menggunakan perintah ```git merge``` <br>
```git merge cv```

11. unggah Git Repository tersebut kedalam GitHub <br>

```git remote add origin https://github.com/ZeldaSibuea22/5-Git-and-Github.git```
     ```git push origin master```

# Note
```git log --graph``` <br>
<img width="527" alt="Capture" src="https://user-images.githubusercontent.com/73489643/134215656-b2b568ba-2cdb-420c-aba4-9fccc4a8d465.PNG">



