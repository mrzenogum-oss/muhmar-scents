<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <meta name="description" content="Muhmar Scents - Premium inspired fragrances for Pakistan. Luxury perfumes at affordable prices with free nationwide delivery. Shop Signature, Gold & Strength collections.">
    <meta name="keywords" content="perfume pakistan, fragrance, attar, muhmar scents, luxury perfume, affordable fragrance, pakistan perfume brand">
    <meta name="author" content="Muhmar Scents">
    <meta name="theme-color" content="#050505">
    <meta name="color-scheme" content="dark light">
    
    <!-- Security: CSP Header -->
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self' 'unsafe-inline' https://fonts.googleapis.com https://connect.facebook.net; style-src 'self' 'unsafe-inline' https://fonts.googleapis.com https://fonts.gstatic.com; font-src 'self' https://fonts.gstatic.com; img-src 'self' data: https:; connect-src 'self' https://wa.me; frame-src https://www.youtube.com;">
    
    <!-- Open Graph -->
    <meta property="og:title" content="Muhmar Scents | Luxury Fragrances for Pakistan">
    <meta property="og:description" content="Premium inspired fragrances. PKR 2,500 with free nationwide delivery.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://muhmarscents.com">
    <meta property="og:image" content="https://muhmarscents.com/og-image.jpg">
    
    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Muhmar Scents">
    <meta name="twitter:description" content="Luxury fragrances for Pakistan">
    
    <!-- PWA Manifest -->
    <link rel="manifest" href="/manifest.json">
    
    <!-- iOS Meta Tags -->
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="apple-mobile-web-app-title" content="Muhmar Scents">
    <link rel="apple-touch-icon" href="/icons/icon-192.png">
    
    <title>Muhmar Scents | Premium Fragrances for Pakistan - PKR 2,500 Free Delivery</title>
    
    <!-- Preload Critical Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preload" href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" as="style" onload="this.onload=null;this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap"></noscript>
    
    <!-- Schema.org JSON-LD -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "Organization",
        "name": "Muhmar Scents",
        "url": "https://muhmarscents.com",
        "logo": "https://muhmarscents.com/logo.png",
        "contactPoint": {
            "@type": "ContactPoint",
            "telephone": "+92-348-0514714",
            "contactType": "sales",
            "areaServed": "PK",
            "availableLanguage": ["English", "Urdu"]
        },
        "sameAs": [
            "https://www.instagram.com/muhmarscents/",
            "https://www.youtube.com/@MuhmarScents"
        ]
    }
    </script>
    
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "Product",
        "name": "Muhmar Scents Collection",
        "image": "https://muhmarscents.com/products.jpg",
        "description": "Premium inspired fragrances for Pakistan",
        "brand": {
            "@type": "Brand",
            "name": "Muhmar Scents"
        },
        "offers": {
            "@type": "AggregateOffer",
            "lowPrice": "2500",
            "highPrice": "2500",
            "priceCurrency": "PKR",
            "availability": "https://schema.org/InStock"
        },
        "aggregateRating": {
            "@type": "AggregateRating",
            "ratingValue": "4.8",
            "reviewCount": "127"
        }
    }
    </script>
    
    <!-- Breadcrumb Schema -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "BreadcrumbList",
        "itemListElement": [
            {"@type": "ListItem", "position": 1, "name": "Home", "item": "https://muhmarscents.com/"},
            {"@type": "ListItem", "position": 2, "name": "Products", "item": "https://muhmarscents.com/#products"}
        ]
    }
    </script>
    
    <!-- FAQ Schema -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "FAQPage",
        "mainEntity": [
            {
                "@type": "Question",
                "name": "How long does delivery take?",
                "acceptedAnswer": {
                    "@type": "Answer",
                    "text": "We offer free delivery nationwide in Pakistan within 5-8 business days."
                }
            },
            {
                "@type": "Question",
                "name": "What payment methods do you accept?",
                "acceptedAnswer": {
                    "@type": "Answer",
                    "text": "We accept Cash on Delivery (COD) nationwide. Pay only when you receive your order."
                }
            }
        ]
    }
    </script>

    <style>
        /* CSS VARIABLES & RESET */
        :root {
            --gold: #D4AF37;
            --gold-light: #F4E4BC;
            --dark: #050505;
            --dark-light: #0a0a0a;
            --signature: #00D9FF;
            --strength: #C0C0C0;
            --success: #22C55E;
            --error: #EF4444;
            --text-muted: rgba(255,255,255,0.6);
            --transition-smooth: cubic-bezier(0.4, 0, 0.2, 1);
            --z-base: 1;
            --z-nav: 100;
            --z-modal: 200;
            --z-toast: 500;
            --z-loader: 999;
            --z-cursor: 9999;
        }

        /* Light Mode Support */
        @media (prefers-color-scheme: light) {
            :root {
                --dark: #f5f5f5;
                --dark-light: #ffffff;
                --text-muted: rgba(0,0,0,0.6);
            }
            body {
                color: #111;
            }
            .product-card {
                background: linear-gradient(145deg, rgba(0,0,0,0.02), rgba(0,0,0,0.01));
                border-color: rgba(0,0,0,0.06);
            }
            .form-field input, .form-field select {
                background: rgba(0,0,0,0.05);
                color: #111;
                border-color: rgba(0,0,0,0.1);
            }
        }

        *, *::before, *::after {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        @media (prefers-reduced-motion: reduce) {
            *, *::before, *::after {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
                scroll-behavior: auto !important;
            }
        }

        html {
            scroll-behavior: smooth;
            font-size: 16px;
        }

        body {
            background: var(--dark);
            color: #fff;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.6;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }

        /* Offline State */
        body.offline::before {
            content: 'You are offline - Some features may not work';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            background: #ff9800;
            color: #000;
            text-align: center;
            padding: 8px;
            z-index: 10000;
            font-size: 14px;
            font-weight: 500;
        }

        /* High Contrast Mode */
        @media (prefers-contrast: high) {
            :root {
                --gold: #FFD700;
                --dark: #000;
                --success: #00ff00;
                --error: #ff0000;
            }
        }

        /* ACCESSIBILITY: Skip Link */
        .skip-link {
            position: absolute;
            top: -40px;
            left: 0;
            background: var(--gold);
            color: #000;
            padding: 8px;
            z-index: 10000;
            transition: top 0.3s;
        }

        .skip-link:focus { top: 0; }

        /* Focus Styles */
        *:focus-visible {
            outline: 3px solid var(--gold);
            outline-offset: 2px;
        }

        button:focus-visible, a:focus-visible, input:focus-visible, select:focus-visible {
            outline: 3px solid var(--gold);
            outline-offset: 2px;
        }

        /* Screen Reader Only */
        .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0, 0, 0, 0);
            white-space: nowrap;
            border-width: 0;
        }

        /* CUSTOM CURSOR - Desktop Only */
        .cursor {
            position: fixed;
            pointer-events: none;
            z-index: var(--z-cursor);
            mix-blend-mode: difference;
        }

        .cursor-dot {
            width: 8px;
            height: 8px;
            background: var(--gold);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            transition: transform 0.1s;
        }

        .cursor-ring {
            width: 40px;
            height: 40px;
            border: 1px solid var(--gold);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            transition: all 0.15s ease-out;
        }

        .cursor.hover .cursor-ring {
            width: 60px;
            height: 60px;
            background: rgba(212, 175, 55, 0.1);
            border-color: transparent;
        }

        @media (hover: none), (pointer: coarse) {
            .cursor { display: none !important; }
            body { cursor: auto !important; }
        }

        /* STICKY HEADER */
        .announcement-bar {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            background: linear-gradient(90deg, rgba(212,175,55,0.15), rgba(212,175,55,0.05), rgba(212,175,55,0.15));
            border-bottom: 1px solid rgba(212,175,55,0.2);
            padding: 10px;
            text-align: center;
            font-size: 13px;
            color: var(--gold);
            letter-spacing: 0.5px;
            z-index: var(--z-nav);
            backdrop-filter: blur(10px);
            transform: translateZ(0);
        }

        .announcement-bar strong { color: #fff; margin: 0 5px; }

        /* NAVIGATION */
        .nav {
            position: fixed;
            top: 38px;
            left: 0;
            right: 0;
            padding: 16px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: var(--z-nav);
            transition: all 0.3s var(--transition-smooth);
            transform: translateZ(0);
        }

        .nav.scrolled {
            top: 0;
            background: rgba(5,5,5,0.98);
            backdrop-filter: blur(20px);
            padding: 12px 5%;
            box-shadow: 0 4px 30px rgba(0,0,0,0.4);
        }

        .nav.hidden { transform: translateY(-100%); }

        .brand {
            display: flex;
            align-items: center;
            gap: 12px;
            text-decoration: none;
            color: var(--gold);
            font-family: 'Cinzel', serif;
            font-size: 20px;
            letter-spacing: 2px;
        }

        .brand-mark {
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: radial-gradient(circle at 30% 30%, #1a1a1a, #000);
            border: 2px solid var(--gold);
            display: grid;
            place-items: center;
            font-weight: 700;
            font-size: 16px;
            box-shadow: 0 0 20px rgba(212,175,55,0.2), inset 0 0 20px rgba(0,0,0,0.5);
            transition: transform 0.3s;
        }

        .brand:hover .brand-mark { transform: rotate(15deg) scale(1.05); }

        /* CART SYSTEM */
        .cart-container { position: relative; }

        .cart-trigger {
            position: relative;
            width: 48px;
            height: 48px;
            border-radius: 50%;
            background: rgba(212,175,55,0.08);
            border: 1px solid rgba(212,175,55,0.3);
            display: grid;
            place-items: center;
            cursor: pointer;
            transition: all 0.3s;
        }

        .cart-trigger:hover, .cart-trigger:focus {
            background: rgba(212,175,55,0.15);
            transform: scale(1.05);
            border-color: var(--gold);
        }

        .cart-trigger svg {
            width: 22px;
            height: 22px;
            stroke: var(--gold);
            stroke-width: 1.5;
            fill: none;
            transition: transform 0.3s;
        }

        .cart-trigger:hover svg { transform: scale(1.1); }

        .cart-badge {
            position: absolute;
            top: -4px;
            right: -4px;
            width: 22px;
            height: 22px;
            background: var(--gold);
            color: #000;
            border-radius: 50%;
            font-size: 11px;
            font-weight: 700;
            display: grid;
            place-items: center;
            transform: scale(0);
            transition: transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .cart-badge.active { transform: scale(1); }

        /* MINI CART */
        .mini-cart {
            position: absolute;
            top: calc(100% + 16px);
            right: 0;
            width: 380px;
            max-height: 70vh;
            background: linear-gradient(145deg, #0a0a0a, #111);
            border: 1px solid rgba(212,175,55,0.2);
            border-radius: 16px;
            padding: 24px;
            box-shadow: 0 25px 50px -12px rgba(0,0,0,0.8);
            opacity: 0;
            visibility: hidden;
            transform: translateY(10px) scale(0.98);
            transition: all 0.3s var(--transition-smooth);
            z-index: var(--z-modal);
            display: flex;
            flex-direction: column;
        }

        .mini-cart.open {
            opacity: 1;
            visibility: visible;
            transform: translateY(0) scale(1);
        }

        .mini-cart-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 16px;
            border-bottom: 1px solid rgba(255,255,255,0.08);
        }

        .mini-cart-title {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 18px;
        }

        .mini-cart-close {
            width: 32px;
            height: 32px;
            border-radius: 50%;
            border: none;
            background: rgba(255,255,255,0.05);
            color: var(--text-muted);
            cursor: pointer;
            display: grid;
            place-items: center;
            transition: all 0.2s;
        }

        .mini-cart-close:hover, .mini-cart-close:focus {
            background: rgba(255,255,255,0.1);
            color: #fff;
        }

        .mini-cart-items {
            flex: 1;
            overflow-y: auto;
            max-height: 300px;
            margin: 0 -8px;
            padding: 0 8px;
        }

        .mini-cart-item {
            display: flex;
            gap: 16px;
            padding: 16px 0;
            border-bottom: 1px solid rgba(255,255,255,0.05);
            animation: slideIn 0.3s ease;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-10px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .mini-cart-thumb {
            width: 60px;
            height: 80px;
            border-radius: 8px;
            flex-shrink: 0;
            display: grid;
            place-items: center;
            font-family: 'Cinzel', serif;
            font-size: 10px;
            color: #fff;
            text-shadow: 0 2px 4px rgba(0,0,0,0.5);
        }

        .mini-cart-details { flex: 1; }

        .mini-cart-name {
            font-weight: 500;
            margin-bottom: 4px;
            color: #fff;
        }

        .mini-cart-meta {
            font-size: 13px;
            color: var(--text-muted);
            margin-bottom: 8px;
        }

        .mini-cart-qty {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .qty-btn {
            width: 28px;
            height: 28px;
            border-radius: 6px;
            border: 1px solid rgba(255,255,255,0.1);
            background: transparent;
            color: #fff;
            cursor: pointer;
            display: grid;
            place-items: center;
            transition: all 0.2s;
            font-size: 16px;
        }

        .qty-btn:hover, .qty-btn:focus {
            background: rgba(212,175,55,0.1);
            border-color: var(--gold);
            color: var(--gold);
        }

        .qty-value {
            min-width: 24px;
            text-align: center;
            font-weight: 500;
        }

        .mini-cart-price {
            text-align: right;
        }

        .mini-cart-amount {
            color: var(--gold);
            font-weight: 600;
            font-size: 15px;
        }

        .mini-cart-remove {
            font-size: 12px;
            color: var(--text-muted);
            cursor: pointer;
            margin-top: 4px;
            transition: color 0.2s;
            background: none;
            border: none;
            padding: 0;
        }

        .mini-cart-remove:hover, .mini-cart-remove:focus {
            color: #ff4444;
        }

        .mini-cart-empty {
            text-align: center;
            padding: 40px 20px;
            color: var(--text-muted);
        }

        .mini-cart-empty-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 16px;
            border-radius: 50%;
            background: rgba(255,255,255,0.03);
            display: grid;
            place-items: center;
            font-size: 40px;
        }

        .mini-cart-footer {
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid rgba(255,255,255,0.08);
        }

        .mini-cart-subtotal {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 16px;
            font-size: 18px;
        }

        .mini-cart-subtotal span:last-child {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 24px;
        }

        .mini-cart-note {
            font-size: 12px;
            color: var(--success);
            text-align: center;
            margin-bottom: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 6px;
        }

        .btn-primary {
            width: 100%;
            padding: 16px;
            background: var(--gold);
            color: #000;
            border: none;
            border-radius: 8px;
            font-family: 'Cinzel', serif;
            font-size: 14px;
            font-weight: 600;
            letter-spacing: 1px;
            cursor: pointer;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }

        .btn-primary::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transform: translateX(-100%);
            transition: transform 0.6s;
        }

        .btn-primary:hover::before { transform: translateX(100%); }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(212,175,55,0.3);
        }

        .btn-primary:active { transform: translateY(0); }

        .btn-primary:disabled {
            opacity: 0.6;
            cursor: not-allowed;
        }

        /* SKELETON LOADING */
        .skeleton {
            background: linear-gradient(90deg, #1a1a1a 25%, #222 50%, #1a1a1a 75%);
            background-size: 200% 100%;
            animation: skeleton-loading 1.5s infinite;
        }

        @keyframes skeleton-loading {
            0% { background-position: 200% 0; }
            100% { background-position: -200% 0; }
        }

        .skeleton-card {
            height: 400px;
            border-radius: 24px;
            margin-bottom: 20px;
        }

        /* HERO SECTION */
        .hero {
            min-height: 100vh;
            display: grid;
            place-items: center;
            position: relative;
            background: radial-gradient(ellipse at center, #0a0a0a 0%, #000 100%);
            overflow: hidden;
            padding-top: 100px;
        }

        #particles-canvas {
            position: absolute;
            inset: 0;
            opacity: 0.6;
            pointer-events: none;
        }

        .hero-content {
            text-align: center;
            z-index: 2;
            padding: 20px;
        }

        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 20px;
            background: rgba(212,175,55,0.1);
            border: 1px solid rgba(212,175,55,0.2);
            border-radius: 50px;
            font-size: 12px;
            color: var(--gold);
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 32px;
            animation: fadeInUp 0.8s ease;
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .hero-title {
            font-family: 'Cinzel', serif;
            font-size: clamp(80px, 15vw, 140px);
            line-height: 1;
            margin-bottom: 24px;
            position: relative;
        }

        @media (max-width: 768px) {
            .hero-title { font-size: clamp(60px, 12vw, 100px); }
        }

        .hero-title span {
            display: block;
            background: linear-gradient(135deg, var(--gold) 0%, #fff 50%, var(--gold) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            filter: drop-shadow(0 0 60px rgba(212,175,55,0.3));
            animation: titleReveal 1s ease-out;
        }

        @keyframes titleReveal {
            from { opacity: 0; transform: translateY(30px) scale(0.95); }
            to { opacity: 1; transform: translateY(0) scale(1); }
        }

        .hero-subtitle {
            font-family: 'Cinzel', serif;
            font-size: clamp(14px, 2vw, 18px);
            color: var(--text-muted);
            letter-spacing: 4px;
            max-width: 600px;
            margin: 0 auto;
            animation: fadeInUp 1s ease 0.3s both;
        }

        .hero-cta {
            margin-top: 48px;
            animation: fadeInUp 1s ease 0.6s both;
        }

        .btn-hero {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            padding: 18px 40px;
            background: transparent;
            border: 2px solid var(--gold);
            color: var(--gold);
            font-family: 'Cinzel', serif;
            font-size: 14px;
            letter-spacing: 2px;
            text-decoration: none;
            border-radius: 4px;
            transition: all 0.4s;
            position: relative;
            overflow: hidden;
        }

        .btn-hero::before {
            content: '';
            position: absolute;
            inset: 0;
            background: var(--gold);
            transform: scaleX(0);
            transform-origin: right;
            transition: transform 0.4s;
            z-index: -1;
        }

        .btn-hero:hover::before, .btn-hero:focus::before {
            transform: scaleX(1);
            transform-origin: left;
        }

        .btn-hero:hover, .btn-hero:focus {
            color: #000;
        }

        /* TRUST BAR */
        .trust-bar {
            display: flex;
            justify-content: center;
            gap: 60px;
            padding: 30px 5%;
            background: linear-gradient(180deg, rgba(212,175,55,0.03), transparent);
            border-top: 1px solid rgba(212,175,55,0.1);
            flex-wrap: wrap;
        }

        .trust-item {
            display: flex;
            align-items: center;
            gap: 12px;
            color: var(--text-muted);
            font-size: 13px;
        }

        .trust-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(212,175,55,0.08);
            display: grid;
            place-items: center;
            font-size: 18px;
        }

        /* PRODUCTS SECTION */
        .products-section {
            padding: 100px 5%;
            max-width: 1400px;
            margin: 0 auto;
        }

        .section-header {
            text-align: center;
            margin-bottom: 80px;
        }

        .section-eyebrow {
            font-size: 12px;
            color: var(--gold);
            letter-spacing: 3px;
            text-transform: uppercase;
            margin-bottom: 16px;
        }

        .section-title {
            font-family: 'Cinzel', serif;
            font-size: clamp(32px, 5vw, 48px);
            background: linear-gradient(90deg, #fff, var(--gold));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 16px;
        }

        .section-desc {
            color: var(--text-muted);
            max-width: 600px;
            margin: 0 auto;
            font-size: 16px;
            line-height: 1.8;
        }

        /* PRODUCT GRID */
        .products-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 40px;
        }

        @media (max-width: 1024px) {
            .products-grid { grid-template-columns: repeat(2, 1fr); }
        }

        @media (max-width: 640px) {
            .products-grid { grid-template-columns: 1fr; }
            .mini-cart { width: 100%; right: -16px; left: -16px; }
        }

        /* PRODUCT CARD */
        .product-card {
            background: linear-gradient(145deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 24px;
            padding: 40px 30px;
            text-align: center;
            position: relative;
            transition: all 0.5s var(--transition-smooth);
            overflow: visible;
            contain: layout style paint; /* Performance optimization */
        }

        @media (prefers-reduced-motion: reduce) {
            .product-card {
                transition: none !important;
            }
            .product-card:hover .product-visual {
                transform: none !important;
            }
        }

        .product-card:hover {
            border-color: rgba(212,175,55,0.2);
            transform: translateY(-8px);
            box-shadow: 0 30px 60px rgba(0,0,0,0.4), 0 0 0 1px rgba(212,175,55,0.1);
        }

        /* BADGES */
        .badge-group {
            position: absolute;
            top: -12px;
            right: 24px;
            display: flex;
            flex-direction: column;
            gap: 8px;
            z-index: 10;
        }

        .badge {
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 11px;
            font-weight: 700;
            letter-spacing: 1px;
            text-transform: uppercase;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        .badge-sale {
            background: linear-gradient(135deg, #ff4444, #cc0000);
            color: #fff;
            animation: pulse-badge 2s infinite;
        }

        @keyframes pulse-badge {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .badge-exclusive {
            background: rgba(212,175,55,0.15);
            color: var(--gold);
            border: 1px solid rgba(212,175,55,0.3);
            backdrop-filter: blur(10px);
        }

        /* PRODUCT VISUAL */
        .product-visual {
            width: 180px;
            height: 260px;
            margin: 0 auto 32px;
            border-radius: 16px;
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.6s;
        }

        .product-card:hover .product-visual {
            transform: rotateY(5deg) rotateX(5deg) translateZ(20px);
        }

        @media (prefers-reduced-motion: reduce) {
            .product-card:hover .product-visual {
                transform: none !important;
            }
        }

        .product-visual-inner {
            position: absolute;
            inset: 0;
            border-radius: 16px;
            display: grid;
            place-items: center;
            font-family: 'Cinzel', serif;
            font-size: 24px;
            font-weight: 600;
            color: #fff;
            text-shadow: 0 4px 20px rgba(0,0,0,0.5);
            overflow: hidden;
        }

        .product-visual-inner::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, rgba(255,255,255,0.2), transparent 50%);
        }

        .product-visual-inner::after {
            content: '';
            position: absolute;
            inset: -50%;
            background: radial-gradient(circle, rgba(255,255,255,0.1), transparent 70%);
            opacity: 0;
            transition: opacity 0.3s;
        }

        .product-card:hover .product-visual-inner::after {
            opacity: 1;
        }

        /* SPECIFIC PRODUCT COLORS - Using CSS classes instead of inline styles */
        .color-signature { color: var(--signature); }
        .color-gold { color: var(--gold); }
        .color-strength { color: var(--strength); }
        
        .border-signature { border-color: var(--signature); }
        .border-gold { border-color: var(--gold); }
        .border-strength { border-color: var(--strength); }

        .visual-signature {
            background: linear-gradient(135deg, #001a2e 0%, #003d5c 50%, #00D9FF 100%);
            box-shadow: 0 20px 60px rgba(0,217,255,0.2);
        }

        .visual-gold {
            background: linear-gradient(135deg, #1a1200 0%, #4a3c00 50%, #D4AF37 100%);
            box-shadow: 0 20px 60px rgba(212,175,55,0.25);
        }

        .visual-strength {
            background: linear-gradient(135deg, #0a0a0a 0%, #2a2a2a 50%, #4a4a4a 100%);
            box-shadow: 0 20px 60px rgba(192,192,192,0.15);
        }

        .product-name {
            font-family: 'Cinzel', serif;
            font-size: 32px;
            margin-bottom: 8px;
            letter-spacing: 3px;
        }

        .product-tagline {
            color: var(--text-muted);
            font-size: 14px;
            letter-spacing: 2px;
            margin-bottom: 24px;
        }

        /* PRICE */
        .price-container {
            margin: 24px 0 32px;
        }

        .price-original {
            display: block;
            font-size: 16px;
            color: rgba(255,255,255,0.3);
            text-decoration: line-through;
            text-decoration-color: #ff4444;
            margin-bottom: 4px;
        }

        .price-current {
            font-family: 'Cinzel', serif;
            font-size: 36px;
            font-weight: 600;
            color: var(--gold);
            text-shadow: 0 0 30px rgba(212,175,55,0.2);
        }

        .price-saving {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            margin-top: 8px;
            padding: 6px 12px;
            background: rgba(34,197,94,0.1);
            color: var(--success);
            border-radius: 20px;
            font-size: 12px;
            font-weight: 500;
        }

        /* ADD TO CART */
        .add-to-cart {
            width: 100%;
            padding: 18px;
            background: transparent;
            border: 1.5px solid;
            border-radius: 8px;
            font-family: 'Cinzel', serif;
            font-size: 14px;
            letter-spacing: 2px;
            cursor: pointer;
            transition: all 0.4s;
            position: relative;
            overflow: hidden;
        }

        .add-to-cart::before {
            content: '';
            position: absolute;
            inset: 0;
            background: currentColor;
            transform: scaleX(0);
            transform-origin: right;
            transition: transform 0.4s;
            z-index: -1;
        }

        .add-to-cart:hover::before, .add-to-cart:focus::before {
            transform: scaleX(1);
            transform-origin: left;
        }

        .add-to-cart:hover, .add-to-cart:focus {
            color: #000 !important;
        }

        .add-to-cart.added {
            background: var(--success);
            border-color: var(--success);
            color: #fff !important;
            pointer-events: none;
        }

        /* DELIVERY NOTE */
        .delivery-pill {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            margin-top: 20px;
            padding: 10px 20px;
            background: rgba(34,197,94,0.08);
            border: 1px solid rgba(34,197,94,0.2);
            border-radius: 50px;
            font-size: 12px;
            color: var(--success);
        }

        /* CHECKOUT PAGES */
        .page-checkout, .page-success {
            display: none;
            min-height: 100vh;
            padding: 120px 5% 60px;
        }

        .page-checkout.active, .page-success.active {
            display: block;
        }

        .checkout-container {
            max-width: 1000px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 400px;
            gap: 60px;
        }

        @media (max-width: 900px) {
            .checkout-container { grid-template-columns: 1fr; }
        }

        .checkout-title {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 32px;
            margin-bottom: 40px;
        }

        .form-card {
            background: rgba(255,255,255,0.02);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 16px;
            padding: 32px;
            margin-bottom: 24px;
        }

        .form-card-title {
            font-size: 18px;
            color: #fff;
            margin-bottom: 24px;
            padding-bottom: 16px;
            border-bottom: 1px solid rgba(255,255,255,0.08);
        }

        .form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        @media (max-width: 640px) {
            .form-row { grid-template-columns: 1fr; }
        }

        .form-field {
            margin-bottom: 20px;
        }

        .form-field label {
            display: block;
            margin-bottom: 8px;
            font-size: 14px;
            color: var(--text-muted);
        }

        .form-field label span { color: #ff4444; }

        .form-field input,
        .form-field select {
            width: 100%;
            padding: 14px 16px;
            background: rgba(255,255,255,0.05);
            border: 1px solid rgba(255,255,255,0.1);
            border-radius: 8px;
            color: #fff;
            font-size: 15px;
            transition: all 0.3s;
        }

        .form-field input:focus,
        .form-field select:focus {
            outline: none;
            border-color: var(--gold);
            background: rgba(212,175,55,0.05);
            box-shadow: 0 0 0 3px rgba(212,175,55,0.1);
        }

        .form-field input::placeholder { color: rgba(255,255,255,0.3); }

        /* VALIDATION STATES */
        .form-field input.error, .form-field select.error {
            border-color: var(--error);
            background: rgba(239,68,68,0.05);
        }

        .error-msg {
            color: var(--error);
            font-size: 12px;
            margin-top: 6px;
            display: none;
        }

        .error-msg[role="alert"] {
            display: none;
        }

        .form-field input.error ~ .error-msg,
        .form-field select.error ~ .error-msg {
            display: block;
        }

        /* ORDER SUMMARY STICKY */
        .order-summary {
            background: rgba(255,255,255,0.02);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 16px;
            padding: 32px;
            height: fit-content;
            position: sticky;
            top: 100px;
        }

        .order-summary-title {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 20px;
            margin-bottom: 24px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255,255,255,0.08);
        }

        .summary-item {
            display: flex;
            justify-content: space-between;
            padding: 16px 0;
            border-bottom: 1px solid rgba(255,255,255,0.05);
        }

        .summary-item-info {
            display: flex;
            gap: 16px;
        }

        .summary-thumb {
            width: 50px;
            height: 65px;
            border-radius: 6px;
            flex-shrink: 0;
        }

        .summary-name {
            font-weight: 500;
            margin-bottom: 4px;
        }

        .summary-qty {
            font-size: 13px;
            color: var(--text-muted);
        }

        .summary-price {
            color: var(--gold);
            font-weight: 600;
        }

        .summary-row {
            display: flex;
            justify-content: space-between;
            padding: 12px 0;
            font-size: 15px;
        }

        .summary-row.discount {
            color: var(--success);
        }

        .summary-total {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 2px solid rgba(212,175,55,0.2);
            font-family: 'Cinzel', serif;
            font-size: 24px;
            color: var(--gold);
        }

        /* PAYMENT METHOD */
        .payment-method {
            display: flex;
            align-items: center;
            gap: 16px;
            padding: 20px;
            background: rgba(212,175,55,0.05);
            border: 2px solid var(--gold);
            border-radius: 12px;
            margin: 24px 0;
        }

        .payment-icon {
            width: 48px;
            height: 48px;
            border-radius: 50%;
            background: rgba(212,175,55,0.1);
            display: grid;
            place-items: center;
            font-size: 24px;
        }

        .payment-info strong {
            display: block;
            color: var(--gold);
            margin-bottom: 4px;
        }

        .payment-info span {
            font-size: 13px;
            color: var(--text-muted);
        }

        /* TRUST POINTS */
        .trust-points {
            margin-top: 24px;
            padding-top: 24px;
            border-top: 1px solid rgba(255,255,255,0.08);
        }

        .trust-point {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 12px;
            font-size: 13px;
            color: var(--text-muted);
        }

        .trust-point::before {
            content: '✓';
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: rgba(34,197,94,0.1);
            color: var(--success);
            display: grid;
            place-items: center;
            font-size: 12px;
            flex-shrink: 0;
        }

        /* SUCCESS PAGE */
        .success-container {
            max-width: 700px;
            margin: 0 auto;
            text-align: center;
        }

        .success-icon {
            width: 120px;
            height: 120px;
            margin: 0 auto 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, rgba(34,197,94,0.1), rgba(34,197,94,0.05));
            border: 2px solid var(--success);
            display: grid;
            place-items: center;
            font-size: 60px;
            animation: scaleIn 0.5s ease;
        }

        @keyframes scaleIn {
            from { transform: scale(0); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        .success-title {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 42px;
            margin-bottom: 16px;
        }

        .success-message {
            color: var(--text-muted);
            font-size: 18px;
            margin-bottom: 40px;
        }

        .whatsapp-card {
            background: linear-gradient(145deg, rgba(37,211,102,0.1), rgba(37,211,102,0.05));
            border: 2px solid #25D366;
            border-radius: 20px;
            padding: 40px;
            margin: 40px 0;
        }

        .whatsapp-card h3 {
            color: #25D366;
            font-size: 24px;
            margin-bottom: 12px;
        }

        .whatsapp-card p {
            color: var(--text-muted);
            margin-bottom: 24px;
            line-height: 1.7;
        }

        .btn-whatsapp {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            padding: 18px 36px;
            background: #25D366;
            color: #fff;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 16px;
            transition: all 0.3s;
            box-shadow: 0 10px 30px rgba(37,211,102,0.3);
        }

        .btn-whatsapp:hover, .btn-whatsapp:focus {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(37,211,102,0.4);
        }

        .order-details-card {
            background: rgba(255,255,255,0.02);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 16px;
            padding: 32px;
            margin: 40px 0;
            text-align: left;
        }

        .order-details-card h4 {
            color: var(--gold);
            font-size: 18px;
            margin-bottom: 24px;
            padding-bottom: 16px;
            border-bottom: 1px solid rgba(255,255,255,0.08);
        }

        .detail-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 16px;
            font-size: 15px;
        }

        .detail-row span:first-child { color: var(--text-muted); }
        .detail-row span:last-child { color: #fff; font-weight: 500; }

        .detail-row.total {
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid rgba(255,255,255,0.08);
            font-family: 'Cinzel', serif;
            font-size: 20px;
            color: var(--gold);
        }

        /* FOOTER */
        .footer {
            background: #000;
            border-top: 1px solid rgba(212,175,55,0.1);
            padding: 80px 5% 40px;
        }

        .footer-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 2fr 1fr 1fr 1fr;
            gap: 60px;
        }

        @media (max-width: 900px) {
            .footer-grid { grid-template-columns: 1fr 1fr; gap: 40px; }
        }

        @media (max-width: 640px) {
            .footer-grid { grid-template-columns: 1fr; }
        }

        .footer-brand h3 {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 28px;
            margin-bottom: 20px;
        }

        .footer-brand p {
            color: var(--text-muted);
            line-height: 1.8;
            margin-bottom: 24px;
        }

        .footer-contact {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .footer-contact div {
            color: var(--text-muted);
            font-size: 15px;
        }

        .footer-contact strong { color: var(--gold); }

        .social-links {
            display: flex;
            gap: 12px;
            margin-top: 24px;
        }

        .social-link {
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: rgba(212,175,55,0.08);
            border: 1px solid rgba(212,175,55,0.2);
            display: grid;
            place-items: center;
            color: var(--gold);
            text-decoration: none;
            font-size: 18px;
            transition: all 0.3s;
        }

        .social-link:hover, .social-link:focus {
            background: var(--gold);
            color: #000;
            transform: translateY(-3px);
        }

        .footer-col h4 {
            color: var(--gold);
            font-size: 14px;
            letter-spacing: 2px;
            text-text-transform: uppercase;
            margin-bottom: 24px;
        }

        .footer-col a {
            display: block;
            color: var(--text-muted);
            text-decoration: none;
            margin-bottom: 12px;
            font-size: 15px;
            transition: color 0.2s;
        }

        .footer-col a:hover, .footer-col a:focus { color: var(--gold); }

        .footer-bottom {
            max-width: 1200px;
            margin: 60px auto 0;
            padding-top: 40px;
            border-top: 1px solid rgba(255,255,255,0.05);
            text-align: center;
            color: rgba(255,255,255,0.3);
            font-size: 14px;
        }

        /* TOAST NOTIFICATION */
        .toast {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%) translateY(100px);
            background: linear-gradient(145deg, #1a1a1a, #222);
            border: 1px solid rgba(212,175,55,0.3);
            border-radius: 12px;
            padding: 20px 28px;
            display: flex;
            align-items: center;
            gap: 16px;
            opacity: 0;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            z-index: var(--z-toast);
            box-shadow: 0 20px 50px rgba(0,0,0,0.5);
        }

        .toast.show {
            opacity: 1;
            transform: translateX(-50%) translateY(0);
        }

        .toast-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(212,175,55,0.1);
            display: grid;
            place-items: center;
            font-size: 20px;
        }

        .toast-content strong {
            display: block;
            color: var(--gold);
            margin-bottom: 4px;
        }

        .toast-content span {
            color: var(--text-muted);
            font-size: 14px;
        }

        /* LOADING OVERLAY */
        .loading-overlay {
            position: fixed;
            inset: 0;
            background: #000;
            display: grid;
            place-items: center;
            z-index: var(--z-loader);
            transition: opacity 0.5s, visibility 0.5s;
        }

        .loading-overlay.hidden {
            opacity: 0;
            visibility: hidden;
        }

        .loader {
            width: 60px;
            height: 60px;
            border: 3px solid rgba(212,175,55,0.1);
            border-top-color: var(--gold);
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        /* SCROLL ANIMATIONS */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s var(--transition-smooth);
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* STICKY ADD TO CART (Mobile) */
        .sticky-cta {
            display: none;
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            padding: 16px;
            background: linear-gradient(to top, #000, rgba(0,0,0,0.95));
            border-top: 1px solid rgba(212,175,55,0.1);
            z-index: 100;
        }

        @media (max-width: 768px) {
            .sticky-cta { display: block; }
            .products-section { padding-bottom: 100px; }
        }

        .sticky-cta-inner {
            display: flex;
            gap: 16px;
            align-items: center;
        }

        .sticky-cta-price {
            flex: 1;
        }

        .sticky-cta-price .current {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            font-size: 24px;
        }

        .sticky-cta-price .original {
            font-size: 14px;
            color: var(--text-muted);
            text-decoration: line-through;
            margin-left: 8px;
        }

        .btn-sticky {
            padding: 14px 32px;
            background: var(--gold);
            color: #000;
            border: none;
            border-radius: 8px;
            font-family: 'Cinzel', serif;
            font-weight: 600;
            font-size: 14px;
            cursor: pointer;
        }

        /* Exit Intent Popup */
        .exit-popup {
            position: fixed;
            inset: 0;
            background: rgba(0,0,0,0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 9999;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s;
        }

        .exit-popup.show {
            opacity: 1;
            visibility: visible;
        }

        .exit-popup-content {
            background: linear-gradient(145deg, #1a1a1a, #111);
            border: 2px solid var(--gold);
            border-radius: 20px;
            padding: 40px;
            text-align: center;
            max-width: 400px;
            transform: scale(0.9);
            transition: transform 0.3s;
        }

        .exit-popup.show .exit-popup-content {
            transform: scale(1);
        }

        /* Reviews Section */
        .reviews-section {
            padding: 60px 5%;
            background: linear-gradient(180deg, transparent, rgba(212,175,55,0.03));
            border-top: 1px solid rgba(212,175,55,0.1);
        }

        .review-card {
            background: rgba(255,255,255,0.02);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 16px;
            padding: 24px;
            margin: 20px auto;
            max-width: 600px;
            text-align: center;
        }

        .review-stars {
            color: var(--gold);
            font-size: 24px;
            margin-bottom: 12px;
        }

        .review-text {
            color: #fff;
            font-style: italic;
            margin-bottom: 12px;
            line-height: 1.6;
        }

        .review-author {
            color: var(--text-muted);
            font-size: 14px;
        }

        /* Inventory Warning */
        .stock-warning {
            color: #ff9800;
            font-size: 12px;
            margin-top: 8px;
            display: flex;
            align-items: center;
            gap: 6px;
            justify-content: center;
        }

        /* Confetti Animation */
        .confetti {
            position: fixed;
            width: 10px;
            height: 10px;
            pointer-events: none;
            z-index: 9999;
        }

        @keyframes confetti-fall {
            0% { transform: translateY(-100px) rotate(0deg); opacity: 1; }
            100% { transform: translateY(100vh) rotate(720deg); opacity: 0; }
        }
    </style>
</head>
<body>
    <!-- SKIP LINKS -->
    <a href="#main" class="skip-link">Skip to main content</a>
    <a href="#products" class="skip-link" style="top: -80px;">Skip to products</a>

    <!-- LOADING -->
    <div class="loading-overlay" id="loader" role="status" aria-live="polite">
        <div class="loader" aria-label="Loading Muhmar Scents"></div>
    </div>

    <!-- CUSTOM CURSOR -->
    <div class="cursor" id="cursor" aria-hidden="true">
        <div class="cursor-dot"></div>
        <div class="cursor-ring"></div>
    </div>

    <!-- ANNOUNCEMENT -->
    <div class="announcement-bar" role="banner" aria-label="Promotional announcement">
        🔥 <strong>LIMITED TIME:</strong> PKR 3,000 → <strong>PKR 2,500</strong> | FREE DELIVERY NATIONWIDE (5-8 DAYS) | ORDER NOW
    </div>

    <!-- NAVIGATION -->
    <nav class="nav" id="nav" role="navigation" aria-label="Main navigation">
        <a href="#" class="brand" onclick="showHome(); return false;" aria-label="Muhmar Scents Home">
            <div class="brand-mark" aria-hidden="true">MS</div>
            <span>MUHMAR SCENTS</span>
        </a>
        
        <div class="cart-container">
            <button class="cart-trigger" onclick="toggleCart(event)" onkeypress="if(event.key==='Enter')toggleCart(event)" aria-label="Shopping cart" aria-expanded="false" aria-controls="miniCart" aria-haspopup="true">
                <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 1 1 0 000 2H6a1 1 0 00-1 1v11a3 3 0 003 3h8a3 3 0 003-3V6a1 1 0 00-1-1h-1a1 1 0 100-2 2 2 0 012 2v11a5 5 0 01-5 5H8a5 5 0 01-5-5V5z" clip-rule="evenodd"/></svg>
                <span class="cart-badge" id="cartBadge" aria-live="polite" aria-atomic="true">0</span>
            </button>
            
            <div class="mini-cart" id="miniCart" role="dialog" aria-label="Shopping cart" aria-modal="true">
                <div class="mini-cart-header">
                    <h3 class="mini-cart-title" id="cartTitle">Your Cart</h3>
                    <button class="mini-cart-close" onclick="toggleCart(event)" aria-label="Close cart">×</button>
                </div>
                <div class="mini-cart-items" id="miniCartItems" role="region" aria-live="polite" aria-atomic="false" aria-relevant="additions removals">
                    <div class="mini-cart-empty">
                        <div class="mini-cart-empty-icon" aria-hidden="true">🛍️</div>
                        <p>Your cart is empty</p>
                    </div>
                </div>
                <div class="mini-cart-footer">
                    <div class="mini-cart-note">
                        <span aria-hidden="true">🚚</span>
                        <span>Free delivery nationwide</span>
                    </div>
                    <div class="mini-cart-subtotal">
                        <span>Subtotal</span>
                        <span id="miniCartTotal">PKR 0</span>
                    </div>
                    <button class="btn-primary" onclick="showCheckout()">View Cart / Checkout</button>
                </div>
            </div>
        </div>
    </nav>

    <!-- MAIN CONTENT -->
    <main id="main">
        
        <!-- HOME PAGE -->
        <div id="homePage">
            
            <!-- HERO -->
            <header class="hero" aria-label="Welcome to Muhmar Scents">
                <canvas id="particles-canvas" aria-hidden="true"></canvas>
                <div class="hero-content">
                    <div class="hero-badge">
                        <span aria-hidden="true">✦</span>
                        <span>Premium Fragrances</span>
                    </div>
                    <h1 class="hero-title">
                        <span>MS</span>
                    </h1>
                    <p class="hero-subtitle">Luxury Fragrances for the Modern Pakistani Gentleman</p>
                    <div class="hero-cta">
                        <a href="#products" class="btn-hero">
                            <span>Explore Collection</span>
                            <span aria-hidden="true">↓</span>
                        </a>
                    </div>
                </div>
            </header>

            <!-- TRUST BAR -->
            <aside class="trust-bar" role="complementary" aria-label="Store benefits">
                <div class="trust-item">
                    <div class="trust-icon" aria-hidden="true">🚚</div>
                    <div>
                        <strong>Free Delivery</strong><br>
                        <span style="color: var(--text-muted); font-size: 12px;">5-8 Days Nationwide</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon" aria-hidden="true">✓</div>
                    <div>
                        <strong>Cash on Delivery</strong><br>
                        <span style="color: var(--text-muted); font-size: 12px;">Pay When You Receive</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon" aria-hidden="true">↩</div>
                    <div>
                        <strong>Easy Returns</strong><br>
                        <span style="color: var(--text-muted); font-size: 12px;">7-Day Return Policy</span>
                    </div>
                </div>
                <div class="trust-item">
                    <div class="trust-icon" aria-hidden="true">💬</div>
                    <div>
                        <strong>24/7 Support</strong><br>
                        <span style="color: var(--text-muted); font-size: 12px;">WhatsApp: 0348-0514714</span>
                    </div>
                </div>
            </aside>

            <!-- PRODUCTS -->
            <section class="products-section" id="products" aria-label="Product collection">
                <div class="section-header reveal">
                    <p class="section-eyebrow">The Collection</p>
                    <h2 class="section-title">Choose Your Scent</h2>
                    <p class="section-desc">Premium inspired fragrances crafted for Pakistan's discerning gentlemen. Long-lasting, affordable luxury.</p>
                </div>

                <div class="products-grid" role="list">
                    
                    <!-- SIGNATURE -->
                    <article class="product-card reveal" role="listitem" aria-labelledby="signature-name">
                        <div class="badge-group" aria-label="Product badges">
                            <span class="badge badge-sale">SALE</span>
                            <span class="badge badge-exclusive">Just For You</span>
                        </div>
                        <figure class="product-visual" aria-labelledby="signature-name">
                            <div class="product-visual-inner visual-signature">
                                <abbr title="Signature">SIG</abbr>
                            </div>
                        </figure>
                        <h3 class="product-name color-signature" id="signature-name">SIGNATURE</h3>
                        <p class="product-tagline">Fresh • Clean • Everyday</p>
                        <div class="price-container">
                            <span class="price-original"><span class="sr-only">Original price: </span>PKR 3,000</span>
                            <span class="price-current"><span class="sr-only">Current price: </span>PKR 2,500</span>
                            <div class="price-saving">
                                <span aria-hidden="true">↓</span>
                                <span>You Save PKR 500!</span>
                            </div>
                        </div>
                        <div id="stock-signature" class="stock-warning" style="display: none;" role="status" aria-live="polite"></div>
                        <button class="add-to-cart color-signature border-signature" 
                                onclick="addToCart('signature', 'Signature', 2500, 'var(--signature)')" 
                                data-product="signature"
                                aria-label="Add Signature to cart">
                            <span class="btn-text">Add to Cart</span>
                        </button>
                        <div class="delivery-pill">
                            <span aria-hidden="true">🚚</span>
                            <span>Free Delivery Nationwide</span>
                        </div>
                    </article>

                    <!-- GOLD -->
                    <article class="product-card reveal" role="listitem" aria-labelledby="gold-name">
                        <div class="badge-group" aria-label="Product badges">
                            <span class="badge badge-sale">SALE</span>
                            <span class="badge badge-exclusive">Just For You</span>
                        </div>
                        <figure class="product-visual" aria-labelledby="gold-name">
                            <div class="product-visual-inner visual-gold">
                                <abbr title="Gold">GLD</abbr>
                            </div>
                        </figure>
                        <h3 class="product-name color-gold" id="gold-name">GOLD</h3>
                        <p class="product-tagline">Warm • Sweet • Bold</p>
                        <div class="price-container">
                            <span class="price-original"><span class="sr-only">Original price: </span>PKR 3,000</span>
                            <span class="price-current"><span class="sr-only">Current price: </span>PKR 2,500</span>
                            <div class="price-saving">
                                <span aria-hidden="true">↓</span>
                                <span>You Save PKR 500!</span>
                            </div>
                        </div>
                        <div id="stock-gold" class="stock-warning" style="display: none;" role="status" aria-live="polite"></div>
                        <button class="add-to-cart color-gold border-gold" 
                                onclick="addToCart('gold', 'Gold', 2500, 'var(--gold)')" 
                                data-product="gold"
                                aria-label="Add Gold to cart">
                            <span class="btn-text">Add to Cart</span>
                        </button>
                        <div class="delivery-pill">
                            <span aria-hidden="true">🚚</span>
                            <span>Free Delivery Nationwide</span>
                        </div>
                    </article>

                    <!-- STRENGTH -->
                    <article class="product-card reveal" role="listitem" aria-labelledby="strength-name">
                        <div class="badge-group" aria-label="Product badges">
                            <span class="badge badge-sale">SALE</span>
                            <span class="badge badge-exclusive">Just For You</span>
                        </div>
                        <figure class="product-visual" aria-labelledby="strength-name">
                            <div class="product-visual-inner visual-strength">
                                <abbr title="Strength">STR</abbr>
                            </div>
                        </figure>
                        <h3 class="product-name color-strength" id="strength-name">STRENGTH</h3>
                        <p class="product-tagline">Warm • Sweet • Masculine</p>
                        <div class="price-container">
                            <span class="price-original"><span class="sr-only">Original price: </span>PKR 3,000</span>
                            <span class="price-current"><span class="sr-only">Current price: </span>PKR 2,500</span>
                            <div class="price-saving">
                                <span aria-hidden="true">↓</span>
                                <span>You Save PKR 500!</span>
                            </div>
                        </div>
                        <div id="stock-strength" class="stock-warning" style="display: none;" role="status" aria-live="polite"></div>
                        <button class="add-to-cart color-strength border-strength" 
                                onclick="addToCart('strength', 'Strength', 2500, 'var(--strength)')" 
                                data-product="strength"
                                aria-label="Add Strength to cart">
                            <span class="btn-text">Add to Cart</span>
                        </button>
                        <div class="delivery-pill">
                            <span aria-hidden="true">🚚</span>
                            <span>Free Delivery Nationwide</span>
                        </div>
                    </article>

                </div>
            </section>

            <!-- Reviews Section -->
            <section class="reviews-section" aria-label="Customer reviews">
                <div class="section-header reveal">
                    <p class="section-eyebrow">Testimonials</p>
                    <h2 class="section-title">What Customers Say</h2>
                </div>
                <div class="review-card reveal">
                    <div class="review-stars" aria-label="5 out of 5 stars">★★★★★</div>
                    <p class="review-text">"Best fragrance I've ever owned! Long lasting and gets compliments everywhere."</p>
                    <span class="review-author">- Ahmed R., Karachi</span>
                    <time datetime="2026-01-15" style="display: block; color: var(--text-muted); font-size: 12px; margin-top: 8px;">January 2026</time>
                </div>
                <div class="review-card reveal">
                    <div class="review-stars" aria-label="5 out of 5 stars">★★★★★</div>
                    <p class="review-text">"Amazing quality for the price. The Signature scent is perfect for daily wear."</p>
                    <span class="review-author">- Bilal K., Lahore</span>
                    <time datetime="2026-01-20" style="display: block; color: var(--text-muted); font-size: 12px; margin-top: 8px;">January 2026</time>
                </div>
            </section>

            <!-- FOOTER -->
            <footer class="footer" role="contentinfo">
                <div class="footer-grid">
                    <div class="footer-brand">
                        <h3>MUHMAR SCENTS</h3>
                        <p>Premium inspired fragrances crafted for Pakistan. Experience luxury at affordable prices with free delivery nationwide.</p>
                        <div class="footer-contact">
                            <div>📞 <strong>0348-0514714</strong></div>
                            <div>🕐 <time datetime="10:00">10 AM</time> - <time datetime="20:00">8 PM</time> (Mon-Sat)</div>
                            <div>🚚 Delivery: 5-8 Days Nationwide</div>
                            <div>📍 Faisalabad, Pakistan</div>
                        </div>
                        <div class="social-links">
                            <a href="https://www.instagram.com/muhmarscents/" target="_blank" rel="noopener noreferrer" class="social-link" aria-label="Instagram">
                                <span aria-hidden="true">IG</span>
                            </a>
                            <a href="https://www.youtube.com/@MuhmarScents" target="_blank" rel="noopener noreferrer" class="social-link" aria-label="YouTube">
                                <span aria-hidden="true">YT</span>
                            </a>
                        </div>
                    </div>
                    <nav class="footer-col" aria-label="Shop links">
                        <h4>Shop</h4>
                        <a href="#products">Signature - PKR 2,500</a>
                        <a href="#products">Gold - PKR 2,500</a>
                        <a href="#products">Strength - PKR 2,500</a>
                        <a href="#" onclick="alert('Gift Cards coming soon')">Gift Cards</a>
                    </nav>
                    <nav class="footer-col" aria-label="Help links">
                        <h4>Help</h4>
                        <a href="#" onclick="alert('Track your order via WhatsApp: 0348-0514714')">Track Order</a>
                        <a href="#" onclick="alert('Returns accepted within 7 days of delivery')">Returns</a>
                        <a href="#" onclick="alert('We deliver nationwide in 5-8 days')">Shipping Info</a>
                        <a href="#" onclick="alert('Contact us: 0348-0514714')">Contact</a>
                    </nav>
                    <nav class="footer-col" aria-label="Legal links">
                        <h4>Legal</h4>
                        <a href="#" onclick="alert('Privacy Policy: We only collect data necessary to process your order')">Privacy Policy</a>
                        <a href="#" onclick="alert('Terms: All sales final unless defective')">Terms of Service</a>
                        <a href="#" onclick="alert('COD available. Pay only when you receive')">Payment Info</a>
                    </nav>
                </div>
                <div class="footer-bottom">
                    <p>&copy; <time datetime="2026">2026</time> MUHMAR SCENTS Pakistan. All Rights Reserved. | Designed for Pakistani Gentlemen</p>
                </div>
            </footer>
        </div>

        <!-- CHECKOUT PAGE -->
        <div class="page-checkout" id="checkoutPage" aria-label="Checkout" hidden>
            <div class="checkout-container">
                <div>
                    <h2 class="checkout-title">Secure Checkout</h2>
                    
                    <form id="checkoutForm" onsubmit="handleCheckout(event)" novalidate>
                        <fieldset class="form-card">
                            <legend class="form-card-title">Contact Information</legend>
                            <div class="form-row">
                                <div class="form-field">
                                    <label for="firstName">First Name <span aria-label="required">*</span></label>
                                    <input type="text" id="firstName" name="firstName" required autocomplete="given-name" minlength="2" aria-describedby="firstNameError" aria-required="true">
                                    <span id="firstNameError" class="error-msg" role="alert" aria-live="polite">Please enter your first name</span>
                                </div>
                                <div class="form-field">
                                    <label for="lastName">Last Name <span aria-label="required">*</span></label>
                                    <input type="text" id="lastName" name="lastName" required autocomplete="family-name" minlength="2" aria-describedby="lastNameError" aria-required="true">
                                    <span id="lastNameError" class="error-msg" role="alert" aria-live="polite">Please enter your last name</span>
                                </div>
                            </div>
                            <div class="form-field">
                                <label for="phone">Phone Number <span aria-label="required">*</span></label>
                                <input type="tel" id="phone" name="phone" required autocomplete="tel" pattern="03[0-9]{9}" placeholder="03XX-XXXXXXX" maxlength="11" aria-describedby="phoneError" aria-required="true">
                                <span id="phoneError" class="error-msg" role="alert" aria-live="polite">Enter valid Pakistani mobile (03XXXXXXXXX)</span>
                            </div>
                        </fieldset>

                        <fieldset class="form-card">
                            <legend class="form-card-title">Shipping Address</legend>
                            <div class="form-field">
                                <label for="address">Street Address <span aria-label="required">*</span></label>
                                <input type="text" id="address" name="address" required autocomplete="street-address" placeholder="House #, Street, Area" aria-describedby="addressError" aria-required="true">
                                <span id="addressError" class="error-msg" role="alert" aria-live="polite">Please enter your complete address</span>
                            </div>
                            <div class="form-row">
                                <div class="form-field">
                                    <label for="city">City <span aria-label="required">*</span></label>
                                    <select id="city" name="city" required aria-describedby="cityError" aria-required="true">
                                        <option value="">Select City</option>
                                        <option value="Karachi">Karachi</option>
                                        <option value="Lahore">Lahore</option>
                                        <option value="Islamabad">Islamabad</option>
                                        <option value="Rawalpindi">Rawalpindi</option>
                                        <option value="Faisalabad">Faisalabad</option>
                                        <option value="Multan">Multan</option>
                                        <option value="Peshawar">Peshawar</option>
                                        <option value="Gujranwala">Gujranwala</option>
                                        <option value="Quetta">Quetta</option>
                                        <option value="Sialkot">Sialkot</option>
                                        <option value="Other">Other</option>
                                    </select>
                                    <span id="cityError" class="error-msg" role="alert" aria-live="polite">Please select your city</span>
                                </div>
                                <div class="form-field">
                                    <label for="province">Province <span aria-label="required">*</span></label>
                                    <select id="province" name="province" required aria-describedby="provinceError" aria-required="true">
                                        <option value="">Select Province</option>
                                        <option value="Punjab">Punjab</option>
                                        <option value="Sindh">Sindh</option>
                                        <option value="KPK">KPK</option>
                                        <option value="Balochistan">Balochistan</option>
                                    </select>
                                    <span id="provinceError" class="error-msg" role="alert" aria-live="polite">Please select your province</span>
                                </div>
                            </div>
                        </fieldset>

                        <button type="submit" class="btn-primary" id="submitOrder">
                            <span class="btn-text">Place Order</span>
                            <span class="btn-loading" style="display: none;" aria-hidden="true">Processing...</span>
                        </button>
                    </form>
                </div>

                <aside class="order-summary" aria-label="Order summary">
                    <h3 class="order-summary-title">Order Summary</h3>
                    <div id="orderSummaryItems" role="list"></div>
                    
                    <div class="summary-row discount">
                        <span>Discount</span>
                        <span>-PKR 500</span>
                    </div>
                    
                    <div class="summary-total">
                        <span>Total</span>
                        <span id="orderTotal">PKR 0</span>
                    </div>

                    <div class="payment-method">
                        <div class="payment-icon" aria-hidden="true">💵</div>
                        <div class="payment-info">
                            <strong>Cash on Delivery</strong>
                            <span>Pay only when you receive your order</span>
                        </div>
                    </div>

                    <div class="trust-points">
                        <div class="trust-point">Free delivery nationwide</div>
                        <div class="trust-point">7-day return policy</div>
                        <div class="trust-point">Authentic products guaranteed</div>
                    </div>
                </aside>
            </div>
        </div>

        <!-- SUCCESS PAGE -->
        <div class="page-success" id="successPage" aria-label="Order Confirmation" hidden>
            <div class="success-container">
                <div class="success-icon" aria-hidden="true">✓</div>
                <h1 class="success-title">Thank You, <span id="successName">!</span></h1>
                <p class="success-message">Your order has been received. Please confirm via WhatsApp so we can process it immediately.</p>

                <div class="whatsapp-card">
                    <h3>📱 Confirm on WhatsApp</h3>
                    <p>Tap the button below to send your order details to our team. This helps us process your order faster and keeps you updated!</p>
                    <a href="#" class="btn-whatsapp" id="whatsappBtn" target="_blank" rel="noopener noreferrer">
                        <span>Send Order on WhatsApp</span>
                        <span aria-hidden="true">→</span>
                    </a>
                </div>

                <div class="order-details-card">
                    <h4>Order Details</h4>
                    <div id="successDetails"></div>
                </div>

                <button class="btn-primary" onclick="showHome()" style="max-width: 300px;">
                    Continue Shopping
                </button>
            </div>
        </div>

    </main>

    <!-- TOAST NOTIFICATION -->
    <div class="toast" id="toast" role="alert" aria-live="assertive" aria-atomic="true">
        <div class="toast-icon" aria-hidden="true">✓</div>
        <div class="toast-content">
            <strong id="toastTitle">Added to Cart</strong>
            <span id="toastMsg">Product added successfully</span>
        </div>
    </div>

    <!-- EXIT INTENT POPUP -->
    <div class="exit-popup" id="exitPopup" role="dialog" aria-label="Special offer" aria-modal="true" aria-hidden="true">
        <div class="exit-popup-content">
            <h3 style="color: var(--gold); font-family: 'Cinzel', serif; margin-bottom: 12px;">Wait! Get 10% Off</h3>
            <p style="color: var(--text-muted); margin-bottom: 20px;">Use code: <strong style="color: var(--gold);">EXIT10</strong></p>
            <button class="btn-primary" onclick="applyDiscount('EXIT10')" style="margin-bottom: 12px;">Apply Code</button>
            <button onclick="closeExitPopup()" style="background: none; border: none; color: var(--text-muted); cursor: pointer;">No thanks</button>
        </div>
    </div>

    <!-- STICKY CTA MOBILE -->
    <div class="sticky-cta" role="complementary" aria-label="Quick cart access">
        <div class="sticky-cta-inner">
            <div class="sticky-cta-price">
                <span class="current" id="stickyPrice">PKR 2,500</span>
                <span class="original">PKR 3,000</span>
            </div>
            <button class="btn-sticky" onclick="scrollToProducts()">Shop Now</button>
        </div>
    </div>

    <!-- ANALYTICS (Deferred) -->
    <script defer>
        // Google Analytics 4
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'GA_MEASUREMENT_ID'); // Replace with actual ID

        // Meta Pixel
        !function(f,b,e,v,n,t,s)
        {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
        n.callMethod.apply(n,arguments):n.queue.push(arguments)};
        if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
        n.queue=[];t=b.createElement(e);t.async=!0;
        t.src=v;s=b.getElementsByTagName(e)[0];
        s.parentNode.insertBefore(t,s)}(window, document,'script',
        'https://connect.facebook.net/en_US/fbevents.js');
        fbq('init', 'META_PIXEL_ID'); // Replace with actual ID
        fbq('track', 'PageView');
    </script>

    <!-- SERVICE WORKER REGISTRATION -->
    <script defer>
        if ('serviceWorker' in navigator) {
            navigator.serviceWorker.register('/sw.js').catch(err => {
                console.warn('SW registration failed:', err);
            });
        }
    </script>

    <!-- MAIN APPLICATION SCRIPT -->
    <script defer>
        // ==========================================
        // UTILITY FUNCTIONS
        // ==========================================
        
        // Sanitize user input to prevent XSS
        function sanitizeInput(input) {
            if (typeof input !== 'string') return '';
            return input
                .trim()
                .replace(/[<>]/g, '') // Prevent XSS
                .substring(0, 255); // Limit length
        }

        // Validate Pakistani phone number
        function validatePakistaniPhone(phone) {
            return /^(\+92|0)?3[0-9]{9}$/.test(phone.replace(/[- ]/g, ''));
        }

        // Generate UUID for CSRF
        function generateUUID() {
            return 'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(/[xy]/g, function(c) {
                var r = Math.random() * 16 | 0, v = c == 'x' ? r : (r & 0x3 | 0x8);
                return v.toString(16);
            });
        }

        // ==========================================
        // STATE MANAGEMENT
        // ==========================================
        const Store = {
            cart: [],
            inventory: {
                signature: { stock: 50, lowStock: 10 },
                gold: { stock: 30, lowStock: 5 },
                strength: { stock: 20, lowStock: 5 }
            },
            csrfToken: generateUUID(),
            
            init() {
                try {
                    const saved = localStorage.getItem('muhmar_cart');
                    if (saved) {
                        // Validate cart data structure
                        const parsed = JSON.parse(saved);
                        if (Array.isArray(parsed)) {
                            this.cart = parsed.filter(item => 
                                item && 
                                typeof item.id === 'string' && 
                                typeof item.qty === 'number' && 
                                item.qty > 0
                            );
                        }
                    }
                } catch (e) {
                    console.warn('Failed to load cart:', e);
                    this.cart = [];
                }
                localStorage.setItem('csrf_token', this.csrfToken);
                this.checkStock();
            },
            
            add(item) {
                // Validate stock
                const stockInfo = this.inventory[item.id];
                if (stockInfo && stockInfo.stock <= 0) {
                    showToast('Out of Stock', 'This item is currently unavailable');
                    return false;
                }

                const existing = this.cart.find(i => i.id === item.id);
                if (existing) {
                    if (stockInfo && existing.qty >= stockInfo.stock) {
                        showToast('Stock Limit', `Only ${stockInfo.stock} units available`);
                        return false;
                    }
                    existing.qty++;
                } else {
                    this.cart.push({...item, qty: 1});
                }
                this.persist();
                this.track('add_to_cart', item);
                return true;
            },

            remove(id) {
                this.cart = this.cart.filter(i => i.id !== id);
                this.persist();
            },

            updateQty(id, delta) {
                const item = this.cart.find(i => i.id === id);
                const stockInfo = this.inventory[id];
                
                if (item) {
                    const newQty = item.qty + delta;
                    if (stockInfo && newQty > stockInfo.stock) {
                        showToast('Stock Limit', `Only ${stockInfo.stock} units available`);
                        return;
                    }
                    item.qty = newQty;
                    if (item.qty <= 0) this.remove(id);
                    else this.persist();
                }
            },

            persist() {
                try {
                    localStorage.setItem('muhmar_cart', JSON.stringify(this.cart));
                    // Also save as abandoned cart for recovery
                    localStorage.setItem('abandoned_cart', JSON.stringify({
                        items: this.cart,
                        timestamp: Date.now(),
                        page: window.location.href
                    }));
                } catch (e) {
                    console.warn('localStorage unavailable:', e);
                    // Fallback: Use sessionStorage or just in-memory
                    try {
                        sessionStorage.setItem('muhmar_cart', JSON.stringify(this.cart));
                    } catch (e2) {
                        console.warn('sessionStorage also unavailable');
                    }
                }
                updateCartUI();
            },

            clear() {
                this.cart = [];
                try {
                    localStorage.removeItem('muhmar_cart');
                } catch (e) {
                    console.warn('Failed to clear cart:', e);
                }
            },

            checkStock() {
                Object.keys(this.inventory).forEach(productId => {
                    const info = this.inventory[productId];
                    const warningEl = document.getElementById(`stock-${productId}`);
                    if (warningEl && info.stock <= info.lowStock) {
                        warningEl.textContent = `⚠️ Only ${info.stock} left!`;
                        warningEl.style.display = 'flex';
                    }
                });
            },

            get total() {
                return this.cart.reduce((sum, i) => sum + (i.price * i.qty), 0);
            },

            get count() {
                return this.cart.reduce((sum, i) => sum + i.qty, 0);
            },

            track(event, data) {
                if (typeof gtag !== 'undefined') {
                    gtag('event', event, data);
                }
                if (typeof fbq !== 'undefined') {
                    fbq('track', event, data);
                }
            }
        };

        // ==========================================
        // UI UPDATES
        // ==========================================
        function updateCartUI() {
            const badge = document.getElementById('cartBadge');
            const count = Store.count;
            
            badge.textContent = count;
            badge.classList.toggle('active', count > 0);
            
            document.getElementById('miniCartTotal').textContent = `PKR ${Store.total.toLocaleString()}`;
            
            const itemsContainer = document.getElementById('miniCartItems');
            if (Store.cart.length === 0) {
                itemsContainer.innerHTML = `
                    <div class="mini-cart-empty">
                        <div class="mini-cart-empty-icon" aria-hidden="true">🛍️</div>
                        <p>Your cart is empty</p>
                        <p style="font-size: 13px; margin-top: 8px;">Add some luxury to your life</p>
                    </div>
                `;
            } else {
                itemsContainer.innerHTML = Store.cart.map(item => `
                    <div class="mini-cart-item" role="listitem">
                        <div class="mini-cart-thumb" style="background: ${sanitizeInput(item.color)}; font-size: 10px; display: grid; place-items: center;" aria-hidden="true">
                            ${sanitizeInput(item.name).substring(0,3).toUpperCase()}
                        </div>
                        <div class="mini-cart-details">
                            <div class="mini-cart-name">${sanitizeInput(item.name)}</div>
                            <div class="mini-cart-meta">PKR ${item.price.toLocaleString()} each</div>
                            <div class="mini-cart-qty">
                                <button class="qty-btn" onclick="Store.updateQty('${item.id}', -1); event.stopPropagation()" aria-label="Decrease quantity">−</button>
                                <span class="qty-value" aria-label="Quantity: ${item.qty}">${item.qty}</span>
                                <button class="qty-btn" onclick="Store.updateQty('${item.id}', 1); event.stopPropagation()" aria-label="Increase quantity">+</button>
                            </div>
                        </div>
                        <div class="mini-cart-price">
                            <div class="mini-cart-amount">PKR ${(item.price * item.qty).toLocaleString()}</div>
                            <button class="mini-cart-remove" onclick="confirmRemove('${item.id}', '${sanitizeInput(item.name)}'); event.stopPropagation()" aria-label="Remove ${sanitizeInput(item.name)} from cart">Remove</button>
                        </div>
                    </div>
                `).join('');
            }
        }

        function confirmRemove(id, name) {
            if (confirm(`Remove ${name} from cart?`)) {
                Store.remove(id);
                showToast('Removed', `${name} removed from cart`);
            }
        }

        // ==========================================
        // CART INTERACTIONS
        // ==========================================
        function toggleCart(e) {
            if (e) e.stopPropagation();
            const cart = document.getElementById('miniCart');
            const trigger = document.querySelector('.cart-trigger');
            const isOpen = cart.classList.toggle('open');
            trigger.setAttribute('aria-expanded', isOpen.toString());
            
            // Focus trap for accessibility
            if (isOpen) {
                cart.querySelector('.mini-cart-close').focus();
            }
        }

        document.addEventListener('click', (e) => {
            if (!e.target.closest('.cart-container')) {
                const cart = document.getElementById('miniCart');
                if (cart.classList.contains('open')) {
                    cart.classList.remove('open');
                    document.querySelector('.cart-trigger').setAttribute('aria-expanded', 'false');
                }
            }
        });

        // Touch gestures for mobile cart
        let touchStartX = 0;
        const cart = document.getElementById('miniCart');
        
        cart.addEventListener('touchstart', (e) => {
            touchStartX = e.touches[0].clientX;
        }, { passive: true });

        cart.addEventListener('touchend', (e) => {
            const touchEndX = e.changedTouches[0].clientX;
            if (touchStartX - touchEndX > 100) { // Swipe left to close
                toggleCart();
            }
        }, { passive: true });

        // ==========================================
        // ADD TO CART WITH FEEDBACK
        // ==========================================
        function addToCart(id, name, price, color) {
            const success = Store.add({id, name, price, color});
            if (!success) return;
            
            // Visual feedback
            const btn = document.querySelector(`[data-product="${id}"]`);
            const originalText = btn.innerHTML;
            btn.classList.add('added');
            btn.innerHTML = '<span>✓ Added!</span>';
            
            // Toast
            showToast('Added to Cart', `${name} added to your cart`);
            
            // Haptic
            if (navigator.vibrate) navigator.vibrate(50);
            
            // Confetti effect for special moments
            if (Store.count === 1) {
                triggerConfetti();
            }
            
            setTimeout(() => {
                btn.classList.remove('added');
                btn.innerHTML = originalText;
            }, 2000);
        }

        function triggerConfetti() {
            const colors = ['#D4AF37', '#00D9FF', '#C0C0C0'];
            for (let i = 0; i < 20; i++) {
                const confetti = document.createElement('div');
                confetti.className = 'confetti';
                confetti.style.left = Math.random() * 100 + 'vw';
                confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
                confetti.style.animation = `confetti-fall ${Math.random() * 2 + 2}s linear forwards`;
                document.body.appendChild(confetti);
                setTimeout(() => confetti.remove(), 4000);
            }
        }

        // ==========================================
        // TOAST NOTIFICATION
        // ==========================================
        let toastTimeout;
        function showToast(title, message) {
            clearTimeout(toastTimeout);
            const toast = document.getElementById('toast');
            document.getElementById('toastTitle').textContent = sanitizeInput(title);
            document.getElementById('toastMsg').textContent = sanitizeInput(message);
            
            toast.classList.add('show');
            toastTimeout = setTimeout(() => toast.classList.remove('show'), 3000);
        }

        // ==========================================
        // PAGE NAVIGATION
        // ==========================================
        function showHome() {
            document.getElementById('homePage').style.display = 'block';
            document.getElementById('checkoutPage').classList.remove('active');
            document.getElementById('checkoutPage').hidden = true;
            document.getElementById('successPage').classList.remove('active');
            document.getElementById('successPage').hidden = true;
            window.scrollTo(0, 0);
            Store.track('page_view', { page_title: 'Home' });
        }

        function showCheckout() {
            if (Store.cart.length === 0) {
                showToast('Cart Empty', 'Please add items to your cart first');
                return;
            }
            document.getElementById('homePage').style.display = 'none';
            const checkoutPage = document.getElementById('checkoutPage');
            checkoutPage.classList.add('active');
            checkoutPage.hidden = false;
            document.getElementById('successPage').classList.remove('active');
            document.getElementById('successPage').hidden = true;
            updateOrderSummary();
            window.scrollTo(0, 0);
            Store.track('begin_checkout', { value: Store.total, currency: 'PKR' });
        }

        function showSuccess() {
            document.getElementById('homePage').style.display = 'none';
            document.getElementById('checkoutPage').classList.remove('active');
            document.getElementById('checkoutPage').hidden = true;
            const successPage = document.getElementById('successPage');
            successPage.classList.add('active');
            successPage.hidden = false;
            window.scrollTo(0, 0);
        }

        function scrollToProducts() {
            document.getElementById('products').scrollIntoView({ behavior: 'smooth' });
        }

        // ==========================================
        // CHECKOUT LOGIC
        // ==========================================
        function updateOrderSummary() {
            const container = document.getElementById('orderSummaryItems');
            container.innerHTML = Store.cart.map(item => `
                <div class="summary-item" role="listitem">
                    <div class="summary-item-info">
                        <div class="summary-thumb" style="background: ${sanitizeInput(item.color)}" aria-hidden="true"></div>
                        <div>
                            <div class="summary-name">${sanitizeInput(item.name)}</div>
                            <div class="summary-qty">Qty: ${item.qty}</div>
                        </div>
                    </div>
                    <div class="summary-price">PKR ${(item.price * item.qty).toLocaleString()}</div>
                </div>
            `).join('');
            
            document.getElementById('orderTotal').textContent = `PKR ${Store.total.toLocaleString()}`;
        }

        async function handleCheckout(e) {
            e.preventDefault();
            const form = e.target;
            const submitBtn = document.getElementById('submitOrder');
            const btnText = submitBtn.querySelector('.btn-text');
            const btnLoading = submitBtn.querySelector('.btn-loading');
            
            // Clear previous errors
            form.querySelectorAll('.error').forEach(el => el.classList.remove('error'));
            
            let isValid = true;
            
            // Validate fields with sanitization
            const fields = ['firstName', 'lastName', 'phone', 'address', 'city', 'province'];
            const formData = {};
            
            fields.forEach(field => {
                const input = form.querySelector(`[name="${field}"]`);
                const sanitized = sanitizeInput(input.value);
                formData[field] = sanitized;
                
                if (!sanitized) {
                    input.classList.add('error');
                    isValid = false;
                }
            });
            
            // Validate phone pattern
            const phone = form.querySelector('[name="phone"]');
            if (!validatePakistaniPhone(phone.value)) {
                phone.classList.add('error');
                isValid = false;
            }
            
            if (!isValid) {
                showToast('Error', 'Please fill all required fields correctly');
                return;
            }
            
            // Show loading state
            submitBtn.disabled = true;
            btnText.style.display = 'none';
            btnLoading.style.display = 'inline';
            
            // Simulate processing delay
            await new Promise(resolve => setTimeout(resolve, 1000));
            
            // Generate order data
            const orderData = {
                name: `${formData.firstName} ${formData.lastName}`,
                phone: formData.phone,
                address: `${formData.address}, ${formData.city}, ${formData.province}`,
                items: Store.cart,
                total: Store.total,
                date: new Date().toISOString(),
                orderNumber: generateOrderNumber()
            };
            
            // Save order to history
            saveOrder(orderData);
            
            // Track conversion
            Store.track('purchase', {
                transaction_id: orderData.orderNumber,
                value: orderData.total,
                currency: 'PKR',
                items: orderData.items
            });
            
            // Reset button
            submitBtn.disabled = false;
            btnText.style.display = 'inline';
            btnLoading.style.display = 'none';
            form.reset();
            
            // Show success
            showSuccessPage(orderData);
            
            // Clear cart
            Store.clear();
        }

        function generateOrderNumber() {
            const prefix = 'MS';
            const timestamp = Date.now().toString().slice(-6);
            const random = Math.floor(Math.random() * 1000).toString().padStart(3, '0');
            return `${prefix}-${timestamp}-${random}`;
        }

        function saveOrder(order) {
            try {
                const orders = JSON.parse(localStorage.getItem('muhmar_orders')) || [];
                orders.push({...order, status: 'pending'});
                localStorage.setItem('muhmar_orders', JSON.stringify(orders.slice(-10)));
            } catch (e) {
                console.warn('Failed to save order:', e);
            }
        }

        function showSuccessPage(orderData) {
            document.getElementById('successName').textContent = sanitizeInput(orderData.name);
            
            // Generate WhatsApp message with proper encoding
            const message = `*New Order - Muhmar Scents*%0A%0A` +
                `*Order #:* ${orderData.orderNumber}%0A` +
                `*Name:* ${sanitizeInput(orderData.name)}%0A` +
                `*Phone:* ${orderData.phone}%0A` +
                `*Address:* ${sanitizeInput(orderData.address)}%0A%0A` +
                `*Order:*%0A${orderData.items.map(i => `• ${sanitizeInput(i.name)} x${i.qty} - PKR ${i.price * i.qty}`).join('%0A')}%0A%0A` +
                `*Total:* PKR ${orderData.total.toLocaleString()}%0A` +
                `*Payment:* Cash on Delivery`;
            
            const whatsappBtn = document.getElementById('whatsappBtn');
            whatsappBtn.href = `https://wa.me/923480514714?text=${message}`;
            whatsappBtn.setAttribute('aria-label', `Send order ${orderData.orderNumber} via WhatsApp`);
            
            // Fill order details
            const date = new Date(orderData.date);
            document.getElementById('successDetails').innerHTML = `
                <div class="detail-row">
                    <span>Order Number</span>
                    <span>#${orderData.orderNumber}</span>
                </div>
                <div class="detail-row">
                    <span>Order Date</span>
                    <time datetime="${orderData.date}">${date.toLocaleDateString()}</time>
                </div>
                <div class="detail-row">
                    <span>Items</span>
                    <span>${orderData.items.length} product(s)</span>
                </div>
                <div class="detail-row">
                    <span>Payment Method</span>
                    <span>Cash on Delivery</span>
                </div>
                <div class="detail-row total">
                    <span>Total Amount</span>
                    <span>PKR ${orderData.total.toLocaleString()}</span>
                </div>
            `;
            
            showSuccess();
            triggerConfetti();
        }

        // ==========================================
        // EXIT INTENT POPUP
        // ==========================================
        let exitPopupShown = false;
        function initExitIntent() {
            document.addEventListener('mouseleave', (e) => {
                if (e.clientY <= 0 && !exitPopupShown && !localStorage.getItem('exit_popup_shown')) {
                    showExitPopup();
                }
            });
        }

        function showExitPopup() {
            exitPopupShown = true;
            const popup = document.getElementById('exitPopup');
            popup.classList.add('show');
            popup.setAttribute('aria-hidden', 'false');
        }

        function closeExitPopup() {
            const popup = document.getElementById('exitPopup');
            popup.classList.remove('show');
            popup.setAttribute('aria-hidden', 'true');
            localStorage.setItem('exit_popup_shown', 'true');
        }

        function applyDiscount(code) {
            showToast('Discount Applied', `${code} will be applied at checkout`);
            closeExitPopup();
            Store.track('apply_discount', { code });
        }

        // ==========================================
        // PARTICLES BACKGROUND (Optimized)
        // ==========================================
        function initParticles() {
            if (window.matchMedia('(pointer: coarse)').matches) return; // Skip on touch devices
            
            const canvas = document.getElementById('particles-canvas');
            const ctx = canvas.getContext('2d');
            let animationId;
            let isVisible = true;
            
            function resize() {
                canvas.width = window.innerWidth;
                canvas.height = window.innerHeight;
            }
            resize();
            window.addEventListener('resize', resize, { passive: true });
            
            const particles = [];
            const particleCount = 25; // Reduced for performance
            
            for (let i = 0; i < particleCount; i++) {
                particles.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height,
                    vx: (Math.random() - 0.5) * 0.5,
                    vy: (Math.random() - 0.5) * 0.5,
                    size: Math.random() * 2 + 1,
                    alpha: Math.random() * 0.5 + 0.1
                });
            }
            
            // Use requestIdleCallback for non-critical animations
            function animate() {
                if (!isVisible) {
                    animationId = requestAnimationFrame(animate);
                    return;
                }
                
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                
                particles.forEach(p => {
                    p.x += p.vx;
                    p.y += p.vy;
                    
                    if (p.x < 0 || p.x > canvas.width) p.vx *= -1;
                    if (p.y < 0 || p.y > canvas.height) p.vy *= -1;
                    
                    ctx.beginPath();
                    ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
                    ctx.fillStyle = `rgba(212, 175, 55, ${p.alpha})`;
                    ctx.fill();
                });
                
                animationId = requestAnimationFrame(animate);
            }
            animate();
            
            // Pause when tab is hidden
            document.addEventListener('visibilitychange', () => {
                isVisible = document.visibilityState === 'visible';
            });
        }

        // ==========================================
        // SCROLL ANIMATIONS
        // ==========================================
        function initScrollAnimations() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('active');
                        observer.unobserve(entry.target); // Only animate once
                    }
                });
            }, { threshold: 0.1, rootMargin: '0px 0px -50px 0px' });
            
            document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
        }

        // ==========================================
        // NAV SCROLL EFFECT
        // ==========================================
        function initNavScroll() {
            const nav = document.getElementById('nav');
            let lastScroll = 0;
            let ticking = false;
            
            window.addEventListener('scroll', () => {
                if (!ticking) {
                    requestAnimationFrame(() => {
                        const current = window.pageYOffset;
                        
                        if (current > 100) {
                            nav.classList.add('scrolled');
                            if (current > lastScroll && current > 200) {
                                nav.classList.add('hidden');
                            } else {
                                nav.classList.remove('hidden');
                            }
                        } else {
                            nav.classList.remove('scrolled', 'hidden');
                        }
                        
                        lastScroll = current;
                        ticking = false;
                    });
                    ticking = true;
                }
            }, { passive: true });
        }

        // ==========================================
        // CUSTOM CURSOR
        // ==========================================
        function initCursor() {
            if (window.matchMedia('(pointer: coarse)').matches) return;
            
            const cursor = document.getElementById('cursor');
            const dot = cursor.querySelector('.cursor-dot');
            const ring = cursor.querySelector('.cursor-ring');
            
            let mouseX = 0, mouseY = 0;
            let ringX = 0, ringY = 0;
            let rafId;
            
            document.addEventListener('mousemove', (e) => {
                mouseX = e.clientX;
                mouseY = e.clientY;
                dot.style.left = mouseX + 'px';
                dot.style.top = mouseY + 'px';
            }, { passive: true });
            
            function animateRing() {
                ringX += (mouseX - ringX) * 0.15;
                ringY += (mouseY - ringY) * 0.15;
                ring.style.left = ringX + 'px';
                ring.style.top = ringY + 'px';
                rafId = requestAnimationFrame(animateRing);
            }
            animateRing();
            
            // Hover states
            document.querySelectorAll('a, button, .product-card').forEach(el => {
                el.addEventListener('mouseenter', () => cursor.classList.add('hover'));
                el.addEventListener('mouseleave', () => cursor.classList.remove('hover'));
            });
            
            // Cleanup on visibility change
            document.addEventListener('visibilitychange', () => {
                if (document.hidden) cancelAnimationFrame(rafId);
                else animateRing();
            });
        }

        // ==========================================
        // OFFLINE DETECTION
        // ==========================================
        function initOfflineDetection() {
            window.addEventListener('offline', () => {
                showToast('You are offline', 'Some features may not work');
                document.body.classList.add('offline');
            });

            window.addEventListener('online', () => {
                showToast('Back online', 'All features restored');
                document.body.classList.remove('offline');
            });
        }

        // ==========================================
        // ABANDONED CART RECOVERY
        // ==========================================
        function checkAbandonedCart() {
            try {
                const abandoned = JSON.parse(localStorage.getItem('abandoned_cart'));
                if (abandoned && Date.now() - abandoned.timestamp > 3600000) { // 1 hour
                    showToast('Welcome back!', 'Your cart items are still saved');
                }
            } catch (e) {
                console.warn('Failed to check abandoned cart:', e);
            }
        }

        // ==========================================
        // PERFORMANCE MONITORING
        // ==========================================
        function initPerformanceMonitoring() {
            if ('PerformanceObserver' in window) {
                const perfObserver = new PerformanceObserver((list) => {
                    list.getEntries().forEach(entry => {
                        if (entry.duration > 100) { // Log slow events
                            console.warn(`Slow interaction: ${entry.name} took ${entry.duration}ms`);
                        }
                    });
                });
                perfObserver.observe({ entryTypes: ['measure', 'navigation'] });
            }
        }

        // ==========================================
        // INITIALIZATION
        // ==========================================
        document.addEventListener('DOMContentLoaded', () => {
            // Hide loader
            setTimeout(() => {
                document.getElementById('loader').classList.add('hidden');
            }, 500);
            
            // Initialize systems
            Store.init();
            updateCartUI();
            initParticles();
            initScrollAnimations();
            initNavScroll();
            initCursor();
            initExitIntent();
            initOfflineDetection();
            checkAbandonedCart();
            initPerformanceMonitoring();
            
            // Track scroll depth
            let maxScroll = 0;
            window.addEventListener('scroll', () => {
                const scrollPercent = Math.round((window.scrollY / (document.body.scrollHeight - window.innerHeight)) * 100);
                if (scrollPercent > maxScroll) {
                    maxScroll = scrollPercent;
                    if (maxScroll === 25 || maxScroll === 50 || maxScroll === 75 || maxScroll === 100) {
                        Store.track('scroll_depth', { percent: maxScroll });
                    }
                }
            }, { passive: true });
        });

        // Global error handler
        window.addEventListener('error', (event) => {
            console.error('Global error:', event.error);
            Store.track('error', { message: event.error?.message });
        });
    </script>
</body>
</html>
