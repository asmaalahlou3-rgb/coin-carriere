<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coin Carrière | Immobilier d'Entreprise</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@0.400.0/dist/umd/lucide.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .bg-corporate-dark { background-color: #0F172A; }
        .bg-corporate-deeper { background-color: #0B1120; }
        .text-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .border-gold { border-color: #D4AF37; }
        .hover-gold:hover { background-color: #C59B27; }
        .glass-card {
            background: rgba(15, 23, 42, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(212, 175, 55, 0.15);
        }
    </style>
</head>
<body class="bg-[#F8F9FA] text-[#1E293B]">

    <nav class="fixed top-0 w-full bg-corporate-deeper/95 backdrop-blur-md z-50 border-b border-slate-800/50">
        <div class="max-w-5xl mx-auto px-6 py-3 flex justify-between items-center">
            <div class="text-white font-bold flex items-center gap-2">
                <div class="w-9 h-9 bg-gold/10 border border-gold rounded-lg flex items-center justify-center">
                    <i data-lucide="briefcase" class="text-gold w-5 h-5"></i>
                </div>
                <div class="flex flex-col leading-none">
                    <span class="text-base font-extrabold tracking-tight">COIN CARRIÈRE</span>
                    <span class="text-[8px] text-gold tracking-widest uppercase font-semibold">Immobilier d'affaires</span>
                </div>
            </div>
            <a href="#formulaire" class="bg-gold text-corporate-deeper font-bold px-4 py-2 rounded-lg text-sm hover-gold transition-all">
                Opportunités
            </a>
        </div>
    </nav>

    <section class="relative bg-cover bg-center pt-24 pb-12" style="background-image: url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070');">
        <div class="absolute inset-0 bg-gradient-to-r from-[#0B1120]/95 via-[#0B1120]/85 to-[#0F172A]/60"></div>
        
        <div class="relative max-w-5xl mx-auto px-6 w-full">
            <div class="max-w-2xl">
                <span class="text-gold uppercase tracking-widest text-xs font-bold mb-3 block">Stratégie foncière au Maroc</span>
                <h1 class="text-3xl md:text-4xl lg:text-5xl font-extrabold text-white mb-4 leading-tight">
                    Transformez votre croissance en opportunité <span class="text-gold">immobilière.</span>
                </h1>
                <p class="text-base md:text-lg text-slate-200 mb-6 leading-relaxed font-light">
                    Coin Carrière accompagne les entreprises dans la recherche, l’acquisition et l’optimisation de leurs actifs immobiliers professionnels.
                </p>
                
                <div class="flex flex-col sm:flex-row gap-3 mb-6">
                    <a href="#formulaire" class="bg-gold text-corporate-deeper font-bold px-5 py-3 rounded-lg shadow-lg hover-gold transition-all text-center flex items-center justify-center gap-2 text-sm">
                        Opportunités exclusives
                        <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </a>
                    <a href="#solutions" class="border-2 border-white/80 text-white font-bold px-5 py-3 rounded-lg hover:bg-white/10 transition-all text-center text-sm">
                        Consultation gratuite
                    </a>
                </div>

                <div class="flex flex-wrap gap-4 text-white text-xs">
                    <div class="flex items-center gap-2"><i data-lucide="shield" class="text-gold w-4 h-4"></i> +10 ans d'expérience</div>
                    <div class="flex items-center gap-2"><i data-lucide="building" class="text-gold w-4 h-4"></i> +200 entreprises</div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-12 bg-white">
        <div class="max-w-5xl mx-auto px-6">
            <div class="text-center mb-8">
                <h2 class="text-2xl md:text-3xl font-extrabold text-corporate-dark mb-2">Votre immobilier freine-t-il votre croissance ?</h2>
                <div class="w-16 h-1 bg-gold mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <div class="bg-[#F8F9FA] p-5 rounded-xl border border-slate-100">
                    <i data-lucide="map-pin" class="text-corporate-dark w-5 h-5 mb-3"></i>
                    <h3 class="text-base font-bold text-corporate-dark mb-1">Mauvais emplacement</h3>
                    <p class="text-slate-600 text-xs leading-relaxed">Une adresse peu stratégique qui affecte votre image de marque.</p>
                </div>
                <div class="bg-[#F8F9FA] p-5 rounded-xl border border-slate-100">
                    <i data-lucide="trending-down" class="text-corporate-dark w-5 h-5 mb-3"></i>
                    <h3 class="text-base font-bold text-corporate-dark mb-1">Loyers trop élevés</h3>
                    <p class="text-slate-600 text-xs leading-relaxed">Des charges fixes disproportionnées qui pénalisent vos marges.</p>
                </div>
                <div class="bg-[#F8F9FA] p-5 rounded-xl border border-slate-100">
                    <i data-lucide="eye-off" class="text-corporate-dark w-5 h-5 mb-3"></i>
                    <h3 class="text-base font-bold text-corporate-dark mb-1">Manque de visibilité</h3>
                    <p class="text-slate-600 text-xs leading-relaxed">L'incapacité d'obtenir des locaux capables de soutenir vos ambitions.</p>
                </div>
                <div class="bg-[#F8F9FA] p-5 rounded-xl border border-slate-100">
                    <i data-lucide="lock" class="text-corporate-dark w-5 h-5 mb-3"></i>
                    <h3 class="text-base font-bold text-corporate-dark mb-1">Opportunités ratées</h3>
                    <p class="text-slate-600 text-xs leading-relaxed">Passer à côté des meilleurs actifs car ils s'échangent hors marché.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="solutions" class="py-12 bg-[#F8F9FA]">
        <div class="max-w-5xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-10 items-center">
                <div class="h-64 bg-slate-200 rounded-2xl flex items-center justify-center text-slate-400 text-sm font-medium">
                    [Image : Réunion d'affaires]
                </div>
                <div>
                    <h2 class="text-2xl md:text-3xl font-extrabold text-corporate-dark mb-4">Une stratégie pensée pour les entreprises</h2>
                    <div class="space-y-4">
                        <div class="flex gap-4">
                            <div class="flex-shrink-0 w-8 h-8 bg-corporate-dark text-white rounded-full flex items-center justify-center font-bold text-sm">1</div>
                            <div>
                                <h3 class="text-base font-bold text-corporate-dark">Analyse stratégique</h3>
                                <p class="text-slate-600 text-xs leading-relaxed">Audit de vos besoins pour aligner budget et potentiel de marché.</p>
                            </div>
                        </div>
                        <div class="flex gap-4">
                            <div class="flex-shrink-0 w-8 h-8 bg-corporate-dark text-white rounded-full flex items-center justify-center font-bold text-sm">2</div>
                            <div>
                                <h3 class="text-base font-bold text-corporate-dark">Accès off-market</h3>
                                <p class="text-slate-600 text-xs leading-relaxed">Accédez à des opportunités rares avant leur mise sur le marché public.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="formulaire" class="py-12 bg-corporate-deeper text-white">
        <div class="max-w-3xl mx-auto px-6">
            <div class="text-center mb-6">
                <h2 class="text-2xl md:text-3xl font-extrabold mb-2">Recevez nos opportunités "Off-Market"</h2>
                <p class="text-sm text-slate-300">Un consultant dédié vous contactera sous 24h.</p>
            </div>

            <form class="space-y-4 glass-card p-6 md:p-8 rounded-2xl">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-medium text-slate-200 mb-1">Nom complet *</label>
                        <input type="text" class="w-full bg-corporate-deeper/50 border border-slate-700 rounded-lg py-2.5 px-4 text-white focus:outline-none focus:border-gold transition-colors text-sm" placeholder="Ex: Karim Benjelloun" required>
                    </div>
                    <div>
                        <label class="block text-xs font-medium text-slate-200 mb-1">Nom de l'Entreprise *</label>
                        <input type="text" class="w-full bg-corporate-deeper/50 border border-slate-700 rounded-lg py-2.5 px-4 text-white focus:outline-none focus:border-gold transition-colors text-sm" placeholder="Ex: Alpha SA" required>
                    </div>
                </div>
                <div>
                    <label class="block text-xs font-medium text-slate-200 mb-1">Téléphone (WhatsApp) *</label>
                    <input type="tel" class="w-full bg-corporate-deeper/50 border border-slate-700 rounded-lg py-2.5 px-4 text-white focus:outline-none focus:border-gold transition-colors text-sm" placeholder="+212 6..." required>
                </div>
                <button type="submit" class="w-full bg-gold text-corporate-deeper font-bold px-5 py-3 rounded-lg shadow-lg hover-gold transition-all duration-300 flex items-center justify-center gap-2 text-sm">
                    Accéder aux meilleures opportunités
                    <i data-lucide="arrow-right" class="w-4 h-4"></i>
                </button>
            </form>
        </div>
    </section>

    <footer class="py-6 bg-corporate-deeper border-t border-slate-800 text-slate-500 text-xs">
        <div class="max-w-5xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center gap-4">
            <span class="font-bold text-white">COIN CARRIÈRE</span>
            <p>&copy; 2026 Coin Carrière. Tous droits réservés.</p>


        <div class="absolute inset-0 bg-corporate-deeper/90"></div>
        
        <div class="relative max-w-5xl mx-auto

    
