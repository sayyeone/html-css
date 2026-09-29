# HTML CONTENT & TEXT

List knowledge
1. Heading
2. Paragraph
3. Text formating
4. Link
5. Image
6. List

## 1. HEADING
heading adalah teks yanng digunakan sebagai **judul atau subjudul** dalam halaman HTML.

- dalam heading menyediakan 6 level
```html
<h1>Heading 1</h1> -> paling utama
<h2>Heading 2</h2> -> subjudul
<h3>Heading 3</h3> -> sub-subjudul
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

- jadi lebih ke struktur bagaimana hierarki dari judulnya contoh:
```txt
BUKU: BELAJAR WEB
│
├── BAB 1: HTML
│   ├── 1.1 Element
│   └── 1.2 Attribute
│
└── BAB 2: CSS
    ├── 2.1 Selector
    └── 2.2 Flexbox
```

## 2. PARAGRAPH
element untuk membuat paragraf teks

- contoh
```html
<p>Hello, my name is Adisty</p>
```

## 3. TEXT FORMATTING
memberikan makna atau penekanan tertentu pada teks

```html
<strong>
<em>
<b>
<i>
<small>
<mark>
<ins>
<del>
```
- strong = memeberi makna bahwa teks tersebut penting
```html
<p>
    <strong>Warning:</strong> This action cannot be undone.
</p>
```

- em = memberikan penakanan (emphasis) pada teks / italic/miring
```html
<p>
    You <em>must</em> complete this form.
</p>
```

- b = membuat teks terlihat bold, tanpa memberikan makna bahwa teks tersebut penting
```html
<p>
    This is a <b>bold</b> word.
</p>
```

- i = menampilkan teks dalam bentuk italic
```html
<p>
    The term <i>frontend</i> is commonly used in web development.
</p>
```

## 4. LINK
membuat teks/elemen yg dapat mengarah ke halaman, file, atau URL lain ketika diklik

```html
<a href="https://github.com">Github</a>
```
- href = attribute, https = attribute value

### External link
link menuju website lain

```html
<a href="https://www.google.com">
    Google
</a>
```

### Internal link
untuk berpindah antarHalaman dalam website sendiri

- dari index.html bisa membuat
```html
<a href="about.html">
    About
</a> -> index.html -> about.html
```

### Link ke bagian tertentu dalam halaman
```html
<h2 id="projects">Projects</h2>

<a href="#projects">
    Go to Projects
</a>
```
