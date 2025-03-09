<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encuesta Fiesta de Bienvenida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .container {
            max-width: 500px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px 0px #aaa;
        }
        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Encuesta: Fiesta de Bienvenida</h2>
        <form id="surveyForm">
            <label>Fecha preferida:</label><br>
            <input type="date" id="fecha" required><br><br>
            
            <label>Tipo de comida preferida:</label><br>
            <select id="comida" required>
                <option value="Buffet">Buffet</option>
                <option value="Parrilla">Parrilla</option>
                <option value="Comida Internacional">Comida Internacional</option>
            </select><br><br>
            
            <label>Estilo de música:</label><br>
            <input type="radio" name="musica" value="Clásica" required> Clásica<br>
            <input type="radio" name="musica" value="Rock"> Rock<br>
            <input type="radio" name="musica" value="Electrónica"> Electrónica<br>
            <input type="radio" name="musica" value="Latina"> Latina<br><br>
            
            <label>Ubicación preferida:</label><br>
            <input type="text" id="ubicacion" placeholder="Ej. Salón de eventos" required><br><br>
            
            <button type="submit" class="button">Enviar</button>
        </form>
        <p id="mensaje"></p>
    </div>

    <script>
        document.getElementById("surveyForm").addEventListener("submit", function(event) {
            event.preventDefault();
            document.getElementById("mensaje").innerText = "¡Gracias por tu respuesta!";
            document.getElementById("surveyForm").reset();
        });
    </script>
</body>
</html>
