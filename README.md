<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Product Showcase</title>

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100">

    <!-- Header -->
    <header class="bg-blue-600 text-white p-5">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row 
                    justify-between items-center gap-3">

            <h1 class="text-2xl font-bold">
                Product Showcase
            </h1>

            <nav class="flex gap-5">
                <a href="#" class="hover:text-gray-200">Home</a>
                <a href="#" class="hover:text-gray-200">Products</a>
                <a href="#" class="hover:text-gray-200">Contact</a>
            </nav>

        </div>
    </header>


    <!-- Main Section -->
    <main class="max-w-6xl mx-auto p-6">

        <h2 class="text-3xl font-bold text-center text-gray-800 mb-8">
            Our Products
        </h2>

        <!-- Product Container -->
        <div class="flex flex-col md:flex-row 
                    flex-wrap justify-center items-stretch gap-6">

            <!-- Product 1 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden
                        w-full md:w-[30%] hover:scale-105 
                        transition-transform">

                <img src="https://images.unsplash.com/photo-1592899677977-9c10ca588bbd?auto=format&fit=crop&w=600&q=80"
                     alt="Smartphone"
                     class="w-full h-52 object-cover">

                <div class="p-5">

                    <h3 class="text-xl font-bold text-gray-800 mb-2">
                        Smartphone
                    </h3>

                    <p class="text-gray-600 mb-4">
                        Modern smartphone with a powerful processor,
                        excellent camera and long-lasting battery.
                    </p>

                    <div class="flex justify-between items-center">
                        <span class="text-xl font-bold text-blue-600">
                            ₹25,999
                        </span>

                        <button class="bg-blue-600 text-white px-4 py-2
                                       rounded hover:bg-blue-700">
                            Buy Now
                        </button>
                    </div>

                </div>
            </div>


            <!-- Product 2 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden
                        w-full md:w-[30%] hover:scale-105 
                        transition-transform">

                <img src="https://images.unsplash.com/photo-1546435770-a3e426bf472b?auto=format&fit=crop&w=600&q=80"
                     alt="Headphones"
                     class="w-full h-52 object-cover">

                <div class="p-5">

                    <h3 class="text-xl font-bold text-gray-800 mb-2">
                        Wireless Headphones
                    </h3>

                    <p class="text-gray-600 mb-4">
                        Enjoy high-quality sound with comfortable
                        wireless headphones and noise cancellation.
                    </p>

                    <div class="flex justify-between items-center">
                        <span class="text-xl font-bold text-blue-600">
                            ₹3,999
                        </span>

                        <button class="bg-blue-600 text-white px-4 py-2
                                       rounded hover:bg-blue-700">
                            Buy Now
                        </button>
                    </div>

                </div>
            </div>


            <!-- Product 3 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden
                        w-full md:w-[30%] hover:scale-105 
                        transition-transform">

                <img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=600&q=80"
                     alt="Laptop"
                     class="w-full h-52 object-cover">

                <div class="p-5">

                    <h3 class="text-xl font-bold text-gray-800 mb-2">
                        Laptop
                    </h3>

                    <p class="text-gray-600 mb-4">
                        Powerful and lightweight laptop suitable for
                        students, professionals and daily work.
                    </p>

                    <div class="flex justify-between items-center">
                        <span class="text-xl font-bold text-blue-600">
                            ₹54,999
                        </span>

                        <button class="bg-blue-600 text-white px-4 py-2
                                       rounded hover:bg-blue-700">
                            Buy Now
                        </button>
                    </div>

                </div>
            </div>

        </div>
    </main>


    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center p-5 mt-10">
        <p>
            © 2026 Product Showcase. All Rights Reserved.
        </p>
    </footer>

</body>
</html>
