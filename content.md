
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

# VR vs AR

<img src="media/img/vrar.png">

------

# Elementos

---

## Pantalla(s)

<img data-src="media/img/vrscreens.jpg">

- 2 pantallas/imágenes alta resolución
- Mínimo 90 fps
- Persistencia píxel < 3ms
- Baja latencia input-output

---

## Sensores y Tracking 

- Cabeza | Manos | otros
- Outside-In / Inside-out
- Giroscopio | Acelerómetro | Cámara | LED | Láser

---

<a href="media/img/vrflow.png"><img src="media/img/vrflow.png"></a>

------

# Dispositivos


---

## Cardboard y similares

<div class="sideimg">
  <div class="images">
    <img src="media/img/cardboard.png" class="sideimg">
  </div>
  <div>
    <ul>
      <li>Casco de cartón* donde metes el teléfono</li>
      <li>3DOF</li>
      <li>Fijar la mirada</li>
    </ul>
  </div>
</div>
---

## Gear VR / Daydream


<div class="sideimg">
  <div class="images">
    <img src="media/img/gearvr.png">
    <img src="media/img/daydream.png">
  </div>
  <div>
    <ul>
      <li>Cascos de plástico donde metes el teléfono</li>
      <li>3DOF</li>
      <li>Mandos 3DOF</li>
    </ul>
  </div>
</div>

---

## Playstation VR / OSVR / Oculus / HTC Vive


<div class="sideimg">
  <div class="images small">
    <img src="media/img/playstation.png">
    <img src="media/img/oculus.png">
    <img src="media/img/vive.png">
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

## iPhone - iPad / Hololens




<div class="sideimg">
  <div class="">
    <img src="media/img/iphone.jpg">
    <img src="media/img/hololens.jpg">
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

<a href="media/img/comparativa.png"><img src="media/img/comparativa.png"></a>

------

# Desarrollo VR

---

## Nativo (OpenGL / DirectX)

- Unity / Unreal / CryEngine / libGDX  / otros / a pinrel

<!-- NOTES -->
Ventajas: 
- Rendimiento
- Buenas herramientas

Desventajas:
- Distribución y versionado
- Iteración y prototipado


---

## Web (WebGL + WebVR)

- Three.js &rarr; A-Frame, ReactVR 
- Babylon.js
- Blend4Web

<!-- NOTES -->

Ventajas:
- Rápida iteración y prototipado
- Fácil e inmediata distribución y versionado
- API Javascript

Desventajas: 
- Rendimiento
- Sin pipeline (mejorando)

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

------

# Consideraciones

- Malestar físico
- Privacidad
- Problemas sociales y éticos

------

# Enlaces

- Mozilla VR: [mozvr.com](http://mozvr.com)
- Google VR: [vr.google.com](http://vr.google.com)
- WebVR: [webvr.info](http://webvr.info) y [webvr.rocks](http://webvr.rocks)
- Noticias: [realovirtual.com](http://realovirtual.com), [uploadvr.com](http://uploadvr.com), [roadtovr.com](http://roadtovr.com)

------

## Gracias! :)

### ¿preguntas?