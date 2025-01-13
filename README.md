<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Profissional</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site Profissional</h1>
        <nav>
            <ul>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#services">Serviços</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Sobre Mim</h2>
        <p>Sou um profissional especializado em [área]. Estou aqui para ajudar você a alcançar seus objetivos.</p>
    </section>

    <section id="services">
        <h2>Meus Serviços</h2>
        <ul>
            <li>Serviço 1</li>
            <li>Serviço 2</li>
            <li>Serviço 3</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Entre em Contato</h2>
        <form action="https://formspree.io/f/{sua-chave}" method="POST">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <textarea name="message" placeholder="Sua Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Meu Site Profissional. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
