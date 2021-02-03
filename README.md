# Data Sekolah Negeri Indonesia APi 
---

Dibuat menggunakan :

<img align="left" alt="Node.js" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" />


---
---
## Semua data saya ambil dari data referensi pendidikan [link](https://referensi.data.kemdikbud.go.id/)
---
Status : On Progress

## Dokumentasi

### Base URL : https://datasekolahapi.herokuapp.com/api/data
> Saat ini baru tersedia data sekolah sd negeri di dua daerah provinsi jakarta, yaitu kepulauan seribu, cilandak dan jagakarsa.
---

### Mendapatkan data berdasarkan jenjang : https://datasekolahapi.herokuapp.com/api/data/jenjanghurufkecil

### Contoh mendapatkan semua data berdasarkan jenjang
```Javascript
fetch('https://datasekolahapi.herokuapp.com/api/data/sd')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(err => console.log(err));
```
---
### Mendapatkan data berdasarkan jenjang dan provinsi : https://datasekolahapi.herokuapp.com/api/data/jenjanghurufkecil/namaprovinsihurufkecil

### Contoh mendapatkan semua data berdasarkan jenjang dan daerah
```Javascript
fetch('https://datasekolahapi.herokuapp.com/api/data/sd/jakarta')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(err => console.log(err));
```
---
### Mendapatkan data berdasarkan jenjang, provinsi dan kecamatan / kabupaten : https://datasekolahapi.herokuapp.com/api/data/jenjanghurufkecil/namaprovinsihurufkecil/namakecamatanhurufkecil

### Contoh mendapatkan semua data berdasarkan jenjang, provinsi dan kecamatan / kabupaten
```Javascript
fetch('https://datasekolahapi.herokuapp.com/api/data/sd/jakarta/cilandak')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(err => console.log(err));
```
---
### Contoh mendapatkan semua data di Javascript
```Javascript
fetch('https://datasekolahapi.herokuapp.com/api/data')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(err => console.error(err));
```
> Untuk mencoba nya anda bisa menggunakan browser Microsoft Edge, Firefox dll, untuk google chrome saat ini ada yang bisa dan ada kena cors.

Terimakasihh.
