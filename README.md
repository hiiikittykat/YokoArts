<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>☁ YokoArts 🩵</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Quicksand & Varela Round for maximum cuteness -->
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&family=Varela+Round&display=swap" rel="stylesheet">
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        bunnyBlue: '#7ab8ff',
                        bunnyLightBlue: '#eef6ff',
                        bunnySky: '#d4e7ff',
                        bunnyDarkBlue: '#3575db',
                        bunnyCream: '#f8fbff',
                        bunnyAccent: '#93c5fd'
                    },
                    fontFamily: {
                        cute: ['"Varela Round"', 'sans-serif'],
                        body: ['Quicksand', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Quicksand', sans-serif;
            background-color: #f4f8ff;
            color: #4a5568;
            overflow-x: hidden;
        }
        h1, h2, h3, h4, .font-cute {
            font-family: 'Varela Round', sans-serif;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(2deg); }
        }
        .animate-float {
            animation: float 4s ease-in-out infinite;
        }
        ::-webkit-scrollbar {
            width: 10px;
        }
        ::-webkit-scrollbar-track {
            background: #eaf3ff;
        }
        ::-webkit-scrollbar-thumb {
            background: #93c5fd;
            border-radius: 9999px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #60a5fa;
        }
    </style>
</head>
<body class="bg-bunnyCream relative selection:bg-blue-200">

    <div class="fixed top-10 left-5 opacity-40 pointer-events-none animate-float hidden md:block z-0">
        <svg width="90" height="60" viewBox="0 0 100 60" fill="#bfdbfe"><path d="M20 50h60a20 20 0 000-40 25 25 0 00-45-5 20 20 0 00-15 45z"/></svg>
    </div>
    <div class="fixed top-40 right-10 opacity-30 pointer-events-none animate-float hidden md:block z-0" style="animation-delay: 1.5s;">
        <svg width="110" height="70" viewBox="0 0 100 60" fill="#93c5fd"><path d="M20 50h60a20 20 0 000-40 25 25 0 00-45-5 20 20 0 00-15 45z"/></svg>
    </div>

    <!-- Navbar -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-blue-100 shadow-sm">
        <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center gap-2 group">
                <div class="w-10 h-10 rounded-full bg-blue-50 flex items-center justify-center border-2 border-blue-200 group-hover:scale-105 transition">
                    <!-- Cute Rabbit Head Mini SVG -->
                    <svg viewBox="0 0 64 64" class="w-7 h-7">
                        <ellipse cx="26" cy="18" rx="4" ry="10" fill="#ffffff" stroke="#7ab8ff" stroke-width="2"/>
                        <ellipse cx="38" cy="18" rx="4" ry="10" fill="#ffffff" stroke="#7ab8ff" stroke-width="2"/>
                        <ellipse cx="26" cy="18" rx="2" ry="7" fill="#ffc8dd"/>
                        <ellipse cx="38" cy="18" rx="2" ry="7" fill="#ffc8dd"/>
                        <circle cx="32" cy="36" r="14" fill="#ffffff" stroke="#7ab8ff" stroke-width="2"/>
                        <circle cx="27" cy="35" r="1.5" fill="#4a5568"/>
                        <circle cx="37" cy="35" r="1.5" fill="#4a5568"/>
                        <ellipse cx="32" cy="38" rx="1.5" ry="1" fill="#ffb6c1"/>
                        <ellipse cx="22" cy="38" rx="2.5" ry="1.2" fill="#ffb6c1" opacity="0.6"/>
                        <ellipse cx="42" cy="38" rx="2.5" ry="1.2" fill="#ffb6c1" opacity="0.6"/>
                    </svg>
                </div>
                <span class="font-cute font-bold text-lg text-blue-500 tracking-wide">YokoArts</span>
            </a>
            <nav class="hidden md:flex gap-6 font-medium text-sm text-gray-600">
                <a href="#welcome" class="hover:text-blue-500 transition">Home</a>
                <a href="#gallery" class="hover:text-blue-500 transition">Gallery</a>
                <a href="#prices" class="hover:text-blue-500 transition">Prices</a>
                <a href="#calculator" class="hover:text-blue-500 transition">Quote Calculator</a>
                <a href="#dos-donts" class="hover:text-blue-500 transition">Can / Can't Draw</a>
                <a href="#rules" class="hover:text-blue-500 transition">Rules</a>
                <a href="#order" class="hover:text-blue-500 transition">How to Order</a>
            </nav>
            <div class="flex items-center gap-3">
                <a href="https://www.tiktok.com/@yoko.arts?_r=1&_t=ZP-9A9WuhRu0AZ" target="_blank" class="w-9 h-9 rounded-full bg-blue-50 hover:bg-blue-100 text-blue-500 flex items-center justify-center border border-blue-200 transition" title="TikTok">
                    <i class="fa-brands fa-tiktok text-sm"></i>
                </a>
                <a href="#order" class="bg-gradient-to-r from-blue-400 to-blue-500 text-white font-cute text-sm px-4 py-2 rounded-full shadow-md hover:shadow-lg hover:from-blue-500 hover:to-blue-600 transition transform hover:-translate-y-0.5">
                    <i class="fa-solid fa-envelope-heart mr-1"></i> Order
                </a>
            </div>
        </div>
    </header>

    <main class="max-w-5xl mx-auto px-4 py-8 relative z-10 space-y-16">

        <!-- Hero Section -->
        <section id="welcome" class="bg-white/90 backdrop-blur rounded-3xl p-6 md:p-10 border-4 border-blue-100 shadow-xl relative overflow-hidden">
            <div class="absolute -right-10 -bottom-10 opacity-15 pointer-events-none">
                <svg width="300" height="300" viewBox="0 0 100 100" fill="#93c5fd"><circle cx="50" cy="50" r="50"/></svg>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-12 gap-8 items-center">
                <div class="md:col-span-7 space-y-4 text-center md:text-left">
                    <span class="inline-block bg-blue-100 text-blue-600 font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider mb-2">
                        🩵 Welcome to my commissions! ✨
                    </span>
                    <h1 class="font-cute text-3xl md:text-4xl lg:text-5xl font-bold text-gray-700 leading-tight">
                        Let's make your <span class="text-blue-500">ideas come true!</span> ☁️
                    </h1>
                    <p class="text-gray-600 leading-relaxed">
                        I'm a very flexible artist and I love experimenting with different styles! My main favorites are anime-inspired art, Moe, and character illustrations, but I'm always willing to try something different. 🩵
                    </p>
                    <p class="text-sm text-gray-500 bg-blue-50 p-3 rounded-2xl border border-blue-100">
                        ✨ <em>If you have an idea that isn't listed below, DM me or send an email! We can talk about what you want together.</em>
                    </p>
                    <div class="pt-2 flex flex-wrap gap-3 justify-center md:justify-start">
                        <a href="#prices" class="bg-blue-400 hover:bg-blue-500 text-white font-cute px-6 py-3 rounded-2xl shadow-md transition transform hover:-scale-105">
                            View Price Range 🎨
                        </a>
                        <a href="#calculator" class="bg-blue-50 hover:bg-blue-100 text-blue-700 font-cute px-6 py-3 rounded-2xl transition border border-blue-200">
                            Calculate Price 🧮
                        </a>
                    </div>
                </div>
                <div class="md:col-span-5 flex justify-center">
                    <!-- Cute Rabbit Showcase Illustration Card -->
                    <div class="relative bg-gradient-to-b from-blue-50 to-white p-4 rounded-3xl border-4 border-white shadow-lg animate-float max-w-xs w-full text-center">
                        <div class="absolute -top-3 -right-3 bg-blue-400 text-white rounded-full w-8 h-8 flex items-center justify-center shadow">
                            <i class="fa-solid fa-crown text-xs"></i>
                        </div>
                        <!-- White Crowned Rabbit SVG Art Piece with Animated Blinking Eyes -->
                        <div class="bg-white rounded-2xl p-4 shadow-inner mb-3 flex flex-col items-center justify-center">
                            <svg viewBox="0 0 200 160" class="w-full h-36">
                                <!-- Bunny Ears -->
                                <ellipse cx="80" cy="35" rx="12" ry="30" fill="#ffffff" stroke="#93c5fd" stroke-width="3"/>
                                <ellipse cx="80" cy="35" rx="6" ry="20" fill="#ffc8dd"/>
                                <ellipse cx="120" cy="35" rx="12" ry="30" fill="#ffffff" stroke="#93c5fd" stroke-width="3"/>
                                <ellipse cx="120" cy="35" rx="6" ry="20" fill="#ffc8dd"/>
                                <!-- Bunny Head -->
                                <ellipse cx="100" cy="95" rx="42" ry="36" fill="#ffffff" stroke="#93c5fd" stroke-width="3"/>
                                <!-- Crown -->
                                <polygon points="85,55 92,38 100,50 108,38 115,55" fill="#facc15" stroke="#eab308" stroke-width="2"/>
                                <circle cx="92" cy="42" r="2" fill="#fff"/>
                                <circle cx="100" cy="48" r="2" fill="#fff"/>
                                <circle cx="108" cy="42" r="2" fill="#fff"/>
                                
                                <!-- Detailed Big Anime Eyes -->
                                <!-- Left Eye -->
                                <g>
                                    <ellipse cx="83" cy="92" rx="6" ry="8" fill="#334155"/>
                                    <circle cx="81" cy="89" r="2.5" fill="#ffffff"/>
                                    <circle cx="85.5" cy="95" r="1.2" fill="#ffffff"/>
                                    <!-- Eyelashes -->
                                    <path d="M 77 84 Q 83 82 89 85" fill="none" stroke="#334155" stroke-width="2" stroke-linecap="round"/>
                                </g>
                                <!-- Right Eye -->
                                <g>
                                    <ellipse cx="117" cy="92" rx="6" ry="8" fill="#334155"/>
                                    <circle cx="115" cy="89" r="2.5" fill="#ffffff"/>
                                    <circle cx="119.5" cy="95" r="1.2" fill="#ffffff"/>
                                    <!-- Eyelashes -->
                                    <path d="M 111 85 Q 117 82 123 84" fill="none" stroke="#334155" stroke-width="2" stroke-linecap="round"/>
                                </g>

                                <!-- Cute Nose & Smile -->
                                <ellipse cx="100" cy="100" rx="3" ry="2" fill="#ffb6c1"/>
                                <path d="M 95 104 Q 100 109 105 104" fill="none" stroke="#334155" stroke-width="2" stroke-linecap="round"/>

                                <!-- Rosy Cheeks -->
                                <ellipse cx="73" cy="101" rx="6" ry="3.5" fill="#ffb6c1" opacity="0.8"/>
                                <ellipse cx="127" cy="101" rx="6" ry="3.5" fill="#ffb6c1" opacity="0.8"/>
                                
                                <!-- Sparkles -->
                                <path d="M40 30 L 43 40 L 53 43 L 43 46 L 40 56 L 37 46 L 27 43 L 37 40 Z" fill="#7ab8ff"/>
                                <path d="M160 30 L 162 36 L 168 38 L 162 40 L 160 46 L 158 40 L 152 38 L 158 36 Z" fill="#7ab8ff"/>
                            </svg>
                            <span class="font-cute text-xs text-blue-500 font-semibold mt-1">✨ Example ✨</span>
                        </div>
                        <h3 class="font-cute font-bold text-gray-700 text-lg">Bunny with a Crown</h3>
                        <p class="text-xs text-gray-500 mt-1">Drew with love and care — and a little thank you!</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Art Gallery Section (Click to View Full Screen!) -->
        <section id="gallery" class="bg-white rounded-3xl p-6 md:p-10 border-4 border-blue-100 shadow-xl space-y-6">
            <div class="text-center space-y-2">
                <span class="bg-blue-100 text-blue-600 font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider">
                    🖼️ My Artwork Showcase
                </span>
                <h2 class="font-cute text-2xl md:text-3xl font-bold text-gray-700">Art Gallery</h2>
                <p class="text-sm text-gray-500 max-w-lg mx-auto">
                    Click on any image to view it in full screen! ✨
                </p>
            </div>

            <!-- Gallery Grid Slots -->
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
                <!-- Slot 1 -->
                <div class="bg-white border-2 border-blue-100 rounded-2xl overflow-hidden shadow-sm group hover:shadow-md transition flex flex-col">
                    <div class="h-48 overflow-hidden bg-blue-50 relative cursor-pointer" onclick="openImageModal('https://media.discordapp.net/attachments/1527528957568618580/1554732456505253888/Untitled228_Restored_20260927164720.png?backend=b2&ex=6abdf4ef&is=6abca36f&hm=6328416dd287cf1f6fd06148c5a20de875b1c390ba92d110b396386c1c1b8779&=&format=webp&quality=lossless&width=512&height=509')">
                        <img src="https://media.discordapp.net/attachments/1527528957568618580/1554732456505253888/Untitled228_Restored_20260927164720.png?backend=b2&ex=6abdf4ef&is=6abca36f&hm=6328416dd287cf1f6fd06148c5a20de875b1c390ba92d110b396386c1c1b8779&=&format=webp&quality=lossless&width=512&height=509">
                    </div>
                    <div class="p-4 bg-white flex flex-col justify-between flex-1">
                        <div>
                            <h4 class="font-cute font-bold text-gray-700 text-sm">Artwork Slot 1</h4>
                            <p class="text-xs text-gray-400 mt-0.5">✨ Commission Piece (Click to Expand)</p>
                        </div>
                    </div>
                </div>

                <!-- Slot 2 -->
                <div class="bg-white border-2 border-blue-100 rounded-2xl overflow-hidden shadow-sm group hover:shadow-md transition flex flex-col">
                    <div class="h-48 overflow-hidden bg-blue-50 relative cursor-pointer" onclick="openImageModal('https://media.discordapp.net/attachments/1527528957568618580/1554718564894642218/Untitled226_20260926144513.png?ex=6abde7ff&is=6abc967f&hm=4097defa5fc6a61a95d6cae03876a0ee000de52cbfab1ece17f6e9b2ba76aa48&=&format=webp&quality=lossless&width=512&height=512')">
                        <img src="https://media.discordapp.net/attachments/1527528957568618580/1554718564894642218/Untitled226_20260926144513.png?ex=6abde7ff&is=6abc967f&hm=4097defa5fc6a61a95d6cae03876a0ee000de52cbfab1ece17f6e9b2ba76aa48&=&format=webp&quality=lossless&width=512&height=512" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-4 bg-white flex flex-col justify-between flex-1">
                        <div>
                            <h4 class="font-cute font-bold text-gray-700 text-sm">Artwork Slot 2</h4>
                            <p class="text-xs text-gray-400 mt-0.5">✨ Commission Piece (Click to Expand)</p>
                        </div>
                    </div>
                </div>

                <!-- Slot 3 -->
                <div class="bg-white border-2 border-blue-100 rounded-2xl overflow-hidden shadow-sm group hover:shadow-md transition flex flex-col">
                    <div class="h-48 overflow-hidden bg-blue-50 relative cursor-pointer" onclick="openImageModal('https://media.discordapp.net/attachments/1527528957568618580/1554718565259677797/Untitled223_20260926114525.png?backend=b2&ex=6abde7ff&is=6abc967f&hm=7b8d61274c94d5c0c6bc599eaaae36c1e8c2c2b2f3155d6e8045f2c125324ba1&=&format=webp&quality=lossless&width=512&height=512')">
                        <img src="https://media.discordapp.net/attachments/1527528957568618580/1554718565259677797/Untitled223_20260926114525.png?backend=b2&ex=6abde7ff&is=6abc967f&hm=7b8d61274c94d5c0c6bc599eaaae36c1e8c2c2b2f3155d6e8045f2c125324ba1&=&format=webp&quality=lossless&width=512&height=512" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-4 bg-white flex flex-col justify-between flex-1">
                        <div>
                            <h4 class="font-cute font-bold text-gray-700 text-sm">Artwork Slot 3</h4>
                            <p class="text-xs text-gray-400 mt-0.5">✨ Commission Piece (Click to Expand)</p>
                        </div>
                    </div>
                </div>

                <!-- Slot 4 -->
                <div class="bg-white border-2 border-blue-100 rounded-2xl overflow-hidden shadow-sm group hover:shadow-md transition flex flex-col">
                    <div class="h-48 overflow-hidden bg-blue-50 relative cursor-pointer" onclick="openImageModal('https://media.discordapp.net/attachments/1527528957568618580/1554718566287147008/Untitled208_20260926032906.png?backend=b2&ex=6abde7ff&is=6abc967f&hm=31abe0155797b21f95ba0aaf6212eeab8cfc4e09e3f3acab072d8f941d93af3c&=&format=webp&quality=lossless&width=512&height=512')">
                        <img src="https://media.discordapp.net/attachments/1527528957568618580/1554718566287147008/Untitled208_20260926032906.png?backend=b2&ex=6abde7ff&is=6abc967f&hm=31abe0155797b21f95ba0aaf6212eeab8cfc4e09e3f3acab072d8f941d93af3c&=&format=webp&quality=lossless&width=512&height=512" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-4 bg-white flex flex-col justify-between flex-1">
                        <div>
                            <h4 class="font-cute font-bold text-gray-700 text-sm">Artwork Slot 4</h4>
                            <p class="text-xs text-gray-400 mt-0.5">✨ Commission Piece (Click to Expand)</p>
                        </div>
                    </div>
                </div>

                <!-- Slot 5 -->
                <div class="bg-white border-2 border-blue-100 rounded-2xl overflow-hidden shadow-sm group hover:shadow-md transition flex flex-col">
                    <div class="h-48 overflow-hidden bg-blue-50 relative cursor-pointer" onclick="openImageModal('https://media.discordapp.net/attachments/1527528957568618580/1554718568367784007/Untitled196.png?backend=b2&ex=6abde7ff&is=6abc967f&hm=ad09d685566f1ad710899cf84032d009ca03bc5183d6848a479ac5ef18ac807b&=&format=webp&quality=lossless&width=265&height=512')">
                        <img src="https://media.discordapp.net/attachments/1527528957568618580/1554718568367784007/Untitled196.png?backend=b2&ex=6abde7ff&is=6abc967f&hm=ad09d685566f1ad710899cf84032d009ca03bc5183d6848a479ac5ef18ac807b&=&format=webp&quality=lossless&width=265&height=512">
                    </div>
                    <div class="p-4 bg-white flex flex-col justify-between flex-1">
                        <div>
                            <h4 class="font-cute font-bold text-gray-700 text-sm">Artwork Slot 5</h4>
                            <p class="text-xs text-gray-400 mt-0.5">✨ Commission Piece (Click to Expand)</p>
                        </div>
                    </div>
                </div>

                <!-- Slot 6 -->
                <div class="bg-white border-2 border-blue-100 rounded-2xl overflow-hidden shadow-sm group hover:shadow-md transition flex flex-col">
                    <div class="h-48 overflow-hidden bg-blue-50 relative cursor-pointer" onclick="openImageModal('https://cdn.discordapp.com/attachments/1527528957568618580/1554725290532540427/image0.jpg?backend=b2&ex=6abdee42&is=6abc9cc2&hm=6cbe9a14f0e051d07cf14176892efc3df6128e3f08465a413b33a03867ae1c06&')">
                        <img src="https://cdn.discordapp.com/attachments/1527528957568618580/1554725290532540427/image0.jpg?backend=b2&ex=6abdee42&is=6abc9cc2&hm=6cbe9a14f0e051d07cf14176892efc3df6128e3f08465a413b33a03867ae1c06&" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-4 bg-white flex flex-col justify-between flex-1">
                        <div>
                            <h4 class="font-cute font-bold text-gray-700 text-sm">Artwork Slot 6</h4>
                            <p class="text-xs text-gray-400 mt-0.5">✨ Commission Piece (Click to Expand)</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="bg-blue-50/80 p-4 rounded-2xl border border-blue-100 text-center">
                <p class="text-xs text-blue-600 font-cute font-semibold">
                    💡 Send your images right here in chat whenever you're ready, and I will place them straight into this gallery for you! 🩵
                </p>
            </div>
        </section>

        <!-- Gemini AI Art Consultant Section -->
        <section id="ai-consultant" class="bg-gradient-to-br from-blue-50 via-white to-sky-50 rounded-3xl p-6 md:p-8 border-4 border-blue-200 shadow-xl">
            <div class="text-center space-y-2 mb-6">
                <span class="bg-blue-400 text-white font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider shadow">
                    ✨ Powered by Gemini AI 🤖
                </span>
                <h2 class="font-cute text-2xl md:text-3xl font-bold text-gray-700">AI Character & Pose Brainstormer</h2>
                <p class="text-sm text-gray-600 max-w-lg mx-auto">
                    Stuck on what to commission? Type a vague theme or keyword below and let Gemini design a cute concept for you!
                </p>
            </div>

            <div class="max-w-2xl mx-auto space-y-4">
                <div class="flex gap-2">
                    <input type="text" id="ai-prompt-input" placeholder="e.g., cyberpunk bunny hacker, magical baker cat..." class="flex-1 bg-white border-2 border-blue-200 rounded-2xl px-4 py-3 text-sm focus:outline-none focus:border-blue-400 shadow-sm">
                    <button onclick="generateAIConcept()" id="ai-submit-btn" class="bg-blue-500 hover:bg-blue-600 text-white font-cute px-6 py-3 rounded-2xl shadow transition flex items-center gap-2">
                        <i class="fa-solid fa-wand-magic-sparkles"></i> Brainstorm
                    </button>
                </div>

                <div id="ai-loading" class="hidden text-center py-6">
                    <div class="inline-block animate-spin rounded-full h-8 w-8 border-4 border-blue-400 border-t-transparent"></div>
                    <p class="font-cute text-xs text-blue-500 mt-2">Gemini is dreaming up something adorable... ☁️</p>
                </div>

                <div id="ai-result-card" class="hidden bg-white rounded-2xl p-6 border-2 border-blue-200 shadow-md space-y-4">
                    <div class="flex justify-between items-center border-b border-blue-100 pb-3">
                        <h4 class="font-cute font-bold text-blue-600 text-lg flex items-center gap-2">
                            <i class="fa-solid fa-star text-amber-400"></i> AI Concept Proposal
                        </h4>
                        <span id="ai-tier-tag" class="bg-blue-50 text-blue-600 font-cute text-xs px-3 py-1 rounded-full border border-blue-100">Medium Tier</span>
                    </div>
                    <div id="ai-result-text" class="text-sm text-gray-700 space-y-2 leading-relaxed font-body"></div>
                    <div class="pt-2 flex justify-end">
                        <button onclick="applyAIConceptToOrder()" class="bg-blue-400 hover:bg-blue-500 text-white font-cute text-xs px-4 py-2.5 rounded-xl shadow transition">
                            Use This in Order Form 📋
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pricing Tiers Section -->
        <section id="prices" class="space-y-6">
            <div class="text-center space-y-2">
                <span class="bg-blue-100 text-blue-600 font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider">
                    💰 Investment & Tiers
                </span>
                <h2 class="font-cute text-3xl font-bold text-gray-700">Commission Price Range</h2>
                <p class="text-sm text-gray-500 max-w-lg mx-auto">Prices may change depending on how detailed the request is. I'll always discuss the price with you before starting!</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Tier 1: Simple -->
                <div class="bg-white rounded-3xl p-6 border-2 border-blue-100 shadow-md hover:shadow-xl transition flex flex-col justify-between relative group">
                    <div class="absolute -top-3 left-6 bg-blue-100 text-blue-700 font-cute text-xs px-3 py-1 rounded-full border border-blue-200">
                        Starter 🩵
                    </div>
                    <div>
                        <div class="flex justify-between items-baseline mb-4 mt-2">
                            <h3 class="font-cute text-xl font-bold text-gray-700">Simple / Small</h3>
                            <span class="font-cute text-2xl font-extrabold text-blue-500">$4 – $7</span>
                        </div>
                        <ul class="space-y-2 text-sm text-gray-600 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Simple icon / chibi</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Headshots</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Simple expressions</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Simple sketches</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Small/simple characters</li>
                        </ul>
                    </div>
                    <a href="#order" onclick="selectTier('Simple / Small', '4-7')" class="block text-center bg-blue-50 hover:bg-blue-100 text-blue-600 font-cute text-sm py-2.5 rounded-xl transition">
                        Select Tier 🩵
                    </a>
                </div>

                <!-- Tier 2: Medium -->
                <div class="bg-white rounded-3xl p-6 border-4 border-blue-200 shadow-lg hover:shadow-2xl transition flex flex-col justify-between relative group transform md:-translate-y-2">
                    <div class="absolute -top-3 left-6 bg-blue-400 text-white font-cute text-xs px-3 py-1 rounded-full shadow">
                        Most Popular ✨
                    </div>
                    <div>
                        <div class="flex justify-between items-baseline mb-4 mt-2">
                            <h3 class="font-cute text-xl font-bold text-gray-700">Medium</h3>
                            <span class="font-cute text-2xl font-extrabold text-blue-500">$8 – $13</span>
                        </div>
                        <ul class="space-y-2 text-sm text-gray-600 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-400 text-xs"></i> Half-body art</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-400 text-xs"></i> More detailed characters</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-400 text-xs"></i> More complicated outfits</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-400 text-xs"></i> Simple backgrounds</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-400 text-xs"></i> Extra details & styling</li>
                        </ul>
                    </div>
                    <a href="#order" onclick="selectTier('Medium', '8-13')" class="block text-center bg-blue-400 hover:bg-blue-500 text-white font-cute text-sm py-2.5 rounded-xl shadow transition">
                        Select Tier 🩵
                    </a>
                </div>

                <!-- Tier 3: Full / Detailed -->
                <div class="bg-white rounded-3xl p-6 border-2 border-blue-100 shadow-md hover:shadow-xl transition flex flex-col justify-between relative group">
                    <div class="absolute -top-3 left-6 bg-sky-100 text-sky-700 font-cute text-xs px-3 py-1 rounded-full border border-sky-200">
                        Masterpiece ☁️
                    </div>
                    <div>
                        <div class="flex justify-between items-baseline mb-4 mt-2">
                            <h3 class="font-cute text-xl font-bold text-gray-700">Full / Detailed</h3>
                            <span class="font-cute text-2xl font-extrabold text-blue-500">$14 – $20+</span>
                        </div>
                        <ul class="space-y-2 text-sm text-gray-600 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Full-body characters</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Detailed outfits</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> More complex poses</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Detailed backgrounds</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-star text-blue-300 text-xs"></i> Multiple characters</li>
                        </ul>
                    </div>
                    <a href="#order" onclick="selectTier('Full / Detailed', '14-20+')" class="block text-center bg-blue-50 hover:bg-blue-100 text-blue-600 font-cute text-sm py-2.5 rounded-xl transition">
                        Select Tier 🩵
                    </a>
                </div>
            </div>

            <!-- Custom Banner -->
            <div class="bg-gradient-to-r from-blue-50 via-sky-50 to-white border-2 border-dashed border-blue-200 rounded-3xl p-6 flex flex-col md:flex-row items-center justify-between gap-4">
                <div class="flex items-center gap-4">
                    <div class="w-12 h-12 rounded-2xl bg-white flex items-center justify-center text-blue-400 text-2xl shadow-sm">
                        <i class="fa-solid fa-wand-magic-sparkles"></i>
                    </div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700 text-lg">Custom Commissions</h4>
                        <p class="text-sm text-gray-600">Starting at <strong class="text-blue-500">$20+</strong> depending on complexity and special requests!</p>
                    </div>
                </div>
                <a href="#calculator" class="bg-white hover:bg-blue-50 text-blue-600 border border-blue-200 font-cute text-sm px-5 py-2.5 rounded-xl shadow-sm transition">
                    Open Calculator 🧮
                </a>
            </div>
        </section>

        <!-- Interactive Quote Calculator -->
        <section id="calculator" class="bg-white rounded-3xl p-6 md:p-8 border-4 border-blue-100 shadow-lg">
            <div class="text-center space-y-2 mb-8">
                <span class="bg-blue-100 text-blue-600 font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider">
                    🧮 Interactive Estimator
                </span>
                <h2 class="font-cute text-2xl md:text-3xl font-bold text-gray-700">Commission Price Calculator</h2>
                <p class="text-sm text-gray-500">Configure your dream piece to estimate the cost instantly!</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Calculator Controls -->
                <div class="space-y-6">
                    <div>
                        <label class="block font-cute font-semibold text-gray-700 mb-2">1. Choose Commission Type:</label>
                        <select id="calc-type" onchange="calculateQuote()" class="w-full bg-blue-50/50 border border-blue-200 rounded-2xl p-3 text-sm font-medium text-gray-700 focus:outline-none focus:border-blue-400">
                            <option value="5">Simple / Small ($4 - $7) [Avg: $5]</option>
                            <option value="10" selected>Medium ($8 - $13) [Avg: $10]</option>
                            <option value="17">Full / Detailed ($14 - $20) [Avg: $17]</option>
                            <option value="25">Complex / Custom ($20+) [Avg: $25]</option>
                        </select>
                    </div>

                    <div>
                        <label class="block font-cute font-semibold text-gray-700 mb-2">2. Additional Characters:</label>
                        <select id="calc-extra-chars" onchange="calculateQuote()" class="w-full bg-blue-50/50 border border-blue-200 rounded-2xl p-3 text-sm font-medium text-gray-700 focus:outline-none focus:border-blue-400">
                            <option value="0">Single Character (0 extra)</option>
                            <option value="6">+1 Extra Character (+$6)</option>
                            <option value="12">+2 Extra Characters (+$12)</option>
                        </select>
                    </div>

                    <div>
                        <label class="block font-cute font-semibold text-gray-700 mb-2">3. Background Style:</label>
                        <select id="calc-bg" onchange="calculateQuote()" class="w-full bg-blue-50/50 border border-blue-200 rounded-2xl p-3 text-sm font-medium text-gray-700 focus:outline-none focus:border-blue-400">
                            <option value="0">Simple / Transparent / Solid (Free)</option>
                            <option value="4">Simple Scene / Pattern (+$4)</option>
                            <option value="8">Detailed Background / Props (+$8)</option>
                        </select>
                    </div>
                </div>

                <!-- Calculator Result Panel -->
                <div class="bg-gradient-to-br from-blue-50/80 to-sky-50/80 rounded-3xl p-6 border-2 border-blue-100 flex flex-col justify-between text-center">
                    <div>
                        <span class="inline-block bg-white text-blue-500 font-cute text-xs px-3 py-1 rounded-full shadow-sm mb-3">
                            ✨ Estimated Investment ✨
                        </span>
                        <div class="font-cute text-4xl md:text-5xl font-extrabold text-blue-600 my-4" id="calc-total">
                            $10 – $14
                        </div>
                        <p class="text-xs text-gray-500 max-w-xs mx-auto">
                            This is an automated estimate. Final pricing will be confirmed before work begins!
                        </p>
                    </div>
                    <div class="pt-6">
                        <button onclick="transferQuoteToOrder()" class="w-full bg-blue-400 hover:bg-blue-500 text-white font-cute py-3 rounded-2xl shadow-md transition">
                            Use This in Order Form 📋
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- What I Can & Can't Draw Section -->
        <section id="dos-donts" class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- What I Can Draw -->
            <div class="bg-white rounded-3xl p-6 md:p-8 border-2 border-blue-100 shadow-md">
                <div class="flex items-center gap-3 mb-6">
                    <div class="w-10 h-10 rounded-2xl bg-blue-50 text-blue-500 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-palette"></i>
                    </div>
                    <div>
                        <h3 class="font-cute text-xl font-bold text-gray-700">What I Can Draw</h3>
                        <p class="text-xs text-gray-500">My specialties & favorite subjects</p>
                    </div>
                </div>
                <ul class="space-y-3 text-sm text-gray-600">
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Original Characters (OCs)
                    </li>
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Anime-inspired characters
                    </li>
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Chibi / Moe characters
                    </li>
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Fanart
                    </li>
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Cute character art & Icons / PFP
                    </li>
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Simple scenes & Character references
                    </li>
                    <li class="flex items-center gap-3 bg-blue-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-star text-blue-400"></i> Different art styles upon request
                    </li>
                </ul>
                <p class="text-xs text-gray-500 mt-4 italic bg-blue-50 p-3 rounded-xl border border-blue-100">
                    💡 I'm a very flexible artist, so don't be afraid to ask about an idea even if it doesn't perfectly fit my usual style!
                </p>
            </div>

            <!-- What I DON'T Draw -->
            <div class="bg-white rounded-3xl p-6 md:p-8 border-2 border-red-100 shadow-md">
                <div class="flex items-center gap-3 mb-6">
                    <div class="w-10 h-10 rounded-2xl bg-red-50 text-red-500 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-ban"></i>
                    </div>
                    <div>
                        <h3 class="font-cute text-xl font-bold text-gray-700">What I DON'T Draw</h3>
                        <p class="text-xs text-gray-500">Strict boundaries & limitations</p>
                    </div>
                </div>
                <ul class="space-y-3 text-sm text-gray-600">
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> Gore / extreme violence
                    </li>
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> CP or any sexual content involving minors
                    </li>
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> Sexual or explicit content (NSFW)
                    </li>
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> Hate or discriminatory artwork
                    </li>
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> Racist, homophobic, transphobic, or hateful content
                    </li>
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> Artwork intended to harass or target someone
                    </li>
                    <li class="flex items-center gap-3 bg-red-50/50 p-2.5 rounded-xl">
                        <i class="fa-solid fa-xmark text-red-400"></i> Anything I personally feel uncomfortable drawing
                    </li>
                </ul>
                <p class="text-xs text-gray-500 mt-4 italic bg-red-50 p-3 rounded-xl border border-red-100">
                    ⚠️ If you're unsure whether your idea is okay, DM me and ask first!
                </p>
            </div>
        </section>

        <!-- Commission Rules Section -->
        <section id="rules" class="bg-white rounded-3xl p-6 md:p-10 border-4 border-blue-100 shadow-lg">
            <div class="text-center space-y-2 mb-8">
                <span class="bg-blue-100 text-blue-600 font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider">
                    📌 Guidelines
                </span>
                <h2 class="font-cute text-2xl md:text-3xl font-bold text-gray-700">Commission Rules</h2>
                <p class="text-sm text-gray-500">Please review these friendly guidelines before commissioning!</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="flex gap-4 p-4 rounded-2xl bg-blue-50/40 border border-blue-100">
                    <div class="text-blue-400 text-xl font-bold mt-0.5">🩵</div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700">Clear Explanation</h4>
                        <p class="text-sm text-gray-600 mt-1">Please explain what you want clearly so I can bring your vision to life accurately.</p>
                    </div>
                </div>

                <div class="flex gap-4 p-4 rounded-2xl bg-blue-50/40 border border-blue-100">
                    <div class="text-blue-400 text-xl font-bold mt-0.5">🩵</div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700">References Welcome</h4>
                        <p class="text-sm text-gray-600 mt-1">I may ask for visual references or mood boards if needed during our chat.</p>
                    </div>
                </div>

                <div class="flex gap-4 p-4 rounded-2xl bg-blue-50/40 border border-blue-100">
                    <div class="text-blue-400 text-xl font-bold mt-0.5">🩵</div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700">Payment & Pricing</h4>
                        <p class="text-sm text-gray-600 mt-1">Payment and pricing will always be discussed and agreed upon before I begin drawing.</p>
                    </div>
                </div>

                <div class="flex gap-4 p-4 rounded-2xl bg-blue-50/40 border border-blue-100">
                    <div class="text-blue-400 text-xl font-bold mt-0.5">🩵</div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700">Patience is Appreciated</h4>
                        <p class="text-sm text-gray-600 mt-1">Please don't rush me—art takes time to craft with care and sweetness!</p>
                    </div>
                </div>

                <div class="flex gap-4 p-4 rounded-2xl bg-blue-50/40 border border-blue-100">
                    <div class="text-blue-400 text-xl font-bold mt-0.5">🩵</div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700">Major Changes</h4>
                        <p class="text-sm text-gray-600 mt-1">Major changes requested after I've already started sketching may cost extra.</p>
                    </div>
                </div>

                <div class="flex gap-4 p-4 rounded-2xl bg-blue-50/40 border border-blue-100">
                    <div class="text-blue-400 text-xl font-bold mt-0.5">🩵</div>
                    <div>
                        <h4 class="font-cute font-bold text-gray-700">Right to Refuse</h4>
                        <p class="text-sm text-gray-600 mt-1">I can refuse a commission if I don't feel comfortable with the request.</p>
                    </div>
                </div>
            </div>

            <div class="mt-6 p-4 rounded-2xl bg-blue-50/60 border border-blue-100 text-center">
                <p class="font-cute text-sm text-blue-700 font-semibold">
                    🩵 Please be respectful when communicating with me. Kindness makes creating art so much more fun! 🩵
                </p>
            </div>
        </section>

        <!-- Socials Section -->
        <section id="socials" class="bg-gradient-to-r from-blue-50 via-sky-50 to-white rounded-3xl p-6 md:p-8 border-4 border-white shadow-xl text-center space-y-4">
            <span class="bg-blue-400 text-white font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider shadow">
                ✨ Connect With Me ✨
            </span>
            <h2 class="font-cute text-2xl md:text-3xl font-bold text-gray-700">My Socials & Contact</h2>
            <p class="text-sm text-gray-600 max-w-md mx-auto">
                Follow my art journey on TikTok or send inquiries directly to my email!
            </p>
            <div class="flex flex-wrap justify-center gap-4 pt-2">
                <a href="https://www.tiktok.com/@yoko.arts?_r=1&_t=ZP-9A9WuhRu0AZ" target="_blank" class="bg-white hover:bg-blue-50 text-blue-600 border-2 border-blue-200 font-cute text-sm px-6 py-3 rounded-2xl shadow-sm transition flex items-center gap-2">
                    <i class="fa-brands fa-tiktok text-lg text-blue-500"></i> TikTok (@yoko.arts)
                </a>
                <a href="mailto:hiiikitty12@gmail.com" class="bg-white hover:bg-blue-50 text-blue-600 border-2 border-blue-200 font-cute text-sm px-6 py-3 rounded-2xl shadow-sm transition flex items-center gap-2">
                    <i class="fa-solid fa-envelope text-lg text-blue-500"></i> Email (hiiikitty12@gmail.com)
                </a>
            </div>
        </section>

        <!-- How to Order & Template Generator -->
        <section id="order" class="bg-gradient-to-br from-blue-50 to-sky-50 rounded-3xl p-6 md:p-10 border-4 border-white shadow-xl">
            <div class="text-center space-y-2 mb-8">
                <span class="bg-blue-400 text-white font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider shadow">
                    💌 Interested?
                </span>
                <h2 class="font-cute text-2xl md:text-3xl font-bold text-gray-700">Send Your Commission Request!</h2>
                <p class="text-sm text-gray-600 max-w-lg mx-auto">
                    Fill in your details below. You can copy the message to clipboard or send it directly to my email <strong>hiiikitty12@gmail.com</strong>!
                </p>
            </div>

            <!-- Template Generator Form -->
            <div class="bg-white rounded-3xl p-6 md:p-8 border-2 border-blue-100 shadow-md max-w-2xl mx-auto space-y-4">
                <h3 class="font-cute font-bold text-gray-700 text-lg flex items-center gap-2">
                    <i class="fa-solid fa-wand-magic text-blue-400"></i> Commission Request Template
                </h3>
                <p class="text-xs text-gray-500">Fill in your details and submit to complete your order!</p>
                
                <div class="space-y-3">
                    <div>
                        <label class="block text-xs font-cute font-semibold text-gray-600 mb-1">Your Name / Handle:</label>
                        <input type="text" id="tpl-name" placeholder="e.g. KittyFan99" class="w-full bg-gray-50 border border-gray-200 rounded-xl p-2.5 text-sm focus:outline-none focus:border-blue-400">
                    </div>
                    <div>
                        <label class="block text-xs font-cute font-semibold text-gray-600 mb-1">Commission Type / Tier:</label>
                        <input type="text" id="tpl-tier" value="Medium ($8-$13)" class="w-full bg-gray-50 border border-gray-200 rounded-xl p-2.5 text-sm focus:outline-none focus:border-blue-400">
                    </div>
                    <div>
                        <label class="block text-xs font-cute font-semibold text-gray-600 mb-1">Character Description & References:</label>
                        <textarea id="tpl-desc" rows="3" class="w-full bg-gray-50 border border-gray-200 rounded-xl p-2.5 text-sm focus:outline-none focus:border-blue-400" placeholder="Describe your OC, pose, mood, clothing, or paste reference links here..."></textarea>
                    </div>
                    <div>
                        <label class="block text-xs font-cute font-semibold text-gray-600 mb-1">Background / Extras:</label>
                        <input type="text" id="tpl-bg" value="Simple colored background with cute stars" class="w-full bg-gray-50 border border-gray-200 rounded-xl p-2.5 text-sm focus:outline-none focus:border-blue-400">
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-cute font-semibold text-gray-600 mb-1">Generated Message Preview:</label>
                    <div id="tpl-output" class="bg-blue-50/50 p-4 rounded-2xl border border-blue-100 text-xs text-gray-700 font-mono whitespace-pre-wrap">
Hi Yoko! I'd love to commission a Medium ($8-$13) piece!
- From: KittyFan99
- Character details: [Describe your character/idea here]
- Background / Extras: Simple colored background with cute stars
- References attached: [Will send in DM/Email]
Thank you so much! 🩵</div>
                </div>

                <div class="pt-2 flex flex-col sm:flex-row gap-3">
                    <button onclick="submitOrderEmail()" class="flex-1 bg-blue-500 hover:bg-blue-600 text-white font-cute text-sm py-3 rounded-xl shadow transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-paper-plane"></i> Send to hiiikitty12@gmail.com 💌
                    </button>
                    <button onclick="copyTemplate()" class="bg-blue-100 hover:bg-blue-200 text-blue-700 font-cute text-xs px-4 py-3 rounded-xl transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-copy"></i> Copy Message
                    </button>
                </div>
                <div id="copy-feedback" class="hidden text-center text-xs font-cute text-green-600 font-semibold">
                    Copied to clipboard successfully! ✨
                </div>
            </div>

            <!-- Closing Thank You -->
            <div class="text-center mt-8 space-y-2">
                <p class="font-cute text-lg text-blue-600 font-bold">
                    ♡ Thank you for supporting my art! ♡
                </p>
                <p class="text-xs text-gray-500">Made with ☁️️ bunny magic and baby blue vibes.</p>
            </div>
        </section>

    </main>

    <!-- FULL-SCREEN IMAGE MODAL OVERLAY -->
    <div id="image-modal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-md hidden flex items-center justify-center p-4 cursor-pointer" onclick="closeImageModal()">
        <div class="relative max-w-4xl max-h-full flex items-center justify-center" onclick="event.stopPropagation()">
            <button onclick="closeImageModal()" class="absolute -top-12 right-0 text-white hover:text-blue-300 text-2xl w-10 h-10 rounded-full bg-black/50 flex items-center justify-center transition">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <img id="modal-image-view" src="" alt="Full Screen View" class="max-w-full max-h-[85vh] object-contain rounded-2xl shadow-2xl border-2 border-white/20">
        </div>
    </div>

    <!-- SUCCESS MODAL OVERLAY -->
    <div id="success-modal" class="fixed inset-0 z-50 bg-black/50 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl p-8 max-w-md w-full border-4 border-blue-200 shadow-2xl text-center space-y-6 transform animate-bounce-short">
            <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mx-auto text-blue-500 text-4xl shadow-inner">
                <i class="fa-solid fa-heart-circle-check"></i>
            </div>
            <div class="space-y-2">
                <h2 class="font-cute text-3xl font-bold text-gray-800">YOUR ALL SET! 🎉</h2>
                <p class="text-sm text-gray-600">
                    Your order message has been prepared and your email app has opened to <strong>hiiikitty12@gmail.com</strong>!
                </p>
            </div>
            <div class="bg-blue-50 p-4 rounded-2xl border border-blue-100 text-xs text-gray-500">
                ✨ Yoko will review your request and get back to you soon!
            </div>
            <div class="flex flex-col gap-3 pt-2">
                <button onclick="openMiniGame()" class="bg-blue-400 hover:bg-blue-500 text-white font-cute py-3 rounded-2xl shadow transition flex items-center justify-center gap-2">
                    <i class="fa-solid fa-gamepad"></i> Play Cute Bunny Mini-Game 🎮
                </button>
                <button onclick="closeSuccessModal()" class="bg-gray-100 hover:bg-gray-200 text-gray-700 font-cute py-3 rounded-2xl transition">
                    Back to Home Page ☁️
                </button>
            </div>
        </div>
    </div>

    <!-- MINI-GAME MODAL -->
    <div id="game-modal" class="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl p-6 md:p-8 max-w-lg w-full border-4 border-blue-200 shadow-2xl text-center space-y-4 relative">
            <button onclick="closeMiniGame()" class="absolute top-4 right-4 text-gray-400 hover:text-gray-600 text-xl w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div>
                <span class="bg-blue-100 text-blue-600 font-cute text-xs px-3 py-1 rounded-full uppercase tracking-wider">
                    🎮 Catch the Stars!
                </span>
                <h3 class="font-cute text-2xl font-bold text-gray-700 mt-1">Bunny Star Catcher</h3>
                <p class="text-xs text-gray-500">Move the bunny using arrow keys or buttons to catch baby blue stars!</p>
            </div>

            <!-- Game Canvas Container -->
            <div class="relative bg-gradient-to-b from-blue-50 to-sky-100 rounded-2xl overflow-hidden border-2 border-blue-200 shadow-inner h-64">
                <canvas id="gameCanvas" width="400" height="250" class="w-full h-full block cursor-pointer"></canvas>
                <div id="game-score-board" class="absolute top-3 left-3 bg-white/80 backdrop-blur px-3 py-1 rounded-full font-cute text-xs font-bold text-blue-600 shadow-sm">
                    Score: <span id="score-val">0</span>
                </div>
                <div id="game-over-screen" class="absolute inset-0 bg-white/90 backdrop-blur flex flex-col items-center justify-center space-y-3 hidden">
                    <h4 class="font-cute text-2xl font-bold text-blue-600">Great Job! ✨</h4>
                    <p class="text-sm text-gray-600" id="final-score-text">You caught 0 stars!</p>
                    <button onclick="restartGame()" class="bg-blue-400 hover:bg-blue-500 text-white font-cute px-6 py-2 rounded-xl shadow">
                        Play Again 🩵
                    </button>
                </div>
            </div>

            <!-- Mobile Controls -->
            <div class="flex justify-center gap-4 pt-2">
                <button onclick="moveBunnyLeft()" class="bg-blue-100 hover:bg-blue-200 text-blue-700 font-cute px-6 py-2.5 rounded-xl shadow active:scale-95 transition">
                    <i class="fa-solid fa-arrow-left"></i> Left
                </button>
                <button onclick="moveBunnyRight()" class="bg-blue-100 hover:bg-blue-200 text-blue-700 font-cute px-6 py-2.5 rounded-xl shadow active:scale-95 transition">
                    Right <i class="fa-solid fa-arrow-right"></i>
                </button>
            </div>

            <div class="pt-2">
                <button onclick="closeMiniGame()" class="text-xs text-gray-500 hover:text-blue-500 underline font-cute">
                    Return to Home Page
                </button>
            </div>
        </div>
    </div>

    <!-- JavaScript for Interactivity -->
    <script>
        // Full-screen image viewer functions
        function openImageModal(imgSrc) {
            const modal = document.getElementById('image-modal');
            const modalImg = document.getElementById('modal-image-view');
            modalImg.src = imgSrc;
            modal.classList.remove('hidden');
        }

        function closeImageModal() {
            const modal = document.getElementById('image-modal');
            modal.classList.add('hidden');
        }

        function calculateQuote() {
            const typeVal = parseInt(document.getElementById('calc-type').value);
            const extraCharsVal = parseInt(document.getElementById('calc-extra-chars').value);
            const bgVal = parseInt(document.getElementById('calc-bg').value);

            const baseTotal = typeVal + extraCharsVal + bgVal;
            const lowRange = baseTotal;
            const highRange = baseTotal + 4;

            document.getElementById('calc-total').innerText = `$${lowRange} – $${highRange}`;
            updateTemplateText();
        }

        function selectTier(tierName, priceRange) {
            const selectEl = document.getElementById('calc-type');
            for(let i=0; i<selectEl.options.length; i++) {
                if(selectEl.options[i].text.includes(tierName)) {
                    selectEl.selectedIndex = i;
                    break;
                }
            }
            calculateQuote();
        }

        function transferQuoteToOrder() {
            const selectEl = document.getElementById('calc-type');
            const selectedOptionText = selectEl.options[selectEl.selectedIndex].text.split(' ')[0];
            const tierText = selectedOptionText + ' (' + document.getElementById('calc-total').innerText + ')';
            document.getElementById('tpl-tier').value = tierText;
            updateTemplateText();
            document.getElementById('order').scrollIntoView({ behavior: 'smooth' });
        }

        function updateTemplateText() {
            const name = document.getElementById('tpl-name').value || 'Anonymous';
            const tier = document.getElementById('tpl-tier').value;
            const desc = document.getElementById('tpl-desc').value || '[Describe your character/idea here]';
            const bg = document.getElementById('tpl-bg').value;

            const message = `Hi Yoko! I'd love to commission a ${tier} piece!\n- From: ${name}\n- Character details: ${desc}\n- Background / Extras: ${bg}\n- References attached: [Will send in DM/Email]\nThank you so much! 🩵`;
            document.getElementById('tpl-output').innerText = message;
        }

        document.getElementById('tpl-name').addEventListener('input', updateTemplateText);
        document.getElementById('tpl-tier').addEventListener('input', updateTemplateText);
        document.getElementById('tpl-desc').addEventListener('input', updateTemplateText);
        document.getElementById('tpl-bg').addEventListener('input', updateTemplateText);

        function copyTemplate() {
            const textToCopy = document.getElementById('tpl-output').innerText;
            const textarea = document.createElement('textarea');
            textarea.value = textToCopy;
            document.body.appendChild(textarea);
            textarea.select();
            try {
                document.execCommand('copy');
                const feedback = document.getElementById('copy-feedback');
                feedback.classList.remove('hidden');
                setTimeout(() => {
                    feedback.classList.add('hidden');
                }, 3000);
            } catch (err) {
                // fallback
            }
            document.body.removeChild(textarea);
        }

        function submitOrderEmail() {
            const message = encodeURIComponent(document.getElementById('tpl-output').innerText);
            const email = "hiiikitty12@gmail.com";
            const subject = encodeURIComponent("New YokoArts Commission Request!");
            
            window.location.href = `mailto:${email}?subject=${subject}&body=${message}`;
            document.getElementById('success-modal').classList.remove('hidden');
        }

        function closeSuccessModal() {
            document.getElementById('success-modal').classList.add('hidden');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function openMiniGame() {
            document.getElementById('success-modal').classList.add('hidden');
            document.getElementById('game-modal').classList.remove('hidden');
            initGame();
        }

        function closeMiniGame() {
            document.getElementById('game-modal').classList.add('hidden');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        let canvas, ctx;
        let bunnyX = 180;
        let bunnyY = 190;
        let bunnyWidth = 40;
        let bunnyHeight = 35;
        let score = 0;
        let gameRunning = false;
        let stars = [];
        let gameInterval, starInterval;

        function initGame() {
            canvas = document.getElementById('gameCanvas');
            ctx = canvas.getContext('2d');
            score = 0;
            stars = [];
            bunnyX = 180;
            document.getElementById('score-val').innerText = score;
            document.getElementById('game-over-screen').classList.add('hidden');
            gameRunning = true;

            if (gameInterval) clearInterval(gameInterval);
            if (starInterval) clearInterval(starInterval);

            gameInterval = setInterval(updateGame, 30);
            starInterval = setInterval(spawnStar, 900);

            window.addEventListener('keydown', handleKeyPress);
        }

        function spawnStar() {
            if (!gameRunning) return;
            const x = Math.random() * (canvas.width - 30);
            stars.push({ x: x, y: 0, speed: 2 + Math.random() * 2 });
        }

        function moveBunnyLeft() {
            bunnyX = Math.max(0, bunnyX - 25);
        }

        function moveBunnyRight() {
            bunnyX = Math.min(canvas.width - bunnyWidth, bunnyX + 25);
        }

        function handleKeyPress(e) {
            if (!gameRunning) return;
            if (e.key === 'ArrowLeft') moveBunnyLeft();
            if (e.key === 'ArrowRight') moveBunnyRight();
        }

        function updateGame() {
            if (!gameRunning) return;

            ctx.clearRect(0, 0, canvas.width, canvas.height);

            ctx.fillStyle = '#ffffff';
            ctx.strokeStyle = '#7ab8ff';
            ctx.lineWidth = 2;
            ctx.beginPath();
            ctx.ellipse(bunnyX + 12, bunnyY - 12, 5, 12, 0, 0, Math.PI * 2);
            ctx.ellipse(bunnyX + 28, bunnyY - 12, 5, 12, 0, 0, Math.PI * 2);
            ctx.fill();
            ctx.stroke();

            ctx.beginPath();
            ctx.arc(bunnyX + 20, bunnyY + 12, 18, 0, Math.PI * 2);
            ctx.fill();
            ctx.stroke();

            ctx.fillStyle = '#333';
            ctx.fillRect(bunnyX + 14, bunnyY + 10, 3, 3);
            ctx.fillRect(bunnyX + 23, bunnyY + 10, 3, 3);

            for (let i = stars.length - 1; i >= 0; i--) {
                let s = stars[i];
                s.y += s.speed;

                ctx.fillStyle = '#7ab8ff';
                ctx.beginPath();
                ctx.arc(s.x + 10, s.y + 10, 10, 0, Math.PI * 2);
                ctx.fill();
                ctx.fillStyle = '#ffffff';
                ctx.font = '10px sans-serif';
                ctx.fillText('★', s.x + 5, s.y + 14);

                if (
                    s.y + 20 >= bunnyY &&
                    s.y <= bunnyY + bunnyHeight &&
                    s.x + 20 >= bunnyX &&
                    s.x <= bunnyX + bunnyWidth
                ) {
                    score++;
                    document.getElementById('score-val').innerText = score;
                    stars.splice(i, 1);
                    if (score >= 15) {
                        endGame();
                    }
                    continue;
                }

                if (s.y > canvas.height) {
                    stars.splice(i, 1);
                }
            }
        }

        function endGame() {
            gameRunning = false;
            clearInterval(gameInterval);
            clearInterval(starInterval);
            document.getElementById('final-score-text').innerText = `You caught ${score} stars! Wonderful job! 🩵`;
            document.getElementById('game-over-screen').classList.remove('hidden');
        }

        function restartGame() {
            initGame();
        }

        async function generateAIConcept() {
            const promptInput = document.getElementById('ai-prompt-input').value.trim();
            if (!promptInput) {
                return;
            }

            const loadingEl = document.getElementById('ai-loading');
            const resultCard = document.getElementById('ai-result-card');
            const submitBtn = document.getElementById('ai-submit-btn');

            loadingEl.classList.remove('hidden');
            resultCard.classList.add('hidden');
            submitBtn.disabled = true;

            const systemPrompt = "You are a creative, sweet assistant for a kawaii anime artist named Yoko. Given a user theme, generate a detailed custom character commission concept including: 1) Character design details, 2) Cute pose/expression, 3) Suggested background/props, and 4) Recommended commission tier. Keep tone cute with emojis.";
            const userQuery = `Brainstorm a kawaii commission concept for: ${promptInput}`;

            const apiKey = "";
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-3-flash-preview:generateContent?key=${apiKey}`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] }
            };

            try {
                let response = null;
                let attempts = 0;
                while (attempts < 3) {
                    try {
                        response = await fetch(apiUrl, {
                            method: 'POST',
                            headers: { 'Content-Type': 'application/json' },
                            body: JSON.stringify(payload)
                        });
                        if (response.ok) break;
                    } catch (e) {}
                    attempts++;
                    await new Promise(r => setTimeout(r, attempts * 1000));
                }

                if (!response || !response.ok) {
                    throw new Error('Failed to reach Gemini API');
                }

                const result = await response.json();
                const candidate = result.candidates?.[0];
                if (candidate && candidate.content?.parts?.[0]?.text) {
                    const text = candidate.content.parts[0].text;
                    document.getElementById('ai-result-text').innerText = text;
                    resultCard.classList.remove('hidden');
                }
            } catch (error) {
                // handle error silently or show fallback
            } finally {
                loadingEl.classList.add('hidden');
                submitBtn.disabled = false;
            }
        }

        function applyAIConceptToOrder() {
            const conceptText = document.getElementById('ai-result-text').innerText;
            document.getElementById('tpl-desc').value = conceptText;
            updateTemplateText();
            document.getElementById('order').scrollIntoView({ behavior: 'smooth' });
        }

        calculateQuote();
    </script>
</body>
</html>
