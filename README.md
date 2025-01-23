<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Лендінг з реєстрацією</title>
</head>
<body>
    <h1>Реєстрація клієнтів</h1>
    <form action="https://formsubmit.co/ваш_емейл@example.com" method="POST">
        <label for="lastName">Прізвище:</label><br>
        <input type="text" id="lastName" name="lastName" required><br><br>
        <label for="firstName">Ім'я:</label><br>
        <input type="text" id="firstName" name="firstName" required><br><br>
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="phone">Телефон:</label><br>
        <input type="tel" id="phone" name="phone" required><br><br>
        <button type="submit">Реєстрація</button>
    </form>
</body>
</html>
