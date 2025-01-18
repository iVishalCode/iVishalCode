<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive README</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(120deg, #1a73e8, #4285f4);
            color: #fff;
            text-align: center;
        }
        h1 {
            margin-top: 20px;
            font-size: 2.5rem;
        }
        h3 {
            font-weight: 300;
            margin: 20px 0;
        }
        .content {
            padding: 20px;
        }
        .section {
            margin: 30px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .icons img {
            margin: 10px;
            width: 50px;
            cursor: pointer;
            transition: transform 0.3s;
        }
        .icons img:hover {
            transform: scale(1.2);
        }
        .tech-stack {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            padding: 10px 0;
        }
        .badge {
            padding: 5px 10px;
            border-radius: 5px;
            background: rgba(255, 255, 255, 0.3);
            font-weight: bold;
            display: inline-block;
        }
        footer {
            margin-top: 30px;
            font-size: 0.8rem;
        }
        .fade-in {
            opacity: 0;
            animation: fadeIn 1s forwards;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Hi 👋, I'm Vishal</h1>
        <h3 class="fade-in">A passionate Full-Stack Developer from India, specializing in scalable and efficient web applications.</h3>

        <div class="section">
            <h3>🌱 Currently Learning</h3>
            <p>TypeScript</p>
        </div>

        <div class="section">
            <h3>💬 Ask Me About</h3>
            <p>JavaScript, React.js, PHP, Express.js, Mongoose</p>
        </div>

        <div class="section">
            <h3>📫 How to Reach Me</h3>
            <p><a href="mailto:ilearnvk@gmail.com" style="color: #FFD700; text-decoration: none;">ilearnvk@gmail.com</a></p>
        </div>

        <div class="section">
            <h3>⚡ Fun Fact</h3>
            <p>Did you know? When I'm not coding, I love hiking adventures! 🌲🚶‍♂️</p>
        </div>

        <div class="section">
            <h3>🛠️ Tech Stack</h3>
            <div class="tech-stack">
                <span class="badge">JavaScript</span>
                <span class="badge">TypeScript</span>
                <span class="badge">Node.js</span>
                <span class="badge">Express.js</span>
                <span class="badge">MongoDB</span>
                <span class="badge">PostgreSQL</span>
                <span class="badge">React</span>
                <span class="badge">Next.js</span>
                <span class="badge">Tailwind CSS</span>
                <span class="badge">Docker</span>
                <span class="badge">Kubernetes</span>
                <span class="badge">AWS</span>
            </div>
        </div>

        <div class="section">
            <h3>📈 GitHub Stats</h3>
            <img src="https://github-readme-stats.vercel.app/api?username=iVishalCode&show_icons=true&theme=radical" alt="GitHub Stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iVishalCode&layout=compact&theme=radical" alt="Top Languages">
        </div>

        <div class="section">
            <h3>Connect with Me</h3>
            <div class="icons">
                <a href="https://linkedin.com/in/vishal-kumar-779054260" target="_blank">
                    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                </a>
                <a href="https://twitter.com/iVishalCode" target="_blank">
                    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
                </a>
                <a href="mailto:ilearnvk@gmail.com" target="_blank">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                </a>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Vishal | Made with HTML, CSS, and JavaScript</p>
    </footer>
</body>
</html>
