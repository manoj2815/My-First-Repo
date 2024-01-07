<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Login Page</title>
    <style>
        body {
            background-color: #f0f2f5;
        }
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .login-form {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.2);
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }
        .form-group button {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: none;
            background-color: #1877f2;
            color: #ffffff;
            font-size: 16px;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #166fe5;
        }
    </style>
</head>
<body>
    <div class="container">
        <form class="login-form" action="#" method="POST">
            <h1>Facebook Login</h1>
            <div class="form-group">
                <label for="email">Email address or phone number</label>
                <input type="text" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <button type="submit">Log In</button>
            </div>
        </form>
    </div>
</body>
</html>
