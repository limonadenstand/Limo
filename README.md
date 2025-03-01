# Aktualisierte finale Version mit dem richtigen Preis für den Kaffee-Becher (2,30 €)
file_path_final_corrected_price = "/mnt/data/oelberg_limonade_final_corrected_price.html"

html_content_final_corrected_price = f"""<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ölberg Limonade – Premium Zitronenerfrischung</title>
    <style>
        body {{
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }}
        header {{
            background: linear-gradient(90deg, #ffcc00, #ff9900);
            color: white;
            padding: 60px 0;
            text-align: center;
            font-size: 36px;
            font-weight: bold;
            box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.2);
            letter-spacing: 2px;
        }}
        .container {{
            width: 90%;
            max-width: 1200px;
            margin: 50px auto;
            text-align: center;
        }}
        .box {{
            background: white;
            padding: 50px;
            margin: 30px 0;
            border-radius: 15px;
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease-in-out;
        }}
        .box:hover {{
            transform: scale(1.05);
        }}
        h2 {{
            color: #ff9900;
            font-size: 28px;
            margin-bottom: 15px;
        }}
        ul {{
            list-style: none;
            padding: 0;
        }}
        ul li {{
            font-size: 24px;
            margin: 15px 0;
            font-weight: bold;
            color: #333;
        }}
        .highlight {{
            font-size: 22px;
            font-weight: bold;
            color: #ff9900;
        }}
        .cta {{
            display: inline-block;
            background: #ff9900;
            color: white;
            padding: 15px 30px;
            font-size: 22px;
            font-weight: bold;
            border-radius: 8px;
            text-decoration: none;
            margin-top: 20px;
            transition: background 0.3s ease-in-out;
        }}
        .cta:hover {{
            background: #cc7700;
        }}
        .map-link {{
            display: inline-block;
            margin-top: 20px;
            font-size: 20px;
            color: #ff9900;
            text-decoration: none;
            font-weight: bold;
        }}
        .map-link:hover {{
            text-decoration: underline;
        }}
        footer {{
            background: #ffcc00;
            text-align: center;
            padding: 25px;
            font-size: 20px;
            margin-top: 40px;
            color: white;
            font-weight: bold;
        }}
    </style>
</head>
<body>
    <header>Ölberg Limonade – Die beste Zitronenerfrischung</header>

    <div class="container">
        <div class="box">
            <h2>🌟 Die erfrischendste Limonade der Stadt! 🌟</h2>
            <p>Unsere **Premium-Zitronenlimonade** wird mit den frischesten Zutaten und viel Liebe hergestellt. Perfekt gekühlt – ein **unvergleichlicher Geschmack** für heiße Tage.</p>
        </div>

        <div class="box">
            <h2>🥇 Unsere Größen & Preise</h2>
            <ul>
                <li>🍋 <b>0,5l Becher</b> – 2,50 €</li>
                <li>🍋 <b>0,2l Becher</b> – 2,00 €</li>
                <li>☕ <b>Kaffee-Becher</b> – 2,30 €</li>
                <li>🛡️ <b>Deckel für Kaffee-Becher</b> – 0,20 €</li>
            </ul>
        </div>

        <div class="box">
            <h2>📍 Wo findest du uns?</h2>
            <p class="highlight">Holzgasse 113, 3400 Klosterneuburg</p>
            <a href="{google_maps_link}" target="_blank" class="map-link">📍 Standort auf Google Maps anzeigen</a>
        </div>

        <div class="box">
            <h2>🕒 Öffnungszeiten</h2>
            <p class="highlight">Geöffnet in den Sommerferien.</p>
            <p>Für weitere Infos kontaktieren Sie uns auf:</p>
            <a href="mailto:{correct_email}" class="cta">📧 {correct_email}</a>
        </div>

        <div class="box">
            <h2>💬 Fragen oder Großbestellungen?</h2>
            <p>Du willst eine größere Menge bestellen oder hast eine Frage?</p>
            <a href="mailto:{correct_email}" class="cta">Jetzt Kontakt aufnehmen</a>
        </div>
    </div>

    <footer>&copy; 2025 Ölberg Limonade – Qualität, Frische & Genuss</footer>
</body>
</html>
"""

# Datei speichern
with open(file_path_final_corrected_price, "w", encoding="utf-8") as file:
    file.write(html_content_final_corrected_price)

# Datei bereitstellen
file_path_final_corrected_price
