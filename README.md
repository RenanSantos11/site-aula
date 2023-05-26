<!DOCTYPE html>
<html>
<head>
    <title>Área de Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .login-container {
            background-color: #ffffff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 40px;
            width: 300px;
        }

        .login-container h1 {
            color: #333333;
            text-align: center;
            margin-bottom: 30px;
        }

        .login-form input[type="text"],
        .login-form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #dddddd;
            border-radius: 3px;
        }

        .login-form input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #333333;
            color: #ffffff;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .login-form input[type="submit"]:hover {
            background-color: #666666;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h1>Área de Login</h1>

        <form class="login-form">
            <input type="text" name="username" placeholder="Nome de usuário"><br>
            <input type="password" name="password" placeholder="Senha"><br>
            <input type="submit" value="Entrar">
        </form>
    </div>
</body>
</html>
