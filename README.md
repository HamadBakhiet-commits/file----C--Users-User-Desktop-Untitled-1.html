<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FreshMart Supermarket</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-green-600 text-white shadow-lg">
        <div class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center">
                    <h1 class="text-2xl font-bold">FreshMart</h1>
                    <span class="ml-2 text-sm">Supermarket</span>
                </div>
                
                <div class="flex-1 max-w-2xl mx-4">
                    <div class="relative">
                        <input type="text" placeholder="Search products..." 
                               class="w-full px-4 py-2 rounded-full text-gray-700 focus:outline-none">
                        <button class="absolute right-2 top-2 text-gray-500">
                            <i class="fas fa-search"></i>
                        </button>
                    </div>
                </div>

                <div class="flex items-center space-x-4">
                    <button class="relative">
                        <i class="fas fa-shopping-cart text-xl"></i>
                        <span class="absolute -top-2 -right-2 bg-red-500 text-white rounded-full w-5 h-5 text-xs flex items-center justify-center">3</span>
                    </button>
                    <button>
                        <i class="fas fa-user text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="bg-white shadow-md">
        <div class="container mx-auto px-4 py-3">
            <div class="flex space-x-6 overflow-x-auto">
                <a href="#" class="text-green-600 font-medium whitespace-nowrap">All Categories</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Fruits & Vegetables</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Dairy & Eggs</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Meat & Seafood</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Bakery</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Beverages</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Snacks</a>
                <a href="#" class="text-gray-600 hover:text-green-600 whitespace-nowrap">Frozen Foods</a>
            </div>
        </div>
    </nav>

    <!-- Hero Banner -->
    <div class="bg-gradient-to-r from-green-500 to-green-600 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">Fresh Groceries Delivered</h2>
            <p class="text-lg mb-6">Get 20% off your first order with code WELCOME20</p>
            <button class="bg-white text-green-600 px-6 py-3 rounded-full font-semibold hover:bg-gray-100">
                Shop Now
            </button>
        </div>
    </div>

    <!-- Featured Products -->
    <section class="container mx-auto px-4 py-8">
        <h2 class="text-2xl font-bold mb-6">Featured Products</h2>
        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-4">
            <!-- Product 1 -->
            <div class="bg-white rounded-lg shadow-md p-4 hover:shadow-lg transition-shadow">
                <img src="https://placeholder-image-service.onrender.com/image/200x200?prompt=fresh organic red apples in a basket&id=apple123" 
                     alt="Fresh organic red apples in a wooden basket with green leaves" class="w-full h-32 object-cover rounded">
                <h3 class="font-semibold mt-2">Organic Apples</h3>
                <p class="text-green-600 font-bold">$4.99/kg</p>
                <button class="mt-2 bg-green-600 text-white px-3 py-1 rounded text-sm w-full">
                    Add to Cart
                </button>
            </div>

            <!-- Product 2 -->
            <div class="bg-white rounded-lg shadow-md p-4 hover:shadow-lg transition-shadow">
                <img src="https://placeholder-image-service.onrender.com/image/200x200?prompt=fresh whole milk bottle with drops&id=milk456" 
                     alt="Glass bottle of fresh whole milk with condensation droplets" class="w-full h-32 object-cover rounded">
                <h3 class="font-semibold mt-2">Fresh Milk</h3>
                <p class="text-green-600 font-bold">$3.49</p>
                <button class="mt-2 bg-green-600 text-white px-3 py-1 rounded text-sm w-full">
                    Add to Cart
                </button>
            </div>

            <!-- Product 3 -->
            <div class="bg-white rounded-lg shadow-md p-4 hover:shadow-lg transition-shadow">
                <img src="https://placeholder-image-service.onrender.com/image/200x200?prompt=freshly baked artisan bread loaf&id=bread789" 
                     alt="Freshly baked artisan bread loaf with crisp crust on wooden board" class="w-full h-32 object-cover rounded">
                <h3 class="font-semibold mt-2">Artisan Bread</h3>
                <p class="text-green-600 font-bold">$5.99</p>
                <button class="mt-2 bg-green-600 text-white px-3 py-1 rounded text-sm w-full">
                    Add to Cart
                </button>
            </div>

            <!-- Product 4 -->
            <div class="bg-white rounded-lg shadow-md p-4 hover:shadow-lg transition-shadow">
                <img src="https://placeholder-image-service.onrender.com/image/200x200?prompt=farm fresh chicken breast&id=chicken012" 
                     alt="Fresh chicken breast fillets on butcher paper with herbs" class="w-full h-32 object-cover rounded">
                <h3 class="font-semibold mt-2">Chicken Breast</h3>
                <p class="text-green-600 font-bold">$8.99/lb</p>
                <button class="mt-2 bg-green-600 text-white px-3 py-1 rounded text-sm w-full">
                    Add to Cart
                </button>
            </div>

            <!-- Product 5 -->
            <div class="bg-white rounded-lg shadow-md p-4 hover:shadow-lg transition-shadow">
                <img src="https://placeholder-image-service.onrender.com/image/200x200?prompt=orange juice carton pouring into glass&id=juice345" 
                     alt="Carton of fresh orange juice pouring into a glass with ice cubes" class="w-full h-32 object-cover rounded">
                <h3 class="font-semibold mt-2">Orange Juice</h3>
                <p class="text-green-600 font-bold">$4.25</p>
                <button class="mt-2 bg-green-600 text-white px-3 py-1 rounded text-sm w-full">
                    Add to Cart
                </button>
            </div>
        </div>
    </section>

    <!-- Categories Section -->
    <section class="container mx-auto px-4 py-8">
        <h2 class="text-2xl font-bold mb-6">Shop by Category</h2>
        <div class="grid grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4">
            <!-- Category 1 -->
            <div class="text-center">
                <div class="bg-green-100 rounded-full p-4 w-20 h-20 mx-auto flex items-center justify-center">
                    <i class="fas fa-apple-alt text-green-600 text-2xl"></i>
                </div>
                <p class="mt-2 font-medium">Fruits & Veggies</p>
            </div>

            <!-- Category 2 -->
            <div class="text-center">
                <div class="bg-blue-100 rounded-full p-4 w-20 h-20 mx-auto flex items-center justify-center">
                    <i class="fas fa-wine-bottle text-blue-600 text-2xl"></i>
                </div>
                <p class="mt-2 font-medium">Dairy</p>
            </div>

            <!-- Category 3 -->
            <div class="text-center">
                <div class="bg-red-100 rounded-full p-4 w-20 h-20 mx-auto flex items-center justify-center">
                    <i class="fas fa-drumstick-bite text-red-600 text-2xl"></i>
                </div>
                <p class="mt-2 font-medium">Meat</p>
            </div>

            <!-- Category 4 -->
            <div class="text-center">
                <div class="bg-yellow-100 rounded-full p-4 w-20 h-20 mx-auto flex items-center justify-center">
                    <i class="fas fa-bread-slice text-yellow-600 text-2xl"></i>
                </div>
                <p class="mt-2 font-medium">Bakery</p>
            </div>

            <!-- Category 5 -->
            <div class="text-center">
                <div class="bg-purple-100 rounded-full p-4 w-20 h-20 mx-auto flex items-center justify-center">
                    <i class="fas fa-wine-glass-alt text-purple-600 text-2xl"></i>
                </div>
                <p class="mt-2 font-medium">Beverages</p>
            </div>

            <!-- Category 6 -->
            <div class="text-center">
                <div class="bg-orange-100 rounded-full p-4 w-20 h-20 mx-auto flex items-center justify-center">
                    <i class="fas fa-cookie text-orange-600 text-2xl"></i>
                </div>
                <p class="mt-2 font-medium">Snacks</p>
            </div>
        </div>
    </section>

    <!-- Weekly Specials -->
    <section class="bg-gray-100 py-8">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl font-bold mb-6">Weekly Specials</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Special 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="https://placeholder-image-service.onrender.com/image/300x200?prompt=organic avocado bundle special offer&id=avocado678" 
                         alt="Bundle of organic avocados with special offer tag and price reduction" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <h3 class="font-semibold">Organic Avocados</h3>
                            <span class="bg-red-500 text-white text-xs px-2 py-1 rounded">20% OFF</span>
                        </div>
                        <div class="flex items-center mt-1">
                            <span class="text-red-600 font-bold">$7.99</span>
                            <span class="text-gray-500 text-sm line-through ml-2">$9.99</span>
                        </div>
                        <button class="mt-3 bg-green-600 text-white px-4 py-2 rounded w-full">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <!-- Special 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="https://placeholder-image-service.onrender.com/image/300x200?prompt=premium ground coffee beans sale&id=coffee901" 
                         alt="Bag of premium ground coffee beans with sale sticker and measuring scoop" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <h3 class="font-semibold">Premium Coffee</h3>
                            <span class="bg-red-500 text-white text-xs px-2 py-1 rounded">15% OFF</span>
                        </div>
                        <div class="flex items-center mt-1">
                            <span class="text-red-600 font-bold">$12.99</span>
                            <span class="text-gray-500 text-sm line-through ml-2">$15.29</span>
                        </div>
                        <button class="mt-3 bg-green-600 text-white px-4 py-2 rounded w-full">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <!-- Special 3 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="https://placeholder-image-service.onrender.com/image/300x200?prompt=fresh salmon fillets discount&id=salmon234" 
                         alt="Fresh salmon fillets on ice with discount price label and lemon slices" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <h3 class="font-semibold">Atlantic Salmon</h3>
                            <span class="bg-red-500 text-white text-xs px-2 py-1 rounded">25% OFF</span>
                        </div>
                        <div class="flex items-center mt-1">
                            <span class="text-red-600 font-bold">$14.99/lb</span>
                            <span class="text-gray-500 text-sm line-through ml-2">$19.99/lb</span>
                        </div>
                        <button class="mt-3 bg-green-600 text-white px-4 py-2 rounded w-full">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <!-- Special 4 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="https://placeholder-image-service.onrender.com/image/300x200?prompt=artisan cheese selection special price&id=cheese567" 
                         alt="Selection of artisan cheeses on wooden board with special price tag" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <h3 class="font-semibold">Artisan Cheese</h3>
                            <span class="bg-red-500 text-white text-xs px-2 py-1 rounded">BUY 1 GET 1</span>
                        </div>
                        <div class="flex items-center mt-1">
                            <span class="text-red-600 font-bold">$8.99</span>
                            <span class="text-gray-500 text-sm line-through ml-2">$17.98</span>
                        </div>
                        <button class="mt-3 bg-green-600 text-white px-4 py-2 rounded w-full">
                            Add to Cart
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="font-bold text-lg mb-4">FreshMart</h3>
                    <p class="text-gray-400">Your neighborhood supermarket for fresh, quality groceries at great prices.</p>
                </div>
                <div>
                    <h4 class="font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white">About Us</a></li>
                        <li><a href="#" class="hover:text-white">Delivery Info</a></li>
                        <li><a href="#" class="hover:text-white">Privacy Policy</a></li>
                        <li><a href="#" class="hover:text-white">Terms of Service</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold mb-4">Customer Service</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white">Contact Us</a></li>
                        <li><a href="#" class="hover:text-white">FAQs</a></li>
                        <li><a href="#" class="hover:text-white">Returns</a></li>
                        <li><a href="#" class="hover:text-white">Support</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold mb-4">Newsletter</h4>
                    <p class="text-gray-400 mb-4">Subscribe for updates and offers</p>
                    <div class="flex">
                        <input type="email" placeholder="Your email" class="px-3 py-2 bg-gray-700 text-white rounded-l">
                        <button class="bg-green-600 px-4 py-2 rounded-r">Subscribe</button>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-6 text-center text-gray-400">
                <p>&copy; 2023 FreshMart Supermarket. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>

