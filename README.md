<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
    </header>
    <main>
        <p>Este é o meu primeiro site criado do zero!</p>
        <button id="botao">Clique aqui</button>
    </main>
    <footer>
        <p>© 2026 - Meu Nome</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
    color: #333;
}

header, footer {
    background-color: #0077b6;
    color: white;
    text-align: center;
    padding: 1rem;
}

main {
    padding: 2rem;
    text-align: center;
}

button {
    background-color: #00b4d8;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background-color: #0096c7;
}
