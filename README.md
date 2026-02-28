<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webbie Board | Sky Blue Edition</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;800&display=swap" rel="stylesheet">
    
    <style>
        /* --- DESIGN TAGS / CSS ORGANIZED --- */
        :root {
            --sky-main: #0ea5e9;
            --sky-light: #e0f2fe;
            --sky-dark: #0369a1;
            --text-main: #0f172a;
            --white-board: #ffffff;
        }

        body { 
            font-family: 'Outfit', sans-serif; 
            scroll-behavior: smooth;
            color: var(--text-main);
        }

        /* Colorful Gradient Backgrounds */
        .hero-gradient {
            background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
        }

        .btn-primary {
            background-color: var(--sky-main);
            color: white;
            transition: all 0.3s ease;
        }

        .btn-primary:hover {
            background-color: var(--sky-dark);
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(14, 165, 233, 0.4);
        }

        /* Whiteboard Visualizer Pattern */
        .whiteboard-pattern {
            background-color: #ffffff;
            background-image:  linear-gradient(#e0f2fe 1.5px, transparent 1.5px), linear-gradient(90deg, #e0f2fe 1.5px, transparent 1.5px);
            background-size: 30px 30px;
        }
    </style>
</head>
<body class="bg-white">

    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md border-b border-sky-100">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-sky-500 rounded-xl flex items-center justify-center text-white shadow-lg shadow-sky-200">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z" />
                    </svg>
                </div>
                <span class="text-2xl font-extrabold tracking-tight text-sky-900">Webbie Board</span>
            </div>
            <div class="hidden md:flex gap-8 font-semibold text-sky-800/70">
                <a href="#home" class="hover:text-sky-500 transition">Home</a>
                <a href="#services" class="hover:text-sky-500 transition">Services</a>
                <a href="#about" class="hover:text-sky-500 transition">About</a>
                <a href="#contact" class="hover:text-sky-500 transition">Contact</a>
            </div>
            <button class="btn-primary px-6 py-2.5 rounded-full font-bold text-sm">
                Launch Board
            </button>
        </div>
    </nav>

    <section id="home" class="hero-gradient pt-40 pb-24 px-6">
        <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center gap-12">
            <div class="lg:w-1/2 text-left">
                <h1 class="text-6xl md:text-7xl font-extrabold text-slate-900 leading-tight mb-6">
                    Your Web Ideas, <span class="text-sky-500">Visualized.</span>
                </h1>
                <p class="text-xl text-slate-600 mb-8 leading-relaxed">
                    The colorful whiteboard for web architects. Drag navbars, style scrollbars, and build your UI blueprint in minutes—not hours.
                </p>
                <div class="flex gap-4">
                    <button class="btn-primary px-8 py-4 rounded-2xl text-lg font-bold">Start Designing</button>
                    <button class="bg-white text-sky-600 border-2 border-sky-100 px-8 py-4 rounded-2xl text-lg font-bold hover:bg-sky-50 transition">See Components</button>
                </div>
            </div>
            <div class="lg:w-1/2 w-full">
                <div class="whiteboard-pattern h-[400px] rounded-3xl border-4 border-white shadow-2xl relative overflow-hidden p-6 flex items-start justify-center">
                    <div class="w-full bg-white shadow-md border border-sky-100 rounded-lg p-3 flex justify-between items-center">
                        <div class="flex gap-2"><div class="w-3 h-3 bg-red-400 rounded-full"></div><div class="w-3 h-3 bg-yellow-400 rounded-full"></div><div class="w-3 h-3 bg-green-400 rounded-full"></div></div>
                        <div class="h-2 w-32 bg-sky-100 rounded"></div>
                        <div class="h-6 w-12 bg-sky-500 rounded"></div>
                    </div>
                    <div class="absolute bottom-10 right-10 w-24 h-48 bg-sky-50 rounded-xl border-2 border-sky-200 p-2 flex flex-col gap-2">
                         <div class="h-1 bg-sky-300 w-full rounded"></div>
                         <div class="h-1 bg-sky-200 w-3/4 rounded"></div>
                         <div class="h-1 bg-sky-100 w-1/2 rounded"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h2 class="text-4xl font-black text-slate-900 mb-12">Every Component is Ready</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="p-6 bg-sky-50 rounded-3xl border-2 border-transparent hover:border-sky-300 transition cursor-pointer">
                    <div class="text-4xl mb-3">🧭</div>
                    <span class="font-bold text-sky-900">Navbars</span>
                </div>
                <div class="p-6 bg-sky-50 rounded-3xl border-2 border-transparent hover:border-sky-300 transition cursor-pointer">
                    <div class="text-4xl mb-3">🖱️</div>
                    <span class="font-bold text-sky-900">Scroll Bars</span>
                </div>
                <div class="p-6 bg-sky-50 rounded-3xl border-2 border-transparent hover:border-sky-300 transition cursor-pointer">
                    <div class="text-4xl mb-3">📄</div>
                    <span class="font-bold text-sky-900">Footers</span>
                </div>
                <div class="p-6 bg-sky-50 rounded-3xl border-2 border-transparent hover:border-sky-300 transition cursor-pointer">
                    <div class="text-4xl mb-3">📱</div>
                    <span class="font-bold text-sky-900">Breakpoints</span>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 bg-sky-600 text-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-6 text-sky-100 underline decoration-sky-300 decoration-4 underline-offset-8">Our Mission</h2>
            <p class="text-xl leading-relaxed opacity-90">
                Webbie Board was created to replace messy hand-drawn sketches with clean, functional blueprints. We believe that if you can see your website's logic before you build it, you'll write better code.
            </p>
        </div>
    </section>

    <section id="contact" class="py-24">
        <div class="max-w-xl mx-auto px-6 bg-white border-2 border-sky-100 p-10 rounded-[2rem] shadow-xl">
            <h3 class="text-3xl font-bold text-center mb-8">Join the Community</h3>
            <div class="space-y-4">
                <input type="text" placeholder="Your Name" class="w-full p-4 bg-sky-50 rounded-xl outline-none focus:ring-2 focus:ring-sky-400 border-none">
                <input type="email" placeholder="Your Email" class="w-full p-4 bg-sky-50 rounded-xl outline-none focus:ring-2 focus:ring-sky-400 border-none">
                <textarea placeholder="Tell us what you're building" rows="4" class="w-full p-4 bg-sky-50 rounded-xl outline-none focus:ring-2 focus:ring-sky-400 border-none"></textarea>
                <button class="btn-primary w-full py-4 rounded-xl font-bold uppercase tracking-widest">Send Message</button>
            </div>
        </div>
    </section>

    <footer class="py-8 text-center text-sky-900/50 font-medium">
        <p>&copy; 2026 Webbie Board • Visualizer Tools for Professionals</p>
    </footer>

</body>
</html>
