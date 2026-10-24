<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muévete Más - Gimnasia Adaptada para Adulto Mayor</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-emerald-600 selection:text-white">

    <!-- Barra Superior de Contacto Rápido -->
    <div class="bg-slate-900 text-slate-200 text-sm py-2 px-4">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
            <div class="flex flex-wrap items-center justify-center sm:justify-start gap-4">
                <span><i class="fa-solid fa-location-dot text-emerald-400 mr-1"></i> San José de Maipo, Cajón del Maipo</span>
                <span><i class="fa-solid fa-house-user text-emerald-400 mr-1"></i> Servicio a Domicilio</span>
                <span class="hidden md:inline"><i class="fa-solid fa-user-check text-emerald-400 mr-1"></i> Profesora Alexandra Alicia</span>
            </div>
            <div class="flex items-center gap-4">
                <a href="https://wa.me/56997974350" target="_blank" class="hover:text-emerald-300 transition flex items-center gap-1 font-semibold">
                    <i class="fa-brands fa-whatsapp text-emerald-400 text-base"></i> +56 9 9797 4350
                </a>
            </div>
        </div>
    </div>

    <!-- Menú de Navegación -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#inicio" class="flex items-center gap-3 group">
                <!-- SVG del Logo con el diseño central original de 4 elementos -->
                <svg class="w-12 h-12 text-slate-900 group-hover:scale-105 transition-transform" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="50" cy="50" r="46" stroke="#1E3A8A" stroke-width="2.5" fill="#FFFFFF"/>
                    <circle cx="50" cy="50" r="41" stroke="#1E3A8A" stroke-width="1.2" fill="none"/>
                    
                    <!-- Dibujo Central Original: 4 Elementos -->
                    <!-- Fuego (Arriba) -->
                    <path d="M50 20 C47 24 45 27 50 31 C55 27 53 24 50 20 Z" stroke="#1E3A8A" stroke-width="1.8" stroke-linejoin="round" fill="none"/>
                    <path d="M50 25 C48 27 49 29 50 29 C51 29 52 27 50 25 Z" stroke="#1E3A8A" stroke-width="1.2" fill="none"/>
                    
                    <!-- Montañas (Estructura central) -->
                    <path d="M28 48 L42 29 L50 40 L58 29 L72 48 Z" stroke="#1E3A8A" stroke-width="1.8" stroke-linejoin="round" fill="none"/>
                    
                    <!-- Aire / Viento (Izquierda) -->
                    <path d="M32 42 C30 38 36 38 35 42 C34 45 30 44 32 47" stroke="#1E3A8A" stroke-width="1.5" stroke-linecap="round" fill="none"/>
                    <path d="M37 43 C35 40 40 40 39 43 C38 45 35 45 37 47" stroke="#1E3A8A" stroke-width="1.5" stroke-linecap="round" fill="none"/>
                    
                    <!-- Agua / Olas (Derecha) -->
                    <path d="M68 42 C66 38 60 38 61 42 C62 45 66 44 64 47" stroke="#1E3A8A" stroke-width="1.5" stroke-linecap="round" fill="none"/>
                    <path d="M63 43 C61 40 56 40 57 43 C58 45 61 45 59 47" stroke="#1E3A8A" stroke-width="1.5" stroke-linecap="round" fill="none"/>
                    
                    <!-- Tierra / Símbolo Central Base -->
                    <path d="M42 51 L50 45 L58 51 L50 67 Z" stroke="#1E3A8A" stroke-width="1.8" stroke-linejoin="round" fill="none"/>
                    <path d="M47 55 L53 55 M47 59 L53 59" stroke="#1E3A8A" stroke-width="1.5" stroke-linecap="round"/>

                    <!-- Iconos Laterales Pequeños (Montaña y Ola) -->
                    <circle cx="16" cy="50" r="5" stroke="#1E3A8A" stroke-width="1.2" fill="none"/>
                    <path d="M13 52 L16 48 L19 52" stroke="#1E3A8A" stroke-width="1" fill="none"/>
                    
                    <circle cx="84" cy="50" r="5" stroke="#1E3A8A" stroke-width="1.2" fill="none"/>
                    <path d="M81 51 C83 49 85 52 87 50" stroke="#1E3A8A" stroke-width="1" fill="none"/>

                    <!-- Texto Curvo Superior: MUÉVETE MÁS (Azul) -->
                    <path id="textArcTop" d="M 12,50 A 38,38 0 1,1 88,50" fill="none" />
                    <text font-size="7.5" font-weight="800" fill="#1E3A8A" letter-spacing="1.2">
                        <textPath href="#textArcTop" startOffset="50%" text-anchor="middle">MUÉVETE MÁS</textPath>
                    </text>

                    <!-- Cañón Andino (Abajo del dibujo central) -->
                    <text x="50" y="74" font-size="5.5" font-weight="800" fill="#1E3A8A" text-anchor="middle" letter-spacing="0.8">CAÑÓN ANDINO</text>

                    <!-- Texto Curvo Inferior: GIMNASIA ADAPTADA PARA ADULTO MAYOR (Verde) -->
                    <path id="textArcBottom" d="M 88,50 A 38,38 0 0,1 12,50" fill="none" />
                    <text font-size="4.6" font-weight="700" fill="#166534" letter-spacing="0.4">
                        <textPath href="#textArcBottom" startOffset="50%" text-anchor="middle">GIMNASIA ADAPTADA PARA ADULTO MAYOR</textPath>
                    </text>
                </svg>

                <div>
                    <span class="text-2xl font-extrabold tracking-tight text-blue-950 block leading-none">Muévete Más</span>
                    <span class="text-xs text-emerald-800 font-bold uppercase tracking-wider block mt-1">Gimnasia Adaptada para Adulto Mayor</span>
                </div>
            </a>

            <nav class="hidden md:flex items-center gap-8 font-semibold text-slate-700">
                <a href="#inicio" class="hover:text-emerald-700 transition">Inicio</a>
                <a href="#servicios" class="hover:text-emerald-700 transition">A Domicilio</a>
                <a href="#beneficios" class="hover:text-emerald-700 transition">Beneficios</a>
                <a href="#contacto" class="hover:text-emerald-700 transition">Contacto</a>
            </nav>

            <div>
                <a href="https://wa.me/56997974350?text=Hola,%20me%20gustaría%20solicitar%20información%20sobre%20las%20clases%20de%20gimnasia%20adaptada%20a%20domicilio." target="_blank" class="bg-emerald-700 hover:bg-emerald-800 text-white font-bold px-5 py-3 rounded-xl shadow-md transition transform active:scale-95 inline-flex items-center gap-2 text-sm sm:text-base">
                    <i class="fa-brands fa-whatsapp text-lg"></i> Contactar
                </a>
            </div>
        </div>
    </header>

    <!-- Sección Principal (Hero) -->
    <section id="inicio" class="relative bg-gradient-to-b from-blue-50/70 via-slate-50 to-white py-16 lg:py-24 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-emerald-100 text-emerald-900 text-sm font-bold shadow-sm">
                        <i class="fa-solid fa-house-chimney-medical text-emerald-700"></i> Atención 100% a Domicilio en Cajón del Maipo
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-blue-950 tracking-tight leading-[1.15]">
                        Salud, fuerza y vitalidad en la <span class="text-emerald-700 underline decoration-emerald-400 decoration-wavy">comodidad de tu hogar</span>
                    </h1>
                    <p class="text-lg sm:text-xl text-slate-600 leading-relaxed font-normal">
                        Programa personalizado de **Gimnasia Adaptada para Adulto Mayor** en San José de Maipo. Diseñado por la **Profesora Alexandra Alicia** para recuperar la movilidad, prevenir caídas y mejorar la calidad de vida sin salir de casa.
                    </p>

                    <div class="flex flex-col sm:flex-row gap-4 pt-2">
                        <a href="https://wa.me/56997974350?text=Hola%20Profesora%20Alexandra,%20quisiera%20consultar%20por%20disponibilidad%20de%20clases%20a%20domicilio." target="_blank" class="bg-emerald-700 hover:bg-emerald-800 text-white font-bold px-8 py-4 rounded-xl text-center shadow-lg shadow-emerald-700/20 transition transform hover:-translate-y-0.5 text-lg flex items-center justify-center gap-3">
                            <i class="fa-brands fa-whatsapp text-2xl"></i> Agendar Evaluación a Domicilio
                        </a>
                    </div>

                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-4 pt-4 border-t border-slate-200 text-sm text-slate-700 font-semibold">
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-circle-check text-emerald-600 text-lg"></i> Sin desplazamientos
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-circle-check text-emerald-600 text-lg"></i> Ritmo individual
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-circle-check text-emerald-600 text-lg"></i> Cañón Andino
                        </div>
                    </div>
                </div>

                <!-- Imagen Destacada -->
                <div class="relative">
                    <div class="relative rounded-3xl overflow-hidden shadow-2xl border-4 border-white bg-blue-950 aspect-[4/3]">
                        <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?auto=format&fit=crop&w=1000&q=80" alt="Gimnasia adaptada para adulto mayor a domicilio" class="w-full h-full object-cover opacity-90">
                        <div class="absolute inset-0 bg-gradient-to-t from-blue-950/80 via-transparent to-transparent flex items-end p-8">
                            <div class="text-white">
                                <p class="text-xs font-bold tracking-widest text-emerald-400 uppercase">Muévete Más • Cañón Andino</p>
                                <p class="text-2xl font-bold">Ejercicios adaptados con atención personalizada e integral</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Modalidad a Domicilio -->
    <section id="servicios" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-emerald-800 font-extrabold text-sm uppercase tracking-wider bg-emerald-100 px-4 py-1.5 rounded-full">Atención Directa</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-blue-950 mt-4 tracking-tight">Servicio de Gimnasia Adaptada a Domicilio</h2>
                <p class="mt-4 text-lg text-slate-600">Llevamos todo el equipamiento necesario y adaptamos la sesión según las condiciones de salud y espacio de cada persona.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm hover:shadow-md transition">
                    <div class="w-14 h-14 bg-blue-100 text-blue-900 rounded-2xl flex items-center justify-center text-2xl mb-6 font-bold">
                        <i class="fa-solid fa-house-heart"></i>
                    </div>
                    <h3 class="text-xl font-bold text-blue-950 mb-3">Comodidad y Seguridad</h3>
                    <p class="text-slate-600 leading-relaxed">Trabajamos en tu propio entorno, eliminando riesgos de traslado y garantizando un clima de confianza y tranquilidad.</p>
                </div>

                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm hover:shadow-md transition">
                    <div class="w-14 h-14 bg-emerald-100 text-emerald-800 rounded-2xl flex items-center justify-center text-2xl mb-6 font-bold">
                        <i class="fa-solid fa-user-doctor"></i>
                    </div>
                    <h3 class="text-xl font-bold text-blue-950 mb-3">Plan 100% Personalizado</h3>
                    <p class="text-slate-600 leading-relaxed">Evaluación inicial para adaptar cada movimiento a problemas articulares, hipertensión, movilidad reducida o recuperación postural.</p>
                </div>

                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm hover:shadow-md transition">
                    <div class="w-14 h-14 bg-blue-100 text-blue-900 rounded-2xl flex items-center justify-center text-2xl mb-6 font-bold">
                        <i class="fa-solid fa-kit-medical"></i>
                    </div>
                    <h3 class="text-xl font-bold text-blue-950 mb-3">Implementación Incluida</h3>
                    <p class="text-slate-600 leading-relaxed">Llevamos materiales suaves y seguros (bandas elásticas, balones, esferas de estimulación y apoyos de estabilidad).</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Beneficios Principales -->
    <section id="beneficios" class="py-20 bg-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-blue-950">¿Qué logramos en cada sesión?</h2>
                <p class="mt-4 text-lg text-slate-600">Un enfoque integral basado en los 4 elementos de la movilidad: equilibrio, fuerza, flexibilidad y bienestar mental.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm">
                    <div class="w-12 h-12 bg-emerald-100 text-emerald-800 rounded-xl flex items-center justify-center text-xl mb-4 font-bold">
                        <i class="fa-solid fa-person-walking"></i>
                    </div>
                    <h3 class="text-xl font-bold text-blue-950 mb-2">Prevención de Caídas</h3>
                    <p class="text-slate-600">Ejercicios orientados a fortalecer tobillos, rodillas y cadera para dar firmeza y equilibrio al caminar dentro y fuera de casa.</p>
                </div>

                <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm">
                    <div class="w-12 h-12 bg-emerald-100 text-emerald-800 rounded-xl flex items-center justify-center text-xl mb-4 font-bold">
                        <i class="fa-solid fa-dumbbell"></i>
                    </div>
                    <h3 class="text-xl font-bold text-blue-950 mb-2">Fuerza Funcional Suave</h3>
                    <p class="text-slate-600">Recuperación de la fuerza necesaria para levantarse de una silla, subir escalones y mantener la autonomía diaria sin molestias.</p>
                </div>

                <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm">
                    <div class="w-12 h-12 bg-emerald-100 text-emerald-800 rounded-xl flex items-center justify-center text-xl mb-4 font-bold">
                        <i class="fa-solid fa-brain"></i>
                    </div>
                    <h3 class="text-xl font-bold text-blue-950 mb-2">Estimulación Motriz y Ánimo</h3>
                    <p class="text-slate-600">Trabajo de coordinación y memoria motora que despierta la energía vital y mejora el ánimo y el descanso nocturno.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de Contacto e Inscripción -->
    <section id="contacto" class="py-20 bg-white border-t border-slate-200">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-emerald-800 font-extrabold text-sm uppercase tracking-wider bg-emerald-100 px-4 py-1.5 rounded-full">Contacto Directo</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-blue-950 mt-4">Consulta Disponibilidad de Horarios</h2>
                <p class="mt-4 text-lg text-slate-600">Escríbenos directamente para coordinar tu primera visita a domicilio en San José de Maipo y alrededores.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-6 mb-12">
                <div class="bg-slate-50 p-6 rounded-2xl border border-slate-200 text-center">
                    <i class="fa-brands fa-whatsapp text-emerald-600 text-3xl mb-3"></i>
                    <h3 class="font-bold text-blue-950">WhatsApp</h3>
                    <a href="https://wa.me/56997974350" target="_blank" class="text-slate-600 hover:text-emerald-700 text-sm font-semibold block mt-1">+56 9 9797 4350</a>
                </div>

                <div class="bg-slate-50 p-6 rounded-2xl border border-slate-200 text-center">
                    <i class="fa-solid fa-envelope text-blue-900 text-3xl mb-3"></i>
                    <h3 class="font-bold text-blue-950">Correo Electrónico</h3>
                    <a href="mailto:muevete+gimnasiaparaeladultomayor@gmail.com" class="text-slate-600 hover:text-blue-900 text-xs font-semibold block mt-1 break-all">muevete+gimnasiaparaeladultomayor@gmail.com</a>
                </div>

                <div class="bg-slate-50 p-6 rounded-2xl border border-slate-200 text-center">
                    <i class="fa-solid fa-map-location-dot text-emerald-600 text-3xl mb-3"></i>
                    <h3 class="font-bold text-blue-950">Ubicación</h3>
                    <p class="text-slate-600 text-sm font-semibold mt-1">San José de Maipo, Cajón del Maipo</p>
                </div>
            </div>

            <!-- Formulario con envío directo a WhatsApp -->
            <div class="bg-slate-50 p-8 sm:p-10 rounded-3xl border border-slate-200 shadow-md">
                <form onsubmit="sendToWhatsApp(event)" class="space-y-6">
                    <div>
                        <label class="block text-sm font-bold text-slate-800 mb-2">Nombre del adulto mayor o familiar</label>
                        <input type="text" id="nombre" required class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:outline-none bg-white" placeholder="Ej: María Rosa / Su hija Claudia">
                    </div>
                    <div class="grid sm:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-bold text-slate-800 mb-2">Teléfono de contacto</label>
                            <input type="tel" id="telefono" required class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:outline-none bg-white" placeholder="Ej: +56 9 1234 5678">
                        </div>
                        <div>
                            <label class="block text-sm font-bold text-slate-800 mb-2">Sector en Cajón del Maipo</label>
                            <input type="text" id="sector" required class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:outline-none bg-white" placeholder="Ej: San José centro, Lagunillas, El Canelo...">
                        </div>
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-slate-800 mb-2">Comentarios o necesidad específica</label>
                        <textarea id="mensaje" rows="4" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:outline-none bg-white" placeholder="Cuéntanos si requiere prevención de caídas, movilidad articular suave o alguna indicación especial..."></textarea>
                    </div>
                    <button type="submit" class="w-full bg-emerald-700 hover:bg-emerald-800 text-white font-extrabold py-4 rounded-xl shadow-lg transition text-lg flex items-center justify-center gap-3">
                        <i class="fa-brands fa-whatsapp text-2xl"></i> Enviar Consulta por WhatsApp
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Pie de Página -->
    <footer class="bg-blue-950 text-slate-300 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4">
            <div class="flex items-center justify-center gap-3 text-white">
                <span class="text-2xl font-extrabold tracking-tight">Muévete Más</span>
            </div>
            <p class="text-emerald-400 font-bold text-sm uppercase tracking-wider">Gimnasia Adaptada para Adulto Mayor • Cañón Andino</p>
            <p class="text-xs text-slate-400">Dirigido por Profesora de Educación Física Alexandra Alicia | San José de Maipo, Chile</p>
            <p class="text-xs text-slate-500 pt-4 border-t border-blue-900">© 2026 Muévete Más. Todos los derechos reservados.</p>
        </div>
    </footer>

    <!-- Botón flotante de WhatsApp -->
    <a href="https://wa.me/56997974350?text=Hola%20Mu%C3%A9vete%20M%C3%A1s,%20quisiera%20consultar%20por%20clases%20de%20gimnasia%20adaptada%20a%20domicilio." target="_blank" class="fixed bottom-6 right-6 bg-emerald-600 hover:bg-emerald-700 text-white w-14 h-14 rounded-full flex items-center justify-center shadow-2xl z-50 transition transform hover:scale-110" title="Contactar por WhatsApp">
        <i class="fa-brands fa-whatsapp text-3xl"></i>
    </a>

    <!-- Lógica JavaScript para formulario -->
    <script>
        function sendToWhatsApp(event) {
            event.preventDefault();
            const nombre = document.getElementById('nombre').value;
            const telefono = document.getElementById('telefono').value;
            const sector = document.getElementById('sector').value;
            const mensaje = document.getElementById('mensaje').value;

            const text = `Hola Profesora Alexandra,%0A%0AMi nombre es: ${encodeURIComponent(nombre)}%0ATeléfono: ${encodeURIComponent(telefono)}%0ASector: ${encodeURIComponent(sector)}%0A%0AMensaje / Consulta:%0A${encodeURIComponent(mensaje)}`;
            
            window.open(`https://wa.me/56997974350?text=${text}`, '_blank');
        }
    </script>
</body>
</html>
