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
                     
# halaman home            
<img width="1920" height="1200" alt="Screenshot 2025-10-16 161231" src="https://github.com/user-attachments/assets/0243ebfd-aa6a-45de-b6dd-539269d8a0bd" />
         
# halaman artikel 
<img width="1920" height="1200" alt="Screenshot 2025-10-16 161027" src="https://github.com/user-attachments/assets/1e54f346-0d53-4cab-a422-d18219bf3a46" />
         
# kode css style
         
                     /* import google font */ 
                     @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap'); 
                     @import url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap'); 
                     
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
                     
                     /* navigasi */ 
                     nav { 
                         display: block; 
                         background-color: #1f5faa; 
                     } 
                     
                     nav a { 
                         padding: 15px 30px; 
                         display: inline-block; 
                         color: #ffffff; 
                         font-size: 14px; 
                         text-decoration: none; 
                         font-weight: bold; 
                     } 
                     
                     nav a.active, 
                     nav a:hover { 
                         background-color: #2b83ea; 
                     } 
                     
                     /* Hero Panel */ 
                     #hero { 
                         background-color: #e4e4e5; 
                         padding: 50px 20px; 
                         margin-bottom: 20px; 
                     } 
                     
                     #hero h1 { 
                         margin-bottom: 20px; 
                         font-size: 35px; 
                     } 
                     
                     #hero p { 
                         margin-bottom: 20px; 
                         font-size: 18px; 
                         line-height: 25px; 
                     } 
                     
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
                     
                     /* widget */ 
                     .widget-box { 
                         border:1px solid #eee; 
                         margin-bottom:20px; 
                     } 
                     
                     .widget-box  .title { 
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
                     
                     /* footer */ 
                     footer { 
                         clear:both; 
                         background-color:#1d1d1d; 
                         padding:20px; 
                         color:#eee; 
                     } 
                     
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
         # menambahkan layout about
         
                  <!DOCTYPE html>
                  <html lang="en">
                  <head> 
                      <meta charset="UTF-8">
                      <meta name="viewport" content="width=device-width, initial-scale=1.0">
                      <title>Tentang Kami</title>
                      <link rel="stylesheet" href="style.css">
                  </head>
                  <body>
                      <div id="container">
                          <header>
                              <h1>Tentang Kami</h1>
                          </header>
                  
                          <nav>
                              <a href="home.html">Home</a>
                              <a href="about.html" class="active">About</a>
                              <a href="artikel.html">Artikel</a>
                              <a href="kontak.html">Kontak</a>
                          </nav>
                  
                          <section id="main">
                              <h2>Deskripsi</h2>
                              <p>Website ini dibuat sebagai latihan dasar layout menggunakan HTML5 dan CSS Float.</p>
                  
                              <h2>Portfolio</h2>
                              <ul>
                                  <li>Project 1 - Desain Web</li>
                                  <li>Project 2 - Sistem Informasi Penjualan</li>
                                  <li>Project 3 - Aplikasi kalkulator</li>
                              </ul>
                          </section>
                  
                          <footer>
                              <p>&copy; 2025 - Universitas Pelita Bangsa</p>
                          </footer>
                      </div>
                  </body>
                  </html> 
         
<img width="1920" height="1200" alt="Screenshot 2025-10-16 160923" src="https://github.com/user-attachments/assets/ea05f05f-bfba-4f69-be95-1abf4dee6790" />
         
# layout kontak
         
         <!DOCTYPE html>
         <html lang="en">
         <head>
             <meta charset="UTF-8">
             <meta name="viewport" content="width=device-width, initial-scale=1.0">
             <title>Kontak Kami</title>
             <link rel="stylesheet" href="style.css">
         </head>
         <body>
             <div id="container">
                 <header>
                     <h1>Kontak Kami</h1>
                 </header>
         
                 <nav>
                     <a href="home.html">Home</a>
                     <a href="artikel.html">Artikel</a>
                     <a href="about.html">About</a>
                     <a href="kontak.html" class="active">Kontak</a>
                 </nav>
         
                 <section id="main">
                     <h2>Hubungi Kami</h2>
                     <form>
                         <label>Nama:</label><br>
                         <input type="text" name="nama" placeholder="Masukkan nama"><br><br>
         
                         <label>Email:</label><br>
                         <input type="email" name="email" placeholder="Masukkan email"><br><br>
         
                         <label>Pesan:</label><br>
                         <textarea name="pesan" rows="5" placeholder="Tulis pesan Anda..."></textarea><br><br>
         
                         <button type="submit">Kirim</button>
                     </form>
                 </section>
         
                 <footer>
                     <p>&copy; 2025 - Universitas Pelita Bangsa</p>
                 </footer>
             </div>
         </body>
         </html>

<img width="1920" height="1200" alt="Screenshot 2025-10-16 161248" src="https://github.com/user-attachments/assets/54700d49-6ddd-4eaa-8861-3de08f605e2d" />
         
                  
                     
                     
                                         
                                
