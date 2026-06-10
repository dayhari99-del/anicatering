<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ANI CATERING - Hidangan Istimewa Kelas Bintang Lima</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    },
                    colors: {
                        gold: {
                            100: '#fef3c7',
                            400: '#fbbf24',
                            500: '#f59e0b',
                            600: '#d97706',
                            700: '#b45309',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .gold-gradient-text {
            background: linear-gradient(135deg, #fef3c7 0%, #fbbf24 50%, #b45309 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gold-border-gradient {
            border-image: linear-gradient(to right, #b45309, #fbbf24, #b45309) 1;
        }
    </style>
</head>
<body class="bg-neutral-950 text-neutral-200 font-sans antialiased overflow-x-hidden">

    <header class="fixed top-0 left-0 w-full bg-neutral-950/90 backdrop-blur-md z-50 border-b border-amber-500/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="text-xl sm:text-2xl font-extrabold tracking-wider text-amber-500 flex items-center gap-2">
                <i data-lucide="utensils" class="w-6 h-6 text-amber-500"></i>
                ANI <span class="text-white font-light">CATERING</span>
            </a>
            
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium tracking-wide">
                <a href="#" class="text-amber-500 transition-colors duration-300">Home</a>
                <a href="#solusi" class="text-neutral-400 hover:text-amber-400 transition-colors duration-300">Tentang</a>
                <a href="#menu" class="text-neutral-400 hover:text-amber-400 transition-colors duration-300">Menu</a>
                <a href="#keunggulan" class="text-neutral-400 hover:text-amber-400 transition-colors duration-300">Keunggulan</a>
            </nav>

            <div class="hidden md:block">
                <a href="https://wa.me/62895321735409" target="_blank" class="inline-flex items-center gap-2 px-5 py-2.5 border border-amber-500 text-amber-500 rounded-full text-sm font-semibold hover:bg-amber-500 hover:text-neutral-950 transition-all duration-300 transform hover:scale-105">
                    <i data-lucide="phone" class="w-4 h-4"></i> Hubungi Kami
                </a>
            </div>

            <button id="menu-btn" class="md:hidden text-amber-500 focus:outline-none" aria-label="Toggle Menu">
                <i data-lucide="menu" class="w-8 h-8"></i>
            </button>
        </div>

        <div id="mobile-menu" class="hidden md:hidden bg-neutral-900 border-b border-amber-500/20 px-4 pt-2 pb-6 space-y-4">
            <a href="#" class="block py-2 text-amber-500 font-medium">Home</a>
            <a href="#solusi" class="block py-2 text-neutral-300 hover:text-amber-400 transition-colors">Tentang</a>
            <a href="#menu" class="block py-2 text-neutral-300 hover:text-amber-400 transition-colors">Menu</a>
            <a href="#keunggulan" class="block py-2 text-neutral-300 hover:text-amber-400 transition-colors">Keunggulan</a>
            <a href="https://wa.me/62895321735409" target="_blank" class="w-full text-center inline-flex justify-center items-center gap-2 px-5 py-3 bg-amber-500 text-neutral-950 rounded-lg font-bold">
                <i data-lucide="phone" class="w-4 h-4"></i> Hubungi Kami
            </a>
        </div>
    </header>

    <section class="relative pt-32 pb-20 md:pt-44 md:pb-32 overflow-hidden bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-neutral-900 via-neutral-950 to-black">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            
            <div class="lg:col-span-7 text-center lg:text-left z-10">
                <span class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-400 text-xs font-semibold tracking-wider uppercase mb-6">
                    <i data-lucide="sparkles" class="w-3.5 h-3.5"></i> Premium Catering Services
                </span>
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-white leading-tight mb-6">
                    Bikin Momen Spesial Anda Tak Terlupakan dengan <span class="gold-gradient-text">Hidangan Istimewa</span> Kelas Bintang Lima
                </h1>
                <p class="text-base sm:text-lg text-neutral-400 font-light leading-relaxed mb-8 max-w-2xl mx-auto lg:mx-0">
                    Pilihan Menu Eropa, Sunda, hingga Nusantara Terbaik di Bandung. Siap Melayani Pernikahan, Syukuran, Khitanan, dan Berbagai Acara Istimewa Anda.
                </p>
                <div class="flex flex-col sm:flex-row justify-center lg:justify-start items-center gap-4">
                    <a href="https://wa.me/62895321735409" target="_blank" class="w-full sm:w-auto text-center inline-flex items-center justify-center gap-3 px-8 py-4 bg-gradient-to-r from-amber-600 via-amber-500 to-amber-600 text-neutral-950 font-bold rounded-xl shadow-[0_4px_20px_rgba(245,158,11,0.4)] hover:shadow-[0_4px_25px_rgba(245,158,11,0.6)] transition-all duration-300 transform hover:-translate-y-0.5">
                        <i data-lucide="whatsapp" class="w-5 h-5 fill-current"></i> Konsultasi Menu & Harga Sekarang (Free)
                    </a>
                </div>
            </div>

            <div class="lg:col-span-5 relative mt-8 lg:mt-0 flex justify-center">
                <div class="relative w-72 h-72 sm:w-96 sm:h-96 lg:w-full lg:h-[450px]">
                    <div class="absolute inset-0 bg-gradient-to-tr from-amber-500 to-transparent opacity-20 rounded-3xl blur-2xl"></div>
                    <div class="w-full h-full rounded-2xl overflow-hidden border-2 border-amber-500/30 shadow-2xl transform rotate-2 hover:rotate-0 transition-transform duration-500">
                        <img src="https://images.unsplash.com/photo-1555244162-803834f70033?auto=format&fit=crop&w=800&q=80" alt="Luxury Wedding Catering" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="solusi" class="py-20 bg-neutral-900 border-y border-amber-500/10">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-b from-neutral-950 to-neutral-900 rounded-3xl border border-amber-500/20 p-8 sm:p-12 lg:p-16 shadow-xl relative overflow-hidden">
                <div class="absolute top-0 right-0 p-8 opacity-5">
                    <i data-lucide="help-circle" class="w-40 h-40 text-amber-500"></i>
                </div>
                
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start relative z-10">
                    <div class="lg:col-span-5">
                        <h2 class="text-xl sm:text-2xl font-bold text-amber-400 mb-4 flex items-center gap-2">
                            <i data-lucide="alert-circle" class="w-5 h-5 text-amber-500 shrink-0"></i> Bingung Pilih Menu?
                        </h2>
                        <p class="text-neutral-400 text-sm sm:text-base leading-relaxed font-light">
                            Setiap tamu punya selera yang berbeda. Ada yang suka makanan lokal yang medok, ada yang rindu masakan nusantara, dan ada juga anak muda yang lebih memilih hidangan modern kebarat-baratan.
                        </p>
                    </div>

                    <div class="hidden lg:block lg:col-span-1 justify-self-center h-full w-[1px] bg-amber-500/20"></div>

                    <div class="lg:col-span-6">
                        <h2 class="text-xl sm:text-2xl font-bold text-white mb-4 flex items-center gap-2">
                            <i data-lucide="check-circle" class="w-5 h-5 text-amber-500 shrink-0"></i> Kami Punya Solusinya!
                        </h2>
                        <p class="text-neutral-300 text-sm sm:text-base leading-relaxed mb-4">
                            <strong class="text-amber-400 font-semibold">ANI CATERING</strong> hadir sebagai solusi satu pintu untuk semua kebutuhan acara Anda! Kami memadukan kelezatan tradisi dan kemewahan kuliner internasional dalam satu pelayanan profesional.
                        </p>
                        <p class="text-neutral-400 text-xs sm:text-sm flex items-center gap-2 bg-neutral-950 p-3 rounded-lg border border-neutral-800">
                            <i data-lucide="map-pin" class="w-4 h-4 text-amber-500 shrink-0"></i> Berlokasi strategis di dekat Terminal Leuwi Panjang, Kota Bandung.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="menu" class="py-20 bg-neutral-950">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-amber-500 font-semibold tracking-wider uppercase text-xs">Pilihan Menu Masterpiece</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">Kombinasi Sempurna Cita Rasa</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                
                <div class="bg-neutral-900 rounded-2xl overflow-hidden border border-neutral-800 hover:border-amber-500/40 transition-all duration-300 group flex flex-col justify-between">
                    <div>
                        <div class="h-48 overflow-hidden relative">
                            <img src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=600&q=80" alt="Masakan Eropa" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <div class="absolute inset-0 bg-gradient-to-t from-neutral-900 via-transparent to-transparent"></div>
                            <span class="absolute top-4 left-4 bg-neutral-950/80 backdrop-blur-sm text-amber-400 text-xs font-semibold px-3 py-1 rounded-full border border-amber-500/30 flex items-center gap-1">
                                <i data-lucide="globe" class="w-3 h-3"></i> Western & Middle East
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-white mb-3">Masakan Eropa</h3>
                            <p class="text-neutral-400 text-sm leading-relaxed mb-4">Hidangan modern internasional dengan standar rasa premium barat dan timur tengah.</p>
                            <div class="space-y-2 border-t border-neutral-800 pt-4">
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Steak Wagyu Juicy</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Spaghetti & Pasta Variant</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Premium Burger</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Nasi Kebuli Kaya Rempah</div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <span class="text-xs text-amber-500/80 italic font-light">+ Puluhan menu Eropa lainnya</span>
                    </div>
                </div>

                <div class="bg-neutral-900 rounded-2xl overflow-hidden border border-neutral-800 hover:border-amber-500/40 transition-all duration-300 group flex flex-col justify-between">
                    <div>
                        <div class="h-48 overflow-hidden relative">
                            <img src="https://images.unsplash.com/photo-1626132647523-66f5bf380027?auto=format&fit=crop&w=600&q=80" alt="Masakan Sunda" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <div class="absolute inset-0 bg-gradient-to-t from-neutral-900 via-transparent to-transparent"></div>
                            <span class="absolute top-4 left-4 bg-neutral-950/80 backdrop-blur-sm text-amber-400 text-xs font-semibold px-3 py-1 rounded-full border border-amber-500/30 flex items-center gap-1">
                                <i data-lucide="heart" class="w-3 h-3"></i> Otentik Tradisional
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-white mb-3">Otentik Masakan Sunda</h3>
                            <p class="text-neutral-400 text-sm leading-relaxed mb-4">Cita rasa masakan parahyangan asli yang kental, segar, dan menggugah selera.</p>
                            <div class="space-y-2 border-t border-neutral-800 pt-4">
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Nasi Liwet & Nasi Timbel</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Karedok Leunca khas Sunda</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Lalapan Segar & Sambal Khas</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Kue Jajanan Pasar Tradisional</div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <span class="text-xs text-amber-500/80 italic font-light">+ Pilihan takjil & jajanan Sunda</span>
                    </div>
                </div>

                <div class="bg-neutral-900 rounded-2xl overflow-hidden border border-neutral-800 hover:border-amber-500/40 transition-all duration-300 group flex flex-col justify-between">
                    <div>
                        <div class="h-48 overflow-hidden relative">
                            <img src="https://images.unsplash.com/photo-1541518763669-27fef04b14ea?auto=format&fit=crop&w=600&q=80" alt="Masakan Nusantara" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <div class="absolute inset-0 bg-gradient-to-t from-neutral-900 via-transparent to-transparent"></div>
                            <span class="absolute top-4 left-4 bg-neutral-950/80 backdrop-blur-sm text-amber-400 text-xs font-semibold px-3 py-1 rounded-full border border-amber-500/30 flex items-center gap-1">
                                <i data-lucide="award" class="w-3 h-3"></i> Mahakarya Kuliner
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-white mb-3">Mahakarya Kuliner Indonesia</h3>
                            <p class="text-neutral-400 text-sm leading-relaxed mb-4">Koleksi menu legendaris dari berbagai pelosok nusantara dengan rempah pilihan.</p>
                            <div class="space-y-2 border-t border-neutral-800 pt-4">
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Rendang Daging Sapi Premium</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Sate Madura Bumbu Kacang</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Sop Daging Sapi Gurih</div>
                                <div class="flex items-center gap-2 text-xs text-neutral-300"><i data-lucide="check" class="w-3.5 h-3.5 text-amber-500"></i> Tempoyak & Pempek Asli</div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <span class="text-xs text-amber-500/80 italic font-light">+ Puluhan menu Nusantara lainnya</span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="keunggulan" class="py-20 bg-neutral-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-amber-500 font-semibold tracking-wider uppercase text-xs">Mengapa Memilih Kami</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">Standar Layanan Terbaik Untuk Anda</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                
                <div class="bg-neutral-950 p-6 rounded-xl border border-neutral-800 hover:border-amber-500/20 transition-colors">
                    <div class="w-12 h-12 bg-amber-500/10 rounded-lg flex items-center justify-center border border-amber-500/30 mb-5">
                        <i data-lucide="layers" class="w-6 h-6 text-amber-500"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Menu Paling Variatif</h3>
                    <p class="text-neutral-400 text-xs sm:text-sm leading-relaxed font-light">
                        Bisa kombinasi menu Sunda, Indonesia, hingga Eropa sekaligus dalam satu paket prasmanan acara Anda.
                    </p>
                </div>

                <div class="bg-neutral-950 p-6 rounded-xl border border-neutral-800 hover:border-amber-500/20 transition-colors">
                    <div class="w-12 h-12 bg-amber-500/10 rounded-lg flex items-center justify-center border border-amber-500/30 mb-5">
                        <i data-lucide="navigation" class="w-6 h-6 text-amber-500"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Lokasi & Akses Cepat</h3>
                    <p class="text-neutral-400 text-xs sm:text-sm leading-relaxed font-light">
                        Dekat Terminal Leuwi Panjang, Bandung. Kami menjamin makanan sampai tepat waktu & hidangan tetap hangat.
                    </p>
                </div>

                <div class="bg-neutral-950 p-6 rounded-xl border border-neutral-800 hover:border-amber-500/20 transition-colors">
                    <div class="w-12 h-12 bg-amber-500/10 rounded-lg flex items-center justify-center border border-amber-500/30 mb-5">
                        <i data-lucide="shield-check" class="w-6 h-6 text-amber-500"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Berkualitas & Higienis</h3>
                    <p class="text-neutral-400 text-xs sm:text-sm leading-relaxed font-light">
                        Dari daging wagyu pilihan hingga sayur lalapan segar diproses secara higienis demi kesehatan para tamu.
                    </p>
                </div>

                <div class="bg-neutral-950 p-6 rounded-xl border border-neutral-800 hover:border-amber-500/20 transition-colors">
                    <div class="w-12 h-12 bg-amber-500/10 rounded-lg flex items-center justify-center border border-amber-500/30 mb-5">
                        <i data-lucide="dollar-sign" class="w-6 h-6 text-amber-500"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Fleksibel Sesuai Budget</h3>
                    <p class="text-neutral-400 text-xs sm:text-sm leading-relaxed font-light">
                        Tidak perlu khawatir, kami siap menyesuaikan porsi dan pilihan ragam menu dengan besaran anggaran Anda.
                    </p>
                </div>

            </div>
        </div>
    </section>

    <section class="py-20 bg-neutral-950 overflow-hidden relative">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-10">
                <i data-lucide="quote" class="w-12 h-12 text-amber-500/30 mx-auto transform rotate-180"></i>
            </div>
            
            <blockquote class="gold-border-gradient border-l-4 pl-6 sm:pl-10 py-4">
                <p class="text-xl sm:text-2xl font-medium italic text-neutral-200 leading-relaxed">
                    "Makanannya enak-enak banget! Kemarin pas nikahan sepupu pakai Ani Catering, tamu-tamu pada muji steak wagyu sama nasi liwetnya. Kombinasi menunya juara!"
                </p>
                <cite class="block mt-6 not-italic">
                    <span class="text-base font-bold text-amber-400">— Rian</span>
                    <span class="text-xs text-neutral-500 block">Bandung</span>
                </cite>
            </blockquote>
        </div>
    </section>

    <section class="py-20 bg-neutral-900 border-t border-amber-500/20 relative">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-amber-500/5 via-transparent to-transparent"></div>
        
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <h2 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight mb-6">
                Wujudkan Acara Impian Anda Tanpa Ribet Urusan Dapur!
            </h2>
            <p class="text-base sm:text-lg text-neutral-300 font-light max-w-2xl mx-auto mb-10 leading-relaxed">
                Biarkan kami yang bekerja di balik layar, sementara Anda menikmati momen bahagia bersama keluarga. Amankan Tanggal Acara Anda Sekarang Juga!
            </p>
            <a href="https://wa.me/62895321735409" target="_blank" class="inline-flex items-center gap-3 px-8 py-4 sm:px-10 sm:py-5 bg-gradient-to-r from-amber-500 to-amber-600 text-neutral-950 font-black rounded-xl text-sm sm:text-base tracking-wider uppercase shadow-[0_4px_30px_rgba(245,158,11,0.3)] hover:shadow-[0_4px_40px_rgba(245,158,11,0.5)] transition-all duration-300 transform hover:scale-105">
                <i data-lucide="message-square" class="w-5 h-5 fill-current"></i> CHAT VIA WHATSAPP (0895327493399)
            </a>
        </div>
    </section>

    <footer class="bg-black text-neutral-500 text-xs sm:text-sm py-12 border-t border-neutral-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8 items-center text-center md:text-left">
            
            <div>
                <p class="text-sm font-bold text-amber-500 tracking-wider">ANI CATERING</p>
                <p class="mt-2 text-neutral-400 font-light">Menyajikan Kemewahan Kuliner Kelas Bintang Lima.</p>
            </div>

            <div class="flex flex-col items-center md:items-start gap-1">
                <span class="text-neutral-400 font-medium flex items-center gap-1">
                    <i data-lucide="map-pin" class="w-4 h-4 text-amber-500"></i> Alamat Kami:
                </span>
                <p class="text-neutral-500 font-light">Dekat Terminal Leuwi Panjang, Kota Bandung.</p>
            </div>

            <div class="md:text-right flex flex-col items-center md:items-end gap-2">
                <div class="flex gap-4 mb-2">
                    <a href="#" class="text-neutral-500 hover:text-amber-500 transition-colors"><i data-lucide="instagram" class="w-5 h-5"></i></a>
                    <a href="#" class="text-neutral-500 hover:text-amber-500 transition-colors"><i data-lucide="facebook" class="w-5 h-5"></i></a>
                </div>
                <p>&copy; 2026 ANI CATERING. All Rights Reserved.</p>
            </div>

        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Mobile Menu Toggle Logic
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking any link inside it
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
