<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shivam Pathak - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            padding: 40px 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        .animated-title {
            font-size: 2.5rem;
            font-weight: 700;
            color: #fff;
            margin-bottom: 10px;
            opacity: 0;
            animation: fadeInUp 1s ease forwards;
        }

        .wave {
            display: inline-block;
            animation: wave 1.5s ease-in-out infinite;
            transform-origin: 70% 70%;
        }

        h3 {
            font-size: 1.4rem;
            color: #58a6ff;
            margin: 15px 0;
        }

        p {
            margin: 10px 0;
            font-size: 1.05rem;
        }

        h2 {
            font-size: 1.8rem;
            color: #fff;
            margin: 30px 0 20px 0;
            border-bottom: 2px solid #30363d;
            padding-bottom: 10px;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }

        .tech-badge {
            display: inline-block;
            padding: 8px 16px;
            background: #21262d;
            border: 1px solid #30363d;
            border-radius: 6px;
            color: #c9d1d9;
            font-weight: 600;
            font-size: 0.9rem;
            transition: transform 0.2s, background 0.2s;
        }

        .tech-badge:hover {
            transform: translateY(-2px);
            background: #30363d;
        }

        .tech-badge.python { border-left: 3px solid #3776AB; }
        .tech-badge.fastapi { border-left: 3px solid #009688; }
        .tech-badge.sklearn { border-left: 3px solid #F7931E; }
        .tech-badge.pandas { border-left: 3px solid #2C2D72; }
        .tech-badge.numpy { border-left: 3px solid #4D77CF; }
        .tech-badge.matplotlib { border-left: 3px solid #11557C; }
        .tech-badge.seaborn { border-left: 3px solid #5E4FA2; }
        .tech-badge.sql { border-left: 3px solid #336791; }
        .tech-badge.git { border-left: 3px solid #F05032; }
        .tech-badge.jupyter { border-left: 3px solid #F37626; }

        ul {
            list-style: none;
            margin: 15px 0;
        }

        ul li {
            padding: 10px 0;
            padding-left: 25px;
            position: relative;
        }

        ul li:before {
            content: "▹";
            position: absolute;
            left: 0;
            color: #58a6ff;
            font-size: 1.2rem;
        }

        .connect-links {
            display: flex;
            gap: 15px;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .connect-btn {
            padding: 10px 20px;
            background: #21262d;
            border: 1px solid #30363d;
            border-radius: 6px;
            color: #c9d1d9;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.2s;
        }

        .connect-btn:hover {
            background: #30363d;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(88, 166, 255, 0.3);
        }

        .connect-btn.email { border-left: 3px solid #D14836; }
        .connect-btn.linkedin { border-left: 3px solid #0077B5; }
        .connect-btn.github { border-left: 3px solid #fff; }

        hr {
            border: none;
            border-top: 1px solid #30363d;
            margin: 30px 0;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            color: #8b949e;
            font-size: 0.95rem;
        }

        .footer a {
            color: #58a6ff;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        strong {
            color: #58a6ff;
            font-weight: 600;
        }

        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
            from {
                opacity: 0;
                transform: translateY(30px);
            }
        }

        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(20deg); }
            75% { transform: rotate(-15deg); }
        }

        @media (max-width: 768px) {
            .animated-title {
                font-size: 1.8rem;
            }
            
            .tech-stack {
                gap: 8px;
            }
            
            .connect-links {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="animated-title">Hi there, I'm Shivam Pathak <span class="wave">👋</span></h1>
        
        <h3>Python Developer | Data Analyst | Data Scientist</h3>
        
        <p>🎓 Computer Science Graduate (June 2025)</p>
        <p>💻 Specializing in <strong>Python Development, Data Science, and Machine Learning</strong></p>
        <p>📊 Interested in <strong>Data Analysis, AI, and Scalable Applications</strong></p>
        <p>✅ TCS NQT 2025 Qualified</p>
        
        <hr>
        
        <h2>🚀 Tech Stack</h2>
        <div class="tech-stack">
            <span class="tech-badge python">Python</span>
            <span class="tech-badge fastapi">FastAPI</span>
            <span class="tech-badge sklearn">Scikit-learn</span>
            <span class="tech-badge pandas">Pandas</span>
            <span class="tech-badge numpy">NumPy</span>
            <span class="tech-badge matplotlib">Matplotlib</span>
            <span class="tech-badge seaborn">Seaborn</span>
            <span class="tech-badge sql">SQL</span>
            <span class="tech-badge git">Git</span>
            <span class="tech-badge jupyter">Jupyter</span>
        </div>
        
        <hr>
        
        <h2>🏆 Achievements & Certifications</h2>
        <ul>
            <li>Cleared <strong>TCS National Qualifier Test (NQT) 2025</strong>, shortlisted for Ninja role interview (Top 10% nationwide)</li>
            <li>Represented state at <strong>National Basketball Championship</strong> 🏀 (teamwork, leadership, performance under pressure)</li>
            <li>Completed <strong>Google Cloud Skills Boost – Generative AI Fundamentals (2024)</strong></li>
            <li>Earned <strong>Python Development Internship Certificate – Cognifyz Technologies (2024)</strong></li>
            <li>Active problem solver on coding platforms with focus on <strong>DSA optimization</strong></li>
        </ul>
        
        <hr>
        
        <h2>📫 Connect with Me</h2>
        <div class="connect-links">
            <a href="mailto:pathakshivam3738@gmail.com" class="connect-btn email">📧 Email</a>
            <a href="https://linkedin.com/in/shivam-pathak-9a76ba246" class="connect-btn linkedin" target="_blank">💼 LinkedIn</a>
            <a href="https://github.com/shivampathak2812" class="connect-btn github" target="_blank">🐙 GitHub</a>
        </div>
        
        <hr>
        
        <div class="footer">
            ⭐️ From <a href="https://github.com/shivampathak2812" target="_blank">shivampathak2812</a>
        </div>
    </div>
</body>
</html>
