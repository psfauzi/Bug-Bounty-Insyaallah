### Grep For Bug Bountys
Grep singkatan dari golbal regular Exppression

Commands | Keterangan
---------|-----------
cat files.txt I grep "string"  | mengambil string.
cat files.txt I grep "string" --color  | mengambil string dan underline dengan warna.


### Sed For Bug Bountys

Commands | Keterangan
---------|-----------
echo hi shifa I sed 's/hi/bye'  | mengganti kata hi menjadi bye ; s = awal..
cat linepattern.txt I sed '/saba/s/hi/bye/'  | Mengganti fil yang memiliki awalan hi menjadi bye dan semua yang mengandung kalimat saba. 
cat linepattern.txt I sed 's/hi/bye/;s/hello/jello/g'  | string hi diubah menjadi bye dan string hello dibuah menjadi jello.
cat urls.txt I sed 's/^/https:\/\//'  | Menambahkan https:// dibelakang nama url.
cat urls.txt I sed 's/[a-z]//g' | Menghapus konten yang mengandung string a-z.    
cat urls.txt I sed 's/[0-9]//g' I sed 'y/abcdefghijklmnopqrstuvwxyz/ABCDEFGHIJKLMNOPQRSTYVWXYZ/'  | mengubah huruf abjad biasa menjadi huruf KAPITAL
at urls.txt I sed  -e 's/com/yahoo/' -e 's/in/go.id/' -e 's/[0-9]//g' | Gunakan -e untuk Multiple perintah satu baris sed


### Awk For Bug Bountys

Commands | Keterangan
---------|-----------
cat linepattern.txt I awk '{print $1}' | $1 = mengambil kata pertama dalam 1 baris kalimat.    
cat patter.txt I awk '/xyz/{print $2}' | /xyz/ = Hanya string xyz dibaris kata kedua dalam 1 baris kalimat.
cat urls.txt I awk '.' '{print $1}' | '.' = untuk menghilangkan data setelah tanda . exp.bounty.com menjadi bounty  
