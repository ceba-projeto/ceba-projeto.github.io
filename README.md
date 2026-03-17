<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site - Layout Sidebar</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            display: flex;
            height: 100vh;
            background-color: #ffffff;
        }

        /* BARRA LATERAL (SIDEBAR) */
        .sidebar {
            width: 250px;
            border-right: 2px solid #000;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding-top: 20px;
        }

        /* O CÍRCULO DA FOTO */
        .perfil-foto {
            width: 120px;
            height: 120px;
            border: 2px solid #000;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            text-transform: uppercase;
            margin-bottom: 10px;
        }

        /* NOME ABAIXO DA FOTO */
        .nome-usuario {
            width: 100%;
            text-align: center;
            border-top: 2px solid #000;
            border-bottom: 2px solid #000;
            padding: 10px 0;
            font-weight: bold;
            text-transform: lowercase;
        }

        /* LINKS CLICÁVEIS (INTERATIVO) */
        .menu-links {
            width: 100%;
            display: flex;
            flex-direction: column;
        }

        .link-interativo {
            width: 100%;
            padding: 15px;
            text-align: center;
            text-decoration: none;
            color: #000;
            border-bottom: 1px solid #000;
            font-weight: 500;
            transition: 0.3s;
        }

        /* Efeito de clique/passar o mouse */
        .link-interativo:hover {
            background-color: #f0f0f0;
            padding-left: 25px; /* Pequeno efeito de movimento */
        }

        /* ÁREA DE CONTEÚDO (DIREITA) */
        .conteudo-principal {
            flex-grow: 1;
            padding: 40px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #ccc;
        }
    </style>
</head>
<body>

    <aside class="sidebar">
        <div class="perfil-foto">
            foto
        </div>

        <div class="nome-usuario">
            antony
        </div>

        <nav class="menu-links">
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
            <a href="#" class="link-interativo">interativo</a>
        </nav>
    </aside>

    <main class="conteudo-principal">
        <h1>Área de Conteúdo</h1>
    </main>

</body>
</html>
