<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 800px;
            padding: 20px;
            text-align: center;
        }
        h1 {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            color: #ff6347;
        }
        h2 {
            font-family: 'Verdana', sans-serif;
            color: #4682b4;
        }
        .section {
            margin: 20px 0;
        }
        .contact-icons {
            font-size: 24px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }
        .contact-icons a {
            color: #4682b4;
            text-decoration: none;
        }
        .contact-icons a:hover {
            color: #ff6347;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My Web Portfolio</h1>
        
        <div class="section">
            <h2>Bio Data</h2>
            <p>Hello! My name is [Your Name], a passionate biochemist with a keen interest in molecular biology and software engineering.</p>
        </div>
        
        <div class="section">
            <h2>Education Background</h2>
            <p>Graduated from South Eastern Kenya University (SEKU) with a BSc in Biochemistry and Molecular Biology.</p>
        </div>
        
        <div class="section">
            <h2>Work Experience</h2>
            <p>Currently working as an Intern Laboratory Analyst, gaining hands-on experience in biochemical analysis and laboratory techniques.</p>
        </div>
        
        <div class="section">
            <h2>Contact</h2>
            <div class="contact-icons">
                <a href="mailto:your.email@example.com" title="Email">
                    <img src="https://img.icons8.com/color/48/000000/email.png" alt="Email Icon">
                </a>
                <a href="https://www.linkedin.com/in/your-profile" title="LinkedIn">
                    <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn Icon">
                </a>
                <a href="https://github.com/your-profile" title="GitHub">
                    <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png" alt="GitHub Icon">
                </a>
            </div>
        </div>
    </div>
</body>
</html>
