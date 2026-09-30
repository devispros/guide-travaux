<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DevisPros & Devis Travaux Gratuit - Guide des travaux et de l'habitat</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                            800: '#065f46',
                            900: '#064e3b',
                        },
                        accent: {
                            500: '#f59e0b',
                            600: '#d97706',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .hero-pattern {
            background: linear-gradient(135deg, rgba(6, 78, 59, 0.95) 0%, rgba(4, 120, 87, 0.9) 100%), url('https://placehold.co/1920x1080/064e3b/ffffff?text=Renovation+Habitat') center/cover no-repeat;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans antialiased flex flex-col min-h-screen">

    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur shadow-sm border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-11 h-11 bg-brand-600 rounded-xl flex items-center justify-center text-white shadow-md shadow-brand-600/20 group-hover:scale-105 transition-transform">
                    <i class="fa-solid fa-house-chimney text-xl"></i>
                </div>
                <div>
                    <span class="text-xl font-extrabold tracking-tight text-gray-900 block leading-tight">Devis<span class="text-brand-600">Pros</span></span>
                    <span class="text-xs text-gray-500 font-medium tracking-wide">Guide des Travaux & Habitat</span>
                </div>
            </a>
            
            <nav class="hidden md:flex items-center gap-8 font-medium text-sm text-gray-600">
                <a href="#services" class="hover:text-brand-600 transition-colors">Nos Services</a>
                <a href="#devis-form" class="hover:text-brand-600 transition-colors">Obtenir un devis</a>
                <a href="#guides" class="hover:text-brand-600 transition-colors">Guides & Conseils</a>
                <a href="#apropos" class="hover:text-brand-600 transition-colors">À propos</a>
            </nav>

            <div class="flex items-center gap-3">
                <a href="https://www.facebook.com/devistravauxgratuit/" target="_blank" rel="noopener noreferrer" class="hidden sm:flex w-10 h-10 rounded-full bg-blue-50 text-blue-600 items-center justify-center hover:bg-blue-100 transition-colors" title="Page Facebook">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="#devis-form" class="bg-brand-600 hover:bg-brand-700 text-white px-5 py-2.5 rounded-xl font-semibold text-sm shadow-md shadow-brand-600/20 transition-all hover:shadow-lg flex items-center gap-2">
                    <i class="fa-solid fa-calculator"></i>
                    <span>Devis Gratuit</span>
                </a>
            </div>
        </div>
    </header>

    <section class="hero-pattern text-white py-20 lg:py-28 relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md px-4 py-2 rounded-full text-brand-100 text-xs font-semibold tracking-wide border border-white/20">
                        <i class="fa-solid fa-shield-check text-accent-500"></i>
                        Artisans qualifiés et vérifiés près de chez vous
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight">
                        Réalisez vos <span class="text-accent-500 underline decoration-accent-500/40">travaux</span> au meilleur prix
                    </h1>
                    <p class="text-lg text-brand-50 font-light max-w-xl leading-relaxed">
                        Bienvenue sur l'espace de ressources dédié à la rénovation, à la construction et à la recherche d'artisans qualifiés. Obtenez rapidement jusqu'à 3 devis gratuits et sans engagement.
                    </p>
                    <div class="flex flex-wrap gap-4 pt-2">
                        <div class="flex items-center gap-2 text-sm bg-black/20 px-3 py-1.5 rounded-lg">
                            <i class="fa-solid fa-check text-accent-500"></i> 100% Gratuit
                        </div>
                        <div class="flex items-center gap-2 text-sm bg-black/20 px-3 py-1.5 rounded-lg">
                            <i class="fa-solid fa-check text-accent-500"></i> Artisans locaux certifiés
                        </div>
                        <div class="flex items-center gap-2 text-sm bg-black/20 px-3 py-1.5 rounded-lg">
                            <i class="fa-solid fa-check text-accent-500"></i> Sans engagement
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-5">
                    <div class="bg-white rounded-3xl p-6 sm:p-8 shadow-2xl text-gray-800 border border-gray-100">
                        <div class="text-center mb-6">
                            <h3 class="text-2xl font-bold text-gray-900">Demande de Devis Express</h3>
                            <p class="text-xs text-gray-500 mt-1">Comparez les artisans de votre région en 2 minutes</p>
                        </div>
                        
                        <!-- Quick Quote Widget Form -->
                        <form id="hero-quote-form" onsubmit="handleQuickQuote(event)" class="space-y-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Type de travaux</label>
                                <select id="hero-service" class="w-full bg-gray-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500 focus:bg-white transition-all">
                                    <option value="renovation">Rénovation globale / intérieure</option>
                                    <option value="isolation">Isolation thermique & Énergie</option>
                                    <option value="plomberie">Plomberie & Chauffage</option>
                                    <option value="electricite">Électricité & Domotique</option>
                                    <option value="toiture">Toiture & Charpente</option>
                                    <option value="peinture">Peinture & Revêtement sols</option>
                                    <option value="autre">Autre projet</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Votre Code Postal</label>
                                <input type="text" id="hero-zip" required placeholder="ex: 75001 ou 69002" class="w-full bg-gray-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500 focus:bg-white transition-all">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Votre Email</label>
                                <input type="email" id="hero-email" required placeholder="votre.email@exemple.fr" class="w-full bg-gray-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500 focus:bg-white transition-all">
                            </div>
                            <button type="submit" class="w-full bg-brand-600 hover:bg-brand-700 text-white font-bold py-3.5 px-6 rounded-xl shadow-lg shadow-brand-600/30 transition-all flex items-center justify-center gap-2">
                                <span>Recevoir mes devis gratuits</span>
                                <i class="fa-solid fa-arrow-right"></i>
                            </button>
                            <p class="text-[11px] text-center text-gray-400 mt-2">En soumettant ce formulaire, vous acceptez d'être mis en relation avec des professionnels partenaires.</p>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-brand-900 text-white py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="space-y-1">
                    <div class="text-3xl lg:text-4xl font-extrabold text-accent-500">+ 45 000</div>
                    <div class="text-xs sm:text-sm text-brand-100 font-medium">Projets réalisés</div>
                </div>
                <div class="space-y-1">
                    <div class="text-3xl lg:text-4xl font-extrabold text-accent-500">12 000</div>
                    <div class="text-xs sm:text-sm text-brand-100 font-medium">Artisans qualifiés</div>
                </div>
                <div class="space-y-1">
                    <div class="text-3xl lg:text-4xl font-extrabold text-accent-500">98%</div>
                    <div class="text-xs sm:text-sm text-brand-100 font-medium">Clients satisfaits</div>
                </div>
                <div class="space-y-1">
                    <div class="text-3xl lg:text-4xl font-extrabold text-accent-500">Gratuit</div>
                    <div class="text-xs sm:text-sm text-brand-100 font-medium">Sans aucun engagement</div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-brand-600 font-bold uppercase tracking-widest text-xs">Nos Domaines d'Intervention</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">Trouvez l'artisan idéal pour chaque projet</h2>
                <p class="text-gray-600 mt-4 text-base">Que ce soit pour du neuf, de la rénovation énergétique ou de l'aménagement, nous référençons les meilleurs professionnels près de chez vous.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 text-2xl mb-6 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                            <i class="fa-solid fa-hammer"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Rénovation & Aménagement</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6">Rénovation complète d'appartement ou de maison, pose de cloisons, sols, carrelage et aménagement des combles.</p>
                    </div>
                    <a href="#devis-form" onclick="selectServiceOption('renovation')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                        <span>Demander un devis</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <!-- Service 2 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 text-2xl mb-6 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                            <i class="fa-solid fa-seedling"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Isolation & Énergie</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6">Isolation thermique des murs, combles, toiture et installation de pompes à chaleur éligibles aux aides de l'État (MaPrimeRénov').</p>
                    </div>
                    <a href="#devis-form" onclick="selectServiceOption('isolation')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                        <span>Demander un devis</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <!-- Service 3 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 text-2xl mb-6 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                            <i class="fa-solid fa-faucet-drip"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Plomberie & Chauffage</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6">Installation sanitaire, rénovation de salle de bains complète, pose de chaudières et systèmes de chauffage performants.</p>
                    </div>
                    <a href="#devis-form" onclick="selectServiceOption('plomberie')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                        <span>Demander un devis</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <!-- Service 4 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 text-2xl mb-6 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                            <i class="fa-solid fa-bolt"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Électricité & Domotique</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6">Mise aux normes électriques, installation de tableaux, prises, éclairages intérieurs/extérieurs et solutions connectées.</p>
                    </div>
                    <a href="#devis-form" onclick="selectServiceOption('electricite')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                        <span>Demander un devis</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <!-- Service 5 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 text-2xl mb-6 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                            <i class="fa-solid fa-house"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Toiture & Charpente</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6">Réfection de toiture, pose de tuiles, zinguerie, traitement de charpente et étanchéité par des couvreurs qualifiés.</p>
                    </div>
                    <a href="#devis-form" onclick="selectServiceOption('toiture')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                        <span>Demander un devis</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>

                <!-- Service 6 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 text-2xl mb-6 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                            <i class="fa-solid fa-paintbrush"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Peinture & Décoration</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-6">Travaux de peinture intérieure et extérieure, pose de papiers peints, enduits décoratifs et revêtements muraux.</p>
                    </div>
                    <a href="#devis-form" onclick="selectServiceOption('peinture')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                        <span>Demander un devis</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <section id="devis-form" class="py-20 bg-white border-y border-gray-100">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-brand-600 font-bold uppercase tracking-widest text-xs">Simulateur en Ligne</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">Obtenez vos devis gratuits en 3 étapes</h2>
                <p class="text-gray-600 mt-2">Remplissez notre formulaire pour être contacté par des artisans qualifiés de votre secteur.</p>
            </div>

            <div class="bg-gray-50 border border-gray-200 rounded-3xl p-6 sm:p-10 shadow-xl relative">
                <!-- Step Progress Header -->
                <div class="flex items-center justify-between mb-8 max-w-md mx-auto">
                    <div id="step-indicator-1" class="flex flex-col items-center">
                        <div class="w-10 h-10 rounded-full bg-brand-600 text-white font-bold flex items-center justify-center text-sm shadow-md">1</div>
                        <span class="text-xs font-semibold text-brand-700 mt-1">Projet</span>
                    </div>
                    <div class="flex-1 h-1 bg-gray-200 mx-2">
                        <div id="progress-bar-1" class="h-full bg-brand-600 w-0 transition-all duration-300"></div>
                    </div>
                    <div id="step-indicator-2" class="flex flex-col items-center">
                        <div class="w-10 h-10 rounded-full bg-gray-200 text-gray-500 font-bold flex items-center justify-center text-sm">2</div>
                        <span class="text-xs font-semibold text-gray-400 mt-1">Détails</span>
                    </div>
                    <div class="flex-1 h-1 bg-gray-200 mx-2">
                        <div id="progress-bar-2" class="h-full bg-brand-600 w-0 transition-all duration-300"></div>
                    </div>
                    <div id="step-indicator-3" class="flex flex-col items-center">
                        <div class="w-10 h-10 rounded-full bg-gray-200 text-gray-500 font-bold flex items-center justify-center text-sm">3</div>
                        <span class="text-xs font-semibold text-gray-400 mt-1">Contact</span>
                    </div>
                </div>

                <form id="multi-step-form" onsubmit="submitFullForm(event)">
                    <!-- Step 1: Project Type -->
                    <div id="form-step-1" class="space-y-6">
                        <h3 class="text-lg font-bold text-gray-900 text-center mb-6">Quel est la nature de votre projet ?</h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
                            <label class="cursor-pointer border-2 border-gray-200 hover:border-brand-600 bg-white p-5 rounded-2xl flex flex-col items-center text-center transition-all group">
                                <input type="radio" name="project_type" value="Rénovation intérieure" class="sr-only peer" checked>
                                <div class="w-12 h-12 rounded-xl bg-gray-50 text-gray-600 flex items-center justify-center text-xl mb-3 peer-checked:bg-brand-600 peer-checked:text-white transition-colors">
                                    <i class="fa-solid fa-house-chimney"></i>
                                </div>
                                <span class="font-bold text-gray-800 text-sm group-hover:text-brand-600">Rénovation intérieure</span>
                            </label>
                            
                            <label class="cursor-pointer border-2 border-gray-200 hover:border-brand-600 bg-white p-5 rounded-2xl flex flex-col items-center text-center transition-all group">
                                <input type="radio" name="project_type" value="Isolation & Énergie" class="sr-only peer">
                                <div class="w-12 h-12 rounded-xl bg-gray-50 text-gray-600 flex items-center justify-center text-xl mb-3 peer-checked:bg-brand-600 peer-checked:text-white transition-colors">
                                    <i class="fa-solid fa-leaf"></i>
                                </div>
                                <span class="font-bold text-gray-800 text-sm group-hover:text-brand-600">Isolation & Énergie</span>
                            </label>

                            <label class="cursor-pointer border-2 border-gray-200 hover:border-brand-600 bg-white p-5 rounded-2xl flex flex-col items-center text-center transition-all group">
                                <input type="radio" name="project_type" value="Plomberie / Chauffage" class="sr-only peer">
                                <div class="w-12 h-12 rounded-xl bg-gray-50 text-gray-600 flex items-center justify-center text-xl mb-3 peer-checked:bg-brand-600 peer-checked:text-white transition-colors">
                                    <i class="fa-solid fa-faucet"></i>
                                </div>
                                <span class="font-bold text-gray-800 text-sm group-hover:text-brand-600">Plomberie / Chauffage</span>
                            </label>

                            <label class="cursor-pointer border-2 border-gray-200 hover:border-brand-600 bg-white p-5 rounded-2xl flex flex-col items-center text-center transition-all group">
                                <input type="radio" name="project_type" value="Toiture / Façade" class="sr-only peer">
                                <div class="w-12 h-12 rounded-xl bg-gray-50 text-gray-600 flex items-center justify-center text-xl mb-3 peer-checked:bg-brand-600 peer-checked:text-white transition-colors">
                                    <i class="fa-solid fa-house"></i>
                                </div>
                                <span class="font-bold text-gray-800 text-sm group-hover:text-brand-600">Toiture / Façade</span>
                            </label>

                            <label class="cursor-pointer border-2 border-gray-200 hover:border-brand-600 bg-white p-5 rounded-2xl flex flex-col items-center text-center transition-all group">
                                <input type="radio" name="project_type" value="Électricité" class="sr-only peer">
                                <div class="w-12 h-12 rounded-xl bg-gray-50 text-gray-600 flex items-center justify-center text-xl mb-3 peer-checked:bg-brand-600 peer-checked:text-white transition-colors">
                                    <i class="fa-solid fa-bolt"></i>
                                </div>
                                <span class="font-bold text-gray-800 text-sm group-hover:text-brand-600">Électricité</span>
                            </label>

                            <label class="cursor-pointer border-2 border-gray-200 hover:border-brand-600 bg-white p-5 rounded-2xl flex flex-col items-center text-center transition-all group">
                                <input type="radio" name="project_type" value="Autre projet" class="sr-only peer">
                                <div class="w-12 h-12 rounded-xl bg-gray-50 text-gray-600 flex items-center justify-center text-xl mb-3 peer-checked:bg-brand-600 peer-checked:text-white transition-colors">
                                    <i class="fa-solid fa-toolbox"></i>
                                </div>
                                <span class="font-bold text-gray-800 text-sm group-hover:text-brand-600">Autre projet</span>
                            </label>
                        </div>
                        <div class="flex justify-end pt-4">
                            <button type="button" onclick="nextStep(2)" class="bg-brand-600 hover:bg-brand-700 text-white font-bold px-8 py-3 rounded-xl shadow-md transition-all flex items-center gap-2">
                                <span>Étape suivante</span>
                                <i class="fa-solid fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>

                    <!-- Step 2: Details & Location -->
                    <div id="form-step-2" class="space-y-6 hidden">
                        <h3 class="text-lg font-bold text-gray-900 text-center mb-6">Précisez les détails et la localisation</h3>
                        <div class="space-y-4 max-w-xl mx-auto">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-2">Description rapide de vos travaux</label>
                                <textarea rows="3" id="project-desc" placeholder="Décrivez votre besoin (surface, délai souhaité, état actuel...)" class="w-full bg-white border border-gray-300 rounded-xl p-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500"></textarea>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-2">Code Postal du chantier</label>
                                <input type="text" id="project-zip" required placeholder="ex: 69001" class="w-full bg-white border border-gray-300 rounded-xl p-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500">
                            </div>
                        </div>
                        <div class="flex justify-between pt-4 max-w-xl mx-auto">
                            <button type="button" onclick="prevStep(1)" class="bg-gray-200 hover:bg-gray-300 text-gray-700 font-bold px-6 py-3 rounded-xl transition-all">
                                <i class="fa-solid fa-arrow-left mr-2"></i> Retour
                            </button>
                            <button type="button" onclick="nextStep(3)" class="bg-brand-600 hover:bg-brand-700 text-white font-bold px-8 py-3 rounded-xl shadow-md transition-all flex items-center gap-2">
                                <span>Étape suivante</span>
                                <i class="fa-solid fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>

                    <!-- Step 3: Contact Information -->
                    <div id="form-step-3" class="space-y-6 hidden">
                        <h3 class="text-lg font-bold text-gray-900 text-center mb-6">Où souhaitez-vous recevoir vos devis ?</h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 max-w-xl mx-auto">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Prénom</label>
                                <input type="text" required placeholder="Jean" class="w-full bg-white border border-gray-300 rounded-xl p-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Nom</label>
                                <input type="text" required placeholder="Dupont" class="w-full bg-white border border-gray-300 rounded-xl p-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Email</label>
                                <input type="email" required placeholder="jean.dupont@exemple.fr" class="w-full bg-white border border-gray-300 rounded-xl p-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase tracking-wider mb-1">Téléphone</label>
                                <input type="tel" required placeholder="06 12 34 56 78" class="w-full bg-white border border-gray-300 rounded-xl p-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-500">
                            </div>
                        </div>
                        <div class="flex justify-between pt-4 max-w-xl mx-auto">
                            <button type="button" onclick="prevStep(2)" class="bg-gray-200 hover:bg-gray-300 text-gray-700 font-bold px-6 py-3 rounded-xl transition-all">
                                <i class="fa-solid fa-arrow-left mr-2"></i> Retour
                            </button>
                            <button type="submit" class="bg-brand-600 hover:bg-brand-700 text-white font-bold px-8 py-3 rounded-xl shadow-lg shadow-brand-600/30 transition-all flex items-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Valider ma demande</span>
                            </button>
                        </div>
                    </div>
                </form>

                <!-- Success Confirmation Box (Hidden by default) -->
                <div id="form-success" class="hidden text-center py-12 space-y-4">
                    <div class="w-20 h-20 bg-brand-100 text-brand-600 rounded-full flex items-center justify-center text-3xl mx-auto shadow-inner">
                        <i class="fa-solid fa-check"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-900">Demande enregistrée avec succès !</h3>
                    <p class="text-gray-600 max-w-md mx-auto text-sm">
                        Merci ! Votre projet a bien été transmis à nos artisans partenaires certifiés de votre région. Vous recevrez vos devis comparatifs sous 24h à 48h.
                    </p>
                    <button onclick="resetForm()" class="bg-brand-600 text-white font-semibold px-6 py-2.5 rounded-xl text-sm shadow hover:bg-brand-700 transition-all">
                        Effectuer une autre demande
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="guides" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12">
                <div>
                    <span class="text-brand-600 font-bold uppercase tracking-widest text-xs">Ressources & Expertise</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">Guide des travaux et de l'habitat</h2>
                </div>
                <p class="text-gray-600 mt-4 md:mt-0 max-w-md text-sm">Découvrez nos conseils d'experts pour réussir vos projets de rénovation, connaître les aides financières et bien choisir vos artisans.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Article 1 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="h-48 overflow-hidden relative">
                            <img src="https://placehold.co/600x400/064e3b/ffffff?text=Aides+Renovation" alt="Aides rénovation énergétique" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <span class="absolute top-4 left-4 bg-brand-600 text-white text-xs font-bold px-3 py-1 rounded-full shadow">Financement</span>
                        </div>
                        <div class="p-6">
                            <div class="text-xs text-gray-400 mb-2"><i class="fa-regular fa-calendar mr-1"></i> 15 Octobre 2026 • 5 min de lecture</div>
                            <h3 class="text-lg font-bold text-gray-900 mb-3 group-hover:text-brand-600 transition-colors">MaPrimeRénov' 2026 : Tout ce qui change pour vos travaux</h3>
                            <p class="text-gray-600 text-sm line-clamp-3">Guide complet sur les nouvelles conditions d'attribution, les plafonds de ressources et les démarches pour financer votre isolation et votre chauffage.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#" onclick="openArticleModal('MaPrimeRénov\' 2026', 'Guide complet sur les nouvelles conditions d\'attribution, les plafonds de ressources et les démarches pour financer votre isolation et votre chauffage.')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                            <span>Lire l'article</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Article 2 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="h-48 overflow-hidden relative">
                            <img src="https://placehold.co/600x400/047857/ffffff?text=Choix+Artisan" alt="Choisir son artisan" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <span class="absolute top-4 left-4 bg-accent-600 text-white text-xs font-bold px-3 py-1 rounded-full shadow">Conseils</span>
                        </div>
                        <div class="p-6">
                            <div class="text-xs text-gray-400 mb-2"><i class="fa-regular fa-calendar mr-1"></i> 10 Octobre 2026 • 4 min de lecture</div>
                            <h3 class="text-lg font-bold text-gray-900 mb-3 group-hover:text-brand-600 transition-colors">Comment bien choisir son artisan RGE ?</h3>
                            <p class="text-gray-600 text-sm line-clamp-3">Assurances décennale, labels de qualité, devis comparatifs : les critères indispensables pour éviter les arnaques et garantir des travaux irréprochables.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#" onclick="openArticleModal('Comment bien choisir son artisan RGE ?', 'Assurances décennale, labels de qualité, devis comparatifs : les critères indispensables pour éviter les arnaques et garantir des travaux irréprochables.')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                            <span>Lire l'article</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Article 3 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all border border-gray-100 flex flex-col justify-between group">
                    <div>
                        <div class="h-48 overflow-hidden relative">
                            <img src="https://placehold.co/600x400/065f46/ffffff?text=Isolation+Thermique" alt="Isolation thermique" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <span class="absolute top-4 left-4 bg-brand-700 text-white text-xs font-bold px-3 py-1 rounded-full shadow">Habitat</span>
                        </div>
                        <div class="p-6">
                            <div class="text-xs text-gray-400 mb-2"><i class="fa-regular fa-calendar mr-1"></i> 2 Octobre 2026 • 6 min de lecture</div>
                            <h3 class="text-lg font-bold text-gray-900 mb-3 group-hover:text-brand-600 transition-colors">Isolation thermique : par l'intérieur ou par l'extérieur ?</h3>
                            <p class="text-gray-600 text-sm line-clamp-3">Avantages, inconvénients, coûts et performances énergétiques comparés de ces deux techniques majeures de rénovation de façade et de murs.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#" onclick="openArticleModal('Isolation thermique : par l\'intérieur ou par l\'extérieur ?', 'Avantages, inconvénients, coûts et performances énergétiques comparés de ces deux techniques majeures de rénovation de façade et de murs.')" class="inline-flex items-center gap-2 text-brand-600 font-semibold text-sm hover:text-brand-700">
                            <span>Lire l'article</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="apropos" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-brand-50 rounded-3xl p-8 lg:p-12 border border-brand-100 grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <span class="text-brand-600 font-bold uppercase tracking-widest text-xs">À propos de notre réseau</span>
                    <h2 class="text-3xl font-extrabold text-gray-900">Simplifier la mise en relation entre particuliers et artisans</h2>
                    <p class="text-gray-700 leading-relaxed text-sm">
                        Bienvenue sur notre espace de ressources dédié à la rénovation, à la construction et à la recherche d'artisans qualifiés. Nous mettons tout en œuvre pour vous accompagner dans vos projets de travaux en vous offrant des conseils fiables et l'accès gratuit à un réseau de professionnels rigoureusement sélectionnés.
                    </p>
                    <div class="flex flex-wrap gap-4 pt-2">
                        <div class="flex items-center gap-3 bg-white p-3 rounded-xl shadow-sm">
                            <i class="fa-solid fa-check-circle text-brand-600 text-lg"></i>
                            <span class="text-xs font-semibold text-gray-800">Devis 100% gratuits</span>
                        </div>
                        <div class="flex items-center gap-3 bg-white p-3 rounded-xl shadow-sm">
                            <i class="fa-solid fa-check-circle text-brand-600 text-lg"></i>
                            <span class="text-xs font-semibold text-gray-800">Artisans certifiés locaux</span>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5 bg-white p-6 sm:p-8 rounded-2xl shadow-sm border border-brand-100 text-center space-y-4">
                    <div class="w-16 h-16 bg-brand-600 text-white rounded-2xl flex items-center justify-center text-2xl mx-auto shadow-md">
                        <i class="fa-solid fa-bullhorn"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900">Rejoignez notre communauté</h3>
                    <p class="text-gray-600 text-sm">Retrouvez toute notre actualité, nos astuces habitat et des témoignages clients sur notre page officielle Facebook.</p>
                    <a href="https://www.facebook.com/devistravauxgratuit/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-xl text-sm shadow-md transition-all w-full">
                        <i class="fa-brands fa-facebook-f"></i>
                        <span>Rejoindre sur Facebook</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-gray-300 pt-16 pb-12 mt-auto border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10 mb-12">
                <div class="space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 bg-brand-600 rounded-xl flex items-center justify-center text-white shadow-md">
                            <i class="fa-solid fa-house-chimney"></i>
                        </div>
                        <span class="text-xl font-extrabold text-white">Devis<span class="text-brand-500">Pros</span></span>
                    </div>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Le guide des travaux et de l'habitat. Plateforme de mise en relation gratuite pour tous vos projets de rénovation et de construction.
                    </p>
                    <div class="flex items-center gap-3 pt-2">
                        <a href="https://www.facebook.com/devistravauxgratuit/" target="_blank" rel="noopener noreferrer" class="w-9 h-9 bg-gray-800 text-white rounded-lg flex items-center justify-center hover:bg-brand-600 transition-colors">
                            <i class="fa-brands fa-facebook-f text-sm"></i>
                        </a>
                        <a href="https://www.devistravauxgratuit.com/" target="_blank" rel="noopener noreferrer" class="w-9 h-9 bg-gray-800 text-white rounded-lg flex items-center justify-center hover:bg-brand-600 transition-colors" title="Site officiel">
                            <i class="fa-solid fa-globe text-sm"></i>
                        </a>
                    </div>
                </div>

                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Liens Officiels</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li><a href="https://www.devistravauxgratuit.com" target="_blank" rel="noopener noreferrer" class="hover:text-brand-500 transition-colors">devistravauxgratuit.com</a></li>
                        <li><a href="https://www.devispros.fr" class="hover:text-brand-500 transition-colors">devispros.fr</a></li>
                        <li><a href="https://www.facebook.com/devistravauxgratuit/" target="_blank" rel="noopener noreferrer" class="hover:text-brand-500 transition-colors">Page Facebook Officielle</a></li>
                        <li><a href="#devis-form" class="hover:text-brand-500 transition-colors">Demander un Devis Gratuit</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Nos Services</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li><a href="#services" class="hover:text-brand-500 transition-colors">Rénovation Intérieure</a></li>
                        <li><a href="#services" class="hover:text-brand-500 transition-colors">Isolation & Énergie</a></li>
                        <li><a href="#services" class="hover:text-brand-500 transition-colors">Plomberie & Chauffage</a></li>
                        <li><a href="#services" class="hover:text-brand-500 transition-colors">Électricité & Domotique</a></li>
                        <li><a href="#services" class="hover:text-brand-500 transition-colors">Toiture & Charpente</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Informations Légales</h4>
                    <p class="text-xs text-gray-400 leading-relaxed mb-4">
                        Service de mise en relation gratuit et sans engagement. Les devis sont réalisés par des entreprises partenaires indépendantes.
                    </p>
                    <p class="text-xs text-gray-500">
                        © 2026 DevisPros.fr / Devis Travaux Gratuit. Tous droits réservés.
                    </p>
                </div>
            </div>

            <div class="border-t border-gray-800 pt-6 text-center text-xs text-gray-500">
                <p>Guide des travaux et de l'habitat — Retrouvez tous nos conseils et obtenez des devis gratuits auprès de professionnels locaux.</p>
            </div>
        </div>
    </footer>

    <div id="article-modal" class="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm hidden items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl relative space-y-4">
            <button onclick="closeArticleModal()" class="absolute top-4 right-4 text-gray-400 hover:text-gray-700 w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="w-12 h-12 rounded-2xl bg-brand-50 text-brand-600 flex items-center justify-center text-xl">
                <i class="fa-solid fa-book-open"></i>
            </div>
            <h3 id="modal-title" class="text-xl font-bold text-gray-900">Titre de l'article</h3>
            <p id="modal-content" class="text-gray-600 text-sm leading-relaxed">Contenu détaillé de l'article...</p>
            <div class="pt-4 flex justify-end">
                <button onclick="closeArticleModal()" class="bg-brand-600 hover:bg-brand-700 text-white text-sm font-semibold px-5 py-2 rounded-xl transition-all">
                    Fermer
                </button>
            </div>
        </div>
    </div>

    <script>
        // Multi-step form state management
        let currentStep = 1;

        function nextStep(step) {
            // Validate step 1 or 2 if needed
            if (step === 2) {
                // Step 1 selected
            }
            if (step === 3) {
                const zip = document.getElementById('project-zip').value;
                if (!zip) {
                    alertBox('Veuillez renseigner le code postal de votre chantier.');
                    return;
                }
            }
            
            document.getElementById(`form-step-${currentStep}`).classList.add('hidden');
            document.getElementById(`step-indicator-${currentStep}`).querySelector('div').className = "w-10 h-10 rounded-full bg-gray-200 text-gray-500 font-bold flex items-center justify-center text-sm";
            
            currentStep = step;
            
            document.getElementById(`form-step-${currentStep}`).classList.remove('hidden');
            document.getElementById(`step-indicator-${currentStep}`).querySelector('div').className = "w-10 h-10 rounded-full bg-brand-600 text-white font-bold flex items-center justify-center text-sm shadow-md";
            
            if (currentStep === 2) {
                document.getElementById('progress-bar-1').style.width = '100%';
            } else if (currentStep === 3) {
                document.getElementById('progress-bar-2').style.width = '100%';
            }
        }

        function prevStep(step) {
            document.getElementById(`form-step-${currentStep}`).classList.add('hidden');
            document.getElementById(`step-indicator-${currentStep}`).querySelector('div').className = "w-10 h-10 rounded-full bg-gray-200 text-gray-500 font-bold flex items-center justify-center text-sm";
            
            currentStep = step;
            
            document.getElementById(`form-step-${currentStep}`).classList.remove('hidden');
            document.getElementById(`step-indicator-${currentStep}`).querySelector('div').className = "w-10 h-10 rounded-full bg-brand-600 text-white font-bold flex items-center justify-center text-sm shadow-md";
            
            if (currentStep === 1) {
                document.getElementById('progress-bar-1').style.width = '0%';
            } else if (currentStep === 2) {
                document.getElementById('progress-bar-2').style.width = '0%';
            }
        }

        function submitFullForm(event) {
            event.preventDefault();
            document.getElementById('multi-step-form').classList.add('
