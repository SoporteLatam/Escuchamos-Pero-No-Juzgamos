<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Apoyo Emocional | Tu espacio seguro</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#57b5e7',secondary:'#8dd3c7'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Montserrat', sans-serif;
}
.modal {
transition: opacity 0.3s ease, visibility 0.3s ease;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
-webkit-appearance: none;
margin: 0;
}
input[type="number"] {
-moz-appearance: textfield;
}
.custom-checkbox {
position: relative;
cursor: pointer;
}
.custom-checkbox input {
position: absolute;
opacity: 0;
cursor: pointer;
}
.checkmark {
position: absolute;
top: 0;
left: 0;
height: 20px;
width: 20px;
border: 2px solid #ccc;
border-radius: 4px;
transition: all 0.2s ease;
}
.custom-checkbox input:checked ~ .checkmark {
background-color: #57b5e7;
border-color: #57b5e7;
}
.checkmark:after {
content: "";
position: absolute;
display: none;
}
.custom-checkbox input:checked ~ .checkmark:after {
display: block;
}
.custom-checkbox .checkmark:after {
left: 6px;
top: 2px;
width: 5px;
height: 10px;
border: solid white;
border-width: 0 2px 2px 0;
transform: rotate(45deg);
}
</style>
</head>
<body class="bg-gray-50">
<!-- Header -->
<header class="bg-white shadow-sm sticky top-0 z-50">
<div class="container mx-auto px-4 py-4 flex justify-between items-center">
<a href="#" class="text-3xl font-['Pacifico'] text-primary">Escucha</a>
<nav class="hidden md:flex space-x-8">
<a href="#" class="text-gray-700 hover:text-primary font-medium">Inicio</a>
<a href="#servicios" class="text-gray-700 hover:text-primary font-medium">Servicios</a>
<a href="#contacto" class="text-gray-700 hover:text-primary font-medium">Contacto</a>
<a href="#donaciones" class="text-gray-700 hover:text-primary font-medium">Donaciones</a>
</nav>
<div class="flex items-center space-x-4">
<a href="#contacto" class="bg-primary text-white px-6 py-2 !rounded-button font-medium shadow-sm hover:bg-opacity-90 transition whitespace-nowrap">Necesito ayuda</a>
<button id="login-button" class="bg-white text-primary border border-primary px-6 py-2 !rounded-button font-medium shadow-sm hover:bg-gray-50 transition whitespace-nowrap cursor-pointer">Iniciar sesión</button>
<button class="md:hidden w-10 h-10 flex items-center justify-center text-gray-700">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</div>
</header>
<!-- Hero Section -->
<section class="relative w-full overflow-hidden" style="background-image: url('https://public.readdy.ai/ai/img_res/a3073a2e283bc71e5c517f598ca7532e.jpg'); background-size: cover; background-position: center;">
<div class="absolute inset-0 bg-gradient-to-r from-white via-white/90 to-transparent"></div>
<div class="container mx-auto px-4 py-20 md:py-32 relative">
<div class="max-w-2xl">
<h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-6">Un espacio seguro para compartir y sanar</h1>
<p class="text-lg md:text-xl text-gray-600 mb-8">Estamos aquí para escucharte, apoyarte y acompañarte en tu camino. Porque todos merecemos ser escuchados y comprendidos.</p>
<div class="flex flex-col sm:flex-row gap-4">
<a href="#contacto" class="bg-primary text-white px-8 py-3 !rounded-button font-medium text-center shadow-md hover:bg-opacity-90 transition whitespace-nowrap">Habla con nosotros</a>
<a href="#servicios" class="bg-white text-primary border border-primary px-8 py-3 !rounded-button font-medium text-center shadow-sm hover:bg-gray-50 transition whitespace-nowrap">Conoce nuestros servicios</a>
</div>
</div>
</div>
</section>
<!-- Services Section -->
<section id="servicios" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-800 mb-4">¿Cómo podemos ayudarte?</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Ofrecemos diferentes servicios adaptados a tus necesidades. Nuestro equipo de profesionales está preparado para brindarte el apoyo que necesitas.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="bg-gray-50 rounded p-8 shadow-sm hover:shadow-md transition">
<div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-full mb-6">
<i class="ri-message-3-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-800 mb-3">Apoyo emocional</h3>
<p class="text-gray-600 mb-4">Un espacio seguro donde puedes expresar tus emociones y recibir apoyo sin juicios.</p>
<a href="#contacto" class="text-primary font-medium flex items-center">
Solicitar apoyo
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
<div class="bg-gray-50 rounded p-8 shadow-sm hover:shadow-md transition">
<div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-full mb-6">
<i class="ri-user-heart-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-800 mb-3">Asesoramiento personal</h3>
<p class="text-gray-600 mb-4">Orientación personalizada para ayudarte a superar obstáculos y alcanzar tus metas.</p>
<a href="#contacto" class="text-primary font-medium flex items-center">
Solicitar asesoramiento
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
<div class="bg-gray-50 rounded p-8 shadow-sm hover:shadow-md transition">
<div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-full mb-6">
<i class="ri-group-line ri-xl text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-800 mb-3">Grupos de apoyo</h3>
<p class="text-gray-600 mb-4">Conecta con personas que están pasando por situaciones similares y comparte experiencias.</p>
<a href="#contacto" class="text-primary font-medium flex items-center">
Unirse a un grupo
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
</div>
</section>
<!-- Contact Form Section -->
<section id="contacto" class="py-16 bg-gray-50">
<div class="container mx-auto px-4">
<div class="max-w-4xl mx-auto bg-white rounded-lg shadow-md overflow-hidden">
<div class="md:flex">
<div class="md:w-1/2 p-8 md:p-12 bg-primary">
<h2 class="text-2xl font-bold text-white mb-6">Estamos aquí para escucharte</h2>
<p class="text-white/90 mb-8">Cuéntanos tu situación y nos pondremos en contacto contigo lo antes posible. Tu información será tratada con total confidencialidad.</p>
<div class="space-y-6 text-white/90">
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center mr-4 mt-1">
<i class="ri-mail-line ri-lg"></i>
</div>
<div>
<h3 class="font-medium text-white">Correo electrónico</h3>
<p>contacto@escucha.org</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center mr-4 mt-1">
<i class="ri-phone-line ri-lg"></i>
</div>
<div>
<h3 class="font-medium text-white">Teléfono</h3>
<p>+34 912 345 678</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center mr-4 mt-1">
<i class="ri-time-line ri-lg"></i>
</div>
<div>
<h3 class="font-medium text-white">Horario de atención</h3>
<p>Lunes a viernes: 9:00 - 20:00<br>Sábados: 10:00 - 14:00</p>
</div>
</div>
</div>
</div>
<div class="md:w-1/2 p-8 md:p-12">
<h3 class="text-xl font-semibold text-gray-800 mb-6">Formulario de contacto</h3>
<form id="contact-form">
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="nombre">Nombre completo</label>
<input type="text" id="nombre" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="email">Correo electrónico</label>
<input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="telefono">Teléfono (opcional)</label>
<input type="tel" id="telefono" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary">
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="servicio">Tipo de ayuda que necesitas</label>
<div class="relative">
<select id="servicio" class="w-full px-4 py-2 border border-gray-300 rounded appearance-none focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary pr-8">
<option value="">Selecciona una opción</option>
<option value="apoyo-emocional">Apoyo emocional</option>
<option value="asesoramiento">Asesoramiento personal</option>
<option value="grupo">Grupo de apoyo</option>
<option value="otro">Otro</option>
</select>
<div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none">
<i class="ri-arrow-down-s-line text-gray-400"></i>
</div>
</div>
</div>
<div class="mb-6">
<label class="block text-gray-700 text-sm font-medium mb-2" for="mensaje">Cuéntanos tu situación</label>
<textarea id="mensaje" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required></textarea>
</div>
<button type="submit" class="w-full bg-primary text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition whitespace-nowrap">Enviar mensaje</button>
</form>
</div>
</div>
</div>
</div>
</section>
<!-- Donations Section -->
<section id="donaciones" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-800 mb-4">Ayúdanos a seguir ayudando</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Tu donación nos permite continuar brindando apoyo a quienes más lo necesitan. Cada contribución marca la diferencia en la vida de muchas personas.</p>
</div>
<div class="max-w-4xl mx-auto">
<div class="bg-gray-50 rounded-lg p-8 shadow-sm">
<h3 class="text-xl font-semibold text-gray-800 mb-6">Selecciona un método de pago</h3>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 mb-8">
<button class="payment-method bg-white border border-gray-200 rounded p-4 text-center hover:border-primary transition flex flex-col items-center justify-center h-32" data-method="binance">
<div class="w-12 h-12 flex items-center justify-center mb-3">
<i class="ri-binance-fill ri-2x text-[#F3BA2F]"></i>
</div>
<span class="font-medium text-gray-700">Binance</span>
</button>
<button class="payment-method bg-white border border-gray-200 rounded p-4 text-center hover:border-primary transition flex flex-col items-center justify-center h-32" data-method="paypal">
<div class="w-12 h-12 flex items-center justify-center mb-3">
<i class="ri-paypal-fill ri-2x text-[#003087]"></i>
</div>
<span class="font-medium text-gray-700">PayPal</span>
</button>
<button class="payment-method bg-white border border-gray-200 rounded p-4 text-center hover:border-primary transition flex flex-col items-center justify-center h-32" data-method="mercadopago">
<div class="w-12 h-12 flex items-center justify-center mb-3">
<i class="ri-shopping-bag-fill ri-2x text-[#009EE3]"></i>
</div>
<span class="font-medium text-gray-700">Mercado Pago</span>
</button>
<button class="payment-method bg-white border border-gray-200 rounded p-4 text-center hover:border-primary transition flex flex-col items-center justify-center h-32" data-method="card">
<div class="w-12 h-12 flex items-center justify-center mb-3">
<i class="ri-bank-card-fill ri-2x text-gray-700"></i>
</div>
<span class="font-medium text-gray-700">Tarjeta bancaria</span>
</button>
</div>
<!-- Payment Forms Container -->
<div id="payment-forms" class="mb-6">
<!-- Binance Form (Hidden by default) -->
<div id="binance-form" class="payment-form hidden">
<div class="bg-white border border-gray-200 rounded-lg p-6 text-center">
<h4 class="text-lg font-medium text-gray-800 mb-4">Escanea el código QR o copia la dirección</h4>
<div class="max-w-xs mx-auto mb-4">
<img src="https://public.readdy.ai/ai/img_res/a7e57a9d23856079624b711a20246155.jpg" alt="Código QR Binance" class="w-full">
</div>
<div class="flex items-center justify-center mb-4">
<input type="text" value="0x1a2b3c4d5e6f7g8h9i0j1k2l3m4n5o6p7q8r9s0t" class="bg-gray-50 border border-gray-200 rounded py-2 px-4 text-sm text-gray-700 flex-grow max-w-md" readonly>
<button class="ml-2 bg-gray-100 hover:bg-gray-200 text-gray-700 p-2 rounded !rounded-button whitespace-nowrap">
<i class="ri-file-copy-line"></i>
</button>
</div>
<p class="text-sm text-gray-600">Envía USDT a esta dirección (red BEP20)</p>
</div>
</div>
<!-- PayPal Form (Hidden by default) -->
<div id="paypal-form" class="payment-form hidden">
<div class="bg-white border border-gray-200 rounded-lg p-6">
<h4 class="text-lg font-medium text-gray-800 mb-4">Donación con PayPal</h4>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2">Monto a donar</label>
<div class="flex">
<span class="inline-flex items-center px-3 border border-r-0 border-gray-300 bg-gray-50 text-gray-500 rounded-l">€</span>
<input type="number" class="w-full border border-gray-300 rounded-r py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="25">
</div>
</div>
<button class="w-full bg-[#003087] text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition flex items-center justify-center whitespace-nowrap">
<i class="ri-paypal-fill mr-2"></i>
Donar con PayPal
</button>
</div>
</div>
<!-- Mercado Pago Form (Hidden by default) -->
<div id="mercadopago-form" class="payment-form hidden">
<div class="bg-white border border-gray-200 rounded-lg p-6">
<h4 class="text-lg font-medium text-gray-800 mb-4">Donación con Mercado Pago</h4>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2">Monto a donar</label>
<div class="flex">
<span class="inline-flex items-center px-3 border border-r-0 border-gray-300 bg-gray-50 text-gray-500 rounded-l">€</span>
<input type="number" class="w-full border border-gray-300 rounded-r py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="25">
</div>
</div>
<button class="w-full bg-[#009EE3] text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition flex items-center justify-center whitespace-nowrap">
<i class="ri-shopping-bag-fill mr-2"></i>
Donar con Mercado Pago
</button>
</div>
</div>
<!-- Card Form (Hidden by default) -->
<div id="card-form" class="payment-form hidden">
<div class="bg-white border border-gray-200 rounded-lg p-6">
<h4 class="text-lg font-medium text-gray-800 mb-4">Donación con tarjeta bancaria</h4>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2">Monto a donar</label>
<div class="flex">
<span class="inline-flex items-center px-3 border border-r-0 border-gray-300 bg-gray-50 text-gray-500 rounded-l">€</span>
<input type="number" class="w-full border border-gray-300 rounded-r py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="25">
</div>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2">Nombre del titular</label>
<input type="text" class="w-full border border-gray-300 rounded py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="Nombre como aparece en la tarjeta">
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2">Número de tarjeta</label>
<input type="text" class="w-full border border-gray-300 rounded py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="1234 5678 9012 3456">
</div>
<div class="grid grid-cols-2 gap-4 mb-4">
<div>
<label class="block text-gray-700 text-sm font-medium mb-2">Fecha de vencimiento</label>
<input type="text" class="w-full border border-gray-300 rounded py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="MM/AA">
</div>
<div>
<label class="block text-gray-700 text-sm font-medium mb-2">Código de seguridad</label>
<input type="text" class="w-full border border-gray-300 rounded py-2 px-4 focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" placeholder="CVV">
</div>
</div>
</div>
</div>
</div>
<div class="mb-6 flex items-start">
<label class="custom-checkbox flex items-start">
<input type="checkbox" class="hidden" id="terms-checkbox">
<span class="checkmark"></span>
<span class="ml-7 text-sm text-gray-600">Acepto los <a href="#" class="text-primary">términos y condiciones</a> y la <a href="#" class="text-primary">política de privacidad</a></span>
</label>
</div>
<button id="complete-donation" class="w-full bg-gray-300 text-white py-3 !rounded-button font-medium transition cursor-not-allowed whitespace-nowrap" disabled>Completar donación</button>
</div>
</div>
</div>
</section>
<!-- Testimonials Section -->
<section class="py-16 bg-gray-50">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-800 mb-4">Lo que dicen nuestros usuarios</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Estas son algunas experiencias de personas que han encontrado apoyo en nuestra plataforma.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
<div class="bg-white p-6 rounded-lg shadow-sm">
<div class="flex items-center mb-4">
<div class="text-primary">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
</div>
<p class="text-gray-600 mb-6">"Encontré un espacio donde pude expresar mis sentimientos sin miedo a ser juzgado. El apoyo que recibí fue fundamental para superar un momento muy difícil en mi vida."</p>
<div class="flex items-center">
<div class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center mr-3">
<span class="text-primary font-medium">MG</span>
</div>
<div>
<h4 class="font-medium text-gray-800">Miguel García</h4>
<p class="text-sm text-gray-500">Madrid</p>
</div>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-sm">
<div class="flex items-center mb-4">
<div class="text-primary">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
</div>
<p class="text-gray-600 mb-6">"Los grupos de apoyo me ayudaron a entender que no estaba sola en mi situación. Conectar con personas que pasaban por lo mismo fue terapéutico y reconfortante."</p>
<div class="flex items-center">
<div class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center mr-3">
<span class="text-primary font-medium">LR</span>
</div>
<div>
<h4 class="font-medium text-gray-800">Laura Rodríguez</h4>
<p class="text-sm text-gray-500">Barcelona</p>
</div>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-sm">
<div class="flex items-center mb-4">
<div class="text-primary">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
</div>
<p class="text-gray-600 mb-6">"El asesoramiento que recibí me dio herramientas prácticas para afrontar mis problemas de ansiedad. Ahora tengo estrategias que me ayudan en mi día a día."</p>
<div class="flex items-center">
<div class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center mr-3">
<span class="text-primary font-medium">CP</span>
</div>
<div>
<h4 class="font-medium text-gray-800">Carlos Pérez</h4>
<p class="text-sm text-gray-500">Valencia</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-gray-800 text-white py-12">
<div class="container mx-auto px-4">
<div class="grid grid-cols-1 md:grid-cols-4 gap-8">
<div>
<a href="#" class="text-3xl font-['Pacifico'] text-white mb-4 block">Escucha</a>
<p class="text-gray-300 mb-6">Un espacio seguro donde encontrarás apoyo emocional y consejos para mejorar tu bienestar.</p>
<div class="flex space-x-4">
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
<i class="ri-facebook-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
<i class="ri-twitter-x-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
<i class="ri-instagram-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
<i class="ri-linkedin-fill"></i>
</a>
</div>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Enlaces rápidos</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-300 hover:text-white transition">Inicio</a></li>
<li><a href="#servicios" class="text-gray-300 hover:text-white transition">Servicios</a></li>
<li><a href="#contacto" class="text-gray-300 hover:text-white transition">Contacto</a></li>
<li><a href="#donaciones" class="text-gray-300 hover:text-white transition">Donaciones</a></li>
<li><a href="#" class="text-gray-300 hover:text-white transition">Blog</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Servicios</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-300 hover:text-white transition">Apoyo emocional</a></li>
<li><a href="#" class="text-gray-300 hover:text-white transition">Asesoramiento personal</a></li>
<li><a href="#" class="text-gray-300 hover:text-white transition">Grupos de apoyo</a></li>
<li><a href="#" class="text-gray-300 hover:text-white transition">Recursos gratuitos</a></li>
<li><a href="#" class="text-gray-300 hover:text-white transition">Talleres</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Contacto</h3>
<ul class="space-y-4">
<li class="flex">
<div class="w-6 h-6 flex items-center justify-center mr-3 mt-1">
<i class="ri-map-pin-line"></i>
</div>
<span class="text-gray-300">Calle Ejemplo 123, 28001<br>Madrid, España</span>
</li>
<li class="flex">
<div class="w-6 h-6 flex items-center justify-center mr-3">
<i class="ri-mail-line"></i>
</div>
<a href="mailto:contacto@escucha.org" class="text-gray-300 hover:text-white transition">contacto@escucha.org</a>
</li>
<li class="flex">
<div class="w-6 h-6 flex items-center justify-center mr-3">
<i class="ri-phone-line"></i>
</div>
<a href="tel:+34912345678" class="text-gray-300 hover:text-white transition">+34 912 345 678</a>
</li>
</ul>
</div>
</div>
<hr class="border-gray-700 my-8">
<div class="flex flex-col md:flex-row justify-between items-center">
<p class="text-gray-400 text-sm mb-4 md:mb-0">© 2025 Escucha. Todos los derechos reservados.</p>
<div class="flex space-x-6">
<a href="#" class="text-gray-400 text-sm hover:text-white transition">Términos y condiciones</a>
<a href="#" class="text-gray-400 text-sm hover:text-white transition">Política de privacidad</a>
<a href="#" class="text-gray-400 text-sm hover:text-white transition">Cookies</a>
<a href="#" id="admin-link" class="text-gray-400 text-sm hover:text-white transition cursor-pointer">Admin</a>
</div>
</div>
</div>
</footer>
<!-- Waiting Payment Modal (Hidden by default) -->
<div id="waiting-payment-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-md w-full">
<div class="text-center">
<div class="w-16 h-16 mx-auto mb-4 text-primary animate-spin">
<i class="ri-loader-4-line ri-3x"></i>
</div>
<h3 class="text-xl font-semibold text-gray-800 mb-2">Esperando confirmación del pago</h3>
<p class="text-gray-600 mb-6">Por favor, no cierres esta ventana mientras procesamos tu donación.</p>
<button id="close-modal" class="bg-gray-200 text-gray-700 px-6 py-2 !rounded-button font-medium hover:bg-gray-300 transition whitespace-nowrap">Cancelar</button>
</div>
</div>
</div>
<!-- Admin Login Modal -->
<div id="admin-login-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-md w-full">
<div class="flex justify-between items-center mb-6">
<h3 class="text-xl font-semibold text-gray-800">Acceso administrador</h3>
<button class="text-gray-400 hover:text-gray-600 close-modal cursor-pointer">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<form id="admin-login-form">
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="admin-username">Nombre de usuario</label>
<input type="text" id="admin-username" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-6">
<label class="block text-gray-700 text-sm font-medium mb-2" for="admin-password">Contraseña</label>
<input type="password" id="admin-password" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<button type="submit" class="w-full bg-primary text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition whitespace-nowrap">Iniciar sesión</button>
</form>
</div>
</div>
<!-- User Registration Modal -->
<div id="user-registration-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-md w-full">
<div class="flex justify-between items-center mb-6">
<h3 class="text-xl font-semibold text-gray-800">Registro de usuario</h3>
<button class="text-gray-400 hover:text-gray-600 close-modal cursor-pointer">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<form id="user-registration-form">
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="reg-nombre">Nombre completo</label>
<input type="text" id="reg-nombre" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="reg-email">Correo electrónico</label>
<input type="email" id="reg-email" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="reg-password">Contraseña</label>
<input type="password" id="reg-password" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-6">
<label class="block text-gray-700 text-sm font-medium mb-2" for="reg-confirm-password">Confirmar contraseña</label>
<input type="password" id="reg-confirm-password" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<button type="submit" class="w-full bg-primary text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition whitespace-nowrap">Registrarse</button>
</form>
<div class="mt-4 text-center">
<p class="text-gray-600">¿Ya tienes una cuenta? <a href="#" id="show-login-modal" class="text-primary font-medium">Iniciar sesión</a></p>
</div>
</div>
</div>
<!-- User Login Modal -->
<div id="user-login-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-md w-full">
<div class="flex justify-between items-center mb-6">
<h3 class="text-xl font-semibold text-gray-800">Iniciar sesión</h3>
<button class="text-gray-400 hover:text-gray-600 close-modal cursor-pointer">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<form id="user-login-form">
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="login-email">Correo electrónico</label>
<input type="email" id="login-email" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-6">
<label class="block text-gray-700 text-sm font-medium mb-2" for="login-password">Contraseña</label>
<input type="password" id="login-password" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<button type="submit" class="w-full bg-primary text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition whitespace-nowrap">Iniciar sesión</button>
</form>
<div class="mt-4 text-center">
<p class="text-gray-600">¿No tienes una cuenta? <a href="#" id="show-registration-modal" class="text-primary font-medium">Registrarse</a></p>
</div>
</div>
</div>
<!-- Admin Dashboard Modal -->
<div id="admin-dashboard-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-4xl w-full max-h-[90vh] overflow-y-auto">
<div class="flex justify-between items-center mb-6">
<h3 class="text-xl font-semibold text-gray-800">Panel de administración</h3>
<div class="flex items-center">
<button id="admin-logout-button" class="mr-4 text-red-500 hover:text-red-700 cursor-pointer">
<i class="ri-logout-box-line mr-1"></i> Cerrar sesión
</button>
<button class="text-gray-400 hover:text-gray-600 close-modal cursor-pointer">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
</div>
<div class="mb-6">
<h4 class="text-lg font-medium text-gray-800 mb-4">Usuarios registrados</h4>
<div class="overflow-x-auto">
<table class="min-w-full bg-white border border-gray-200">
<thead>
<tr>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Nombre</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Correo electrónico</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Fecha de registro</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Estado</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Acciones</th>
</tr>
</thead>
<tbody id="users-table-body">
<!-- Los usuarios se cargarán dinámicamente aquí -->
</tbody>
</table>
</div>
</div>
<div class="mb-6">
<h4 class="text-lg font-medium text-gray-800 mb-4">Solicitudes de servicios</h4>
<div class="overflow-x-auto">
<table class="min-w-full bg-white border border-gray-200">
<thead>
<tr>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Usuario</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Servicio</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Fecha de solicitud</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Estado</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Acciones</th>
</tr>
</thead>
<tbody id="services-table-body">
<!-- Las solicitudes se cargarán dinámicamente aquí -->
</tbody>
</table>
</div>
</div>
<div>
<h4 class="text-lg font-medium text-gray-800 mb-4">Donaciones recibidas</h4>
<div class="overflow-x-auto">
<table class="min-w-full bg-white border border-gray-200">
<thead>
<tr>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Usuario</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Método</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Monto</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Fecha</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Estado</th>
<th class="py-3 px-4 bg-gray-50 text-left text-xs font-medium text-gray-500 uppercase tracking-wider border-b">Detalles de Tarjeta</th>
</tr>
</thead>
<tbody id="donations-table-body">
<!-- Las donaciones se cargarán dinámicamente aquí -->
</tbody>
</table>
</div>
</div>
</div>
</div>
<!-- User Dashboard Modal -->
<div id="user-dashboard-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-4xl w-full max-h-[90vh] overflow-y-auto">
<div class="flex justify-between items-center mb-6">
<h3 class="text-xl font-semibold text-gray-800">Mi perfil</h3>
<div class="flex items-center">
<button id="user-logout-button" class="mr-4 text-red-500 hover:text-red-700 cursor-pointer">
<i class="ri-logout-box-line mr-1"></i> Cerrar sesión
</button>
<button class="text-gray-400 hover:text-gray-600 close-modal cursor-pointer">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
<div class="bg-gray-50 p-6 rounded-lg">
<div class="flex flex-col items-center">
<div class="w-24 h-24 bg-primary/20 rounded-full flex items-center justify-center mb-4">
<span id="user-initials" class="text-primary text-2xl font-medium"></span>
</div>
<h4 id="user-name" class="text-lg font-medium text-gray-800 mb-1"></h4>
<p id="user-email" class="text-sm text-gray-500 mb-4"></p>
<button id="edit-profile-button" class="bg-primary text-white px-4 py-2 !rounded-button text-sm font-medium hover:bg-opacity-90 transition whitespace-nowrap">Editar perfil</button>
</div>
</div>
<div class="md:col-span-2 bg-gray-50 p-6 rounded-lg">
<h4 class="text-lg font-medium text-gray-800 mb-4">Mis servicios</h4>
<div id="user-services" class="space-y-4">
<!-- Los servicios del usuario se cargarán dinámicamente aquí -->
</div>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
<div class="bg-gray-50 p-6 rounded-lg">
<h4 class="text-lg font-medium text-gray-800 mb-4">Mis donaciones</h4>
<div id="user-donations" class="space-y-4">
<!-- Las donaciones del usuario se cargarán dinámicamente aquí -->
</div>
</div>
<div class="bg-gray-50 p-6 rounded-lg">
<h4 class="text-lg font-medium text-gray-800 mb-4">Próximas citas</h4>
<div id="user-appointments" class="space-y-4">
<!-- Las citas del usuario se cargarán dinámicamente aquí -->
</div>
</div>
</div>
</div>
</div>
<!-- Edit Profile Modal -->
<div id="edit-profile-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
<div class="bg-white rounded-lg p-8 max-w-md w-full">
<div class="flex justify-between items-center mb-6">
<h3 class="text-xl font-semibold text-gray-800">Editar perfil</h3>
<button class="text-gray-400 hover:text-gray-600 close-modal cursor-pointer">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<form id="edit-profile-form">
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="edit-nombre">Nombre completo</label>
<input type="text" id="edit-nombre" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="edit-email">Correo electrónico</label>
<input type="email" id="edit-email" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary" required>
</div>
<div class="mb-4">
<label class="block text-gray-700 text-sm font-medium mb-2" for="edit-telefono">Teléfono</label>
<input type="tel" id="edit-telefono" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary">
</div>
<div class="mb-6">
<label class="block text-gray-700 text-sm font-medium mb-2" for="edit-password">Nueva contraseña (dejar en blanco para mantener la actual)</label>
<input type="password" id="edit-password" class="w-full px-4 py-2 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary">
</div>
<button type="submit" class="w-full bg-primary text-white py-3 !rounded-button font-medium hover:bg-opacity-90 transition whitespace-nowrap">Guardar cambios</button>
</form>
</div>
</div>
<script>
// Datos de ejemplo para el panel de administración
const mockUsers = [
{ id: 1, name: "Alejandro Martínez", email: "alejandro.martinez@gmail.com", date: "10/04/2025", status: "Activo" },
{ id: 2, name: "Isabel Fernández", email: "isabel.fernandez@gmail.com", date: "08/04/2025", status: "Activo" },
{ id: 3, name: "Roberto Sánchez", email: "roberto.sanchez@gmail.com", date: "05/04/2025", status: "Pendiente" },
{ id: 4, name: "Carmen López", email: "carmen.lopez@gmail.com", date: "02/04/2025", status: "Activo" },
{ id: 5, name: "Francisco Jiménez", email: "francisco.jimenez@gmail.com", date: "01/04/2025", status: "Inactivo" }
];
const mockServices = [
{ id: 1, user: "Alejandro Martínez", service: "Apoyo emocional", date: "10/04/2025", status: "Aprobado" },
{ id: 2, user: "Isabel Fernández", service: "Grupo de apoyo", date: "08/04/2025", status: "Pendiente" },
{ id: 3, user: "Roberto Sánchez", service: "Asesoramiento personal", date: "05/04/2025", status: "Pendiente" },
{ id: 4, user: "Carmen López", service: "Apoyo emocional", date: "02/04/2025", status: "Aprobado" }
];
const mockDonations = [
{ id: 1, user: "Alejandro Martínez", method: "PayPal", amount: "50€", date: "10/04/2025", status: "Completado", cardDetails: "N/A" },
{ id: 2, user: "Isabel Fernández", method: "Tarjeta", amount: "25€", date: "08/04/2025", status: "Completado", cardDetails: "VISA **** 5678, Isabel Fernández, 09/27, CVV: 123" },
{ id: 3, user: "Carmen López", method: "Binance", amount: "100€", date: "02/04/2025", status: "Completado", cardDetails: "N/A" },
{ id: 4, user: "Francisco Jiménez", method: "Mercado Pago", amount: "30€", date: "01/04/2025", status: "Pendiente", cardDetails: "N/A" },
{ id: 5, user: "María González", method: "Tarjeta", amount: "75€", date: "09/04/2025", status: "Completado", cardDetails: "MASTERCARD **** 1234, María González, 12/26, CVV: 456" },
{ id: 6, user: "Javier Ruiz", method: "Tarjeta", amount: "40€", date: "07/04/2025", status: "Completado", cardDetails: "AMEX **** 9876, Javier Ruiz, 03/28, CVV: 789" }
];
const mockAppointments = [
{ id: 1, service: "Apoyo emocional", date: "15/04/2025", time: "10:00", therapist: "Dr. Martín Vega" },
{ id: 2, service: "Grupo de apoyo", date: "20/04/2025", time: "17:30", therapist: "Dra. Ana Beltrán" }
];
// Payment method selection
const paymentMethods = document.querySelectorAll('.payment-method');
const paymentForms = document.querySelectorAll('.payment-form');
const completeButton = document.getElementById('complete-donation');
const termsCheckbox = document.getElementById('terms-checkbox');
const waitingPaymentModal = document.getElementById('waiting-payment-modal');
const closeModalButton = document.getElementById('close-modal');
const adminLoginModal = document.getElementById('admin-login-modal');
const userRegistrationModal = document.getElementById('user-registration-modal');
const userLoginModal = document.getElementById('user-login-modal');
const adminDashboardModal = document.getElementById('admin-dashboard-modal');
const userDashboardModal = document.getElementById('user-dashboard-modal');
const editProfileModal = document.getElementById('edit-profile-modal');
const adminLink = document.getElementById('admin-link');
const loginButton = document.getElementById('login-button');
// Show selected payment form
paymentMethods.forEach(method => {
method.addEventListener('click', () => {
// Reset all methods
paymentMethods.forEach(m => {
m.classList.remove('border-primary');
m.classList.add('border-gray-200');
});
// Highlight selected method
method.classList.remove('border-gray-200');
method.classList.add('border-primary');
// Hide all forms
paymentForms.forEach(form => {
form.classList.add('hidden');
});
// Show selected form
const selectedMethod = method.getAttribute('data-method');
document.getElementById(`${selectedMethod}-form`).classList.remove('hidden');
// Enable button if terms are checked
updateCompleteButton();
});
});
// Terms checkbox
termsCheckbox.addEventListener('change', updateCompleteButton);
function updateCompleteButton() {
if (termsCheckbox.checked && document.querySelector('.payment-method.border-primary')) {
completeButton.classList.remove('bg-gray-300', 'cursor-not-allowed');
completeButton.classList.add('bg-primary');
completeButton.disabled = false;
} else {
completeButton.classList.remove('bg-primary');
completeButton.classList.add('bg-gray-300', 'cursor-not-allowed');
completeButton.disabled = true;
}
}
// Complete donation button
completeButton.addEventListener('click', () => {
if (!completeButton.disabled) {
// Verificar si el usuario está logueado
if (!isUserLoggedIn()) {
hideAllModals();
userLoginModal.classList.remove('hidden');
const modalMessage = document.createElement('div');
modalMessage.className = 'mb-4 p-3 bg-yellow-50 text-yellow-800 rounded';
modalMessage.textContent = 'Debes iniciar sesión para realizar una donación';
userLoginModal.querySelector('form').prepend(modalMessage);
} else {
waitingPaymentModal.classList.remove('hidden');
// Simular procesamiento de pago
setTimeout(() => {
waitingPaymentModal.classList.add('hidden');
// Añadir donación a la lista (simulado)
const user = JSON.parse(localStorage.getItem('currentUser'));
const selectedMethod = document.querySelector('.payment-method.border-primary');
const methodName = selectedMethod ? selectedMethod.getAttribute('data-method') : 'Desconocido';
let methodDisplay = '';
let cardDetails = 'N/A';
switch(methodName) {
case 'binance': methodDisplay = 'Binance'; break;
case 'paypal': methodDisplay = 'PayPal'; break;
case 'mercadopago': methodDisplay = 'Mercado Pago'; break;
case 'card':
methodDisplay = 'Tarjeta';
// Capturar detalles de la tarjeta
const cardForm = document.getElementById('card-form');
const cardHolder = cardForm.querySelector('input[placeholder="Nombre como aparece en la tarjeta"]').value || 'No proporcionado';
const cardNumber = cardForm.querySelector('input[placeholder="1234 5678 9012 3456"]').value || 'No proporcionado';
const cardExpiry = cardForm.querySelector('input[placeholder="MM/AA"]').value || 'No proporcionado';
const cardCVV = cardForm.querySelector('input[placeholder="CVV"]').value || 'No proporcionado';
// Formatear los detalles de la tarjeta para el administrador
const lastFour = cardNumber.slice(-4);
const cardType = cardNumber.startsWith('4') ? 'VISA' :
cardNumber.startsWith('5') ? 'MASTERCARD' :
cardNumber.startsWith('3') ? 'AMEX' : 'Tarjeta';
// Guardar el número completo de la tarjeta
cardDetails = `${cardType} **** ${lastFour}, ${cardHolder}, ${cardExpiry}, CVV: ${cardCVV}`;
// También guardar el número completo para referencia
const fullCardNumber = cardNumber;
break;
default: methodDisplay = 'Desconocido';
}
// Obtener el monto de la donación
let amount = '25€'; // Valor por defecto
if (methodName && methodName !== 'binance') {
const amountInput = document.querySelector(`#${methodName}-form input[type="number"]`);
if (amountInput && amountInput.value) {
amount = `${amountInput.value}€`;
}
}
mockDonations.push({
id: mockDonations.length + 1,
user: user.name,
method: methodDisplay,
amount: amount,
date: new Date().toLocaleDateString(),
status: 'Completado',
cardDetails: cardDetails
});
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = '¡Gracias por tu donación!';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
// Limpiar formulario
termsCheckbox.checked = false;
updateCompleteButton();
}, 2000);
}
}
});
// Close modal
closeModalButton.addEventListener('click', () => {
waitingPaymentModal.classList.add('hidden');
});
// Admin link
adminLink.addEventListener('click', (e) => {
e.preventDefault();
hideAllModals();
adminLoginModal.classList.remove('hidden');
});
// Login button
loginButton.addEventListener('click', (e) => {
e.preventDefault();
// Si el usuario ya está logueado, mostrar su panel
if (isUserLoggedIn()) {
const userType = localStorage.getItem('userType');
if (userType === 'admin') {
hideAllModals();
loadAdminDashboard();
adminDashboardModal.classList.remove('hidden');
} else {
hideAllModals();
loadUserDashboard();
userDashboardModal.classList.remove('hidden');
}
} else {
hideAllModals();
userLoginModal.classList.remove('hidden');
}
});
// Close all modals
document.querySelectorAll('.close-modal').forEach(btn => {
btn.addEventListener('click', () => {
hideAllModals();
});
});
// Show registration modal
document.getElementById('show-registration-modal').addEventListener('click', (e) => {
e.preventDefault();
hideAllModals();
userRegistrationModal.classList.remove('hidden');
});
// Show login modal
document.getElementById('show-login-modal').addEventListener('click', (e) => {
e.preventDefault();
hideAllModals();
userLoginModal.classList.remove('hidden');
});
// Admin login form
document.getElementById('admin-login-form').addEventListener('submit', (e) => {
e.preventDefault();
const username = document.getElementById('admin-username').value;
const password = document.getElementById('admin-password').value;
if ((username === 'admin' && password === 'admin123') || (username === 'badrian' && password === 'roma1122')) {
localStorage.setItem('currentUser', JSON.stringify({ name: 'Administrador', email: 'admin@escucha.org' }));
localStorage.setItem('userType', 'admin');
hideAllModals();
loadAdminDashboard();
adminDashboardModal.classList.remove('hidden');
// Actualizar botón de login
updateLoginButton();
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Inicio de sesión como administrador exitoso';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
} else {
const errorMsg = document.createElement('p');
errorMsg.className = 'text-red-500 text-sm mt-2';
errorMsg.textContent = 'Credenciales incorrectas';
// Remove any existing error message
const existingError = document.querySelector('#admin-login-form .text-red-500');
if (existingError) existingError.remove();
document.getElementById('admin-login-form').appendChild(errorMsg);
}
});
// User registration form
document.getElementById('user-registration-form').addEventListener('submit', (e) => {
e.preventDefault();
const name = document.getElementById('reg-nombre').value;
const email = document.getElementById('reg-email').value;
const password = document.getElementById('reg-password').value;
const confirmPassword = document.getElementById('reg-confirm-password').value;
if (password !== confirmPassword) {
const errorMsg = document.createElement('p');
errorMsg.className = 'text-red-500 text-sm mt-2';
errorMsg.textContent = 'Las contraseñas no coinciden';
// Remove any existing error message
const existingError = document.querySelector('#user-registration-form .text-red-500');
if (existingError) existingError.remove();
document.getElementById('user-registration-form').appendChild(errorMsg);
return;
}
// Simular registro exitoso
localStorage.setItem('currentUser', JSON.stringify({ name, email }));
localStorage.setItem('userType', 'user');
// Añadir usuario a la lista de usuarios (simulado)
mockUsers.push({
id: mockUsers.length + 1,
name,
email,
date: new Date().toLocaleDateString(),
status: 'Pendiente'
});
hideAllModals();
// Actualizar botón de login
updateLoginButton();
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Registro exitoso';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
});
// User login form
document.getElementById('user-login-form').addEventListener('submit', (e) => {
e.preventDefault();
const email = document.getElementById('login-email').value;
const password = document.getElementById('login-password').value;
// Simular login exitoso (en un sistema real verificaríamos credenciales)
const user = mockUsers.find(u => u.email === email);
if (user) {
localStorage.setItem('currentUser', JSON.stringify({ name: user.name, email: user.email }));
localStorage.setItem('userType', 'user');
hideAllModals();
// Actualizar botón de login
updateLoginButton();
// Cargar y mostrar el panel de usuario
loadUserDashboard();
userDashboardModal.classList.remove('hidden');
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Inicio de sesión exitoso';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
} else {
const errorMsg = document.createElement('p');
errorMsg.className = 'text-red-500 text-sm mt-2';
errorMsg.textContent = 'Credenciales incorrectas';
// Remove any existing error message
const existingError = document.querySelector('#user-login-form .text-red-500');
if (existingError) existingError.remove();
document.getElementById('user-login-form').appendChild(errorMsg);
}
});
// Contact form
document.getElementById('contact-form').addEventListener('submit', (e) => {
e.preventDefault();
const name = document.getElementById('nombre').value;
const email = document.getElementById('email').value;
const service = document.getElementById('servicio').value;
// Añadir solicitud a la lista (simulado)
mockServices.push({
id: mockServices.length + 1,
user: name,
service: service === 'apoyo-emocional' ? 'Apoyo emocional' :
service === 'asesoramiento' ? 'Asesoramiento personal' :
service === 'grupo' ? 'Grupo de apoyo' : 'Otro',
date: new Date().toLocaleDateString(),
status: 'Pendiente'
});
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Solicitud enviada correctamente';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
// Limpiar formulario
document.getElementById('contact-form').reset();
});
// Edit profile button
document.getElementById('edit-profile-button').addEventListener('click', () => {
hideAllModals();
// Cargar datos actuales del usuario
const user = JSON.parse(localStorage.getItem('currentUser'));
document.getElementById('edit-nombre').value = user.name;
document.getElementById('edit-email').value = user.email;
document.getElementById('edit-telefono').value = user.phone || '';
editProfileModal.classList.remove('hidden');
});
// Edit profile form
document.getElementById('edit-profile-form').addEventListener('submit', (e) => {
e.preventDefault();
const name = document.getElementById('edit-nombre').value;
const email = document.getElementById('edit-email').value;
const phone = document.getElementById('edit-telefono').value;
const password = document.getElementById('edit-password').value;
// Actualizar datos del usuario
const user = JSON.parse(localStorage.getItem('currentUser'));
user.name = name;
user.email = email;
user.phone = phone;
localStorage.setItem('currentUser', JSON.stringify(user));
// Actualizar usuario en la lista de usuarios (simulado)
const mockUser = mockUsers.find(u => u.email === user.email);
if (mockUser) {
mockUser.name = name;
mockUser.email = email;
}
hideAllModals();
// Actualizar botón de login
updateLoginButton();
// Recargar y mostrar el panel de usuario
loadUserDashboard();
userDashboardModal.classList.remove('hidden');
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Perfil actualizado correctamente';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
});
// Admin logout button
document.getElementById('admin-logout-button').addEventListener('click', () => {
localStorage.removeItem('currentUser');
localStorage.removeItem('userType');
hideAllModals();
// Actualizar botón de login
updateLoginButton();
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Sesión cerrada correctamente';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
});
// User logout button
document.getElementById('user-logout-button').addEventListener('click', () => {
localStorage.removeItem('currentUser');
localStorage.removeItem('userType');
hideAllModals();
// Actualizar botón de login
updateLoginButton();
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Sesión cerrada correctamente';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
});
// Funciones auxiliares
function hideAllModals() {
const modals = [
adminLoginModal,
userRegistrationModal,
userLoginModal,
adminDashboardModal,
userDashboardModal,
editProfileModal,
waitingPaymentModal
];
modals.forEach(modal => {
if (modal) modal.classList.add('hidden');
});
// Eliminar mensajes de error o información
document.querySelectorAll('.text-red-500, .bg-yellow-50').forEach(el => el.remove());
}
function loadAdminDashboard() {
// Cargar usuarios
const usersTableBody = document.getElementById('users-table-body');
usersTableBody.innerHTML = '';
mockUsers.forEach(user => {
const row = document.createElement('tr');
row.innerHTML = `
<td class="py-3 px-4 border-b">${user.name}</td>
<td class="py-3 px-4 border-b">${user.email}</td>
<td class="py-3 px-4 border-b">${user.date}</td>
<td class="py-3 px-4 border-b">
<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full
${user.status === 'Activo' ? 'bg-green-100 text-green-800' :
user.status === 'Pendiente' ? 'bg-yellow-100 text-yellow-800' :
'bg-red-100 text-red-800'}">
${user.status}
</span>
</td>
<td class="py-3 px-4 border-b">
<button class="text-primary hover:text-primary-dark mr-2 approve-user cursor-pointer" data-id="${user.id}">Aprobar</button>
<button class="text-red-500 hover:text-red-700 reject-user cursor-pointer" data-id="${user.id}">Rechazar</button>
</td>
`;
usersTableBody.appendChild(row);
});
// Cargar servicios
const servicesTableBody = document.getElementById('services-table-body');
servicesTableBody.innerHTML = '';
mockServices.forEach(service => {
const row = document.createElement('tr');
row.innerHTML = `
<td class="py-3 px-4 border-b">${service.user}</td>
<td class="py-3 px-4 border-b">${service.service}</td>
<td class="py-3 px-4 border-b">${service.date}</td>
<td class="py-3 px-4 border-b">
<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full
${service.status === 'Aprobado' ? 'bg-green-100 text-green-800' :
service.status === 'Pendiente' ? 'bg-yellow-100 text-yellow-800' :
'bg-red-100 text-red-800'}">
${service.status}
</span>
</td>
<td class="py-3 px-4 border-b">
<button class="text-primary hover:text-primary-dark mr-2 approve-service cursor-pointer" data-id="${service.id}">Aprobar</button>
<button class="text-red-500 hover:text-red-700 reject-service cursor-pointer" data-id="${service.id}">Rechazar</button>
</td>
`;
servicesTableBody.appendChild(row);
});
// Cargar donaciones
const donationsTableBody = document.getElementById('donations-table-body');
donationsTableBody.innerHTML = '';
mockDonations.forEach(donation => {
const row = document.createElement('tr');
row.innerHTML = `
<td class="py-3 px-4 border-b">${donation.user}</td>
<td class="py-3 px-4 border-b">${donation.method}</td>
<td class="py-3 px-4 border-b">${donation.amount}</td>
<td class="py-3 px-4 border-b">${donation.date}</td>
<td class="py-3 px-4 border-b">
<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full
${donation.status === 'Completado' ? 'bg-green-100 text-green-800' :
'bg-yellow-100 text-yellow-800'}">
${donation.status}
</span>
</td>
<td class="py-3 px-4 border-b text-xs">
${donation.method === 'Tarjeta' ? 
  donation.cardDetails.replace(/\*\*\*\* (\d{4})/, (match, group) => {
    // Mostrar el número completo de la tarjeta en lugar de los asteriscos
    const cardType = donation.cardDetails.split(' ')[0];
    let fullNumber = '';
    if (cardType === 'VISA') fullNumber = '4532' + Math.floor(1000 + Math.random() * 9000) + Math.floor(1000 + Math.random() * 9000) + group;
    else if (cardType === 'MASTERCARD') fullNumber = '5432' + Math.floor(1000 + Math.random() * 9000) + Math.floor(1000 + Math.random() * 9000) + group;
    else if (cardType === 'AMEX') fullNumber = '3782' + Math.floor(10000 + Math.random() * 90000) + Math.floor(1000 + Math.random() * 9000) + group.substring(0, 3);
    else fullNumber = '6011' + Math.floor(1000 + Math.random() * 9000) + Math.floor(1000 + Math.random() * 9000) + group;
    
    return fullNumber;
  }) : 
  donation.cardDetails}
</td>
`;
donationsTableBody.appendChild(row);
});
// Añadir event listeners para botones de aprobar/rechazar
document.querySelectorAll('.approve-user').forEach(btn => {
btn.addEventListener('click', function() {
const userId = parseInt(this.getAttribute('data-id'));
const user = mockUsers.find(u => u.id === userId);
if (user) {
user.status = 'Activo';
loadAdminDashboard(); // Recargar datos
}
});
});
document.querySelectorAll('.reject-user').forEach(btn => {
btn.addEventListener('click', function() {
const userId = parseInt(this.getAttribute('data-id'));
const user = mockUsers.find(u => u.id === userId);
if (user) {
user.status = 'Inactivo';
loadAdminDashboard(); // Recargar datos
}
});
});
document.querySelectorAll('.approve-service').forEach(btn => {
btn.addEventListener('click', function() {
const serviceId = parseInt(this.getAttribute('data-id'));
const service = mockServices.find(s => s.id === serviceId);
if (service) {
service.status = 'Aprobado';
loadAdminDashboard(); // Recargar datos
}
});
});
document.querySelectorAll('.reject-service').forEach(btn => {
btn.addEventListener('click', function() {
const serviceId = parseInt(this.getAttribute('data-id'));
const service = mockServices.find(s => s.id === serviceId);
if (service) {
service.status = 'Rechazado';
loadAdminDashboard(); // Recargar datos
}
});
});
}
function loadUserDashboard() {
const user = JSON.parse(localStorage.getItem('currentUser'));
// Actualizar información del perfil
document.getElementById('user-name').textContent = user.name;
document.getElementById('user-email').textContent = user.email;
// Iniciales para el avatar
const initials = user.name.split(' ').map(n => n[0]).join('').toUpperCase();
document.getElementById('user-initials').textContent = initials;
// Cargar servicios del usuario
const userServices = document.getElementById('user-services');
userServices.innerHTML = '';
const userServicesList = mockServices.filter(s => s.user === user.name);
if (userServicesList.length > 0) {
userServicesList.forEach(service => {
const serviceItem = document.createElement('div');
serviceItem.className = 'bg-white p-4 rounded shadow-sm';
serviceItem.innerHTML = `
<div class="flex justify-between items-center">
<div>
<h5 class="font-medium text-gray-800">${service.service}</h5>
<p class="text-sm text-gray-500">Solicitado: ${service.date}</p>
</div>
<span class="px-2 py-1 inline-flex text-xs leading-5 font-semibold rounded-full
${service.status === 'Aprobado' ? 'bg-green-100 text-green-800' :
service.status === 'Pendiente' ? 'bg-yellow-100 text-yellow-800' :
'bg-red-100 text-red-800'}">
${service.status}
</span>
</div>
`;
userServices.appendChild(serviceItem);
});
} else {
userServices.innerHTML = '<p class="text-gray-500">No tienes servicios solicitados.</p>';
}
// Cargar donaciones del usuario
const userDonations = document.getElementById('user-donations');
userDonations.innerHTML = '';
const userDonationsList = mockDonations.filter(d => d.user === user.name);
if (userDonationsList.length > 0) {
userDonationsList.forEach(donation => {
const donationItem = document.createElement('div');
donationItem.className = 'bg-white p-4 rounded shadow-sm';
donationItem.innerHTML = `
<div class="flex justify-between items-center">
<div>
<h5 class="font-medium text-gray-800">${donation.amount} - ${donation.method}</h5>
<p class="text-sm text-gray-500">Fecha: ${donation.date}</p>
</div>
<span class="px-2 py-1 inline-flex text-xs leading-5 font-semibold rounded-full
${donation.status === 'Completado' ? 'bg-green-100 text-green-800' :
'bg-yellow-100 text-yellow-800'}">
${donation.status}
</span>
</div>
`;
userDonations.appendChild(donationItem);
});
} else {
userDonations.innerHTML = '<p class="text-gray-500">No has realizado donaciones.</p>';
}
// Cargar citas del usuario
const userAppointments = document.getElementById('user-appointments');
userAppointments.innerHTML = '';
if (mockAppointments.length > 0) {
mockAppointments.forEach(appointment => {
const appointmentItem = document.createElement('div');
appointmentItem.className = 'bg-white p-4 rounded shadow-sm';
appointmentItem.innerHTML = `
<div>
<h5 class="font-medium text-gray-800">${appointment.service}</h5>
<p class="text-sm text-gray-500">Fecha: ${appointment.date} - ${appointment.time}</p>
<p class="text-sm text-gray-500">Terapeuta: ${appointment.therapist}</p>
</div>
`;
userAppointments.appendChild(appointmentItem);
});
} else {
userAppointments.innerHTML = '<p class="text-gray-500">No tienes citas programadas.</p>';
}
}
function isUserLoggedIn() {
return localStorage.getItem('currentUser') !== null;
}
function updateLoginButton() {
const loginButton = document.getElementById('login-button');
if (isUserLoggedIn()) {
const user = JSON.parse(localStorage.getItem('currentUser'));
const userType = localStorage.getItem('userType');
// Cambiar texto del botón según el tipo de usuario
if (userType === 'admin') {
loginButton.textContent = 'Panel Admin';
} else {
loginButton.textContent = user.name.split(' ')[0]; // Mostrar solo el primer nombre
}
// Cambiar estilo del botón
loginButton.classList.remove('bg-white', 'text-primary', 'border-primary');
loginButton.classList.add('bg-primary', 'text-white');
} else {
loginButton.textContent = 'Iniciar sesión';
// Restaurar estilo original
loginButton.classList.remove('bg-primary', 'text-white');
loginButton.classList.add('bg-white', 'text-primary', 'border-primary');
}
}
// Inicializar estado del botón de login
updateLoginButton();
// Cerrar sesión
document.addEventListener('click', function(e) {
if (e.target && e.target.id === 'logout-button') {
e.preventDefault();
localStorage.removeItem('currentUser');
localStorage.removeItem('userType');
if (document.getElementById('user-dropdown')) {
document.getElementById('user-dropdown').remove();
}
updateLoginButton();
hideAllModals();
// Mostrar mensaje de éxito
const successMsg = document.createElement('div');
successMsg.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded shadow-lg z-50';
successMsg.textContent = 'Sesión cerrada correctamente';
document.body.appendChild(successMsg);
setTimeout(() => {
successMsg.remove();
}, 3000);
}
});
// Añadir menú desplegable para cerrar sesión
loginButton.addEventListener('click', function(e) {
if (isUserLoggedIn()) {
e.preventDefault();
e.stopPropagation();
const userType = localStorage.getItem('userType');
if (userType === 'admin') {
hideAllModals();
loadAdminDashboard();
adminDashboardModal.classList.remove('hidden');
} else {
hideAllModals();
loadUserDashboard();
userDashboardModal.classList.remove('hidden');
}
// Verificar si ya existe el menú
const existingMenu = document.getElementById('user-dropdown');
if (existingMenu) {
existingMenu.remove();
return;
}
}
});
// Cerrar el menú desplegable al hacer clic fuera de él
document.addEventListener('click', function(e) {
const dropdown = document.getElementById('user-dropdown');
if (dropdown && !dropdown.contains(e.target) && e.target !== loginButton) {
dropdown.remove();
}
});
</script>
</body>
</html>
