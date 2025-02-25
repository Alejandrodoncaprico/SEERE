<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Hukum Indonesia</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">SEERE</div>
            <ul>
                <li><a href="#beranda">Beranda</a></li>
                <li><a href="#layanan">Layanan Hukum</a></li>
                <li><a href="#artikel">Artikel</a></li>
                <li><a href="#konsultasi">Konsultasi</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h1>Solusi Hukum Terpercaya</h1>
            <p>Dapatkan informasi dan bantuan hukum dari para ahli</p>
            <button>Konsultasi Sekarang</button>
        </section>

        <section id="layanan">
            <h2>Layanan Kami</h2>
            <div class="layanan-grid">
                <div class="layanan-item">
                    <h3>Hukum Pidana</h3>
                    <p>Bantuan untuk kasus pidana</p>
                </div>
                <div class="layanan-item">
                    <h3>Hukum Perdata</h3>
                    <p>Penanganan perkara perdata</p>
                </div>
                <div class="layanan-item">
                    <h3>Hukum Bisnis</h3>
                    <p>Konsultasi hukum bisnis</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Portal Hukum Indonesia. Hak Cipta Dilindungi.</p>
    </footer>
</body>
</html>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
}

header {
    background: #2c3e50;
    padding: 1rem;
    color: white;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
}

#hero {
    background: #34495e;
    color: white;
    text-align: center;
    padding: 4rem 2rem;
}

#hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

button {
    background: #e74c3c;
    color: white;
    border: none;
    padding: 1rem 2rem;
    margin-top: 1rem;
    cursor: pointer;
    border-radius: 5px;
}

.layanan-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    padding: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.layanan-item {
    background: #f5f6fa;
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
}

footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    width: 100%;
} 
