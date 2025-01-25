<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ahmad Afzal - Developer Profile</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/animejs@3.2.1/lib/anime.min.js"></script>
    <style>
        @keyframes gradient-animation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .tech-icon {
            transition: transform 0.3s ease, filter 0.3s ease;
        }
        .tech-icon:hover {
            transform: scale(1.2);
            filter: brightness(1.2);
        }
        .gradient-text {
            background: linear-gradient(45deg, #6a11cb 0%, #2575fc 100%);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            animation: gradient-animation 5s ease infinite;
            background-size: 400% 400%;
        }
    </style>
</head>
<body class="bg-gray-900 text-white">
    <div class="container mx-auto px-4 py-8">
        <div class="text-center">
            <h1 class="text-5xl font-bold gradient-text mb-4">Ahmad Afzal</h1>
            <h3 class="text-2xl text-gray-300 mb-6">Code like a poet, debug like a detective</h3>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-gray-800 rounded-lg p-6 shadow-lg">
                <h3 class="text-2xl font-semibold mb-4 text-blue-400">About Me</h3>
                <ul class="space-y-2">
                    <li>🔭 Currently working on: <span class="text-green-400">MedTalk (Medical Diagnostic System)</span></li>
                    <li>🌱 Learning: <span class="text-purple-400">Cloud Computing</span></li>
                    <li>💬 Expertise: MERN Stack, Machine Learning, NLP, Computer Vision</li>
                </ul>
            </div>

            <div class="bg-gray-800 rounded-lg p-6 shadow-lg">
                <h3 class="text-2xl font-semibold mb-4 text-blue-400">Contact</h3>
                <div class="flex space-x-4 justify-center">
                    <a href="mailto:ahmadafzalch007@gmail.com" class="hover:text-blue-500">📧 Email</a>
                    <a href="https://linkedin.com/in/ahmed-afzal-0074981b8" class="hover:text-blue-500">LinkedIn</a>
                    <a href="https://github.com/ahmadafzal007" class="hover:text-blue-500">GitHub</a>
                </div>
            </div>
        </div>

        <div class="mt-8">
            <h3 class="text-3xl text-center mb-6 gradient-text">Technologies & Tools</h3>
            <div class="grid grid-cols-6 gap-6 place-items-center">
                <!-- Existing Technologies -->
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" class="w-20 h-20 tech-icon" />
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" class="w-20 h-20 tech-icon" />
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="python" class="w-20 h-20 tech-icon" />
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" class="w-20 h-20 tech-icon" />
                
                <!-- New Technologies -->
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" class="w-20 h-20 tech-icon" />
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain-wordmark.svg" alt="django" class="w-20 h-20 tech-icon" />
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="tensorflow" class="w-20 h-20 tech-icon" />
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" class="w-20 h-20 tech-icon" />
            </div>
        </div>
    </div>

    <script>
        // Optional: Add some subtle animations
        anime({
            targets: '.tech-icon',
            translateY: [
                { value: -10, duration: 800 },
                { value: 0, duration: 800 }
            ],
            loop: true,
            easing: 'easeInOutQuad'
        });
    </script>
</body>
</html>
