# login-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create New Account</title>
    <link rel="stylesheet" href="account.css">
</head>
<body>
    <div class="container">
        <h2>Create New Account</h2>
        <form id="createAccountForm" onsubmit="createAccount(); return true;">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <label for="confirmPassword">Confirm Password:</label>
            <input type="password" id="confirmPassword" name="confirmPassword" required>

            <button type="submit"><a href="newlogin.html" target="_self" >Submit</a></a></button>
        </form>
    </div>

    <script src="create_account.js"></script>
</body>
</html>
