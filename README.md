# WEB_KPP

### Anggota Kelompok :
|             Nama              |     NRP    |
|-------------------------------|------------|
| Aisha Ayya Ratiandari         | 5027231056 |
| Aisyah Rahmasari              | 5027231072 |
| Wira Samudra Siregar          | 5027231041 |
| Muhammad Kenas                | 5027231069 |


```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-800 text-white">
    <header class="bg-gray-700 p-4 fixed w-full z-10">
        <nav class="flex justify-end">
            <a href="#home" class="mx-4 font-bold">Home</a>
            <a href="#about" class="mx-4">About Us</a>
            <a href="#works" class="mx-4">Our Works</a>
            <a href="#photos" class="mx-4">Photos</a>
        </nav>
    </header>

    <main>
        <!-- Home Section -->
        <section id="home" class="h-screen bg-cover bg-center" style="background-image: url('img/page_1.jpg');">
            <div class="flex items-center justify-center h-full bg-black bg-opacity-50">
                <div class="text-center text-white">
                    <h1 class="text-6xl font-bold mb-4">BASIC MEDIA SCHOOLING</h1>
                    <p class="text-xl max-w-3xl mx-auto">
                        Pelatihan yang dilakukan pada pengembangan skill peserta dalam bermedia informasi.
                        Di sini kita akan diajarkan mengenai dasar-dasar dari Design, Copywrite,
                        Photography, dan Website.
                    </p>
                </div>
            </div>
        </section>
        

        <!-- About Us Section -->
        <section id="about" class="py-16">
            <div class="container mx-auto relative">
                <h2 class="text-4xl font-bold mb-8 -rotate-90 absolute left-0 top-16 -translate-x-16">KELOMPOK 8</h2>
                <div class="grid grid-cols-4 gap-8 ml-20">
                    <!-- Anggota 1 -->
                    <div class="bg-gray-600 rounded-lg p-6 text-center">
                        <div class="mb-4">
                            <div class="bg-gray-400 rounded-full w-32 h-32 mx-auto"></div> <!-- image -->
                        </div>
                        <p class="text-lg font-bold mb-2">5027231056</p>
                        <h3 class="text-2xl font-bold mt-4">AISHA AYYA RATIANDARI</h3>
                        <p>Lombok</p>
                        <p class="text-sm">Membaca apa saja</p>
                    </div>
        
                    <!-- Anggota 2 -->
                    <div class="bg-gray-600 rounded-lg p-6 text-center">
                        <div class="mb-4">
                            <div class="bg-gray-400 rounded-full w-32 h-32 mx-auto"></div> <!--image -->
                        </div>
                        <p class="text-lg font-bold mb-2">5027231072</p>
                        <h3 class="text-2xl font-bold mt-4">AISYAH RAHMASARI</h3>
                        <p>Batam</p>
                        <p class="text-sm">Menonton drakor</p>
                    </div>
        
                    <!-- Anggota 3 -->
                    <div class="bg-gray-600 rounded-lg p-6 text-center">
                        <div class="mb-4">
                            <img src="img/wira.jpg" alt="Wira Samudra" class="rounded-full w-32 h-32 mx-auto">                        
                        </div>
                        <p class="text-lg font-bold mb-2">5027231041</p>
                        <h3 class="text-2xl font-bold mt-4">WIRA SAMUDRA</h3>
                        <p>Jakarta</p>
                        <p class="text-sm">Jalan-jalan</p>
                    </div>
        
                    <!-- Anggota 4 -->
                    <div class="bg-gray-600 rounded-lg p-6 text-center">
                        <div class="mb-4">
                            <img src="img/kenas.jpg" alt="Muhammad Kenas" class="rounded-full w-32 h-32 mx-auto">
                        </div>
                        <p class="text-lg font-bold mb-2">5027231069</p>
                        <h3 class="text-2xl font-bold mt-4">MUHAMMAD KENAS</h3>
                        <p>Bontang</p>
                        <p class="text-sm">Menonton drakor</p>
                    </div>
                </div>
            </div>
        </section>
        

        <!-- Our Works Section -->
        <section id="works" class="py-16 bg-gray-700">
            <div class="container mx-auto relative">
                <h2 class="text-4xl font-bold mb-8 -rotate-90 absolute left-0 top-16 -translate-x-16">OUR WORKS</h2>
                <div class="grid grid-cols-1 gap-4 ml-20">
                    <div class="bg-gray-600 h-32"></div>
                    <div class="bg-gray-600 h-32"></div>
                    <div class="bg-gray-600 h-32"></div>
                    <div class="bg-gray-600 h-32"></div>
                </div>
            </div>
        </section>

        <!-- Photos Section -->
<section id="photos" class="py-16">
    <div class="container mx-auto relative">
        <h2 class="text-4xl font-bold mb-8 -rotate-90 absolute left-0 top-16 -translate-x-7">PHOTOS</h2>
        <div class="grid grid-cols-4 gap-4 ml-20">
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (5).JPG" alt="Photo 1" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (6).JPG" alt="Photo 2" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (7).JPG" alt="Photo 3" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (8).JPG" alt="Photo 4" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (9).JPG" alt="Photo 5" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (2).JPG" alt="Photo 6" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (11).JPG" alt="Photo 7" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp2 1.jpg" alt="Photo 8" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp11 1.jpg" alt="Photo 9" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (10).jpg" alt="Photo 10" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (3).jpg" alt="Photo 11" class="w-full h-full object-cover rounded-lg">
            </div>
            <div class="bg-gray-600 h-48">
                <img src="img/kpp (4).jpg" alt="Photo 12" class="w-full h-full object-cover rounded-lg">
            </div>
        </div>
    </div>
</section>

    </main>
</body>
</html>
```
