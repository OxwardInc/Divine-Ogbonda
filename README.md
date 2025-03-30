<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        h1, h3, p {
            opacity: 0;
            animation: fadeIn 1s forwards ease-in-out;
        }
        img {
            max-width: 100%;
        }
        .section {
            margin: 30px 0;
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }
        .visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>

    <h1 class="animate__animated animate__fadeInDown">Hi 👋, I'm Divine Ogbonda</h1>
    <h3 class="animate__animated animate__fadeInUp">A Data Engineer & Business Analyst | Founder & CEO of Dispatch Hub</h3>

    <p class="section">
        <a href="https://www.linkedin.com/in/divine-ogbonda-625014179/">
            <img src="https://img.shields.io/badge/LinkedIn-DivineOgbonda-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
        </a>
        <a href="mailto:oxward@dispatchhub.org">
            <img src="https://img.shields.io/badge/Email-oxward@dispatchhub.org-red?style=flat-square&logo=gmail" alt="Email">
        </a>
    </p>

    <div class="section">
        <h2>🔥 About Me</h2>
        <p>💼 CEO & Founder of <a href="https://dispatchhub.org">Dispatch Hub</a></p>
        <p>🚀 Experienced in Data Engineering, SQL, Python, NLP & Machine Learning</p>
        <p>📊 Passionate about Business Analysis, ETL Pipelines, and Data Warehousing</p>
        <p>🌍 Building scalable logistics solutions for e-commerce in Nigeria</p>
    </div>

    <div class="section">
        <h2>🚀 Tech Stack</h2>
        <img src="https://skillicons.dev/icons?i=python,postgres,django,aws,html,css,js,react,github"/>
    </div>

    <div class="section">
        <h2>📈 GitHub Stats</h2>
        <img src="https://github-readme-stats.vercel.app/api?username=OxwardInc&show_icons=true&theme=dark" width="48%">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=OxwardInc&layout=compact&theme=dark" width="48%">
        <br>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=OxwardInc&theme=dark" width="48%">
        <img src="https://github-readme-activity-graph.cyclic.app/graph?username=OxwardInc&theme=github-dark" width="100%">
    </div>

    <div class="section">
        <h2>📫 Connect with Me</h2>
        <a href="https://www.linkedin.com/in/divine-ogbonda-625014179/">
            <img src="https://img.shields.io/badge/LinkedIn-DivineOgbonda-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
        </a>
        <a href="mailto:oxward@dispatchhub.org">
            <img src="https://img.shields.io/badge/Email-oxward@dispatchhub.org-red?style=for-the-badge&logo=gmail" alt="Email">
        </a>
    </div>

    <script>
        const sections = document.querySelectorAll('.section');
        window.addEventListener('scroll', () => {
            sections.forEach(section => {
                const sectionTop = section.getBoundingClientRect().top;
                if (sectionTop < window.innerHeight - 100) {
                    section.classList.add('visible');
                }
            });
        });
    </script>
</body>
</html>
