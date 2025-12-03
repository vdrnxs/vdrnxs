<!-- header-animated.svg -->
<svg viewBox="0 0 800 400" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes gradient { /* tu gradient */ }
    @keyframes fadeIn { /* tu fade-in */ }
    .hero { animation: fadeIn 1s ease-out; }
  </style>
  
  <foreignObject width="800" height="400">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <h1 class="hero">a4n Labs</h1>
      <p>Freelance developer • Fintech & DeFi specialist</p>
    </div>
  </foreignObject>

  <foreignObject x="0" y="0" width="400" height="300">
  <div xmlns="http://www.w3.org/1999/xhtml" style="width:100%; height:100%;">
    <style>
      .gradient-box {
        background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
        background-size: 600% 400%;
        animation: gradient 15s ease infinite;
        width: 100%;
        height: 100%;
      }
      @keyframes gradient {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
      }
    </style>
    <div class="gradient-box"></div>
  </div>
</foreignObject>
</svg>
```

### Opción 3: Mantener el HTML como landing (ACTUAL)

Tu HTML actual es excelente como landing page. Solo sincroniza con GitHub via README que linkee a él.

---

## Mi recomendación específica para TI (Adrien)

Dado que:
- Estás construyendo **portfolio para mercado laboral español**
- Necesitas mostrar **habilidades técnicas reales**
- El HTML está **muy pulido ya**

**Yo haría esto:**

### 1️⃣ Mantén el HTML donde está (portfolio.com)
- Es tu landing page profesional
- Mantiene toda la interactividad

### 2️⃣ Crea un README estratégico en GitHub
- Minimalista y elegante (como tu estilo)
- 1-2 SVGs animados (header + stats)
- Links a tu portfolio completo
- Muestra proyectos destacados

### 3️⃣ Estructura así:
```
README.md (lo que ves en GitHub)
├── SVG Header animado
├── About (breve)
├── Tech stack (badges)
├── Featured projects (con links)
├── GitHub Stats
└── Contact + Links

