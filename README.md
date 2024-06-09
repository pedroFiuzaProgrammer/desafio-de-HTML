<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo à Minha Página Web!</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
    
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Somos uma equipe apaixonada por desenvolvimento web, design e tecnologia. Nosso objetivo é criar soluções inovadoras que atendam às necessidades de nossos clientes.</p>
    </section>
    
    <section id="servicos">
        <h2>Nossos Serviços</h2>
        <ul>
            <li>Design Web Personalizado</li>
            <li>Desenvolvimento de Aplicativos Web</li>
            <li>Hospedagem e Manutenção</li>
            <li>Otimização para Mecanismos de Busca (SEO)</li>
        </ul>
    </section>
    
    <section id="portfolio">
        <h2>Portfolio</h2>
        <p>Aqui estão alguns dos projetos que já desenvolvemos:</p>
        <ul>
            <li><a href="#">Projeto 1</a></li>
            <li><a href="#">Projeto 2</a></li>
            <li><a href="#">Projeto 3</a></li>
        </ul>
    </section>
    
    <section id="contato">
        <h2>Entre em Contato</h2>
        <p>Estamos ansiosos para ouvir sobre o seu projeto. Entre em contato conosco hoje mesmo!</p>
        <form action="#" method="post">
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome" required><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="mensagem">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem" rows="4" required></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 Minha Página Web</p>
    </footer>
</body>
</html> 
