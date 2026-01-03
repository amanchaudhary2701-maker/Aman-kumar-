
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aman Singh Education - Best Learning Platform</title>
    <style>
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
        
        /* Header */
        header {
            background: linear-gradient(135deg, #1a2980, #26d0ce);
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .logo {
            font-size: 28px;
            font-weight: bold;
            display: flex;
            align-items: center;
        }
        
        .logo span {
            color: #ffd700;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 30px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            font-size: 18px;
            transition: 0.3s;
        }
        
        .nav-links a:hover {
            color: #ffd700;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
            margin-bottom: 50px;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .hero p {
            font-size: 20px;
            max-width: 800px;
            margin: 0 auto 30px;
        }
        
        .btn {
            display: inline-block;
            background: #ff6b6b;
            color: white;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
            transition: 0.3s;
            border: none;
            cursor: pointer;
        }
        
        .btn:hover {
            background: #ff5252;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        
        /* Courses Section */
        .section-title {
            text-align: center;
            margin: 60px 0 40px;
            color: #1a2980;
            font-size: 36px;
        }
        
        .courses {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }
        
        .course-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        
        .course-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.15);
        }
        
        .course-img {
            height: 200px;
            background-color: #1a2980;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 60px;
        }
        
        .course-content {
            padding: 25px;
        }
        
        .course-content h3 {
            color: #1a2980;
            margin-bottom: 15px;
            font-size: 22px;
        }
        
        /* About Section */
        .about {
            background: white;
            padding: 60px 20px;
            margin: 60px 0;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .about-content {
            display: flex;
            align-items: center;
            gap: 40px;
            flex-wrap: wrap;
        }
        
        .about-text {
            flex: 1;
            min-width: 300px;
        }
        
        .about-text h2 {
            color: #1a2980;
            margin-bottom: 20px;
            font-size: 32px;
        }
        
        /* Contact */
        .contact {
            background: linear-gradient(135deg, #1a2980, #26d0ce);
            color: white;
            padding: 60px 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 60px;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 30px auto;
        }
        
        .form-group {
            margin-bottom: 20px;
            text-align: left;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 15px;
            border-radius: 8px;
            border: none;
            font-size: 16px;
        }
        
        /* Footer */
        footer {
            background: #1a2980;
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 36px;
            }
            
            .courses {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header & Navigation -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">Aman<span>Singh</span> Education</div>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#courses">Courses</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <!-- PASTE THIS AFTER HERO SECTION (Line 119) -->
<div class="container" style="margin: 60px auto; text-align: center;">
    <h2 style="color: #1a2980; margin-bottom: 20px; font-size: 32px;">Free Sample Lecture</h2>
    <p style="color: #666; margin-bottom: 30px; max-width: 600px; margin-left: auto; margin-right: auto;">
        Experience teaching quality with this free physics lecture
    </p>
    
    <div style="max-width: 800px; margin: 0 auto; border-radius: 12px; overflow: hidden; box-shadow: 0 15px 35px rgba(0,0,0,0.1);">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; background: #000;">
            <iframe 
                src="https://www.youtube.com/embed/YOUR_VIDEO_ID_HERE" 
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen
                title="Aman Singh Physics Lecture">
            </iframe>
        </div>
    </div>
    
    <div style="margin-top: 25px;">
        <a href="https://youtube.com/@AmanSinghEducation" target="_blank" style="background: #ff0000; color: white; padding: 12px 25px; border-radius: 5px; text-decoration: none; display: inline-block; margin: 10px;">
            ▶️ More Videos on YouTube
        </a>
        <a href="#courses" style="background: #1a2980; color: white; padding: 12px 25px; border-radius: 5px; text-decoration: none; display: inline-block; margin: 10px;">
            📚 View All Courses
        </a>
    </div>
</div>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <h1>Welcome to Aman Singh Education Hub</h1>
            <p>Quality Education | Expert Guidance | Proven Results<br>Science, Mathematics & Competitive Exams Preparation</p>
            <a href="#courses" class="btn">Explore Courses</a>
        </div>
    </section>

    <!-- Courses Section -->
    <div class="container">
        <h2 class="section-title" id="courses">Our Courses</h2>
        <div class="courses">
            <div class="course-card">
                <div class="course-img">🔬</div>
                <div class="course-content">
                    <h3>Science (Physics, Chemistry, Biology)</h3>
                    <p>Complete NCERT syllabus with advanced concepts. Regular tests and doubt sessions.</p>
                    <p><strong>Classes:</strong> 9th, 10th, 11th, 12th</p>
                </div>
            </div>
            
            <div class="course-card">
                <div class="course-img">📐</div>
                <div class="course-content">
                    <h3>Mathematics</h3>
                    <p>From basics to advanced level. Problem-solving techniques and shortcut methods.</p>
                    <p><strong>Special:</strong> IIT-JEE Foundation</p>
                </div>
            </div>
            
            <div class="course-card">
                <div class="course-img">🎯</div>
                <div class="course-content">
                    <h3>Competitive Exams</h3>
                    <p>JEE, NEET, CUET preparation with mock tests and previous year papers analysis.</p>
                    <p><strong>Features:</strong> Personal mentorship</p>
                </div>
            </div>
        </div>
    </div>

    <!-- About Section -->
    <div class="container">
        <section class="about" id="about">
            <div class="about-content">
                <div class="about-text">
                    <h2>About Aman Singh</h2>
                    <p>With over 10 years of teaching experience, Aman Singh specializes in making complex concepts simple and understandable.</p>
                    <p><strong>Qualifications:</strong> M.Sc. (Physics), B.Ed., NET Qualified</p>
                    <p><strong>Experience:</strong> Former faculty at reputed coaching institutes</p>
                    <p><strong>Teaching Style:</strong> Focus on conceptual clarity and application</p>
                    <br>
                    <a href="#contact" class="btn">Join Today</a>
                </div>
            </div>
        </section>
    </div>

    <!-- Contact Section -->
    <div class="container">
        <section class="contact" id="contact">
            <h2 style="color: white;">Contact Us</h2>
            <p>Start your learning journey today!</p>
            
            <div class="contact-form">
                <form id="contactForm">
                    <div class="form-group">
                        <label for="name">Full Name</label>
                        <input type="text" id="name" placeholder="Enter your name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="phone">Phone Number</label>
                        <input type="tel" id="phone" placeholder="Enter your phone number" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="course">Select Course</label>
                        <select id="course" style="width:100%; padding:15px; border-radius:8px;">
                            <option>Science (9th-10th)</option>
                            <option>Science (11th-12th)</option>
                            <option>Mathematics</option>
                            <option>JEE Preparation</option>
                            <option>NEET Preparation</option>
                        </select>
                    </div>
                    
                    <button type="submit" class="btn">Enroll Now</button>
                </form>
            </div>
            
            <div style="margin-top: 30px;">
                <p>📞 Call: +91-9151345504</p>
                <p>📧 Email: amansingh.education@gmail.com</p>
                <p>📍 Location: paryagraj India</p>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <h3>Aman Singh Education</h3>
            <p>Building Future, One Student at a Time</p>
            <p style="margin-top: 20px; font-size: 14px; opacity: 0.8;">© 2024 Aman Singh Education. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Simple form submission
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you! We will contact you within 24 hours.');
            this.reset();
        });
        
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                if(targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if(targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
