<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DeviPros | Générateur de Devis & Factures pour Indépendants et TPE</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eef2ff',
                            100: '#e0e7ff',
                            500: '#6366f1',
                            600: '#4f46e5',
                            700: '#4338ca',
                            900: '#312e81',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts Inter & Lucide Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body class="bg-slate-50 text-slate-800 dark:bg-slate-950 dark:text-slate-100 font-sans antialiased transition-colors duration-300">

    <header class="sticky top-0 z-50 bg-white/80 dark:bg-slate-900/80 backdrop-blur-md border-b border-slate-200 dark:border-slate-800 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Logo -->
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-indigo-400 flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-brand-500/30">
                    DP
                </div>
                <span class="text-2xl font-extrabold bg-gradient-to-r from-brand-600 to-indigo-500 bg-clip-text text-transparent">
                    DeviPros<span class="text-xs ml-1 px-2 py-0.5 rounded-full bg-brand-100 dark:bg-brand-900/50 text-brand-700 dark:text-brand-300 font-medium">www.devipros.fr</span>
                </span>
            </div>

            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center space-x-8 font-medium text-sm">
                <a href="#features" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">Fonctionnalités</a>
                <a href="#simulator" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">Simulateur</a>
                <a href="#testimonials" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">Témoignages</a>
                <a href="#pricing" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">Tarifs</a>
                <a href="#faq" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">FAQ</a>
            </nav>

            <!-- Actions (Theme Toggle & CTA) -->
            <div class="flex items-center space-x-4">
                <button id="themeToggle" aria-label="Changer de thème" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:bg-slate-200 dark:hover:bg-slate-700 transition-all">
                    <i data-lucide="sun" class="w-5 h-5 hidden dark:block"></i>
                    <i data-lucide="moon" class="w-5 h-5 block dark:hidden"></i>
                </button>
                <a href="#pricing" class="hidden sm:inline-flex items-center justify-center px-4 py-2.5 rounded-xl border border-slate-300 dark:border-slate-700 text-sm font-semibold hover:bg-slate-100 dark:hover:bg-slate-800 transition-all">
                    Connexion
                </a>
                <a href="#simulator" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white text-sm font-semibold shadow-lg shadow-brand-600/30 transition-all transform hover:-translate-y-0.5">
                    Essai gratuit
                </a>
            </div>
        </div>
    </header>

    <section class="relative pt-20 pb-32 overflow-hidden">
        <div class="absolute inset-0 -z-10 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-brand-100/60 via-transparent to-transparent dark:from-brand-950/40"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="inline-flex items-center space-x-2 px-3.5 py-1.5 rounded-full bg-brand-50 dark:bg-brand-900/40 text-brand-700 dark:text-brand-300 text-xs font-semibold mb-8 border border-brand-200 dark:border-brand-800">
                <i data-lucide="sparkles" class="w-4 h-4 text-brand-600"></i>
                <span>La nouvelle référence pour les freelances et TPE françaises</span>
            </div>
            
            <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight max-w-4xl mx-auto leading-tight">
                Générez vos <span class="bg-gradient-to-r from-brand-600 to-indigo-500 bg-clip-text text-transparent">devis et factures</span> conformes en 2 clics.
            </h1>
            
            <p class="mt-6 text-lg sm:text-xl text-slate-600 dark:text-slate-400 max-w-2xl mx-auto font-normal">
                Piloutez votre micro-entreprise ou votre TPE sans friction. Devis pro, signature électronique légale, relances automatiques et suivi de trésorerie.
            </p>

            <div class="mt-10 flex flex-col sm:flex-row justify-center items-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="#simulator" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-semibold text-base shadow-xl shadow-brand-600/30 transition-all transform hover:-translate-y-0.5 flex items-center justify-center space-x-2">
                    <span>Créer un devis gratuit</span>
                    <i data-lucide="arrow-right" class="w-5 h-5"></i>
                </a>
                <a href="#features" class="w-full sm:w-auto px-8 py-4 rounded-xl border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800 font-semibold text-base transition-all flex items-center justify-center space-x-2">
                    <i data-lucide="play-circle" class="w-5 h-5 text-brand-600"></i>
                    <span>Voir la démo</span>
                </a>
            </div>

            <!-- Trust badges -->
            <div class="mt-16 pt-8 border-t border-slate-200 dark:border-slate-800 flex flex-wrap justify-center items-center gap-8 text-xs font-semibold text-slate-500 dark:text-slate-400">
                <div class="flex items-center space-x-2"><i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-500"></i><span>Conforme Facturation 2026</span></div>
                <div class="flex items-center space-x-2"><i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-500"></i><span>Hébergement 100% Sécurisé en France</span></div>
                <div class="flex items-center space-x-2"><i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-500"></i><span>Sans engagement • Essai 14 jours</span></div>
            </div>
        </div>
    </section>

    <section id="simulator" class="py-24 bg-white dark:bg-slate-900 border-y border-slate-200 dark:border-slate-800 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-bold tracking-tight">Simulateur de Devis Interactif</h2>
                <p class="mt-4 text-slate-600 dark:text-slate-400 text-lg">Testez instantanément la puissance et la simplicité de notre générateur de documents.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                <!-- Controls Column -->
                <div class="lg:col-span-5 bg-slate-50 dark:bg-slate-800/50 p-6 sm:p-8 rounded-2xl border border-slate-200 dark:border-slate-700 shadow-sm space-y-6">
                    <h3 class="text-xl font-bold flex items-center space-x-2">
                        <i data-lucide="sliders" class="w-5 h-5 text-brand-600"></i>
                        <span>Paramètres du Devis</span>
                    </h3>

                    <div>
                        <label class="block text-sm font-medium mb-2">Nom de votre entreprise / Freelance</label>
                        <input type="text" id="simCompany" value="Studio WebCraft" class="w-full px-4 py-3 rounded-xl border border-slate-300 dark:border-slate-600 bg-white dark:bg-slate-900 text-sm focus:ring-2 focus:ring-brand-500 focus:outline-none">
                    </div>

                    <div>
                        <label class="block text-sm font-medium mb-2">Nom du Client</label>
                        <input type="text" id="simClient" value="Entreprise Innovante SAS" class="w-full px-4 py-3 rounded-xl border border-slate-300 dark:border-slate-600 bg-white dark:bg-slate-900 text-sm focus:ring-2 focus:ring-brand-500 focus:outline-none">
                    </div>

                    <div class="grid grid-cols-2 gap-4">
                        <div>
                            <label class="block text-sm font-medium mb-2">TJM / Forfait (€)</label>
                            <input type="number" id="simPrice" value="650" class="w-full px-4 py-3 rounded-xl border border-slate-300 dark:border-slate-600 bg-white dark:bg-slate-900 text-sm focus:ring-2 focus:ring-brand-500 focus:outline-none">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-2">Quantité / Jours</label>
                            <input type="number" id="simQty" value="5" class="w-full px-4 py-3 rounded-xl border border-slate-300 dark:border-slate-600 bg-white dark:bg-slate-900 text-sm focus:ring-2 focus:ring-brand-500 focus:outline-none">
                        </div>
                    </div>

                    <div>
                        <label class="block text-sm font-medium mb-2">Taux de TVA (%)</label>
                        <select id="simTva" class="w-full px-4 py-3 rounded-xl border border-slate-300 dark:border-slate-600 bg-white dark:bg-slate-900 text-sm focus:ring-2 focus:ring-brand-500 focus:outline-none">
                            <option value="20">20% (Taux standard)</option>
                            <option value="10">10% (Taux intermédiaire)</option>
                            <option value="5.5">5.5% (Taux réduit)</option>
                            <option value="0">0% (Franchise en base de TVA)</option>
                        </select>
                    </div>

                    <button onclick="triggerNotification('Devis généré avec succès ! Prêt pour export PDF.')" class="w-full py-3.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-semibold text-sm shadow-md shadow-brand-600/30 transition-all flex items-center justify-center space-x-2">
                        <i data-lucide="download" class="w-4 h-4"></i>
                        <span>Télécharger l'aperçu PDF</span>
                    </button>
                </div>

                <!-- Preview Column -->
                <div class="lg:col-span-7 bg-white dark:bg-slate-900 p-8 sm:p-12 rounded-2xl border border-slate-200 dark:border-slate-800 shadow-xl relative overflow-hidden">
                    <div class="absolute top-4 right-4 flex items-center space-x-2">
                        <span class="inline-block w-3 h-3 rounded-full bg-emerald-500 animate-pulse"></span>
                        <span class="text-xs font-semibold text-emerald-600 dark:text-emerald-400 uppercase tracking-wider">Devis Conforme #DEV-2026-089</span>
                    </div>

                    <div class="flex justify-between items-start mb-8">
                        <div>
                            <h4 id="prevCompany" class="text-2xl font-black text-slate-900 dark:text-white">Studio WebCraft</h4>
                            <p class="text-xs text-slate-500 mt-1">12 rue de la République, 75001 Paris</p>
                            <p class="text-xs text-slate-500">SIRET : 894 123 456 00012</p>
                        </div>
                        <div class="text-right">
                            <span class="text-xl font-bold text-brand-600">DEVIS</span>
                            <p class="text-xs text-slate-500 mt-1">Date : 30/09/2026</p>
                            <p class="text-xs text-slate-500">Validité : 30 jours</p>
                        </div>
                    </div>

                    <div class="mb-8 p-4 rounded-xl bg-slate-50 dark:bg-slate-800/60 border border-slate-200 dark:border-slate-700">
                        <span class="text-xs font-semibold uppercase text-slate-400">Facturé à :</span>
                        <h5 id="prevClient" class="text-base font-bold text-slate-800 dark:text-slate-200 mt-1">Entreprise Innovante SAS</h5>
                        <p class="text-xs text-slate-500">45 avenue des Champs-Élysées, 75008 Paris</p>
                    </div>

                    <!-- Items Table -->
                    <div class="overflow-x-auto mb-8">
                        <table class="w-full text-left text-sm">
                            <thead>
                                <tr class="border-b border-slate-200 dark:border-slate-700 text-slate-400 text-xs uppercase">
                                    <th class="py-3 font-semibold">Description</th>
                                    <th class="py-3 font-semibold text-center">Qté</th>
                                    <th class="py-3 font-semibold text-right">Prix H.T.</th>
                                    <th class="py-3 font-semibold text-right">Total H.T.</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-slate-100 dark:divide-slate-800">
                                <tr>
                                    <td class="py-4 font-medium text-slate-800 dark:text-slate-200">Refonte complète UI/UX & Intégration Web Responsive</td>
                                    <td id="prevQty" class="py-4 text-center">5</td>
                                    <td id="prevUnitPrice" class="py-4 text-right">650,00 €</td>
                                    <td id="prevSubtotal" class="py-4 text-right font-semibold">3 250,00 €</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>

                    <!-- Totals Calculation -->
                    <div class="flex justify-end">
                        <div class="w-72 space-y-2 text-sm">
                            <div class="flex justify-between text-slate-600 dark:text-slate-400">
                                <span>Total H.T.</span>
                                <span id="prevTotalHt" class="font-medium">3 250,00 €</span>
                            </div>
                            <div class="flex justify-between text-slate-600 dark:text-slate-400">
                                <span id="prevTvaLabel">TVA (20%)</span>
                                <span id="prevTotalTva" class="font-medium">650,00 €</span>
                            </div>
                            <div class="flex justify-between text-lg font-extrabold pt-3 border-t border-slate-200 dark:border-slate-700 text-brand-600">
                                <span>Total T.T.C.</span>
                                <span id="prevTotalTtc">3 900,00 €</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="features" class="py-24 bg-slate-50 dark:bg-slate-950 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-20">
                <span class="text-brand-600 dark:text-brand-400 text-sm font-semibold uppercase tracking-wider">Fonctionnalités Clés</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold mt-3 tracking-tight">Tout ce dont vous avez besoin pour facturer efficacement</h2>
                <p class="mt-4 text-slate-600 dark:text-slate-400 text-lg">Conçu spécifiquement pour répondre aux exigences réglementaires françaises (Loi anti-fraude TVA, facture électronique).</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Feature 1 -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-xl transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-50 dark:bg-brand-900/50 flex items-center justify-center text-brand-600 dark:text-brand-400 mb-6 group-hover:scale-110 transition-transform">
                        <i data-lucide="file-text" class="w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Devis & Factures Pro</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Éditez des documents professionnels aux normes françaises en quelques clics avec numérotation séquentielle automatique.</p>
                </div>

                <!-- Feature 2 -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-xl transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-50 dark:bg-brand-900/50 flex items-center justify-center text-brand-600 dark:text-brand-400 mb-6 group-hover:scale-110 transition-transform">
                        <i data-lucide="users" class="w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Gestion CRM Clients</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Centralisez l'historique de vos clients, leurs coordonnées SIRET, TVA intracommunautaire et l'état de leurs règlements.</p>
                </div>

                <!-- Feature 3 -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-xl transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-50 dark:bg-brand-900/50 flex items-center justify-center text-brand-600 dark:text-brand-400 mb-6 group-hover:scale-110 transition-transform">
                        <i data-lucide="bell-ring" class="w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Relances Automatiques</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Fini les impayés ! Programmez des rappels cordiaux ou fermes automatiques pour vos factures arrivées à échéance.</p>
                </div>

                <!-- Feature 4 -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-xl transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-50 dark:bg-brand-900/50 flex items-center justify-center text-brand-600 dark:text-brand-400 mb-6 group-hover:scale-110 transition-transform">
                        <i data-lucide="pen-tool" class="w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Signature Électronique</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Faites valider vos devis en ligne instantanément par vos clients grâce à notre signature électronique sécurisée à valeur juridique.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="testimonials" class="py-24 bg-white dark:bg-slate-900 border-y border-slate-200 dark:border-slate-800 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-20">
                <span class="text-brand-600 dark:text-brand-400 text-sm font-semibold uppercase tracking-wider">Témoignages</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold mt-3 tracking-tight">Adopté par plus de 12 000 indépendants</h2>
                <p class="mt-4 text-slate-600 dark:text-slate-400 text-lg">Découvrez pourquoi freelances, consultants et artisans recommandent DeviPros au quotidien.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="p-8 rounded-2xl bg-slate-50 dark:bg-slate-800/50 border border-slate-200 dark:border-slate-700 flex flex-col justify-between">
                    <div>
                        <div class="flex text-amber-400 mb-4 space-x-1">
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                        </div>
                        <p class="text-slate-700 dark:text-slate-300 text-sm leading-relaxed">
                            "Avant DeviPros, je passais des heures sur Word et Excel. Aujourd'hui, mes devis sont envoyés et signés électroniquement en moins de 5 minutes. Un gain de temps incroyable !"
                        </p>
                    </div>
                    <div class="mt-8 flex items-center space-x-4 pt-4 border-t border-slate-200 dark:border-slate-700">
                        <div class="w-10 h-10 rounded-full bg-brand-600 text-white font-bold flex items-center justify-center text-sm">
                            SL
                        </div>
                        <div>
                            <h4 class="font-bold text-sm">Sophie Laurent</h4>
                            <p class="text-xs text-slate-500">Graphiste Freelance</p>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="p-8 rounded-2xl bg-slate-50 dark:bg-slate-800/50 border border-slate-200 dark:border-slate-700 flex flex-col justify-between">
                    <div>
                        <div class="flex text-amber-400 mb-4 space-x-1">
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                        </div>
                        <p class="text-slate-700 dark:text-slate-300 text-sm leading-relaxed">
                            "Les relances automatiques de factures ont complètement éliminé mes retards de paiement. Mes clients règlent beaucoup plus vite grâce aux liens de paiement intégrés."
                        </p>
                    </div>
                    <div class="mt-8 flex items-center space-x-4 pt-4 border-t border-slate-200 dark:border-slate-700">
                        <div class="w-10 h-10 rounded-full bg-indigo-500 text-white font-bold flex items-center justify-center text-sm">
                            TM
                        </div>
                        <div>
                            <h4 class="font-bold text-sm">Thomas Moreau</h4>
                            <p class="text-xs text-slate-500">Développeur Full-Stack</p>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 3 -->
                <div class="p-8 rounded-2xl bg-slate-50 dark:bg-slate-800/50 border border-slate-200 dark:border-slate-700 flex flex-col justify-between">
                    <div>
                        <div class="flex text-amber-400 mb-4 space-x-1">
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                            <i data-lucide="star" class="w-4 h-4 fill-current"></i>
                        </div>
                        <p class="text-slate-700 dark:text-slate-300 text-sm leading-relaxed">
                            "Interface ultra épurée et support client ultra réactif. Tout est aux normes françaises 2026, je peux me concentrer à 100% sur mon cœur de métier."
                        </p>
                    </div>
                    <div class="mt-8 flex items-center space-x-4 pt-4 border-t border-slate-200 dark:border-slate-700">
                        <div class="w-10 h-10 rounded-full bg-purple-600 text-white font-bold flex items-center justify-center text-sm">
                            CB
                        </div>
                        <div>
                            <h4 class="font-bold text-sm">Claire Bernard</h4>
                            <p class="text-xs text-slate-500">Consultante en Stratégie</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="py-24 bg-slate-50 dark:bg-slate-950 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-20">
                <span class="text-brand-600 dark:text-brand-400 text-sm font-semibold uppercase tracking-wider">Tarifs Transparents</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold mt-3 tracking-tight">Des prix simples, sans mauvaise surprise</h2>
                <p class="mt-4 text-slate-600 dark:text-slate-400 text-lg">Choisissez la formule adaptée à votre activité. Changez ou annulez à tout moment.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 items-center">
                <!-- Free Plan -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 shadow-sm">
                    <h3 class="text-xl font-bold">Découverte</h3>
                    <p class="text-slate-500 text-xs mt-1">Idéal pour débuter son activité</p>
                    <div class="my-6 flex items-baseline">
                        <span class="text-4xl font-extrabold">0 €</span>
                        <span class="text-slate-500 text-sm ml-2">/ mois</span>
                    </div>
                    <ul class="space-y-4 text-sm text-slate-600 dark:text-slate-400 mb-8">
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Jusqu'à 5 devis/factures par mois</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>1 utilisateur</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Export PDF standard</span></li>
                        <li class="flex items-center space-x-3 text-slate-300 dark:text-slate-700"><i data-lucide="x" class="w-4 h-4"></i><span>Signature électronique</span></li>
                    </ul>
                    <a href="#simulator" class="block text-center py-3 rounded-xl border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800 font-semibold text-sm transition-all">Commencer gratuit</a>
                </div>

                <!-- Pro Plan (Featured) -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border-2 border-brand-600 shadow-2xl relative">
                    <div class="absolute -top-3.5 left-1/2 transform -translate-x-1/2 px-4 py-1 rounded-full bg-brand-600 text-white text-xs font-bold uppercase tracking-wider">
                        Le plus populaire
                    </div>
                    <h3 class="text-xl font-bold">Pro Freelance</h3>
                    <p class="text-slate-500 text-xs mt-1">Pour les indépendants actifs</p>
                    <div class="my-6 flex items-baseline">
                        <span class="text-5xl font-extrabold">12 €</span>
                        <span class="text-slate-500 text-sm ml-2">/ mois H.T.</span>
                    </div>
                    <ul class="space-y-4 text-sm text-slate-600 dark:text-slate-400 mb-8">
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Devis & factures illimités</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Signature électronique illimitée</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Relances automatiques impayés</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>CRM clients & suivi de trésorerie</span></li>
                    </ul>
                    <a href="#simulator" class="block text-center py-3.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-semibold text-sm shadow-lg shadow-brand-600/30 transition-all">Essai gratuit 14 jours</a>
                </div>

                <!-- TPE Plan -->
                <div class="p-8 rounded-2xl bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 shadow-sm">
                    <h3 class="text-xl font-bold">Cabinet & TPE</h3>
                    <p class="text-slate-500 text-xs mt-1">Pour les structures en croissance</p>
                    <div class="my-6 flex items-baseline">
                        <span class="text-4xl font-extrabold">29 €</span>
                        <span class="text-slate-500 text-sm ml-2">/ mois H.T.</span>
                    </div>
                    <ul class="space-y-4 text-sm text-slate-600 dark:text-slate-400 mb-8">
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Tout du plan Pro inclus</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Jusqu'à 5 utilisateurs</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Accès expert-comptable dédié</span></li>
                        <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-brand-600"></i><span>Support prioritaire 7j/7</span></li>
                    </ul>
                    <a href="#simulator" class="block text-center py-3 rounded-xl border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800 font-semibold text-sm transition-all">Choisir TPE</a>
                </div>
            </div>
        </div>
    </section>

    <section id="faq" class="py-24 bg-white dark:bg-slate-900 border-t border-slate-200 dark:border-slate-800 transition-colors">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-brand-600 dark:text-brand-400 text-sm font-semibold uppercase tracking-wider">FAQ</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold mt-3 tracking-tight">Questions Fréquentes</h2>
            </div>

            <div class="space-y-6">
                <div class="p-6 rounded-2xl bg-slate-50 dark:bg-slate-800/50 border border-slate-200 dark:border-slate-700">
                    <h3 class="font-bold text-lg mb-2">Les devis et factures sont-ils conformes à la législation française ?</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Oui, tous les documents générés sur DeviPros respectent scrupuleusement les exigences de l'administration fiscale française, notamment en matière de numérotation séquentielle et de mentions obligatoires.</p>
                </div>

                <div class="p-6 rounded-2xl bg-slate-50 dark:bg-slate-800/50 border border-slate-200 dark:border-slate-700">
                    <h3 class="font-bold text-lg mb-2">Puis-je tester la plateforme gratuitement ?</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Absolument ! Vous bénéficiez de 14 jours d'essai gratuit sur toutes nos formules Pro sans avoir à saisir votre carte bancaire.</p>
                </div>

                <div class="p-6 rounded-2xl bg-slate-50 dark:bg-slate-800/50 border border-slate-200 dark:border-slate-700">
                    <h3 class="font-bold text-lg mb-2">Comment fonctionne la signature électronique ?</h3>
                    <p class="text-slate-600 dark:text-slate-400 text-sm leading-relaxed">Lorsque vous envoyez votre devis, votre client reçoit un lien sécurisé lui permettant de signer directement en ligne du bout du doigt ou de la souris. Vous êtes notifié instantanément.</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 py-16 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-4 gap-12 mb-12">
            <div>
                <div class="flex items-center space-x-3 mb-4">
                    <div class="w-8 h-8 rounded-lg bg-brand-600 flex items-center justify-center text-white font-bold text-lg">
                        DP
                    </div>
                    <span class="text-xl font-bold text-white">DeviPros</span>
                </div>
                <p class="text-sm leading-relaxed">La solution de facturation et devis conçue pour simplifier la vie des indépendants et TPE en France.</p>
            </div>
            <div>
                <h4 class="text-white font-semibold text-sm uppercase tracking-wider mb-4">Navigation</h4>
                <ul class="space-y-2 text-sm">
                    <li><a href="#features" class="hover:text-white transition-colors">Fonctionnalités</a></li>
                    <li><a href="#simulator" class="hover:text-white transition-colors">Simulateur</a></li>
                    <li><a href="#pricing" class="hover:text-white transition-colors">Tarifs</a></li>
                    <li><a href="#testimonials" class="hover:text-white transition-colors">Témoignages</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-semibold text-sm uppercase tracking-wider mb-4">Légal</h4>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" class="hover:text-white transition-colors">Mentions légales</a></li>
                    <li><a href="#" class="hover:text-white transition-colors">Politique de confidentialité</a></li>
                    <li><a href="#" class="hover:text-white transition-colors">Conditions Générales (CGV)</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-semibold text-sm uppercase tracking-wider mb-4">Contact</h4>
                <p class="text-sm mb-2">Support : support@devipros.fr</p>
                <p class="text-sm">www.devipros.fr • Paris, France</p>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 border-t border-slate-800 text-center text-xs">
            &copy; 2026 DeviPros (www.devipros.fr). Tous droits réservés.
        </div>
    </footer>

    <!-- Notification Toast -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-32 opacity-0 transition-all duration-300 bg-slate-900 text-white dark:bg-white dark:text-slate-900 px-6 py-4 rounded-xl shadow-2xl flex items-center space-x-3 text-sm font-semibold">
        <i data-lucide="check-circle" class="w-5 h-5 text-emerald-400"></i>
        <span id="toastMessage">Notification</span>
    </div>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Theme Toggle Logic
        const themeToggleBtn = document.getElementById('themeToggle');
        const htmlElement = document.documentElement;

        // Check stored theme or system preference
        if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
            htmlElement.classList.add('dark');
        } else {
            htmlElement.classList.remove('dark');
        }

        themeToggleBtn.addEventListener('click', () => {
            if (htmlElement.classList.contains('dark')) {
                htmlElement.classList.remove('dark');
                localStorage.theme = 'light';
            } else {
                htmlElement.classList.add('dark');
                localStorage.theme = 'dark';
            }
        });

        // Interactive Simulator Logic
        const simCompany = document.getElementById('simCompany');
        const simClient = document.getElementById('simClient');
        const simPrice = document.getElementById('simPrice');
        const simQty = document.getElementById('simQty');
        const simTva = document.getElementById('simTva');

        const prevCompany = document.getElementById('prevCompany');
        const prevClient = document.getElementById('prevClient');
        const prevQty = document.getElementById('prevQty');
        const prevUnitPrice = document.getElementById('prevUnitPrice');
        const prevSubtotal = document.getElementById('prevSubtotal');
        const prevTotalHt = document.getElementById('prevTotalHt');
        const prevTvaLabel = document.getElementById('prevTvaLabel');
        const prevTotalTva = document.getElementById('prevTotalTva');
        const prevTotalTtc = document.getElementById('prevTotalTtc');

        function updateSimulator() {
            const company = simCompany.value || 'Mon Entreprise';
            const client = simClient.value || 'Mon Client';
            const price = parseFloat(simPrice.value) || 0;
            const qty = parseFloat(simQty.value) || 0;
            const tvaRate = parseFloat(simTva.value) || 0;

            prevCompany.textContent = company;
            prevClient.textContent = client;
            prevQty.textContent = qty;
            
            const subtotal = price * qty;
            const tvaAmount = subtotal * (tvaRate / 100);
            const totalTtc = subtotal + tvaAmount;

            const formatCurrency = (val) => val.toLocaleString('fr-FR', { minimumFractionDigits: 2, maximumFractionDigits: 2 }) + ' €';

            prevUnitPrice.textContent = formatCurrency(price);
            prevSubtotal.textContent = formatCurrency(subtotal);
            prevTotalHt.textContent = formatCurrency(subtotal);
            prevTvaLabel.textContent = `TVA (${tvaRate}%)`;
            prevTotalTva.textContent = formatCurrency(tvaAmount);
            prevTotalTtc.textContent = formatCurrency(totalTtc);
        }

        [simCompany, simClient, simPrice, simQty, simTva].forEach(el => {
            el.addEventListener('input', updateSimulator);
            el.addEventListener('change', updateSimulator);
        });

        // Toast Notification Trigger
        function triggerNotification(message) {
            const toast = document.getElementById('toast');
            const toastMessage = document.getElementById('toastMessage');
            toastMessage.textContent = message;
            toast.classList.remove('translate-y-32', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-32', 'opacity-0');
            }, 3500);
        }

        // Run initial calculation
        updateSimulator();
    </script>
</body>
</html>
