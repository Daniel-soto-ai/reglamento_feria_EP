<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografía: Postulación Feria Emprende Pueblito</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
        }
        .chart-container {
            position: relative;
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            max-width: 500px;
            height: 320px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        /* New Brand Colors */
        :root {
            --brand-purple: #4A247D;
            --brand-green: #00A651;
            --brand-red: #EF4135;
            --brand-blue: #0033A0;
            --brand-teal: #00A99D;
            --brand-yellow: #FFC72C;
        }
    </style>
</head>
<body class="text-gray-800">

    <div class="container mx-auto p-4 md:p-8 max-w-6xl">

        <header class="text-center py-8">
            <div class="flex justify-between items-center mb-8 px-4">
                <img src="http://googleusercontent.com/file_content/8" alt="Logo Pueblito de las Vizcachas" class="h-12 md:h-16">
                <img src="http://googleusercontent.com/file_content/7" alt="Logo Emprende Pueblito" class="h-16 md:h-20">
            </div>
            <h1 class="text-4xl md:text-5xl font-extrabold" style="color: var(--brand-purple);">Postula a la Feria "Emprende Pueblito"</h1>
            <p class="text-lg md:text-xl mt-4 text-gray-600">Una guía visual para entender cómo ser parte de nuestra comunidad de talento local.</p>
        </header>

        <main class="space-y-16 md:space-y-24">

            <section class="bg-white p-8 rounded-2xl shadow-lg">
                <h2 class="text-3xl font-bold text-center mb-6" style="color: var(--brand-purple);">Tu Talento es el Protagonista</h2>
                <p class="text-center text-gray-600 max-w-3xl mx-auto mb-8">Nuestra feria celebra la creatividad y la elaboración propia. Para mantener nuestra identidad, es clave que tus productos cumplan con estos criterios.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="border-4 rounded-xl p-6" style="border-color: var(--brand-green);">
                        <h3 class="text-2xl font-bold flex items-center mb-4" style="color: var(--brand-green);">
                            <span class="text-3xl mr-3">✅</span> Productos Permitidos
                        </h3>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Creaciones de diseño y arte propio.</li>
                            <li>Artesanía en madera, cuero, metal, etc.</li>
                            <li>Tejidos y creaciones textiles.</li>
                            <li>Joyería y bisutería de autor.</li>
                            <li>Cosmética natural de elaboración propia.</li>
                        </ul>
                    </div>
                    <div class="border-4 rounded-xl p-6" style="border-color: var(--brand-red);">
                        <h3 class="text-2xl font-bold flex items-center mb-4" style="color: var(--brand-red);">
                            <span class="text-3xl mr-3">❌</span> Productos Prohibidos
                        </h3>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Productos de reventa o industriales.</li>
                            <li>Alimentos y bebidas (gastronomía).</li>
                            <li>Cualquier producto no declarado en la postulación.</li>
                        </ul>
                    </div>
                </div>
            </section>

            <section>
                <h2 class="text-3xl font-bold text-center mb-8" style="color: var(--brand-purple);">Un Proceso Simple en 2 Etapas</h2>
                <div class="flex flex-col md:flex-row items-center justify-center gap-4 md:gap-0">
                    <div class="bg-white p-6 rounded-2xl shadow-lg text-center w-full md:w-1/3">
                        <div class="text-5xl font-bold text-white mx-auto w-20 h-20 flex items-center justify-center rounded-full mb-4" style="background-color: var(--brand-blue);">1</div>
                        <h3 class="text-xl font-bold mb-2">Postulación y Selección</h3>
                        <p class="text-gray-600">Completa el formulario online con tus datos y las fotos de tus productos. ¡En esta etapa no necesitas documentos!</p>
                    </div>
                    <div class="text-5xl font-bold text-gray-300 hidden md:block mx-8">→</div>
                    <div class="text-5xl font-bold text-gray-300 md:hidden my-4">↓</div>
                    <div class="bg-white p-6 rounded-2xl shadow-lg text-center w-full md:w-1/3">
                        <div class="text-5xl font-bold text-white mx-auto w-20 h-20 flex items-center justify-center rounded-full mb-4" style="background-color: var(--brand-green);">2</div>
                        <h3 class="text-xl font-bold mb-2">Formalización</h3>
                        <p class="text-gray-600">Si eres seleccionado/a, te contactaremos para que envíes tus documentos y firmes el convenio de participación.</p>
                    </div>
                </div>
            </section>

            <section class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                <div class="bg-white p-8 rounded-2xl shadow-lg h-full">
                    <h2 class="text-3xl font-bold text-center mb-6" style="color: var(--brand-purple);">Fechas que Debes Recordar</h2>
                    <div class="space-y-6">
                        <div>
                            <h3 class="text-xl font-bold" style="color: #073B4C;">Período de Postulación</h3>
                            <p class="text-gray-600">Tienes desde el <strong style="color: var(--brand-blue);">30 de abril</strong> hasta el <strong style="color: var(--brand-blue);">01 de noviembre de 2025</strong> para enviar tu formulario.</p>
                        </div>
                        <hr>
                        <div>
                            <h3 class="text-xl font-bold" style="color: #073B4C;">Notificación de Seleccionados</h3>
                            <p class="text-gray-600">Serás notificado/a el <strong style="color: var(--brand-blue);">día 15 del mes anterior</strong> al ciclo de la feria. ¡Revisa tu correo y WhatsApp!</p>
                        </div>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-2xl shadow-lg h-full">
                     <h2 class="text-3xl font-bold text-center mb-6" style="color: var(--brand-purple);">Categorías de Emprendimientos</h2>
                     <p class="text-center text-gray-600 mb-4">Visualizamos una feria diversa. Aquí una idea de la distribución de rubros que buscamos.</p>
                    <div class="chart-container">
                        <canvas id="categoryChart"></canvas>
                    </div>
                </div>
            </section>
            
            <section>
                <h2 class="text-3xl font-bold text-center mb-8" style="color: var(--brand-purple);">Compromisos del Emprendedor Seleccionado</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="bg-white p-6 rounded-2xl shadow-lg text-center">
                        <div class="text-5xl mb-3">🤝</div>
                        <h3 class="text-xl font-bold mb-2">Asistencia</h3>
                        <p class="text-gray-600">Participación obligatoria en todas las fechas del ciclo. Avisa con 48h de anticipación si no puedes asistir.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-lg text-center">
                        <div class="text-5xl mb-3">⏰</div>
                        <h3 class="text-xl font-bold mb-2">Puntualidad</h3>
                        <p class="text-gray-600">Tu stand debe estar listo 15 minutos antes de la apertura oficial de la feria.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-lg text-center">
                        <div class="text-5xl mb-3">🧹</div>
                        <h3 class="text-xl font-bold mb-2">Cuidado del Espacio</h3>
                        <p class="text-gray-600">Mantén tu módulo de 2x2m limpio, ordenado y cuida la estructura proporcionada.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-lg text-center">
                        <div class="text-5xl mb-3">❤️</div>
                        <h3 class="text-xl font-bold mb-2">Buena Convivencia</h3>
                        <p class="text-gray-600">Respeta a tus compañeros, al público y las normas del parque para un ambiente familiar y positivo.</p>
                    </div>
                </div>
            </section>

            <section class="grid grid-cols-1 md:grid-cols-1 gap-8 items-center">
                 <div class="bg-white p-8 rounded-2xl shadow-lg h-full">
                    <h2 class="text-3xl font-bold text-center mb-6" style="color: var(--brand-purple);">Juego Limpio: Sistema de Rotación</h2>
                    <p class="text-center text-gray-600 mb-4 max-w-2xl mx-auto">Para dar oportunidades a todos, la feria opera con un sistema de rotación. Esto asegura una participación justa y una oferta siempre renovada para los visitantes. Un ciclo participas, y el siguiente descansas para crear y prepararte.</p>
                    <div class="chart-container">
                        <canvas id="rotationChart"></canvas>
                    </div>
                </div>
            </section>

        </main>

        <footer class="text-center mt-16 md:mt-24 pt-8 border-t">
            <div class="flex justify-center items-center space-x-8 mb-4">
                 <img src="http://googleusercontent.com/file_content/8" alt="Logo Pueblito de las Vizcachas" class="h-12">
                 <img src="http://googleusercontent.com/file_content/7" alt="Logo Emprende Pueblito" class="h-14">
            </div>
            <p class="text-gray-600">Corporación Municipal Pueblito de las Vizcachas</p>
            <p class="text-gray-500 text-sm">Para dudas, contactar a: emprendimiento.pueblito@gmail.com</p>
        </footer>

    </div>

    <script>
        function wrapText(label) {
            const maxLength = 16;
            if (typeof label === 'string' && label.length > maxLength) {
                const words = label.split(' ');
                const lines = [];
                let currentLine = '';
                words.forEach(word => {
                    if ((currentLine + word).length > maxLength) {
                        lines.push(currentLine.trim());
                        currentLine = '';
                    }
                    currentLine += word + ' ';
                });
                lines.push(currentLine.trim());
                return lines;
            }
            return label;
        }
        
        const tooltipTitleCallback = function(tooltipItems) {
            const item = tooltipItems[0];
            let label = item.chart.data.labels[item.dataIndex];
            if (Array.isArray(label)) {
              return label.join(' ');
            } else {
              return label;
            }
        };

        const categoryChartCtx = document.getElementById('categoryChart').getContext('2d');
        new Chart(categoryChartCtx, {
            type: 'bar',
            data: {
                labels: ['Artesanía', 'Tejidos', 'Joyería de Autor', 'Cosmética Natural', 'Arte y Diseño'],
                datasets: [{
                    label: 'Distribución de Rubros',
                    data: [30, 25, 20, 15, 10],
                    backgroundColor: ['#0033A0', '#EF4135', '#00A99D', '#FFC72C', '#4A247D'],
                    borderColor: '#ffffff',
                    borderWidth: 2,
                    borderRadius: 5
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        grid: {
                            color: '#e5e7eb'
                        }
                    },
                    x: {
                         grid: {
                            display: false
                        }
                    }
                }
            }
        });

        const rotationChartCtx = document.getElementById('rotationChart').getContext('2d');
        new Chart(rotationChartCtx, {
            type: 'doughnut',
            data: {
                labels: ['Tu Ciclo de Participación', wrapText('Ciclo de Descanso y Creación')],
                datasets: [{
                    label: 'Sistema de Rotación',
                    data: [50, 50],
                    backgroundColor: ['#4A247D', '#FFC72C'],
                    borderColor: '#ffffff',
                    borderWidth: 4,
                    hoverOffset: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                cutout: '60%',
                plugins: {
                    legend: {
                        position: 'bottom',
                        labels: {
                            padding: 20,
                            font: {
                                size: 14
                            }
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>
