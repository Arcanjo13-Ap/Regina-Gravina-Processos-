# Regina-Gravina-Processos-
<!DOCTYPE html> <!-- Declaração do tipo de documento para HTML5 -->
<html lang="pt-BR"> <!-- Define o idioma da página como português do Brasil -->
<head>
    <meta charset="UTF-8"> <!-- Define a codificação de caracteres para UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Garante a responsividade da página em dispositivos móveis -->
    <meta name="description" content="Site da PixelCraft, especialista em desenvolvimento front-end e soluções digitais."> <!-- Descrição para SEO -->
    <title>PixelCraft - Página Inicial</title> <!-- Define o título da página -->
    <link rel="stylesheet" href="style/styles.css"> <!-- Link para o arquivo CSS externo (melhoria na organização) -->
    
    
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <h1>PixelCraft</h1> <!-- Título principal da página -->

        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#services">Serviços</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Seção de Introdução -->
    <section id="home">
        <h2>Seja Bem-vindo</h2>
        <img src="Front-end.jpg" alt="Imagem de Exemplo" width="600" height="500"> <!-- Imagem de introdução -->
    
    <!-- Seção Sobre -->
    <section id="about">
        <h2>Sobre Nós</h2>
        <p>Bem-vindo à PixelCraft! Somos uma equipe apaixonada por tecnologia e inovação, especializada em desenvolvimento front-end e sistemas. Nossa missão é transformar ideias em soluções digitais eficientes e visualmente atraentes.</p>
        <div>
            <h3>Visão Geral</h3>
            <p>Nossa visão é ser líder em inovação tecnológica, oferecendo soluções digitais que transformam ideias em realidade.</p>
        </div>
        <div>
            <h3>Missão</h3>
            <p>Nossa missão é ajudar empresas e indivíduos a alcançar seus objetivos digitais através de soluções personalizadas e inovadoras.</p>
        </div>
        <div>
            <h3>Valores</h3>
            <p>Valorizamos a inovação, qualidade, colaboração e transparência em todos os nossos projetos.</p>
        </div>
    </section>

    <!-- Seção de Serviços -->
    <section id="services">
        <h2>Serviços</h2>
        <ul>
            <li>Consultoria em TI</li>
            <li>Desenvolvimento de sites responsivos</li>
            <li>Suporte Técnico</li>
            <li>Design de interfaces de usuário (UI) intuitivas e atraentes</li>
        </ul>

        <!-- Tabela de Preços -->
        <h3>Preços</h3> <!--é uma tag de HTML que define um título de nível 3 em um documento HTML. -->
        <table border="1"> <!--|Essa linha de comando  cria uma tabela HTML com uma borda de 1 pixel ao redor de cada célula, ajudando a visualizar a estrutura da tabela. -->
            <thead> <!--Essa linha de comando define o cabeçalho de uma tabela em HTML, agrupando as linhas que contêm os títulos das colunas. -->
                <tr> <!--Essa linha de comando é usada para agrupar um conjunto de células dentro de uma tabela.-->
                    <th>Serviços</th>
                    <th>Preços</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Consultoria em TI</td>
                    <td>R$ 5000,00</td>
                </tr>
                <tr>
                    <td>Desenvolvimento de sites responsivos</td>
                    <td>R$ 12000,00</td>
                </tr>
                <tr>
                    <td>Suporte Técnico</td>
                    <td>R$ 10000,00</td>
                </tr>
                <tr>
                    <td>Design de interfaces de usuário</td>
                    <td>R$ 14000,00</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Seção de Contato -->
    <section id="contact">
        <h2>Contato</h2>
        <p>Preencha o formulário abaixo para entrar em contato conosco:</p>
        <form action="/submit" method="post">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <br>
            <input type="submit" value="Enviar">
        </form>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 PixelCraft. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
