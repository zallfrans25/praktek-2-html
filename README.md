# praktek-2-html

<!DOCTYPE html>
<html lang="en">
<head>
    <head>
        <!-- menyisipkan css eksternal -->
        <link rel="stylesheet" href="style_eksternal.css" type="text/css">
        </head>
    <title>CSS Dasar</title>
<style>
body {
font-family:'Open Sans', sans-serif;
}
header {
min-height: 80px;
border-bottom:1px solid #77CCEF;
}
h1 {
font-size: 24px;
color: #ffee00;
text-align: center;
padding: 20px 10px;
}
h1 i {
color:#09ff00;
}
</style>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>
    <body background="backgrnd.jpg"> </body>
<header>
<h1>CSS Internal dan <i>Inline CSS</i></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1Web.html">HTML Dasar</a>
<a href="https://ecampus.pelitabangsa.ac.id/pb/index.jsp">Ecampus</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
<h1 style="text-align:center; color:#ffee00;
">Hello World</h1>
<p style="text-align: center; color: #ccd8e4;"> Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
    Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
    dan CSS.</p>
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>
