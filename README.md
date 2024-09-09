<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanisha Singh's Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqk1w27TLihaJzM7zG+Ch9bg+07+y7lQ1ulW8K/BQPq+VyiFpz8/5GbfM1QaQxZH9mH+9cU7H2o=#" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
            overflow-x: hidden;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: center;
        }

        h1 {
            font-size: 3em;
            color: #333;
            margin-bottom: 10px;
        }

        .about-me {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
        }

        .about-me img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-right: 20px;
            border: 5px solid #333;
        }

        .about-me p {
            text-align: left;
            line-height: 1.6;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-bottom: 20px;
        }

        .skill-badge {
            margin: 5px;
            padding: 10px;
            background-color: #eee;
            border-radius: 5px;
            font-weight: bold;
            text-align: center;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .skill-badge:hover {
            transform: scale(1.1);
            background-color: #ddd;
        }

        .socials {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .social-link {
            margin: 0 10px;
            font-size: 24px;
            color: #333;
            transition: color 0.3s ease;
        }

        .social-link:hover {
            color: #5cb85c;
        }

        .stats-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-bottom: 20px;
        }

        .stats-card {
            margin: 10px;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 300px;
            transition: transform 0.3s ease;
        }

        .stats-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        }

        .stats-card h3 {
            color: #333;
            margin-bottom: 10px;
        }

        .stats-card img {
            width: 100%;
            max-width: 300px;
        }

        .quote-container {
            text-align: center;
            margin-bottom: 20px;
            padding: 20px;
            background-color: #eee;
            border-radius: 5px;
        }

        .quote-container p {
            font-style: italic;
            color: #555;
        }

        .github-stats {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .github-stats img {
            margin: 0 10px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #eee;
        }

        footer p {
            color: #333;
        }

        /* Activity Graph Styling */
        .activity-graph {
            margin-bottom: 20px;
            width: 100%;
        }

        .activity-graph img {
            width: 100%;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .stats-card {
                width: 100%;
                margin-bottom: 15px;
            }

            .github-stats img {
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Tanisha Singh</h1>
        <div class="about-me">
            <img src="https://avatars.githubusercontent.com/u/73097560?v=4" alt="Tanisha Singh">
            <p>👋 I'm Tanisha Singh from IIII BHAGALPUR (2022-26).<br>🔭 I'm diving deep into full-stack development, leveraging my React, Node.js, and Express expertise to build robust and interactive web applications.<br>👯 I'm looking to collaborate on Open Source Community.<br>💬 Beyond individual projects, I'm passionate about Artificial Intelligence and Machine Learning 💡.</p>
        </div>

        <h2>🌐 Socials:</h2>
        <div class="socials">
            <a href="https://instagram.com/tanishasingh4785" class="social-link"><i class="fab fa-instagram"></i></a>
            <a href="https://linkedin.com/in/TANISHASINGH" class="social-link"><i class="fab fa-linkedin-in"></i></a>
        </div>

        <h2>💻 Tech Stack:</h2>
        <div class="skills">
            <div class="skill-badge">C++</div>
            <div class="skill-badge">C</div>
            <div class="skill-badge">HTML5</div>
            <div class="skill-badge">GitHub Pages</div>
            <div class="skill-badge">Firebase</div>
            <div class="skill-badge">Netlify</div>
            <div class="skill-badge">Vercel</div>
            <div class="skill-badge">Angular.js</div>
            <div class="skill-badge">Bootstrap</div>
            <div class="skill-badge">Django</div>
            <div class="skill-badge">NodeJS</div>
            <div class="skill-badge">MySQL</div>
            <div class="skill-badge">MongoDB</div>
            <div class="skill-badge">Adobe</div>
            <div class="skill-badge">Figma</div>
            <div class="skill-badge">Canva</div>
            <div class="skill-badge">NumPy</div>
            <div class="skill-badge">Pandas</div>
            <div class="skill-badge">PyTorch</div>
            <div class="skill-badge">Matplotlib</div>
            <div class="skill-badge">TensorFlow</div>
        </div>

        <div class="stats-container">
            <div class="stats-card">
                <h3>GitHub Stats</h3>
                <img src="https://github-readme-stats.vercel.app/api?username=TANISHA-singh-7&theme=highcontrast&hide_border=false&include_all_commits=true&count_private=true" alt="GitHub Stats">
            </div>
            <div class="stats-card">
                <h3>GitHub Streak</h3>
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=TANISHA-singh-7&theme=highcontrast&hide_border=false" alt="GitHub Streak">
            </div>
            <div class="stats-card">
                <h3>Top Languages</h3>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TANISHA-singh-7&theme=highcontrast&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages">
            </div>
        </div>

        <div class="github-stats">
            <img src="https://github-profile-trophy.vercel.app/?username=TANISHA-singh-7&theme=radical&no-frame=false&no-bg=false&margin-w=4" alt="GitHub Trophies">
        </div>

        <div class="quote-container">
            <p>
                <iframe src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" style="width: 100%; height: 30px; border: 0;"></iframe>
            </p>
        </div>

        <div class="github-stats">
            <img src="https://github-contributor-stats.vercel.app/api?username=TANISHA-singh-7&limit=5&theme=neon&combine_all_yearly_contributions=true" alt="Top Contributed Repos">
        </div>

        <div class="activity-graph">
            <img src="https://github-readme-activity-graph.vercel.app/graph?username=TANISHA-singh-7&theme=react-dark" alt="GitHub Activity Graph">
        </div>

        <footer>
            <p>© 2023 Tanisha Singh. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
