# Data Sekolah Negeri Indonesia APi 
---

## Dibuat menggunakan :

[![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)

  Fast, unopinionated, minimalist web framework for [node](http://nodejs.org).

  [![NPM Version][npm-image]][npm-url]
  [![NPM Downloads][downloads-image]][downloads-url]
  [![Linux Build][travis-image]][travis-url]
  [![Windows Build][appveyor-image]][appveyor-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

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

[npm-image]: https://img.shields.io/npm/v/express.svg
[npm-url]: https://npmjs.org/package/express
[downloads-image]: https://img.shields.io/npm/dm/express.svg
[downloads-url]: https://npmcharts.com/compare/express?minimal=true
[travis-image]: https://img.shields.io/travis/expressjs/express/master.svg?label=linux
[travis-url]: https://travis-ci.org/expressjs/express
[appveyor-image]: https://img.shields.io/appveyor/ci/dougwilson/express/master.svg?label=windows
[appveyor-url]: https://ci.appveyor.com/project/dougwilson/express
[coveralls-image]: https://img.shields.io/coveralls/expressjs/express/master.svg
[coveralls-url]: https://coveralls.io/r/expressjs/express?branch=master

Terimakasihh.
