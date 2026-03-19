<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laxmi Bakery | Freshly Baked Happiness in Ahmedabad</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Plus+Jakarta+Sans:wght@300;400;600&display=swap');
        
        body { font-family: 'Plus Jakarta Sans', sans-serif; background-color: #fdfbf7; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        
        .gold-accent { color: #c5a059; }
        .bg-bakery-warm { background-color: #fdfbf7; }
        .btn-premium {
            background: linear-gradient(135deg, #c5a059 0%, #a68545 100%);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .btn-premium:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(197, 160, 89, 0.2);
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(197, 160, 89, 0.1);
        }
    </style>
</head>
<body>

    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-orange-100">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold gold-accent tracking-tighter">LAXMI BAKERY</div>
            <div class="hidden md:flex space-x-8 text-sm font-medium text-gray-700">
                <a href="#home" class="hover:text-[#c5a059] transition">Home</a>
                <a href="#menu" class="hover:text-[#c5a059] transition">Menu</a>
                <a href="#about" class="hover:text-[#c5a059] transition">Our Story</a>
                <a href="#location" class="hover:text-[#c5a059] transition">Find Us</a>
            </div>
            <a href="tel:7359032759" class="btn-premium text-white px-5 py-2 rounded-full text-sm">Call Now</a>
        </div>
    </nav>

    <section id="home" class="relative h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&q=80" alt="Bakery Background" class="w-full h-full object-cover brightness-50">
        </div>
        <div class="relative z-10 text-center px-4" data-aos="fade-up">
            <span class="text-gold-accent uppercase tracking-[0.3em] text-sm mb-4 block text-white/90">Traditional Taste since 1990</span>
            <h1 class="text-5xl md:text-7xl text-white mb-6">Freshly Baked <br> Happiness Every Day</h1>
            <p class="text-white/80 text-lg md:text-xl max-w-2xl mx-auto mb-10 font-light">
                Delicious puffs, pastries, and bakery treats made fresh in the heart of Maninagar.
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a href="#menu" class="btn-premium text-white px-10 py-4 rounded-full font-semibold">Order Now</a>
                <a href="#location" class="bg-white/10 backdrop-blur-md border border-white/20 text-white px-10 py-4 rounded-full font-semibold hover:bg-white hover:text-gray-900 transition">Visit Us</a>
            </div>
        </div>
    </section>

    <section id="menu" class="py-24 px-6 bg-bakery-warm">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl text-gray-800 mb-4">Our Signature Menu</h2>
                <div class="w-20 h-1 bg-[#c5a059] mx-auto"></div>
            </div>

            <div class="grid md:grid-cols-3 gap-12">
                <div class="glass-card p-8 rounded-3xl shadow-sm" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex items-center mb-6">
                        <i data-lucide="croissant" class="gold-accent mr-3"></i>
                        <h3 class="text-2xl">Puff Junction</h3>
                    </div>
                    <ul class="space-y-4 text-gray-600">
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Kachori</span> <span class="font-semibold text-gray-900">₹10</span></li>
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Veg Puff</span> <span class="font-semibold text-gray-900">₹15</span></li>
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Chinese / Schezwan</span> <span class="font-semibold text-gray-900">₹15</span></li>
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Soya Chilly</span> <span class="font-semibold text-gray-900">₹15</span></li>
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Paneer Chilly</span> <span class="font-semibold text-gray-900">₹20</span></li>
                    </ul>
                </div>

                <div class="glass-card p-8 rounded-3xl shadow-sm" data-aos="fade-up" data-aos-delay="200">
                    <div class="flex items-center mb-6">
                        <i data-lucide="utensils" class="gold-accent mr-3"></i>
                        <h3 class="text-2xl">Hotdogs & More</h3>
                    </div>
                    <ul class="space-y-4 text-gray-600">
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Chinese Hotdog</span> <span class="font-semibold text-gray-900">₹20</span></li>
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Paneer Hotdog</span> <span class="font-semibold text-gray-900">₹30</span></li>
                        <li class="flex justify-between border-b border-dashed border-gray-200 pb-2"><span>Paneer Kulcha</span> <span class="font-semibold text-gray-900">₹30</span></li>
                    </ul>
                </div>

                <div class="glass-card p-8 rounded-3xl shadow-sm" data-aos="fade-up" data-aos-delay="300">
                    <div class="flex items-center mb-6">
                        <i data-lucide="cake" class="gold-accent mr-3"></i>
                        <h3 class="text-2xl">Specialties</h3>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-[#c5a059]/10 text-[#c5a059] px-4 py-2 rounded-full text-sm">Fresh Khari</span>
                        <span class="bg-[#c5a059]/10 text-[#c5a059] px-4 py-2 rounded-full text-sm">Soft Toast</span>
                        <span class="bg-[#c5a059]/10 text-[#c5a059] px-4 py-2 rounded-full text-sm">Bread & Pav</span>
                        <span class="bg-[#c5a059]/10 text-[#c5a059] px-4 py-2 rounded-full text-sm">Cake Pastry</span>
                        <span class="bg-[#c5a059]/10 text-[#c5a059] px-4 py-2 rounded-full text-sm">Crunchy Cookies</span>
                    </div>
                    <p class="mt-6 text-sm italic text-gray-500">*We accept Customised Cake orders for all occasions!</p>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 px-6 bg-white">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-center text-3xl mb-16">Chef's Recommendations</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="group overflow-hidden rounded-2xl relative" data-aos="zoom-in">
                    <img src="https://images.unsplash.com/photo-1495147466023-ac5c588e2e94?auto=format&fit=crop&q=80&w=400" class="w-full h-64 object-cover group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 flex items-end p-6 transition">
                        <p class="text-white font-medium">Assorted Cookies</p>
                    </div>
                </div>
                <div class="group overflow-hidden rounded-2xl relative" data-aos="zoom-in" data-aos-delay="100">
                    <img src="https://images.unsplash.com/photo-1555507036-ab1f4038808a?auto=format&fit=crop&q=80&w=400" class="w-full h-64 object-cover group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 flex items-end p-6 transition">
                        <p class="text-white font-medium">Golden Puffs</p>
                    </div>
                </div>
                <div class="group overflow-hidden rounded-2xl relative" data-aos="zoom-in" data-aos-delay="200">
                    <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&q=80&w=400" class="w-full h-64 object-cover group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 flex items-end p-6 transition">
                        <p class="text-white font-medium">Custom Cakes</p>
                    </div>
                </div>
                <div class="group overflow-hidden rounded-2xl relative" data-aos="zoom-in" data-aos-delay="300">
                    <img src="https://images.unsplash.com/photo-1558961363-fa8fdf82db35?auto=format&fit=crop&q=80&w=400" class="w-full h-64 object-cover group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 flex items-end p-6 transition">
                        <p class="text-white font-medium">Fresh Khari</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="location" class="py-24 px-6 bg-bakery-warm">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 items-start">
            <div data-aos="fade-right">
                <h2 class="text-4xl mb-8">Visit Our Bakery</h2>
                <div class="space-y-6 text-gray-600 mb-8">
                    <div class="flex items-start">
                        <i data-lucide="map-pin" class="gold-accent mr-4 mt-1"></i>
                        <p>Shop No. 94, Laxmi Bakery, Railway Station Under,<br>Nathalal Jagad Flyover, Opp. Maninagar,<br>Sindhi Market, Ahmedabad 380008</p>
                    </div>
                    <div class="flex items-center">
                        <i data-lucide="phone" class="gold-accent mr-4"></i>
                        <p>+91 73590 32759</p>
                    </div>
                    <div class="flex items-center">
                        <i data-lucide="clock" class="gold-accent mr-4"></i>
                        <p>Open Daily: 8:00 AM - 10:00 PM</p>
                    </div>
                </div>
                <div class="rounded-3xl overflow-hidden shadow-lg h-64 grayscale hover:grayscale-0 transition duration-500">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3672.486259796016!2d72.5996841!3d22.9967115!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x395e85c18600d86f%3A0xf6508c90b0e53a2b!2sLaxmi%20Bakery!5e0!3m2!1sen!2sin!4v1700000000000" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </div>

            <div class="glass-card p-10 rounded-3xl" data-aos="fade-left">
                <h3 class="text-2xl mb-6">Send a Message</h3>
                <form class="space-y-4">
                    <input type="text" placeholder="Your Name" class="w-full px-6 py-4 rounded-xl border border-orange-100 focus:outline-none focus:ring-2 focus:ring-[#c5a059]/20">
                    <input type="email" placeholder="Your Email" class="w-full px-6 py-4 rounded-xl border border-orange-100 focus:outline-none focus:ring-2 focus:ring-[#c5a059]/20">
                    <textarea placeholder="Tell us what you're craving..." rows="4" class="w-full px-6 py-4 rounded-xl border border-orange-100 focus:outline-none focus:ring-2 focus:ring-[#c5a059]/20"></textarea>
                    <button class="btn-premium text-white w-full py-4 rounded-xl font-bold uppercase tracking-wider">Send Inquiry</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="py-12 border-t border-orange-100 text-center">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-xl font-bold gold-accent mb-6">LAXMI BAKERY</div>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="#" class="text-gray-400 hover:text-[#c5a059] transition"><i data-lucide="instagram"></i></a>
                <a href="#" class="text-gray-400 hover:text-[#c5a059] transition"><i data-lucide="facebook"></i></a>
                <a href="#" class="text-gray-400 hover:text-[#c5a059] transition"><i data-lucide="twitter"></i></a>
            </div>
            <p class="text-sm text-gray-400">&copy; 2026 Laxmi Bakery Ahmedabad. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        // Initialize Icons
        lucide.createIcons();
        // Initialize Animations
        AOS.init({ duration: 1000, once: true });
    </script>
</body>
</html>
