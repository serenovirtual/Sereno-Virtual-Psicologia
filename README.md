# Sereno Virtual · Psicología

App móvil de bienestar emocional con **un menú de 3 juegos cortos** (1 a 3 minutos cada uno). Cada juego entrena una habilidad distinta que se usa en psicología clínica:

| Juego | Qué entrena | Base psicológica |
|---|---|---|
| **Respira con la Luna** | Calmar el cuerpo | Respiración diafragmática y regulación del sistema nervioso |
| **Detective de Pensamientos** | Ordenar la mente | Terapia Cognitivo-Conductual (TCC): distinguir hechos de interpretaciones |
| **Jardín de Gratitud** | Entrenar lo bueno | Psicología positiva: diario de gratitud |

## Prototipo jugable

`index.html` es un prototipo funcional de los 3 juegos. No necesita instalación: ábrelo en el navegador del celular (o en el modo móvil del navegador de escritorio).

## Publicar gratis con un enlace (sin Play Store)

La app es una **app web instalable (PWA)**: se abre con un enlace y, desde Chrome, se puede agregar a la pantalla de inicio como cualquier app. Funciona sin internet después de la primera visita.

**Activar GitHub Pages (gratis, una sola vez):**
1. En GitHub, abre el repositorio → **Settings** → **Pages**.
2. En *Build and deployment* → *Source*, elige **Deploy from a branch**.
3. En *Branch*, elige la rama con el código (hoy: `claude/sereno-virtual-psychology-games-dyobu8`, o `main` si la crean) y la carpeta **/ (root)**. Pulsa **Save**.
4. En 1 o 2 minutos la app queda en: **https://serenovirtual.github.io/Sereno-Virtual-Psicologia/**

Cada vez que se suban cambios a esa rama, el enlace se actualiza solo.

**Instalarla en el celular:**
- **Android (Chrome):** abre el enlace → menú ⋮ → **Instalar app** (o “Agregar a pantalla de inicio”).
- **iPhone (Safari):** abre el enlace → botón **Compartir** → **Agregar a inicio**.

---

## Los 3 juegos propuestos

### 1. Respira con la Luna 🌕 (calma el cuerpo · 2 min)
- **Cómo se juega:** una luna punteada (la guía) crece y se encoge al ritmo de la respiración. El jugador **mantiene el dedo en la pantalla para inhalar** y **lo suelta para exhalar**. Su propia luna sigue el dedo.
- **Puntaje:** % de *sincronía* con la guía durante 4 ciclos.
- **Modos:** Cuadrada 4·4·4·4 (ansiedad, foco), Relajante 4·7·8 (antes de dormir), Coherente 5·5 (equilibrio).
- **Por qué es original:** no es solo un video de respiración; tocar la pantalla convierte el ejercicio en un reto de ritmo y obliga a prestar atención al cuerpo.

### 2. Detective de Pensamientos 🔍 (ordena la mente · 3 min)
- **Cómo se juega:** aparecen tarjetas con frases como *“Mi amiga no contestó en 3 horas”* o *“Mi amiga ya no me quiere”*. El jugador **desliza a la izquierda si es un HECHO** y **a la derecha si es una INTERPRETACIÓN**, como en una app de citas.
- **Después de cada tarjeta:** explica la distorsión cognitiva (lectura de mente, catastrofización, generalización, etiquetado, “debería”…) y propone un **pensamiento más equilibrado**.
- **Por qué es original:** convierte la técnica central de la TCC en un gesto rápido y familiar (deslizar), con aprendizaje en cada jugada.

### 3. Jardín de Gratitud 🌼 (entrena lo bueno · 1 min)
- **Cómo se juega:** el usuario escribe algo que agradece hoy y **planta una flor única** (color y pétalos al azar). Al tocar una flor se lee lo que escribió ese día.
- **Ayudas:** sugerencias rápidas (“Una persona”, “Algo pequeño”, “Mi cuerpo”, “Un logro”) para quien no sabe qué escribir.
- **Por qué funciona:** crea un hábito diario. El jardín se llena con el tiempo y se convierte en un recuerdo visual de lo bueno.

---

## Otras ideas de juegos (para cambiar o ampliar el menú)

| Idea | Mecánica | Base psicológica |
|---|---|---|
| **Hojas en el Río** | Escribes un pensamiento que te preocupa, lo pones sobre una hoja y lo ves alejarse por el río. | Defusión cognitiva (Terapia de Aceptación y Compromiso, ACT) |
| **Ancla 5-4-3-2-1** | Mini búsqueda del tesoro: nombra 5 cosas que ves, 4 que tocas, 3 que oyes, 2 que hueles, 1 que saboreas. | Técnica de *grounding* para ansiedad y ataques de pánico |
| **Termómetro de Emociones** | Eliges un emoji y su intensidad (0–10); una mascota reacciona y sugiere uno de los otros juegos. | Identificación y registro emocional |
| **Burbujas de Preocupación** | Las preocupaciones caen como burbujas; las separas en “puedo hacer algo” o “no depende de mí”. | Resolución de problemas y aceptación |
| **Luciérnagas Atentas** | Toca solo la luciérnaga que brilla lento y lleva el ritmo; ignora las que parpadean rápido. | Entrenamiento de atención plena (*mindfulness*) |
| **Mascota Serena** | Un personaje que se pone feliz cuando completas los juegos durante la semana. | Refuerzo positivo y adherencia al hábito |

**Sugerencia:** mantener 3 juegos en el menú (uno de **cuerpo**, uno de **mente** y uno de **emoción**) y rotar las ideas extra como “juego de la semana”.

---

## Siguientes pasos sugeridos
1. **Validar** el contenido de las tarjetas y los textos con un psicólogo del equipo.
2. **Probar** el prototipo con 5 a 10 usuarios y medir qué juego repiten más.
3. **Elegir tecnología** para la app final: Flutter o React Native (Android + iOS con un solo código), o convertir este prototipo en una PWA instalable.
4. **Agregar** un registro de ánimo antes/después de cada juego para medir el impacto.

> Sereno Virtual acompaña el bienestar, pero no reemplaza la atención psicológica profesional. La app debe mostrar siempre cómo contactar a la línea de emergencias del país del usuario.
