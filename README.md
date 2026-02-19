<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Celestial Scout Law | Constellations in the Night Sky</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --scout-blue: #003366;
            --scout-gold: #f1be48;
            --scout-light-gold: #f9e1a2;
        }
        body {
            background-color: #f8f9fa;
            color: #333;
        }
        .bg-scout-blue { background-color: var(--scout-blue); }
        .text-scout-blue { color: var(--scout-blue); }
        .bg-scout-gold { background-color: var(--scout-gold); }
        .text-scout-gold { color: var(--scout-gold); }
        .border-scout-gold { border-color: var(--scout-gold); }
        
        .hero-gradient {
            background: linear-gradient(135deg, var(--scout-blue) 0%, #001f3f 100%);
        }
        .constellation-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .sticky-header {
            position: sticky;
            top: 0;
            z-index: 50;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header class="hero-gradient text-white py-12 px-4 shadow-xl text-center border-b-4 border-scout-gold">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">The Celestial Scout Law</h1>
            <p class="text-lg md:text-xl text-scout-light-gold italic">"Look up at the stars and learn your way home."</p>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 py-8">
        
        <!-- Table Section -->
        <section class="mb-12 overflow-x-auto bg-white rounded-lg shadow-md">
            <table class="min-w-full leading-normal">
                <thead>
                    <tr class="bg-scout-blue text-white">
                        <th class="px-5 py-4 border-b-2 border-scout-gold text-left text-xs font-semibold uppercase tracking-wider">Scout Law</th>
                        <th class="px-5 py-4 border-b-2 border-scout-gold text-left text-xs font-semibold uppercase tracking-wider">Constellation</th>
                        <th class="px-5 py-4 border-b-2 border-scout-gold text-left text-xs font-semibold uppercase tracking-wider">Best Viewing</th>
                        <th class="px-5 py-4 border-b-2 border-scout-gold text-left text-xs font-semibold uppercase tracking-wider">Key Features</th>
                    </tr>
                </thead>
                <tbody class="text-sm">
                    <!-- Row 1 -->
                    <tr>
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">1. Trustworthy</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Ursa Minor</td>
                        <td class="px-5 py-4 border-b border-gray-200">Year-round</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Polaris (The North Star)</td>
                    </tr>
                    <!-- Row 2 -->
                    <tr class="bg-blue-50">
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">2. Loyal</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Canis Major</td>
                        <td class="px-5 py-4 border-b border-gray-200">Winter (Feb–Mar)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Sirius (The Dog Star)</td>
                    </tr>
                    <!-- Row 3 -->
                    <tr>
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">3. Helpful</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Sagittarius</td>
                        <td class="px-5 py-4 border-b border-gray-200">Summer (July–Aug)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">The Galactic Center</td>
                    </tr>
                    <!-- Row 4 -->
                    <tr class="bg-blue-50">
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">4. Friendly</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Gemini</td>
                        <td class="px-5 py-4 border-b border-gray-200">Winter/Spring</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Castor & Pollux</td>
                    </tr>
                    <!-- Row 5 -->
                    <tr>
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">5. Courteous</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Libra</td>
                        <td class="px-5 py-4 border-b border-gray-200">Late Spring (June)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">The Scales of Justice</td>
                    </tr>
                    <!-- Row 6 -->
                    <tr class="bg-blue-50">
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">6. Kind</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Delphinus</td>
                        <td class="px-5 py-4 border-b border-gray-200">Summer/Fall (Sept)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Diamond Shape</td>
                    </tr>
                    <!-- Row 7 -->
                    <tr>
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">7. Obedient</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Boötes</td>
                        <td class="px-5 py-4 border-b border-gray-200">Spring/Summer</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Arcturus</td>
                    </tr>
                    <!-- Row 8 -->
                    <tr class="bg-blue-50">
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">8. Cheerful</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Corona Borealis</td>
                        <td class="px-5 py-4 border-b border-gray-200">Summer (July)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Ariadne's Crown</td>
                    </tr>
                    <!-- Row 9 -->
                    <tr>
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">9. Thrifty</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Taurus</td>
                        <td class="px-5 py-4 border-b border-gray-200">Winter (Jan–Feb)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Pleiades Cluster</td>
                    </tr>
                    <!-- Row 10 -->
                    <tr class="bg-blue-50">
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">10. Brave</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Leo</td>
                        <td class="px-5 py-4 border-b border-gray-200">Spring (April)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">Regulus (Little King)</td>
                    </tr>
                    <!-- Row 11 -->
                    <tr>
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">11. Clean</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Aquarius</td>
                        <td class="px-5 py-4 border-b border-gray-200">Fall (October)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">The Helix Nebula</td>
                    </tr>
                    <!-- Row 12 -->
                    <tr class="bg-blue-50">
                        <td class="px-5 py-4 border-b border-gray-200 font-bold text-scout-blue">12. Reverent</td>
                        <td class="px-5 py-4 border-b border-gray-200 italic">Ara</td>
                        <td class="px-5 py-4 border-b border-gray-200">Summer (South)</td>
                        <td class="px-5 py-4 border-b border-gray-200 font-medium">The Altar</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Detailed Explanations Section -->
        <h2 class="text-3xl font-bold text-scout-blue mb-8 text-center border-b-2 border-scout-gold inline-block w-full pb-2">Celestial Wisdom</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            
            <!-- 1. Trustworthy -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">1. Trustworthy</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">URSA MINOR</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    For thousands of years, explorers and scouts have relied on Polaris because it is the only star that does not move. In Scouting, being trustworthy means being that same kind of "True North"—someone people can always depend on.
                </p>
            </div>

            <!-- 2. Loyal -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">2. Loyal</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">CANIS MAJOR</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    Home to Sirius (the Dog Star), this constellation represents Laelaps, the dog who never failed to catch what it was sent after. It embodies the "never-quit" loyalty to a person or a cause.
                </p>
            </div>

            <!-- 3. Helpful -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">3. Helpful</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">SAGITTARIUS</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    Identified with Chiron, the wisest and most helpful of the Centaurs. He was a teacher to heroes, known for sharing his knowledge of medicine and music to help others grow.
                </p>
            </div>

            <!-- 4. Friendly -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">4. Friendly</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">GEMINI</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    The story of Castor and Pollux is the ultimate tale of friendship. They were so inseparable they begged Zeus to remain together forever. They are the symbol of brotherhood.
                </p>
            </div>

            <!-- 5. Courteous -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">5. Courteous</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">LIBRA</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    Courteousness is about respect and balance. Libra represents the scales of justice and harmony—emphasizing the "civil" and polite nature of law and order.
                </p>
            </div>

            <!-- 6. Kind -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">6. Kind</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">DELPHINUS</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    A symbol of kindness shown to those in distress, representing the dolphin that saved the poet Arion from drowning. In mythology, the dolphin was seen as a savior.
                </p>
            </div>

            <!-- 7. Obedient -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">7. Obedient</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">BOÖTES</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    The "Herdsman" who follows the Great Bear around the North Pole. He represents the discipline of following a path and the dutiful nature of someone tending to their charges.
                </p>
            </div>

            <!-- 8. Cheerful -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">8. Cheerful</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">CORONA BOREALIS</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    The jeweled crown looks like a bright, wide smile in the sky. It serves as a reminder of the joy and celebration that follow a job well done.
                </p>
            </div>

            <!-- 9. Thrifty -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">9. Thrifty</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">TAURUS</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    Associated with the "Horn of Plenty." It represents resourcefulness—taking raw energy and turning it into a sustainable living through hard work.
                </p>
            </div>

            <!-- 10. Brave -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">10. Brave</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">LEO</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    A symbol of courage and strength. It represents the bravery required to face difficult challenges head-on without flinching.
                </p>
            </div>

            <!-- 11. Clean -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">11. Clean</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">AQUARIUS</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    Depicted as a young man pouring water from an urn. It represents the cleansing of the earth and the refreshing, purifying nature of water.
                </p>
            </div>

            <!-- 12. Reverent -->
            <div class="constellation-card bg-white p-6 rounded-lg shadow-md border-l-8 border-scout-blue">
                <div class="flex justify-between items-start mb-4">
                    <h3 class="text-xl font-bold text-scout-blue">12. Reverent</h3>
                    <span class="bg-scout-gold text-white text-xs px-2 py-1 rounded font-bold">ARA</span>
                </div>
                <p class="text-gray-700 leading-relaxed text-sm">
                    Represents the altar where the gods first made their vows. It is a symbol of devotion, solemnity, and a connection to something greater than oneself.
                </p>
            </div>

        </div>
    </main>

    <footer class="bg-scout-blue text-white py-8 mt-12 border-t-4 border-scout-gold">
        <div class="text-center">
            <p>&copy; 2024 The Celestial Scout | Stargazing the Law</p>
            <p class="text-scout-light-gold text-sm mt-2">Cub Scout Blue & Gold Edition</p>
        </div>
    </footer>

</body>
</html>
