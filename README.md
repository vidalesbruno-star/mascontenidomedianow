<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>+CONTENIDO — Sistema de Edición Estratégica | MASINNOVACIONES</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            serif: ['Instrument Serif', 'serif'],
            mono: ['JetBrains Mono', 'monospace'],
          },
          colors: {
            polar: {
              bg: '#09090B',
              surface: '#111114',
              elevated: '#18181B',
              border: '#27272A',
              muted: '#A1A1AA',
              accent: '#FFFFFF',
            }
          }
        }
      }
    }
  </script>
  <style>
    body {
      background-color: #09090B;
      color: #FAFAFA;
      font-feature-settings: "cv02", "cv03", "cv04", "cv11";
    }
    .grid-bg {
      background-size: 48px 48px;
      background-image: 
        linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
    }
    .polar-card {
      background: linear-gradient(180deg, rgba(24, 24, 27, 0.7) 0%, rgba(17, 17, 20, 0.9) 100%);
      border: 1px solid #27272A;
      transition: border-color 0.25s ease, transform 0.25s ease;
    }
    .polar-card:hover {
      border-color: #3F3F46;
    }
    .radial-spoke {
      transform-origin: 100px 100px;
      transition: opacity 0.3s ease;
    }
    ::-webkit-scrollbar {
      width: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #09090B;
    }
    ::-webkit-scrollbar-thumb {
      background: #27272A;
      border-radius: 3px;
    }
  </style>
</head>
<body class="antialiased selection:bg-white selection:text-black">

  <!-- Top Navigation -->
  <header class="sticky top-0 z-40 border-b border-polar-border bg-polar-bg/85 backdrop-blur-md">
    <div class="max-w-5xl mx-auto px-6 h-16 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-6 h-6 rounded-full border border-white/80 flex items-center justify-center">
          <div class="w-2 h-2 bg-white rounded-full"></div>
        </div>
        <span class="font-mono text-xs tracking-widest uppercase text-white font-medium">+CONTENIDO</span>
        <span class="hidden sm:inline-block text-polar-border">/</span>
        <span class="hidden sm:inline-block font-mono text-[11px] text-polar-muted">BY MASINNOVACIONES</span>
      </div>
      <a href="#aplicar" class="px-4 py-2 rounded-full bg-white text-black text-xs font-medium hover:bg-zinc-200 transition-colors">
        Aplicar a prueba gratis
      </a>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative overflow-hidden border-b border-polar-border grid-bg">
    <div class="max-w-5xl mx-auto px-6 pt-20 pb-24 md:pt-28 md:pb-32">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        
        <div class="lg:col-span-8 space-y-6">
          <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full border border-polar-border bg-polar-surface text-xs font-mono text-polar-muted">
            <span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-pulse"></span>
            CUPOS LIMITADOS · EDICIÓN ILIMITADA
          </div>
          
          <h1 class="text-4xl sm:text-5xl md:text-6xl font-normal tracking-tight leading-[1.08] text-white">
            Encuentra tus ángulos ganadores y monetiza sin ser esclavo del algoritmo.
          </h1>
          
          <p class="text-base sm:text-lg text-polar-muted max-w-2xl leading-relaxed font-light">
            Para lograr calidad viral primero dominamos la <span class="text-white font-normal">cantidad estratégica</span>. Nosotros absorbemos toda tu edición diaria para que recuperes tu tiempo, te enfoques en ser el mejor de tu industria y escales tu facturación.
          </p>

          <div class="pt-4 flex flex-col sm:flex-row items-start sm:items-center gap-4">
            <a href="#aplicar" class="w-full sm:w-auto text-center px-6 py-3.5 rounded-full bg-white text-black text-sm font-medium hover:bg-zinc-200 transition-all">
              Solicitar mi primer video gratis →
            </a>
            <a href="#prueba-social" class="w-full sm:w-auto text-center px-6 py-3.5 rounded-full border border-polar-border bg-polar-surface text-zinc-300 text-sm hover:border-zinc-500 transition-colors">
              Ver resultados de @masinnovaciones
            </a>
          </div>
        </div>

        <!-- Polar-style Geometric Radial Graphic -->
        <div class="lg:col-span-4 flex justify-center lg:justify-end">
          <div class="relative w-56 h-56 sm:w-64 sm:h-64 flex items-center justify-center">
            <svg viewBox="0 0 200 200" class="w-full h-full text-white/80">
              <circle cx="100" cy="100" r="92" fill="none" stroke="#27272A" stroke-width="1" stroke-dasharray="2 4"/>
              <circle cx="100" cy="100" r="64" fill="none" stroke="#27272A" stroke-width="1"/>
              <g stroke="currentColor" stroke-width="1.2">
                <line x1="100" y1="8" x2="100" y2="34" />
                <line x1="100" y1="166" x2="100" y2="192" />
                <line x1="8" y1="100" x2="34" y2="100" />
                <line x1="166" y1="100" x2="192" y2="100" />
                <line x1="35" y1="35" x2="53" y2="53" />
                <line x1="147" y1="147" x2="165" y2="165" />
                <line x1="165" y1="35" x2="147" y2="53" />
                <line x1="53" y1="147" x2="35" y2="165" />
                <line x1="65" y1="15" x2="74" y2="39" opacity="0.4"/>
                <line x1="135" y1="15" x2="126" y2="39" opacity="0.4"/>
                <line x1="15" y1="65" x2="39" y2="74" opacity="0.4"/>
                <line x1="185" y1="65" x2="161" y2="74" opacity="0.4"/>
                <line x1="15" y1="135" x2="39" y2="126" opacity="0.4"/>
                <line x1="185" y1="135" x2="161" y2="126" opacity="0.4"/>
                <line x1="65" y1="185" x2="74" y2="161" opacity="0.4"/>
                <line x1="135" y1="185" x2="126" y2="161" opacity="0.4"/>
              </g>
              <circle cx="100" cy="100" r="18" fill="#111114" stroke="#FFFFFF" stroke-width="1.5"/>
              <circle cx="100" cy="100" r="4" fill="#FFFFFF"/>
            </svg>
            <div class="absolute bottom-2 font-mono text-[10px] tracking-widest text-polar-muted uppercase">
              +102.5M VISTAS EN 90D
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Sales Argumentation Section (The 4 Core Pillars) -->
  <section class="py-20 md:py-28 border-b border-polar-border">
    <div class="max-w-5xl mx-auto px-6">
      <div class="mb-14">
        <p class="font-mono text-xs text-polar-muted uppercase tracking-widest mb-3">01 // LA FILOSOFÍA +CONTENIDO</p>
        <h2 class="text-3xl sm:text-4xl font-normal tracking-tight text-white max-w-2xl">
          Deja de adivinar qué publicar. Construye un sistema predecible de atención y ventas.
        </h2>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        
        <!-- Pillar 1 -->
        <div class="polar-card rounded-2xl p-8 space-y-4">
          <div class="flex items-center justify-between">
            <span class="font-mono text-xs text-zinc-400">01 — MONETIZACIÓN</span>
            <span class="w-2 h-2 rounded-full bg-white/40"></span>
          </div>
          <h3 class="text-xl font-medium text-white">Encuentra tus ángulos ganadores</h3>
          <p class="text-sm text-polar-muted leading-relaxed">
            Las vistas vacías no pagan facturas. Testeamos ganchos, narrativas y formatos alineados directamente a tu oferta y estrategia de monetización para detectar qué mensajes convierten espectadores en clientes.
          </p>
        </div>

        <!-- Pillar 2 -->
        <div class="polar-card rounded-2xl p-8 space-y-4">
          <div class="flex items-center justify-between">
            <span class="font-mono text-xs text-zinc-400">02 — VELOCIDAD & VOLUMEN</span>
            <span class="w-2 h-2 rounded-full bg-white/40"></span>
          </div>
          <h3 class="text-xl font-medium text-white">Para hacer calidad, primero hacemos cantidad</h3>
          <p class="text-sm text-polar-muted leading-relaxed">
            La perfección aislada es el enemigo del crecimiento orgánico. Publicar con alta frecuencia nos da datos reales del mercado rápido; sobre lo que funciona, pulimos y escalamos la calidad.
          </p>
        </div>

        <!-- Pillar 3 -->
        <div class="polar-card rounded-2xl p-8 space-y-4">
          <div class="flex items-center justify-between">
            <span class="font-mono text-xs text-zinc-400">03 — APALANCAMIENTO</span>
            <span class="w-2 h-2 rounded-full bg-white/40"></span>
          </div>
          <h3 class="text-xl font-medium text-white">Recupera tu tiempo para ser el mejor</h3>
          <p class="text-sm text-polar-muted leading-relaxed">
            Tu trabajo no es pasar 4 horas al día cortando silencios o animando subtítulos. Te devolvemos decenas de horas a la semana para que te dediques a estudiar, crear mejores productos y liderar tu industria.
          </p>
        </div>

        <!-- Pillar 4 -->
        <div class="polar-card rounded-2xl p-8 space-y-4">
          <div class="flex items-center justify-between">
            <span class="font-mono text-xs text-zinc-400">04 — IDENTIDAD PROPIA</span>
            <span class="w-2 h-2 rounded-full bg-white/40"></span>
          </div>
          <h3 class="text-xl font-medium text-white">Nosotros nos acoplamos a ti, no tú al algoritmo</h3>
          <p class="text-sm text-polar-muted leading-relaxed">
            No te obligamos a hacer bailes ni tendencias que diluyen tu autoridad. Adaptamos el ritmo visual, la tipografía y la narrativa a tu esencia natural para que escales siendo 100% tú.
          </p>
        </div>

      </div>
    </div>
  </section>

  <!-- Proof of Work Section (Capturas Reales @masinnovaciones) -->
  <section id="prueba-social" class="py-20 md:py-28 border-b border-polar-border bg-polar-surface/40">
    <div class="max-w-5xl mx-auto px-6">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 gap-6">
        <div>
          <p class="font-mono text-xs text-polar-muted uppercase tracking-widest mb-3">02 // PRUEBA REAL & ESTÁNDAR VISUAL @MASINNOVACIONES</p>
          <h2 class="text-3xl sm:text-4xl font-normal tracking-tight text-white">
            Resultados comprobados con millones de reproducciones orgánicas.
          </h2>
        </div>
        <a href="https://www.instagram.com/masinnovaciones/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-full border border-polar-border bg-polar-elevated text-xs font-mono text-white hover:border-zinc-500 transition-colors shrink-0">
          Ver perfil en vivo @masinnovaciones ↗
        </a>
      </div>

      <!-- KPI Strip -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-4 mb-10">
        <div class="polar-card rounded-xl p-4">
          <div class="font-mono text-[11px] text-polar-muted uppercase">TOP REEL VIRAL</div>
          <div class="text-2xl font-medium text-white mt-1">2.4M</div>
          <div class="text-xs text-zinc-400 mt-0.5">Reproducciones orgánicas</div>
        </div>
        <div class="polar-card rounded-xl p-4">
          <div class="font-mono text-[11px] text-polar-muted uppercase">CONSISTENCIA</div>
          <div class="text-2xl font-medium text-white mt-1">1.5M / 1.1M</div>
          <div class="text-xs text-zinc-400 mt-0.5">Múltiples hits en feed</div>
        </div>
        <div class="polar-card rounded-xl p-4">
          <div class="font-mono text-[11px] text-polar-muted uppercase">RETENCIÓN BASE</div>
          <div class="text-2xl font-medium text-white mt-1">300K – 892K</div>
          <div class="text-xs text-zinc-400 mt-0.5">Promedio de piezas clave</div>
        </div>
        <div class="polar-card rounded-xl p-4">
          <div class="font-mono text-[11px] text-polar-muted uppercase">IDENTIDAD</div>
          <div class="text-2xl font-medium text-white mt-1">100%</div>
          <div class="text-xs text-zinc-400 mt-0.5">Adaptado a tu esencia</div>
        </div>
      </div>

      <!-- 3 Capturas Reales de Grid @masinnovaciones -->
      <div class="space-y-8">
        
        <!-- Bloque 1 -->
        <div class="polar-card rounded-2xl overflow-hidden">
          <div class="px-6 py-4 border-b border-polar-border flex flex-wrap items-center justify-between gap-2 bg-polar-bg/60">
            <div class="flex items-center gap-3">
              <span class="font-mono text-xs text-white">BLOQUE 01 // REELS DE ALTO ALCANCE</span>
              <span class="hidden sm:inline-block font-mono text-[11px] text-emerald-400 bg-emerald-400/10 px-2.5 py-0.5 rounded-full">2.4M · 1.5M · 1.1M · 892K vistas</span>
            </div>
            <button type="button" onclick="openImageModal('Screenshot 2026-11-16 174812.png', 'Bloque 01 — Piezas virales de 2.4M, 1.5M y 1.1M de vistas')" class="font-mono text-xs text-polar-muted hover:text-white transition-colors">
              Ampliar captura ↗
            </button>
          </div>
          <div class="p-3 sm:p-4 bg-black cursor-zoom-in" onclick="openImageModal('Screenshot 2026-11-16 174812.png', 'Bloque 01 — Piezas virales de 2.4M, 1.5M y 1.1M de vistas')">
            <img src="Screenshot 2026-11-16 174812.png" alt="Métricas reales MasInnovaciones 2.4M y 1.5M vistas" class="w-full h-auto rounded-lg border border-zinc-900" loading="lazy" />
          </div>
        </div>

        <!-- Bloque 2 -->
        <div class="polar-card rounded-2xl overflow-hidden">
          <div class="px-6 py-4 border-b border-polar-border flex flex-wrap items-center justify-between gap-2 bg-polar-bg/60">
            <div class="flex items-center gap-3">
              <span class="font-mono text-xs text-white">BLOQUE 02 // CONSISTENCIA DE FEED</span>
              <span class="hidden sm:inline-block font-mono text-[11px] text-zinc-300 bg-zinc-800 px-2.5 py-0.5 rounded-full">396K · 314K · 268K · 266K vistas</span>
            </div>
            <button type="button" onclick="openImageModal('Screenshot 2026-11-16 174701.png', 'Bloque 02 — Tracción sostenida entre 140K y 396K vistas por pieza')" class="font-mono text-xs text-polar-muted hover:text-white transition-colors">
              Ampliar captura ↗
            </button>
          </div>
          <div class="p-3 sm:p-4 bg-black cursor-zoom-in" onclick="openImageModal('Screenshot 2026-11-16 174701.png', 'Bloque 02 — Tracción sostenida entre 140K y 396K vistas por pieza')">
            <img src="Screenshot 2026-11-16 174701.png" alt="Métricas reales MasInnovaciones 396 mil y 314 mil vistas" class="w-full h-auto rounded-lg border border-zinc-900" loading="lazy" />
          </div>
        </div>

        <!-- Bloque 3 -->
        <div class="polar-card rounded-2xl overflow-hidden">
          <div class="px-6 py-4 border-b border-polar-border flex flex-wrap items-center justify-between gap-2 bg-polar-bg/60">
            <div class="flex items-center gap-3">
              <span class="font-mono text-xs text-white">BLOQUE 03 // RETENCIÓN & AUTORIDAD</span>
              <span class="hidden sm:inline-block font-mono text-[11px] text-zinc-300 bg-zinc-800 px-2.5 py-0.5 rounded-full">502K · 415K · 332K · 321K vistas</span>
            </div>
            <button type="button" onclick="openImageModal('Screenshot 2026-11-16 174611.png', 'Bloque 03 — Retención sostenida con piezas de 502K y 415K vistas')" class="font-mono text-xs text-polar-muted hover:text-white transition-colors">
              Ampliar captura ↗
            </button>
          </div>
          <div class="p-3 sm:p-4 bg-black cursor-zoom-in" onclick="openImageModal('Screenshot 2026-11-16 174611.png', 'Bloque 03 — Retención sostenida con piezas de 502K y 415K vistas')">
            <img src="Screenshot 2026-11-16 174611.png" alt="Métricas reales MasInnovaciones 502 mil y 415 mil vistas" class="w-full h-auto rounded-lg border border-zinc-900" loading="lazy" />
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Qualification Funnel / Questionnaire Section -->
  <section id="aplicar" class="py-20 md:py-28">
    <div class="max-w-3xl mx-auto px-6">
      
      <div class="text-center mb-12 space-y-3">
        <p class="font-mono text-xs text-polar-muted uppercase tracking-widest">03 // FILTRO DE APLICACIÓN DIRECTA</p>
        <h2 class="text-3xl sm:text-4xl font-normal tracking-tight text-white">
          Aplica para tu edición ilimitada y prueba gratis
        </h2>
        <p class="text-sm sm:text-base text-polar-muted max-w-xl mx-auto">
          Responde 4 preguntas breves para auditar tu perfil y habilitar tu acceso directo a WhatsApp con Bruno.
        </p>
      </div>

      <!-- Interactive Form Card -->
      <div class="polar-card rounded-2xl p-6 sm:p-10 shadow-2xl">
        
        <!-- Progress Bar -->
        <div class="mb-8">
          <div class="flex justify-between font-mono text-xs text-polar-muted mb-2">
            <span id="step-label">PASO 1 DE 4</span>
            <span id="step-percent">25%</span>
          </div>
          <div class="w-full h-1 bg-polar-elevated rounded-full overflow-hidden">
            <div id="progress-bar" class="h-full bg-white transition-all duration-300" style="width: 25%"></div>
          </div>
        </div>

        <form id="qualification-form" onsubmit="return false;">
          
          <!-- Step 1: Social Handle -->
          <div class="form-step space-y-6" data-step="1">
            <div>
              <label for="ig-handle" class="block text-lg font-medium text-white mb-2">
                1. ¿Cuál es tu usuario de Instagram o red principal?
              </label>
              <p class="text-xs text-polar-muted mb-4">
                Lo revisaremos antes de hablar para identificar tus ángulos de monetización actuales.
              </p>
              <input type="text" id="ig-handle" placeholder="@tuusuario" required
                class="w-full px-4 py-3.5 rounded-xl bg-polar-bg border border-polar-border text-white placeholder-zinc-600 focus:outline-none focus:border-white transition-colors font-mono text-sm" />
            </div>
            <div class="flex justify-end">
              <button type="button" onclick="nextStep(2)" class="px-6 py-3 rounded-full bg-white text-black text-sm font-medium hover:bg-zinc-200 transition-colors">
                Siguiente →
              </button>
            </div>
          </div>

          <!-- Step 2: Volume & Goal -->
          <div class="form-step hidden space-y-6" data-step="2">
            <div>
              <label class="block text-lg font-medium text-white mb-2">
                2. ¿Qué volumen de contenido buscas publicar al mes?
              </label>
              <p class="text-xs text-polar-muted mb-4">
                Selecciona el ritmo con el que quieres testear ángulos en tu industria.
              </p>
              <div class="space-y-3" id="volume-options">
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="volume" value="12 a 15 videos/mes (3-4 por semana)" class="accent-white w-4 h-4">
                  <span class="text-sm text-zinc-200">12 a 15 videos/mes (3–4 por semana)</span>
                </label>
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="volume" value="20 a 30 videos/mes (Diario)" class="accent-white w-4 h-4" checked>
                  <span class="text-sm text-zinc-200">20 a 30 videos/mes (Publicación diaria — Recomendado)</span>
                </label>
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="volume" value="+30 videos/mes (Omnipresencia multi-plataforma)" class="accent-white w-4 h-4">
                  <span class="text-sm text-zinc-200">+30 videos/mes (Reels + TikTok + Shorts)</span>
                </label>
              </div>
            </div>
            <div class="flex justify-between">
              <button type="button" onclick="prevStep(1)" class="px-5 py-3 rounded-full border border-polar-border text-zinc-400 text-sm hover:text-white transition-colors">
                ← Atrás
              </button>
              <button type="button" onclick="nextStep(3)" class="px-6 py-3 rounded-full bg-white text-black text-sm font-medium hover:bg-zinc-200 transition-colors">
                Siguiente →
              </button>
            </div>
          </div>

          <!-- Step 3: Monetization / Bottleneck -->
          <div class="form-step hidden space-y-6" data-step="3">
            <div>
              <label class="block text-lg font-medium text-white mb-2">
                3. ¿Cuál es tu enfoque principal hoy al delegar tu edición?
              </label>
              <p class="text-xs text-polar-muted mb-4">
                Esto define cómo estructuraremos tus ganchos y llamados a la acción.
              </p>
              <div class="space-y-3" id="goal-options">
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="goal" value="Vender mis servicios, mentorías o infoproductos" class="accent-white w-4 h-4" checked>
                  <span class="text-sm text-zinc-200">Vender mis servicios, mentorías o productos digitales</span>
                </label>
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="goal" value="Recuperar mi tiempo y mantener consistencia sin editar yo" class="accent-white w-4 h-4">
                  <span class="text-sm text-zinc-200">Recuperar mi tiempo y dejar de editar yo mismo</span>
                </label>
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="goal" value="Posicionar mi marca personal como referente de mi nicho" class="accent-white w-4 h-4">
                  <span class="text-sm text-zinc-200">Posicionar mi marca personal como autoridad en mi industria</span>
                </label>
              </div>
            </div>
            <div class="flex justify-between">
              <button type="button" onclick="prevStep(2)" class="px-5 py-3 rounded-full border border-polar-border text-zinc-400 text-sm hover:text-white transition-colors">
                ← Atrás
              </button>
              <button type="button" onclick="nextStep(4)" class="px-6 py-3 rounded-full bg-white text-black text-sm font-medium hover:bg-zinc-200 transition-colors">
                Siguiente →
              </button>
            </div>
          </div>

          <!-- Step 4: Budget Filter -->
          <div class="form-step hidden space-y-6" data-step="4">
            <div>
              <label class="block text-lg font-medium text-white mb-2">
                4. Nuestros planes de edición ilimitada comienzan en $169 USD/mes.
              </label>
              <p class="text-xs text-polar-muted mb-4">
                Incluye auditoría de ángulos, entregas en 48–72h, revisiones ilimitadas y tu <strong class="text-white">primer video editado gratis</strong> antes de pagar. ¿Cuentas con este presupuesto para invertir hoy?
              </p>
              <div class="space-y-3">
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-emerald-500/60 cursor-pointer transition-colors">
                  <input type="radio" name="budget" value="qualified" class="accent-white w-4 h-4" checked>
                  <span class="text-sm text-white font-medium">Sí, cuento con el presupuesto y quiero mi prueba gratis</span>
                </label>
                <label class="flex items-center gap-3 p-4 rounded-xl border border-polar-border bg-polar-bg hover:border-zinc-500 cursor-pointer transition-colors">
                  <input type="radio" name="budget" value="unqualified" class="accent-white w-4 h-4">
                  <span class="text-sm text-zinc-400">Por ahora no cuento con ese presupuesto mensual</span>
                </label>
              </div>
            </div>
            <div class="flex justify-between items-center pt-2">
              <button type="button" onclick="prevStep(3)" class="px-5 py-3 rounded-full border border-polar-border text-zinc-400 text-sm hover:text-white transition-colors">
                ← Atrás
              </button>
              <button type="button" onclick="evaluateApplication()" class="px-7 py-3.5 rounded-full bg-white text-black text-sm font-medium hover:bg-zinc-200 transition-colors">
                Finalizar aplicación →
              </button>
            </div>
          </div>

          <!-- Result: Qualified -> Direct WhatsApp -->
          <div id="result-qualified" class="hidden text-center py-6 space-y-6">
            <div class="w-12 h-12 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 flex items-center justify-center mx-auto font-mono text-lg">
              ✓
            </div>
            <div class="space-y-2">
              <span class="font-mono text-xs text-emerald-400 uppercase tracking-widest">PERFIL CALIFICADO</span>
              <h3 class="text-2xl font-medium text-white">Tu cupo para prueba gratis está habilitado</h3>
              <p class="text-sm text-polar-muted max-w-md mx-auto">
                Haz clic abajo para abrir chat directo con Bruno en WhatsApp con los datos de tu perfil ya cargados y coordinar tu primer video sin costo.
              </p>
            </div>
            <div>
              <a id="whatsapp-cta" href="#" target="_blank" rel="noopener noreferrer"
                class="inline-flex items-center justify-center gap-2 w-full sm:w-auto px-8 py-4 rounded-full bg-white text-black text-sm font-medium hover:bg-zinc-200 transition-all">
                <span>Hablar con Bruno por WhatsApp</span>
                <span>↗</span>
              </a>
            </div>
            <p class="font-mono text-[11px] text-zinc-500">
              Respuesta directa 1 a 1 · Sin compromiso de permanencia
            </p>
          </div>

          <!-- Result: Unqualified -> Nurture Channel -->
          <div id="result-unqualified" class="hidden text-center py-6 space-y-6">
            <div class="w-12 h-12 rounded-full bg-zinc-800 border border-polar-border text-zinc-400 flex items-center justify-center mx-auto font-mono text-lg">
              +
            </div>
            <div class="space-y-2">
              <span class="font-mono text-xs text-polar-muted uppercase tracking-widest">RECURSOS GRATUITOS</span>
              <h3 class="text-2xl font-medium text-white">Gracias por tu interés en +CONTENIDO</h3>
              <p class="text-sm text-polar-muted max-w-md mx-auto">
                Cuando estés listo para delegar tu producción diaria, aquí estaremos. Mientras tanto, sigue nuestras estructuras y análisis gratuitos en Instagram.
              </p>
            </div>
            <div>
              <a href="https://www.instagram.com/masinnovaciones/" target="_blank" rel="noopener noreferrer"
                class="inline-flex items-center justify-center gap-2 px-6 py-3.5 rounded-full border border-polar-border bg-polar-bg text-white text-sm hover:border-zinc-500 transition-colors">
                Ir a @masinnovaciones en Instagram ↗
              </a>
            </div>
          </div>

        </form>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer class="border-t border-polar-border py-12 bg-polar-bg">
    <div class="max-w-5xl mx-auto px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
      <div class="flex items-center gap-2">
        <span class="font-mono text-xs text-white">+CONTENIDO</span>
        <span class="text-polar-border">·</span>
        <span class="font-mono text-xs text-polar-muted">MASINNOVACIONES</span>
      </div>
      <div class="flex items-center gap-6">
        <span class="font-mono text-xs text-zinc-500">© 2026 Todos los derechos reservados.</span>
      </div>
    </div>
  </footer>

  <!-- Lightbox Modal for Fullscreen Captures -->
  <div id="image-modal" class="fixed inset-0 z-50 hidden bg-black/95 backdrop-blur-md flex items-center justify-center p-4" onclick="closeImageModal()">
    <div class="relative w-full max-w-5xl bg-polar-surface border border-polar-border rounded-2xl overflow-hidden shadow-2xl" onclick="event.stopPropagation()">
      <div class="px-5 py-3.5 border-b border-polar-border flex items-center justify-between bg-polar-bg">
        <span id="modal-caption" class="font-mono text-xs text-white">Vista ampliada</span>
        <button type="button" onclick="closeImageModal()" class="w-8 h-8 rounded-full border border-polar-border text-zinc-400 hover:text-white flex items-center justify-center font-mono text-xs">
          ✕
        </button>
      </div>
      <div class="p-3 bg-black max-h-[82vh] overflow-y-auto flex justify-center">
        <img id="modal-img" src="" alt="Vista ampliada" class="w-full h-auto rounded-lg" />
      </div>
    </div>
  </div>

  <script>
    const WHATSAPP_NUMBER = "524445544111";

    function openImageModal(src, caption) {
      const modal = document.getElementById('image-modal');
      const img = document.getElementById('modal-img');
      const cap = document.getElementById('modal-caption');
      img.src = src;
      cap.textContent = caption;
      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeImageModal() {
      const modal = document.getElementById('image-modal');
      modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape') closeImageModal();
    });

    function showStep(stepNumber) {
      document.querySelectorAll('.form-step').forEach(el => el.classList.add('hidden'));
      const target = document.querySelector(`.form-step[data-step="${stepNumber}"]`);
      if (target) target.classList.remove('hidden');

      const percent = stepNumber * 25;
      document.getElementById('step-label').textContent = `PASO ${stepNumber} DE 4`;
      document.getElementById('step-percent').textContent = `${percent}%`;
      document.getElementById('progress-bar').style.width = `${percent}%`;
    }

    function nextStep(stepNumber) {
      if (stepNumber === 2) {
        const handleInput = document.getElementById('ig-handle');
        if (!handleInput.value.trim()) {
          handleInput.focus();
          handleInput.classList.add('border-red-500');
          return;
        }
        handleInput.classList.remove('border-red-500');
      }
      showStep(stepNumber);
    }

    function prevStep(stepNumber) {
      showStep(stepNumber);
    }

    function evaluateApplication() {
      const handleRaw = document.getElementById('ig-handle').value.trim();
      const handle = handleRaw.startsWith('@') ? handleRaw : `@${handleRaw}`;
      const volume = document.querySelector('input[name="volume"]:checked')?.value || '';
      const goal = document.querySelector('input[name="goal"]:checked')?.value || '';
      const budget = document.querySelector('input[name="budget"]:checked')?.value || 'unqualified';

      document.querySelectorAll('.form-step').forEach(el => el.classList.add('hidden'));
      document.getElementById('step-label').textContent = 'COMPLETADO';
      document.getElementById('step-percent').textContent = '100%';
      document.getElementById('progress-bar').style.width = '100%';

      if (budget === 'qualified') {
        const message = `Hola Bruno, acabo de aplicar a +CONTENIDO y quiero mi primer video editado gratis.\n\n• Perfil: ${handle}\n• Volumen buscado: ${volume}\n• Enfoque: ${goal}`;
        const waUrl = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(message)}`;
        
        document.getElementById('whatsapp-cta').href = waUrl;
        document.getElementById('result-qualified').classList.remove('hidden');
      } else {
        document.getElementById('result-unqualified').classList.remove('hidden');
      }
    }
  </script>
</body>
</html>
