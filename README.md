# 🌻 Galaxia de Amor y Flores Amarillas • Para Ericka

Una experiencia interactiva y cinematográfica en 3D desarrollada con **Three.js**, **WebGL**, **GSAP** y **Canvas-Confetti**, diseñada como un homenaje romántico donde una espiral cósmica dorada cobija girasoles botánicos realistas, cartas de amor, un corazón latiente en el núcleo y música de fondo.

---

## ✨ Características Principales

1. **💖 Galaxia Dorada en Forma de Corazón**:
   - Más de 16,500 partículas estelares distribuidas mediante curvas paramétricas que, al ser observadas desde arriba o en perspectiva elevada, forman un **espectacular corazón cósmico dorado**.
   - Botón interactivo de **"Vista Corazón"** para orientar la cámara inmediatamente hacia la perspectiva cenital perfecta.
   - Rotación lenta y armónica en tiempo real.

2. **🌻 Girasoles Botánicos Realistas en 3D**:
   - Modelos tridimensionales con **tallo verde curvado orgánico**, **hojas botánicas con nervaduras**, **sépalos verdes en el cáliz**, y **dos capas concéntricas de pétalos dorados** (24 exteriores y 22 interiores escalonados con degradado cálido).
   - Centro botánico 3D oscuro y afelpado con filotaxis áurea de Fermat (600 semillas y polen dorado).
   - Destellos y motes de polen mágico flotando alrededor de cada flor en lugar de halos planos que lavan la imagen.

3. **💛 Núcleo del Corazón Paramétrico Latiente**:
   - Un corazón tridimensional paramétrico en el centro de la galaxia compuesto por más de 3,000 partículas brillantes.
   - Simulación de latido cardíaco vital sístole/diástole (`Math.sin`) con luz ámbar pulsante.

4. **💌 Sistema de Cartas de Amor Glassmorphism**:
   - Cada girasol custodia un capítulo romántico con títulos caligráficos ('Dancing Script'), marco fotográfico e inspiradores párrafos poéticos.
   - Vuelo cinemático de cámara con **GSAP** que hace zoom hacia el girasol seleccionado antes de abrir la carta.
   - Explosión de pétalos amarillos y chispas doradas con **Canvas-Confetti** al desplegar cada carta.

5. **🍃 Lluvia de Pétalos en Primer Plano**:
   - 65 pétalos 3D flotando y rotando suavemente con la brisa espacial alrededor de la cámara.

6. **🎵 Reproductor de Audio Flotante con Doble Motor**:
   - Reproductor minimalista con disco de vinilo giratorio y barras de ondas ecualizadoras animadas en CSS.
   - Doble soporte: pista romántica predeterminada + **Sintetizador Romántico Web Audio API** que genera una progresión ambiental en caso de ausencia de red o bloqueos de CORS.

7. **📱 Controles Intuitivos y Responsivos**:
   - Navegación orbital suave con límites y amortiguación (*damping*).
   - Botón de vista corazón y botón de recentrado.
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

Simplemente abre el archivo `index.html` en cualquier navegador moderno o ejecútalo con un servidor local:

```bash
# Con Python
python3 -m http.server 8080

# Con Node / npx
npx serve .
```

---
Hecho con todo el amor del universo para **Ericka** ❤️
