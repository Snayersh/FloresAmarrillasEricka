# 🌻 Galaxia de Amor y Flores Amarillas • Para Ericka

Una experiencia interactiva y cinematográfica en 3D desarrollada con **Three.js**, **WebGL**, **GSAP** y **Canvas-Confetti**, diseñada como un homenaje romántico donde una espiral cósmica dorada cobija girasoles interactivos, cartas de amor, un corazón latiente en el núcleo y música de fondo.

---

## ✨ Características Principales

1. **🌌 Galaxia Espiral Dorada**:
   - Más de 12,000 partículas distribuidas en brazos espirales logarítmicos con gradientes de oro pulido (`#FFD700`), amarillo girasol (`#FFC107`), ámbar cálido y blanco estelar.
   - Rotación cósmica lenta y suave en tiempo real.

2. **💛 Núcleo del Corazón Paramétrico Latiente**:
   - Un corazón tridimensional paramétrico en el centro de la galaxia compuesto por más de 2,800 partículas brillantes.
   - Simulación de latido cardíaco vital (sístole y diástole con modulación de luz puntual ámbar) mediante funciones senoidales continuas.

3. **🌻 Girasoles Procedurales en Órbita**:
   - Texturas de girasoles hiperrealistas generadas proceduralmente mediante Canvas 2D en alta resolución (sin depender de imágenes externas lentas).
   - Patrón botánico de filotaxis de Fermat en el centro del disco y múltiples capas de pétalos dorados basados en secuencias de Fibonacci.
   - 7 girasoles orbitando en trayectorias elípticas inclinadas con halos luminosos (*glow billboards*).

4. **💌 Sistema de Cartas de Amor Glassmorphism**:
   - Cada girasol custodia un capítulo romántico con títulos caligráficos ('Dancing Script'), marco fotográfico e inspiradores párrafos poéticos.
   - Vuelo cinemático de cámara con **GSAP** que hace zoom hacia el girasol seleccionado antes de abrir la carta.
   - Explosión de pétalos amarillos y chispas doradas con **Canvas-Confetti** al desplegar cada carta.

5. **🍃 Lluvia de Pétalos en Primer Plano**:
   - Más de 60 pétalos en 3D curvados flotando y rotando suavemente con la brisa espacial alrededor de la cámara.

6. **🎵 Reproductor de Audio Flotante con Doble Motor**:
   - Reproductor minimalista con disco de vinilo giratorio y barras de ondas ecualizadoras animadas en CSS.
   - Doble soporte: pista romántica predeterminada + **Sintetizador Romántico Web Audio API** que genera una progresión ambiental en caso de ausencia de red o bloqueos de CORS.

7. **📱 Controles Intuitivos y Responsivos**:
   - Navegación orbital completa con límites y amortiguación (*damping*).
   - Botón de recentrado para volver a la vista general en cualquier momento.
   - Compatible con pantallas táctiles móviles y escritorio.

---

## 🛠️ Tecnologías Empleadas

- **Three.js (r128)** & **OrbitControls**
- **GSAP 3.12+**
- **Canvas-Confetti**
- **Google Fonts** ('Cinzel', 'Dancing Script', 'Montserrat')
- **FontAwesome 6**

---

## 🚀 Ejecución

Simplemente abre el archivo `index.html` en cualquier navegador moderno o sírvelo con cualquier servidor web:

```bash
# Con Python
python3 -m http.server 8080

# Con Node / npx
npx serve .
```

---
Hecho con todo el amor del universo para **Ericka** ❤️
