<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website Template</title>
    <!-- Load Tailwind CSS via CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind to use the Inter font -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light gray background */
        }
    </style>
</head>
<body class="min-h-screen flex flex-col antialiased text-gray-800">

    <!-- 1. Header (Navigation Bar) -->
    <header class="bg-white shadow-md sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Logo/Site Title -->
            <div class="text-2xl font-bold text-indigo-600">
                Project Name
            </div>
            <!-- Navigation Links (Hidden on mobile, shown on larger screens) -->
            <nav class="hidden md:flex space-x-6">
                <a href="#" class="text-gray-600 hover:text-indigo-600 transition duration-150">Home</a>
                <a href="#" class="text-gray-600 hover:text-indigo-600 transition duration-150">Features</a>
                <a href="#" class="text-gray-600 hover:text-indigo-600 transition duration-150">Pricing</a>
                <a href="#" class="text-gray-600 hover:text-indigo-600 transition duration-150">Contact</a>
            </nav>
            <!-- Mobile Menu Icon (Placeholder for functionality) -->
            <button class="md:hidden p-2 rounded-lg text-gray-600 hover:bg-gray-100">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
    </header>

    <!-- 2. Main Content Area -->
    <main class="flex-grow max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">

        <!-- Hero Section -->
        <section class="text-center mb-16 bg-white p-8 sm:p-12 rounded-xl shadow-lg border border-indigo-100">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 mb-4 leading-tight">
                Build Your Next Big Idea
            </h1>
            <p class="text-xl text-gray-500 mb-8 max-w-3xl mx-auto">
                This responsive template provides a solid foundation for any modern web project, featuring clean design and mobile-first principles.
            </p>
            <button class="px-8 py-3 bg-indigo-600 text-white font-semibold rounded-lg shadow-lg hover:bg-indigo-700 transition duration-200 transform hover:scale-[1.02] active:scale-[0.98]">
                Get Started Today
            </button>
        </section>

        <!-- Feature Cards Section -->
        <section class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
            <!-- Card 1 -->
            <div class="bg-white p-6 rounded-xl shadow-md border-t-4 border-indigo-500">
                <h3 class="text-xl font-semibold mb-3 text-indigo-600">Fully Responsive</h3>
                <p class="text-gray-600">Layouts automatically adapt to all screen sizes, from mobile phones to large desktop monitors.</p>
            </div>
            <!-- Card 2 -->
            <div class="bg-white p-6 rounded-xl shadow-md border-t-4 border-indigo-500">
                <h3 class="text-xl font-semibold mb-3 text-indigo-600">Modern Styling</h3>
                <p class="text-gray-600">Styled using Tailwind CSS for a professional, clean, and customizable aesthetic.</p>
            </div>
            <!-- Card 3 -->
            <div class="bg-white p-6 rounded-xl shadow-md border-t-4 border-indigo-500">
                <h3 class="text-xl font-semibold mb-3 text-indigo-600">Single File Simplicity</h3>
                <p class="text-gray-600">All HTML, CSS, and basic structure are contained in this one easy-to-manage file.</p>
            </div>
        </section>

        <!-- Placeholder Content Area -->
        <section class="bg-white p-8 rounded-xl shadow-lg">
            <h2 class="text-2xl font-bold mb-4 text-gray-900">Content Section Title</h2>
            <p class="text-gray-600 leading-relaxed">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </p>
            <div class="mt-6 p-4 bg-indigo-50/50 rounded-lg text-sm text-indigo-800 border border-indigo-200">
                <span class="font-medium">Pro Tip:</span> Use `md:`, `lg:`, and `xl:` prefixes in Tailwind to quickly adjust elements for different breakpoints!
            </div>
        </section>
    </main>

    <!-- 3. Footer -->
    <footer class="bg-gray-800 text-white mt-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 text-center">
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-8 mb-4 text-sm">
                <a href="#" class="hover:text-indigo-400 transition duration-150">Privacy Policy</a>
                <a href="#" class="hover:text-indigo-400 transition duration-150">Terms of Service</a>
                <a href="#" class="hover:text-indigo-400 transition duration-150">Contact Us</a>
            </div>
            <p class="text-sm text-gray-400">
                &copy; 2025 Project Name. All rights reserved.
            </p>
        </div>
    </footer>

</body>
</html>

