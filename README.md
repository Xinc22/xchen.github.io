<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chen Xin | Cellist, Composer & Music Producer</title>
  <meta name="description" content="Chen Xin is a classically trained cellist and music producer blending classical traditions with contemporary sounds. Explore his compositions, performances, and collaborations.">

  <link rel="icon" href="/favicon.ico" type="image/x-icon">

  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#3b82f6',
            secondary: '#8b5cf6'
          },
          borderRadius: {
            none: '0px',
            sm: '4px',
            DEFAULT: '8px',
            md: '12px',
            lg: '16px',
            xl: '20px',
            '2xl': '24px',
            '3xl': '32px',
            full: '9999px',
            button: '8px'
          }
        }
      },
      corePlugins: { preflight: false }
    }
  </script>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">

  <style>
    :where([class^="ri-"])::before { content: "\f3c2"; }
    html { scroll-behavior: smooth; }
    body { font-family: 'Poppins', sans-serif; transition: background-color 0.3s, color 0.3s; }
    h1, h2, h3, h4, h5, h6 { font-family: 'Playfair Display', serif; }
    .fade-in { opacity: 0; transform: translateY(20px); transition: opacity 0.6s ease-out, transform 0.6s ease-out; }
    .fade-in.visible { opacity: 1; transform: translateY(0); }
    #backToTopBtn { display: none; position: fixed; bottom: 40px; right: 40px; z-index: 100; }
  </style>
</head>
<body class="bg-white dark:bg-gray-900 dark:text-white">

<!-- Hero Section -->
<section class="min-h-screen flex flex-col justify-center items-center text-center p-10 fade-in">
  <h1 class="text-5xl font-bold text-primary mb-6">Chen Xin</h1>
  <p class="text-lg text-gray-700 dark:text-gray-300">Cellist | Composer | Music Producer</p>
  <a href="#about" class="mt-8 inline-block px-6 py-3 bg-primary text-white rounded-full text-lg hover:scale-105 hover:shadow-lg transition">Learn More</a>
</section>

<!-- About Section -->
<section id="about" class="py-20 bg-gray-50 dark:bg-gray-800 fade-in">
  <div class="max-w-4xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">About Me</h2>
    <p class="text-gray-700 dark:text-gray-300 leading-relaxed">
      Chen Xin is a classically trained cellist and music producer who blends tradition and innovation. Starting music at age six on Gulangyu Island, China, he developed a unique connection to sound. After moving to the U.S., he distinguished himself as a principal cellist and competition winner. At Berklee College of Music, he expanded into jazz, blues, and rock, embracing improvisation and modern production techniques. Chen continues pushing artistic boundaries while balancing rigorous academic and professional achievements.
    </p>
  </div>
</section>

<!-- Skills Section -->
<section id="skills" class="py-20 fade-in">
  <div class="max-w-6xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">Skills</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10">
      <div><h3 class="text-xl font-semibold mb-2">Composition</h3><p>Creating original pieces across genres.</p></div>
      <div><h3 class="text-xl font-semibold mb-2">Arranging</h3><p>Adapting works for different ensembles.</p></div>
      <div><h3 class="text-xl font-semibold mb-2">Music Production</h3><p>Producing professional-quality music.</p></div>
      <div><h3 class="text-xl font-semibold mb-2">Commercial Music</h3><p>Scoring for ads and media projects.</p></div>
      <div><h3 class="text-xl font-semibold mb-2">String Writing</h3><p>Expertise in composing for strings.</p></div>
      <div><h3 class="text-xl font-semibold mb-2">Brass Writing</h3><p>Crafting powerful brass arrangements.</p></div>
    </div>
  </div>
</section>

<!-- Projects Section -->
<section id="projects" class="py-20 bg-gray-50 dark:bg-gray-800 fade-in">
  <div class="max-w-6xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">Projects</h2>
    <p class="text-gray-600 dark:text-gray-400 mb-10">Showcasing selected works through YouTube links.</p>
    <a href="https://youtube.com" target="_blank" class="inline-block px-6 py-3 bg-primary text-white rounded-full text-lg hover:scale-105 hover:shadow-lg transition">View Projects</a>
  </div>
</section>

<!-- Music Section -->
<section id="music" class="py-20 fade-in">
  <div class="max-w-6xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">Music</h2>
    <p class="text-gray-600 dark:text-gray-400 mb-10">Listen to Chen Xin's works on QQ Music.</p>
    <a href="https://y.qq.com" target="_blank" class="inline-block px-6 py-3 bg-primary text-white rounded-full text-lg hover:scale-105 hover:shadow-lg transition">Visit QQ Music</a>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-20 bg-gray-50 dark:bg-gray-800 fade-in">
  <div class="max-w-4xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">Contact</h2>
    <p class="text-gray-600 dark:text-gray-400 mb-6">Feel free to reach out for collaborations or inquiries.</p>
    <p class="text-gray-700 dark:text-gray-300">Email: <a href="mailto:xinchencc22@gmail.com" class="text-primary hover:underline">xinchencc22@gmail.com</a></p>
    <p class="text-gray-700 dark:text-gray-300">Instagram: <a href="https://instagram.com/xinc_22" class="text-primary hover:underline">@xinc_22</a></p>
    <p class="text-gray-700 dark:text-gray-300">WeChat: ww1234wwwwwwwwwww</p>
  </div>
</section>

<!-- Back to Top Button -->
<button id="backToTopBtn" class="px-4 py-3 bg-primary text-white rounded-full hover:bg-blue-700">⬆️ Top</button>

<!-- Footer -->
<footer class="text-center py-8 text-gray-500 text-sm">
  © <span id="year"></span> Chen Xin. All rights reserved.
</footer>

<script>
// Fade in sections when scrolling
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
    }
  });
});
document.querySelectorAll('.fade-in').forEach(section => {
  observer.observe(section);
});

// Back to Top Button
const backToTopBtn = document.getElementById('backToTopBtn');
window.addEventListener('scroll', () => {
  if (window.scrollY > 400) {
    backToTopBtn.style.display = 'block';
  } else {
    backToTopBtn.style.display = 'none';
  }
});
backToTopBtn.addEventListener('click', () => {
  window.scrollTo({ top: 0, behavior: 'smooth' });
});

// Dynamic Year
document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
