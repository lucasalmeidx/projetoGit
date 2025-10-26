<!-- <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem vindo ao Meu Site!</h1>
        <nav>
            <a href="#">Inicio</a>
            <a href="#">Sobre</a>
            <a href="#">Contato</a>
        </nav>

        <button id="toggle-theme">🌙 Modo Escuro</button>
    </header>

    <main>
        <section class="intro">
            <h2>Olá! 👋</h2>
            <p>Esse é o meu primeiro projeto em HTML e CSS. Aqui estou aprendendo a criar sites simples e publicar no GitHub!</p>
            <button>Saiba mais</button>
        </section>
    </main>
    
    <footer>
        <p>Feito por Lucas de Almeida</p>
    </footer>

    <script>
        const btn = document.getElementById('toggle-theme');
        const body = document.body;

        btn.addEventListener('click', () => {
            body.classList.toggle('dark-mode');

            if(body.classList.contains('dark-mode')){
                btn.textContent = '☀️ Modo Claro';
            }

            else{
                btn.textContent = '🌙 Modo Escuro';
            }
        });
    </script>
    
</body>
</html>

-->