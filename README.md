<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Canecas e Mimos Personalizados</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <h1>Canecas e Mimos Personalizados</h1>
        <p>Personalize seus presentes com exclusividade! Entre em contato pelo WhatsApp: <strong>61 99353-3051</strong></p>
        <nav>
            <ul>
                <li><a href="#canecas">Tipos de Canecas</a></li>
                <li><a href="#mimos">Mimos Personalizados</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Seção Tipos de Canecas -->
    <section id="canecas">
        <h2>Tipos de Canecas</h2>
        <div class="produtos">
            <div class="produto">
                <img src="link-para-imagem-caneca-1" alt="Caneca de Cerâmica">
                <h3>Caneca de Cerâmica</h3>
                <p>Perfeita para café e chá, disponível em diversos designs.</p>
            </div>
            <div class="produto">
                <img src="link-para-imagem-caneca-2" alt="Caneca Mágica">
                <h3>Caneca Mágica</h3>
                <p>Revela a imagem quando adicionada bebida quente.</p>
            </div>
            <div class="produto">
                <img src="link-para-imagem-caneca-3" alt="Caneca de Vidro">
                <h3>Caneca de Vidro</h3>
                <p>Elegante e durável, ideal para bebidas frias ou quentes.</p>
            </div>
        </div>
    </section>

    <!-- Seção Mimos Personalizados -->
    <section id="mimos">
        <h2>Mimos Personalizados</h2>
        <div class="produtos">
            <div class="produto">
                <img src="link-para-imagem-mimo-1" alt="Chaveiro Personalizado">
                <h3>Chaveiro Personalizado</h3>
                <p>Personalize com seu nome, frases ou imagens especiais.</p>
            </div>
            <div class="produto">
                <img src="link-para-imagem-mimo-2" alt="Almofada Personalizada">
                <h3>Almofada Personalizada</h3>
                <p>Conforto e estilo com seu design exclusivo.</p>
            </div>
            <div class="produto">
                <img src="link-para-imagem-mimo-3" alt="Porta-Retrato Personalizado">
                <h3>Porta-Retrato Personalizado</h3>
                <p>Guarde suas memórias em um porta-retrato feito especialmente para você.</p>
            </div>
        </div>
    </section>

    <!-- Seção de Contato -->
    <section id="contato">
        <h2>Entre em Contato</h2>
        <p>Gostou de algum dos nossos produtos? Entre em contato pelo WhatsApp: <strong>61 99353-3051</strong></p>
        <form id="form-contato">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Canecas e Mimos Personalizados. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
