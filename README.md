<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foolish Ltd - Developer Profile</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for aesthetic background and text shadow */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #000000; /* Changed to Black */
        }
        .header-cover {
            background-image: url('https://placehold.co/1200x300/1E40AF/FFFFFF?text=Foolish+Ltd+Cover+Image');
            background-size: cover;
            background-position: center;
            height: 300px;
        }
        .card-shadow {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.5), 0 4px 6px -2px rgba(0, 0, 0, 0.1); /* Darker shadow for contrast */
        }
    </style>
</head>
<body>

    <!-- Main Container -->
    <div class="min-h-screen">

        <!-- 1. COVER IMAGE SECTION -->
        <!-- Removed rounded-b-2xl class -->
        <header class="header-cover w-full mb-8 card-shadow"></header>

        <!-- Main Content Wrapper (Container for Profile, Bio, and GIFs) -->
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 -mt-24">
            
            <!-- Profile Picture and Name (Now left-aligned and side-by-side) -->
            <div class="flex justify-start mb-12">
                <div class="flex items-center space-x-6"> 
                    <!-- Profile Picture (Edges are now sharp) -->
                    <img 
                        src="https://placehold.co/150x150/EF4444/FFFFFF?text=Logo" 
                        alt="Foolish Ltd Profile Picture" 
                        class="w-32 h-32 md:w-40 md:h-40 border-4 border-white object-cover card-shadow flex-shrink-0"
                    >
                    <!-- Text Container -->
                    <div>
                        <!-- Text color updated to white -->
                        <h1 class="text-4xl md:text-5xl font-extrabold text-white">Foolish Ltd.</h1>
                        <p class="text-xl text-gray-400 font-medium">App Development & Digital Shenanigans</p>
                    </div>
                </div>
            </div>

            <!-- 2. MAIN LAYOUT: GIFS (Left & Right) and BIO (Center) -->
            <!-- Updated grid: now uses 12 columns on large screens (lg:grid-cols-12) -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                
                <!-- LEFT GIF COLUMN (Now takes up 2/12 columns on large screens) -->
                <aside class="hidden lg:block space-y-6 lg:col-span-2">
                    <!-- Removed bg-white, p-4, rounded-xl, and card-shadow -->
                    <div class="flex flex-col items-center">
                        <h3 class="text-lg font-semibold text-gray-200 mb-3">GIF Showcase</h3>
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Fun+GIF+1" 
                            alt="Placeholder GIF 1" 
                            class="w-full h-auto mb-4"
                        >
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Cool+GIF+2" 
                            alt="Placeholder GIF 2" 
                            class="w-full h-auto"
                        >
                    </div>
                </aside>

                <!-- CENTER BIO AND CONTENT (Now takes up 8/12 columns on large screens) -->
                <main class="lg:col-span-8">
                    <!-- Removed rounded-xl class to make the central column box sharp -->
                    <div class="bg-white p-8 card-shadow">
                        <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b-2 border-red-500 pb-2">Our Bio & Mission</h2>
                        
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            Welcome to the digital playground of Foolish Ltd. We are a small, dynamic team focused on building innovative, fun, and slightly unconventional mobile applications. Our goal isn't just to solve problems, but to make the process engaging and memorable for both the user and ourselves. We believe that a little bit of foolishness is essential for groundbreaking design!
                        </p>
                        
                        <p class="text-gray-700 mb-6 leading-relaxed">
                            Founded in 2025, Foolish Ltd. is committed to quality code, transparent development, and a dash of delightful absurdity. We specialize in cross-platform tools and experimental UI/UX concepts.
                        </p>

                        <div class="mt-6 border-t pt-4">
                            <h3 class="text-xl font-semibold text-red-600 mb-3">Contact & Links</h3>
                            <ul class="space-y-2 text-gray-600">
                                <li><strong>Email:</strong> <a href="mailto:contact@foolishltd.com" class="text-blue-600 hover:text-blue-800 transition">contact@foolishltd.com</a></li>
                                <li><strong>GitHub:</strong> <a href="#" class="text-blue-600 hover:text-blue-800 transition">/foolish-ltd-dev</a></li>
                                <li><strong>Current Project:</strong> <span class="font-mono bg-yellow-100 px-2 py-1 rounded-md">Project Codename: Bananapants</span></li>
                            </ul>
                        </div>
                    </div>
                </main>

                <!-- RIGHT GIF COLUMN (Now takes up 2/12 columns on large screens) -->
                <aside class="hidden lg:block space-y-6 lg:col-span-2">
                    <!-- Removed bg-white, p-4, rounded-xl, and card-shadow -->
                    <div class="flex flex-col items-center">
                        <h3 class="text-lg font-semibold text-gray-200 mb-3">Dev Status</h3>
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Build+Success" 
                            alt="Placeholder GIF 3" 
                            class="w-full h-auto mb-4"
                        >
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Coding+Cat" 
                            alt="Placeholder GIF 4" 
                            class="w-full h-auto"
                        >
                    </div>
                </aside>

                <!-- Mobile GIF Section (Displayed below content on small screens) -->
                <div class="lg:hidden mt-8 space-y-6">
                    <h2 class="text-2xl font-bold text-white border-b pb-2 mb-4">Latest Visuals</h2>
                    <div class="grid grid-cols-2 gap-4">
                         <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Fun+GIF+1" 
                            alt="Placeholder GIF 1" 
                            class="w-full h-auto card-shadow"
                        >
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Cool+GIF+2" 
                            alt="Placeholder GIF 2" 
                            class="w-full h-auto card-shadow"
                        >
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Build+Success" 
                            alt="Placeholder GIF 3" 
                            class="w-full h-auto card-shadow"
                        >
                        <img 
                            src="https://placehold.co/200x200/4B5563/FFFFFF?text=Coding+Cat" 
                            alt="Placeholder GIF 4" 
                            class="w-full h-auto card-shadow"
                        >
                    </div>
                </div>

            </div>
        </div>

        <!-- Footer -->
        <footer class="mt-12 py-6 bg-gray-800 text-white">
            <div class="container mx-auto px-4 text-center text-sm">
                &copy; 2025 Foolish Ltd. | All Rights Reserved.
            </div>
        </footer>
    </div>

</body>
</html>
