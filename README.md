<!DOCTYPE html>
<html lang="en">
file:///Users/xinchen/Downloads/Chen-Xin---Musician-Portfolio.html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chen Xin | Cellist, Composer & Music Producer</title>
<script src="https://cdn.tailwindcss.com?version=3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#3b82f6',secondary:'#8b5cf6'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
html {
scroll-behavior: smooth;
}
body {
font-family: 'Poppins', sans-serif;
}
h1, h2, h3, h4, h5, h6 {
font-family: 'Playfair Display', serif;
}
.hero-section {
background-image: linear-gradient(to right, rgba(255, 255, 255, 0.9) 40%, rgba(255, 255, 255, 0.7) 60%, rgba(255, 255, 255, 0.4) 80%, rgba(255, 255, 255, 0) 100%), url('https://static.readdy.ai/image/1bdd8ddb370fd7239bcf6e6f6cee28c0/b9a820a5dd117928dd83642df29009cd.png');
background-size: cover;
background-position: center right;
}
.skill-card {
transition: all 0.3s ease;
}
.skill-card:hover {
transform: translateY(-5px);
}
.nav-link {
position: relative;
}
.nav-link::after {
content: '';
position: absolute;
width: 0;
height: 2px;
bottom: -2px;
left: 0;
background-color: #3b82f6;
transition: width 0.3s ease;
}
.nav-link:hover::after {
width: 100%;
}
.active::after {
width: 100%;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
-webkit-appearance: none;
margin: 0;
}
.project-card {
transition: transform 0.3s ease;
}
.project-card:hover {
transform: scale(1.02);
}
.custom-checkbox {
display: none;
}
.custom-checkbox-label {
position: relative;
padding-left: 30px;
cursor: pointer;
}
.custom-checkbox-label::before {
content: '';
position: absolute;
left: 0;
top: 0;
width: 20px;
height: 20px;
border: 2px solid #3b82f6;
border-radius: 4px;
background-color: white;
}
.custom-checkbox:checked + .custom-checkbox-label::before {
background-color: #3b82f6;
}
.custom-checkbox:checked + .custom-checkbox-label::after {
content: '✓';
position: absolute;
left: 5px;
top: -1px;
color: white;
font-size: 14px;
}
</style>
</head>
<body class="bg-white">
<!-- Navigation -->
<nav class="fixed top-0 left-0 w-full bg-white bg-opacity-95 shadow-sm z-50">
<div class="container mx-auto px-6 py-4 flex justify-between items-center">
<a href="#" class="text-2xl font-['Pacifico'] text-gray-800">Chen Xin</a>
<div class="hidden md:flex space-x-8">
<a href="#about" class="nav-link text-gray-700 hover:text-primary transition-colors">About</a>
<a href="#skills" class="nav-link text-gray-700 hover:text-primary transition-colors">Skills</a>
<a href="#projects" class="nav-link text-gray-700 hover:text-primary transition-colors">Projects</a>
<a href="#music" class="nav-link text-gray-700 hover:text-primary transition-colors">Music</a>
<a href="#contact" class="nav-link text-gray-700 hover:text-primary transition-colors">Contact</a>
</div>
<div class="md:hidden flex items-center">
<button id="mobile-menu-button" class="w-10 h-10 flex items-center justify-center text-gray-700">
<i class="ri-menu-line ri-2x"></i>
</button>
</div>
</div>
<!-- Mobile Menu -->
<div id="mobile-menu" class="hidden md:hidden bg-white w-full">
<div class="container mx-auto px-6 py-4 flex flex-col space-y-4">
<a href="#about" class="text-gray-700 hover:text-primary transition-colors">About</a>
<a href="#skills" class="text-gray-700 hover:text-primary transition-colors">Skills</a>
<a href="#projects" class="text-gray-700 hover:text-primary transition-colors">Projects</a>
<a href="#music" class="text-gray-700 hover:text-primary transition-colors">Music</a>
<a href="#contact" class="text-gray-700 hover:text-primary transition-colors">Contact</a>
</div>
</div>
</nav>
<!-- Hero Section -->
<section class="hero-section min-h-screen flex items-center pt-16">
<div class="container mx-auto px-6 w-full">
<div class="max-w-2xl">
<h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 mb-4">Xin Chen</h1>
<p class="text-lg md:text-xl text-gray-700 mb-8">Cellist, Composer & Music Producer blending classical traditions with contemporary sounds</p>
<a href="#projects" class="px-8 py-3 bg-primary text-white font-medium !rounded-button hover:bg-blue-600 transition-colors whitespace-nowrap">Explore My Work</a>
</div>
</div>
</section>
<!-- About Section -->
<section id="about" class="py-20 bg-gray-50">
<div class="container mx-auto px-6">
<h2 class="text-3xl md:text-4xl font-bold text-center mb-16">About Me</h2>
<div class="flex flex-col md:flex-row items-center gap-12">
<div class="md:w-1/2">
<img src="https://static.readdy.ai/image/1bdd8ddb370fd7239bcf6e6f6cee28c0/8a8dac54e415eb86b6fb38e4d2978bd8.png" alt="Chen Xin" class="rounded-lg shadow-lg w-full max-w-md mx-auto object-cover object-top">
</div>
<div class="md:w-1/2">
<p class="text-gray-700 mb-6 leading-relaxed">Chen Xin is a classically trained cellist and music producer with a passion for blending tradition and innovation. He began his musical journey at the age of six on Gulangyu Island, China—known as the "Island of Music"—where he developed a deep sensitivity to sound and an intuitive connection to music.
In 2016, Chen moved to the United States and quickly distinguished himself. He became the principal cellist of his high school orchestra and won first place for two consecutive years in the MTAC Whittier Branch VOCE competition in Los Angeles. While excelling in classical performance, Chen was also drawn to composition and improvisation. By the age of ten, he was creating original melodies on the cello—an act that often challenged traditional expectations and fueled his desire to forge his own musical path.
Choosing creativity over convention, Chen enrolled at Berklee College of Music to explore contemporary styles. There, he expanded his artistry by playing jazz, blues, and rock on the cello, embracing improvisation as a cornerstone of his performances. He also refined his skills as a music producer and arranger, building upon his self-taught foundation in guitar and piano. At Berklee, he mastered digital audio workstations (DAWs) and developed a love for arranging large brass ensembles, drawing from a wide range of musical influences.
Despite financial hardships, Chen persevered. Balancing full-time study with part-time work as a restaurant server, he maintained a 3.8 GPA and was awarded Berklee’s $30,000 Thrive Scholarship. His relentless dedication reflects his belief that music is not just a career, but a lifelong adventure.
Today, Chen continues to push forward, blending diverse sounds and embracing every challenge as part of the beautiful journey that music has shaped for him.
</p>
<p class="text-gray-700 mb-6 leading-relaxed">
</p>
<p class="text-gray-700 mb-6 leading-relaxed">
</p>
<div class="flex gap-4">
<a href="#contact" class="px-6 py-2 bg-primary text-white font-medium !rounded-button hover:bg-blue-600 transition-colors whitespace-nowrap">Get in Touch</a>
<a href="#projects" class="px-6 py-2 border border-gray-300 text-gray-700 font-medium !rounded-button hover:bg-gray-100 transition-colors whitespace-nowrap">View Projects</a>
</div>
</div>
</div>
</div>
</section>
<!-- Skills Section -->
<section id="skills" class="py-20">
<div class="container mx-auto px-6">
<h2 class="text-3xl md:text-4xl font-bold text-center mb-16">My Skills</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Skill 1 -->
<div class="skill-card bg-white p-8 rounded-lg shadow-md border border-gray-100">
<div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
<i class="ri-music-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Composition</h3>
<p class="text-gray-600">Creating original musical pieces across various genres, from classical chamber music to contemporary experimental works, with a focus on emotional storytelling and technical precision.</p>
</div>
<!-- Skill 2 -->
<div class="skill-card bg-white p-8 rounded-lg shadow-md border border-gray-100">
<div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
<i class="ri-file-music-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Arranging</h3>
<p class="text-gray-600">Transforming existing musical works into new contexts, adapting compositions for different ensembles, and reimagining classics with contemporary elements.</p>
</div>
<!-- Skill 3 -->
<div class="skill-card bg-white p-8 rounded-lg shadow-md border border-gray-100">
<div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
<i class="ri-sound-module-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Music Production</h3>
<p class="text-gray-600">Utilizing industry-standard digital audio workstations and recording techniques to produce polished, professional-quality music from concept to final master.</p>
</div>
<!-- Skill 4 -->
<div class="skill-card bg-white p-8 rounded-lg shadow-md border border-gray-100">
<div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
<i class="ri-advertisement-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Commercial Music</h3>
<p class="text-gray-600">Creating compelling musical scores for advertising, brand campaigns, and commercial projects that effectively communicate emotional messages and enhance visual media.</p>
</div>
<!-- Skill 5 -->
<div class="skill-card bg-white p-8 rounded-lg shadow-md border border-gray-100">
<div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
<i class="ri-cello-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">String Writing</h3>
<p class="text-gray-600">Specialized expertise in composing and arranging for string instruments, with intimate knowledge of string techniques, articulations, and ensemble dynamics.</p>
</div>
<!-- Skill 6 -->
<div class="skill-card bg-white p-8 rounded-lg shadow-md border border-gray-100">
<div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
<i class="ri-trumpet-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3">Brass Writing</h3>
<p class="text-gray-600">Crafting powerful and expressive brass arrangements with attention to range, dynamics, and tonal color, enhancing compositions with rich brass textures.</p>
</div>
</div>
</div>
</section>
<!-- Projects Section -->
<section id="projects" class="py-20 bg-gray-50">
<div class="container mx-auto px-6">
<h2 class="text-3xl md:text-4xl font-bold text-center mb-6">Featured Projects</h2>
<p class="text-center text-gray-600 mb-16 max-w-3xl mx-auto">A selection of my compositions, performances, and collaborative works showcasing my diverse musical approach and technical expertise.</p>
<!-- Filter Buttons -->
<div class="flex flex-wrap justify-center gap-4 mb-12">
<button class="filter-btn px-6 py-2 bg-primary text-white font-medium !rounded-button whitespace-nowrap" data-filter="all">All Projects</button>
<button class="filter-btn px-6 py-2 bg-white text-gray-700 border border-gray-300 font-medium !rounded-button hover:bg-gray-100 transition-colors whitespace-nowrap" data-filter="composition">Compositions</button>
<button class="filter-btn px-6 py-2 bg-white text-gray-700 border border-gray-300 font-medium !rounded-button hover:bg-gray-100 transition-colors whitespace-nowrap" data-filter="performance">Performances</button>
<button class="filter-btn px-6 py-2 bg-white text-gray-700 border border-gray-300 font-medium !rounded-button hover:bg-gray-100 transition-colors whitespace-nowrap" data-filter="collaboration">Collaborations</button>
</div>
<!-- Projects Grid -->
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Project 1 -->
<div class="project-card bg-white rounded-lg overflow-hidden shadow-md" data-category="composition">
<div class="relative pb-[56.25%]">
<iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Chen Xin - Echoes of Gulangyu" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Echoes of Gulangyu</h3>
<p class="text-gray-600 mb-4">An original composition blending traditional Chinese melodies with contemporary cello techniques, inspired by my childhood on Gulangyu Island.</p>
<div class="flex items-center text-sm text-gray-500">
<span class="bg-blue-100 text-primary px-3 py-1 rounded-full">Composition</span>
</div>
</div>
</div>
<!-- Project 2 -->
<div class="project-card bg-white rounded-lg overflow-hidden shadow-md" data-category="performance">
<div class="relative pb-[56.25%]">
<a href="https://youtu.be/WA_c21vKZuU?feature=shared" data-readdy="true">
<iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Bach Cello Suite No.1 - Chen Xin Live at Berklee" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</a>
</div>
<div class="p-6">
<a href="https://youtu.be/WA_c21vKZuU?feature=shared" data-readdy="true" class="block hover:opacity-80 transition-opacity">
<h3 class="text-xl font-semibold mb-2">Bach Cello Suite No.1</h3>
<p class="text-gray-600 mb-4">Live performance at Berklee College of Music, showcasing my interpretation of this foundational piece in the cello repertoire.</p>
<div class="flex items-center text-sm text-gray-500">
<span class="bg-blue-100 text-primary px-3 py-1 rounded-full">Performance</span>
</div>
</a>
</div>
</div>
<!-- Project 3 -->
<div class="project-card bg-white rounded-lg overflow-hidden shadow-md" data-category="collaboration">
<div class="relative pb-[56.25%]">
<a href="https://youtu.be/WA_c21vKZuU?feature=shared" data-readdy="true">
<iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Urban Strings - Collaboration with DJ Kenzo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</a>
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Urban Strings</h3>
<p class="text-gray-600 mb-4">A collaborative project with DJ Kenzo, fusing classical cello with electronic beats and urban soundscapes.</p>
<div class="flex items-center text-sm text-gray-500">
<span class="bg-blue-100 text-primary px-3 py-1 rounded-full">Collaboration</span>
</div>
</div>
</div>
<!-- Project 4 -->
<div class="project-card bg-white rounded-lg overflow-hidden shadow-md" data-category="composition">
<div class="relative pb-[56.25%]">
<iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Seasons in Transit - Original Composition" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Seasons in Transit</h3>
<p class="text-gray-600 mb-4">A four-movement original composition for cello and piano, exploring the emotional transitions between seasons as metaphors for life changes.</p>
<div class="flex items-center text-sm text-gray-500">
<span class="bg-blue-100 text-primary px-3 py-1 rounded-full">Composition</span>
</div>
</div>
</div>
<!-- Project 5 -->
<div class="project-card bg-white rounded-lg overflow-hidden shadow-md" data-category="performance">
<div class="relative pb-[56.25%]">
<iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Jazz Cello Improvisations - Live Session" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Jazz Cello Improvisations</h3>
<p class="text-gray-600 mb-4">Live session exploring the versatility of cello in jazz contexts, featuring spontaneous improvisations over standard jazz progressions.</p>
<div class="flex items-center text-sm text-gray-500">
<span class="bg-blue-100 text-primary px-3 py-1 rounded-full">Performance</span>
</div>
</div>
</div>
<!-- Project 6 -->
<div class="project-card bg-white rounded-lg overflow-hidden shadow-md" data-category="collaboration">
<div class="relative pb-[56.25%]">
<iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Soundscapes - Film Score Collaboration" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-2">Soundscapes</h3>
<p class="text-gray-600 mb-4">Original score for an independent short film, created in collaboration with filmmaker Emma Rodriguez, exploring themes of memory and identity.</p>
<div class="flex items-center text-sm text-gray-500">
<span class="bg-blue-100 text-primary px-3 py-1 rounded-full">Collaboration</span>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Music Section -->
<section id="music" class="py-20 bg-gradient-to-b from-white to-gray-100">
<div class="container mx-auto px-6">
<h2 class="text-3xl md:text-4xl font-bold text-center mb-6">My Music</h2>
<p class="text-center text-gray-600 mb-16 max-w-3xl mx-auto">Discover my original compositions and arrangements on streaming platforms. From solo cello works to collaborative projects, my music reflects my journey and artistic vision.</p>
<div class="max-w-4xl mx-auto bg-white rounded-lg shadow-lg overflow-hidden">
<div class="flex flex-col md:flex-row">
<div class="md:w-2/5 bg-gray-900">
<img src="https://readdy.ai/api/search-image?query=Modern%20album%20cover%20art%20featuring%20a%20cello%20silhouette%20against%20an%20abstract%20blue%20and%20purple%20gradient%20background%2C%20minimalist%20design%20with%20elegant%20typography%2C%20professional%20music%20album%20artwork%2C%20high-quality%20digital%20art%20with%20clean%20lines%20and%20subtle%20textures&width=600&height=600&seq=123458&orientation=squarish" alt="Chen Xin Music" class="w-full h-full object-cover object-top">
</div>
<div class="md:w-3/5 p-8">
<div class="flex items-center mb-6">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center mr-6">
<i class="ri-qq-music-fill ri-xl text-white"></i>
</div>
<div>
<h3 class="text-2xl font-semibold">My Music</h3>
<p class="text-gray-600">Stream my complete collection</p>
</div>
</div>
<p class="text-gray-700 mb-8">
Explore my full catalog of original compositions, performances, and collaborations on QQ Music. From classical interpretations to contemporary experimental works, my music reflects my journey as an artist and my passion for musical exploration.
</p>
<div class="mb-8">
<h4 class="text-lg font-semibold mb-4">Featured Tracks</h4>
<ul class="space-y-4">
<li class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
<a href="https://c6.y.qq.com/base/fcgi-bin/u?__=NYpMG6Q4KIKv" data-readdy="true" class="flex items-center hover:bg-gray-100 transition-colors">
<div class="w-10 h-10 flex items-center justify-center mr-4 text-primary">
<i class="ri-play-circle-line ri-xl"></i>
</div>
<div>
<p class="font-medium">If I can</p>
<p class="text-sm text-gray-500">Original Composition</p>
</div>
</a>
<span class="text-sm text-gray-500">4:32</span>
</li>
<li class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
<a href="https://c6.y.qq.com/base/fcgi-bin/u?__=DcrHA0Q4KmYc" data-readdy="true" class="flex items-center hover:bg-gray-100 transition-colors">
<div class="w-10 h-10 flex items-center justify-center mr-4 text-primary">
<i class="ri-play-circle-line ri-xl"></i>
</div>
<div>
<p class="font-medium">Ending</p>
<p class="text-sm text-gray-500">Collaboration</p>
</div>
</a>
<span class="text-sm text-gray-500">3:47</span>
</li>
<li class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
<a href="https://c6.y.qq.com/base/fcgi-bin/u?__=DcrHA0Q4KmYc" data-readdy="true" class="flex items-center hover:bg-gray-100 transition-colors">
<div class="w-10 h-10 flex items-center justify-center mr-4 text-primary">
<i class="ri-play-circle-line ri-xl"></i>
</div>
<div>
<p class="font-medium">Dream</p>
<p class="text-sm text-gray-500">Original Composition</p>
</div>
</a>
<span class="text-sm text-gray-500">5:16</span>
</li>
</ul>
</div>
<a href="https://y.qq.com" target="_blank" class="inline-block px-8 py-3 bg-primary text-white font-medium !rounded-button hover:bg-blue-600 transition-colors whitespace-nowrap">Visit QQ Music Profile</a>
</div>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-20">
<div class="container mx-auto px-6">
<h2 class="text-3xl md:text-4xl font-bold text-center mb-6">Get in Touch</h2>
<p class="text-center text-gray-600 mb-16 max-w-3xl mx-auto">Whether you're interested in collaborating on a project, booking a performance, or simply want to connect, I'd love to hear from you.</p>
<div class="flex flex-col lg:flex-row gap-12 max-w-6xl mx-auto">
<div class="lg:w-1/2">
<h3 class="text-2xl font-semibold mb-6">Send Me a Message</h3>
<form class="space-y-6">
<div>
<label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
<input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Your name">
</div>
<div>
<label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
<input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Your email address">
</div>
<div>
<label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Subject</label>
<input type="text" id="subject" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="What is this regarding?">
</div>
<div>
<label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
<textarea id="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Your message"></textarea>
</div>
<div class="flex items-center">
<input type="checkbox" id="newsletter" class="custom-checkbox">
<label for="newsletter" class="custom-checkbox-label text-gray-700">Subscribe to my newsletter for updates on new releases and performances</label>
</div>
<button type="submit" class="px-8 py-3 bg-primary text-white font-medium !rounded-button hover:bg-blue-600 transition-colors whitespace-nowrap">Send Message</button>
</form>
</div>
<div class="lg:w-1/2">
<h3 class="text-2xl font-semibold mb-6">Contact Information</h3>
<div class="space-y-8">
<div class="flex items-start">
<div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0">
<i class="ri-mail-line ri-lg text-primary"></i>
</div>
<div>
<h4 class="text-lg font-medium mb-1">Email</h4>
<p class="text-gray-600 mb-1">For inquiries and bookings:</p>
<a href="mailto:xinchencc22@gmail.com" class="text-primary hover:underline">xinchencc22@gmail.com</a>
</div>
</div>
<div class="flex items-start">
<div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0">
<i class="ri-instagram-line ri-lg text-primary"></i>
</div>
<div>
<h4 class="text-lg font-medium mb-1">Instagram</h4>
<p class="text-gray-600 mb-1">Follow my musical journey:</p>
<a href="https://instagram.com/xinc_22" target="_blank" class="text-primary hover:underline">@xinc_22</a>
</div>
</div>
<div class="flex items-start">
<div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0">
<i class="ri-wechat-line ri-lg text-primary"></i>
</div>
<div>
<h4 class="text-lg font-medium mb-1">WeChat</h4>
<p class="text-gray-600 mb-1">Connect with me on WeChat:</p>
<p class="text-gray-800">ww1234wwwwwwwwwww</p>
<button id="show-qr-code" class="mt-2 px-4 py-2 text-sm bg-gray-100 text-gray-700 !rounded-button hover:bg-gray-200 transition-colors whitespace-nowrap">Show QR Code</button>
</div>
</div>
<div class="mt-8">
<h4 class="text-lg font-medium mb-4">Current Location</h4>
<p class="text-gray-600 mb-2">Boston, Massachusetts, USA</p>
<p class="text-gray-600">Available for performances and collaborations worldwide</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- QR Code Modal -->
<div id="qr-code-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
<div class="bg-white rounded-lg p-8 max-w-sm w-full">
<div class="flex justify-between items-center mb-4">
<h3 class="text-xl font-semibold">WeChat QR Code</h3>
<button id="close-modal" class="w-8 h-8 flex items-center justify-center text-gray-500 hover:text-gray-700">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<div class="flex justify-center mb-6">
<img src="https://readdy.ai/api/search-image?query=WeChat%20QR%20code%20on%20a%20clean%20white%20background%2C%20simple%20black%20and%20white%20QR%20code%20design%2C%20professional%20looking%2C%20high%20resolution%2C%20minimalist%20style&width=300&height=300&seq=123459&orientation=squarish" alt="WeChat QR Code" class="w-48 h-48 object-cover">
</div>
<p class="text-center text-gray-600">Scan with WeChat app to connect</p>
</div>
</div>
<!-- Footer -->
<footer class="bg-gray-900 text-white py-12">
<div class="container mx-auto px-6">
<div class="flex flex-col md:flex-row justify-between items-center">
<div class="mb-6 md:mb-0">
<a href="#" class="text-2xl font-['Pacifico'] text-white">Chen Xin</a>
<p class="mt-2 text-gray-400">Cellist, Composer & Music Producer</p>
</div>
<div class="flex space-x-6">
<a href="mailto:xinchencc22@gmail.com" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-primary transition-colors">
<i class="ri-mail-line ri-lg"></i>
</a>
<a href="https://instagram.com/xinc_22" target="_blank" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-primary transition-colors">
<i class="ri-instagram-line ri-lg"></i>
</a>
<a href="#" id="footer-wechat" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-primary transition-colors">
<i class="ri-wechat-line ri-lg"></i>
</a>
<a href="https://y.qq.com" target="_blank" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-primary transition-colors">
<i class="ri-qq-music-fill ri-lg"></i>
</a>
</div>
</div>
<hr class="border-gray-800 my-8">
<div class="flex flex-col md:flex-row justify-between items-center">
<p class="text-gray-400 text-sm mb-4 md:mb-0">© 2025 Chen Xin. All rights reserved.</p>
<div class="flex space-x-8">
<a href="#about" class="text-gray-400 hover:text-white transition-colors text-sm">About</a>
<a href="#skills" class="text-gray-400 hover:text-white transition-colors text-sm">Skills</a>
<a href="#projects" class="text-gray-400 hover:text-white transition-colors text-sm">Projects</a>
<a href="#music" class="text-gray-400 hover:text-white transition-colors text-sm">Music</a>
<a href="#contact" class="text-gray-400 hover:text-white transition-colors text-sm">Contact</a>
</div>
</div>
</div>
</footer>
<!-- Back to Top Button -->
<button id="back-to-top" class="fixed bottom-8 right-8 w-12 h-12 bg-primary text-white rounded-full shadow-lg flex items-center justify-center opacity-0 invisible transition-all duration-300">
<i class="ri-arrow-up-line ri-lg"></i>
</button>
<script>
document.addEventListener('DOMContentLoaded', function() {
// Mobile menu toggle
const mobileMenuButton = document.getElementById('mobile-menu-button');
const mobileMenu = document.getElementById('mobile-menu');
mobileMenuButton.addEventListener('click', function() {
mobileMenu.classList.toggle('hidden');
});
// Close mobile menu when clicking a link
const mobileLinks = mobileMenu.querySelectorAll('a');
mobileLinks.forEach(link => {
link.addEventListener('click', function() {
mobileMenu.classList.add('hidden');
});
});
});
document.addEventListener('DOMContentLoaded', function() {
// Project filtering
const filterButtons = document.querySelectorAll('.filter-btn');
const projectCards = document.querySelectorAll('.project-card');
filterButtons.forEach(button => {
button.addEventListener('click', function() {
// Remove active class from all buttons
filterButtons.forEach(btn => {
btn.classList.remove('bg-primary', 'text-white');
btn.classList.add('bg-white', 'text-gray-700', 'border', 'border-gray-300', 'hover:bg-gray-100');
});
// Add active class to clicked button
this.classList.remove('bg-white', 'text-gray-700', 'border', 'border-gray-300', 'hover:bg-gray-100');
this.classList.add('bg-primary', 'text-white');
const filter = this.getAttribute('data-filter');
projectCards.forEach(card => {
if (filter === 'all' || card.getAttribute('data-category') === filter) {
card.style.display = 'block';
} else {
card.style.display = 'none';
}
});
});
});
});
document.addEventListener('DOMContentLoaded', function() {
// Back to top button
const backToTopButton = document.getElementById('back-to-top');
window.addEventListener('scroll', function() {
if (window.pageYOffset > 300) {
backToTopButton.classList.remove('opacity-0', 'invisible');
backToTopButton.classList.add('opacity-100', 'visible');
} else {
backToTopButton.classList.remove('opacity-100', 'visible');
backToTopButton.classList.add('opacity-0', 'invisible');
}
});
backToTopButton.addEventListener('click', function() {
window.scrollTo({
top: 0,
behavior: 'smooth'
});
});
});
document.addEventListener('DOMContentLoaded', function() {
// QR Code Modal
const showQrCodeButton = document.getElementById('show-qr-code');
const footerWechatButton = document.getElementById('footer-wechat');
const qrCodeModal = document.getElementById('qr-code-modal');
const closeModalButton = document.getElementById('close-modal');
function showModal() {
qrCodeModal.classList.remove('hidden');
}
function hideModal() {
qrCodeModal.classList.add('hidden');
}
showQrCodeButton.addEventListener('click', showModal);
footerWechatButton.addEventListener('click', showModal);
closeModalButton.addEventListener('click', hideModal);
qrCodeModal.addEventListener('click', function(e) {
if (e.target === qrCodeModal) {
hideModal();
}
});
document.addEventListener('keydown', function(e) {
if (e.key === 'Escape') {
hideModal();
}
});
});
document.addEventListener('DOMContentLoaded', function() {
// Smooth scrolling for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function(e) {
e.preventDefault();
const targetId = this.getAttribute('href');
if (targetId === '#') return;
const targetElement = document.querySelector(targetId);
if (targetElement) {
const navHeight = document.querySelector('nav').offsetHeight;
const targetPosition = targetElement.getBoundingClientRect().top + window.pageYOffset - navHeight;
window.scrollTo({
top: targetPosition,
behavior: 'smooth'
});
}
});
});
});
</script>
</body>
</html>
