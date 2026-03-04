<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Primer Proyecto</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.3);
            animation: fadeIn 1.5s ease-in-out;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.2em;
            opacity: 0.9;
        }

        button {
            margin-top: 20px;
            padding: 12px 25px;
            border: none;
            border-radius: 30px;
            background: #00c6ff;
            color: white;
            font-size: 1em;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #0072ff;
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>Hola Mundo 🌎</h1>
        <p>Mi primer proyecto publicado en GitHub</p>
        <button onclick="mostrarMensaje()">Haz clic aquí</button>
    </div>

    <script>
        function mostrarMensaje() {
            alert("¡Felicidades Karloz! 🚀 Ya estás publicando como Ingeniero en Sistemas");
        }
    </script>

</body>
</html>
