<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 40px 0;
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            transition: transform 0.3s ease-in-out;
        }

        header img:hover {
            transform: scale(1.1);
        }

        header .name {
            margin-top: 20px;
        }

        .skills,
        .education,
        .job-experience,
        .contact {
            background-color: #fff;
            padding: 40px 20px;
            margin-top: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            display: inline-block;
            margin: 0 10px;
        }

        a {
            color: #3498db;
            text-decoration: none;
            transition: color 0.3s ease-in-out;
        }

        a:hover {
            color: #2070af;
        }

        footer {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
    <title>Your Professional Portfolio</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="C:\Users\gopal\OneDrive\Documents\Desktop\ANJL9833.JPG .JPG" "alt=your photo">
            <div class="name">
                <h1>BIJJAM GOPAL REDDY</h1>
                <p>Web Developer</p>
            </div>
        </div>
    </header>

    <section class="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>            
                <li>Google Cloud</li>
                <!-- Add more skills as needed -->
            </ul>
        </div>
    </section>

    <section class="education">
        <div class="container">
            <h2>Education</h2>
            <div class="education-item">
                <h3>University Name: Mohan Babu University</h3>
                <p>Degree in Computer Science and Engineering</p>
                <p>Year of Graduation: 2026</p>
            </div>
        </div>
    </section>

    <section class="job-experience">
        <div class="container">
            <h2>Job Experience</h2>
            <div class="job-item">
                <h3>Company Name</h3>
                <p>Position: Web Developer</p>
                <p>Duration: Fresher</p>
                <!-- Add more job experience as needed -->
            </div>
        </div>
    </section>

    <section class="contact">
        <div class="container">
            <h2>Contact</h2>
            <ul>
                <li>Email: <a href="gopalreddybijjam846@gmail.com">gopalreddybijjam846@gmail.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/gopal-reddy-5b5b15267?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BG47m%2FkD5R5SfPnGQRncM8Q%3D%3D" target="_blank">LinkedIn</a></li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Professional Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
