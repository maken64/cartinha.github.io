
<html>
<head>
    <title>cartinha (aceita pfv 😭)</title>
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
    <p id="question">oii fernanda, vc aceita nmr cmg?.</p>
    <div id="buttons">
        <button onclick="redirecionarParaWhatsApp()">Sim</button>
        <button onclick="responder('nao')">Não</button>
    </div>
    <p id="response"></p>

    <script>
        function redirecionarParaWhatsApp() {
            var numeroWhatsApp = "+5568996059753"; // Substitua pelo seu número de telefone, incluindo o código do país
            var mensagem = "aceito simm, eu te amo ❤️"; // Substitua pela mensagem que você deseja enviar
            
            var linkWhatsApp = "https://wa.me/" + numeroWhatsApp + "?text=" + encodeURIComponent(mensagem);
            
            window.location.href = linkWhatsApp;
        }
        
        function responder(resposta) {
            var responseElement = document.getElementById('response');

            if (resposta === 'sim') {
                responseElement.innerHTML = "Que ótimo! Eu estou muito feliz por você ter aceitado. Mal posso esperar para começarmos esse relacionamento juntos!";
            } else if (resposta === 'nao') {
                responseElement.innerHTML = "Ah, entendo. Não tem problema, eu respeito a sua decisão. Se um dia você mudar de ideia, estarei aqui.";
            }
        }
    </script>
</body>
</html>
