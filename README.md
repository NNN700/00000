<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>jQuery Mobile Example</title>
    <link rel="stylesheet" href="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
    <script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>
    <script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>
    <!-- Home Page -->
    <div data-role="page" id="home">
        <div data-role="header">
            <h1>Home</h1>
            <a href="#about" data-icon="info" class="ui-btn-right">About</a>
        </div>
        <div data-role="content">
            <h2>Welcome to Home Page</h2>
            <p>This is the home page of our jQuery Mobile site.</p>
            <a href="#services" data-role="button">Services</a>
            <a href="#contact" data-role="button">Contact</a>
        </div>
        <div data-role="footer">
            <h4>Footer Text</h4>
        </div>
    </div>

    <!-- Services Page -->
    <div data-role="page" id="services">
        <div data-role="header">
            <h1>Services</h1>
            <a href="#home" data-icon="home" class="ui-btn-right">Home</a>
        </div>
        <div data-role="content">
            <h2>Our Services</h2>
            <p>Details about the services we offer.</p>
            <a href="#home" data-role="button">Back to Home</a>
        </div>
        <div data-role="footer">
            <h4>Footer Text</h4>
        </div>
    </div>

    <!-- About Page -->
    <div data-role="page" id="about">
        <div data-role="header">
            <h1>About</h1>
            <a href="#home" data-icon="home" class="ui-btn-right">Home</a>
        </div>
        <div data-role="content">
            <h2>About Us</h2>
            <p>Information about our website and company.</p>
            <a href="#home" data-role="button">Back to Home</a>
        </div>
        <div data-role="footer">
            <h4>Footer Text</h4>
        </div>
    </div>

    <!-- Contact Page -->
    <div data-role="page" id="contact">
        <div data-role="header">
            <h1>Contact</h1>
            <a href="#home" data-icon="home" class="ui-btn-right">Home</a>
        </div>
        <div data-role="content">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" name="name" id="name">
                <label for="email">Email:</label>
                <input type="email" name="email" id="email">
                <label for="message">Message:</label>
                <textarea name="message" id="message"></textarea>
                <button type="submit">Submit</button>
            </form>
            <a href="#home" data-role="button">Back to Home</a>
        </div>
        <div data-role="footer">
            <h4>Footer Text</h4>
        </div>
    </div>
</body>
</html>
