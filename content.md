
# Una introducción a la Realidad Virtual

Diego F. Goberna | [@feiss](http://twitter.com/feiss) | [feiss.be](http://feiss.be)

<!-- NOTES -->
Charla = breve introducción a VR
Situación / posibilidades a hoy en día

------

# Qué es la Realidad Virtual?

<!-- NOTES -->
- Preguntar cuántos probaron la VR.
- Plataforma HW+SW que permite simular la presencia física del usuario en un entorno "virtual" o distinto al real.
- Cambiará cómo jugamos, trabajamos y nos comunicamos. 

---

 Arquitectura HW + SW que permite al usuario *sentir* que está en otro entorno diferente al real.

---

<img data-src="media/img/virtuality.png">

------

# Elementos

---

## Pantalla(s)

<img data-src="media/img/vrscreens.jpg">

- 1 imagen por ojo (alta resolución)
- Mínimo 90 fps
- Persistencia píxel < 3ms
- Baja latencia input-output

---

## Sensores y Tracking 

- Cabeza | Manos | otros
- Outside-In / Inside-out
- Giroscopio | Acelerómetro | Cámara | LED | Láser

---

<a href="media/img/vrflow.png"><img data-src="media/img/vrflow.png"></a>

------

# Dispositivos


---

## Cardboard y similares

<div class="sideimg">
  <div class="images">
    <img data-src="media/img/cardboard.png" class="sideimg">
  </div>
  <div>
    <ul>
      <li>Casco donde metes el teléfono</li>
      <li>3DOF</li>
      <li>Fijar la mirada</li>
    </ul>
  </div>
</div>
---

## Gear VR / Daydream


<div class="sideimg">
  <div class="images">
    <img data-src="media/img/gearvr.png">
    <img data-src="media/img/daydream.png">
  </div>
  <div>
    <ul>
      <li>Casco donde metes un teléfono Samsung, Pixel o similares</li>
      <li>3DOF</li>
      <li>Mandos 3DOF</li>
    </ul>
  </div>
</div>

---

## Playstation VR / OSVR <br> Oculus Rift / HTC Vive


<div class="sideimg">
  <div class="images small">
    <img data-src="media/img/playstation.png">
    <img data-src="media/img/oculus.png">
    <img data-src="media/img/vive.png">
  </div>
  <div>
    <ul>
      <li>Cascos con pantallas incorporadas</li>
      <li>6DOF (Room Scale)</li>
      <li>Mandos 6DOF</li>
      <li>Tracking outside-in</li>
    </ul>
  </div>
</div>


---

## iPhone - iPad <br> Windows Mixed Reality - Hololens

<div class="sideimg">
  <div class="">
    <img data-src="media/img/iphone.jpg">
    <img data-src="media/img/hololens.jpg">
  </div>
  <div>
    <ul>
      <li>AR</li>
      <li>6DOF ( > Room Scale)</li>
      <li>Tracking inside-out</li>
    </ul>
  </div>
</div>

---

## Comparativa

<a href="media/img/comparacion.png"><img data-src="media/img/comparacion.png"></a>

------

# Consumo VR

- Mayoría de títulos indies / pequeños estudios
- Grandes estudios animándose <span class="small">(Valve, Ubisoft, EA, Bethesda, ...)</span>
- Stores / Browsers <span class="small">(Steam, Oculus, Viveport, Samsung VR, Carmel, ...)</span>
- Steam: 1980, Daydream: 150, Cardboard: ∞ 
- [SteamVR Performance Tool](http://store.steampowered.com/app/323910/)
- Windows (MacOS y Linux comenzando)
------

# Desarrollo VR

Igual que una aplicación/juego 3D, salvo:
- Alto rendimiento (90 FPS, alta resolución x 2)
- Cámara muy limitada y siempre en primera persona
- Interacciones con muchas posibilidades
- Dimensiones y distancias reales
- Altas expectativas respecto a interactividad y físicas

---

## Nativo (OpenGL / DirectX)

<img data-src="media/img/engines.png">

<!-- NOTES -->
Ventajas: 
- Rendimiento
- Buenas herramientas

Desventajas:
- Distribución y versionado
- Iteración y prototipado


---

## Web (WebGL + WebVR)

<img data-src="media/img/frameworks.png">

<!-- NOTES -->

Ventajas:
- Rápida iteración y prototipado
- Fácil e inmediata distribución y versionado
- API Javascript

Desventajas: 
- Rendimiento
- Sin pipeline (mejorando)

---

## Soporte Navegadores

- **Windows**
    - Oculus Rift: Firefox Nightly, Chromium
    - HTC Vive: Firefox Nightly, Servo y Chromium
    - Windows Mixed Reality: Edge
- **Mac**
    - Firefox Nightly
- **Linux**
    - HTC Vive: Firefox 56 beta (agosto)

---

- **Android e iOS (9.1)**
   - Chrome/ium, Firefox y Safari
   - GearVR: Samsung Internet y Carmel

- <span>+ info y enlaces:</span> [webvr.rocks](http://webvr.rocks)

---

## Tips

- Todo es 3D (X veces más esfuerzo que 2D)
- Es más fácil hacer los objetos "creíbles"
- Para evitar "mareos":
    - No muevas la cámara ni el escenario (teleport)
    - 90 FPS sin saltos
- Campo abierto para la experimentación
    - Nuevas narrativas
    - Nuevos modelos de UX


------

# Aplicaciones prácticas

- Entretenimiento y Arte <span class="small">(juegos, películas, eventos...)</span>
- Medicina y psicología <span class="small">(fobias, percepción, dolor...)</span>
- Productividad <span class="small">(office, cad..)</span>
- Publicidad
- Divulgación y enseñanza <span class="small">(museos, lugares...)</span>
- Simuladores de tareas <span class="small">(oficios, ejército, habilidades...)</span>
- Comunicación
- ???

<!-- NOTES -->
Entretenimiento y Arte
- Juegos
- Películas
- Conciertos y eventos
- Exposiciones

Medicina y psicología 
- Tratamiento de fobias
- Estudio del comportamiento
- Cambios de perspectiva
- Estudios y control de la percepción
- Tratamiento del dolor

Productividad 
- Office, outlook, etc.

Publicidad

Divulgación y enseñanza
- Centros educativos
- Museos
- Lugares de interés

Simuladores de tareas
- Oficios
- Destrezas

Comunicación
- Chats y videoconferencias
- Redes sociales (Metaverso)
- Trabajo a distancia

---
<a href="media/img/bigscreen.jpg"><img data-src="media/img/bigscreen.jpg"></a>
---
<a href="media/img/coffee.jpg"><img data-src="media/img/coffee.jpg"></a>
---
<a href="media/img/military.jpg"><img data-src="media/img/military.jpg"></a>
---
<a href="media/img/british.jpg"><img data-src="media/img/british.jpg"></a>
---
<a href="media/video/quill.gif"><img data-src="media/video/quill.gif"></a>
---
<a href="media/img/googleearth.jpg"><img data-src="media/img/googleearth.jpg"></a>
---
<a href="media/img/asilo.jpg"><img data-src="media/img/asilo.jpg"></a>
------

# Consideraciones

- Salud <span class="small">(mareo, larga exposición, ...)</span>
- Privacidad <span class="small">(body tracking, pantallas virtuales, ... )</span>
- Problemas sociales y éticos <span class="small">(uso masivo, acoso, ...)</span>

------

# Enlaces

- Mozilla VR: [mozvr.com](http://mozvr.com)
- Google VR: [vr.google.com](http://vr.google.com)
- WebVR: [webvr.info](http://webvr.info) y [webvr.rocks](http://webvr.rocks)
- Noticias: [realovirtual.com](http://realovirtual.com), [uploadvr.com](http://uploadvr.com), [roadtovr.com](http://roadtovr.com), [inside.com/vrar](https://inside.com/vrar)

------

## Gracias!

¿preguntas?
