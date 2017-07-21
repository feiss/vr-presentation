
# Realidad Virtual 101

Diego F. Goberna | [@feiss](http://twitter.com/feiss) | [feiss.be](http://feiss.be)

<!-- NOTES -->
Breve introducción a VR
Situación / posibilidades a hoy en día

------

# Qué es la Realidad Virtual?

<!-- NOTES -->
- Preguntar cuántos probaron la VR.
- Plataforma HW+SW que permite simular la presencia física del usuario en un entorno "virtual" o distinto al real.
- Cambiará cómo jugamos, trabajamos y nos comunicamos. 

------
<!-- .slide -->

# Aplicaciones prácticas

---

## Entretenimiento 

- Juegos
- Películas
- Conciertos y eventos
- ...

---

## Medicina y psicología 

- Tratamiento de fobias
- Estudio del comportamiento
- Cambios de perspectiva
- Estudios y control de la percepción
- Tratamiento del dolor
- ...


---

## Productividad 
## Publicidad

---

## Divulgación y enseñanza

- Centros educativos
- Museos
- Lugares de interés
- ...

---

## Arte

- Creaciones artísticas
- Exposiciones
- ...

---

## Simuladores de tareas

- Oficios
- Destrezas
- ...

---

## Comunicación

- Chats y videoconferencias
- Redes sociales (Metaverso)
- Trabajo a distancia
- ...

------

# Consideraciones

- Malestar físico
- Privacidad
- Problemas sociales y éticos

------

# Elementos

---

## Pantalla(s)

<img data-src="media/img/vrscreens.jpg">

- 2 pantallas alta resolución
- Mínimo 90 FPS
- Persistencia píxel < 3ms
- Baja latencia input-output

---

## Sensores y Tracking 

- Cabeza | Manos | otros
- Outside-In / Inside-out
- Giroscopio | Acelerómetro | Cámara | LED | Láser

---

[Diagrama chachi]

------

# Dispositivos

---

| 3DOF | 3DOF +  MANDOS | 6DOF <br> Outside-In (Room Scale) | 6DOF <br> Inside-Out |
|------|------|------|------|
| - Móviles <br> - Cardboard | - Daydream <br> - Gear VR | - HTC Vive <br> - Oculus <br> - PSX VR <br> - OSVR | - iPhone 7* <br> - Hololens* |

---

[tabla comparativa]

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

# Enlaces

- Mozilla VR: [mozvr.com](http://mozvr.com)
- WebVR: [webvr.info](http://webvr.info) y [webvr.rocks](http://webvr.rocks)
- Noticias: [realovirtual.com](http://realovirtual.com), [uploadvr.com](http://uploadvr.com), [roadtovr.com](http://roadtovr.com)

------

## Gracias! :)