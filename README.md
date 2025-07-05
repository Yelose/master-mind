# master-mind

Mastermind game 1p vs pc local | JavaScript | Html5 | Sass

# 🎯 Mastermind – Proyecto Personalizado

Este es un proyecto en desarrollo inspirado en el clásico juego de lógica **Mastermind**, creado con **HTML**, **SCSS** y **JavaScript puro**.  
Actualmente es un proyecto base funcional con mecánicas básicas, pero tiene una hoja de ruta clara para convertirse en una versión más rica, estratégica y rejugable.

---

## 🚧 Estado actual del proyecto

✅ Proyecto base funcional:

- Generación de combinación secreta aleatoria.
- Elección del número de chinchetas (longitud del código).
- Elección del número de colores disponibles.
- El jugador puede comprobar intentos y ver los resultados.

⏳ En desarrollo:

- Sistema de puntuación inteligente por partida.
- Registro de récords por dificultad.
- Guardado y recuperación del progreso.
- Interfaz visual más elaborada.

---

## 🎯 Objetivo del proyecto

Desarrollar una versión personalizada de Mastermind centrada en la **estrategia, eficiencia y mejora personal**, con un sistema de **puntuación dinámica** y **récords por dificultad**.

### 📌 Idea principal del modo personalizado

- Cada partida otorga una **puntuación individual**, calculada en función de la **dificultad** (colores y chinchetas) y la **cantidad de intentos** usados.
- El jugador acumula puntos hasta alcanzar un máximo de **100**.
- Cuando el jugador llega a 100 puntos, puede **guardar su récord** según dificultad.
- Si lo desea, puede **guardar su progreso** antes de agotar los puntos.
- Los récords se mostrarán por configuración de dificultad (por ejemplo: `5x4 → 12 partidas`).

---

## 📈 Hoja de ruta y próximos pasos

- [ ] ✅ Terminar lógica básica de juego
- [ ] 🔢 Implementar sistema de puntuación por partida
- [ ] 💾 Guardar puntuaciones y progreso en `localStorage`
- [ ] 🧠 Crear algoritmo de puntuación según dificultad e intentos
- [ ] 🧱 Mostrar los récords por dificultad en el lateral
- [ ] 🔁 Permitir guardar y continuar progreso actual
- [ ] 🧼 Añadir botón para reiniciar progreso
- [ ] 🎨 Mejorar diseño visual y usabilidad
- [ ] 🚀 Preparar despliegue en GitHub Pages

---

## 🕹️ Instrucciones del juego clásico (versión base)

1. Selecciona el número de **chinchetas** (longitud del código) y el número de **colores disponibles**.
2. Pulsa **"Nueva Partida"** para generar una combinación secreta.
3. Elige tus colores para formar un intento y pulsa **"Comprobar"**.
4. El sistema te mostrará cuántos colores están en la posición correcta y cuántos están mal colocados.
5. Repite hasta acertar la combinación.  
   No hay límite de intentos en esta versión.

---

## 💡 Instrucciones del modo personalizado (en desarrollo)

1. Elige la dificultad (colores y chinchetas).
2. Completa tantas partidas como puedas con el menor número de intentos.
3. Cada partida te otorga una **puntuación dinámica**.
4. El objetivo es **acumular hasta 100 puntos sin fallar demasiado**.
5. Cuando llegas a 100, se guarda tu **récord** por dificultad.
6. También puedes **guardar tu progreso** manualmente en cualquier momento.
7. Tu historial de récords se mostrará en el lateral de la pantalla.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- SCSS (Sass)
- JavaScript vanilla
- GitHub Pages para el despliegue

---

## 📄 Licencia

Este proyecto está disponible bajo la licencia MIT.
