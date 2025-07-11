<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Dream Perfect Photography</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 50px;
            padding: 40px 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .header .subtitle {
            font-size: 1.2em;
            opacity: 0.9;
            font-style: italic;
        }

        .about-content {
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }

        .photographer-section {
            display: grid;
            grid-template-columns: 300px 1fr;
            gap: 40px;
            align-items: center;
            margin: 40px 0;
            padding: 30px;
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        }

        .photographer-image {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            border: 8px solid white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            object-fit: cover;
            background: #f0f0f0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.1em;
            color: #666;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .photographer-image:hover {
            transform: scale(1.05);
        }

        .photographer-info h2 {
            color: #333;
            font-size: 2.2em;
            margin-bottom: 15px;
        }

        .photographer-info p {
            font-size: 1.1em;
            margin-bottom: 20px;
            color: #555;
        }

        .expertise-list {
            list-style: none;
            margin-top: 20px;
        }

        .expertise-list li {
            background: white;
            padding: 8px 15px;
            margin: 5px 0;
            border-radius: 25px;
            display: inline-block;
            margin-right: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            font-size: 0.95em;
        }

        .section {
            margin: 40px 0;
        }

        .section h2 {
            color: #333;
            font-size: 2em;
            margin-bottom: 20px;
            border-left: 5px solid #667eea;
            padding-left: 20px;
        }

        .section p {
            font-size: 1.1em;
            margin-bottom: 15px;
            color: #555;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }

        .feature-card {
            background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-card h3 {
            color: #333;
            margin-bottom: 15px;
            font-size: 1.3em;
        }

        .cta-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            border-radius: 15px;
            text-align: center;
            margin-top: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .cta-section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .cta-section p {
            font-size: 1.2em;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .cta-button {
            display: inline-block;
            background: white;
            color: #667eea;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: all 0.3s ease;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #666;
            font-style: italic;
        }

        @media (max-width: 768px) {
            .photographer-section {
                grid-template-columns: 1fr;
                text-align: center;
            }
            
            .photographer-image {
                width: 250px;
                height: 250px;
                margin: 0 auto;
            }
            
            .header h1 {
                font-size: 2.2em;
            }
            
            .features-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>Dream Perfect Photography</h1>
            <p class="subtitle">Capturing Life's Most Precious Moments</p>
        </header>

        <div class="about-content">
            <div class="section">
                <p style="font-size: 1.2em; text-align: center; margin-bottom: 30px;">
                    Welcome to Dream Perfect Photography, where every frame tells a story and every moment becomes a timeless memory. We specialize in transforming your most cherished occasions into stunning visual narratives that you'll treasure for a lifetime.
                </p>
            </div>

            <div class="photographer-section">
                <div class="photographer-image">
                    <!-- Replace this div with an actual img tag when you have the image -->
                    <!-- <img src="path-to-sumit-image.jpg" alt="Sumit Zoting - Professional Photographer" class="photographer-image"> -->
                    Click here to add<br>Sumit Zoting's<br>professional photo
                </div>
                <div class="photographer-info">
                    <h2>Meet Sumit Zoting</h2>
                    <p><strong>Your Creative Vision Partner</strong></p>
                    <p>With years of experience behind the lens, Sumit Zoting brings a unique blend of technical expertise and artistic vision to every project. His passion for photography stems from a deep appreciation for life's beautiful moments and an unwavering commitment to excellence.</p>
                    <ul class="expertise-list">
                        <li>Wedding Photography</li>
                        <li>Portrait Sessions</li>
                        <li>Event Documentation</li>
                        <li>Commercial Photography</li>
                        <li>Creative Art Photography</li>
                    </ul>
                </div>
            </div>

            <div class="section">
                <h2>Our Photography Philosophy</h2>
                <p>We understand that every client is unique, and so is their story. Our approach combines personalized service with professional excellence to create meaningful visual narratives.</p>
            </div>

            <div class="features-grid">
                <div class="feature-card">
                    <h3>✨ Experience You Can Trust</h3>
                    <p>Proven track record of satisfied clients and successful projects across various photography genres.</p>
                </div>
                <div class="feature-card">
                    <h3>✨ Comprehensive Services</h3>
                    <p>From intimate gatherings to grand celebrations, we cover all your photography needs.</p>
                </div>
                <div class="feature-card">
                    <h3>✨ Premium Quality</h3>
                    <p>High-resolution images with professional editing and enhancement for stunning results.</p>
                </div>
                <div class="feature-card">
                    <h3>✨ Customer-Centric Approach</h3>
                    <p>Your satisfaction is our top priority, with personalized service tailored to your vision.</p>
                </div>
                <div class="feature-card">
                    <h3>✨ Creative Storytelling</h3>
                    <p>Capturing not just moments, but the emotions and stories behind them.</p>
                </div>
                <div class="feature-card">
                    <h3>✨ Professional Excellence</h3>
                    <p>State-of-the-art equipment and cutting-edge techniques for exceptional results.</p>
                </div>
            </div>
        </div>

        <div class="cta-section">
            <h2>Let's Create Magic Together</h2>
            <p>Every photograph we take is a testament to our commitment to excellence and our passion for preserving life's most beautiful moments.</p>
            <a href="#contact" class="cta-button">Contact Us Today</a>
        </div>

        <div class="footer">
            <p>Dream Perfect Photography by Sumit Zoting - Where Every Shot is Picture Perfect</p>
        </div>
    </div>
</body>
</html>