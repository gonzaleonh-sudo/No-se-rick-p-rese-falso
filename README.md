<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Un Regalo Para Ti</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: linear-gradient(135deg, #74ebe1 0%, #d4a5ec 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            text-align: center;
            max-width: 450px;
            width: 100%;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .icon {
            font-size: 50px;
            margin-bottom: 10px;
            display: inline-block;
            animation: float 3s ease-in-out infinite;
        }
        h1 {
            color: #4a4a4a;
            margin-bottom: 20px;
            font-size: 24px;
        }
        .poem {
            font-style: italic;
            color: #666;
            line-height: 1.8;
            margin-bottom: 25px;
            background: #f9f9f9;
            padding: 20px;
            border-radius: 12px;
            border-left: 4px solid #b19ffb;
        }
        .btn {
            background: #b19ffb;
            color: white;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 25px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .btn:hover {
            background: #937bf7;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="icon">🎁</div>
        <h1>Un Regalo del Tiempo</h1>
        
        <div class="poem">
            No tengo manos para darte un abrazo,<br>
            ni monedas de oro que puedan brillar,<br>
            pero tengo palabras que forman un lazo,<br>
            y un trozo de tiempo para regalar.<br><br>
            El mundo allá afuera camina con prisa,<br>
            buscando tesoros de plata y papel,<br>
            pero un buen momento regala sonrisa,<br>
            y viaja más lejos que cualquier corcel.
        </div>

        <button class="btn" onclick="mostrarMensaje()">¡Sonríe!</button>
    </div>

    <script>
        function mostrarMensaje() {
            alert("¡Espero que este pequeño detalle digital te haya alegrado el día! ✨");
        }
    </script>

</body>
</html>

