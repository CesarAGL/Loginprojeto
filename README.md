 #projetoLogin
 Tela de Login com HTML, CSS e JavaScript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Login</title>
</head>
<body>
    <form action="*php" method="post">
        <fieldset>
            <h1>Login</h1>

            <label for="usuario">Usuário:</label>
            <input name="usuario" type="text" required><br><br>

            <label for="senha">Senha:</label>
            <input name="senha" type="password"><br><br>

            <input type="checkbox" name="manterLogado" value="sim">Manter Logado <br><br>

            <input type="submit" value="Login"><br><br>

            <a href=" ">Ainda não tem conta?</a><br><br>
            <a href=" ">Esqueceu a senha?</a>

        </fieldset>
    </form>
</body>
</html>
