### Grep For Bug Bountys
Grep singkatan dari golbal regular Exppression

Commands | Keterangan
---------|-----------
cat files.txt | grep "string" >  mengambil string.
cat files.txt | grep "string" --color >  mengambil string dan underline dengan warna.


### Sed For Bug Bountys

1. echo hi shifa | sed 's/hi/bye' > mengganti kata hi menjadi bye ; s = awal dan g=akhir.
2. cat linepattern.txt | sed '/saba/s/hi/bye/' > Mengganti fil yang memiliki awalan hi menjadi bye dan semua yang mengandung kalimat saba. 
3. cat linepattern.txt | sed 's/hi/bye/;s/hello/jello/g' > string hi diubah menjadi bye dan string hello dibuah menjadi jello.
4. cat urls.txt | sed 's/^/https:\/\//' > Menambahkan https:// dibelakang nama url.
5. 

