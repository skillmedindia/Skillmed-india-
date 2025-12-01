<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SkillMed India - Nation's Largest CPR & First Aid School Training Program</title>
    <meta name="description" content="SkillMed India empowers school students with CPR, First Aid, Disaster Management & Emergency Response training across India." />

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Arial, sans-serif;
            background: #f4f7fb;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #0061ff, #4dabff);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        nav {
            background: white;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            padding: 12px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            margin: 0 18px;
            text-decoration: none;
            color: #0061ff;
            font-weight: bold;
            font-size: 16px;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1580281657527-47d5c99c7b5d?auto=format&fit=crop&w=1400&q=60') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 140px 20px;
        }

        .hero h1 {
            font-size: 3.2em;
            margin: 0;
            font-weight: 700;
        }

        .hero p {
            font-size: 1.4em;
            margin-top: 15px;
        }

        .btn {
            background: #28a745;
            padding: 12px 26px;
            color: white;
            border-radius: 6px;
            text-decoration: none;
            font-size: 18px;
            display: inline-block;
            margin-top: 20px;
        }

        section {
            max-width: 1200px;
            margin: auto;
            padding: 50px 25px;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            grid-gap: 30px;
        }

        .feature-box {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            text-align: center;
        }

        .courses ul {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            list-style: none;
            line-height: 1.8;
        }

        form {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: auto;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 6px;
            border: 1px solid #ccc;
        }

        button {
            background: #0061ff;
            color: white;
            border: none;
            padding: 12px;
            width: 100%;
            font-size: 18px;
            border-radius: 6px;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #1f2937;
            color: white;
        }
    </style>
</head>

<body>
    <header>
        <h1>SkillMed India</h1>
        <p>Nation's Largest CPR & First Aid Training Program for School Students</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#programs">Programs</a>
        <a href="#impact">Impact</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <h1>Empowering Young India with Life‑Saving Skills</h1>
        <p>CPR • First Aid • Disaster Management • Emergency Response</p>
        <a href="#contact" class="btn">Register Your School</a>
    </section>

    <section id="about">
        <h2>About SkillMed India</h2>
        <p>SkillMed India is a national-level initiative designed to make every Indian school student confident in emergencies. We train students in CPR, First Aid, Injury Prevention, Emergency Response, and Disaster Preparedness with real-life simulations and certified instructors.</p>

        <div class="features">
            <div class="feature-box">
                <h3>Certified Instructors</h3>
                <p>Our trainers include doctors, EMTs, nurses, and certified first responders.</p>
            </div>

            <div class="feature-box">
                <h3>Hands-On Training</h3>
                <p>Live CPR mannequins, AED demos, bleeding control kits & real-life scenarios.</p>
            </div>

            <div class="feature-box">
                <h3>Government-Aligned Mission</h3>
                <p>Supporting National Education Policy (NEP) goals for health & safety literacy.</p>
            </div>
        </div>
    </section>

    <section id="programs" class="courses">
        <h2>Our Training Programs</h2>
        <ul>
            <li><strong>CPR Training:</strong> Chest compressions, rescue breaths & AED awareness.</li>
            <li><strong>First Aid Essentials:</strong> Burns, cuts, fractures, choking, bleeding control.</li>
            <li><strong>Disaster Management:</strong> Fire safety, evacuation drills, risk management.</li>
            <li><strong>Emergency Response:</strong> Assessment, call for help, safe intervention.</li>
            <li><strong>School Safety Workshops:</strong> Teacher + student combined modules.</li>
        </ul>
    </section>

    <section id="impact">
        <h2>Our Impact</h2>
        <p>SkillMed India is rapidly expanding with the goal to train <strong>1 Crore+ school students</strong> by 2030.</p>

        <div class="features">
            <div class="feature-box">
                <h3>150+ Schools Trained</h3>
                <p>Across multiple states in India.</p>
            </div>
            <div class="feature-box">
                <h3>50,000+ Students Certified</h3>
                <p>Learning CPR, First Aid & emergency handling.</p>
            </div>
            <div class="feature-box">
                <h3>National Training Team</h3>
                <p>Medical professionals leading every workshop.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>

        <form id="contactForm">
            <input type="text" placeholder="Your Name" required />
            <input type="email" placeholder="Your Email" required />
            <textarea placeholder="Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>

        <p style="text-align:center; margin-top:20px;">Email: info@skillmedindia.com | Phone: +91 98765 43210</p>
    </section>

    <footer>
        <p>© 2025 SkillMed India — CPR & First Aid Training Initiative</p>
    </footer>

    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you! Our team will contact you shortly.');
        });
    </script>
</body>
</html>
