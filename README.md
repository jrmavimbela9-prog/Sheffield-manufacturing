<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sheffield Manufacturing | Industrial Engineering & Fabrication Durban</title>
    <meta name="description" content="Sheffield Manufacturing - Premium industrial manufacturing, metal fabrication & engineering solutions in Durban, KZN. B2B supplier for construction, mining & logistics.">
    <meta name="keywords" content="Durban manufacturing company, industrial engineering Durban, metal fabrication South Africa, manufacturing services KZN, B2B industrial suppliers Durban">
    
    <!-- OpenGraph Tags -->
    <meta property="og:title" content="Sheffield Manufacturing | Industrial Engineering Durban">
    <meta property="og:description" content="Precision industrial manufacturing & engineering solutions in Durban, KZN.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.sheffieldmfg.co.za">
    <meta property="og:image" content="https://www.sheffieldmfg.co.za/assets/og-image.jpg">
    
    <!-- Structured Data -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "LocalBusiness",
        "name": "Sheffield Manufacturing",
        "address": {
            "@type": "PostalAddress",
            "addressLocality": "Jacobs",
            "addressRegion": "Durban",
            "addressCountry": "South Africa"
        },
        "telephone": "[PHONE NUMBER]",
        "email": "[EMAIL ADDRESS]",
        "url": "https://www.sheffieldmfg.co.za",
        "description": "Industrial manufacturing and engineering solutions in Durban, KZN"
    }
    </script>
    
    <style>
        :root {
            --primary: #1a237e;
            --primary-dark: #0d1642;
            --secondary: #37474f;
            --accent: #ff6f00;
            --light: #f5f5f5;
            --white: #ffffff;
            --text: #333333;
            --text-light: #666666;
            --border: #e0e0e0;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        /* Navigation */
        .navbar {
            background: var(--white);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            transition: all 0.3s ease;
        }
        
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
            text-decoration: none;
        }
        
        .logo span {
            color: var(--accent);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--text);
            font-weight: 500;
            transition: color 0.3s;
            position: relative;
        }
        
        .nav-links a:hover {
            color: var(--primary);
        }
        
        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent);
            transition: width 0.3s;
        }
        
        .nav-links a:hover::after {
            width: 100%;
        }
        
        .mobile-menu {
            display: none;
            flex-direction: column;
            gap: 5px;
            cursor: pointer;
        }
        
        .mobile-menu span {
            width: 25px;
            height: 3px;
            background: var(--primary);
            transition: all 0.3s;
        }
        
        /* Hero Section */
        .hero {
            margin-top: 70px;
            background: linear-gradient(135deg, var(--primary-dark) 0%, var(--primary) 100%);
            color: var(--white);
            padding: 8rem 2rem 6rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><g fill="%23ffffff" fill-opacity="0.05"><path d="M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z"/></g></g></svg>');
            opacity: 0.3;
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
            animation: fadeInUp 1s ease;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            font-weight: 700;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.25rem;
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        
        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        .btn {
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: inline-block;
        }
        
        .btn-primary {
            background: var(--accent);
            color: var(--white);
        }
        
        .btn-primary:hover {
            background: #e65100;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(255,111,0,0.3);
        }
        
        .btn-secondary {
            background: transparent;
            color: var(--white);
            border: 2px solid var(--white);
        }
        
        .btn-secondary:hover {
            background: var(--white);
            color: var(--primary);
        }
        
        /* Trust Indicators */
        .trust-section {
            background: var(--light);
            padding: 3rem 2rem;
        }
        
        .trust-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .trust-card {
            text-align: center;
            padding: 2rem;
            background: var(--white);
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }
        
        .trust-card:hover {
            transform: translateY(-5px);
        }
        
        .trust-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--primary);
        }
        
        .trust-card h3 {
            font-size: 2rem;
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        
        .trust-card p {
            color: var(--text-light);
        }
        
        /* Services Overview */
        .services-overview {
            padding: 5rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .section-header {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .section-header h2 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 1rem;
        }
        
        .section-header p {
            color: var(--text-light);
            max-width: 600px;
            margin: 0 auto;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            padding: 2rem;
            border: 1px solid var(--border);
            border-radius: 8px;
            transition: all 0.3s;
            background: var(--white);
        }
        
        .service-card:hover {
            border-color: var(--primary);
            box-shadow: 0 5px 20px rgba(26,35,126,0.1);
            transform: translateY(-3px);
        }
        
        .service-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--accent);
        }
        
        .service-card h3 {
            font-size: 1.25rem;
            margin-bottom: 0.5rem;
            color: var(--primary);
        }
        
        .service-card p {
            color: var(--text-light);
            margin-bottom: 1rem;
        }
        
        .service-link {
            color: var(--accent);
            text-decoration: none;
            font-weight: 600;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        /* Industries */
        .industries {
            background: var(--secondary);
            color: var(--white);
            padding: 5rem 2rem;
        }
        
        .industries-container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .industries-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .industry-card {
            text-align: center;
            padding: 2rem;
            background: rgba(255,255,255,0.1);
            border-radius: 8px;
            transition: all 0.3s;
        }
        
        .industry-card:hover {
            background: rgba(255,255,255,0.2);
            transform: translateY(-5px);
        }
        
        .industry-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        
        /* About Preview */
        .about-preview {
            padding: 5rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }
        
        .about-content h2 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 1.5rem;
        }
        
        .about-content p {
            margin-bottom: 1.5rem;
            color: var(--text-light);
        }
        
        .about-features {
            list-style: none;
            margin-top: 2rem;
        }
        
        .about-features li {
            padding: 0.5rem 0;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .about-features li::before {
            content: '✓';
            color: var(--accent);
            font-weight: bold;
        }
        
        .about-image {
            background: var(--light);
            height: 400px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-light);
            font-size: 1.2rem;
        }
        
        /* Projects Preview */
        .projects-preview {
            background: var(--light);
            padding: 5rem 2rem;
        }
        
        .projects-container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .project-card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
        }
        
        .project-image {
            height: 200px;
            background: var(--secondary);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-size: 3rem;
        }
        
        .project-info {
            padding: 1.5rem;
        }
        
        .project-info h3 {
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        
        .project-info p {
            color: var(--text-light);
            font-size: 0.9rem;
        }
        
        .project-tag {
            display: inline-block;
            padding: 0.25rem 0.75rem;
            background: var(--primary);
            color: var(--white);
            border-radius: 20px;
            font-size: 0.8rem;
            margin-top: 1rem;
        }
        
        /* Contact Preview */
        .contact-preview {
            padding: 5rem 2rem;
            text-align: center;
            background: var(--primary);
            color: var(--white);
        }
        
        .contact-preview h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .contact-preview p {
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        /* Footer */
        footer {
            background: var(--primary-dark);
            color: var(--white);
            padding: 3rem 2rem 1rem;
        }
        
        .footer-container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
        }
        
        .footer-section h3 {
            margin-bottom: 1.5rem;
            color: var(--accent);
        }
        
        .footer-section p, .footer-section a {
            color: rgba(255,255,255,0.8);
            text-decoration: none;
            line-height: 2;
        }
        
        .footer-section a:hover {
            color: var(--accent);
        }
        
        .footer-bottom {
            max-width: 1200px;
            margin: 3rem auto 0;
            padding-top: 2rem;
            border-top: 1px solid rgba(255,255,255,0.1);
            text-align: center;
            color: rgba(255,255,255,0.6);
        }
        
        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease;
        }
        
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .mobile-menu {
                display: flex;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .about-preview {
                grid-template-columns: 1fr;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <a href="#" class="logo">Sheffield<span>Manufacturing</span></a>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#industries">Industries</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="mobile-menu">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Industrial Manufacturing & Engineering Solutions in Durban</h1>
            <p>Precision engineering, reliable fabrication, and industrial excellence for South Africa's leading B2B sectors</p>
            <div class="hero-buttons">
                <a href="#contact" class="btn btn-primary">Request a Quote</a>
                <a href="#contact" class="btn btn-secondary">Contact Us</a>
            </div>
        </div>
    </section>

    <!-- Trust Indicators -->
    <section class="trust-section">
        <div class="trust-grid">
            <div class="trust-card fade-in">
                <div class="trust-icon">🏭</div>
                <h3>[YEARS]</h3>
                <p>Years of Industrial Excellence</p>
            </div>
            <div class="trust-card fade-in">
                <div class="trust-icon">⚙️</div>
                <h3>[NUMBER]</h3>
                <p>Industries Served</p>
            </div>
            <div class="trust-card fade-in">
                <div class="trust-icon">✓</div>
                <h3>[PERCENTAGE]</h3>
                <p>On-Time Delivery Rate</p>
            </div>
            <div class="trust-card fade-in">
                <div class="trust-icon">🏆</div>
                <h3>[CERTIFICATION]</h3>
                <p>Quality Certified</p>
            </div>
        </div>
    </section>

    <!-- Services Overview -->
    <section id="services" class="services-overview">
        <div class="section-header fade-in">
            <h2>Our Industrial Capabilities</h2>
            <p>Comprehensive manufacturing and engineering solutions tailored for large-scale B2B operations</p>
        </div>
        <div class="services-grid">
            <div class="service-card fade-in">
                <div class="service-icon">🔧</div>
                <h3>Metal Fabrication</h3>
                <p>Precision cutting, welding, and forming of structural steel and metal components for industrial applications.</p>
                <a href="#" class="service-link">Learn More →</a>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🏗️</div>
                <h3>Industrial Manufacturing</h3>
                <p>Full-scale production of industrial equipment, machinery parts, and custom manufacturing solutions.</p>
                <a href="#" class="service-link">Learn More →</a>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">📐</div>
                <h3>Engineering Support</h3>
                <p>Technical consulting, CAD design, prototyping, and engineering optimization for your projects.</p>
                <a href="#" class="service-link">Learn More →</a>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🔩</div>
                <h3>Custom Production</h3>
                <p>Tailored manufacturing solutions designed to meet your exact specifications and production requirements.</p>
                <a href="#" class="service-link">Learn More →</a>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🛠️</div>
                <h3>Maintenance & Repairs</h3>
                <p>Industrial equipment servicing, emergency repairs, and preventive maintenance programs.</p>
                <a href="#" class="service-link">Learn More →</a>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">📦</div>
                <h3>Bulk Industrial Supply</h3>
                <p>High-volume manufacturing and consistent supply chain solutions for large-scale operations.</p>
                <a href="#" class="service-link">Learn More →</a>
            </div>
        </div>
    </section>

    <!-- Industries Served -->
    <section id="industries" class="industries">
        <div class="industries-container">
            <div class="section-header fade-in">
                <h2 style="color: white;">Industries We Serve</h2>
                <p style="color: rgba(255,255,255,0.8);">Trusted manufacturing partner across key South African industrial sectors</p>
            </div>
            <div class="industries-grid">
                <div class="industry-card fade-in">
                    <div class="industry-icon">🏗️</div>
                    <h3>Construction</h3>
                    <p>Structural steel, reinforcement, and building materials</p>
                </div>
                <div class="industry-card fade-in">
                    <div class="industry-icon">🚛</div>
                    <h3>Logistics & Transport</h3>
                    <p>Fleet maintenance, trailer fabrication, and components</p>
                </div>
                <div class="industry-card fade-in">
                    <div class="industry-icon">⛏️</div>
                    <h3>Mining Supply Chain</h3>
                    <p>Heavy-duty equipment, wear parts, and processing components</p>
                </div>
                <div class="industry-card fade-in">
                    <div class="industry-icon">⚗️</div>
                    <h3>Chemical Industry</h3>
                    <p>Tanks, piping systems, and corrosion-resistant fabrication</p>
                </div>
                <div class="industry-card fade-in">
                    <div class="industry-icon">🏭</div>
                    <h3>Manufacturing Sector</h3>
                    <p>OEM parts, tooling, and production line components</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Preview -->
    <section id="about" class="about-preview">
        <div class="about-content fade-in">
            <h2>Engineering Excellence in Durban</h2>
            <p>Sheffield Manufacturing is a leading industrial engineering company based in Jacobs, Durban. We specialize in delivering precision manufacturing solutions that meet the highest standards of quality and reliability.</p>
            <p>Our mission is to provide precision, reliability, and industrial excellence to every project we undertake. We envision becoming Durban's most trusted manufacturing partner for large-scale industrial operations.</p>
            <ul class="about-features">
                <li>Skilled workforce with specialized industrial expertise</li>
                <li>Industrial-grade equipment and modern facilities</li>
                <li>Rigorous quality assurance processes</li>
                <li>Commitment to on-time delivery</li>
                <li>Tender-ready documentation and compliance</li>
            </ul>
            <a href="#contact" class="btn btn-primary" style="margin-top: 2rem;">Work With Us</a>
        </div>
        <div class="about-image fade-in">
            [FACILITY IMAGE PLACEHOLDER]
        </div>
    </section>

    <!-- Projects Preview -->
    <section id="projects" class="projects-preview">
        <div class="projects-container">
            <div class="section-header fade-in">
                <h2>Featured Projects</h2>
                <p>Demonstrating our capability to deliver complex industrial solutions across KZN</p>
            </div>
            <div class="projects-grid">
                <div class="project-card fade-in">
                    <div class="project-image">🏗️</div>
                    <div class="project-info">
                        <h3>Industrial Fabrication Project</h3>
                        <p>Large-scale structural steel fabrication for major Durban construction client</p>
                        <span class="project-tag">Durban</span>
                    </div>
                </div>
                <div class="project-card fade-in">
                    <div class="project-image">⚙️</div>
                    <div class="project-info">
                        <h3>Custom Engineering Solution</h3>
                        <p>Specialized machinery components designed for KZN manufacturing facility</p>
                        <span class="project-tag">KZN Client</span>
                    </div>
                </div>
                <div class="project-card fade-in">
                    <div class="project-image">🔩</div>
                    <div class="project-info">
                        <h3>Bulk Production Run</h3>
                        <p>High-volume manufacturing of standardized industrial parts with consistent quality</p>
                        <span class="project-tag">Industrial</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Preview -->
    <section id="contact" class="contact-preview">
        <div class="fade-in">
            <h2>Ready to Start Your Project?</h2>
            <p>Contact Sheffield Manufacturing for quotes, tenders, and industrial partnerships</p>
            <a href="#contact-page" class="btn btn-primary" style="font-size: 1.2rem; padding: 1.2rem 3rem;">Request a Quote Within 24 Hours</a>
            <div class="contact-info">
                <div class="contact-item">
                    <span>📞</span>
                    <span>[PHONE NUMBER]</span>
                </div>
                <div class="contact-item">
                    <span>✉️</span>
                    <span>[EMAIL ADDRESS]</span>
                </div>
                <div class="contact-item">
                    <span>📍</span>
                    <span>Jacobs, Durban, South Africa</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-container">
            <div class="footer-section">
                <h3>Sheffield Manufacturing</h3>
                <p>Precision engineering and industrial manufacturing solutions in Durban, KZN. Serving South Africa's leading B2B sectors with quality and reliability.</p>
            </div>
            <div class="footer-section">
                <h3>Quick Links</h3>
                <p><a href="#home">Home</a></p>
                <p><a href="#about">About Us</a></p>
                <p><a href="#services">Services</a></p>
                <p><a href="#projects">Projects</a></p>
                <p><a href="#contact">Contact</a></p>
            </div>
            <div class="footer-section">
                <h3>Services</h3>
                <p><a href="#">Metal Fabrication</a></p>
                <p><a href="#">Industrial Manufacturing</a></p>
                <p><a href="#">Engineering Support</a></p>
                <p><a href="#">Custom Production</a></p>
                <p><a href="#">Maintenance & Repairs</a></p>
            </div>
            <div class="footer-section">
                <h3>Contact Info</h3>
                <p>📞 [PHONE NUMBER]</p>
                <p>✉️ [EMAIL ADDRESS]</p>
                <p>📍 Jacobs, Durban<br>South Africa</p>
                <p>🕐 Mon-Fri: 08:00 - 17:00</p>
            </div>
        </div>
        <div class="footer-bottom">
            <p>© 2024 Sheffield Manufacturing. All rights reserved. | Industrial Engineering Durban</p>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.querySelector('.mobile-menu').addEventListener('click', function() {
            document.querySelector('.nav-links').classList.toggle('active');
        });
        
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
        
        // Scroll animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });
        
        // Navbar background on scroll
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 50) {
                navbar.style.boxShadow = '0 2px 20px rgba(0,0,0,0.1)';
            } else {
                navbar.style.boxShadow = '0 2px 10px rgba(0,0,0,0.1)';
            }
        });
    </script>
</body>
</html>
