<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anand Bajpai - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
        }
        .navbar {
            transition: all 0.3s ease;
        }
        .navbar.scrolled {
            background-color: #1a202c;
        }
        .section {
            padding: 4rem 0;
        }
        .project-card {
            transition: transform 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-10px);
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar fixed top-0 w-full bg-gray-900 text-white p-4 z-10">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">Anand Bajpai</h1>
            <ul class="flex space-x-6">
                <li><a href="#home" class="hover:text-blue-400">Home</a></li>
                <li><a href="#about" class="hover:text-blue-400">About</a></li>
                <li><a href="#skills" class="hover:text-blue-400">Skills</a></li>
                <li><a href="#projects" class="hover:text-blue-400">Projects</a></li>
                <li><a href="#contact" class="hover:text-blue-400">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="section bg-gray-900 text-white flex items-center justify-center h-screen">
        <div class="text-center">
            <h2 class="text-5xl font-bold mb-4">Welcome to My Portfolio</h2>
            <p class="text-xl mb-6">Anand Bajpai | Computer Science & Engineering Student</p>
            <a href="#about" class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700">Learn More</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">About Me</h2>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-6 md:mb-0">
                    <img src="https://via.placeholder.com/300" alt="Anand Bajpai" class="rounded-full mx-auto">
                </div>
                <div class="md:w-1/2 text-center md:text-left">
                    <p class="text-lg mb-4">
                        I'm Anand Bajpai, a B.Tech student in Computer Science & Engineering at Dr. A.P.J. Abdul Kalam Technical University (2022-2026). Passionate about technology, I specialize in Python, HTML, CSS, JavaScript, and MySQL. My goal is to build innovative solutions through coding and data science.
                    </p>
                    <p class="text-lg">
                        Currently, I'm honing my skills through projects and internships, with a focus on web development and database management. Connect with me to explore opportunities!
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Programming</h3>
                    <p>Python, JavaScript</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Web Development</h3>
                    <p>HTML, CSS</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Databases</h3>
                    <p>MySQL</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Tools</h3>
                    <p>Microsoft Excel, Git</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Certifications</h3>
                    <p>Data Science Course with Guaranteed Internship</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="project-card bg-gray-100 p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-2">Personal Portfolio Website</h3>
                    <p class="mb-4">A responsive portfolio website built with HTML, CSS, and JavaScript to showcase my projects and skills. Features a contact form and project gallery.</p>
                    <a href="#" class="text-blue-600 hover:underline">View Project</a>
                </div>
                <div class="project-card bg-gray-100 p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-2">Student Database Management System</h3>
                    <p class="mb-4">A MySQL-based system to manage student records, with a front-end interface built using HTML and CSS, and Python scripts for data processing.</p>
                    <a href="#" class="text-blue-600 hover:underline">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section bg-gray-900 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8">Get in Touch</h2>
            <p class="text-lg mb-6">Feel free to reach out for collaborations or opportunities!</p>
            <div class="space-y-4">
                <p>Email: <a href="mail to:balpaianand1013871@gmail.com" class="hover:text-blue-400">balpaianand1013871@gmail.com</a></p>
                <p>Phone no: <a href="#" class="hover:text-blue-400">+91 7897478339</a></p>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/anandbajpai-48a314298" class="hover:text-blue-400">linkedin.com/in/anandbajpai</a></p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Anand Bajpai. All rights reserved.</p>
        </div>
    </footer>

    <!-- JavaScript for Navbar Scroll Effect -->
    <script>
        window.addEventListener('scroll', () => {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });
    </script>
</body>
</html>
