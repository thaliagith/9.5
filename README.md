<!DOCTYPE html>
<html lang="en">
<head>
    <title>Contact Form</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Contact Us</h1>

    <form method="post" action="http://webdevbasics.net/scripts/demo.php">
        <fieldset>
            <legend>Contact Information</legend>

            <div class="form-group">
                <label for="first-name">First Name:</label>
                <input type="text" id="first-name" name="first-name" placeholder="Enter your first name" required>
            </div>

            <div class="form-group">
                <label for="last-name">Last Name:</label>
                <input type="text" id="last-name" name="last-name" placeholder="Enter your last name" required>
            </div>

            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
            </div>
            <div class="form-group">
                <label for="comments">Comments:</label>
                <textarea id="comments" name="comments" rows="5" cols="40" placeholder="Enter your comments here..."></textarea>
            </div>

            <div class="form-buttons">
                <input type="submit" value="Contact" aria-label="Submit the contact form">
                <input type="reset" value="Reset" aria-label="Reset the contact form">
            </div>
        </fieldset>
    </form>
</body>
</html>
