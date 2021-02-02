# Data Sekolah Negeri Indonesia APi 
---

Dibuat menggunakan Express JS
---

Status : On Progress

## Dokumentasi

### Base URL : https://datasekolahapi.herokuapp.com/api/data
> Saat ini baru tersedia data sekolah sd negeri di dua daerah provinsi jakarta, yaitu kepulauan seribu dan cilandak
---

## Contoh Get data Javascript
```Javascript
fetch('https://datasekolahapi.herokuapp.com/api/data')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(err => console.error(err));
```
> Saya sudah tes melalui browser Microsoft Edge dan tidak ada masalah, saat ini hanya ada masalah cors saja di browser chrome, saya akan perbaiki :)

Terimakasihh.
