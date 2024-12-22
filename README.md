<!DOCTYPE html>
<html lang="si">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>හෙළ බෝ - Hela Bo</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.9.1/gsap.min.js"></script>
</head>
<!-- Rest of the code remains exactly the same as before -->
<body class="bg-gradient-to-br from-green-50 to-white min-h-screen">
    <!-- Navigation -->
    <nav class="fixed w-full bg-white/80 backdrop-blur-md shadow-sm z-50">
        <div class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="text-2xl font-bold text-green-600">හෙළ බෝ</div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-600 hover:text-green-600 transition-colors">මුල් පිටුව</a>
                    <a href="#benefits" class="text-gray-600 hover:text-green-600 transition-colors">වාසි</a>
                    <a href="#services" class="text-gray-600 hover:text-green-600 transition-colors">සේවා</a>
                    <a href="#contact" class="text-gray-600 hover:text-green-600 transition-colors">සම්බන්ධ වන්න</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-32 pb-20">
        <div class="container mx-auto px-6">
            <div class="text-center">
                <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">
                    <span class="text-green-600">හෙළ බෝ..</span>
                </h1>
                <p class="text-xl md:text-2xl text-gray-600 mb-8">ගොවියා සහ පරිභෝගිකයා අතර සෘජු සම්බන්ධය!</p>
                <div class="flex flex-col md:flex-row justify-center gap-4">
                    <button class="bg-green-600 text-white px-8 py-3 rounded-lg hover:bg-green-700 transition-colors">
                        අපි සමඟ එක්වන්න
                    </button>
                    <button class="border-2 border-green-600 text-green-600 px-8 py-3 rounded-lg hover:bg-green-50 transition-colors">
                        තවත් දැනගන්න
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section id="benefits" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16">ඔබට හෙළ බෝ.. වෙතින් ලැබෙන වාසිය</h2>
            <div class="grid md:grid-cols-2 gap-12">
                <!-- Farmers Benefits -->
                <div class="space-y-8">
                    <h3 class="text-2xl font-semibold text-green-600 mb-6">ගොවීන් සඳහා</h3>
                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center flex-shrink-0">
                                <span class="text-green-600 text-xl">🌾</span>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">සෘජු වෙළඳපොළක්</h4>
                                <p class="text-gray-600">ඔබේ නිෂ්පාදන අන් අය හමුවට ගෙන යාමට පහසුකම්.</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center flex-shrink-0">
                                <span class="text-green-600 text-xl">💰</span>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">ඉහළ ආදායමක්</h4>
                                <p class="text-gray-600">මැදිස්ථයන් නැතිව ආදායම උපයන්න.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Consumers Benefits -->
                <div class="space-y-8">
                    <h3 class="text-2xl font-semibold text-green-600 mb-6">පරිභෝගිකයින් සඳහා</h3>
                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center flex-shrink-0">
                                <span class="text-green-600 text-xl">🥬</span>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">නව තත්වයේ භාණ්ඩ</h4>
                                <p class="text-gray-600">ගොවියාගෙන්ම මිලදී ගන්න.</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center flex-shrink-0">
                                <span class="text-green-600 text-xl">✨</span>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">පිරිසිදු හා විශ්වාසනීයභාවය</h4>
                                <p class="text-gray-600">තත්ත්ව සහිත කෘෂි භාණ්ඩ.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16">අපි කරන දේ</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <span class="text-2xl">🌏</span>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4">ගෝලීය සම්බන්ධතා</h3>
                    <p class="text-gray-600 text-center">ගොවීන්ට ලෝකය පුරා වෙළඳපොළක් ලබා දෙන්න.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <span class="text-2xl">🤝</span>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4">අවබෝධය සහ විශ්වාසය</h3>
                    <p class="text-gray-600 text-center">ගොවියා සහ පරිභෝගිකයා අතර විශ්වාසය බිහි කිරීම.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <span class="text-2xl">🌱</span>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4">පරිසර හිතකාමී බව</h3>
                    <p class="text-gray-600 text-center">අතිරික්ත මාලා සහ ආහාර අපතේ නොයවන පරිසර හිතකාමී ක්‍රම.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-3xl font-bold mb-8">සම්බන්ධ වන්න</h2>
                <p class="text-xl text-gray-600 mb-8">"හෙළ බෝ.." සමඟ ඔබේ ආහාර ගමන නව මුහුණුවරකට ගෙන යන්න.</p>
                <div class="flex flex-col md:flex-row justify-center gap-6 mb-12">
                    <div class="flex items-center justify-center gap-3">
                        <span class="text-2xl">📞</span>
                        <a href="tel:+940761586202" class="text-green-600 hover:text-green-700">(+94) 0761586202</a>
                    </div>
                    <div class="flex items-center justify-center gap-3">
                        <span class="text-2xl">📧</span>
                        <a href="dularashehan1111gmail.com" class="text-green-600 hover:text-green-700">dularashehan1111@gmail.com</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="text-center">
                <div class="text-2xl font-bold mb-4">හෙළ බෝ</div>
                <p class="text-gray-400">© 2024 හෙළ බෝ. සියලුම හිමිකම් ඇවිරිණි.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scroll for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Animation on scroll using GSAP
        gsap.from('.container > div', {
            opacity: 0,
            y: 50,
            duration: 1,
            stagger: 0.2,
            scrollTrigger: {
                trigger: '.container',
                start: 'top center',
                end: 'bottom center',
            }
        });
    </script>
</body>
</html>
