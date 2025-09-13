<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Godwin Izibili | Professional Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        deepblue: {
                            50: '#000a1a',
                            100: '#000918',
                            200: '#000816',
                            300: '#000714',
                            400: '#000612',
                            500: '#000510',
                            600: '#00040e',
                            700: '#00030c',
                            800: '#00020a',
                            900: '#000108',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .hero-bg {
            background: linear-gradient(135deg, rgba(0, 6, 18, 0.95) 0%, rgba(0, 10, 26, 0.9) 100%);
        }
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
        }
        .timeline-item:not(:last-child)::after {
            content: '';
            position: absolute;
            left: 1.25rem;
            top: 2.5rem;
            height: calc(100% - 2.5rem);
            width: 2px;
            background-color: #e5e7eb;
        }
    </style>
</head>
<body class="bg-gray-50 font-sans antialiased">
    <!-- Hero Section with Vanta.js Background -->
    <div id="hero" class="relative hero-bg text-white overflow-hidden">
        <div class="absolute inset-0 z-0" id="vanta-bg"></div>
        <div class="container mx-auto px-6 py-24 md:py-32 relative z-10">
            <div class="max-w-3xl mx-auto text-center" data-aos="fade-up">
                <h1 class="text-4xl md:text-6xl font-bold mb-4">Godwin Izibili</h1>
                <p class="text-xl md:text-2xl mb-8">AST*QA, MSc, MBA | Researcher & Educator</p>
                <div class="flex justify-center space-x-4">
                    <a href="#about" class="px-6 py-3 bg-white text-deepblue-700 rounded-full font-medium hover:bg-gray-100 transition duration-300">
                        Learn More
                    </a>
                    <a href="#contact" class="px-6 py-3 border-2 border-white text-white rounded-full font-medium hover:bg-white hover:text-deepblue-700 transition duration-300">
                        Contact Me
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Navigation -->
    <nav class="sticky top-0 bg-white shadow-md z-50">
        <div class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <a href="#" class="text-2xl font-bold text-deepblue-700">G.I.</a>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-gray-700 hover:text-deepblue-600 transition">About</a>
                    <a href="#experience" class="text-gray-700 hover:text-deepblue-600 transition">Experience</a>
                    <a href="#education" class="text-gray-700 hover:text-deepblue-600 transition">Education</a>
                    <a href="#skills" class="text-gray-700 hover:text-deepblue-600 transition">Skills</a>
                    <a href="#projects" class="text-gray-700 hover:text-deepblue-600 transition">Projects</a>
                    <a href="#contact" class="text-gray-700 hover:text-deepblue-600 transition">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none" id="menu-toggle">
                    <i data-feather="menu"></i>
                </button>
            </div>
            <div class="md:hidden hidden py-2" id="mobile-menu">
                <a href="#about" class="block py-2 text-gray-700 hover:text-deepblue-600 transition">About</a>
                <a href="#experience" class="block py-2 text-gray-700 hover:text-deepblue-600 transition">Experience</a>
                <a href="#education" class="block py-2 text-gray-700 hover:text-deepblue-600 transition">Education</a>
                <a href="#skills" class="block py-2 text-gray-700 hover:text-deepblue-600 transition">Skills</a>
                <a href="#projects" class="block py-2 text-gray-700 hover:text-deepblue-600 transition">Projects</a>
                <a href="#contact" class="block py-2 text-gray-700 hover:text-deepblue-600 transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">About Me</h2>
                <div class="flex flex-col md:flex-row items-center gap-8">
                    <div class="w-full md:w-1/3" data-aos="fade-right">
                        <img src="http://static.photos/technology/640x360/42" alt="Godwin Izibili" class="rounded-lg shadow-xl w-full">
                    </div>
                    <div class="w-full md:w-2/3" data-aos="fade-left">
                        <p class="text-lg text-gray-700 mb-6">
                            Enthusiastic educator and researcher with a multidisciplinary background in Information Technology, Business Administration, and Engineering. Experienced in teaching, curriculum development, and academic research.
                        </p>
                        <p class="text-lg text-gray-700 mb-6">
                            Passionate about fostering diversity and inclusion in STEM education and committed to supporting the success of all students through innovative pedagogy and holistic student engagement.
                        </p>
                        <div class="grid grid-cols-2 gap-4">
                            <div class="flex items-center">
                                <i data-feather="map-pin" class="text-deepblue-600 mr-2"></i>
                                <span class="text-gray-700">Media, PA</span>
                            </div>
                            <div class="flex items-center">
                                <i data-feather="mail" class="text-deepblue-600 mr-2"></i>
                                <span class="text-gray-700">godwin.izibili@gmail.com</span>
                            </div>
                            <div class="flex items-center">
                                <i data-feather="phone" class="text-deepblue-600 mr-2"></i>
                                <span class="text-gray-700">(620) 757-8528</span>
                            </div>
                            <div class="flex items-center">
                                <i data-feather="linkedin" class="text-deepblue-600 mr-2"></i>
                                <a href="https://www.linkedin.com/in/gizibili" class="text-gray-700 hover:text-deepblue-600 transition">LinkedIn Profile</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">Work Experience</h2>
            <div class="max-w-4xl mx-auto">
                <div class="space-y-8">
                    <!-- Experience Item 1 -->
                    <div class="bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
                        <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                            <h3 class="text-xl font-bold text-deepblue-700">Lecturer</h3>
                            <span class="text-gray-600">July 2025 - Present</span>
                        </div>
                        <p class="text-gray-700 font-medium mb-2">Pennsylvania State University | Media, PA</p>
                        <ul class="list-disc pl-5 space-y-2 text-gray-700">
                            <li>Implement pedagogical strategies and college-wide policies to support student success.</li>
                            <li>Guide students in aligning goals and performance with academic requirements.</li>
                            <li>Cultivate a positive learning environment through proficient classroom management.</li>
                        </ul>
                    </div>

                    <!-- Experience Item 2 -->
                    <div class="bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
                        <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                            <h3 class="text-xl font-bold text-deepblue-700">Assistant Professor</h3>
                            <span class="text-gray-600">Aug 2024 - July 2025</span>
                        </div>
                        <p class="text-gray-700 font-medium mb-2">Garden City Community College | Garden City, KS</p>
                        <ul class="list-disc pl-5 space-y-2 text-gray-700">
                            <li>Supported students through pedagogy and implementation of college policies.</li>
                            <li>Fostered a positive collaborative atmosphere and promoted active learning.</li>
                            <li>Developed and delivered curriculum emphasizing diverse instructional strategies.</li>
                        </ul>
                    </div>

                    <!-- Experience Item 2 -->
                    <div class="bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
                        <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                            <h3 class="text-xl font-bold text-deepblue-700">Graduate Research Assistant</h3>
                            <span class="text-gray-600">May 2024 – August 2024</span>
                        </div>
                        <p class="text-gray-700 font-medium mb-2">Emporia State University | Emporia, KS</p>
                        <ul class="list-disc pl-5 space-y-2 text-gray-700">
                            <li>Research topics and conduct literature reviews.</li>
                            <li>Collect and log data and use software tools to manage/analyze data.</li>
                            <li>Document research processes and keep records of test results and findings.</li>
                        </ul>
                    </div>

                    <!-- Add more experience items following the same pattern -->
                    <!-- Experience Item 3 -->
                    <div class="bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
                        <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                            <h3 class="text-xl font-bold text-deepblue-700">Graduate Teaching Assistant</h3>
                            <span class="text-gray-600">Aug 2022 – May 2024</span>
                        </div>
                        <p class="text-gray-700 font-medium mb-2">Emporia State University | Emporia, KS</p>
                        <ul class="list-disc pl-5 space-y-2 text-gray-700">
                            <li>Mentored students through pedagogy (teaching) and applying university-wide policies and procedures.</li>
                            <li>Ensured effective student learning outcomes, professional development, and active learning.</li>
                            <li>Created integrative learning through interpersonal relationships with students.</li>
                        </ul>
                    </div>

                    <!-- Experience Item 4 -->
                    <div class="bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
                        <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                            <h3 class="text-xl font-bold text-deepblue-700">Head of Operations</h3>
                            <span class="text-gray-600">May 2018 - Aug 2021</span>
                        </div>
                        <p class="text-gray-700 font-medium mb-2">Cadworks Limited | Lagos, NG</p>
                        <ul class="list-disc pl-5 space-y-2 text-gray-700">
                            <li>Led comprehensive bug-tracking system management, effectively resolving over 50 identified issues.</li>
                            <li>Created revisions to the previously existing employee engagement procedures, leading to 40% employee satisfaction.</li>
                            <li>Efficiently coordinated and chaired team meetings and walkthroughs.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">Education</h2>
            <div class="max-w-4xl mx-auto">
                <div class="relative">
                    <!-- Timeline Item 1 -->
                    <div class="timeline-item mb-8 pl-8 relative" data-aos="fade-right">
                        <div class="absolute left-0 top-0 w-10 h-10 rounded-full bg-deepblue-600 flex items-center justify-center text-white">
                            <i data-feather="book"></i>
                        </div>
                        <div class="bg-gray-50 p-6 rounded-lg shadow-sm">
                            <h3 class="text-xl font-bold text-deepblue-700 mb-1">Master of Business Administration</h3>
                            <p class="text-gray-700 font-medium mb-2">Emporia State University | Aug 2022 - Aug 2024</p>
                        </div>
                    </div>

                    <!-- Timeline Item 2 -->
                    <div class="timeline-item mb-8 pl-8 relative" data-aos="fade-right">
                        <div class="absolute left-0 top-0 w-10 h-10 rounded-full bg-deepblue-600 flex items-center justify-center text-white">
                            <i data-feather="book"></i>
                        </div>
                        <div class="bg-gray-50 p-6 rounded-lg shadow-sm">
                            <h3 class="text-xl font-bold text-deepblue-700 mb-1">Master of Science in Information Technology</h3>
                            <p class="text-gray-700 font-medium mb-2">Emporia State University | Aug 2021 - Dec 2023</p>
                        </div>
                    </div>

                    <!-- Timeline Item 3 -->
                    <div class="timeline-item mb-8 pl-8 relative" data-aos="fade-right">
                        <div class="absolute left-0 top-0 w-10 h-10 rounded-full bg-deepblue-600 flex items-center justify-center text-white">
                            <i data-feather="book"></i>
                        </div>
                        <div class="bg-gray-50 p-6 rounded-lg shadow-sm">
                            <h3 class="text-xl font-bold text-deepblue-700 mb-1">Bachelor of Engineering in Mechanical Engineering</h3>
                            <p class="text-gray-700 font-medium mb-2">University of Benin | Jan 2008 - Nov 2012</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">Skills & Expertise</h2>
            <div class="max-w-6xl mx-auto">
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <!-- Skill Category 1 -->
                    <div class="skill-card bg-white p-6 rounded-lg shadow-md transition duration-300" data-aos="flip-up">
                        <div class="flex items-center mb-3">
                            <div class="w-10 h-10 rounded-full bg-deepblue-100 flex items-center justify-center mr-3">
                                <i data-feather="cpu" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="font-bold text-deepblue-700">Technical Skills</h3>
                        </div>
                        <ul class="space-y-2 text-gray-700">
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Programming (Python, Java)
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Database Management
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Big Data Tools
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Testing Frameworks
                            </li>
                        </ul>
                    </div>

                    <!-- Skill Category 2 -->
                    <div class="skill-card bg-white p-6 rounded-lg shadow-md transition duration-300" data-aos="flip-up">
                        <div class="flex items-center mb-3">
                            <div class="w-10 h-10 rounded-full bg-deepblue-100 flex items-center justify-center mr-3">
                                <i data-feather="users" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="font-bold text-deepblue-700">Management</h3>
                        </div>
                        <ul class="space-y-2 text-gray-700">
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Strategic Planning
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Team Leadership
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Project Management
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Operations Management
                            </li>
                        </ul>
                    </div>

                    <!-- Skill Category 3 -->
                    <div class="skill-card bg-white p-6 rounded-lg shadow-md transition duration-300" data-aos="flip-up">
                        <div class="flex items-center mb-3">
                            <div class="w-10 h-10 rounded-full bg-deepblue-100 flex items-center justify-center mr-3">
                                <i data-feather="book-open" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="font-bold text-deepblue-700">Teaching & Research</h3>
                        </div>
                        <ul class="space-y-2 text-gray-700">
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Pedagogy
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Curriculum Development
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Academic Research
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Literature Review
                            </li>
                        </ul>
                    </div>

                    <!-- Skill Category 4 -->
                    <div class="skill-card bg-white p-6 rounded-lg shadow-md transition duration-300" data-aos="flip-up">
                        <div class="flex items-center mb-3">
                            <div class="w-10 h-10 rounded-full bg-deepblue-100 flex items-center justify-center mr-3">
                                <i data-feather="tool" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="font-bold text-deepblue-700">Engineering</h3>
                        </div>
                        <ul class="space-y-2 text-gray-700">
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                AutoCAD
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                SolidWorks
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                3D Printing
                            </li>
                            <li class="flex items-center">
                                <i data-feather="check" class="text-green-500 mr-2 w-4"></i>
                                Mechanical Design
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">Projects & Publications</h2>
            <div class="max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- Project 1 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md" data-aos="zoom-in">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 rounded-full bg-deepblue-100 flex items-center justify-center mr-4">
                                <i data-feather="cloud" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="text-xl font-bold text-deepblue-700">Cloud Database Project</h3>
                        </div>
                        <p class="text-gray-700 mb-4">Built an AWS (RDS) database and extracted systems using big data tools such as PIG Latin, Hive, and MySQL.</p>
                        <span class="inline-block bg-deepblue-100 text-deepblue-700 px-3 py-1 rounded-full text-sm">Jul 2023 - Mar 2024</span>
                    </div>

                    <!-- Project 2 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md" data-aos="zoom-in">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 rounded-full bg-deepblue-100 flex items-center justify-center mr-4">
                                <i data-feather="users" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="text-xl font-bold text-deepblue-700">edX Students Tech Mentorship</h3>
                        </div>
                        <p class="text-gray-700 mb-4">Mentored for the May and August boot camp edX program for graduates, assisting with project management.</p>
                        <span class="inline-block bg-deepblue-100 text-deepblue-700 px-3 py-1 rounded-full text-sm">Jul 2023 - Aug 2023</span>
                    </div>

                    <!-- Project 3 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md" data-aos="zoom-in">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 rounded-full bg-deepblue-100 flex items-center justify-center mr-4">
                                <i data-feather="printer" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="text-xl font-bold text-deepblue-700">APWEN Town And Gown 3D Printing Training</h3>
                        </div>
                        <p class="text-gray-700 mb-4">Facilitated the 3D printing training for young students and graduates organized by APWEN.</p>
                        <span class="inline-block bg-deepblue-100 text-deepblue-700 px-3 py-1 rounded-full text-sm">Nov 2020 - Dec 2020</span>
                    </div>

                    <!-- Project 4 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md" data-aos="zoom-in">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 rounded-full bg-deepblue-100 flex items-center justify-center mr-4">
                                <i data-feather="book" class="text-deepblue-600"></i>
                            </div>
                            <h3 class="text-xl font-bold text-deepblue-700">3D Printing in Nigeria</h3>
                        </div>
                        <p class="text-gray-700 mb-4">Publication about the state and future of 3D printing technology in Nigeria.</p>
                        <span class="inline-block bg-deepblue-100 text-deepblue-700 px-3 py-1 rounded-full text-sm">Aug 2019</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Certifications Section -->
    <section id="certifications" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">Certifications</h2>
            <div class="max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-6">
                    <!-- Certification 1 -->
                    <div class="bg-white p-6 rounded-lg shadow-md flex items-start" data-aos="fade-right">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="award" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">CC Certified in Cybersecurity</h3>
                            <p class="text-gray-600 mb-2">ISC2 | Nov 2024</p>
                        </div>
                    </div>

                    <!-- Certification 2 -->
                    <div class="bg-white p-6 rounded-lg shadow-md flex items-start" data-aos="fade-left">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="award" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">AWS Academy Graduate</h3>
                            <p class="text-gray-600 mb-2">AWS Academy cloud foundations | Jan 2022</p>
                        </div>
                    </div>

                    <!-- Certification 3 -->
                    <div class="bg-white p-6 rounded-lg shadow-md flex items-start" data-aos="fade-right">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="award" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">Fundamentals of Waterfall Project Management</h3>
                            <p class="text-gray-600 mb-2">Project Management Professional, PMP | Jan 2022</p>
                        </div>
                    </div>

                    <!-- Certification 4 -->
                    <div class="bg-white p-6 rounded-lg shadow-md flex items-start" data-aos="fade-left">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="award" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">ASTQA Certification</h3>
                            <p class="text-gray-600 mb-2">International Software Testing Qualifications Board | Jan 2023</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Awards Section -->
    <section id="awards" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-deepblue-700 mb-12" data-aos="fade-up">Awards & Honors</h2>
            <div class="max-w-4xl mx-auto">
                <div class="space-y-6">
                    <!-- Award 1 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm flex items-start" data-aos="fade-up">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="star" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">Stephen J. Butcher Outstanding Graduate Award</h3>
                            <p class="text-gray-600 mb-2">School of Business and Technology - Emporia State University | Apr 2024</p>
                        </div>
                    </div>

                    <!-- Award 2 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm flex items-start" data-aos="fade-up">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="star" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">Departmental Student Award</h3>
                            <p class="text-gray-600 mb-2">School of Business and Technology - Emporia State University | Oct 2023 & Mar 2024</p>
                        </div>
                    </div>

                    <!-- Award 3 -->
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm flex items-start" data-aos="fade-up">
                        <div class="bg-deepblue-100 p-3 rounded-lg mr-4">
                            <i data-feather="star" class="text-deepblue-600 w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-deepblue-700 mb-1">Merit Award Winner Science Talent Search</h3>
                            <p class="text-gray-600 mb-2">Science Teachers Association of Nigeria | May 2006</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-deepblue-700 text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12" data-aos="fade-up">Get In Touch</h2>
            <div class="max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-12">
                    <div data-aos="fade-right">
                        <h3 class="text-xl font-bold mb-4">Contact Information</h3>
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <i data-feather="map-pin" class="mr-3 mt-1"></i>
                                <div>
                                    <p class="font-medium">Location</p>
                                    <p class="text-deepblue-200">Garden City, KS 67846</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <i data-feather="mail" class="mr-3 mt-1"></i>
                                <div>
                                    <p class="font-medium">Email</p>
                                    <p class="text-deepblue-200">godwin.izibili@gmail.com</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <i data-feather="phone" class="mr-3 mt-1"></i>
                                <div>
                                    <p class="font-medium">Phone</p>
                                    <p class="text-deepblue-200">(620) 757-8528</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <i data-feather="linkedin" class="mr-3 mt-1"></i>
                                <div>
                                    <p class="font-medium">LinkedIn</p>
                                    <a href="https://www.linkedin.com/in/gizibili" class="text-deepblue-200 hover:underline">linkedin.com/in/gizibili</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div data-aos="fade-left">
                        <h3 class="text-xl font-bold mb-4">Send Me a Message</h3>
                        <form class="space-y-4">
                            <div>
                                <label for="name" class="block mb-1">Name</label>
                                <input type="text" id="name" class="w-full px-4 py-2 rounded bg-deepblue-800 border border-deepblue-600 focus:outline-none focus:ring-2 focus:ring-deepblue-400">
                            </div>
                            <div>
                                <label for="email" class="block mb-1">Email</label>
                                <input type="email" id="email" class="w-full px-4 py-2 rounded bg-deepblue-800 border border-deepblue-600 focus:outline-none focus:ring-2 focus:ring-deepblue-400">
                            </div>
                            <div>
                                <label for="message" class="block mb-1">Message</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-2 rounded bg-deepblue-800 border border-deepblue-600 focus:outline-none focus:ring-2 focus:ring-deepblue-400"></textarea>
                            </div>
                            <button type="submit" class="px-6 py-3 bg-white text-deepblue-700 rounded-full font-medium hover:bg-gray-100 transition duration-300">
                                Send Message
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-deepblue-900 text-white py-8">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <p>&copy; 2024 Godwin Izibili. All rights reserved.</p>
                </div>
                <div class="flex space-x-6">
                    <a href="https://www.linkedin.com/in/gizibili" class="hover:text-deepblue-300 transition">
                        <i data-feather="linkedin"></i>
                    </a>
                    <a href="mailto:godwin.izibili@gmail.com" class="hover:text-deepblue-300 transition">
                        <i data-feather="mail"></i>
                    </a>
                    <a href="tel:6207578528" class="hover:text-deepblue-300 transition">
                        <i data-feather="phone"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script>
        // Initialize AOS
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });

        // Initialize Vanta.js
        VANTA.GLOBE({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x3b82f6,
            backgroundColor: 0x0,
            size: 1.00
        });

        // Mobile menu toggle
        document.getElementById('menu-toggle').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
            feather.replace();
        });

        // Replace all feather icons
        feather.replace();
    </script>
</body>
</html>
