## Hi there 👋

<!--
**Melendez11L/Melendez11L** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi amor</title>
    <style>
        body {
            background-color: #EDE7F6;
            color: #4A148C;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: #6A1B9A;
            font-size: 2.5em;
        }
        button {
            background-color: #6A1B9A;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }
        button:hover {
            background-color: #4A148C;
        }
        p {
            font-size: 1.5em;
            font-style: italic;
            text-align: center;
            margin: 20px;
        }
        .hearts {
            font-size: 3em;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1>Para mi amor</h1>
    <button onclick="showPhrase()">Empezar</button>
    <p id="phrase"></p>
    <div class="hearts">💜💜💜</div>

    <script>
        const phrases = [
            "Eres mi sueño hecho realidad.",
            "Cada día a tu lado es una bendición.",
            "Tu sonrisa ilumina mi mundo.",
            "Eres la razón por la que creo en el amor.",
            "Contigo, todo es mejor.",
            "Mi lugar favorito está a tu lado.",
            "Eres mi refugio y mi paz.",
            "No puedo imaginar mi vida sin ti.",
            "Tu amor es mi mayor tesoro.",
            "Eres el latido de mi corazón.",
            "Cada vez que te miro, me enamoro más.",
            "Gracias por ser mi todo.",
            "Eres el amor de mi vida.",
            "Sin ti, mis días estarían incompletos.",
            "Tu amor me hace sentir invencible.",
            "Te amo más de lo que las palabras pueden expresar.",
            "Eres mi felicidad eterna.",
            "Gracias por existir y por amarme.",
            "Eres la razón de mis sonrisas.",
            "No necesito nada más cuando estoy contigo.",
            "Eres mi ángel en la tierra.",
            "Contigo encontré mi hogar.",
            "Eres mi alma gemela.",
            "Eres mi inspiración diaria.",
            "Mi corazón es tuyo, ahora y siempre.",
            "Eres mi mejor amiga y mi gran amor.",
            "Por tu lado, todo es posible.",
            "Gracias por ser tú.",
            "Eres la melodía de mi vida.",
            "Tu amor es un regalo que valoro cada día.",
            "Eres mi razón de ser.",
            "Contigo, siento que puedo volar.",
            "Tu amor me completa.",
            "Eres la estrella que ilumina mi cielo.",
            "Te amo con todo mi corazón.",
            "Eres mi persona favorita en el mundo.",
            "Gracias por cada momento compartido.",
            "Eres el aire que respiro.",
            "Mi amor por ti no tiene límites.",
            "Eres mi todo.",
            "Contigo, todo es perfecto.",
            "Eres mi luz en la oscuridad.",
            "Te amo más allá de las estrellas.",
            "Eres mi sol en los días nublados.",
            "No puedo esperar a pasar el resto de mi vida contigo.",
            "Eres la razón de mi felicidad.",
            "Gracias por hacerme tan feliz.",
            "Eres mi sueño hecho realidad.",
            "Eres mi amor eterno.",
            "Te amo más cada día.",
            "Eres mi lugar seguro.",
            "Eres mi mundo entero.",
            "Contigo, el amor es verdadero.",
            "Eres mi mejor mitad.",
            "Eres mi razón para sonreír.",
            "Te amo más allá de las palabras.",
            "Eres mi todo y más.",
            "Eres mi amor perfecto.",
            "Contigo, todo es maravilloso.",
            "Eres la razón de mi alegría.",
            "Gracias por amarme.",
            "Eres mi amor y mi vida.",
            "Eres mi razón de vivir.",
            "Contigo, me siento completo.",
            "Eres mi razón para luchar.",
            "Te amo más que a nada.",
            "Eres mi vida y mi amor.",
            "Eres mi felicidad eterna.",
            "Eres la razón de mi ser.",
            "Eres mi amor sin fin.",
            "Contigo, el mundo es un lugar mejor.",
            "Eres mi todo y más.",
            "Eres mi razón de esperanza.",
            "Eres mi amor incondicional.",
            "Eres mi razón para soñar.",
            "Contigo, todo es posible.",
            "Eres mi luz en la oscuridad.",
            "Eres mi amor verdadero.",
            "Eres mi razón de alegría.",
            "Eres mi corazón y mi alma.",
            "Eres mi razón de felicidad.",
            "Contigo, la vida es más hermosa.",
            "Eres mi amor eterno.",
            "Eres mi razón de esperanza.",
            "Eres mi razón de amor.",
            "Eres mi razón de ser.",
            "Contigo, el amor es verdadero.",
            "Eres mi razón de sonreír.",
            "Eres mi todo.",
            "Eres mi razón de vivir.",
            "Eres mi amor y mi vida.",
            "Eres mi razón de esperanza.",
            "Eres mi amor incondicional.",
            "Eres mi razón de felicidad.",
            "Eres mi amor eterno.",
            "Contigo, el mundo es mejor.",
            "Eres mi razón de alegría.",
            "Eres mi luz y mi amor.",
            "Eres mi razón de esperanza.",
            "Eres mi amor verdadero."
        ];

        function showPhrase() {
            const randomIndex = Math.floor(Math.random() * phrases.length);
            document.getElementById('phrase').innerText = phrases[randomIndex];
        }
    </script>
</body>
</html>
