<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Name – Portfolio</title>
  <meta name="description" content="Personal site built with GitHub Pages." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <!-- Tailwind via CDN for quick start -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    /* Simple navbar blur on scroll */
    .scrolled { backdrop-filter: blur(8px); background-color: rgba(255,255,255,0.6); }
  </style>
</head>
<body class="font-[Inter] text-slate-800">
  <!-- NAV -->
  <header id="top" class="fixed top-0 inset-x-0 z-50">
    <nav id="nav" class="mx-auto max-w-6xl px-4 py-3 flex items-center justify-between">
      <a href="#top" class="text-xl font-extrabold tracking-tight">YourName<span class="text-sky-600">.dev</span></a>
      <div class="hidden md:flex gap-6 text-sm">
        <a href="#about" class="hover:text-sky-700">About</a>
        <a href="#projects" class="hover:text-sky-700">Projects</a>
        <a href="#contact" class="hover:text-sky-700">Contact</a>
        <a href="https://github.com/yourusername" class="hover:text-sky-700" target="_blank" rel="noopener">GitHub</a>
      </div>
    </nav>
  </header>

  <!-- HERO -->
  <section class="pt-28 md:pt-40 bg-gradient-to-b from-sky-50 to-white">
    <div class="mx-auto max-w-6xl px-4 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl md:text-6xl font-extrabold leading-tight">Hi, I'm <span class="text-sky-700">Your Name</span>.<br/> I build things for the web & AI.</h1>
        <p class="mt-5 text-slate-600 max-w-prose">Welcome to my GitHub Pages site. You'll find a quick snapshot of who I am, what I'm learning, and a few projects. Replace this text with your own intro.</p>
        <div class="mt-8 flex gap-3">
          <a href="#projects" class="px-5 py-3 rounded-2xl bg-sky-700 hover:bg-sky-800 text-white font-semibold shadow">See Projects</a>
          <a href="#contact" class="px-5 py-3 rounded-2xl border border-slate-300 hover:border-sky-700 font-semibold">Contact</a>
        </div>
      </div>
      <div class="relative">
        <div class="aspect-[4/3] rounded-3xl bg-gradient-to-tr from-sky-200 to-sky-100 shadow-inner"></div>
        <div class="absolute -bottom-6 -right-6 bg-white/70 border border-slate-200 rounded-2xl p-4 shadow">
          <p class="text-sm">🚀 Deployed with <strong>GitHub Pages</strong></p>
        </div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-20">
    <div class="mx-auto max-w-6xl px-4 grid md:grid-cols-3 gap-10">
      <div class="md:col-span-1">
        <h2 class="text-2xl font-bold">About</h2>
        <p class="text-slate-600">A quick bio.</p>
      </div>
      <div class="md:col-span-2 space-y-4 leading-relaxed">
        <p>I'm a developer / analyst / creator. Replace this section with your real background, skills, and interests. You can keep it short or expand it as your site grows.</p>
        <ul class="list-disc pl-6">
          <li>Focus areas: web, data, AI</li>
          <li>Tools: Python, JavaScript, Google Cloud</li>
          <li>Location: Your City, Country</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-20 bg-slate-50">
    <div class="mx-auto max-w-6xl px-4">
      <div class="flex items-end justify-between mb-10">
        <div>
          <h2 class="text-2xl font-bold">Projects</h2>
          <p class="text-slate-600">A few things I've shipped or am learning with.</p>
        </div>
        <a class="text-sm text-sky-700 hover:underline" href="https://github.com/yourusername?tab=repositories" target="_blank" rel="noopener">All repos →</a>
      </div>
      <div class="grid md:grid-cols-3 gap-6">
        <!-- Card 1 -->
        <article class="rounded-2xl bg-white border border-slate-200 shadow-sm overflow-hidden">
          <div class="h-32 bg-gradient-to-br from-sky-200 to-white"></div>
          <div class="p-5 space-y-2">
            <h3 class="font-semibold">Project One</h3>
            <p class="text-sm text-slate-600">Short description of what it is, why you built it, and tech used.</p>
            <div class="text-sm">
              <a class="text-sky-700 hover:underline" href="#">Live</a>
              <span class="mx-2 text-slate-400">•</span>
              <a class="text-sky-700 hover:underline" href="#">Code</a>
            </div>
          </div>
        </article>
        <!-- Card 2 -->
        <article class="rounded-2xl bg-white border border-slate-200 shadow-sm overflow-hidden">
          <div class="h-32 bg-gradient-to-br from-sky-200 to-white"></div>
          <div class="p-5 space-y-2">
            <h3 class="font-semibold">Project Two</h3>
            <p class="text-sm text-slate-600">Another brief description. Keep it simple; link out to the repo.</p>
            <div class="text-sm">
              <a class="text-sky-700 hover:underline" href="#">Live</a>
              <span class="mx-2 text-slate-400">•</span>
              <a class="text-sky-700 hover:underline" href="#">Code</a>
            </div>
          </div>
        </article>
        <!-- Card 3 -->
        <article class="rounded-2xl bg-white border border-slate-200 shadow-sm overflow-hidden">
          <div class="h-32 bg-gradient-to-br from-sky-200 to-white"></div>
          <div class="p-5 space-y-2">
            <h3 class="font-semibold">Project Three</h3>
            <p class="text-sm text-slate-600">Learning notes, small experiment, or portfolio piece.</p>
            <div class="text-sm">
              <a class="text-sky-700 hover:underline" href="#">Live</a>
              <span class="mx-2 text-slate-400">•</span>
              <a class="text-sky-700 hover:underline" href="#">Code</a>
            </div>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-20">
    <div class="mx-auto max-w-2xl px-4 text-center">
      <h2 class="text-2xl font-bold">Contact</h2>
      <p class="text-slate-600 mt-2">Have an idea or want to say hi? Drop a note:</p>
      <form class="mt-8 grid gap-3" name="contact" method="POST" data-netlify="true">
        <input type="hidden" name="form-name" value="contact" />
        <input required class="border border-slate-300 rounded-xl px-4 py-3" type="text" name="name" placeholder="Your name"/>
        <input required class="border border-slate-300 rounded-xl px-4 py-3" type="email" name="email" placeholder="Your email"/>
        <textarea required class="border border-slate-300 rounded-xl px-4 py-3" name="message" rows="4" placeholder="Your message"></textarea>
        <button class="justify-self-center px-6 py-3 rounded-2xl bg-sky-700 hover:bg-sky-800 text-white font-semibold shadow" type="submit">Send</button>
      </form>
      <p class="text-xs text-slate-500 mt-3">(This demo form posts to Netlify if you host there. On GitHub Pages, replace with your email link.)</p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-10 border-t border-slate-200">
    <div class="mx-auto max-w-6xl px-4 text-sm flex flex-col md:flex-row items-center justify-between gap-4">
      <p>© <span id="year"></span> Your Name</p>
      <div class="flex gap-4">
        <a class="hover:underline" href="mailto:you@example.com">you@example.com</a>
        <a class="hover:underline" href="https://github.com/yourusername" target="_blank" rel="noopener">GitHub</a>
        <a class="hover:underline" href="#top">Back to top ↑</a>
      </div>
    </div>
  </footer>

  <script>
    // Set current year in footer
    document.getElementById('year').textContent = new Date().getFullYear();
    // Add blur background when scrolling
    const nav = document.getElementById('nav');
    window.addEventListener('scroll', () => {
      if (window.scrollY > 8) nav.classList.add('scrolled');
      else nav.classList.remove('scrolled');
    });
  </script>
</body>
</html># Nemra
Professional site for NEMRA AI Solutions
