# Lab4Web. (PERTEMUAN 5)

# Muhamad Faisal Ilham
## TI.22.A3

## Tugas : 
1. Tambahkan Layout untuk menu About=> buat single layout yang berisi deskripsi, portfolio, dll
2. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll

### 1. Layout Menu About
![Screenshot_24](https://github.com/vsal19/Lab4Web./assets/115516624/b83bac8f-e9d8-4873-9cf2-dc8d717cccaa)

#### Code HTML :
```
<!DOCTYPE html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>About Me</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="about">
            <div class="row">
                <img src="faisal.jpg.jpeg" title="faisal" alt="Foto Faisal" width="200px
                " class="image-circle" style="float: left; border: 2px solid black;">
                <h1>Faisal</h1>
                <p>Nama saya Muhamad Faisal Ilham, Saya adalah seorang mahasiswa Universitas Pelita Bangsa,Jurusan Teknik Informatika. Saya lahir di Bekasi,19 Juni 2004. dan saya sedang mempelajari html css & js sebagai jalan menuju front end developer</p>
            </div>
        </section>
        <footer>
            <p style="text-align: center;">@Faisal</p>
        </footer>
    </div>
</body>
</html>
```

#### Code CSS
```
#about{
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
}
#about h1{
    margin-bottom: 10px;
    font-size: 35px;
    position: relative;
    left: 15px;
}
#about p{
    margin-bottom: 20px;
    font-size: 18px;
    padding: 30px;
    line-height: 25px;
    position: relative;
    left: 15px;
```

### 1. Layout Menu Contact

#### Code HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Contact Me</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="kontak">
            <div class="login">
                <input type="text" placeholder="Your Name" class="input">
                <input type="text" placeholder="Your Email" class="input">
            </div>
            <div class="subject">
                <input type="text" placeholder="Subject" class="input"> 
            </div>
            <div class="msg">
                <textarea name="Message" id="Message" cols="35" rows="10" class="area" class="input" placeholder="Your Message"></textarea>
            </div>
            <button type="submit">Send</button>
        </section>
    </div>
</body>
</html>
```

#### Code CSS



