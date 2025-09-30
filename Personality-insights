<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personality Insights | MBTI Resources & Community</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            /* Sophisticated neutral palette with subtle accents */
            --primary: #2d3748; /* Charcoal */
            --primary-light: #4a5568;
            --secondary: #6b46c1; /* Muted purple */
            --accent: #e2e8f0; /* Light gray */
            --light: #f8fafc; /* Off-white */
            --dark: #1a202c; /* Deep charcoal */
            --text: #2d3748;
            --text-light: #718096;
            --border: #e2e8f0;
            --success: #48bb78;
            --warning: #ecc94b;
            --mbti-blue: #4299e1;
            --mbti-green: #48bb78;
            --mbti-yellow: #ecc94b;
            --mbti-red: #f56565;
            
            /* Gradients */
            --gradient-primary: linear-gradient(135deg, #6b46c1, #4a5568);
            --gradient-subtle: linear-gradient(135deg, #f8fafc, #e2e8f0);
            
            /* Typography */
            --font-main: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            --font-heading: 'Playfair Display', serif;
            --font-display: 'Inter', sans-serif;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: var(--light);
            color: var(--text);
            font-family: var(--font-main);
            line-height: 1.7;
            font-size: 16px;
            overflow-x: hidden;
        }
        
        /* Header & Navigation */
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 2px 20px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid var(--border);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.2rem 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-family: var(--font-display);
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary);
            text-decoration: none;
            transition: all 0.3s ease;
        }
        
        .logo:hover {
            color: var(--secondary);
        }
        
        .logo-icon {
            background: var(--secondary);
            color: white;
            width: 45px;
            height: 45px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.3rem;
            box-shadow: 0 4px 12px rgba(107, 70, 193, 0.3);
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        nav a {
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            padding: 0.6rem 0;
            position: relative;
            transition: all 0.3s ease;
            font-size: 1.05rem;
        }
        
        nav a:hover {
            color: var(--secondary);
        }
        
        nav a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--secondary);
            border-radius: 2px;
            transition: width 0.3s ease;
        }
        
        nav a:hover::after {
            width: 100%;
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            color: var(--primary);
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            background: var(--gradient-subtle);
            padding: 6rem 0 4rem;
            margin-bottom: 3rem;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 Q50,20 100,0 L100,100 Q50,80 0,100 Z" fill="rgba(107, 70, 193, 0.05)"/></svg>');
            background-size: cover;
            opacity: 0.7;
        }
        
        .hero-content {
            position: relative;
            max-width: 700px;
            margin: 0 auto;
            text-align: center;
            z-index: 2;
        }
        
        .hero h1 {
            font-family: var(--font-heading);
            font-size: 3.2rem;
            margin-bottom: 1.5rem;
            color: var(--primary-dark);
            line-height: 1.2;
            font-weight: 600;
        }
        
        .hero p {
            font-size: 1.25rem;
            color: var(--text-light);
            margin-bottom: 2.5rem;
            max-width: 650px;
            margin-left: auto;
            margin-right: auto;
            font-weight: 300;
        }
        
        .hero-buttons {
            display: flex;
            justify-content: center;
            gap: 1.2rem;
            margin-top: 1.5rem;
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background: var(--secondary);
            color: white;
            padding: 0.9rem 2.2rem;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 1.05rem;
            box-shadow: 0 6px 20px rgba(107, 70, 193, 0.25);
            font-family: var(--font-display);
        }
        
        .btn:hover {
            background: #5a3ca8;
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(107, 70, 193, 0.35);
        }
        
        .btn-outline {
            background: transparent;
            border: 2px solid var(--secondary);
            color: var(--secondary);
        }
        
        .btn-outline:hover {
            background: var(--secondary);
            color: white;
        }
        
        .btn i {
            margin-left: 0.6rem;
            transition: transform 0.3s ease;
        }
        
        .btn:hover i {
            transform: translateX(3px);
        }
        
        /* Section Styling */
        .section {
            padding: 5rem 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3.5rem;
            position: relative;
        }
        
        .section-title h2 {
            font-family: var(--font-heading);
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 1.2rem;
            font-weight: 600;
        }
        
        .section-title p {
            color: var(--text-light);
            max-width: 650px;
            margin: 0 auto;
            font-size: 1.1rem;
            font-weight: 300;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -18px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--secondary);
            border-radius: 2px;
        }
        
        /* MBTI Overview Section */
        .mbti-overview {
            background: white;
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            margin-bottom: 4rem;
        }
        
        .mbti-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .mbti-card {
            background: var(--light);
            border-radius: 16px;
            padding: 2rem;
            text-align: center;
            transition: all 0.3s ease;
            border: 1px solid var(--border);
        }
        
        .mbti-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.12);
            border-color: rgba(107, 70, 193, 0.2);
        }
        
        .mbti-icon {
            width: 70px;
            height: 70px;
            background: var(--secondary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1.5rem;
            color: white;
            font-size: 1.8rem;
        }
        
        .mbti-card h3 {
            font-family: var(--font-display);
            margin-bottom: 1rem;
            color: var(--primary);
        }
        
        .mbti-card p {
            color: var(--text-light);
            font-size: 0.95rem;
            font-weight: 300;
        }
        
        /* Products Section */
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 2.8rem;
        }
        
        .product-card {
            background: white;
            border-radius: 18px;
            overflow: hidden;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            transition: all 0.4s ease;
            border: 1px solid var(--border);
            position: relative;
            overflow: visible;
        }
        
        .product-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: var(--secondary);
            transform: scaleX(0);
            transform-origin: right;
            transition: transform 0.4s ease;
        }
        
        .product-card:hover::before {
            transform: scaleX(1);
            transform-origin: left;
        }
        
        .product-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
        }
        
        .product-img {
            height: 220px;
            background: linear-gradient(135deg, #f0f4f8, #e6eef5);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3.2rem;
            color: var(--secondary);
            position: relative;
            overflow: hidden;
        }
        
        .product-img::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="%236b46c1" opacity="0.1"/><circle cx="80" cy="30" r="1.5" fill="%236b46c1" opacity="0.1"/><circle cx="50" cy="70" r="2.5" fill="%236b46c1" opacity="0.1"/></svg>');
            background-size: 300px;
        }
        
        .product-info {
            padding: 2rem;
        }
        
        .product-type {
            display: inline-block;
            background: var(--accent);
            color: var(--primary);
            padding: 0.35rem 1rem;
            border-radius: 30px;
            font-size: 0.88rem;
            margin-bottom: 1rem;
            font-weight: 600;
            letter-spacing: 0.5px;
        }
        
        .product-title {
            font-family: var(--font-display);
            font-size: 1.4rem;
            margin-bottom: 0.6rem;
            color: var(--primary);
            font-weight: 700;
        }
        
        .product-author {
            color: var(--text-light);
            font-style: italic;
            margin-bottom: 1.2rem;
            display: block;
            font-weight: 300;
        }
        
        .product-price {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--secondary);
            margin-bottom: 1.4rem;
            font-family: var(--font-display);
        }
        
        .mbti-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem;
            margin-bottom: 1.5rem;
        }
        
        .mbti-badge {
            display: inline-block;
            padding: 0.3rem 0.9rem;
            border-radius: 30px;
            font-size: 0.82rem;
            font-weight: 600;
            color: white;
            font-family: var(--font-display);
            letter-spacing: 0.3px;
        }
        
        .mbti-nt { background: var(--mbti-blue); }
        .mbti-nf { background: var(--mbti-green); }
        .mbti-sj { background: var(--mbti-yellow); color: var(--dark); }
        .mbti-sp { background: var(--mbti-red); }
        
        /* Blog Section */
        .blog-container {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 3.5rem;
        }
        
        .blog-posts {
            display: flex;
            flex-direction: column;
            gap: 3rem;
        }
        
        .blog-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            transition: all 0.3s ease;
            border: 1px solid var(--border);
        }
        
        .blog-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 35px rgba(0,0,0,0.12);
        }
        
        .blog-img {
            height: 240px;
            background: linear-gradient(135deg, #f0f4f8, #e6eef5);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--secondary);
            font-size: 3.8rem;
            position: relative;
            overflow: hidden;
        }
        
        .blog-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .blog-content {
            padding: 2.2rem;
        }
        
        .blog-meta {
            display: flex;
            gap: 1.5rem;
            color: var(--text-light);
            font-size: 0.95rem;
            margin-bottom: 1.2rem;
            font-weight: 300;
        }
        
        .blog-meta span {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .blog-title {
            font-family: var(--font-heading);
            font-size: 1.8rem;
            margin-bottom: 1.2rem;
            color: var(--primary);
            font-weight: 600;
            line-height: 1.3;
        }
        
        .blog-excerpt {
            color: var(--text-light);
            margin-bottom: 1.8rem;
            line-height: 1.8;
            font-weight: 300;
        }
        
        .blog-read-more {
            color: var(--secondary);
            font-weight: 600;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 0.6rem;
            transition: all 0.3s ease;
            font-family: var(--font-display);
        }
        
        .blog-read-more:hover {
            gap: 0.9rem;
            color: #5a3ca8;
        }
        
        /* Blog Sidebar */
        .blog-sidebar {
            display: flex;
            flex-direction: column;
            gap: 2.5rem;
        }
        
        .sidebar-widget {
            background: white;
            border-radius: 18px;
            padding: 2rem;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            border: 1px solid var(--border);
        }
        
        .sidebar-title {
            font-family: var(--font-heading);
            font-size: 1.5rem;
            margin-bottom: 1.8rem;
            color: var(--primary);
            padding-bottom: 0.9rem;
            border-bottom: 2px solid var(--accent);
            font-weight: 600;
        }
        
        .categories-list, .recent-posts-list {
            list-style: none;
        }
        
        .categories-list li, .recent-posts-list li {
            padding: 0.7rem 0;
            border-bottom: 1px solid var(--accent);
        }
        
        .categories-list li:last-child, .recent-posts-list li:last-child {
            border-bottom: none;
        }
        
        .categories-list a, .recent-posts-list a {
            color: var(--text);
            text-decoration: none;
            display: flex;
            justify-content: space-between;
            transition: all 0.3s ease;
            font-weight: 400;
        }
        
        .categories-list a:hover, .recent-posts-list a:hover {
            color: var(--secondary);
            padding-left: 5px;
        }
        
        .search-box {
            display: flex;
            margin-top: 1rem;
        }
        
        .search-box input {
            flex: 1;
            padding: 0.9rem 1.4rem;
            border: 1px solid var(--border);
            border-radius: 30px 0 0 30px;
            outline: none;
            font-size: 1rem;
            background: var(--accent);
            font-family: var(--font-main);
        }
        
        .search-box button {
            background: var(--secondary);
            color: white;
            border: none;
            padding: 0.9rem 1.6rem;
            border-radius: 0 30px 30px 0;
            cursor: pointer;
            transition: background 0.3s ease;
            font-family: var(--font-display);
            font-weight: 600;
        }
        
        .search-box button:hover {
            background: #5a3ca8;
        }
        
        /* Testimonials Section */
        .testimonials {
            background: var(--gradient-subtle);
            padding: 5rem 0;
            margin: 4rem 0;
            border-radius: 25px;
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2.5rem;
            margin-top: 2.5rem;
        }
        
        .testimonial-card {
            background: white;
            border-radius: 18px;
            padding: 2.5rem;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            position: relative;
        }
        
        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 4rem;
            color: var(--secondary);
            opacity: 0.1;
            font-family: var(--font-heading);
            line-height: 1;
        }
        
        .testimonial-content {
            margin-bottom: 1.8rem;
            font-style: italic;
            color: var(--text);
            font-weight: 300;
            line-height: 1.8;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        
        .author-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--secondary);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: 600;
            font-size: 1.2rem;
        }
        
        .author-info h4 {
            color: var(--primary);
            margin-bottom: 0.2rem;
        }
        
        .author-info p {
            color: var(--text-light);
            font-size: 0.9rem;
        }
        
        /* Footer */
        footer {
            background: var(--primary);
            color: white;
            padding: 5rem 0 2.5rem;
            margin-top: 3rem;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 3rem;
        }
        
        .footer-column h3 {
            font-family: var(--font-heading);
            font-size: 1.6rem;
            margin-bottom: 2rem;
            position: relative;
            padding-bottom: 0.8rem;
            font-weight: 600;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background: var(--secondary);
        }
        
        .footer-column p {
            color: #a0aec0;
            margin-bottom: 1.8rem;
            line-height: 1.8;
            font-weight: 300;
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 1rem;
        }
        
        .footer-column a {
            color: #a0aec0;
            text-decoration: none;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 0.9rem;
            font-weight: 400;
        }
        
        .footer-column a:hover {
            color: var(--secondary);
            transform: translateX(3px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 2.5rem;
            border-top: 1px solid #2d3748;
            color: #a0aec0;
            font-size: 1rem;
            font-weight: 300;
        }
        
        /* Page Navigation */
        .page-nav {
            display: flex;
            justify-content: center;
            gap: 0.5rem;
            margin-top: 3rem;
        }
        
        .page-nav a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: white;
            color: var(--primary);
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .page-nav a:hover, .page-nav a.active {
            background: var(--secondary);
            color: white;
            transform: translateY(-3px);
        }
        
        /* Responsive Design */
        @media (max-width: 992px) {
            .blog-container {
                grid-template-columns: 1fr;
            }
            
            .hero h1 {
                font-size: 2.6rem;
            }
            
            .mbti-grid {
                grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            }
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 1.2rem;
            }
            
            nav ul {
                flex-wrap: wrap;
                justify-content: center;
                gap: 1.2rem;
            }
            
            .hero {
                padding: 4rem 0 3rem;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: center;
                gap: 1rem;
            }
            
            .btn {
                width: 85%;
                justify-content: center;
            }
            
            .section {
                padding: 3.5rem 0;
            }
            
            .section-title h2 {
                font-size: 2.1rem;
            }
            
            .mbti-overview {
                padding: 2rem;
            }
        }
        
        @media (max-width: 576px) {
            .products-grid, .testimonials-grid {
                grid-template-columns: 1fr;
            }
            
            .hero-buttons .btn {
                width: 100%;
            }
            
            nav ul {
                gap: 0.8rem;
            }
            
            .page-nav a {
                width: 40px;
                height: 40px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <a href="#" class="logo">
                    <div class="logo-icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <span>Personality Insights</span>
                </a>
                <nav>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#types">Types</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#blog">Blog</a></li>
                        <li><a href="#about">About</a></li>
                    </ul>
                </nav>
                <button class="mobile-menu-btn">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Discover Your Personality Type & Cognitive Functions</h1>
                <p>Explore the fascinating world of MBTI, cognitive functions, and personality psychology with our curated resources, community insights, and expert guidance.</p>
                <div class="hero-buttons">
                    <a href="#products" class="btn">Shop Resources <i class="fas fa-arrow-right"></i></a>
                    <a href="#types" class="btn btn-outline">Explore Types <i class="fas fa-arrow-right"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- MBTI Types Overview -->
    <section class="section" id="types">
        <div class="container">
            <div class="section-title">
                <h2>The 16 Personality Types</h2>
                <p>Understanding the four dimensions that create your unique personality profile</p>
            </div>
            <div class="mbti-overview">
                <div class="mbti-grid">
                    <div class="mbti-card">
                        <div class="mbti-icon" style="background: var(--mbti-blue);">
                            <i class="fas fa-lightbulb"></i>
                        </div>
                        <h3>Intuition (N)</h3>
                        <p>Focuses on patterns, possibilities, and future implications rather than concrete details.</p>
                    </div>
                    <div class="mbti-card">
                        <div class="mbti-icon" style="background: var(--mbti-green);">
                            <i class="fas fa-heart"></i>
                        </div>
                        <h3>Feeling (F)</h3>
                        <p>Makes decisions based on personal values, harmony, and the impact on people.</p>
                    </div>
                    <div class="mbti-card">
                        <div class="mbti-icon" style="background: var(--mbti-yellow);">
                            <i class="fas fa-ruler-combined"></i>
                        </div>
                        <h3>Judging (J)</h3>
                        <p>Prefers structure, planning, and organization in approaching the outside world.</p>
                    </div>
                    <div class="mbti-card">
                        <div class="mbti-icon" style="background: var(--mbti-red);">
                            <i class="fas fa-bolt"></i>
                        </div>
                        <h3>Perceiving (P)</h3>
                        <p>Embraces flexibility, spontaneity, and keeping options open in the outside world.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="section">
        <div class="container">
            <div class="section-title">
                <h2>Recommended Resources</h2>
                <p>Curated books and materials to deepen your understanding of personality types and cognitive functions.</p>
            </div>
            <div class="products-grid">
                <!-- Product 1 -->
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-book"></i>
                    </div>
                    <div class="product-info">
                        <span class="product-type">Bestseller</span>
                        <h3 class="product-title">Please Understand Me II</h3>
                        <span class="product-author">by David Keirsey</span>
                        <div class="product-price">$18.99</div>
                        <div class="mbti-tags">
                            <span class="mbti-badge mbti-nt">NT</span>
                            <span class="mbti-badge mbti-nf">NF</span>
                        </div>
                        <a href="https://www.amazon.com/Please-Understand-Me-II-Temperament/dp/0960695427/?tag=personalityinsights-20" target="_blank" class="btn" style="padding: 0.75rem 1.6rem; font-size: 0.95rem; width: 100%;">View on Amazon</a>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-book"></i>
                    </div>
                    <div class="product-info">
                        <span class="product-type">Classic</span>
                        <h3 class="product-title">Gifts Differing</h3>
                        <span class="product-author">by Isabel Briggs Myers</span>
                        <div class="product-price">$16.95</div>
                        <div class="mbti-tags">
                            <span class="mbti-badge mbti-nt">NT</span>
                            <span class="mbti-badge mbti-nf">NF</span>
                            <span class="mbti-badge mbti-sj">SJ</span>
                            <span class="mbti-badge mbti-sp">SP</span>
                        </div>
                        <a href="https://www.amazon.com/Gifts-Differing-Understanding-Personality-Type/dp/089096074X/?tag=personalityinsights-20" target="_blank" class="btn" style="padding: 0.75rem 1.6rem; font-size: 0.95rem; width: 100%;">View on Amazon</a>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-book"></i>
                    </div>
                    <div class="product-info">
                        <span class="product-type">Workbook</span>
                        <h3 class="product-title">Cognitive Functions Guide</h3>
                        <span class="product-author">by Personality Junkie</span>
                        <div class="product-price">$12.99</div>
                        <div class="mbti-tags">
                            <span class="mbti-badge mbti-nt">NT</span>
                            <span class="mbti-badge mbti-nf">NF</span>
                        </div>
                        <a href="https://www.amazon.com/MBTI-Cognitive-Functions-Guide-Understanding/dp/B08XYZABC1/?tag=personalityinsights-20" target="_blank" class="btn" style="padding: 0.75rem 1.6rem; font-size: 0.95rem; width: 100%;">View on Amazon</a>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-book"></i>
                    </div>
                    <div class="product-info">
                        <span class="product-type">Journal</span>
                        <h3 class="product-title">Type Reflection Journal</h3>
                        <span class="product-author">by Personality Insights</span>
                        <div class="product-price">$14.99</div>
                        <div class="mbti-tags">
                            <span class="mbti-badge mbti-nt">NT</span>
                            <span class="mbti-badge mbti-nf">NF</span>
                            <span class="mbti-badge mbti-sj">SJ</span>
                            <span class="mbti-badge mbti-sp">SP</span>
                        </div>
                        <a href="https://www.amazon.com/Type-Reflection-Journal-Personality-Insights/dp/B09ABCDEF1/?tag=personalityinsights-20" target="_blank" class="btn" style="padding: 0.75rem 1.6rem; font-size: 0.95rem; width: 100%;">View on Amazon</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>Community Insights</h2>
                <p>Hear from others who have discovered their personality type</p>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <p class="testimonial-content">Discovering I'm an INFJ completely changed how I understand myself. The cognitive functions explanation helped me see why I process information the way I do.</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">S</div>
                        <div class="author-info">
                            <h4>Sarah M.</h4>
                            <p>INFJ - Counselor</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-content">As an ESTP, I always thought I was just 'impulsive.' Learning about my dominant Extraverted Sensing helped me appreciate my natural strengths in crisis situations.</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">M</div>
                        <div class="author-info">
                            <h4>Michael T.</h4>
                            <p>ESTP - Entrepreneur</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-content">The resources on this site helped me understand my INTP partner so much better. Our communication has improved dramatically since learning about our different cognitive functions.</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">E</div>
                        <div class="author-info">
                            <h4>Emma L.</h4>
                            <p>ENFJ - Teacher</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="section" style="background-color: #f8fafc;">
        <div class="container">
            <div class="section-title">
                <h2>Latest Articles</h2>
                <p>Insights, research, and practical applications of personality psychology and cognitive functions.</p>
            </div>
            <div class="blog-container">
                <div class="blog-posts">
                    <!-- Blog Post 1 -->
                    <article class="blog-card">
                        <div class="blog-img">
                            <i class="fas fa-sync-alt"></i>
                        </div>
                        <div class="blog-content">
                            <div class="blog-meta">
                                <span><i class="far fa-calendar"></i> June 15, 2023</span>
                                <span><i class="far fa-clock"></i> 8 min read</span>
                            </div>
                            <h2 class="blog-title">Understanding Cognitive Functions: Beyond the 4 Letters</h2>
                            <p class="blog-excerpt">Dive deep into the eight cognitive functions that form the foundation of MBTI theory. Learn how dominant, auxiliary, tertiary, and inferior functions interact to create the full personality dynamic, and why two people with the same four-letter type can express themselves so differently.</p>
                            <a href="#" class="blog-read-more">Read full article <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </article>
                    
                    <!-- Blog Post 2 -->
                    <article class="blog-card">
                        <div class="blog-img">
                            <i class="fas fa-user-friends"></i>
                        </div>
                        <div class="blog-content">
                            <div class="blog-meta">
                                <span><i class="far fa-calendar"></i> May 28, 2023</span>
                                <span><i class="far fa-clock"></i> 10 min read</span>
                            </div>
                            <h2 class="blog-title">How Different Types Handle Conflict in Relationships</h2>
                            <p class="blog-excerpt">Explore how each MBTI type approaches disagreements and what strategies work best for resolving conflicts with different personalities. Discover why INFJs withdraw while ESTPs confront, and how to navigate these differences with empathy and understanding.</p>
                            <a href="#" class="blog-read-more">Read full article <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </article>
                    
                    <!-- Blog Post 3 -->
                    <article class="blog-card">
                        <div class="blog-img">
                            <i class="fas fa-heart"></i>
                        </div>
                        <div class="blog-content">
                            <div class="blog-meta">
                                <span><i class="far fa-calendar"></i> May 10, 2023</span>
                                <span><i class="far fa-clock"></i> 7 min read</span>
                            </div>
                            <h2 class="blog-title">MBTI in Relationships: Finding Your Perfect Match</h2>
                            <p class="blog-excerpt">Discover which personality types tend to complement each other and how to navigate relationships with different cognitive styles. Learn about the dynamics between sensing and intuitive partners, and how to bridge communication gaps for deeper connection.</p>
                            <a href="#" class="blog-read-more">Read full article <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </article>
                </div>
                
                <!-- Blog Sidebar -->
                <div class="blog-sidebar">
                    <!-- Search Widget -->
                    <div class="sidebar-widget">
                        <h3 class="sidebar-title">Search Articles</h3>
                        <p>Find specific topics about personality types and cognitive functions.</p>
                        <div class="search-box">
                            <input type="text" placeholder="Search blog...">
                            <button><i class="fas fa-search"></i></button>
                        </div>
                    </div>
                    
                    <!-- Categories Widget -->
                    <div class="sidebar-widget">
                        <h3 class="sidebar-title">Categories</h3>
                        <ul class="categories-list">
                            <li><a href="#">Cognitive Functions <span>(12)</span></a></li>
                            <li><a href="#">Type Dynamics <span>(8)</span></a></li>
                            <li><a href="#">Relationships <span>(15)</span></a></li>
                            <li><a href="#">Career & Work <span>(10)</span></a></li>
                            <li><a href="#">Personal Growth <span>(14)</span></a></li>
                            <li><a href="#">MBTI Research <span>(6)</span></a></li>
                        </ul>
                    </div>
                    
                    <!-- Recent Posts Widget -->
                    <div class="sidebar-widget">
                        <h3 class="sidebar-title">Recent Posts</h3>
                        <ul class="recent-posts-list">
                            <li><a href="#">Understanding Your Inferior Function <i class="fas fa-arrow-right"></i></a></li>
                            <li><a href="#">The Shadow Functions Explained <i class="fas fa-arrow-right"></i></a></li>
                            <li><a href="#">Type Development Through Life Stages <i class="fas fa-arrow-right"></i></a></li>
                            <li><a href="#">Common Misconceptions About MBTI <i class="fas fa-arrow-right"></i></a></li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div class="page-nav">
                <a href="#" class="active">1</a>
                <a href="#">2</a>
                <a href="#">3</a>
                <a href="#"><i class="fas fa-arrow-right"></i></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="about">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Personality Insights</h3>
                    <p>Your trusted resource for MBTI knowledge, books, and community discussions about personality types and cognitive functions.</p>
                    <p>We focus on evidence-based approaches to personality psychology while maintaining accessibility for all learners.</p>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home"><i class="fas fa-chevron-right"></i> Home</a></li>
                        <li><a href="#types"><i class="fas fa-chevron-right"></i> Personality Types</a></li>
                        <li><a href="#products"><i class="fas fa-chevron-right"></i> Shop Resources</a></li>
                        <li><a href="#blog"><i class="fas fa-chevron-right"></i> Blog</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Free Resources</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Resources</h3>
                    <ul>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Cognitive Functions</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Type Compatibility</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Development Tips</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Research Studies</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Recommended Reading</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Connect</h3>
                    <ul>
                        <li><a href="#"><i class="fab fa-facebook"></i> Facebook Community</a></li>
                        <li><a href="#"><i class="fab fa-instagram"></i> Instagram</a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i> Twitter</a></li>
                        <li><a href="#"><i class="fab fa-youtube"></i> YouTube Channel</a></li>
                        <li><a href="#"><i class="fas fa-envelope"></i> Newsletter</a></li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 Personality Insights. As an Amazon Associate, we earn from qualifying purchases. All content is for educational purposes only.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    window.scrollTo({
                        top: target.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Mobile menu toggle
        const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
        const navMenu = document.querySelector('nav ul');
        
        if (mobileMenuBtn) {
            mobileMenuBtn.addEventListener('click', () => {
                navMenu.classList.toggle('show');
            });
        }
        
        // Add subtle animations on scroll
        const observerOptions = {
            root: null,
            rootMargin: '0px',
            threshold: 0.1
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animated');
                }
            });
        }, observerOptions);
        
        // Observe sections for animation
        document.querySelectorAll('.section, .hero, .testimonials').forEach(section => {
            observer.observe(section);
        });
    </script>
</body>
</html>
