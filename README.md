 # Lab4Web
 # Nama: Keysia nurhayati br panjaitan
 # Nim : 312410350
 # Kelas : TI.24.A4
            
 # membuat Box Element
             ```html
            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>Box Element</title>
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
                    .div4 {
                        background: blue;
                        clear: left;
                        float: none;
                    }
                </style>
            </head>
            <body>
                <header>
                    <h1>Box Element</h1>
                </header>
                <section>
                    <div class="div1">Div 1</div>
                    <div class="div2">Div 2</div>
                    <div class="div3">Div 3</div>
                    <div class="div4">Div 4 (Clearfix)</div>
                </section>
            </body>
            </html>

<img width="1920" height="1200" alt="Screenshot 2025-10-16 161317" src="https://github.com/user-attachments/assets/490d087c-0f55-4658-bb88-e8c486501e73" />
            
 # membuat layout sederhana
             <!DOCTYPE html>
            <html lang="en">
            <head>
              <meta charset="UTF-8">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <title>Artikel</title>
              <link rel="stylesheet" href="style.css">
            </head>
            <body>
              <div id="container">
                <header>
                  <h1>Layout Sederhana</h1>
                </header>
            
                <nav>
                  <a href="home.html">Home</a>
                  <a href="artikel.html" class="active">Artikel</a>
                  <a href="about.html">About</a>
                  <a href="kontak.html">Kontak</a>
                </nav>
            
                <section id="wrapper">
                  <section id="main">
                    <article class="entry">
                      <h2>Judul Artikel Pertama</h2>
                      <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
                      <p>
                        Ini adalah contoh artikel pertama. Kamu bisa menuliskan isi artikel atau berita di sini.
                        Artikel ini menggunakan elemen <code>&lt;article&gt;</code> yang termasuk bagian dari HTML5 semantic element.
                      </p>
                    </article>
            
                    <hr class="divider">
            
                    <article class="entry">
                      <h2>Judul Artikel Kedua</h2>
                      <img src="https://dummyimage.com/150/3e73e6/fff.png" alt="" class="right-img">
                      <p>
                        Ini adalah contoh artikel kedua. Kamu bisa menambahkan gambar dan teks sesuai kebutuhan.
                        Gambar bisa berada di kiri atau kanan sesuai kelas CSS yang digunakan.
                      </p>
                    </article>
                  </section>
            
                  <aside id="sidebar">
                    <div class="widget-box">
                      <h3 class="title">Artikel Lain</h3>
                      <ul>
                        <li><a href="#">Tips Desain Web</a></li>
                        <li><a href="#">Belajar CSS Layout</a></li>
                        <li><a href="#">Responsive Design</a></li>
                      </ul>
                    </div>
                  </aside>
                </section>
            
                <footer>
                  <p>&copy; 2025 - Universitas Pelita Bangsa</p>
                </footer>
              </div>
            </body>
            </html>
            
    <img width="1920" height="1200" alt="Screenshot 2025-10-16 161231" src="https://github.com/user-attachments/assets/0243ebfd-aa6a-45de-b6dd-539269d8a0bd" />
                    
           
