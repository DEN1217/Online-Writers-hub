<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Writer's Hub</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Writer's Hub</h1>
        <p>Connecting Writers and Clients Worldwide</p>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#how-it-works">How It Works</a></li>
                <li><a href="#subscription">Subscription</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Writer's Hub is a global platform connecting online writers and clients, providing opportunities for collaboration and growth.</p>
    </section>

    <section id="how-it-works">
        <h2>How It Works</h2>
        <p>Clients post writing tasks, and writers bid on them. Subscriptions ensure premium features for both clients and writers.</p>
    </section>

    <section id="subscription">
        <h2>Subscription Plans</h2>
        <div class="plans">
            <div class="plan">
                <h3>Basic Plan</h3>
                <p>$10/month</p>
                <p>Access to 10 job postings.</p>
                <p>Pay via MPesa or bank transfer to:</p>
                <p><strong>Phone:</strong> +254746061609</p>
                <button onclick="subscribe('Basic Plan')">Subscribe</button>
            </div>
            <div class="plan">
                <h3>Premium Plan</h3>
                <p>$30/month</p>
                <p>Unlimited access and priority support.</p>
                <p>Pay via MPesa or bank transfer to:</p>
                <p><strong>Phone:</strong> +254746061609</p>
                <button onclick="subscribe('Premium Plan')">Subscribe</button>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to contact us:</p>
        <p><strong>Email:</strong> <a href="mailto:dennykimuu@gmail.com">dennykimuu@gmail.com</a></p>
        <p><strong>Phone:</strong> +254746061609</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Writer's Hub. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
