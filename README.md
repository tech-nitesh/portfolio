<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nitesh Kumar - Freelance Graphic Designer & Video Editor</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .bg-gradient-purple {
            background: linear-gradient(135deg, #8B5CF6, #6D28D9);
        }
        .accent-color {
            color: #8B5CF6;
        }
        .bg-accent {
            background-color: #8B5CF6;
        }
        .bg-accent-light {
            background-color: #F5F3FF;
        }
        .border-accent {
            border-color: #8B5CF6;
        }
        .ring-accent:focus {
            --tw-ring-color: #8B5CF6;
        }
        .portfolio-item {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .portfolio-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        [x-cloak] { display: none !important; }
    </style>
</head>
<body class="bg-white text-gray-800 antialiased">

    <!-- Sticky Hire Me Button -->
    <a href="#contact" class="fixed bottom-5 right-5 bg-gradient-purple text-white py-3 px-6 rounded-full shadow-lg z-50 hover:scale-105 transform transition-transform duration-300 ease-in-out font-semibold">
        Hire Me
    </a>

    <!-- Header -->
    <header class="bg-white/80 backdrop-blur-md sticky top-0 z-40 border-b border-gray-200">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-900">
                Nitesh<span class="accent-color">.</span>
            </a>
            <nav class="hidden md:flex space-x-8 items-center">
                <a href="#services" class="text-gray-600 hover:accent-color transition-colors">Services</a>
                <a href="#portfolio" class="text-gray-600 hover:accent-color transition-colors">Portfolio</a>
                <a href="#about" class="text-gray-600 hover:accent-color transition-colors">About</a>
                <a href="#contact" class="text-gray-600 hover:accent-color transition-colors">Contact</a>
            </nav>
            <a href="#contact" class="hidden md:inline-block bg-accent text-white font-medium py-2 px-4 rounded-lg hover:opacity-90 transition-opacity">
                Let's Work Together
            </a>
            <button id="mobile-menu-button" class="md:hidden">
                <i data-lucide="menu" class="w-6 h-6"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4 space-y-2">
            <a href="#services" class="block text-gray-600 hover:accent-color transition-colors">Services</a>
            <a href="#portfolio" class="block text-gray-600 hover:accent-color transition-colors">Portfolio</a>
            <a href="#about" class="block text-gray-600 hover:accent-color transition-colors">About</a>
            <a href="#contact" class="block text-gray-600 hover:accent-color transition-colors">Contact</a>
            <a href="#contact" class="block bg-accent text-white font-medium mt-2 py-2 px-4 rounded-lg hover:opacity-90 transition-opacity text-center">
                Let's Work Together
            </a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="py-20 md:py-32">
            <div class="container mx-auto px-6 text-center">
                <div class="flex justify-center mb-8">
                    <img src="https://media.licdn.com/dms/image/v2/D4E03AQGEL-kZ1LCFkQ/profile-displayphoto-shrink_200_200/B4EZRWYrVIGgAY-/0/1736616119016?e=1756339200&v=beta&t=VN9cKu45hYjRn5xizbULyyj4IVl2fJxiw-c829tW1Yc" alt="Nitesh Kumar Profile Photo" class="w-32 h-32 md:w-40 md:h-40 rounded-full object-cover border-4 border-white shadow-lg" onerror="this.onerror=null;this.src='https://placehold.co/160x160/F5F3FF/8B5CF6?text=NK';">
                </div>
                <h1 class="text-4xl md:text-6xl font-extrabold text-gray-900 leading-tight mb-4">
                    Designs that <span class="accent-color">Click</span>. Edits that <span class="accent-color">Stick</span>.
                </h1>
                <p class="text-lg md:text-xl text-gray-600 max-w-3xl mx-auto mb-8">
                    Hi, I’m Nitesh — I create logos, posters, reels, and AI visuals that grab attention.
                </p>
                <div class="flex justify-center items-center space-x-4">
                    <a href="#contact" class="bg-gradient-purple text-white font-bold py-3 px-8 rounded-full hover:scale-105 transform transition-transform duration-300 ease-in-out">
                        Let’s Work Together
                    </a>
                    <a href="https://drive.google.com/file/d/1JrRNU6RKN3Kwl3bsciR_Z4XMuFJMB5rA/view?usp=drive_link" target="_blank" rel="noopener noreferrer" id="download-resume" class="bg-gray-200 text-gray-700 font-bold py-3 px-8 rounded-full hover:bg-gray-300 transition-colors">
                        Download Resume
                    </a>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-20 bg-accent-light">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">My Services</h2>
                    <p class="text-lg text-gray-600 mt-2">What I can do for you.</p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Service Card 1 -->
                    <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 text-center">
                        <div class="inline-block bg-accent-light p-4 rounded-full mb-4">
                            <i data-lucide="gem" class="accent-color w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Logo Design</h3>
                        <p class="text-gray-500">Crafting unique and memorable logos that define your brand identity.</p>
                    </div>
                    <!-- Service Card 2 -->
                    <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 text-center">
                        <div class="inline-block bg-accent-light p-4 rounded-full mb-4">
                            <i data-lucide="image" class="accent-color w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Poster & Banner Creation</h3>
                        <p class="text-gray-500">Designing eye-catching posters and banners for events and promotions.</p>
                    </div>
                    <!-- Service Card 3 -->
                    <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 text-center">
                        <div class="inline-block bg-accent-light p-4 rounded-full mb-4">
                            <i data-lucide="film" class="accent-color w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Reels/Video Editing</h3>
                        <p class="text-gray-500">Editing engaging short-form videos that capture and hold attention.</p>
                    </div>
                    <!-- Service Card 4 -->
                    <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 text-center">
                        <div class="inline-block bg-accent-light p-4 rounded-full mb-4">
                            <i data-lucide="layout-grid" class="accent-color w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Social Media Post Design</h3>
                        <p class="text-gray-500">Creating stunning visuals for your social media channels to boost engagement.</p>
                    </div>
                    <!-- Service Card 5 -->
                    <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 text-center">
                        <div class="inline-block bg-accent-light p-4 rounded-full mb-4">
                            <i data-lucide="sparkles" class="accent-color w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">AI Image Generation</h3>
                        <p class="text-gray-500">Leveraging AI to produce unique and imaginative visuals for any concept.</p>
                    </div>
                    <!-- Service Card 6 -->
                    <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 text-center">
                        <div class="inline-block bg-accent-light p-4 rounded-full mb-4">
                            <i data-lucide="youtube" class="accent-color w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">YouTube Thumbnail Design</h3>
                        <p class="text-gray-500">Designing click-worthy thumbnails that increase your video views.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio" class="py-20" x-data="{ filter: 'all' }">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">My Portfolio</h2>
                    <p class="text-lg text-gray-600 mt-2">A selection of my recent work.</p>
                </div>
                <!-- Filter Buttons -->
                <div class="flex justify-center flex-wrap gap-2 md:gap-4 mb-12">
                    <button @click="filter = 'all'" :class="{ 'bg-accent text-white': filter === 'all', 'bg-gray-200 text-gray-700': filter !== 'all' }" class="px-6 py-2 rounded-full font-medium transition-colors">All</button>
                    <button @click="filter = 'logos'" :class="{ 'bg-accent text-white': filter === 'logos', 'bg-gray-200 text-gray-700': filter !== 'logos' }" class="px-6 py-2 rounded-full font-medium transition-colors">Logos</button>
                    <button @click="filter = 'videos'" :class="{ 'bg-accent text-white': filter === 'videos', 'bg-gray-200 text-gray-700': filter !== 'videos' }" class="px-6 py-2 rounded-full font-medium transition-colors">Videos</button>
                    <button @click="filter = 'ai-art'" :class="{ 'bg-accent text-white': filter === 'ai-art', 'bg-gray-200 text-gray-700': filter !== 'ai-art' }" class="px-6 py-2 rounded-full font-medium transition-colors">AI Art</button>
                    <button @click="filter = 'posters'" :class="{ 'bg-accent text-white': filter === 'posters', 'bg-gray-200 text-gray-700': filter !== 'posters' }" class="px-6 py-2 rounded-full font-medium transition-colors">Posters</button>
                </div>

                <!-- Portfolio Grid -->
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Item 1: Logo -->
                    <div class="portfolio-item rounded-lg overflow-hidden" x-show="filter === 'all' || filter === 'logos'" x-transition>
                        <img src="https://placehold.co/600x400/8B5CF6/FFFFFF?text=Zenith+Fitness+Logo" alt="Zenith Fitness Logo" class="w-full h-auto object-cover">
                    </div>
                    <!-- Item 2: Video -->
                    <div class="portfolio-item rounded-lg overflow-hidden" x-show="filter === 'all' || filter === 'videos'" x-transition>
                        <img src="https://placehold.co/600x400/6D28D9/FFFFFF?text=Travel+Reel:+Bali" alt="Travel Reel Thumbnail" class="w-full h-auto object-cover">
                    </div>
                    <!-- Item 3: AI Art -->
                    <div class="portfolio-item rounded-lg overflow-hidden" x-show="filter === 'all' || filter === 'ai-art'" x-transition>
                        <img src="https://placehold.co/600x400/A78BFA/FFFFFF?text=AI+Art:+Cyberpunk+City" alt="AI Generated Cyberpunk City" class="w-full h-auto object-cover">
                    </div>
                    <!-- Item 4: Poster -->
                    <div class="portfolio-item rounded-lg overflow-hidden" x-show="filter === 'all' || filter === 'posters'" x-transition>
                        <img src="https://placehold.co/600x400/8B5CF6/FFFFFF?text=Summer+Music+Fest+Poster" alt="Summer Music Festival Poster" class="w-full h-auto object-cover">
                    </div>
                     <!-- Item 5: Video -->
                    <div class="portfolio-item rounded-lg overflow-hidden" x-show="filter === 'all' || filter === 'videos'" x-transition>
                        <img src="https://placehold.co/600x400/6D28D9/FFFFFF?text=Nova+Smartwatch+Ad" alt="Nova Smartwatch Ad Thumbnail" class="w-full h-auto object-cover">
                    </div>
                    <!-- Item 6: Logo -->
                    <div class="portfolio-item rounded-lg overflow-hidden" x-show="filter === 'all' || filter === 'logos'" x-transition>
                        <img src="https://placehold.co/600x400/A78BFA/FFFFFF?text=Bloom+Cafe+Logo" alt="Bloom Cafe Logo" class="w-full h-auto object-cover">
                    </div>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-20 bg-accent-light">
            <div class="container mx-auto px-6">
                <div class="flex flex-col md:flex-row items-center gap-12">
                    <div class="md:w-1/3 flex-shrink-0">
                        <img src="https://media.licdn.com/dms/image/v2/D4E03AQGEL-kZ1LCFkQ/profile-displayphoto-shrink_200_200/B4EZRWYrVIGgAY-/0/1736616119016?e=1756339200&v=beta&t=VN9cKu45hYjRn5xizbULyyj4IVl2fJxiw-c829tW1Yc" alt="About Nitesh Kumar" class="rounded-xl shadow-lg w-full max-w-sm mx-auto" onerror="this.onerror=null;this.src='https://placehold.co/400x400/F5F3FF/8B5CF6?text=NK';">
                    </div>
                    <div class="md:w-2/3">
                        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">About Me</h2>
                        <p class="text-lg text-gray-600 mb-4">
                            I’m a B.Tech CSE student and freelance designer with 2+ years of experience. I’ve worked with creators and startups, building eye-catching visuals that perform.
                        </p>
                        <p class="text-lg text-gray-600">
                            My passion lies at the intersection of technology and creativity. Whether it's a sleek logo, a dynamic video, or a mind-bending AI image, I am dedicated to delivering high-quality work that not only looks great but also achieves its purpose. I am always learning and exploring new tools to stay at the forefront of design.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Get in Touch</h2>
                    <p class="text-lg text-gray-600 mt-2">Have a project in mind? Let's collaborate.</p>
                </div>
                <div class="max-w-4xl mx-auto flex flex-col md:flex-row gap-12">
                    <!-- Contact Form -->
                    <div class="md:w-2/3 bg-gray-50 p-8 rounded-lg">
                        <form id="contact-form" action="https://script.google.com/macros/s/AKfycbxeIOMloYpMGpcDhH3Ukft3bZ8AwOZ7lg0s81w1jYVQu9HGch1RD8sDKpV2wzuf511D/exec" method="POST">
                            <div class="mb-4">
                                <label for="name" class="block text-gray-700 font-medium mb-2">Name</label>
                                <input type="text" id="name" name="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none ring-accent focus:ring-2" required>
                            </div>
                            <div class="mb-4">
                                <label for="email" class="block text-gray-700 font-medium mb-2">Email</label>
                                <input type="email" id="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none ring-accent focus:ring-2" required>
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-gray-700 font-medium mb-2">Message</label>
                                <textarea id="message" name="message" rows="5" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none ring-accent focus:ring-2" required></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-gradient-purple text-white font-bold py-3 px-6 rounded-lg hover:opacity-90 transition-opacity">
                                Send Message
                            </button>
                            <p id="form-status" class="text-center mt-4"></p>
                        </form>
                    </div>
                    <!-- Contact Info -->
                    <div class="md:w-1/3">
                        <div class="space-y-6">
                            <div class="flex items-start gap-4">
                                <div class="bg-accent-light p-3 rounded-full"><i data-lucide="mail" class="accent-color w-6 h-6"></i></div>
                                <div>
                                    <h4 class="font-semibold text-lg">Email</h4>
                                    <a href="mailto:editingbynitesh@gmail.com" class="text-gray-600 hover:accent-color">editingbynitesh@gmail.com</a>
                                </div>
                            </div>
                             <div class="flex items-start gap-4">
                                <div class="bg-accent-light p-3 rounded-full"><i data-lucide="phone" class="accent-color w-6 h-6"></i></div>
                                <div>
                                    <h4 class="font-semibold text-lg">Phone</h4>
                                    <a href="tel:+919142476621" class="text-gray-600 hover:accent-color">+91 91424 76621</a>
                                </div>
                            </div>
                            <div class="flex items-start gap-4">
                                <div class="bg-accent-light p-3 rounded-full"><i data-lucide="map-pin" class="accent-color w-6 h-6"></i></div>
                                <div>
                                    <h4 class="font-semibold text-lg">Location</h4>
                                    <p class="text-gray-600">India (Available for remote work)</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2024 Nitesh Kumar. All Rights Reserved.</p>
            <p class="text-sm text-gray-400 mt-2">Designed to make an impact.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js" defer></script>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
        
        // Contact Form Submission with Fetch API for Google Apps Script
        const contactForm = document.getElementById('contact-form');
        const formStatus = document.getElementById('form-status');

        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            const form = e.target;
            const data = new FormData(form);
            
            formStatus.textContent = 'Sending...';
            formStatus.classList.remove('text-red-500', 'text-green-600');
            formStatus.classList.add('text-gray-600');

            fetch(form.action, {
                method: form.method,
                body: data,
            }).then(response => {
                formStatus.textContent = "Thank you! Your message has been sent.";
                formStatus.classList.remove('text-red-500');
                formStatus.classList.add('text-green-600');
                form.reset();
            }).catch(error => {
                formStatus.textContent = "Oops! There was a problem submitting your form.";
                formStatus.classList.remove('text-green-600');
                formStatus.classList.add('text-red-500');
            });
        });
    </script>
</body>
</html>
