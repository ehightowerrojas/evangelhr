            background: linear-gradient(135deg, rgba(78, 84, 200, 0.9), rgba(143, 148, 251, 0.9)), url('https://images.unsplash.com/photo-1596496181871-9681eacf9764?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
        }
        
        .registration h2 {
            color: white;
        }
        
        .registration p {
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 1.1rem;
        }
        
        .cohort-info {
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 30px;
            max-width: 600px;
            margin: 30px auto;
            backdrop-filter: blur(5px);
        }
        
        .cohort-info h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
        }
        
        .cohort-details {
            list-style: none;
            margin-bottom: 30px;
        }
        
        .cohort-details li {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .cohort-icon {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
        }
        
        .registration-buttons {
            margin-top: 30px;
        }
        
        .spots-left {
            display: inline-block;
            background-color: rgba(255, 255, 255, 0.2);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            margin-top: 15px;
        }
        
        /* Contact Section */
        .contact {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .contact-container {
            display: flex;
            gap: 50px;
            margin-top: 50px;
        }
        
        .contact-form {
            flex: 1;
            background-color: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: var(--shadow);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--dark);
        }
        
        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            transition: var(--transition);
        }
        
        .form-control:focus {
            border-color: var(--primary);
            outline: none;
            box-shadow: 0 0 0 2px rgba(78, 84, 200, 0.2);
        }
        
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        
        .submit-btn {
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 30px;
            font-size: 1rem;
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
            box-shadow: 0 4px 15px rgba(78, 84, 200, 0.4);
        }
        
        .submit-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(78, 84, 200, 0.6);
        }
        
        .contact-info {
            flex: 1;
        }
        
        .contact-card {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: var(--shadow);
            margin-bottom: 30px;
        }
        
        .contact-card h3 {
            font-size: 1.3rem;
            margin-bottom: 20px;
            color: var(--dark);
        }
        
        .contact-detail {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .contact-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, var(--primary-light), var(--primary));
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }
        
        .social-link {
            width: 40px;
            height: 40px;
            background-color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: var(--shadow);
            color: var(--primary);
            font-size: 1.2rem;
            transition: var(--transition);
        }
        
        .social-link:hover {
            transform: translateY(-5px);
            color: white;
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
        }
        
        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 30px 0;
        }
        
        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            gap: 40px;
        }
        
        .footer-logo {
            flex: 1;
            min-width: 200px;
        }
        
        .footer-logo h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }
        
        .footer-logo h3 i {
            margin-right: 10px;
        }
        
        .footer-logo p {
            color: rgba(255, 255, 255, 0.7);
            margin-bottom: 20px;
        }
        
        .footer-links {
            flex: 1;
            min-width: 200px;
        }
        
        .footer-links h4 {
            font-size: 1.1rem;
            margin-bottom: 20px;
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        
        .footer-links h4::after {
            content: '';
            position: absolute;
            width: 50px;
            height: 2px;
            background-color: var(--secondary);
            bottom: 0;
            left: 0;
        }
        
        .footer-links ul {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 10px;
        }
        
        .footer-links a {
            color: rgba(255, 255, 255, 0.7);
            transition: var(--transition);
        }
        
        .footer-links a:hover {
            color: white;
            padding-left: 5px;
        }
        
        .footer-contact {
            flex: 1;
            min-width: 200px;
        }
        
        .footer-contact h4 {
            font-size: 1.1rem;
            margin-bottom: 20px;
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        
        .footer-contact h4::after {
            content: '';
            position: absolute;
            width: 50px;
            height: 2px;
            background-color: var(--secondary);
            bottom: 0;
            left: 0;
        }
        
        .footer-contact p {
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            color: rgba(255, 255, 255, 0.7);
        }
        
        .footer-contact p i {
            margin-right: 10px;
            color: var(--secondary);
        }
        
        .footer-bottom {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            text-align: center;
            color: rgba(255, 255, 255, 0.5);
            font-size: 0.9rem;
        }
        
        /* Responsive Styles */
        @media screen and (max-width: 992px) {
            .pricing-cards {
                flex-direction: column;
                align-items: center;
            }
            
            .pricing-card {
                max-width: 100%;
                width: 100%;
                margin-bottom: 30px;
            }
            
            .pricing-card.featured {
                transform: scale(1);
            }
            
            .educators-content {
                flex-direction: column;
            }
            
            .educators-image {
                margin-bottom: 30px;
            }
            
            .contact-container {
                flex-direction: column;
            }
        }
        
        @media screen and (max-width: 768px) {
            .hero {
                padding: 80px 0 60px;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero-buttons {
                flex-direction: column;
                gap: 15px;
            }
            
            .nav-links {
                position: fixed;
                top: 70px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 70px);
                background-color: white;
                flex-direction: column;
                align-items: center;
                justify-content: flex-start;
                padding-top: 40px;
                transition: 0.4s;
                box-shadow: var(--shadow);
            }
            
            .nav-links.active {
                left: 0;
            }
            
            .nav-links li {
                margin: 15px 0;
            }
            
            .mobile-menu {
                display: block;
            }
            
            .footer-content {
                flex-direction: column;
                gap: 30px;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <nav>
                <a href="/" class="logo">
                    <i class="fas fa-robot"></i>
                    Intro to AI
                </a>
                <ul class="nav-links">
                    <li><a href="#features">Benefits</a></li>
                    <li><a href="#curriculum">Curriculum</a></li>
                    <li><a href="#showcase">Projects</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#faq">FAQ</a></li>
                    <li><a href="#educators">For Educators</a></li>
                </ul>
                <a href="#registration" class="cta-button">Enroll Now</a>
                <div class="mobile-menu">
                    <i class="fas fa-bars"></i>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Empower Your Child with AI Skills for the Future</h1>
            <p>A 10-hour interactive course teaching middle and high school students the fundamentals of artificial intelligence with real-world projects. No coding experience required!</p>
            <div class="hero-buttons">
                <a href="#registration" class="btn btn-primary btn-large">Register for Next Cohort</a>
                <a href="#curriculum" class="btn btn-secondary btn-large">View Curriculum</a>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <div class="section-title">
                <h2>Why Choose This Course?</h2>
                <p>Our AI course is designed to give students a competitive edge while making learning fun and accessible.</p>
            </div>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-project-diagram"></i>
                    </div>
                    <h3>Project-Based Learning</h3>
                    <p>Students build real AI applications they can showcase to friends, family, and even on college applications.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h3>No Coding Required</h3>
                    <p>Our course uses intuitive tools that allow students to learn AI concepts without programming experience.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Small Class Size</h3>
                    <p>Limited to 15 students per cohort, ensuring personalized attention and interactive learning experiences.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-certificate"></i>
                    </div>
                    <h3>Certified Curriculum</h3>
                    <p>We use curriculum developed by aiEDU.org, a respected nonprofit organization specializing in AI education.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <h3>College Application Boost</h3>
                    <p>Students gain valuable skills and projects that demonstrate initiative and technological aptitude to colleges.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-dollar-sign"></i>
                    </div>
                    <h3>Affordable Pricing</h3>
                    <p>At half the cost of similar programs, we make quality AI education accessible to more students.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Curriculum Section -->
    <section class="curriculum" id="curriculum">
        <div class="container">
            <div class="section-title">
                <h2>Course Curriculum</h2>
                <p>Our comprehensive 10-hour curriculum introduces students to key AI concepts through hands-on projects.</p>
            </div>
            <div class="curriculum-weeks">
                <div class="week-card">
                    <div class="week-header">
                        <h3>Week 1: Introduction to AI & Image Generation</h3>
                        <div class="week-toggle"><i class="fas fa-chevron-down"></i></div>
                    </div>
                    <div class="week-content">
                        <p>Students begin their AI journey by understanding fundamental concepts and creating their first AI-generated images.</p>
                        <ul>
                            <li>What is artificial intelligence and how does it work?</li>
                            <li>Exploring different types of AI systems</li>
                            <li>Understanding how AI is used in everyday applications</li>
                            <li>Introduction to ethical considerations in AI</li>
                        </ul>
                        <div class="week-project">
                            <h4>Project: AI Art Generator</h4>
                            <p>Students will create custom artwork using DALL-E and other image generation tools, learning how to craft effective prompts that produce desired results.</p>
                        </div>
                    </div>
                </div>
                
                <div class="week-card">
                    <div class="week-header">
                        <h3>Week 2: Conversational AI & Chatbots</h3>
                        <div class="week-toggle"><i class="fas fa-chevron-down"></i></div>
                    </div>
                    <div class="week-content">
                        <p>Students explore how AI can understand and generate human language, and build their own specialized chatbot.</p>
                        <ul>
                            <li>How language models work and their capabilities</li>
                            <li>Techniques for effective prompt engineering</li>
                            <li>Understanding context and conversation flow</li>
                            <li>Exploring biases in language models</li>
                        </ul>
                        <div class="week-project">
                            <h4>Project: Custom Knowledge Chatbot</h4>
                            <p>Students will create a specialized chatbot trained on topics of their choice that can answer questions and provide information in a specific domain.</p>
                        </div>
                    </div>
                </div>
                
                <div class="week-card">
                    <div class="week-header">
                        <h3>Week 3: Voice AI & Audio Processing</h3>
                        <div class="week-toggle"><i class="fas fa-chevron-down"></i></div>
                    </div>
                    <div class="week-content">
                        <p>Students learn how AI can process and generate speech, and build a voice assistant application.</p>
                        <ul>
                            <li>Speech recognition and text-to-speech technologies</li>
                            <li>Understanding voice interfaces and user experience</li>
                            <li>Audio analysis and processing techniques</li>
                            <li>Building conversational interfaces</li>
                        </ul>
                        <div class="week-project">
                            <h4>Project: Homework Helper Voice Assistant</h4>
                            <p>Students will develop a voice assistant that can answer questions, provide explanations, and help with homework tasks through natural conversation.</p>
                        </div>
                    </div>
                </div>
                
                <div class="week-card">
                    <div class="week-header">
                        <h3>Week 4: Recommendation Systems</h3>
                        <div class="week-toggle"><i class="fas fa-chevron-down"></i></div>
                    </div>
                    <div class="week-content">
                        <p>Students explore how AI can make personalized recommendations based on preferences and patterns.</p>
                        <ul>
                            <li>How recommendation algorithms work</li>
                            <li>Content-based vs. collaborative filtering</li>
                            <li>Pattern recognition in user behavior</li>
                            <li>Evaluating recommendation quality</li>
                        </ul>
                        <div class="week-project">
                            <h4>Project: Personal Recommendation Engine</h4>
                            <p>Students will build a system that recommends movies, music, books, or other content based on user preferences and behavior patterns.</p>
                        </div>
                    </div>
                </div>
                
                <div class="week-card">
                    <div class="week-header">
                        <h3>Week 5: Final Project & AI Ethics</h3>
                        <div class="week-toggle"><i class="fas fa-chevron-down"></i></div>
                    </div>
                    <div class="week-content">
                        <p>Students complete a capstone project while exploring the ethical implications of AI technology.</p>
                        <ul>
                            <li>Current challenges and limitations in AI</li>
                            <li>Ethical considerations and responsible AI use</li>
                            <li>Future trends and career opportunities in AI</li>
                            <li>Project planning and implementation</li>
                        </ul>
                        <div class="week-project">
                            <h4>Project: Capstone AI Application</h4>
                            <p>Students will design and build their own AI application that combines multiple concepts learned throughout the course, addressing a real-world problem or interest.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Student Project Showcase -->
    <section class="showcase" id="showcase">
        <div class="container">
            <div class="section-title">
                <h2>Student Project Showcase</h2>
                <p>See what our students have created using the skills they've learned in our AI course.</p>
            </div>
            <div class="project-gallery">
                <div class="project-item">
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1633613286991-611fe299c4be?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="AI Art Generator">
                    </div>
                    <div class="project-info">
                        <h3>Fantasy Landscape Generator</h3>
                        <p>An AI tool that creates unique fantasy landscapes based on text descriptions, with custom settings for style and mood.</p>
                        <div class="student-info">
                            <div class="student-avatar">
                                <img src="https://randomuser.me/api/portraits/kids/1.jpg" alt="Student">
                            </div>
                            <div>
                                <div class="student-name">Alex W.</div>
                                <div class="student-grade">7th Grade</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="project-item">
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1499951360447-b19be8fe80f5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="History Tutor Chatbot">
                    </div>
                    <div class="project-info">
                        <h3>History Tutor Chatbot</h3>
                        <p>A specialized chatbot that helps students learn history through interactive conversations, quizzes, and storytelling.</p>
                        <div class="student-info">
                            <div class="student-avatar">
                                <img src="https://randomuser.me/api/portraits/kids/2.jpg" alt="Student">
                            </div>
                            <div>
                                <div class="student-name">Maya L.</div>
                                <div class="student-grade">9th Grade</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="project-item">
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1583324113626-70df0f4deaab?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1408&q=80" alt="Music Recommendation">
                    </div>
                    <div class="project-info">
                        <h3>Mood-Based Music Recommender</h3>
                        <p>An AI system that suggests music based on the user's current mood, weather, time of day, and past listening preferences.</p>
                        <div class="student-info">
                            <div class="student-avatar">
                                <img src="https://randomuser.me/api/portraits/kids/3.jpg" alt="Student">
                            </div>
                            <div>
                                <div class="student-name">Jayden T.</div>
                                <div class="student-grade">8th Grade</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>What Parents & Students Say</h2>
                <p>Hear from families who have experienced our AI course.</p>
            </div>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <p class="testimonial-content">My daughter was initially intimidated by AI, but after just one class, she was excited to show me what she could create. The instructor has a gift for making complex concepts accessible to kids.</p>
                    <div class="testimonial-author">
                        <div class="author-image">
                            <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Parent">
                        </div>
                        <div class="author-info">
                            <h4>Jennifer R.</h4>
                            <p>Parent of 7th Grader</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p class="testimonial-content">This course was way more fun than I expected! I thought we'd just be learning boring stuff, but we actually got to make cool projects. I even used my AI art generator for a school assignment!</p>
                    <div class="testimonial-author">
                        <div class="author-image">
                            <img src="https://randomuser.me/api/portraits/kids/4.jpg" alt="Student">
                        </div>
                        <div class="author-info">
                            <h4>Tyler M.</h4>
                            <p>8th Grade Student</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p class="testimonial-content">As a school counselor, I've recommended this course to several students interested in technology. The curriculum is rigorous yet accessible, and the projects give students valuable skills they can showcase.</p>
                    <div class="testimonial-author">
                        <div class="author-image">
                            <img src="https://randomuser.me/api/portraits/men/42.jpg" alt="Counselor">
                        </div>
                        <div class="author-info">
                            <h4>David L.</h4>
                            <p>High School Counselor</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="pricing" id="pricing">
        <div class="container">
            <div class="section-title">
                <h2>Affordable Investment in Your Child's Future</h2>
                <p>Our pricing is designed to make quality AI education accessible to more students.</p>
            </div>
            <div class="pricing-cards">
                <div class="pricing-card">
                    <div class="pricing-header">
                        <div class="pricing-name">Early Bird Registration</div>
                        <div class="pricing-price">$400</div>
                        <div class="pricing-period">10 hours of instruction</div>
                    </div>
                    <ul class="pricing-features">
                        <li>Full 5-week curriculum</li>
                        <li>Small class size (max 15 students)</li>
                        <li>Live, interactive online sessions</li>
                        <li>Project portfolio development</li>
                        <li>Certificate of completion</li>
                    </ul>
                    <div class="pricing-cta">
                        <a href="#registration" class="btn btn-secondary">Register Now</a>
                    </div>
                </div>
                
                <div class="pricing-card featured">
                    <div class="pricing-header">
                        <div class="pricing-name">Standard Registration</div>
                        <div class="pricing-price">$450</div>
                        <div class="pricing-period">10 hours of instruction</div>
                    </div>
                    <ul class="pricing-features">
                        <li>Everything in Early Bird package</li>
                        <li>Priority access to instructor</li>
                        <li>Extended project support</li>
                        <li>Additional resource materials</li>
                        <li>Course completion certificate</li>
                    </ul>
                    <div class="pricing-cta">
                        <a href="#registration" class="btn btn-primary">Register Now</a>
                    </div>
                </div>
                
                <div class="pricing-card">
                    <div class="pricing-header">
                        <div class="pricing-name">Friend Referral</div>
                        <div class="pricing-price">$425</div>
                        <div class="pricing-period">10 hours of instruction</div>
                    </div>
                    <ul class="pricing-features">
                        <li>Everything in Standard package</li>
                        <li>$<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intro to AI - Middle & High School Course | Evangel Hightower-Rojas</title>
    <meta name="description" content="A 10-hour interactive course teaching middle and high school students the fundamentals of artificial intelligence with real-world projects and no coding experience required.">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #4e54c8;
            --primary-light: #8f94fb;
            --secondary: #1abc9c;
            --dark: #2c3e50;
            --light: #f8f9fb;
            --text: #333333;
            --text-light: #666666;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            color: var(--text);
            line-height: 1.6;
            background-color: var(--light);
        }
        
        a {
            text-decoration: none;
            color: var(--primary);
            transition: var(--transition);
        }
        
        a:hover {
            color: var(--secondary);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: 600;
            text-align: center;
            transition: var(--transition);
            cursor: pointer;
        }
        
        .btn-primary {
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            color: white;
            box-shadow: 0 4px 15px rgba(78, 84, 200, 0.4);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(78, 84, 200, 0.6);
            color: white;
        }
        
        .btn-secondary {
            background-color: white;
            color: var(--primary);
            border: 2px solid var(--primary);
        }
        
        .btn-secondary:hover {
            background-color: var(--primary);
            color: white;
        }
        
        .btn-large {
            padding: 15px 30px;
            font-size: 1.1rem;
        }
        
        /* Header Styles */
        header {
            background-color: white;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
            display: flex;
            align-items: center;
        }
        
        .logo i {
            margin-right: 10px;
            font-size: 1.8rem;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 30px;
        }
        
        .nav-links a {
            color: var(--text);
            font-weight: 500;
            padding: 5px 0;
            position: relative;
        }
        
        .nav-links a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: var(--primary);
            transition: var(--transition);
        }
        
        .nav-links a:hover::after {
            width: 100%;
        }
        
        .cta-button {
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            color: white;
            padding: 8px 20px;
            border-radius: 30px;
            font-weight: 600;
            box-shadow: 0 4px 15px rgba(78, 84, 200, 0.4);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(78, 84, 200, 0.6);
            color: white;
        }
        
        .mobile-menu {
            display: none;
            cursor: pointer;
            font-size: 1.5rem;
            color: var(--primary);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, rgba(78, 84, 200, 0.9), rgba(143, 148, 251, 0.9)), url('https://images.unsplash.com/photo-1620712943543-bcc4688e7485?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 0 80px;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 2.8rem;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        
        .hero-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        /* Features Section */
        .features {
            padding: 80px 0;
            background-color: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 2.2rem;
            display: inline-block;
            padding-bottom: 10px;
            color: var(--dark);
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            width: 80px;
            height: 3px;
            background-color: var(--secondary);
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .section-title p {
            color: var(--text-light);
            max-width: 700px;
            margin: 15px auto 0;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: var(--transition);
            text-align: center;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .feature-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 20px;
            background: linear-gradient(135deg, var(--primary-light), var(--primary));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
        }
        
        .feature-card h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        /* Curriculum Section */
        .curriculum {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .curriculum-weeks {
            margin-top: 50px;
        }
        
        .week-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--shadow);
            margin-bottom: 30px;
        }
        
        .week-header {
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            color: white;
            padding: 15px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: pointer;
        }
        
        .week-header h3 {
            font-size: 1.2rem;
            font-weight: 600;
        }
        
        .week-toggle {
            font-size: 1.2rem;
            transition: var(--transition);
        }
        
        .week-toggle.active {
            transform: rotate(180deg);
        }
        
        .week-content {
            padding: 0;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease, padding 0.3s ease;
        }
        
        .week-content.active {
            padding: 25px;
            max-height: 500px;
        }
        
        .week-content ul {
            list-style: none;
        }
        
        .week-content li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
        }
        
        .week-content li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--secondary);
            font-weight: bold;
        }
        
        .week-content p {
            margin-bottom: 15px;
        }
        
        .week-project {
            background-color: var(--light);
            padding: 15px;
            border-radius: 5px;
            margin-top: 15px;
        }
        
        .week-project h4 {
            font-size: 1rem;
            margin-bottom: 10px;
            color: var(--primary);
        }
        
        /* Showcase Section */
        .showcase {
            padding: 80px 0;
            background-color: white;
        }
        
        .project-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }
        
        .project-item {
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--shadow);
            background-color: white;
            transition: var(--transition);
        }
        
        .project-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .project-image {
            height: 200px;
            overflow: hidden;
        }
        
        .project-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .project-item:hover .project-image img {
            transform: scale(1.1);
        }
        
        .project-info {
            padding: 20px;
        }
        
        .project-info h3 {
            font-size: 1.1rem;
            margin-bottom: 10px;
            color: var(--dark);
        }
        
        .project-info p {
            color: var(--text-light);
            font-size: 0.95rem;
        }
        
        .student-info {
            display: flex;
            align-items: center;
            margin-top: 15px;
        }
        
        .student-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
            overflow: hidden;
        }
        
        .student-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .student-name {
            font-size: 0.9rem;
            color: var(--text);
        }
        
        .student-grade {
            font-size: 0.8rem;
            color: var(--text-light);
        }
        
        /* Testimonials Section */
        .testimonials {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .testimonial-card {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: var(--shadow);
            position: relative;
        }
        
        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 4rem;
            color: rgba(78, 84, 200, 0.1);
            font-family: Georgia, serif;
        }
        
        .testimonial-content {
            margin-bottom: 20px;
            font-style: italic;
            z-index: 1;
            position: relative;
            color: var(--text);
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .author-image {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
        }
        
        .author-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .author-info h4 {
            font-size: 1rem;
            margin-bottom: 5px;
            color: var(--dark);
        }
        
        .author-info p {
            font-size: 0.85rem;
            color: var(--text-light);
        }
        
        /* Pricing Section */
        .pricing {
            padding: 80px 0;
            background-color: white;
        }
        
        .pricing-cards {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 50px;
        }
        
        .pricing-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: var(--shadow);
            padding: 40px 30px;
            text-align: center;
            max-width: 350px;
            width: 100%;
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }
        
        .pricing-card.featured {
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        
        .pricing-card.featured::before {
            content: 'Most Popular';
            position: absolute;
            top: 0;
            right: 0;
            background-color: var(--secondary);
            color: white;
            font-size: 0.8rem;
            padding: 5px 15px;
            border-bottom-left-radius: 10px;
        }
        
        .pricing-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .pricing-header {
            margin-bottom: 30px;
        }
        
        .pricing-name {
            font-size: 1.3rem;
            color: var(--dark);
            margin-bottom: 15px;
        }
        
        .pricing-price {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 5px;
        }
        
        .pricing-period {
            color: var(--text-light);
            font-size: 0.9rem;
        }
        
        .pricing-features {
            list-style: none;
            margin-bottom: 30px;
        }
        
        .pricing-features li {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }
        
        .pricing-features li:last-child {
            border-bottom: none;
        }
        
        .pricing-cta {
            margin-top: 20px;
        }
        
        .scholarship-note {
            margin-top: 40px;
            padding: 20px;
            background-color: var(--light);
            border-radius: 10px;
            text-align: center;
        }
        
        .scholarship-note p {
            margin-bottom: 15px;
        }
        
        /* FAQ Section */
        .faq {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .faq-list {
            max-width: 800px;
            margin: 50px auto 0;
        }
        
        .faq-item {
            background-color: white;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: var(--shadow);
            overflow: hidden;
        }
        
        .faq-question {
            padding: 20px 25px;
            font-size: 1.1rem;
            font-weight: 600;
            color: var(--dark);
            background-color: white;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .faq-toggle {
            font-size: 1.2rem;
            transition: var(--transition);
        }
        
        .faq-toggle.active {
            transform: rotate(180deg);
        }
        
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease, padding 0.3s ease;
        }
        
        .faq-answer.active {
            max-height: 300px;
            padding: 0 25px 20px;
        }
        
        /* For Educators Section */
        .educators {
            padding: 80px 0;
            background-color: white;
        }
        
        .educators-content {
            display: flex;
            align-items: center;
            gap: 50px;
            margin-top: 50px;
        }
        
        .educators-image {
            flex: 1;
        }
        
        .educators-image img {
            width: 100%;
            border-radius: 10px;
            box-shadow: var(--shadow);
        }
        
        .educators-text {
            flex: 1;
        }
        
        .educators-text h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--dark);
        }
        
        .educators-text p {
            margin-bottom: 20px;
        }
        
        .educators-list {
            list-style: none;
            margin: 20px 0;
        }
        
        .educators-list li {
            margin-bottom: 15px;
            padding-left: 30px;
            position: relative;
        }
        
        .educators-list li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--secondary);
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        /* Registration Section */
        .registration {
            padding: 80px 0;
            background: linear-gradient(135deg, rgba(78, 84, 200, 0.9), rgba(143, 148, 251, 0.9)), url('https://images.unsplash.com/photo-1596496181871-9681eacf9764?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
