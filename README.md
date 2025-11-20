<!-- Navigation -->
<nav class="fixed w-full z-50 top-0 start-0 border-b border-slate-800 bg-slate-950/80 backdrop-blur-md transition-all duration-300" id="navbar">
    <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between p-4">
        <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse">
            <span class="self-center text-2xl font-bold whitespace-nowrap text-white tracking-tight">ISHAN<span class="text-[#4FC3F7]">.</span></span>
        </a>
        <div class="flex md:order-2 space-x-3 md:space-x-0 rtl:space-x-reverse">
            <a href="https://ishan-omega.vercel.app/" target="_blank" class="text-white bg-[#4FC3F7] hover:bg-sky-500 focus:ring-4 focus:outline-none focus:ring-sky-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center transition-all shadow-[0_0_15px_rgba(79,195,247,0.5)]">
                Visit Portfolio
            </a>
        </div>
        <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1">
            <ul class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-slate-800 rounded-lg md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0">
                <li><a href="#about" class="block py-2 px-3 text-slate-300 hover:text-[#4FC3F7] md:p-0 transition-colors">About</a></li>
                <li><a href="#stack" class="block py-2 px-3 text-slate-300 hover:text-[#4FC3F7] md:p-0 transition-colors">Tech Stack</a></li>
                <li><a href="#stats" class="block py-2 px-3 text-slate-300 hover:text-[#4FC3F7] md:p-0 transition-colors">Stats</a></li>
                <li><a href="#connect" class="block py-2 px-3 text-slate-300 hover:text-[#4FC3F7] md:p-0 transition-colors">Connect</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="min-h-screen flex items-center justify-center pt-20 relative overflow-hidden">
    <!-- Background decorations -->
    <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-sky-500/10 rounded-full blur-3xl -z-10 animate-pulse"></div>
    <div class="absolute bottom-1/4 right-1/4 w-96 h-96 bg-purple-500/10 rounded-full blur-3xl -z-10 animate-pulse delay-700"></div>

    <div class="text-center max-w-5xl px-6 py-12 reveal active">
        <div class="mb-6 inline-block">
            <img src="https://komarev.com/ghpvc/?username=WAH-ISHAN&style=flat-square&color=4FC3F7" alt="Profile Views" class="h-6 opacity-80 hover:opacity-100 transition-opacity">
        </div>
        
        <h1 class="text-5xl md:text-7xl font-bold text-white mb-4 tracking-tight">
            Hi there, I'm <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#4FC3F7] to-blue-600">ISHAN</span> <span class="animate-bounce inline-block">👋</span>
        </h1>
        
        <h3 class="text-xl md:text-2xl text-slate-400 mb-8 font-light">
            AI Engineer in Progress · Full‑Stack Developer
        </h3>

        <div class="flex justify-center mb-10 h-16">
            <!-- Typing SVG from prompt -->
            <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=4FC3F7&center=true&vCenter=true&width=600&lines=Crafting+AI+Solutions+%F0%9F%A4%96;Building+Intelligent+Apps+%E2%9A%99%EF%B8%8F;Learning+End-to-End+MLOps+%F0%9F%92%BB;Transforming+Ideas+into+Code+%F0%9F%96%A5%EF%B8%8F" alt="Typing Animation" class="max-w-full h-full object-contain">
        </div>

        <div class="flex justify-center gap-4">
            <a href="#about" class="text-white border border-slate-600 hover:bg-slate-800 focus:ring-4 focus:outline-none focus:ring-slate-700 font-medium rounded-lg text-sm px-6 py-3 text-center transition-all">
                More About Me
            </a>
            <a href="#connect" class="text-slate-900 bg-white hover:bg-slate-100 focus:ring-4 focus:outline-none focus:ring-slate-200 font-medium rounded-lg text-sm px-6 py-3 text-center transition-all">
                Let's Connect
            </a>
        </div>
        
        <div class="mt-12 animate-bounce text-slate-600">
            <svg class="w-6 h-6 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path></svg>
        </div>
    </div>
</section>

<div class="max-w-7xl mx-auto px-6 space-y-32 pb-20">

    <!-- About Me Section -->
    <section id="about" class="reveal">
        <div class="flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2 order-2 md:order-1 space-y-6">
                <div class="flex items-center gap-3 mb-4">
                    <span class="text-3xl">🔍</span>
                    <h2 class="text-3xl font-bold text-white">About Me</h2>
                </div>
                
                <div class="glass-card p-8 rounded-2xl space-y-4 text-lg leading-relaxed">
                    <ul class="space-y-4 list-none">
                        <li class="flex items-start gap-3">
                            <span class="mt-1 text-[#4FC3F7]">🧠</span>
                            <span>Focused on <strong>AI/ML</strong>, <strong>Enterprise App Development</strong>, and <strong>MERN-Stack Development</strong></span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="mt-1 text-[#4FC3F7]">👨‍💻</span>
                            <span>Using tools like <code class="bg-slate-800 px-1 py-0.5 rounded text-[#4FC3F7] font-mono text-sm">TensorFlow</code>, <code class="bg-slate-800 px-1 py-0.5 rounded text-[#4FC3F7] font-mono text-sm">FastAPI</code>, <code class="bg-slate-800 px-1 py-0.5 rounded text-[#4FC3F7] font-mono text-sm">React</code>, <code class="bg-slate-800 px-1 py-0.5 rounded text-[#4FC3F7] font-mono text-sm">Spring Boot</code></span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="mt-1 text-[#4FC3F7]">🎮</span>
                            <span>Exploring 3D UI/UX with <strong>Three.js</strong> and <strong>Blender</strong></span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="mt-1 text-[#4FC3F7]">🗃️</span>
                            <span>Experienced with both SQL (MySQL) and NoSQL (MongoDB)</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="mt-1 text-[#4FC3F7]">🔄</span>
                            <span>Building real-world solutions combining AI, automation, and reliable ML pipelines</span>
                        </li>
                    </ul>
                </div>

                <!-- Fun Fact -->
                <div class="mt-6 p-4 border-l-4 border-[#4FC3F7] bg-slate-900/50 italic">
                    <h4 class="font-bold text-white mb-1 flex items-center gap-2">⚡ Fun Fact</h4>
                    <p>"I debug life the same way I debug code—one breakpoint at a time. 😉"</p>
                </div>
            </div>

            <div class="md:w-1/2 order-1 md:order-2 flex justify-center">
                <div class="relative">
                    <div class="absolute inset-0 bg-gradient-to-tr from-[#4FC3F7] to-purple-600 rounded-full blur-2xl opacity-20 animate-pulse"></div>
                    <img src="https://raw.githubusercontent.com/sanjay-kv/sanjay-kv/main/Assets/illustration.png" alt="Illustration" class="relative z-10 w-80 md:w-96 drop-shadow-2xl hover:scale-105 transition-transform duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- Learning & Interests Grid -->
    <section class="reveal">
        <div class="grid md:grid-cols-2 gap-8">
            <!-- Currently Learning -->
            <div class="glass-card p-6 rounded-2xl">
                <h3 class="text-xl font-bold text-white mb-4 flex items-center gap-2">
                    🌱 Currently Learning
                </h3>
                <ul class="space-y-3">
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">🔬</span>
                        <span>Deep Learning: Transformers, GANs, Vision-Language Models</span>
                    </li>
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">⚙️</span>
                        <span>CI/CD with Docker, GitHub Actions, K8s</span>
                    </li>
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">💡</span>
                        <span>Next.js + Blender embedded scenes</span>
                    </li>
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">🎨</span>
                        <span>Framer Motion for animation-rich UI</span>
                    </li>
                </ul>
            </div>

            <!-- Ask Me About -->
            <div class="glass-card p-6 rounded-2xl">
                <h3 class="text-xl font-bold text-white mb-4 flex items-center gap-2">
                    🧠 Ask Me About
                </h3>
                <ul class="space-y-3">
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">🔁</span>
                        <span>My journey from <strong>Finance to AI</strong></span>
                    </li>
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">⚙️</span>
                        <span>Architecting scalable backend systems</span>
                    </li>
                    <li class="flex items-center gap-3 p-2 hover:bg-slate-800/50 rounded transition-colors">
                        <span class="text-xl">💡</span>
                        <span>Turning vague ideas into <strong>production AI</strong></span>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Tech Stack Section -->
    <section id="stack" class="reveal">
        <div class="text-center mb-10">
            <h2 class="text-3xl font-bold text-white mb-2">🛠️ Tech Stack</h2>
            <p class="text-slate-400">My weapon of choice for building digital products</p>
        </div>

        <div class="space-y-8">
            <!-- Languages -->
            <div class="glass-card p-6 rounded-2xl">
                <h3 class="text-lg font-semibold text-[#4FC3F7] mb-4">Languages & Frameworks</h3>
                <div class="flex flex-wrap justify-center gap-3">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/javascript-%23323330?style=for-the-badge&logo=javascript" alt="JavaScript">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/java-%23ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js" alt="Node.js">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/SpringBoot-%236DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="FastAPI">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js" alt="Next.js">
                    <img class="tech-badge h-8 md:h-10" src="https://img.shields.io/badge/three.js-black?style=for-the-badge&logo=three.js" alt="Three.js">
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- AI/ML -->
                <div class="glass-card p-6 rounded-2xl">
                    <h3 class="text-lg font-semibold text-[#4FC3F7] mb-4">AI & Machine Learning</h3>
                    <div class="flex flex-wrap gap-3">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/TensorFlow-%23FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white" alt="TensorFlow">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/PyTorch-%23EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/Keras-%23D00000?style=for-the-badge&logo=Keras&logoColor=white" alt="Keras">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/scikit--learn-%23F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/pandas-%23150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
                    </div>
                </div>

                <!-- Tools & DB -->
                <div class="glass-card p-6 rounded-2xl">
                    <h3 class="text-lg font-semibold text-[#4FC3F7] mb-4">Databases & Tools</h3>
                    <div class="flex flex-wrap gap-3">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/mysql-%2300f?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/MongoDB-%234ea94b?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/docker-%230db7ed?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/GitHub_Actions-%232671E5?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
                        <img class="tech-badge h-8" src="https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white" alt="Blender">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- GitHub Stats -->
    <section id="stats" class="reveal">
        <h2 class="text-3xl font-bold text-white mb-8 text-center">📊 GitHub Stats</h2>
        <div class="flex flex-wrap justify-center gap-4">
            <img src="https://github-readme-stats.vercel.app/api?username=WAH-ISHAN&theme=tokyonight&show_icons=true&hide_border=false" alt="GitHub Stats" class="h-40 md:h-48 shadow-lg rounded hover:scale-105 transition-transform">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=WAH-ISHAN&theme=tokyonight&hide_border=false" alt="Streak Stats" class="h-40 md:h-48 shadow-lg rounded hover:scale-105 transition-transform">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=WAH-ISHAN&layout=compact&theme=tokyonight&hide_border=false" alt="Top Languages" class="h-40 md:h-48 shadow-lg rounded hover:scale-105 transition-transform">
        </div>
    </section>

    <!-- Support & Visitor Count -->
    <section class="reveal text-center">
        <div class="glass-card p-8 rounded-2xl inline-block w-full max-w-3xl">
            <h2 class="text-2xl font-bold text-white mb-4">💖 Support / Sponsor Me</h2>
            <p class="mb-6 text-slate-400">
                If you like my work and want to support me to keep building cool AI and software projects.
            </p>
            <div class="flex flex-wrap justify-center gap-4 mb-8">
                <a href="https://github.com/sponsors/WAH-ISHAN" target="_blank">
                    <img src="https://img.shields.io/badge/Sponsor-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Sponsor on GitHub" class="h-10 hover:opacity-80 transition-opacity">
                </a>
                <a href="#" target="_blank">
                    <img src="https://img.shields.io/badge/Support-Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white" alt="Support on Patreon" class="h-10 hover:opacity-80 transition-opacity">
                </a>
                <a href="#" target="_blank">
                    <img src="https://img.shields.io/badge/Buy%20me%20a%20Coffee-Ko--Fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Buy me a Coffee" class="h-10 hover:opacity-80 transition-opacity">
                </a>
            </div>
            
            <div class="border-t border-slate-700 pt-6">
                <h4 class="text-sm uppercase tracking-widest text-slate-500 mb-3">Visitor Counter</h4>
                <img src="https://visitcount.itsvg.in/api?id=WAH-ISHAN&icon=6&color=12" alt="Visitor Count" class="mx-auto h-8">
            </div>
        </div>
    </section>

</div>

<!-- Footer / Connect -->
<footer id="connect" class="bg-slate-950 border-t border-slate-800 py-12">
    <div class="max-w-7xl mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold text-white mb-8">🌐 Connect With Me</h2>
        <div class="flex justify-center gap-6 mb-10">
            <a href="https://www.linkedin.com/in/w-a-h-ishan-715176305" target="_blank" class="transform hover:scale-110 transition-transform">
                <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" class="h-10">
            </a>
            <a href="https://discord.gg/ishan048896" target="_blank" class="transform hover:scale-110 transition-transform">
                <img alt="Discord" src="https://img.shields.io/badge/Discord-%237289DA?style=for-the-badge&logo=discord&logoColor=white" class="h-10">
            </a>
            <a href="https://www.hackerrank.com/profile/wahasinduishan" target="_blank" class="transform hover:scale-110 transition-transform">
                <img alt="HackerRank" src="https://img.shields.io/badge/HackerRank-%232EC866?style=for-the-badge&logo=hackerrank&logoColor=white" class="h-10">
            </a>
        </div>
        <p class="text-slate-500">
            © 2024 Ishan. Crafted with <span class="text-red-500">❤</span> and Code.
        </p>
    </div>
</footer>

<script>
    // Scroll Reveal Animation
    document.addEventListener('DOMContentLoaded', () => {
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                    // Optional: Stop observing once revealed
                    // observer.unobserve(entry.target); 
                }
            });
        }, observerOptions);

        document.querySelectorAll('.reveal').forEach(el => {
            observer.observe(el);
        });

        // Navbar background toggle on scroll
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('shadow-lg', 'bg-slate-950/95');
                navbar.classList.remove('bg-slate-950/80');
            } else {
                navbar.classList.remove('shadow-lg', 'bg-slate-950/95');
                navbar.classList.add('bg-slate-950/80');
            }
        });
    });
</script>
