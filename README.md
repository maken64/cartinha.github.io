amo<html>
<head>
    <title</title>
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
    <p id="question">oii fernanda, aceita namorar cmg?.</p>
    <div id="buttons">
        <button onclick="redirecionarParaWhatsApp()">Sim</button>
        <button onclick="responder('sim')">Não</button>
    </div>
    <p id="response"></p>

    <script>
        function redirecionarParaWhatsApp() {
            // Substitua o número de telefone abaixo pelo seu número do WhatsApp
            var numeroWhatsApp = "+5568996059753";
            
            // Substitua a mensagem abaixo pela mensagem que você deseja enviar
            var mensagem = "aceito sim, eu te amo ❤️❤️";
            
            var linkWhatsApp = "https://wa.me/5568996059753 + "?text=" + encodeURIComponent(eu te amo fernanda ❤️❤️);
            
            window.location.href = linkWhatsApp;
        }
        
        function responder(resposta) {
            var responseElement = document.getElementById('response');

            if (resposta === 'sim') {
                responseElement.innerHTML = " aeeeee, qbomm";
            } else if (resposta === 'nao') {
                responseElement.innerHTML = "Ah, entendo. Não tem problema, eu respeito a sua decisão. Se um dia você mudar de ideia, estarei aqui.";
            }
        }
    </script>
</body>
</html>
