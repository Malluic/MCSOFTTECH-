<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MC-SoftTech | Premium IT Solutions</title>
    <style>
        /* CSS: Styling and Layout */
        :root {
            --primary-color: #0d6efd;
            --secondary-color: #002244;
            --text-color: #333;
            --bg-light: #f8f9fa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            scroll-behavior: smooth;
        }

        body {
            color: var(--text-color);
            background-color: var(--bg-light);
        }

        /* Navbar */
        header {
            background-color: white;
            padding: 10px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        /* Logo Styling */
        .logo {
            max-height: 70px; /* Logo ki height yahan se adjust karein */
            width: auto;
            object-fit: contain;
            cursor: pointer;
        }

        nav a {
            text-decoration: none;
            color: var(--text-color);
            margin-left: 20px;
            font-weight: 600;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--primary-color);
        }

        /* Hero Section */
        .hero {
            margin-top: 80px; /* Adjusted for logo height */
            background: linear-gradient(135deg, var(--secondary-color), var(--primary-color));
            color: white;
            padding: 100px 20px;
            text-align: center;
        }

        .hero h2 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn {
            background-color: white;
            color: var(--primary-color);
            padding: 12px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            border: none;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: #e2e2e2;
        }

        /* Services Section */
        .services, .contact, .about {
            padding: 60px 20px;
            text-align: center;
            max-width: 1200px;
            margin: auto;
        }

        .section-title {
            font-size: 32px;
            margin-bottom: 40px;
            color: var(--secondary-color);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .card h3 {
            color: var(--primary-color);
            margin-bottom: 15px;
        }

        /* Contact Form */
        .contact form {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: left;
        }

        .input-group {
            margin-bottom: 15px;
        }

        .input-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .input-group input, .input-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .btn-submit {
            background-color: var(--primary-color);
            color: white;
            width: 100%;
            font-size: 16px;
            padding: 12px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .btn-submit:hover {
            background-color: var(--secondary-color);
        }

        #formStatus {
            margin-top: 15px;
            font-weight: bold;
            text-align: center;
        }

        /* Footer */
        footer {
            background-color: var(--secondary-color);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                padding: 15px;
            }
            .logo {
                margin-bottom: 15px;
            }
            nav {
                margin-top: 10px;
            }
            nav a {
                margin-left: 10px;
                margin-right: 10px;
            }
        }
    </style>
</head>
<body>

    <!-- Header / Navbar with updated Logo -->
    <header>
        <a href="#home">
            <img src="1000674168.png" alt="MC-SoftTech Logo" class="logo">
        </a>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Innovative Full Stack & IT Solutions</h2>
        <p>Empowering businesses with modern website development, enterprise software, and scalable digital solutions.</p>
        <a href="#contact" class="btn">Get Started</a>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2 class="section-title">About Our Company</h2>
        <p style="max-width: 800px; margin: auto; line-height: 1.6;">
            Located in Vijayapura, Karnataka, MC-SoftTech is dedicated to delivering high-quality web and software applications. We merge modern glassmorphism UI/UX design with robust architectures to give your business the digital presence it deserves.
        </p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2 class="section-title">Our Premium Services</h2>
        <div class="grid">
            <div class="card">
                <h3>Website Development</h3>
                <p>Fully responsive, dynamic, and fast-loading corporate websites.</p>
            </div>
            <div class="card">
                <h3>Software Development</h3>
                <p>Custom software solutions tailored for your business needs.</p>
            </div>
            <div class="card">
                <h3>App Development</h3>
                <p>High-performance mobile applications for Android and iOS.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2 class="section-title">Contact Us</h2>
        <p style="margin-bottom: 20px;">Address: Shastri Nagar, Sainik School First Gate, Vijayapura, Karnataka, India</p>
        
        <form id="contactForm">
            <!-- Web3Forms Access Key yahan dalein -->
            <input type="hidden" name="access_key" value="7b1a9e9f-1389-42b3-a9ce-333f19a80d04">
            
            <div class="input-group">
                <label>Full Name</label>
                <input type="text" name="name" required placeholder="Enter your full name">
            </div>
            <div class="input-group">
                <label>Mobile Number</label>
                <input type="tel" name="phone" required placeholder="Enter mobile number">
            </div>
            <div class="input-group">
                <label>Email Address</label>
                <input type="email" name="email" required placeholder="Enter email address">
            </div>
            <div class="input-group">
                <label>Message</label>
                <textarea name="message" rows="4" required placeholder="How can we help you?"></textarea>
            </div>
            
            <input type="checkbox" name="botcheck" class="hidden" style="display: none;">

            <button type="submit" class="btn btn-submit">Send Message</button>
            <p id="formStatus"></p>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 MC-SoftTech. All Rights Reserved.</p>
        <p>Email: mallikarjunchougule445@gmail.com</p>
    </footer>

    <!-- JavaScript: Handling Form Submission without Page Reload -->
    <script>
        const form = document.getElementById('contactForm');
        const statusMessage = document.getElementById('formStatus');

        form.addEventListener('submit', function(e) {
            e.preventDefault(); 
            statusMessage.style.color = "blue";
            statusMessage.textContent = "Sending message...";

            const formData = new FormData(form);
            const object = Object.fromEntries(formData);
            const json = JSON.stringify(object);

            fetch('https://api.web3forms.com/submit', {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json',
                    'Accept': 'application/json'
                },
                body: json
            })
            .then(async (response) => {
                let json = await response.json();
                if (response.status == 200) {
                    statusMessage.style.color = "green";
                    statusMessage.textContent = "Success! Your message has been sent to MC-SoftTech.";
                    form.reset();
                } else {
                    console.log(response);
                    statusMessage.style.color = "red";
                    statusMessage.textContent = json.message;
                }
            })
            .catch(error => {
                console.log(error);
                statusMessage.style.color = "red";
                statusMessage.textContent = "Something went wrong! Please try again.";
            });
        });
    </script>
</body>
</html>
