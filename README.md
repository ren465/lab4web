# lab4web
***
# Membuat Dokumen HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box Element</title>
</head>
<body>
  <header>
      <h1>Box Element</h1>
  </header>
</body>
</html>
# Membuat Box Element
***

<section>
  <div class="div1">Div 1</div>
  <div class="div2">Div 2</div>
  <div class="div3">Div 3</div>
</section>

# CSS Float Property
***
<style>
  div {
      float:left;
      padding: 10px;
}
.div1 {
  background: red;
}
.div2 {
  background: yellow;
}
.div3 {
  background: green;
}
</style>
***

![1](https://user-images.githubusercontent.com/81818422/115855536-8bd37a80-a455-11eb-922d-d78131a35f64.png)

# Mengatur Clearflik Element
***
<section>
  <div class="div1">Div 1</div>
  <div class="div2">Div 2</div>
  <div class="div3">Div 3</div>
  <div class="div4">Div 4</div>
</section>
***
Kemudian atur property clear pada CSS, seperti berikut.
***
.div4 {
  background-color: blue;
  clear: left;
  float: none;
}
****

![2](https://user-images.githubusercontent.com/81818422/115855987-13b98480-a456-11eb-81b6-1995ee79f8bb.png)

# Membuat Layout Sederhana

***
<!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
    
    </div>
</body>
</html>

***

![3](https://user-images.githubusercontent.com/81818422/115857082-75c6b980-a457-11eb-9eed-bf38530a4bc0.png)

Kemudian tambahkan kode CSS untuk membuat layoutnya

/* import google font */
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400
;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0
,300;0,700;1,300&display=swap');
/* Reset CSS */
* {
margin: 0;
padding: 0;
}
body {
line-height:1;
font-size:100%;
font-family:'Open Sans', sans-serif;
color:#5a5a5a;
}
#container {
width: 980px;
margin: 0 auto;
box-shadow: 0 0 1em #cccccc;
}
/* header */
header {
padding: 20px;
}
header h1 {
margin: 20px 10px;
color: #b5b5b5;
}

# Membuat Navigasi
* navigasi */ nav { display: block; background-color: #1f5faa; } nav a { padding: 15px 30px; display: inline-block; color: #ffffff; font-size: 14px; text-decoration: none; font-weight: bold; } nav a.active, nav a:hover { background-color: #2b83ea; }

# Hello Word

***

![4](https://user-images.githubusercontent.com/81818422/115857846-6ac05900-a458-11eb-8c72-8edb6f10b785.png)

# Mengatur Layout Main dan Sidebar
Selanjutnya mengatur main content dan sidebar, tambahkan CSS float.
***
/* main content */
#wrapper {
margin: 0;
}
#main {
float: left;
width: 640px;
padding: 20px;
}
/* sidebar area */
#sidebar {
float: left;
width: 260px;
padding: 20px;
}
# Membuat Sidebar Widget
Kemudian selanjutnya menambahkan element lain dalam sidebar.
***
<aside id="sidebar">
<div class="widget-box">
<h3 class="title">Widget Header</h3>
<ul>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
</ul>
</div>
<div class="widget-box">
<h3 class="title">Widget Text</h3>
<p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
pharetra est nunc, nec pretium nunc pretium ac.</p>
</div>
</aside>
* Kemudian tambahkan CSS.
/* widget */
.widget-box {
border:1px solid #eee;
margin-bottom:20px;
}
.widget-box .title {
padding:10px 16px;
background-color:#428bca;
color:#fff;
}
.widget-box ul {
list-style-type:none;
}
.widget-box li {
border-bottom:1px solid #eee;
}
.widget-box li a {
padding:10px 16px;
color:#333;
display:block;
text-decoration:none;
}
.widget-box li:hover a {
background-color:#eee;
}
.widget-box p {
padding:15px;
line-height:25px;
}
***
![5](https://user-images.githubusercontent.com/81818422/115858353-081b8d00-a459-11eb-8931-6b0652d56d65.png)

# Mengatur Footer
* Selanjutnya mengatur tampilan footer. Tambahkan CSS untuk footer.
* /* footer */
footer {
clear:both;
background-color:#1d1d1d;
padding:20px;
color:#eee;
}
***

![6](https://user-images.githubusercontent.com/81818422/115858576-5466cd00-a459-11eb-87a8-8816e01a90ef.png)


# Menambahkan Elemen lainnya pada Main Content
<section id="main">
<div class="row">
<div class="box">
<img src="https://dummyimage.com/120/db7d25/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
<div class="box">
<img src="https://dummyimage.com/120/3e73e6/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
<div class="box">
<img src="https://dummyimage.com/120/71e6d4/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
</div>
</section>
* Kemudian tambahkan CSS.

/* box */
.box {
display:block;
float:left;
width:33.333333%;
box-sizing:border-box;
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
padding:0 10px;
text-align:center;
}
.box h3 {
margin: 15px 0;
}
.box p {
line-height: 20px;
font-size: 14px;
margin-bottom: 15px;
}
box img {
border: 0;
vertical-align: middle;
}
.image-circle {
border-radius: 50%;
}
.row {
margin: 0 -10px;
box-sizing: border-box;
-moz-box-sizing: border-box;
-webkit-box-sizing: border-box;
}
.row:after, .row:before,
.entry:after, .entry:before {
content:'';
display:table;
}
.row:after,
.entry:after {
clear:both;
}
***
![7](https://user-images.githubusercontent.com/81818422/115858937-bd4e4500-a459-11eb-91de-9101c5473387.png)

# Menambahkan Content Artikel
<hr class="divider" />
<article class="entry">
<h2>First featurette heading.</h2>
<img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
</article>
<hr class="divider" />
<article class="entry">
<h2>First featurette heading.</h2>
<img src="https://dummyimage.com/150/7b8a70/fff.png" alt=""
class="right-img">
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
</article>
* Kemudian tambahkan CSS.

.divider {
border:0;
border-top:1px solid #eeeeee;
margin:40px 0;
}
/* entry */
.entry {
margin: 15px 0;
}
.entry h2 {
margin-bottom: 20px;
}
.entry p {
line-height: 25px;
}
.entry img {
float: left;
border-radius: 5px;
margin-right: 15px;
}
.entry .right-img {
float: right;
}
***
![8](https://user-images.githubusercontent.com/81818422/115859246-19b16480-a45a-11eb-809e-583ac82096af.png)

# Pertanyaan dan Tugas
* 1. Tambahkan Layout untuk menu About
=> buat single layout yang berisi deskripsi, portfolio, dll
2. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll
# Jawaban 1
![9](https://user-images.githubusercontent.com/81818422/115864246-d0b0de80-a460-11eb-9328-281fd9575c78.png)
# Jawaban 2
![10](https://user-images.githubusercontent.com/81818422/115865479-934d5080-a462-11eb-84d4-41a8b54b8a6e.png)
