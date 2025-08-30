<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Painel ESP - Soares</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #800020; /* Fundo vinho */
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    #painel {
        background-color: rgba(0,0,0,0.5);
        padding: 30px 50px;
        border-radius: 15px;
        text-align: center;
        box-shadow: 0 0 20px rgba(0,0,0,0.7);
    }

    h1 {
        margin: 0;
        font-size: 3em;
        color: #FFD700; /* dourado */
    }

    button {
        margin-top: 20px;
        padding: 10px 20px;
        font-size: 1em;
        border: none;
        border-radius: 10px;
        background-color: #FFD700;
        color: #800020;
        cursor: pointer;
        transition: 0.3s;
    }

    button:hover {
        background-color: #fff;
        color: #800020;
    }
</style>
</head>
<body>
    <div id="painel">
        <h1>Soares</h1>
        <button onclick="alert('ESP ativado!')">Ativar ESP</button>
    </div>
</body>
</html>
