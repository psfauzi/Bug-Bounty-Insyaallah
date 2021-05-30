### Grep For Bug Bountys
Grep singkatan dari golbal regular Exppression

Commands | Keterangan
---------|-----------
1.cat files.txt I grep "string"  | mengambil string.
2.cat files.txt I grep "string" --color  | mengambil string dan underline dengan warna.


### Sed For Bug Bountys

Commands | Keterangan
---------|-----------
1.echo hi shifa I sed 's/hi/bye'  | mengganti kata hi menjadi bye ; s = awal..
2.cat linepattern.txt I sed '/saba/s/hi/bye/'  | Mengganti fil yang memiliki awalan hi menjadi bye dan semua yang mengandung kalimat saba. 
3.cat linepattern.txt I sed 's/hi/bye/;s/hello/jello/g'  | string hi diubah menjadi bye dan string hello dibuah menjadi jello.
4.cat urls.txt I sed 's/^/https:\/\//'  | Menambahkan https:// dibelakang nama url.
5.cat urls.txt I sed 's/[a-z]//g' | Menghapus konten yang mengandung string a-z.    
6.cat urls.txt I sed 's/[0-9]//g' I sed 'y/abcdefghijklmnopqrstuvwxyz/ABCDEFGHIJKLMNOPQRSTYVWXYZ/'  | mengubah huruf abjad biasa menjadi huruf KAPITAL
