# DAY-01 HTML FUNDAMENTALS

HTML = HyperText Markup Language
- bahasa yang digunakan untuk menentukan struktur dan makna konten halaman web

## HTML Element
keseluruhan struktur yang terdiri dari 

*misalnya*
```html
<h1>My Profile</h1>
<p>Halo, aku Adis</p>
<button>Contact Me</button>
```
- h1 -> heading utama
- p -> paragraf
- button -> tombolnya

## Tag vs Element
Tag = bagian yg berada diantara tanda < >

```html
<h1> </h1>
```

Element = keseluruhan struktur
```html
<h1>Hello World</h1>
```

## Void Element
element yang tidak memiliki content dan closing tag
```html
<img>
<br>
<hr>
<input>
<meta>
<link>
```
contoh
```html
<img src="profile.jpg" alt="Profile">
```

## 2. Attribute
mengatur karakteristik ,konfigurasi, atau memberikan informasi tambahan tentang elemen tersebut

```html
<a href="https://example.com">Visit Website</a>
```
- href = sebuah attribute

**Contoh attribute yg digunakan**
- href = digunakanpada a untuk menentukan tujuan link
```html
<a href="https://google.com">Google</a>
```

- src = menentukan sumber file, misalnya gambar
```html
<img src="profile.jpg">
```

- alt = memberikan teks alternatif untuk gambar
```html
<img
    src="profile.jpg"
    alt="Foto profil Adis"
>
```

- id = memberikan identitas unik pada sebuah element, id akan digunakan untuk css / js
```html
<p id="description">
    Hello World
</p>
```

- class = memberikan nama class pada element
```html
<p class="description">
    Hello World
</p>
```
- satu element bisa memiliki banyak attribute

## 3. HTML Document
sebuah dokumen/file yang berisi struktur HTML untuk membangun satu halaman web
- biasanya file HTML memiliki ekstensi:
```txt
.html
```

## Struktur Dasar HTML Document
```html
<!DOCTYPE html>

<html>
<head>
    <title>My Website</title>
</head>

<body>

    <h1>Hello World</h1>

</body>
</html>
```

- !DOCTYPE html = memberi tahu browser bahwa dokumen menggunakan HTML modern
- html = root element dari sebuah dokumen HTML
- head = 
