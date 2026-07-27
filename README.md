# electrotech-solutions
Official website for Electrotech Solutions 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ElectroTech Solutions | Powering Your Future</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Custom CSS -->
    <style>
        html {
            scroll-behavior: smooth;
        }

        :root {
            --primary-blue: #0d6efd;
            --dark-blue: #0a429b;
        }
        
        .bg-primary-custom {
            background-color: var(--primary-blue);
        }

        .hero-section {
            background: linear-gradient(rgba(10, 66, 155, 0.85), rgba(10, 66, 155, 0.85)), url('https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 0;
        }

        .floating-whatsapp {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background-color: #25d366;
            color: white;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 8px rgba(0,0,0,0.3);
            z-index: 1000;
            width: 60px;
            height: 60px;
            line-height: 60px;
            transition: all 0.3s ease;
        }

        .floating-whatsapp:hover {
            color: white;
            background-color: #128c7e;
            transform: scale(1.1);
        }

        .card-custom {
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card-custom:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(13, 110, 253, 0.15);
        }

        .map-container {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/94786680839" class="floating-whatsapp" target="_blank" title="Chat on WhatsApp">
        <i class="fab fa-whatsapp"></i>
    </a>

    <!-- Top Contact Bar -->
    <div class="bg-dark text-white py-2">
        <div class="container d-flex justify-content-between align-items-center flex-wrap">
            <div>
                <small class="me-3"><i class="fas fa-phone-alt me-1 text-primary"></i> 078 668 0839 / 076 768 0839</small>
                <small><i class="fas fa-envelope me-1 text-primary"></i> electrotechsolutions3@gmail.com</small>
            </div>
            <div>
                <a href="https://www.facebook.com/profile.php?id=61581548343175" target="_blank" class="text-white me-2"><i class="fab fa-facebook fs-5"></i></a>
            </div>
        </div>
    </div>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white sticky-top shadow-sm">
        <div class="container">
            <a class="navbar-brand text-decoration-none" href="#">
                <h3 class="fw-bold text-primary m-0">ElectroTech <span class="text-dark">Solutions</span></h3>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto fw-semibold">
                    <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact Us</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Banner -->
    <section id="home" class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 fw-bold mb-3">Powering Your Future with Reliable Electrical Solutions</h1>
            <p class="lead mb-4">High-quality electrical products and professional solutions for residential, commercial, and industrial applications.</p>
            <div>
                <a href="tel:0786680839" class="btn btn-primary btn-lg me-2 mb-2"><i class="fas fa-phone-alt me-1"></i> Call Now</a>
                <a href="https://wa.me/94786680839" class="btn btn-success btn-lg me-2 mb-2" target="_blank"><i class="fab fa-whatsapp me-1"></i> WhatsApp</a>
                <a href="#contact" class="btn btn-outline-light btn-lg mb-2">Get a Quote</a>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h2 class="fw-bold text-primary mb-3">Welcome to ElectroTech Solutions</h2>
                    <p class="text-muted">We provide high-quality electrical products and professional solutions for residential, commercial, and industrial applications. Our commitment is to deliver reliable products, expert support, and excellent customer service.</p>
                    <p class="text-muted">විශ්වාසනීය විදුලි උපකරණ සහ වෘත්තීයමය සේවාවන් ලබාගැනීමට අදම අප හා සම්බන්ධ වන්න.</p>
                </div>
                <div class="col-md-6 text-center">
                    <i class="fas fa-bolt text-primary" style="font-size: 8rem;"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-5 bg-light">
        <div class="container">
            <h2 class="fw-bold text-center text-primary mb-4">Our Products</h2>
            <div class="row g-4">
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">MCB</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">MCCB</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">RCCB / RCBO</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">SPD</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">ATS Panels</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">DB Panels</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">VFD</div></div>
                <div class="col-md-3 col-6"><div class="card p-3 text-center card-custom fw-bold text-dark">Electrical Accessories</div></div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-5">
        <div class="container">
            <h2 class="fw-bold text-center text-primary mb-5">Our Services</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card card-custom p-4 text-center">
                        <i class="fas fa-drafting-compass text-primary mb-3" style="font-size: 2.5rem;"></i>
                        <h5 class="fw-bold">Electrical Panel Design</h5>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card card-custom p-4 text-center">
                        <i class="fas fa-tools text-primary mb-3" style="font-size: 2.5rem;"></i>
                        <h5 class="fw-bold">Installation</h5>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card card-custom p-4 text-center">
                        <i class="fas fa-wrench text-primary mb-3" style="font-size: 2.5rem;"></i>
                        <h5 class="fw-bold">Maintenance</h5>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card card-custom p-4 text-center">
                        <i class="fas fa-industry text-primary mb-3" style="font-size: 2.5rem;"></i>
                        <h5 class="fw-bold">Industrial Electrical Solutions</h5>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card card-custom p-4 text-center">
                        <i class="fas fa-user-tie text-primary mb-3" style="font-size: 2.5rem;"></i>
                        <h5 class="fw-bold">Consultation</h5>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="fw-bold text-center text-primary mb-5">Contact Us</h2>
            <div class="row g-4">
                <div class="col-md-5">
                    <h4 class="fw-bold mb-3">Get in Touch</h4>
                    <p><i class="fas fa-phone-alt text-primary me-2"></i> 078 668 0839 / 076 768 0839</p>
                    <p><i class="fas fa-envelope text-primary me-2"></i> electrotechsolutions3@gmail.com</p>
                    <p><i class="fas fa-map-marker-alt text-primary me-2"></i> 165/A/1, Thenkuttiyawa, Mahakubukkadawala</p>
                    <a href="https://www.facebook.com/profile.php?id=61581548343175" target="_blank" class="btn btn-primary my-2">
                        <i class="fab fa-facebook me-1"></i> Visit Facebook Page
                    </a>
                    
                    <!-- Google Map Embed -->
                    <div class="map-container mt-3">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15814.246419747975!2d79.880000!3d7.750000!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zN8KwNDUnMDAuMCJOIDc5wrA1Mic0OC4wIkU!52e0!3m2!1sen!2slk!4v1620000000000!5m2!1sen!2slk" width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                    </div>
                </div>
                <div class="col-md-7">
                    <form>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Your Name" required>
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Your Email / Phone Number" required>
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="5" placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary w-100 py-2 fw-bold">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p class="m-0">&copy; 2026 ElectroTech Solutions. All Rights Reserved.</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
