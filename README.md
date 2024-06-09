<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dinesh's GitHub Profile</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }

        h1, h3 {
            margin: 10px 0;
        }

        .social-icons a,
        .skills img {
            margin: 10px;
            transition: transform 0.3s ease;
        }

        .social-icons a:hover,
        .skills img:hover {
            transform: scale(1.1);
        }

        .stats img {
            margin: 20px 0;
            width: 100%;
        }

        .animate-fade-in {
            animation: fadeIn 2s;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .animate-bounce {
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-30px);
            }
            60% {
                transform: translateY(-15px);
            }
        }

        .gradient {
            background: linear-gradient(45deg, #6a11cb 0%, #2575fc 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1 class="animate-fade-in gradient">Hi 👋, I'm Dinesh</h1>
        <h3 class="animate-fade-in gradient">A Competitive Programmer and ML Enthusiast</h3>
        <img src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" width="100%" height="400" alt="Coding Gif" class="animate-fade-in">

        <ul>
            <li>🔭 I’m currently working on <strong>code tracker website</strong></li>
            <li>🌱 I’m currently learning <strong>Tensorflow</strong></li>
            <li>💬 Ask me about <strong>C++, Python, Machine Learning</strong></li>
            <li>📫 How to reach me <strong>dinesharagonda79@gmail.com</strong></li>
        </ul>

        <h3 class="gradient">Connect with me:</h3>
        <p class="social-icons">
            <a href="https://linkedin.com/in/dinesh-aragonda" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="40" width="40" />
            </a>
            <a href="https://fb.com/dinesh.aragonda" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="40" width="40" />
            </a>
            <a href="https://instagram.com/dinesh_aragonda" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="40" width="40" />
            </a>
        </p>

        <h3 class="gradient">Languages and Tools:</h3>
        <p class="skills">
            <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40" />
            </a>
            <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40" />
            </a>
            <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40" />
            </a>
            <a href="https://expressjs.com" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" width="40" height="40" />
            </a>
            <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40" />
            </a>
            <a href="https://www.java.com" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="40" height="40" />
            </a>
            <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40" />
            </a>
            <a href="https://nodejs.org" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40" />
            </a>
            <a href="https://www.python.org" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40" />
            </a>
            <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40" />
            </a>
        </p>

        <h3 class="gradient">My GitHub Stats:</h3>
        <p class="stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=dinesh-aragonda-79&show_icons=true&locale=en&layout=compact" alt="Dinesh's Top Languages" class="animate-fade-in">
            <img src="https://github-readme-stats.vercel.app/api?username=dinesh-aragonda-79&show_icons=true&locale=en" alt="Dinesh's GitHub Stats" class="animate-fade-in">
        </p>
    </div>
</body>

<script>
    document.addEventListener("DOMContentLoaded", function () {
        const gradientTextElements = document.querySelectorAll('.gradient');
        gradientTextElements.forEach(element => {
            element.style.background = 'linear-gradient(45deg, #6a11cb, #2575fc)';
            element.style.webkitBackgroundClip = 'text';
            element.style.webkitTextFillColor = 'transparent';
        });
    });
</script>

</html>
