<!DOCTYPE html>
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
            background: linear-gradient(135deg, rgba(78, 84, 200, 0.9), rgba(143, 148, 251, 0.9)), url('https://images.unsplash.com
