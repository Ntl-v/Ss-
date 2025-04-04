# Ss-

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Me perdonas?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        h1 {
            font-size: 24px;
        }
        #imagen {
            margin-top: 15px;
            width: 200px; /* Ajusta el tamaño de la imagen */
            border-radius: 10px;
        }
        #buttons {
            margin-top: 20px;
        }
        button {
            font-size: 16px;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        #btnSi {
            background-color: #4CAF50;
            color: white;
            font-size: 16px;
        }
        #btnNo {
            background-color: #f44336;
            color: white;
        }
    </style>
</head>
<body>

    <h1>¿Me perdonas?</h1>
    <img id="imagen" src="997081EC-5D8B-496B-A3E5-C686D465A358.jpeg" alt="Gatito tierno">
    
    <div id="buttons">
        <button id="btnSi" onclick="perdonar()">Sí</button>
        <button id="btnNo" onclick="agrandarSi()">No</button>
    </div>

    <script>
        let tamanoSi = 16;

        function agrandarSi() {
            tamanoSi += 5; 
            let botonSi = document.getElementById("btnSi");

            if (tamanoSi >= 40) {
                alert("Tendrás que perdonarme sí o sí");
            }
            
            botonSi.style.fontSize = tamanoSi + "px";
            botonSi.style.padding = (tamanoSi / 2) + "px " + (tamanoSi) + "px";
        }

        function perdonar() {
            alert("Gracias amor:( de verdad lamento haberte hecho pasar un mal momento. Eres muy importante para mí, te quiero demasiado, y soy la más feliz a tu lado. Quiero mejorar y haré todo lo posible para que estemos bien, porque eres lo más bonito que me ha pasado y no quisiera perderte, me llenas el corazón, y quiero ser parte de todo en tu vida, tanto en lo bueno como en lo malo, sobre todo en los momentos difíciles, para estar ahí apoyándote. Nunca me había sentido así por alguien, y eso me hace muy feliz, pero al mismo tiempo me da miedo, porque perderte sería demasiado doloroso. Hay muchas cosas que aún no me atrevo a decirte, pero quiero que tengas claro que lo que siento por ti es más que solo cariño, contigo siento comodidad, admiración, y me encanta el hombre que eres y quisiera seguir creciendo y aprendiendo a tu lado.
Te quiero muchísimo ❤️");
        }
    </script>

</body>
</html>