<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Contact Whitewater Rafting Co. for inquiries, reservations, or feedback about our rafting services.">
    <title>Contact Us | Whitewater Rafting</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles/rafting.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <img src="images/logo.jpeg" alt="Rafting Company Logo">
            <h1>Whitewater Rafting Co.</h1>
            <nav>
                <a href="index.html">Home</a>
                <a href="about.html">About Us</a>
                <a href="trips.html">Trips</a>
                <a href="contact.html">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Company Information -->
        <section class="company-info">
            <h2>Company Information</h2>
            <p><strong>Address:</strong> 123 River Road, Adventure City, State ZIP</p>
            <p><strong>Phone:</strong> (123) 456-7890</p>
            <p><strong>Email:</strong> info@whitewaterrafting.com</p>
        </section>

        <!-- Google Map -->
        <section class="google-map">
            <h2>Find Us on the Map</h2>
            <iframe src="https://www.google.com/maps/embed?..." width="400" height="300"></iframe>
        </section>

        <!-- Employee Profiles -->
        <section class="employee-profiles">
            <h2>Meet Our Team</h2>
            <div class="profile">
                <img src="images/employee1.jpg" alt="Crispus1">
                <p>Crispus2 - Lead Guide</p>
            </div>
            <div class="profile">
                <img src="images/employee2.jpg" alt="Crispus1">
                <p>Crispus2 - Customer Service Manager</p>
            </div>
            <div class="profile">
                <img src="images/employee3.jpg" alt="Crispus1">
                <p>Crispus2 - Marketing Specialist</p>
            </div>
        </section>

        <!-- Contact Form -->
        <section class="contact-form">
            <h2>Send Us a Message</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label>Purpose of Message:</label>
                <input type="radio" id="general" name="purpose" value="general" required>
                <label for="general">General Inquiry</label>
                <input type="radio" id="reservation" name="purpose" value="reservation" required>
                <label for="reservation">Reservation Question</label>
                <input type="radio" id="suggestion" name="purpose" value="suggestion" required>
                <label for="suggestion">Website Suggestion</label>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <label for="newsletter">
                    <input type="checkbox" id="newsletter" name="newsletter">
                    Please subscribe me to the monthly newsletter
                </label>

                <button type="submit">Send Your Message</button>
            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Whitewater Rafting Co. All rights reserved.</p>
        <p><a href="https://app.moqups.com/FX0PQZR6QjqdM5tzbp4uTFjfh25RdRdu/view/page/ad12de680">View Contact Us Wireframe</a></p>
        <div class="social-links">
            <a href="#"><img src="images/facebook.png" alt="Facebook"></a>
            <a href="#"><img src="images/twitter.png" alt="Twitter"></a>
            <a href="#"><img src="images/instagram.png" alt="Instagram"></a>
        </div>
    </footer>
</body>
</html># week05
