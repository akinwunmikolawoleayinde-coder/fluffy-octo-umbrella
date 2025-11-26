<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DeeCouture-Chic | Luxury Fashion House</title>
  <meta name="description" content="DeeCouture-Chic by Damilola offers elegant and sustainable fashion designs. Explore our gallery and get in touch for more">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  
  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "name": "DeeCouture-Chic by Damilola",
      "url": "YOUR_WEBSITE_URL_HERE", 
      "logo": "URL_TO_YOUR_LOGO_IMAGE",
      "contactPoint": {
        "@type": "ContactPoint",
        "telephone": "+2348078170196",
        "contactType": "Customer Service",
        "email": "Akinwunmidamilola67@gmail.com"
      },
      "sameAs": [
        "https://www.facebook.com/DEECOUTURE-Chic",
        "https://www.instagram.com/DEECOUTURE-Chic",
        "https://www.twitter.com/DEECOUTURE-Chic"
      ]
    }
  </script>
  <style>
    :root {
      --bg-primary: #0a0a0a;
      --bg-secondary: #111;
      --accent-gold: #cfa144;
      --text-light: #fff;
      --text-muted: #aaa;
      --font-main: 'Roboto', sans-serif;
      --font-heading: 'Playfair Display', serif;
    }

    /* Base */
    body {
      background: var(--bg-primary);
      color: var(--text-light);
      font-family: var(--font-main);
      margin: 0;
      line-height: 1.6;
    }

    /* Header */
    header {
      background: var(--bg-secondary);
      padding: 2rem 0;
      text-align: center;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    h1 {
      font-family: var(--font-heading);
      font-size: 2.5rem;
      margin: 0;
      letter-spacing: 0.05em;
    }

    /* Navigation */
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0.5rem 0 0;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }
    nav a {
      color: var(--text-light);
      text-decoration: none;
      font-weight: 500;
      position: relative;
      transition: color 0.3s;
    }
    nav a::after {
      content: '';
      position: absolute;
      bottom: -4px;
      left: 0;
      width: 0;
      height: 2px;
      background: var(--accent-gold);
      transition: width 0.3s;
    }
    nav a:hover,
    nav a.active {
      color: var(--accent-gold);
    }
    nav a:hover::after,
    nav a.active::after {
      width: 100%;
    }

    /* Sections */
    section {
      max-width: 1000px;
      margin: 3rem auto;
      padding: 0 1rem;
    }
    h2 {
      font-family: var(--font-heading);
      color: var(--accent-gold);
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }
    p {
      color: var(--text-muted);
    }

    /* Buttons */
    a.button {
      display: inline-block;
      padding: 0.8rem 2rem;
      background: transparent;
      border: 1px solid var(--accent-gold);
      color: var(--accent-gold);
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s;
    }
    a.button:hover {
      background: var(--accent-gold);
      color: var(--bg-primary);
    }

    /* Images */
    img {
      width: 100%;
      max-width: 600px;
      display: block;
      margin: 2rem auto;
      border: 1px solid rgba(255,255,255,0.1);
    }

    /* Gallery */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .gallery-item {
      position: relative;
      overflow: hidden;
      border: 1px solid rgba(255,255,255,0.1);
      
      /* Fade-in Animation Start State (Inherited) */
      transition: all 0.7s ease-out;
    }
    
    .gallery-item:hover {
      transform: translateY(-5px);
    }
    .gallery-item img {
      width: 100%;
      height: 300px; 
      object-fit: cover;
      margin: 0;
    }

    /* SCROLL REVEAL STYLES (Applies to .gallery-item and .reveal) */
    .gallery-item, .reveal {
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.7s ease-out;
    }

    /* SCROLL REVEAL ACTIVE STATE */
    .gallery-item.fade-in, .reveal.fade-in {
        opacity: 1;
        transform: translateY(0);
    }
    

    /* Footer */
    footer {
      background: var(--bg-secondary);
      padding: 2rem 0;
      text-align: center;
      border-top: 1px solid rgba(255,255,255,0.1);
    }
    footer p {
      margin: 0 0 1rem;
    }
    footer ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
    }
    footer a {
      color: var(--text-muted);
      text-decoration: none;
      transition: color 0.3s;
    }
    footer a:hover {
      color: var(--accent-gold);
    }

    /* Back to Top Button Styling */
    #backToTopBtn {
        display: none; /* Hidden by default */
        position: fixed; 
        bottom: 20px; 
        right: 30px; 
        z-index: 99; 
        border: none; 
        outline: none; 
        background-color: var(--accent-gold); 
        color: var(--bg-primary); 
        cursor: pointer; 
        padding: 15px; 
        border-radius: 4px;
        font-size: 18px;
        font-weight: bold;
        opacity: 0.8;
        transition: opacity 0.3s;
    }

    #backToTopBtn:hover {
        opacity: 1;
    }

    /* Responsive tweak */
    @media (max-width: 768px) {
      nav ul { 
        flex-direction: column;
        gap: 1rem; 
      }
      h1 { font-size: 2rem; }
      .gallery {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>DeeCouture-Chic by Damilola</h1>
    <nav>
      <ul>
        <li><a href="#about" class="active">About</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero">
      <h2>Elegant & Sustainable Fashion</h2>
      <p>Check out our latest collection!</p>
      <a href="#gallery" class="button">View Collection</a>
    </section>

    <section id="about" class="reveal">
      <h2>About DeeCouture-Chic</h2>
      <p>Welcome to my world of fashion! I'm Damilola, a passionate designer creating garments that exude elegance and sophistication.</p>
      <ul>
        <li>As a fashion designer, I draw inspiration from the intersection of art, culture, and technology.</li>
        <li>My designs are guided by a passion for sustainability and a commitment to creating garments that are both beautiful and responsible.</li>
        <li>With a keen eye for detail and a love of experimentation, I push the boundaries of fashion to create truly unique and innovative designs.</li>
      </ul>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <p>Explore our latest fashion creations and designs.</p>
      <div class="gallery">
        <div class="gallery-item">
          <img src="https://i.imgur.com/jjElYdQ.jpeg" alt="DeeCouture-Chic Fashion Design 1" width="300" height="300" loading="lazy">
        </div>
        <div class="gallery-item">
          <img src="https://i.imgur.com/KUw7zGQ.jpeg" alt="DeeCouture-Chic Fashion Design 2" width="300" height="300" loading="lazy">
        </div>
        <div class="gallery-item">
          <img src="https://i.imgur.com/c5gkjlb.jpeg" alt="DeeCouture-Chic Fashion Design 3" width="300" height="300" loading="lazy">
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>If you wish to get in touch, please reach us through the following methods:</p>
      <ul>
        <li>Phone: <a href="tel:08078170196">08078170196</a></li>
        <li>Email: <a href="mailto:Akinwunmidamilola67@gmail.com">Akinwunmidamilola67@gmail.com</a></li>
      </ul>
      <a class="button" href="mailto:Akinwunmidamilola67@gmail.com">Get In Touch</a>
    </section>
  </main>

  <footer>
    <p>Follow Us:</p>
    <ul>
      <li><a href="https://www.facebook.com/DEECOUTURE-Chic" target="_blank">Facebook</a></li>
      <li><a href="https://www.instagram.com/DEECOUTURE-Chic" target="_blank">Instagram</a></li>
      <li><a href="https://www.twitter.com/DEECOUTURE-Chic" target="_blank">Twitter</a></li>
    </ul>
    <p>&copy; 2023 DeeCouture-Chic by Damilola. All rights reserved.</p>
  </footer>

  <script>
    document.addEventListener('DOMContentLoaded', function() {
        
        // 1. Smooth Scrolling and Active Navigation Link Logic
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetSection = document.querySelector(targetId);
                
                if (targetSection) {
                    window.scrollTo({
                        top: targetSection.offsetTop - 20,
                        behavior: 'smooth'
                    });
                }
                
                // Update the 'active' class
                document.querySelectorAll('nav a').forEach(link => {
                    link.classList.remove('active');
                });
                this.classList.add('active');
            });
        });

        // 2. Scroll-to-Top Button Functionality
        const backToTopBtn = document.createElement('button');
        backToTopBtn.textContent = '↑ Top'; 
        backToTopBtn.id = 'backToTopBtn';
        document.body.appendChild(backToTopBtn);

        const toggleBackToTopButton = () => {
            if (window.scrollY > 300) { 
                backToTopBtn.style.display = 'block';
            } else {
                backToTopBtn.style.display = 'none';
            }
        };

        backToTopBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        window.addEventListener('scroll', toggleBackToTopButton);
        toggleBackToTopButton(); // Initialize button state

        // 3. Scroll Animation for Gallery and Reveal Items
        const elementsToReveal = document.querySelectorAll('.gallery-item, .reveal');

        const observer = new IntersectionObserver(entries => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                    observer.unobserve(entry.target);
                }
            });
        }, {
            threshold: 0.2 
        });

        elementsToReveal.forEach(item => {
            observer.observe(item);
        });

    });
  </script>
</body>
</html>
