## <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OKI Token | Orgone Kelowna Initiative</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { background: #0a0f0c; color: #e0e0e0; font-family: system-ui, sans-serif; }
        .gradient-text { background: linear-gradient(135deg, #00d9ff, #00b8a9, #7ae582); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .glass { background: rgba(26,31,28,0.8); backdrop-filter: blur(10px); border: 1px solid rgba(0,217,255,0.1); }
    </style>
</head>
<body class="antialiased">

    <!-- Nav -->
    <nav class="fixed w-full z-50 glass border-b border-cyan-500/10">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded-full bg-gradient-to-br from-cyan-400 to-green-400 flex items-center justify-center">
                    <i data-lucide="hexagon" class="w-5 h-5 text-black"></i>
                </div>
                <span class="font-bold text-xl">OKI<span class="text-cyan-400">Token</span></span>
            </div>
            <div class="hidden md:flex gap-6 text-sm text-gray-400">
                <a href="#impact" class="hover:text-white">Impact</a>
                <a href="#token" class="hover:text-white">Token</a>
                <a href="#science" class="hover:text-white">Science</a>
            </div>
        </div>
    </nav>

    <!-- Hero -->
    <section class="min-h-screen flex items-center justify-center pt-20 px-4">
        <div class="max-w-4xl mx-auto text-center">
            <div class="inline-flex items-center gap-2 glass px-3 py-1 rounded-full mb-6 text-sm text-cyan-400">
                <span class="w-2 h-2 bg-green-400 rounded-full animate-pulse"></span>
                Live from Kelowna, BC
            </div>
            <h1 class="text-5xl md:text-7xl font-bold mb-6">
                Restoring <span class="gradient-text">Nature's Balance</span>
            </h1>
            <p class="text-xl text-gray-400 mb-8 max-w-2xl mx-auto">
                20X stronger orgone technology. Salmon returning to 7 creeks. 5G remediation. 
                Atmospheric restoration. Now open-source for global impact.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <button class="bg-gradient-to-r from-cyan-400 to-teal-400 text-black font-bold px-8 py-3 rounded-full hover:scale-105 transition">
                    Get OKI Token
                </button>
                <button class="glass text-white px-8 py-3 rounded-full hover:bg-cyan-500/10 transition">
                    Watch Documentation
                </button>
            </div>
            
            <!-- Stats -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-12 max-w-3xl mx-auto">
                <div class="glass p-4 rounded-xl">
                    <div class="text-2xl font-bold text-cyan-400">7</div>
                    <div class="text-xs text-gray-500">Creeks Restored</div>
                </div>
                <div class="glass p-4 rounded-xl">
                    <div class="text-2xl font-bold text-green-400">20X</div>
                    <div class="text-xs text-gray-500">Strength</div>
                </div>
                <div class="glass p-4 rounded-xl">
                    <div class="text-2xl font-bold text-teal-400">12+</div>
                    <div class="text-xs text-gray-500">Cell Towers</div>
                </div>
                <div class="glass p-4 rounded-xl">
                    <div class="text-2xl font-bold text-white">3</div>
                    <div class="text-xs text-gray-500">Chembusters</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="impact" class="py-20 px-4">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12">Documented Impact</h2>
            
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Creek Restoration -->
                <div class="glass rounded-2xl p-6">
                    <div class="flex items-center gap-2 mb-4 text-cyan-400">
                        <i data-lucide="waves" class="w-5 h-5"></i>
                        <span class="font-medium">Aquatic Restoration</span>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Salmon Creek Restoration</h3>
                    <p class="text-gray-400 text-sm mb-4">
                        Seven creeks around Kelowna declared biologically dead now support 
                        thriving salmon runs. Scientists said it was impossible.
                    </p>
                    <div class="flex items-center gap-4 text-xs text-gray-500">
                        <span>7/7 Creeks Active</span>
                        <span>3 Years Running</span>
                    </div>
                </div>

                <!-- 5G Remediation -->
                <div class="glass rounded-2xl p-6">
                    <div class="flex items-center gap-2 mb-4 text-teal-400">
                        <i data-lucide="tower-control" class="w-5 h-5"></i>
                        <span class="font-medium">EMF Remediation</span>
                    </div>
                    <h3 class="text-xl font-bold mb-2">5G Test Bed Remediation</h3>
                    <p class="text-gray-400 text-sm mb-4">
                        Kelowna is an official 5G test bed city. Orgone devices placed on 
                        12+ cell towers to harmonize electromagnetic radiation.
                    </p>
                    <div class="flex items-center gap-4 text-xs text-gray-500">
                        <span>12+ Towers Treated</span>
                        <span>Community Monitoring</span>
                    </div>
                </div>

                <!-- Chembusters -->
                <div class="glass rounded-2xl p-6">
                    <div class="flex items-center gap-2 mb-4 text-green-400">
                        <i data-lucide="cloud" class="w-5 h-5"></i>
                        <span class="font-medium">Atmospheric Engineering</span>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Community Chembusters</h3>
                    <p class="text-gray-400 text-sm mb-4">
                        $8,000 invested in 3 chembusters deployed across Kelowna. 
                        Documented atmospheric remediation results.
                    </p>
                    <div class="flex items-center gap-4 text-xs text-gray-500">
                        <span>24/7 Operation</span>
                        <span>$8K Community Investment</span>
                    </div>
                </div>

                <!-- Houseboat -->
                <div class="glass rounded-2xl p-6 border-cyan-500/30">
                    <div class="flex items-center gap-2 mb-4 text-cyan-400">
                        <i data-lucide="anchor" class="w-5 h-5"></i>
                        <span class="font-medium">Mobile Lab</span>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Houseboat Water Project</h3>
                    <p class="text-gray-400 text-sm mb-4">
                        Converting a houseboat into a mobile orgone research station 
                        for Okanagan Lake water purification.
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="text-xs text-gray-500">Fundraising: $50K Goal</span>
                        <button class="text-xs bg-cyan-500/20 text-cyan-400 px-3 py-1 rounded-full">Support</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Token Section -->
    <section id="token" class="py-20 px-4 bg-black/20">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-4xl font-bold mb-4">OKI Token</h2>
            <p class="text-gray-400 mb-12">Open-source. No patents. No barriers. Just results.</p>
            
            <div class="glass rounded-2xl p-8 mb-8">
                <div class="grid md:grid-cols-3 gap-6 text-left">
                    <div>
                        <i data-lucide="download" class="w-6 h-6 text-cyan-400 mb-2"></i>
                        <h4 class="font-bold mb-1">Blueprints</h4>
                        <p class="text-sm text-gray-400">Access 20X orgone formulas</p>
                    </div>
                    <div>
                        <i data-lucide="vote" class="w-6 h-6 text-teal-400 mb-2"></i>
                        <h4 class="font-bold mb-1">Governance</h4>
                        <p class="text-sm text-gray-400">Vote on project funding</p>
                    </div>
                    <div>
                        <i data-lucide="award" class="w-6 h-6 text-green-400 mb-2"></i>
                        <h4 class="font-bold mb-1">Certification</h4>
                        <p class="text-sm text-gray-400">Become OKI Certified Builder</p>
                    </div>
                </div>
            </div>

            <!-- Tokenomics -->
            <div class="glass rounded-2xl p-6 text-left">
                <h3 class="font-bold mb-6 text-center">Token Distribution</h3>
                <div class="space-y-3 text-sm">
                    <div class="flex justify-between"><span class="text-gray-400">Community & Public Good</span><span class="text-cyan-400">40%</span></div>
                    <div class="w-full bg-gray-800 rounded-full h-2"><div class="bg-cyan-400 h-2 rounded-full" style="width:40%"></div></div>
                    
                    <div class="flex justify-between"><span class="text-gray-400">Ecosystem Development</span><span class="text-teal-400">25%</span></div>
                    <div class="w-full bg-gray-800 rounded-full h-2"><div class="bg-teal-400 h-2 rounded-full" style="width:25%"></div></div>
                    
                    <div class="flex justify-between"><span class="text-gray-400">Team & Advisors</span><span class="text-green-400">15%</span></div>
                    <div class="w-full bg-gray-800 rounded-full h-2"><div class="bg-green-400 h-2 rounded-full" style="width:15%"></div></div>
                    
                    <div class="flex justify-between"><span class="text-gray-400">Treasury</span><span class="text-white">10%</span></div>
                    <div class="w-full bg-gray-800 rounded-full h-2"><div class="bg-white h-2 rounded-full" style="width:10%"></div></div>
                    
                    <div class="flex justify-between"><span class="text-gray-400">Liquidity</span><span class="text-gray-400">10%</span></div>
                    <div class="w-full bg-gray-800 rounded-full h-2"><div class="bg-gray-400 h-2 rounded-full" style="width:10%"></div></div>
                </div>
                <div class="mt-6 pt-6 border-t border-gray-700 flex justify-between">
                    <span class="text-gray-400">Total Supply</span>
                    <span class="font-bold">1,000,000,000 OKI</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Science -->
    <section id="science" class="py-20 px-4">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12">20X Stronger</h2>
            <div class="glass rounded-2xl p-8">
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="bg-black/30 p-4 rounded-xl">
                        <div class="text-cyan-400 font-bold text-lg">Biological</div>
                        <p class="text-sm text-gray-400">Seed germination, plant growth, microbial activity</p>
                    </div>
                    <div class="bg-black/30 p-4 rounded-xl">
                        <div class="text-teal-400 font-bold text-lg">EMF Harmonization</div>
                        <p class="text-sm text-gray-400">Spectral analysis of field chaos reduction</p>
                    </div>
                    <div class="bg-black/30 p-4 rounded-xl">
                        <div class="text-green-400 font-bold text-lg">Water Quality</div>
                        <p class="text-sm text-gray-400">Oxidative potential, dissolved oxygen levels</p>
                    </div>
                    <div class="bg-black/30 p-4 rounded-xl">
                        <div class="text-white font-bold text-lg">Durability</div>
                        <p class="text-sm text-gray-400">50+ year lifespan vs 10-15 standard</p>
                    </div>
                </div>
                <div class="mt-6 p-4 bg-cyan-500/10 rounded-xl border border-cyan-500/20 text-sm text-gray-300">
                    Independent validation studies underway. All claims based on observable, measurable phenomena.
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-cyan-500/10 py-12 px-4 bg-black/30">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded-full bg-gradient-to-br from-cyan-400 to-green-400 flex items-center justify-center">
                    <i data-lucide="hexagon" class="w-5 h-5 text-black"></i>
                </div>
                <span class="font-bold">OKI<span class="text-cyan-400">Token</span></span>
            </div>
            <div class="flex gap-6 text-sm text-gray-400">
                <a href="https://tiktok.com/@yourhandle" class="hover:text-cyan-400">TikTok</a>
                <a href="#" class="hover:text-cyan-400">Discord</a>
                <a href="#" class="hover:text-cyan-400">GitHub</a>
            </div>
            <div class="text-sm text-gray-500">© 2024 Orgone Kelowna Initiative</div>
        </div>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
 👋

<!--
**okitoken-Kelowna-orgoneproject/Okitoken-kelowna-orgoneproject** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
