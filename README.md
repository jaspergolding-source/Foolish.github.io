# <!DOCTYPE html>

# <html lang="en">

# <head>

# &nbsp;   <meta charset="UTF-8">

# &nbsp;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

# &nbsp;   <title>Foolish Ltd - Developer Profile</title>

# &nbsp;   <!-- Load Tailwind CSS -->

# &nbsp;   <script src="https://cdn.tailwindcss.com"></script>

# &nbsp;   <style>

# &nbsp;       /\* Custom styles for aesthetic background and text shadow \*/

# &nbsp;       body {

# &nbsp;           font-family: 'Inter', sans-serif;

# &nbsp;           background-color: #000000; /\* Changed to Black \*/

# &nbsp;       }

# &nbsp;       .header-cover {

# &nbsp;           background-image: url('https://placehold.co/1200x300/1E40AF/FFFFFF?text=Foolish+Ltd+Cover+Image');

# &nbsp;           background-size: cover;

# &nbsp;           background-position: center;

# &nbsp;           height: 300px;

# &nbsp;       }

# &nbsp;       .card-shadow {

# &nbsp;           box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.5), 0 4px 6px -2px rgba(0, 0, 0, 0.1); /\* Darker shadow for contrast \*/

# &nbsp;       }

# &nbsp;   </style>

# </head>

# <body>

# 

# &nbsp;   <!-- Main Container -->

# &nbsp;   <div class="min-h-screen">

# 

# &nbsp;       <!-- 1. COVER IMAGE SECTION -->

# &nbsp;       <!-- Removed rounded-b-2xl class -->

# &nbsp;       <header class="header-cover w-full mb-8 card-shadow"></header>

# 

# &nbsp;       <!-- Main Content Wrapper (Container for Profile, Bio, and GIFs) -->

# &nbsp;       <div class="container mx-auto px-4 sm:px-6 lg:px-8 -mt-24">

# &nbsp;           

# &nbsp;           <!-- Profile Picture and Name (Now left-aligned and side-by-side) -->

# &nbsp;           <div class="flex justify-start mb-12">

# &nbsp;               <div class="flex items-center space-x-6"> 

# &nbsp;                   <!-- Profile Picture (Edges are now sharp) -->

# &nbsp;                   <img 

# &nbsp;                       src="https://placehold.co/150x150/EF4444/FFFFFF?text=Logo" 

# &nbsp;                       alt="Foolish Ltd Profile Picture" 

# &nbsp;                       class="w-32 h-32 md:w-40 md:h-40 border-4 border-white object-cover card-shadow flex-shrink-0"

# &nbsp;                   >

# &nbsp;                   <!-- Text Container -->

# &nbsp;                   <div>

# &nbsp;                       <!-- Text color updated to white -->

# &nbsp;                       <h1 class="text-4xl md:text-5xl font-extrabold text-white">Foolish Ltd.</h1>

# &nbsp;                       <p class="text-xl text-gray-400 font-medium">App Development \& Digital Shenanigans</p>

# &nbsp;                   </div>

# &nbsp;               </div>

# &nbsp;           </div>

# 

# &nbsp;           <!-- 2. MAIN LAYOUT: GIFS (Left \& Right) and BIO (Center) -->

# &nbsp;           <!-- Updated grid: now uses 12 columns on large screens (lg:grid-cols-12) -->

# &nbsp;           <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">

# &nbsp;               

# &nbsp;               <!-- LEFT GIF COLUMN (Now takes up 2/12 columns on large screens) -->

# &nbsp;               <aside class="hidden lg:block space-y-6 lg:col-span-2">

# &nbsp;                   <!-- Removed bg-white, p-4, rounded-xl, and card-shadow -->

# &nbsp;                   <div class="flex flex-col items-center">

# &nbsp;                       <h3 class="text-lg font-semibold text-gray-200 mb-3">GIF Showcase</h3>

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Fun+GIF+1" 

# &nbsp;                           alt="Placeholder GIF 1" 

# &nbsp;                           class="w-full h-auto mb-4"

# &nbsp;                       >

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Cool+GIF+2" 

# &nbsp;                           alt="Placeholder GIF 2" 

# &nbsp;                           class="w-full h-auto"

# &nbsp;                       >

# &nbsp;                   </div>

# &nbsp;               </aside>

# 

# &nbsp;               <!-- CENTER BIO AND CONTENT (Now takes up 8/12 columns on large screens) -->

# &nbsp;               <main class="lg:col-span-8">

# &nbsp;                   <!-- Removed rounded-xl class to make the central column box sharp -->

# &nbsp;                   <div class="bg-white p-8 card-shadow">

# &nbsp;                       <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b-2 border-red-500 pb-2">Our Bio \& Mission</h2>

# &nbsp;                       

# &nbsp;                       <p class="text-gray-700 mb-4 leading-relaxed">

# &nbsp;                           Welcome to the digital playground of Foolish Ltd. We are a small, dynamic team focused on building innovative, fun, and slightly unconventional mobile applications. Our goal isn't just to solve problems, but to make the process engaging and memorable for both the user and ourselves. We believe that a little bit of foolishness is essential for groundbreaking design!

# &nbsp;                       </p>

# &nbsp;                       

# &nbsp;                       <p class="text-gray-700 mb-6 leading-relaxed">

# &nbsp;                           Founded in 2025, Foolish Ltd. is committed to quality code, transparent development, and a dash of delightful absurdity. We specialize in cross-platform tools and experimental UI/UX concepts.

# &nbsp;                       </p>

# 

# &nbsp;                       <div class="mt-6 border-t pt-4">

# &nbsp;                           <h3 class="text-xl font-semibold text-red-600 mb-3">Contact \& Links</h3>

# &nbsp;                           <ul class="space-y-2 text-gray-600">

# &nbsp;                               <li><strong>Email:</strong> <a href="mailto:contact@foolishltd.com" class="text-blue-600 hover:text-blue-800 transition">contact@foolishltd.com</a></li>

# &nbsp;                               <li><strong>GitHub:</strong> <a href="#" class="text-blue-600 hover:text-blue-800 transition">/foolish-ltd-dev</a></li>

# &nbsp;                               <li><strong>Current Project:</strong> <span class="font-mono bg-yellow-100 px-2 py-1 rounded-md">Project Codename: Bananapants</span></li>

# &nbsp;                           </ul>

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;               </main>

# 

# &nbsp;               <!-- RIGHT GIF COLUMN (Now takes up 2/12 columns on large screens) -->

# &nbsp;               <aside class="hidden lg:block space-y-6 lg:col-span-2">

# &nbsp;                   <!-- Removed bg-white, p-4, rounded-xl, and card-shadow -->

# &nbsp;                   <div class="flex flex-col items-center">

# &nbsp;                       <h3 class="text-lg font-semibold text-gray-200 mb-3">Dev Status</h3>

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Build+Success" 

# &nbsp;                           alt="Placeholder GIF 3" 

# &nbsp;                           class="w-full h-auto mb-4"

# &nbsp;                       >

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Coding+Cat" 

# &nbsp;                           alt="Placeholder GIF 4" 

# &nbsp;                           class="w-full h-auto"

# &nbsp;                       >

# &nbsp;                   </div>

# &nbsp;               </aside>

# 

# &nbsp;               <!-- Mobile GIF Section (Displayed below content on small screens) -->

# &nbsp;               <div class="lg:hidden mt-8 space-y-6">

# &nbsp;                   <h2 class="text-2xl font-bold text-white border-b pb-2 mb-4">Latest Visuals</h2>

# &nbsp;                   <div class="grid grid-cols-2 gap-4">

# &nbsp;                        <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Fun+GIF+1" 

# &nbsp;                           alt="Placeholder GIF 1" 

# &nbsp;                           class="w-full h-auto card-shadow"

# &nbsp;                       >

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Cool+GIF+2" 

# &nbsp;                           alt="Placeholder GIF 2" 

# &nbsp;                           class="w-full h-auto card-shadow"

# &nbsp;                       >

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Build+Success" 

# &nbsp;                           alt="Placeholder GIF 3" 

# &nbsp;                           class="w-full h-auto card-shadow"

# &nbsp;                       >

# &nbsp;                       <img 

# &nbsp;                           src="https://placehold.co/200x200/4B5563/FFFFFF?text=Coding+Cat" 

# &nbsp;                           alt="Placeholder GIF 4" 

# &nbsp;                           class="w-full h-auto card-shadow"

# &nbsp;                       >

# &nbsp;                   </div>

# &nbsp;               </div>

# 

# &nbsp;           </div>

# &nbsp;       </div>

# 

# &nbsp;       <!-- Footer -->

# &nbsp;       <footer class="mt-12 py-6 bg-gray-800 text-white">

# &nbsp;           <div class="container mx-auto px-4 text-center text-sm">

# &nbsp;               \&copy; 2025 Foolish Ltd. | All Rights Reserved.

# &nbsp;           </div>

# &nbsp;       </footer>

# &nbsp;   </div>

# 

# </body>

# </html>

# 

