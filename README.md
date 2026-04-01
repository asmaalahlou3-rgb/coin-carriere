<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coin Carrière | Immobilier d'Entreprise Stratégique</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@0.400.0/dist/umd/lucide.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        
        /* Palette Vert Émeraude & Or */
        .bg-emerald-dark { background-color: #04241B; }
        .bg-emerald-deeper { background-color: #02140F; }
        .text-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .border-gold { border-color: #D4AF37; }
        .hover-gold:hover { background-color: #C59B27; }
        
        /* Effet "Glassmorphism" pour le design premium */
        .glass-card {
            background: rgba(4, 36, 27, 0.6);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(212, 175, 55, 0.15);
        }
        .glass-card:hover {
            border: 1px solid rgba(212, 175, 55, 0.4);
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-[#F4F7F6] text-[#02140F]">

    <nav class="fixed top-0 w-full bg-emerald-deeper/90 backdrop-blur-md z-50 border-b border-emerald-900/50">
        <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
            <div class="text-white font-bold text-2xl flex items-center gap-3">
                <div class="w-11 h-11 bg-gold/10 border border-gold rounded-lg flex items-center justify-center">
                    <i data-lucide="briefcase" class="text-gold w-6 h-6"></i>
                </div>
                <div class="flex flex-col leading-none">
                    <span class="text-xl font-extrabold tracking-tight">COIN CARRIÈRE</span>
                    <span class="text-[10px] text-gold tracking-widest uppercase font-semibold">Immobilier d'affaires</span>
                </div>
            </div>
            
            <a href="#formulaire" class="bg-gold text-emerald-deeper font-bold px-6 py-3 rounded-lg text-sm hover-gold transition-all shadow-lg shadow-gold/10">
                Opportunités exclusives
            </a>
        </div>
    </nav>

    <section class="relative min-h-screen flex items-center bg-cover bg-center pt-20" style="background-image: url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070');">
        <div class="absolute inset-0 bg-gradient-to-r from-[#02140F]/95 via-[#02140F]/85 to-[#04241B]/60"></div>
        
        <div class="relative max-w-7xl mx-auto px-6 lg:px-8 w-full py-24">
            <div class="max-w-4xl">
                <span class="text-gold uppercase tracking-widest text-sm font-bold mb-5 block">Stratégie foncière au Maroc</span>
                
                <h1 class="text-5xl md:text-6xl lg:text-7xl font-extrabold text-white mb-6 leading-tight">
                    Prenez le contrôle de votre <span class="text-gold">croissance immobilière.</span>
                </h1>
                
                <p class="text-xl md:text-2xl text-slate-200 mb-10 max-w-3xl leading-relaxed font-light">
                    Coin Carrière accompagne les entreprises leaders dans la recherche, l’acquisition et l’optimisation de leurs actifs professionnels.
                </p>
                
                <div class="flex flex-col sm:flex-row gap-5 mb-14">
                    <a href="#formulaire" class="bg-gold text-emerald-deeper font-bold px-8 py-4 rounded-lg shadow-xl shadow-gold/20 hover-gold transition-all text-center flex items-center justify-center gap-2 text-lg">
                        Accéder aux offres Off-Market
                        <i data-lucide="arrow-right" class="w-6 h-6"></i>
                    </a>
                    <a href="#agents" class="border-2 border-white/80 text-white font-bold px-8 py-4 rounded-lg hover:bg-white/10 transition-all text-center text-lg">
                        Contacter un expert
                    </a>
                </div>

                <div class="flex flex-wrap gap-8 text-white text-base">
                    <div class="flex items-center gap-3"><i data-lucide="shield" class="text-gold w-6 h-6"></i> +10 ans d'expertise</div>
                    <div class="flex items-center gap-3"><i data-lucide="building" class="text-gold w-6 h-6"></i> +200 entreprises gérées</div>
                    <div class="flex items-center gap-3"><i data-lucide="globe" class="text-gold w-6 h-6"></i> Réseau 100% Privé</div>
                </div>
            </div>
        </div>
    </section>

    <section id="agents" class="py-24 bg-[#F4F7F6]">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-gold uppercase tracking-widest text-xs font-bold mb-3 block">Des experts à votre écoute</span>
                <h2 class="text-4xl md:text-5xl font-extrabold text-emerald-deeper mb-5">Nos Consultants Senior</h2>
                <div class="w-24 h-1.5 bg-gold mx-auto mb-6"></div>
                <p class="text-xl text-slate-600 max-w-2xl mx-auto leading-relaxed">Faites équipe avec des professionnels chevronnés du marché marocain.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                <div class="bg-white rounded-2xl overflow-hidden shadow-xl shadow-slate-200/60 hover:shadow-2xl transition-all group">
                    <div class="h-96 bg-slate-200 relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center text-slate-400 text-lg font-medium">Portrait Consultant</div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-emerald-deeper mb-1">Karim El Mansouri</h3>
                        <p class="text-gold text-base font-semibold mb-4">Directeur Pôle Bureaux</p>
                        <p class="text-slate-600 text-base leading-relaxed mb-6">Expert en négociations de baux commerciaux pour les grandes firmes à Casablanca.</p>
                        <div class="flex items-center gap-5 text-slate-400">
                            <i data-lucide="linkedin" class="w-6 h-6 hover:text-emerald-dark cursor-pointer transition-colors"></i>
                            <i data-lucide="mail" class="w-6 h-6 hover:text-emerald-dark cursor-pointer transition-colors"></i>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-2xl overflow-hidden shadow-xl shadow-slate-200/60 hover:shadow-2xl transition-all group">
                    <div class="h-96 bg-slate-200 relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center text-slate-400 text-lg font-medium">Portrait Consultante</div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-emerald-deeper mb-1">Sofia Bennani</h3>
                        <p class="text-gold text-base font-semibold mb-4">Spécialiste Retail & Commerces</p>
                        <p class="text-slate-600 text-base leading-relaxed mb-6">Forte d'un carnet d'adresses exclusif pour les meilleurs emplacements de Rabat.</p>
                        <div class="flex items-center gap-5 text-slate-400">
                            <i data-lucide="linkedin" class="w-6 h-6 hover:text-emerald-dark cursor-pointer transition-colors"></i>
                            <i data-lucide="mail" class="w-6 h-6 hover:text-emerald-dark cursor-pointer transition-colors"></i>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-2xl overflow-hidden shadow-xl shadow-slate-200/60 hover:shadow-2xl transition-all group">
                    <div class="h-96 bg-slate-200 relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center text-slate-400 text-lg font-medium">Portrait Consultant</div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-emerald-deeper mb-1">Youssef Amrani</h3>
                        <p class="text-gold text-base font-semibold mb-4">Consultant Logistique</p>
                        <p class="text-slate-600 text-base leading-relaxed mb-6">Assure l'implantation de vos hubs industriels sur tout le territoire marocain.</p>
                        <div class="flex items-center gap-5 text-slate-400">
                            <i data-lucide="linkedin" class="w-6 h-6 hover:text-emerald-dark cursor-pointer transition-colors"></i>
                            <i data-lucide="mail" class="w-6 h-6 hover:text-emerald-dark cursor-pointer transition-colors"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-gold uppercase tracking-widest text-xs font-bold mb-3 block">Paroles de leaders</span>
                <h2 class="text-4xl md:text-5xl font-extrabold text-emerald-deeper mb-5">Ils nous font confiance</h2>
                <div class="w-24 h-1.5 bg-gold mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                <div class="bg-[#F4F7F6] p-10 rounded-2xl flex flex-col justify-between border border-transparent hover:border-gold/20 hover:bg-white hover:shadow-xl transition-all">
                    <div>
                        <div class="flex text-gold mb-5">
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                        </div>
                        <p class="text-slate-700 text-lg leading-relaxed mb-8 font-light">
                            "Coin Carrière a compris nos enjeux à l'international. Ils nous ont déniché un plateau de bureaux exceptionnel au sein de la CFC."
                        </p>
                    </div>
                    <div class="flex items-center gap-4 border-t border-slate-200 pt-6">
                        <div class="w-12 h-12 bg-slate-300 rounded-full"></div>
                        <div>
                            <p class="text-lg font-bold text-emerald-deeper">Kamil B.</p>
                            <p class="text-sm text-slate-500">Directeur Général, Tech Corp</p>
                        </div>
                    </div>
                </div>

                <div class="bg-[#F4F7F6] p-10 rounded-2xl flex flex-col justify-between border border-transparent hover:border-gold/20 hover:bg-white hover:shadow-xl transition-all">
                    <div>
                        <div class="flex text-gold mb-5">
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                        </div>
                        <p class="text-slate-700 text-lg leading-relaxed mb-8 font-light">
                            "Une agilité folle. Coin Carrière a su écouter nos contraintes spatiales et nous proposer des solutions en un temps record."
                        </p>
                    </div>
                    <div class="flex items-center gap-4 border-t border-slate-200 pt-6">
                        <div class="w-12 h-12 bg-slate-300 rounded-full"></div>
                        <div>
                            <p class="text-lg font-bold text-emerald-deeper">Sanaa M.</p>
                            <p class="text-sm text-slate-500">Fondatrice & CEO, Startup IA</p>
                        </div>
                    </div>
                </div>

                <div class="bg-[#F4F7F6] p-10 rounded-2xl flex flex-col justify-between border border-transparent hover:border-gold/20 hover:bg-white hover:shadow-xl transition-all">
                    <div>
                        <div class="flex text-gold mb-5">
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                            <i data-lucide="star" class="w-5 h-5 fill-current"></i>
                        </div>
                        <p class="text-slate-700 text-lg leading-relaxed mb-8 font-light">
                            "Un accompagnement rigoureux de bout en bout pour notre plateforme logistique. Des économies générées indispensables."
                        </p>
                    </div>
                    <div class="flex items-center gap-4 border-t border-slate-200 pt-6">
                        <div class="w-12 h-12 bg-slate-300 rounded-full"></div>
                        <div>
                            <p class="text-lg font-bold text-emerald-deeper">Omar T.</p>
                            <p class="text-sm text-slate-500">Directeur Supply Chain</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="formulaire" class="py-24 bg-emerald-deeper text-white">
        <div class="max-w-5xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-gold uppercase tracking-widest text-xs font-bold mb-3 block">Prenez une longueur d'avance</span>
                <h2 class="text-4xl md:text-5xl font-extrabold mb-5">Recevez nos opportunités "Off-Market"</h2>
                <p class="text-xl text-slate-300 max-w-2xl mx-auto leading-relaxed">Remplissez le formulaire. Un consultant dédié vous contactera sous 24h.</p>
            </div>

            <form class="space-y-8 glass-card p-10 md:p-14 rounded-3xl">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div>
                        <label class="block text-base font-medium text-slate-200 mb-3">Nom complet *</label>
                        <input type="text" class="w-full bg-emerald-deeper/50 border border-emerald-800 rounded-lg py-4 px-5 text-white focus:outline-none focus:border-gold transition-colors text-lg" placeholder="Ex: Karim Benjelloun" required>
                    </div>
                    <div>
                        <label class="block text-base font-medium text-slate-200 mb-3">Nom de l'Entreprise *</label>
                        <input type="text" class="w-full bg-emerald-deeper/50 border border-emerald-800 rounded-lg py-4 px-5 text-white focus:outline-none focus:border-gold transition-colors text-lg" placeholder="Ex: Alpha SA" required>
                    </div>
                </div>

                <div>
                    <label class="block text-base font-medium text-slate-200 mb-3">Téléphone professionnel (WhatsApp) *</label>
                    <input type="tel" class="w-full bg-emerald-deeper/50 border border-emerald-800 rounded-lg py-4 px-5 text-white focus:outline-none focus:border-gold transition-colors text-lg" placeholder="+212 6..." required>
                </div>

                <button type="submit" class="w-full bg-gold text-emerald-deeper font-bold px-8 py-5 rounded-lg shadow-lg shadow-gold/10 hover-gold transition-all duration-300 flex items-center justify-center gap-3 text-xl">
                    Accéder aux opportunités
                    <i data-lucide="arrow-right" class="w-6 h-6"></i>
                </button>
                <p class="text-sm text-slate-400 text-center">En soumettant ce formulaire, vous acceptez nos conditions de confidentialité strictes.</p>
            </form>
        </div>
    </section>

    <footer class="py-14 bg-emerald-deeper border-t border-emerald-900/50 text-slate-400 text-base">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center gap-8">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-gold/10 border border-gold rounded flex items-center justify-center">
                    <i data-lucide="briefcase" class="text-gold w-5 h-5"></i>
                </div>
                <div class="flex flex-col leading-none">
                    <span class="text-base font-extrabold text-white tracking-tight">COIN CARRIÈRE</span>
                    <span class="text-[9px] text-gold tracking-widest font-semibold">IMMOBILIER D'AFFAIRES</span>
                </div>
            </div>
            <p>&copy; 2026 Coin Carrière. Tous droits réservés.</p>
        </div>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
                            
