<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Task</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 flex flex-col min-h-screen">

    <header class="bg-green-600 text-white text-center py-6">
        <h1 class="text-3xl font-bold">Welcome to Your Website Task</h1>
    </header>

    <nav class="bg-green-600 text-white py-3">
        <ul class="flex justify-center space-x-6">
            <li><a href="#" class="hover:underline">Home</a></li>
            <li><a href="#" class="hover:underline">About</a></li>
            <li><a href="#" class="hover:underline">Contact</a></li>
        </ul>
    </nav>


    <main class="flex-grow flex flex-col items-center justify-center p-6">
        <div class="grid md:grid-cols-3 gap-6 max-w-5xl">
            
            <div class="bg-white shadow-lg rounded-lg p-6">
                <h2 class="text-green-600 text-xl font-bold">About CSS</h2>
                <p class="text-gray-700 mt-2">Cascading Style Sheets (CSS) allow you to style and layout your web pages, adding colors, spacing, and more.</p>
            </div>

            <div class="bg-white shadow-lg rounded-lg p-6">
                <h2 class="text-green-600 text-xl font-bold">Responsive Design</h2>
                <p class="text-gray-700 mt-2">Responsive design ensures your webpage looks great on all devices, from desktops to mobile phones.</p>
            </div>

         
            <div class="bg-white shadow-lg rounded-lg p-6">
                <h2 class="text-green-600 text-xl font-bold">Box Model</h2>
                <p class="text-gray-700 mt-2">The CSS box model describes the rectangular boxes generated for elements. It includes margins, borders, padding, and the actual content.</p>
            </div>

        </div>
    </main>

    <footer class="bg-gray-900 text-white text-center p-4 mt-auto">
        <p>Created by [Student Name] | Follow us on 
            <a href="#" class="text-green-400 hover:underline">Instagram</a> | 
            <a href="#" class="text-green-400 hover:underline">Twitter</a> | 
            <a href="#" class="text-green-400 hover:underline">LinkedIn</a>
        </p>
    </footer>

</body>
</html>
