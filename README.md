# ALZONIADERMATO
"Add file">"upload files"
`meu_site.html`
`index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Pessoal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff69b4;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff1493;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ff69b4;
        }
        .container {
            padding: 20px;
        }
        .blog-post {
            border-bottom: 1px solid #ddd;
            margin-bottom: 20px;
            padding-bottom: 20px;
        }
        .contact-form, .gallery, .videos, .social-feeds {
            margin-top: 20px;
        }
        footer {
            background-color: #ff1493;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .social-links a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }
        .video {
            margin-bottom: 20px;
        }
        .video iframe {
            width: 100%;
            height: 315px;
        }
    </style>
</head>
<body>

<header>
    <h1>Bem-vindo ao Meu Site Pessoal</h1>
    <p>Focado em Dermatologia e Cirurgias Dermatológicas</p>
</header>

<nav>
    <a href="#blog">Blog</a>
    <a href="#contact">Contato</a>
    <a href="#videos">Vídeos</a>
</nav>

<div class="container">

    <section id="blog">
        <h2>Blog</h2>
        <div class="blog-post">
            <h3>Título do Post</h3>
            <p>Conteúdo do post...</p>
        </div>
        <!-- Adicione mais posts conforme necessário -->
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <div class="contact-form">
            <form action="https://example.com/submit" method="POST">
                <label for="name">Nome:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Mensagem:</label><br>
                <textarea id="message" name="message" required></textarea><br>
                <input type="submit" value="Enviar">
            </form>
        </div>
    </section>

    <section class="gallery">
        <h2>Galeria de Imagens</h2>
        <!-- Adicione suas imagens aqui -->
    </section>

    <section id="videos" class="videos">
        <h2>Vídeos</h2>
        <div class="video">
            <iframe src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <!-- Adicione mais vídeos conforme necessário -->
    </section>

    <section class="social-feeds">
        <h2>Feeds das Redes Sociais</h2>
        <!-- Integração com Instagram -->
        <div>
            <h3>Instagram</h3>
            <div id="instagram-feed">
                <!-- Código de integração do feed do Instagram -->
            </div>
        </div>
        <!-- Integração com LinkedIn -->
        <div>
            <h3>LinkedIn</h3>
            <div id="linkedin-feed">
                <!-- Código de integração do feed do LinkedIn -->
            </div>
        </div>
        <!-- Integração com GitHub -->
        <div>
            <h3>GitHub</h3>
            <div id="github-feed">
                <!-- Código de integração do feed do GitHub -->
            </div>
        </div>
    </section>

</div>

<footer>
    <div class="social-links">
        <a href="https://instagram.com/username" target="_blank">Instagram</a>
        <a href="https://linkedin.com/in/username" target="_blank">LinkedIn</a>
        <a href="https://github.com/username" target="_blank">GitHub</a>
    </div>
    <p>&copy; 2024 Meu Site Pessoal</p>
</footer>

</body>
</html>
