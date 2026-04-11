<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Roberto Rodriguez // The Terminal Luminary</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&amp;family=Inter:wght@300;400;500;600;700&amp;family=JetBrains+Mono:wght@400;500&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-error": "#490006",
                        "on-background": "#f1f3fc",
                        "on-tertiary-container": "#ffffff",
                        "error-container": "#9f0519",
                        "on-surface-variant": "#a8abb3",
                        "on-primary": "#006165",
                        "surface-variant": "#20262f",
                        "tertiary-fixed": "#d896ff",
                        "on-tertiary-fixed": "#2a0043",
                        "outline": "#72757d",
                        "background": "#0a0e14",
                        "on-secondary-fixed": "#004627",
                        "on-secondary-fixed-variant": "#00653b",
                        "secondary-fixed-dim": "#00ec90",
                        "surface-container-lowest": "#000000",
                        "on-tertiary-fixed-variant": "#5c008a",
                        "tertiary-fixed-dim": "#d082ff",
                        "error": "#ff716c",
                        "primary-fixed": "#00f4fe",
                        "secondary-fixed": "#00fc9a",
                        "inverse-on-surface": "#51555c",
                        "tertiary-container": "#ad00fe",
                        "inverse-surface": "#f8f9ff",
                        "surface-container-low": "#0f141a",
                        "surface-tint": "#a1faff",
                        "surface-bright": "#262c36",
                        "on-primary-container": "#00575b",
                        "surface-container": "#151a21",
                        "primary-fixed-dim": "#00e5ee",
                        "secondary-container": "#006d40",
                        "on-primary-fixed": "#004346",
                        "on-secondary-container": "#e2ffe8",
                        "error-dim": "#d7383b",
                        "surface": "#0a0e14",
                        "primary": "#a1faff",
                        "surface-container-highest": "#20262f",
                        "surface-dim": "#0a0e14",
                        "inverse-primary": "#006a6e",
                        "on-secondary": "#005b34",
                        "tertiary": "#cd7aff",
                        "primary-dim": "#00e5ee",
                        "outline-variant": "#44484f",
                        "secondary-dim": "#00ec90",
                        "on-error-container": "#ffa8a3",
                        "on-tertiary": "#370054",
                        "primary-container": "#00f4fe",
                        "secondary": "#00fc9a",
                        "tertiary-dim": "#b121ff",
                        "surface-container-high": "#1b2028",
                        "on-primary-fixed-variant": "#006266",
                        "on-surface": "#f1f3fc"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "fontFamily": {
                        "headline": ["Space Grotesk"],
                        "body": ["Inter"],
                        "label": ["Space Grotesk"],
                        "mono": ["JetBrains Mono"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-card {
            background: rgba(32, 38, 47, 0.6);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
        .hero-gradient {
            background: linear-gradient(135deg, #a1faff 0%, #00f4fe 100%);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface font-body selection:bg-primary selection:text-on-primary">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#0a0e14] dark:bg-[#0a0e14]">
<nav class="flex justify-between items-center px-6 py-4 w-full">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-[#00F5FF]" data-icon="terminal">terminal</span>
<span class="text-xl font-bold text-[#00F5FF] uppercase tracking-widest font-['Space_Grotesk']">The Terminal Luminary</span>
</div>
<div class="hidden md:flex gap-8 items-center">
<a class="text-[#a1faff] font-bold font-['Space_Grotesk'] tracking-tight hover:text-[#00F5FF] transition-colors duration-300 cursor-pointer active:scale-95" href="#intro">Intro</a>
<a class="text-slate-400 font-['Space_Grotesk'] tracking-tight hover:text-[#00F5FF] transition-colors duration-300 cursor-pointer active:scale-95" href="#skills">Skills</a>
<a class="text-slate-400 font-['Space_Grotesk'] tracking-tight hover:text-[#00F5FF] transition-colors duration-300 cursor-pointer active:scale-95" href="#projects">Projects</a>
<a class="text-slate-400 font-['Space_Grotesk'] tracking-tight hover:text-[#00F5FF] transition-colors duration-300 cursor-pointer active:scale-95" href="#stats">Stats</a>
</div>
<span class="material-symbols-outlined text-[#00F5FF] md:hidden" data-icon="menu">menu</span>
</nav>
</header>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto space-y-32">
<!-- Hero Section -->
<section class="relative flex flex-col md:flex-row items-center gap-12 min-h-[530px]" id="intro">
<div class="w-full md:w-3/5 space-y-6">
<div class="inline-flex items-center px-3 py-1 rounded-full bg-surface-container-highest border border-outline-variant/15 gap-2">
<span class="w-2 h-2 rounded-full bg-secondary"></span>
<span class="text-xs font-mono uppercase tracking-widest text-secondary">Available for Projects</span>
</div>
<h1 class="text-6xl md:text-8xl font-headline font-bold tracking-tighter leading-tight">
                    Roberto <br/>
<span class="hero-gradient bg-clip-text text-transparent">Rodriguez</span>
</h1>
<p class="text-xl md:text-2xl text-on-surface-variant font-light max-w-2xl">
                    Aspiring Frontend Engineer / <span class="text-primary">Creative Developer</span>. 
                    Passionate about building modern, responsive web applications with a focus on UI/UX.
                </p>
<div class="flex gap-4 pt-4">
<button class="bg-primary text-on-primary px-8 py-3 rounded-md font-semibold hover:opacity-90 transition-all flex items-center gap-2">
                        View Resume <span class="material-symbols-outlined" data-icon="arrow_outward">arrow_outward</span>
</button>
<button class="border border-outline-variant text-primary px-8 py-3 rounded-md font-semibold hover:bg-primary/5 transition-all">
                        Connect
                    </button>
</div>
</div>
<div class="w-full md:w-2/5 flex justify-center md:justify-end">
<div class="relative w-64 h-64 md:w-80 md:h-80">
<div class="absolute inset-0 bg-primary/20 blur-3xl rounded-full"></div>
<div class="relative w-full h-full rounded-2xl overflow-hidden border border-outline-variant/20">
<img alt="Professional portrait" class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" data-alt="Professional cinematic headshot of a young male creative developer with soft studio lighting and dark atmospheric background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAggw5BoExI_cwSpblA3PyTKImZIPoZtlLWLKUubMHYTbFACjeB25NgooWgjPdnKGjOFHMqjImKhhf3YskoQuF-YN6NO9sQfzzUrBlOvliWWATazuCtWJLiytdFV5mNR5trScsbBn5ULJTXJao8fCUGHgBN6zyzHFZp6p-XL75TJnNvM8CuXIWPa3m3WCW3fnfVxqcc8kNP4nl_n1HPX_V3BNRY36ZQrbMFgrBdNp7Viw2TIOJO6RDaLnGK7wJRvdba9l-RYHJQn1s"/>
</div>
</div>
</div>
</section>
<!-- Skills Section -->
<section class="bg-surface-container-low rounded-3xl p-8 md:p-16" id="skills">
<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
<div class="space-y-8">
<h2 class="text-4xl font-headline font-bold">Tech Stack</h2>
<div class="flex flex-wrap gap-4">
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-secondary"></span>
<span class="font-mono text-sm">React</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-secondary"></span>
<span class="font-mono text-sm">TypeScript</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-secondary"></span>
<span class="font-mono text-sm">JavaScript</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-secondary"></span>
<span class="font-mono text-sm">HTML5</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-secondary"></span>
<span class="font-mono text-sm">SCSS/CSS</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-secondary"></span>
<span class="font-mono text-sm">Styled Components</span>
</div>
</div>
</div>
<div class="space-y-8">
<h2 class="text-4xl font-headline font-bold">Tools &amp; Flow</h2>
<div class="flex flex-wrap gap-4">
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-tertiary"></span>
<span class="font-mono text-sm">Git</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-tertiary"></span>
<span class="font-mono text-sm">GitHub</span>
</div>
<div class="px-6 py-3 bg-surface-container-highest rounded-full flex items-center gap-3 border border-outline-variant/10">
<span class="w-1 h-1 rounded-full bg-tertiary"></span>
<span class="font-mono text-sm">VS Code</span>
</div>
</div>
</div>
</div>
</section>
<!-- Projects Section (Bento Grid) -->
<section class="space-y-12" id="projects">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
<h2 class="text-5xl font-headline font-bold">Featured Projects</h2>
<p class="text-on-surface-variant font-mono">/ SELECTED WORKS 2024</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 h-auto md:h-[800px]">
<!-- Main Featured Project -->
<div class="md:col-span-8 group relative overflow-hidden rounded-3xl glass-card border border-outline-variant/10 flex flex-col">
<div class="p-8 space-y-4 z-10 flex-shrink-0">
<div class="flex items-center justify-between">
<h3 class="text-3xl font-headline font-bold text-primary">artsie</h3>
<span class="text-xs font-mono px-2 py-1 bg-secondary/20 text-secondary rounded">COMPLETED</span>
</div>
<p class="text-on-surface-variant max-w-lg">
                            Web App showcasing the Art Institute of Chicago's public API. A minimal, focused interface for discovering timeless art.
                        </p>
<div class="flex gap-2">
<span class="text-xs font-mono text-primary-dim">TypeScript</span>
<span class="text-xs font-mono text-primary-dim">REST API</span>
</div>
</div>
<div class="flex-grow relative mt-4 overflow-hidden rounded-t-[2rem] mx-4 border-t border-x border-outline-variant/20">
<img alt="Artsie preview" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="Clean minimal UI of an art gallery app featuring classical paintings in a sleek dark mode grid" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAjsGXuNItyO6IR4n5T6lmyJ7AU96NfGnEZrOmCQYosyfne6BdgAppUrd6QmKsFMbCswiMCGRtP0NCVteAG-Z7CHtcriuDZZUlcq5-FkIIQ7nt91cVIYaVyQqCTuk-s1Uz3MdaGihYMRM-3Y1r-i3Y3cm_cUrRm7bSJKI9Kzug0KQWYikRz_IU8i5X0TnhlcIDBRGKTkrZy9Ly9u7LST6tLhBW6FnBfPHgf6w2W0gMYwavyR5H1NU0LuG7LHjUpo-Bdd93fEWUtJuc"/>
</div>
</div>
<!-- Secondary Project -->
<div class="md:col-span-4 flex flex-col gap-6">
<div class="flex-1 glass-card rounded-3xl border border-outline-variant/10 p-8 flex flex-col justify-between hover:border-primary/30 transition-colors">
<div>
<div class="flex items-center justify-between mb-4">
<h3 class="text-2xl font-headline font-bold">react-playlist-library</h3>
<span class="material-symbols-outlined text-on-surface-variant" data-icon="queue_music">queue_music</span>
</div>
<p class="text-sm text-on-surface-variant">A JavaScript-based library for managing complex playlists and media queues with ease.</p>
</div>
<div class="flex items-center justify-between pt-6">
<span class="text-xs font-mono text-secondary">JavaScript Lib</span>
<span class="material-symbols-outlined text-primary text-sm" data-icon="arrow_forward">arrow_forward</span>
</div>
</div>
<div class="flex-1 glass-card rounded-3xl border border-outline-variant/10 p-8 flex flex-col justify-between hover:border-primary/30 transition-colors">
<div>
<div class="flex items-center justify-between mb-4">
<h3 class="text-2xl font-headline font-bold">caras-react-ts</h3>
<span class="text-xs font-mono px-2 py-1 bg-tertiary/20 text-tertiary rounded">IN PROGRESS</span>
</div>
<p class="text-sm text-on-surface-variant">A modern, satirical celebrity magazine landing page. Exploring the limits of React 19 and Styled Components.</p>
</div>
<div class="flex flex-wrap gap-2 pt-6">
<span class="text-[10px] font-mono px-2 py-0.5 bg-surface-container-highest rounded">React 19</span>
<span class="text-[10px] font-mono px-2 py-0.5 bg-surface-container-highest rounded">Styled Components</span>
</div>
</div>
</div>
</div>
</section>
<!-- Stats Section -->
<section class="grid grid-cols-1 md:grid-cols-3 gap-8" id="stats">
<div class="md:col-span-2 space-y-6">
<h2 class="text-4xl font-headline font-bold flex items-center gap-3">
<span class="material-symbols-outlined text-primary" data-icon="analytics">analytics</span>
                    Core Metrics
                </h2>
<div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
<div class="bg-surface-container rounded-2xl p-6 border border-outline-variant/5">
<div class="text-on-surface-variant text-sm font-mono mb-4 uppercase">Top Languages</div>
<div class="space-y-3">
<div class="space-y-1">
<div class="flex justify-between text-xs font-mono"><span class="text-primary">TypeScript</span><span>74%</span></div>
<div class="h-1.5 w-full bg-surface-variant rounded-full overflow-hidden">
<div class="h-full bg-primary" style="width: 74%"></div>
</div>
</div>
<div class="space-y-1">
<div class="flex justify-between text-xs font-mono"><span class="text-secondary">JavaScript</span><span>18%</span></div>
<div class="h-1.5 w-full bg-surface-variant rounded-full overflow-hidden">
<div class="h-full bg-secondary" style="width: 18%"></div>
</div>
</div>
<div class="space-y-1">
<div class="flex justify-between text-xs font-mono"><span class="text-on-surface-variant">CSS</span><span>8%</span></div>
<div class="h-1.5 w-full bg-surface-variant rounded-full overflow-hidden">
<div class="h-full bg-outline" style="width: 8%"></div>
</div>
</div>
</div>
</div>
<div class="bg-surface-container rounded-2xl p-6 border border-outline-variant/5 flex flex-col justify-between">
<div class="text-on-surface-variant text-sm font-mono mb-4 uppercase">GitHub Activity</div>
<div class="flex items-end gap-2 h-24">
<!-- Mock Sparkline -->
<div class="flex-1 bg-primary/20 rounded-t h-[40%]"></div>
<div class="flex-1 bg-primary/30 rounded-t h-[60%]"></div>
<div class="flex-1 bg-primary/20 rounded-t h-[30%]"></div>
<div class="flex-1 bg-primary/50 rounded-t h-[80%]"></div>
<div class="flex-1 bg-primary/40 rounded-t h-[55%]"></div>
<div class="flex-1 bg-primary/70 rounded-t h-[95%]"></div>
<div class="flex-1 bg-primary/40 rounded-t h-[50%]"></div>
</div>
<div class="pt-4 text-2xl font-bold font-headline">24 Day Streak</div>
</div>
</div>
</div>
<div class="bg-surface-container-high rounded-3xl p-8 border border-outline-variant/10 flex flex-col justify-center items-center text-center space-y-4">
<span class="material-symbols-outlined text-5xl text-secondary" data-icon="bolt" style="font-variation-settings: 'FILL' 1">bolt</span>
<div class="text-4xl font-headline font-bold">156+</div>
<div class="text-on-surface-variant font-mono uppercase tracking-widest text-xs">Total Contributions</div>
<div class="w-full h-px bg-outline-variant/20 my-2"></div>
<div class="text-primary text-sm">Consistent Daily Growth</div>
</div>
</section>
<!-- Connect Section -->
<section class="flex flex-col items-center text-center space-y-12 py-20 border-y border-outline-variant/10">
<h2 class="text-5xl md:text-6xl font-headline font-bold tracking-tight">Let's build something <br/> <span class="hero-gradient bg-clip-text text-transparent">extraordinary.</span></h2>
<div class="flex flex-wrap justify-center gap-8">
<a class="flex items-center gap-3 text-on-surface-variant hover:text-primary transition-colors duration-300" href="https://github.com/roberrcast">
<span class="material-symbols-outlined text-3xl" data-icon="terminal">terminal</span>
<span class="text-xl font-headline font-medium">roberrcast</span>
</a>
<a class="flex items-center gap-3 text-on-surface-variant hover:text-primary transition-colors duration-300" href="https://linkedin.com/in/roberto-rodriguez-frontend-engineer">
<span class="material-symbols-outlined text-3xl" data-icon="link">link</span>
<span class="text-xl font-headline font-medium">LinkedIn</span>
</a>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full py-12 bg-[#0a0e14] border-t border-[#44484f]/10">
<div class="flex flex-col md:flex-row items-center justify-between px-8 max-w-7xl mx-auto space-y-4 md:space-y-0">
<div class="text-[#00F5FF] font-mono text-lg font-bold">@roberrcast</div>
<p class="font-['Inter'] text-sm text-slate-500">© 2024 Developer Editorial // Designed for The Terminal Luminary</p>
<div class="flex gap-6">
<a class="text-slate-500 hover:text-[#00F5FF] underline decoration-2 underline-offset-4 transition-all duration-300" href="#">GitHub</a>
<a class="text-slate-500 hover:text-[#00F5FF] underline decoration-2 underline-offset-4 transition-all duration-300" href="#">LinkedIn</a>
<a class="text-slate-500 hover:text-[#00F5FF] underline decoration-2 underline-offset-4 transition-all duration-300" href="#">Portfolio</a>
<a class="text-slate-500 hover:text-[#00F5FF] underline decoration-2 underline-offset-4 transition-all duration-300" href="#">Contact</a>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full z-50 flex justify-around items-center px-4 pb-6 pt-2 bg-[#0f141a]/60 backdrop-blur-xl border-t border-[#44484f]/15 shadow-[0_-10px_40px_rgba(0,0,0,0.4)]">
<a class="flex flex-col items-center justify-center bg-[#1b2028] text-[#00F5FF] rounded-xl p-2 scale-110 duration-200" href="#intro">
<span class="material-symbols-outlined" data-icon="person">person</span>
<span class="font-['Space_Grotesk'] text-[10px] uppercase tracking-tighter">Intro</span>
</a>
<a class="flex flex-col items-center justify-center text-slate-500 p-2 hover:bg-[#1b2028] transition-all" href="#skills">
<span class="material-symbols-outlined" data-icon="bolt">bolt</span>
<span class="font-['Space_Grotesk'] text-[10px] uppercase tracking-tighter">Skills</span>
</a>
<a class="flex flex-col items-center justify-center text-slate-500 p-2 hover:bg-[#1b2028] transition-all" href="#projects">
<span class="material-symbols-outlined" data-icon="code">code</span>
<span class="font-['Space_Grotesk'] text-[10px] uppercase tracking-tighter">Projects</span>
</a>
<a class="flex flex-col items-center justify-center text-slate-500 p-2 hover:bg-[#1b2028] transition-all" href="#stats">
<span class="material-symbols-outlined" data-icon="analytics">analytics</span>
<span class="font-['Space_Grotesk'] text-[10px] uppercase tracking-tighter">Stats</span>
</a>
</nav>
</body></html>
**AkuraDiary/AkuraDIary** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
