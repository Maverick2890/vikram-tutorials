# vikram-tutorials
balbharati solutions
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vikram Tutorials Solutions - Maharashtra State Board Class 9 Science Solutions</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header styles */
        header {
            background-color: #1a5276;
            color: white;
            padding: 15px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
        }
        
        .logo-icon {
            font-size: 28px;
            margin-right: 10px;
            color: #f39c12;
        }
        
        .logo-text {
            font-size: 24px;
            font-weight: bold;
            color: white;
        }
        
        .logo-text span {
            color: #f39c12;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: #f39c12;
        }
        
        /* Hero section */
        .hero {
            background: linear-gradient(135deg, #1a5276, #2980b9);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 25px;
        }
        
        .btn {
            display: inline-block;
            background-color: #e74c3c;
            color: white;
            padding: 12px 25px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #c0392b;
        }
        
        /* Main content */
        .main-content {
            padding: 50px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: #1a5276;
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background-color: #f39c12;
            margin: 10px auto;
        }
        
        .chapters-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }
        
        .chapter-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .chapter-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
        }
        
        .chapter-header {
            background-color: #2980b9;
            color: white;
            padding: 15px;
            text-align: center;
        }
        
        .chapter-content {
            padding: 20px;
        }
        
        .chapter-content ul {
            list-style: none;
        }
        
        .chapter-content li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        
        .chapter-content li:before {
            content: '•';
            color: #f39c12;
            position: absolute;
            left: 0;
        }
        
        .chapter-content a {
            color: #1a5276;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .chapter-content a:hover {
            color: #2980b9;
        }
        
        /* Resources section */
        .resources {
            background-color: #f1f2f6;
            padding: 50px 0;
        }
        
        .resources-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .resource-card {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .resource-card:hover {
            transform: translateY(-5px);
        }
        
        .resource-icon {
            font-size: 40px;
            color: #2980b9;
            margin-bottom: 15px;
        }
        
        /* Features section */
        .features {
            padding: 50px 0;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .feature-icon {
            font-size: 40px;
            color: #f39c12;
            margin-bottom: 20px;
        }
        
        /* Footer */
        footer {
            background-color: #1a5276;
            color: white;
            padding: 40px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-section h3 {
            color: #f39c12;
            margin-bottom: 20px;
            font-size: 1.2rem;
        }
        
        .footer-section ul {
            list-style: none;
        }
        
        .footer-section ul li {
            margin-bottom: 10px;
        }
        
        .footer-section a {
            color: #ecf0f1;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-section a:hover {
            color: #f39c12;
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255,255,255,0.1);
            font-size: 0.9rem;
            color: #bdc3c7;
        }
        
        /* Responsive styles */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 15px;
                flex-wrap: wrap;
                justify-content: center;
            }
            
            nav ul li {
                margin: 5px 10px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <div class="logo-icon">📚</div>
                    <div class="logo-text">Vikram <span>Tutorials</span></div>
                </div>
                <nav>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Solutions</a></li>
                        <li><a href="#">Classes</a></li>
                        <li><a href="#">Subjects</a></li>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Maharashtra State Board Class 9 Science Solutions</h1>
            <p>Comprehensive chapter-wise solutions for Class 9 Science textbook as per the Maharashtra State Board syllabus. Clear your doubts and excel in your exams with our detailed explanations.</p>
            <a href="#solutions" class="btn">View Solutions</a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="container">
            <h2 class="section-title">Why Choose Vikram Tutorials?</h2>
            
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🎯</div>
                    <h3>Expert Solutions</h3>
                    <p>Prepared by experienced educators with deep subject knowledge</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">📖</div>
                    <h3>Comprehensive Coverage</h3>
                    <p>Complete syllabus coverage with step-by-step explanations</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">🚀</div>
                    <h3>Exam Focused</h3>
                    <p>Content specifically designed to help you score better in exams</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Content -->
    <section class="main-content" id="solutions">
        <div class="container">
            <h2 class="section-title">Class 9 Science Chapters</h2>
            
            <div class="chapters-grid">
                <!-- Chapter 1 -->
                <div class="chapter-card">
                    <div class="chapter-header">
                        <h3>Chapter 1: Laws of Motion</h3>
                    </div>
                    <div class="chapter-content">
                        <ul>
                            <li><a href="#">Exercise Questions & Answers</a></li>
                            <li><a href="#">Important Questions</a></li>
                            <li><a href="#">Numerical Problems</a></li>
                            <li><a href="#">Chapter Summary</a></li>
                        </ul>
                    </div>
                </div>
                
                <!-- Chapter 2 -->
                <div class="chapter-card">
                    <div class="chapter-header">
                        <h3>Chapter 2: Work and Energy</h3>
                    </div>
                    <div class="chapter-content">
                        <ul>
                            <li><a href="#">Exercise Questions & Answers</a></li>
                            <li><a href="#">Important Questions</a></li>
                            <li><a href="#">Numerical Problems</a></li>
                            <li><a href="#">Chapter Summary</a></li>
                        </ul>
                    </div>
                </div>
                
                <!-- Chapter 3 -->
                <div class="chapter-card">
                    <div class="chapter-header">
                        <h3>Chapter 3: Current Electricity</h3>
                    </div>
                    <div class="chapter-content">
                        <ul>
                            <li><a href="#">Exercise Questions & Answers</a></li>
                            <li><a href="#">Important Questions</a></li>
                            <li><a href="#">Numerical Problems</a></li>
                            <li><a href="#">Chapter Summary</a></li>
                        </ul>
                    </div>
                </div>
                
                <!-- Chapter 4 -->
                <div class="chapter-card">
                    <div class="chapter-header">
                        <h3>Chapter 4: Measurement of Matter</h3>
                    </div>
                    <div class="chapter-content">
                        <ul>
                            <li><a href="#">Exercise Questions & Answers</a></li>
                            <li><a href="#">Important Questions</a></li>
                            <li><a href="#">Numerical Problems</a></li>
                            <li><a href="#">Chapter Summary</a></li>
                        </ul>
                    </div>
                </div>
                
                <!-- Chapter 5 -->
                <div class="chapter-card">
                    <div class="chapter-header">
                        <h3>Chapter 5: Acids, Bases and Salts</h3>
                    </div>
                    <div class="chapter-content">
                        <ul>
                            <li><a href="#">Exercise Questions & Answers</a></li>
                            <li><a href="#">Important Questions</a></li>
                            <li><a href="#">Numerical Problems</a></li>
                            <li><a href="#">Chapter Summary</a></li>
                        </ul>
                    </div>
                </div>
                
                <!-- Chapter 6 -->
                <div class="chapter-card">
                    <div class="chapter-header">
                        <h3>Chapter 6: Classification of Plants</h3>
                    </div>
                    <div class="chapter-content">
                        <ul>
                            <li><a href="#">Exercise Questions & Answers</a></li>
                            <li><a href="#">Important Questions</a></li>
                            <li><a href="#">Numerical Problems</a></li>
                            <li><a href="#">Chapter Summary</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Resources Section -->
    <section class="resources">
        <div class="container">
            <h2 class="section-title">Additional Resources</h2>
            
            <div class="resources-grid">
                <div class="resource-card">
                    <div class="resource-icon">📚</div>
                    <h3>Sample Papers</h3>
                    <p>Practice with previous year question papers and sample papers</p>
                </div>
                
                <div class="resource-card">
                    <div class="resource-icon">📝</div>
                    <h3>Revision Notes</h3>
                    <p>Concise notes for quick revision before exams</p>
                </div>
                
                <div class="resource-card">
                    <div class="resource-icon">🔬</div>
                    <h3>Lab Manual</h3>
                    <p>Step-by-step solutions for practical experiments</p>
                </div>
                
                <div class="resource-card">
                    <div class="resource-icon">📊</div>
                    <h3>MCQs</h3>
                    <p>Multiple choice questions with detailed explanations</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Terms of Service</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h3>Classes</h3>
                    <ul>
                        <li><a href="#">Class 6 Solutions</a></li>
                        <li><a href="#">Class 7 Solutions</a></li>
                        <li><a href="#">Class 8 Solutions</a></li>
                        <li><a href="#">Class 9 Solutions</a></li>
                        <li><a href="#">Class 10 Solutions</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h3>Subjects</h3>
                    <ul>
                        <li><a href="#">Science</a></li>
                        <li><a href="#">Mathematics</a></li>
                        <li><a href="#">Social Science</a></li>
                        <li><a href="#">English</a></li>
                        <li><a href="#">Hindi</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h3>Contact Info</h3>
                    <ul>
                        <li>Email: info@vikramtutorials.com</li>
                        <li>Phone: +91 9876543210</li>
                        <li>Address: Pune, Maharashtra</li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Vikram Tutorials Solutions. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
