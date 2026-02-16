<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Política de Privacidad - Zplit</title>
    <meta name="description" content="Política de Privacidad oficial de la aplicación Zplit.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Outfit:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00897b;
            --primary-light: #4ebaaa;
            --primary-dark: #005b4f;
            --accent: #26a69a;
            --bg: #f9fafb;
            --text-main: #1f2937;
            --text-secondary: #4b5563;
            --white: #ffffff;
            --card-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: var(--text-main);
            background-color: var(--bg);
            background-image: 
                radial-gradient(at 0% 0%, hsla(174, 100%, 95%, 1) 0, transparent 50%), 
                radial-gradient(at 50% 0%, hsla(172, 100%, 97%, 1) 0, transparent 50%), 
                radial-gradient(at 100% 0%, hsla(170, 100%, 95%, 1) 0, transparent 50%);
            min-height: 100vh;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeInDown 0.8s ease-out;
        }

        .logo {
            font-family: 'Outfit', sans-serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 0.5rem;
            letter-spacing: -0.02em;
        }

        .subtitle {
            font-family: 'Outfit', sans-serif;
            color: var(--text-secondary);
            font-weight: 400;
            font-size: 1.1rem;
        }

        .card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-radius: 24px;
            padding: 3rem;
            box-shadow: var(--card-shadow);
            border: 1px solid rgba(255, 255, 255, 0.5);
            animation: fadeInUp 0.8s ease-out;
        }

        .last-updated {
            font-size: 0.875rem;
            color: var(--text-secondary);
            margin-bottom: 2rem;
            display: block;
            border-left: 3px solid var(--primary);
            padding-left: 1rem;
            font-style: italic;
        }

        h1 {
            font-family: 'Outfit', sans-serif;
            font-size: 2rem;
            color: var(--primary-dark);
            margin-bottom: 1.5rem;
            font-weight: 700;
        }

        h2 {
            font-family: 'Outfit', sans-serif;
            font-size: 1.5rem;
            color: var(--primary);
            margin-top: 2.5rem;
            margin-bottom: 1rem;
            font-weight: 600;
        }

        h3 {
            font-family: 'Inter', sans-serif;
            font-size: 1.1rem;
            color: var(--text-main);
            margin-top: 1.5rem;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }

        p {
            margin-bottom: 1.25rem;
            color: var(--text-secondary);
            text-align: justify;
        }

        ul {
            margin-bottom: 1.5rem;
            padding-left: 1.5rem;
        }

        li {
            margin-bottom: 0.75rem;
            color: var(--text-secondary);
        }

        li strong {
            color: var(--text-main);
        }

        footer {
            text-align: center;
            margin-top: 4rem;
            color: var(--text-secondary);
            font-size: 0.9rem;
            padding-bottom: 2rem;
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 640px) {
            .card {
                padding: 1.5rem;
                border-radius: 16px;
            }
            .logo {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">Zplit</div>
            <div class="subtitle">Dividir cuentas nunca fue tan fácil</div>
        </header>

        <main class="card">
            <h1>Política de Privacidad</h1>
            <span class="last-updated">Última actualización: 16 de febrero de 2026</span>

            <p>En <strong>Zplit</strong> (en adelante, "la Aplicación"), nos tomamos muy en serio tu privacidad. Esta Política de Privacidad describe cómo recopilamos, usamos y protegemos tu información cuando utilizas nuestra aplicación móvil.</p>

            <h2>1. Información que Recopilamos</h2>

            <h3>1.1. Imágenes y Datos de Boletas</h3>
            <p>Para funcionar, Zplit requiere acceso a tu <strong>cámara</strong> y <strong>galería de fotos</strong>.</p>
            <ul>
                <li><strong>Imágenes:</strong> Cuando capturas o seleccionas una foto de una boleta, la imagen se procesa temporalmente para extraer la información.</li>
                <li><strong>Datos Extraídos:</strong> Extraemos ítems, precios, nombres de comercios, fechas y montos totales. Estos datos se utilizan exclusivamente para permitirte dividir la cuenta con otros participantes.</li>
            </ul>

            <h3>1.2. Información del Dispositivo</h3>
            <p>Recopilamos un <strong>Identificador de Dispositivo Anónimo</strong> para:</p>
            <ul>
                <li>Gestionar tus límites de uso de la Inteligencia Artificial (tokens).</li>
                <li>Mantener tus sesiones de forma anónima sin necesidad de que crees una cuenta con correo electrónico (por defecto).</li>
            </ul>

            <h3>1.3. Datos de Uso</h3>
            <p>Podemos recopilar información básica sobre cómo interactúas con la aplicación (pantallas visitadas, errores técnicos) para mejorar la estabilidad y experiencia de usuario.</p>

            <h2>2. Cómo Usamos tu Información</h2>
            <p>Utilizamos la información recopilada para:</p>
            <ul>
                <li><strong>Procesamiento con IA:</strong> Enviamos las imágenes de las boletas a proveedores de Inteligencia Artificial (como OpenAI, Google o Anthropic) para realizar el reconocimiento de texto (OCR) y la extracción de datos. Estas imágenes no se utilizan para entrenar modelos de IA de terceros bajo nuestras configuraciones de privacidad actuales.</li>
                <li><strong>Cálculos de Cuenta:</strong> Realizar los cálculos automáticos de propinas, descuentos y asignación de ítems entre participantes.</li>
                <li><strong>Sincronización:</strong> Si decides registrar una cuenta permanente en el futuro, tus datos anónimos podrán vincularse a tu cuenta.</li>
            </ul>

            <h2>3. Compartición de Información</h2>
            <p><strong>No vendemos tus datos a terceros.</strong> Compartimos información solo en los siguientes casos:</p>
            <ul>
                <li><strong>Proveedores de IA:</strong> Como se mencionó, los datos de las boletas se procesan a través de APIs de proveedores externos (OpenAI/Google/Anthropic) estrictamente para la extracción de datos.</li>
                <li><strong>Compartición por el Usuario:</strong> La aplicación permite compartir el resumen de la cuenta a través de <strong>WhatsApp</strong> u otras aplicaciones de mensajería. Esto es una acción iniciada explícitamente por ti.</li>
                <li><strong>Servicios de Backend:</strong> Utilizamos <strong>Supabase</strong> para el almacenamiento de datos de configuración y límites de usuario.</li>
            </ul>

            <h2>4. Almacenamiento y Seguridad</h2>
            <ul>
                <li><strong>Almacenamiento Local:</strong> Utilizamos el almacenamiento del dispositivo (AsyncStorage) para guardar preferencias temporales.</li>
                <li><strong>Seguridad en la Nube:</strong> Los datos enviados a nuestro backend en Supabase están protegidos por medidas de seguridad de nivel industrial y reglas de acceso (RLS).</li>
                <li><strong>Retención:</strong> Las imágenes procesadas no se almacenan permanentemente en nuestros servidores a menos que sea necesario para la funcionalidad solicitada por el usuario.</li>
            </ul>

            <h2>5. Tus Derechos</h2>
            <p>Tienes derecho a:</p>
            <ul>
                <li><strong>Acceso y Rectificación:</strong> Puedes ver y editar los datos extraídos de las boletas antes de finalizar el resumen.</li>
                <li><strong>Eliminación:</strong> Puedes eliminar la aplicación en cualquier momento, lo que eliminará los datos locales. Para solicitudes de eliminación de datos en el servidor vinculados a tu identificador de dispositivo, puedes contactarnos.</li>
                <li><strong>Control de Permisos:</strong> Puedes revocar el acceso a la cámara y fotos desde los ajustes de tu sistema operativo.</li>
            </ul>

            <h2>6. Cambios a esta Política</h2>
            <p>Podemos actualizar nuestra Política de Privacidad periódicamente. Te notificaremos cualquier cambio publicando la nueva versión dentro de la aplicación.</p>

            <h2>7. Contacto</h2>
            <p>Si tienes preguntas sobre esta Política de Privacidad, puedes contactarnos a través de los canales oficiales proporcionados por el desarrollador en la tienda de aplicaciones.</p>
        </main>

        <footer>
            &copy; 2026 Zplit - Todos los derechos reservados.
        </footer>
    </div>
</body>
</html>
