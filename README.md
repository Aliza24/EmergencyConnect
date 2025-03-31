# EmergencyConnect
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EmergencyConnect</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(135deg, #74EBD5, #ACB6E5);
            color: #333;
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }
        header, footer {
            background: rgba(0, 0, 0, 0.9);
            color: #fff;
        }
        header nav ul {
            display: flex;
            justify-content: space-around;
            list-style: none;
            padding: 0;
        }
        header nav ul li a {
            text-decoration: none;
            color: #74EBD5;
            transition: 0.3s;
            font-weight: bold;
        }
        header nav ul li a:hover {
            color: #ff5722;
            transform: scale(1.1);
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            background: url('images/healthcare-bg.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
            animation: fadeIn 1s ease-in;
        }
        .hero-content h2 {
            font-size: 4rem;
            animation: slideIn 1.2s ease-in;
        }
        .hero-content p {
            font-size: 1.5rem;
            margin: 20px 0;
            animation: fadeIn 2s ease-in;
        }
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: #ff5722;
            color: #fff;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        .btn:hover {
            background: #e64a19;
            transform: translateY(-5px);
        }
        .stats, .services, .about, .contact, .faq, .news, .hospitals {
            padding: 80px 20px;
            text-align: center;
        }
        .services {
            background: linear-gradient(135deg, #f4f4f4, #ffffff);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        .service-container {
            display: flex;
            justify-content: space-around;
            gap: 40px;
            flex-wrap: wrap;
        }
        .service {
            background: linear-gradient(135deg, #ff5722, #ff9800);
            color: #fff;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            padding: 40px;
            border-radius: 15px;
            transition: transform 0.3s, box-shadow 0.3s;
            width: calc(30% - 20px);
            text-align: center;
            transform: scale(1);
            transition: all 0.3s ease-in-out;
        }
        .service:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 12px 30px rgba(0,0,0,0.3);
        }
        .service i {
            font-size: 4rem;
            margin-bottom: 20px;
        }
        .service h3 {
            font-size: 2rem;
            margin-bottom: 15px;
        }
        .service p {
            font-size: 1.2rem;
        }
        .footer {
            background: rgba(0, 0, 0, 0.9);
            color: #fff;
            text-align: center;
            padding: 20px 0;
            transition: all 0.3s;
        }
        .footer:hover {
            background: #333;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes slideIn {
            0% { transform: translateY(-100px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>EmergencyConnect</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                  <li><a href="hospitals.html">Hospitals</a></li>
                   <li><a href="#news">News</a></li>
                   <li><a href="#faq">FAQ</a></li>
                  <li><a href="#contact">Contact</a></li>
                    <li><a href="#about">About Us</a></li>
                  
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="hero-content">
                <h2>Saving Lives by Serving Emergencies</h2>
                <p>Connecting hospitals and nursing centers to provide easy access to blood, organs, and medical resources.</p>
                <a href="#services" class="btn">Explore Services</a>
            </div>
        </section>
        
        <section id="services" class="services">
            <h2>Our Services</h2>
            <div class="service-container">
                <div class="service">
                    <i class="fas fa-tint"></i>
                    <h3>Medical Resource Availability</h3>
                    <p>Real-time availability of medical resources across cities.</p>
                </div>
                <div class="service">
                    <i class="fas fa-heartbeat"></i>
                    <h3>Blood & Organ Donation</h3>
                    <p>Find or donate blood & organs easily.</p>
                </div>
                <div class="service">
                    <i class="fas fa-ambulance"></i>
                    <h3>Emergency Assistance</h3>
                    <p>Quick access to emergency services.</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Integrated Healthcare Network. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
