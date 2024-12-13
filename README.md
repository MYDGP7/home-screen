<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styling */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        /* Hero Section */
        .hero {
            background-image: url('https://via.placeholder.com/1600x800'); /* Replace with your image */
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 3.5em;
            margin-bottom: 20px;
            font-weight: bold;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        .hero .cta-button {
            padding: 15px 30px;
            background-color: #007BFF;
            color: white;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
        }

        /* Features Section */
        .features {
            display: flex;
            justify-content: center;
            padding: 60px 20px;
            background-color: #f4f4f4;
            text-align: center;
        }

        .feature {
            margin: 0 20px;
            flex: 1;
        }

        .feature h3 {
            margin-bottom: 15px;
            font-size: 1.5em;
        }

        .feature p {
            font-size: 1em;
        }

        /* Testimonial Section */
        .testimonials {
            background-color: #ffffff;
            padding: 60px 20px;
            text-align: center;
        }

        .testimonials h2 {
            margin-bottom: 30px;
            font-size: 2em;
        }

        .testimonial {
            margin: 20px auto;
            max-width: 600px;
        }

        .testimonial p {
            font-size: 1.1em;
            margin-bottom: 10px;
        }

        .testimonial cite {
            font-style: italic;
            color: #555;
        }

        /* CTA Section */
        .cta {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        .cta h2 {
            margin-bottom: 20px;
            font-size: 2.5em;
        }

        .cta .cta-button {
            padding: 15px 30px;
            background-color: #fff;
            color: #007BFF;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
        }

        /* Footer Section */
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        .footer a {
            color: #ddd;
            text-decoration: none;
            margin: 0 10px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .features {
                flex-direction: column;
            }

            .feature {
                margin-bottom: 30px;
                text-align: center;
            }

            .hero h1 {
                font-size: 2.5em;
            }

            .hero p {
                font-size: 1em;
            }

            .cta h2 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h1>Simplify, Automate, Achieve Success with MYDGP’s Service Solutions</h1>
            <p>Discover how MYDGP transforms your service management through powerful automation and simple solutions.</p>
            <a href="#cta" class="cta-button">Get Started Today</a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="feature">
            <h3>Fast Performance</h3>
            <p>Enjoy lightning-fast speeds and maximum efficiency.</p>
        </div>
        <div class="feature">
            <h3>User-Friendly</h3>
            <p>Easy to use, with a design that anyone can navigate.</p>
        </div>
        <div class="feature">
            <h3>Affordable Pricing</h3>
            <p>Get the best value for your money with our competitive pricing.</p>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <h2>What Our Users Are Saying</h2>
        <div class="testimonial">
            <p>"This product has completely changed how I work. I can't imagine going back!"</p>
            <cite>- Jane Doe, CEO of Company X</cite>
        </div>
        <div class="testimonial">
            <p>"Best purchase I’ve ever made! Worth every penny."</p>
            <cite>- John Smith, Marketing Specialist</cite>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta" id="cta">
        <h2>Start Your Free Trial Now!</h2>
        <a href="#" class="cta-button">Sign Up</a>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <p>© 2024 MYDGP. All rights reserved.</p>
        <p>
            <a href="#">Privacy Policy</a>
            <a href="#">Terms of Service</a>
            <a href="#">Contact Us</a>
        </p>
    </footer>

</body>
</html>
