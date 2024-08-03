# MTBinstallatie
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MTB Installatie</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header img {
            max-width: 200px;
        }
        nav {
            background-color: #444;
            color: #fff;
            display: flex;
            justify-content: center;
            padding: 1rem 0;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 2rem 0;
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 0.5rem;
        }
        .services, .portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .service, .portfolio-item {
            background-color: #fff;
            padding: 1rem;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            flex: 1 1 calc(33.333% - 2rem);
            box-sizing: border-box;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="data:image/jpeg;base64,[BASE64_LOGO_HERE]" alt="MTB Installatie Logo">
    </header>
    <nav>
        <a href="#over-ons">Over ons</a>
        <a href="#diensten">Diensten</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="over-ons" class="section">
            <h2>Over ons</h2>
            <p>Welkom bij MTB Installatie. Wij zijn uw betrouwbare partner voor alle loodgieterswerkzaamheden in Oss en omgeving. Met jarenlange ervaring en een toegewijd team, bieden wij een breed scala aan diensten aan om aan al uw behoeften te voldoen.</p>
        </section>
        <section id="diensten" class="section">
            <h2>Diensten</h2>
            <div class="services">
                <div class="service">
                    <h3>Installatie van leidingen</h3>
                    <p>Professionele installatie van water- en gasleidingen.</p>
                </div>
                <div class="service">
                    <h3>Reparaties</h3>
                    <p>Snel en efficiënt oplossen van alle loodgietersproblemen.</p>
                </div>
                <div class="service">
                    <h3>Onderhoud</h3>
                    <p>Regelmatig onderhoud om problemen te voorkomen en de levensduur van uw installatie te verlengen.</p>
                </div>
            </div>
        </section>
        <section id="portfolio" class="section">
            <h2>Portfolio</h2>
            <div class="portfolio">
                <div class="portfolio-item">
                    <h3>Project 1</h3>
                    <p>Beschrijving van een succesvol afgerond project.</p>
                </div>
                <div class="portfolio-item">
                    <h3>Project 2</h3>
                    <p>Beschrijving van een ander succesvol afgerond project.</p>
                </div>
                <div class="portfolio-item">
                    <h3>Project 3</h3>
                    <p>Beschrijving van weer een ander succesvol afgerond project.</p>
                </div>
            </div>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Adres: Kievit 46, 5348 VE Oss</p>
            <p>Telefoon: 06-39 88 75 66</p>
            <p>Email: <a href="mailto:mtbinstallatie@gmail.com">mtbinstallatie@gmail.com</a></p>
            <form action="mailto:mtbinstallatie@gmail.com" method="post" enctype="text/plain">
                <label for="name">Naam:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Bericht:</label><br>
                <textarea id="message" name="message" required></textarea><br>
                <input type="submit" value="Verstuur">
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 MTB Installatie. Alle rechten voorbehouden.</p>
    </footer>
</body>
</html>