<!DOCTYPE html>
<html>
<head>
    <title>My Personal Portfolio</title>
    <style>
          {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #e0f7ff;
            color: #2c3e50;
            line-height: 1.6;
        }

        header {
            background-color: #ffc6e0;
            padding: 30px;
            text-align: center;
        }
        .profile {
	background: white; 
	width: 320px; 
	margin: 30px auto; 
	padding: 20px; 
	border-radius: 20px; 
	box-shadow: 0 4px 10px #e8a5c0;
        }
	.photo {
	width: 110px; 
	height: 110px; 
	border-radius: 50%; 
	border: 4px solid pink; 
	object-fit: cover;
	}
        h1 {
            color: #d63384;
            font-size: 28px;
        }

        nav {
            background-color: #b3e5fc;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
        }

        nav a {
            display: inline-block;
            background-color: #ff87b5;
            color: white;
            padding: 10px 20px;
            margin: 5px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: #d63384;
        }

        section {
            padding: 30px;
            max-width: 900px;
            margin: 0 auto;
        }

        h2 {
            color: #d63384;
            border-bottom: 3px solid #b3e5fc;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .card {
            background-color: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        .skills-list {
            list-style: none;
        }

        .skills-list li {
            background-color: #e0f7ff;
            margin: 8px 0;
            padding: 10px 15px;
            border-radius: 8px;
        }

        .code-box {
            background-color: #2c3e50;
            color: #f8f8f8;
            padding: 20px;
            border-radius: 10px;
            font-family: monospace;
            font-size: 13px;
            overflow-x: auto;
            line-height: 1.5;
        }

        footer {
            background-color: #ffc6e0;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <!-- HEADER / PERSONAL INFO -->
    <header id="home">
        <img src="IMG_20251230_125805_263.jpg class=
"photo" alt="My Profile Picture">
        <h1>Delo Cristine Canonizado </h1>
        <p>BS Information Technology — 1-C</p>
        <p>Email: cathqt2627@gmail.com | Phone: 0965-550-3388</p>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Me</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#java">Java Code</a>
    </nav>

    <!-- ABOUT ME -->
    <section id="about">
        <h2> Personal Information</h2>
        <div class="card">
            <p><strong>Full Name:</strong> Delo Cristine Canonizado</p>
            <p><strong+>Nickname:</strong> Kikay</p>
            <p><strong>Age:</strong> 18</p>
            <p><strong>Location:</strong> Lennec Sitio Sanfelipe Guimba, Nueva Ecija</p>
            <p>Hi there! It's me Tin🌸 I'm a first-year BSIT student at Our Lady of the Sacred Heart College. I am passionate about technology, learning how computers work, and creating simple programs. My goal is to become a skilled IT professional who can help others through technology. I am hardworking, eager to learn more, and always ready for new challenges.</p>
        </div>
    </section>
    <!-- EDUCATION -->
    <section id="education">
        <h2> Educational Background</h2>
        <div class="card">
            <h3>College</h3>
            <p><strong>Our Lady of the Sacred Heart College, Inc.</strong></p>
            <p>Bachelor of Science in Information Technology</p>
            <p>2026 Present</p>
            <br>
            <h3>Senior High School</h3>
            <p><strong>Pacac Senior High School</strong></p>
            <p>ABM — Accountancy, Business And Management Strand</p>
            <p>2026 — 2025</p>
            <br>
            <h3>Junior High School</h3>
            <p><strong>Pacac Junior High School</strong></p>
            <p>2024 — 2023</p>
        </div>
    </section>

    <!-- SKILLS -->
    <section id="skills">
        <h2>Technical Skills</h2>
        <div class="card">
            <ul class="skills-list">
                <li> Basic HTML & CSS — creating a simple webpages for my portfolio</li>
                <li> Java Programming — understanding logical for my portfolio systems</li>
                <li> Microsoft Offic
