# Victor1
<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Victor Navarro</title>
    <style>
        body {
            background-color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column;
        }
        .logo {
            font-size: 3em;
            font-weight: bold;
            color: black;
        }
        form {
            margin-top: 30px;
            text-align: center;
        }
        input[type="email"] {
            padding: 10px;
            font-size: 1em;
            margin-right: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            padding: 10px 20px;
            font-size: 1em;
            border: none;
            background-color: black;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #333;
        }
    </style>
</head>
<body>
    <div class="logo">Victor Navarro</div>
    <form action="mailto:your-victor.navarro.promesa.com" method="post" enctype="text/plain">
        <input type="email" name="email" placeholder="Zadejte svůj email" required>
        <input type="submit" value="Přihlásit se">
    </form>
</body>
</html>