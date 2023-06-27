
<html>
<head>
    <title>Pedido de Namoro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
        }
        
        #question {
            font-size: 20px;
        }
        
        #buttons {
            margin-top: 20px;
        }
        
        #response {
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Carta de Pedido de Namoro</h1>
    <p id="question">oii, Fernanda vc aceita namorar comigo?.</p>
    <div id="buttons">
        <button onclick="responder('sim')">Sim</button>
        <button onclick="responder('nao')">Não</button>
    </div>
    <p id="response"></p>

    <script>
        function responder(resposta) {
            var responseElement = document.getElementById('response');

            if (resposta === 'sim') {
                responseElement.innerHTML = "aeeeeeee,qbom";
            } else if (resposta === 'nao') {
                responseElement.innerHTML = "entao se foda";
            }
        }
    </script>
</body>
</html>
