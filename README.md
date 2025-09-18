<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adil Zulhidan - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Adil Zulhidan</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero-section text-white text-center d-flex align-items-center">
        <div class="container" data-aos="fade-up">
            <h1 class="display-3 fw-bold">Adil Zulhidan</h1>
            <p class="lead my-4">A passionate developer building creative and efficient solutions.</p>
            <a href="#projects" class="btn btn-brand btn-lg">View My Work <i class="bi bi-arrow-right-short"></i></a>
        </div>
    </header>

    <section id="about" class="py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6" data-aos="fade-right">
                    <img src="image/Gemini_Generated_Image_uisg27uisg27uisg.png" class="img-fluid rounded-circle shadow-lg" style="width: 200px; height: 200px; object-fit: cover;">
                </div>
                <div class="col-lg-6" data-aos="fade-left" data-aos-delay="200">
                    <h2 class="display-5 fw-bold mb-3">About Me</h2>
                    <p class="text-muted">Hello! I'm Adil Zulhidan, specializing in modern web development. I focus on creating clean, elegant, and high-performing websites and applications. My passion lies in turning ideas into tangible, user-friendly products.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="bg-light py-5">
        <div class="container">
            <div class="text-center" data-aos="fade-up">
                <h2 class="display-5 fw-bold">My Projects</h2>
                <p class="text-muted mb-5">Here are a few projects I've worked on.</p>
            </div>
            <div class="row">
                <div class="col-md-4 mb-4" data-aos="fade-up">
                    <div class="card project-card h-100">
                        <img src="https://via.placeholder.com/400x300" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Project One</h5>
                            <p class="card-text">A brief but engaging description of what this project is all about.</p>
                        </div>
                        <div class="card-footer">
                            <a href="#" class="btn btn-sm btn-outline-primary">View Details</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="card project-card h-100">
                        <img src="https://via.placeholder.com/400x300" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">CV</h5>
                            <p class="card-text">A brief but engaging description of what this project is all about.</p>
                        </div>
                        <div class="card-footer">
                            <a href="#" class="btn btn-sm btn-outline-primary">View Details</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4" data-aos="fade-up" data-aos-delay="400">
                    <div class="card project-card h-100">
                        <img src="https://via.placeholder.com/400x300" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Certificate</h5>
                            <p class="card-text">Sertifikat Ethical Hacker dari Netacad Cisco.</p>
                        </div>
                        <div class="card-footer">
                            <a href="certificate.php" class="btn btn-sm btn-outline-primary">View Details</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <div class="text-center" data-aos="fade-up">
                <h2 class="display-5 fw-bold">Get In Touch</h2>
                <p class="text-muted mb-5">Have a question or want to work together? Let's talk.</p>
            </div>
            <div class="row justify-content-center">
                <div class="col-lg-6" data-aos="fade-up" data-aos-delay="200">
                    <form action="#" method="POST">
                        <div class="mb-3">
                            <input type="text" class="form-control" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" name="email" placeholder="Your Email" required>
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" name="message" rows="5" placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-brand w-100">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-dark text-white text-center py-4">
        <div class="container">
            <p class="mb-0">&copy; <?php echo date('Y'); ?> Adil Zulhidan. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true,
        });
    </script>
</body>
</html>
