# Praktikum 3 web: Membuat List, Table dan Form

## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
</body>
</html>
```

hasli output 

![image](https://github.com/Agussetiaa/praktikumweb3/assets/115542822/8f915bb8-bd6d-48c1-bad7-7d911f0e84d9)


Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
```
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
      <li>Pemrograman Web</li>
      <li>Sistem Informasi</li>
      <li>Basis Data 2</li>
    </ol>
</section>
```

Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada
section unordered-list, seperti berikut.
```
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
      <li>Jaringan Komputer</li>
      <li>Struktur Data</li>
      <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```

hasil output 


![image](https://github.com/Agussetiaa/praktikumweb3/assets/115542822/0bcfcf68-99bc-45ce-a77a-990745aff56d)


Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
```
<section id="unorder-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Industi</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntasi</dd>
            <dd>Manajemen</dd>
            <dd>BisnIS Digital</dd>
        </dl>
    </section>
```

hasil output


![image](https://github.com/Agussetiaa/praktikumweb3/assets/115542822/4026bdf7-b6b0-468e-9ca7-149504251ecb)


Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML lanjutan</title>
</head>
<body>
  <header>
    <h1>Membuat table</h1>
  </header>
</body>
</html>
```

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
<table border="1" cellpadding="4" cellspacing="3">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Teknik</td>
      <td>Teknik Informatika</td>
  </tr>
  <tr>
      <td>2.</td>
      <td>Teknik</td>
      <td>Teknik Industri</td>
  </tr>
  <tr>
      <td>3.</td>
      <td>Teknik</td>
      <td>Teknik Lingkungan</td>
  </tr>
  </tbody>
</table>
```

![image](https://github.com/Agussetiaa/praktikumweb3/assets/115542822/b964195b-c462-480b-a5de-c97b1ec41465)

Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan
cellspacing pada tag table.

```
<table border="1" cellpadding="4" cellspacing="3">
```



