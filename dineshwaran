<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Portfolio of Dineshwaran S | MSc Software Systems | AI Innovator | Multimedia Creator" />
  <title>Dineshwaran S - Portfolio</title>

  <!-- Favicon -->
  <link rel="icon" href="favicon.ico" type="image/x-icon" />

  <!-- Tailwind CSS -->
  <link rel="preconnect" href="https://cdn.tailwindcss.com">
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Three.js -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

  <style>
    html { scroll-behavior: smooth; }
    body { margin: 0; font-family: 'Inter', sans-serif; color: #f9fafb; background: #0a0a0a; }
    #bgCanvas { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; }

    .glass {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255, 255, 255, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .glass:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(99, 102, 241, 0.4);
    }

    .fade-up { opacity: 0; transform: translateY(30px); transition: all 0.8s ease-out; }
    .fade-up.show { opacity: 1; transform: translateY(0); }
  </style>
</head>
<body>

  <!-- Background -->
  <canvas id="bgCanvas"></canvas>

  <!-- Navbar -->
  <nav class="fixed top-0 left-0 w-full bg-black/40 backdrop-blur-md shadow-lg z-50">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-indigo-400">Dineshwaran S</h1>
      <div class="space-x-6 hidden md:flex">
        <a href="#about" aria-label="About Section" class="hover:text-indigo-400">About</a>
        <a href="#skills" aria-label="Skills Section" class="hover:text-indigo-400">Skills</a>
        <a href="#projects" aria-label="Projects Section" class="hover:text-indigo-400">Projects</a>
        <a href="#contact" aria-label="Contact Section" class="hover:text-indigo-400">Contact</a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-6">
    <h2 class="text-5xl md:text-6xl font-extrabold mb-6">Hi, I'm <span class="text-indigo-400">Dineshwaran</span></h2>
    <p class="text-lg md:text-2xl text-gray-300 mb-10">MSc Software Systems | AI Innovator | Multimedia Creator</p>
    <a href="#projects" class="px-8 py-3 bg-indigo-600 hover:bg-indigo-700 rounded-full shadow-lg">See My Work</a>
  </section>

  <!-- About -->
  <section id="about" class="py-20 px-6 max-w-4xl mx-auto text-center fade-up">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6">About Me</h2>
    <div class="glass p-8 rounded-2xl">
      <p class="text-lg text-gray-300">
        I’m <span class="text-indigo-300 font-semibold">Dineshwaran S</span>, pursuing <span class="text-indigo-400">MSc in Software Systems</span>.  
        My expertise blends <b>AI & Computer Vision</b> with <b>Creative Multimedia</b>.  
        From intelligent surveillance systems to visually stunning media, I build solutions that matter.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-20 fade-up">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-indigo-400 text-center mb-12">My Skills</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="glass p-6 rounded-2xl text-center">
          <h3 class="text-2xl mb-2">🎬 Video Editing</h3>
          <p class="text-gray-400">Creating engaging videos for academic, creative, and promotional purposes.</p>
        </div>
        <div class="glass p-6 rounded-2xl text-center">
          <h3 class="text-2xl mb-2">🎨 Poster Design</h3>
          <p class="text-gray-400">Designing digital posters, event banners, and impactful visual content.</p>
        </div>
        <div class="glass p-6 rounded-2xl text-center">
          <h3 class="text-2xl mb-2">🤖 AI & Software</h3>
          <p class="text-gray-400">Building AI-driven systems and modern web/software applications.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-20 px-6 fade-up">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-indigo-400 text-center mb-12">Projects</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="glass p-6 rounded-2xl">
          <h3 class="text-2xl font-semibold mb-3 text-indigo-300">🔒 SafeLens</h3>
          <p class="text-gray-400">AI system detecting violence in CCTV footage, enabling real-time public safety alerts.</p>
        </div>
        <div class="glass p-6 rounded-2xl">
          <h3 class="text-2xl font-semibold mb-3 text-indigo-300">🐟 Underwater Fish Detection</h3>
          <p class="text-gray-400">Deep learning-based marine vision project to classify and detect underwater species.</p>
        </div>
        <div class="glass p-6 rounded-2xl">
          <h3 class="text-2xl font-semibold mb-3 text-indigo-300">🩸 Red-Circle Blood Bank</h3>
          <p class="text-gray-400">A web-based platform connecting donors and patients to simplify emergency blood needs.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 text-center fade-up">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6">Contact Me</h2>
    <p class="text-lg text-gray-300 mb-6">Let’s connect and collaborate!</p>
    <div class="glass max-w-md mx-auto p-6 rounded-2xl space-y-3">
      <p>📞 <a href="tel:+919442216507" class="hover:text-indigo-400">+91 94422 16507</a></p>
      <p>📧 <a href="mailto:dineshwaran410@gmail.com" class="hover:text-indigo-400">dineshwaran410@gmail.com</a></p>
      <div class="flex justify-center gap-6 text-xl mt-4">
        <a href="https://github.com/dineshwaran-coder" target="_blank" class="hover:text-indigo-400" aria-label="GitHub Profile">GitHub</a>
        <a href="https://www.linkedin.com/in/dineshwaran-s-73b728371" target="_blank" class="hover:text-indigo-400" aria-label="LinkedIn Profile">LinkedIn</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-400 text-sm">
    © <span id="year"></span> Dineshwaran S. All rights reserved.
  </footer>

  <!-- Scripts -->
  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    // Fade Animation
    const faders = document.querySelectorAll(".fade-up");
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => { if (entry.isIntersecting) entry.target.classList.add("show"); });
    }, { threshold: 0.2 });
    faders.forEach(el => observer.observe(el));

    // Three.js Background
    const canvas = document.getElementById("bgCanvas");
    const scene = new THREE.Scene();
    const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
    const renderer = new THREE.WebGLRenderer({ canvas, antialias: true });
    renderer.setSize(window.innerWidth, window.innerHeight);
    camera.position.z = 5;

    const particles = new THREE.BufferGeometry();
    const count = 1500;
    const positions = [];
    for (let i = 0; i < count; i++) {
      positions.push((Math.random() - 0.5) * 20);
      positions.push((Math.random() - 0.5) * 20);
      positions.push((Math.random() - 0.5) * 20);
    }
    particles.setAttribute("position", new THREE.Float32BufferAttribute(positions, 3));
    const material = new THREE.PointsMaterial({ color: 0x6366f1, size: 0.05, transparent: true, opacity: 0.8 });
    const particleMesh = new THREE.Points(particles, material);
    scene.add(particleMesh);

    function animate() {
      requestAnimationFrame(animate);
      particleMesh.rotation.y += 0.0008;
      particleMesh.rotation.x += 0.0005;
      renderer.render(scene, camera);
    }
    animate();

    window.addEventListener("resize", () => {
      camera.aspect = window.innerWidth / window.innerHeight;
      camera.updateProjectionMatrix();
      renderer.setSize(window.innerWidth, window.innerHeight);
    });
  </script>
</body>
</html>
