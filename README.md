<!DOCTYPE html>
<html>
<head>
    <title>Registration</title>
    <script>
        function validateForm() {
            // Perform form validation here (e.g., check if all required fields are filled)
            // You can use JavaScript to perform validation before submission
            // For simplicity, this example checks only if the email is not empty
            var email = document.getElementById("email").value;
            if (email === "") {
                alert("Email must be filled out");
                return false;
            }
        }
    </script>
</head>
<body>
    <h2>User Registration</h2>
    <form onsubmit="return validateForm()">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required><br><br>
        <input type="submit" value="Register">
    </form>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Confirmation</title>
</head>
<body>
    <h2>Registration Successful</h2>
    <p>Thank you for registering! Your account has been created.</p>
    <!-- Display the registered email -->
    <p>Your registered email: example@email.com</p>
    <!-- You can add more details or links here -->
</body>
</html>
