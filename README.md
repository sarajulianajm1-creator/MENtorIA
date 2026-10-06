# 🧮 Aventuras Matemáticas · 1° Grado

Colección de **20 juegos interactivos didácticos** diseñados para estudiantes de primer grado de primaria, orientados al desarrollo del pensamiento matemático temprano, el sentido numérico, el cálculo mental y la resolución de problemas cotidianos.

---

## 🚀 Despliegue en GitHub Pages (Paso a Paso)

Este repositorio está 100% optimizado para desplegarse como un sitio web público y gratuito a través de **GitHub Pages**.

### Paso 1: Subir el proyecto a GitHub
Si aún no has subido esta carpeta a GitHub, inicializa el repositorio y súbelo a tu cuenta:
```bash
git init
git add .
git commit -m "Añadir portal interactivo y 20 juegos matemáticos"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

### Paso 2: Activar GitHub Pages
1. Abre tu repositorio en [GitHub.com](https://github.com).
2. Haz clic en la pestaña **Settings** (Configuración) en la parte superior derecha.
3. En el menú de navegación izquierdo, selecciona **Pages**.
4. Bajo la sección **Build and deployment**:
   - En **Source**, selecciona `Deploy from a branch`.
   - En **Branch**, selecciona `main` y en la carpeta selecciona `/ (root)`.
5. Haz clic en el botón **Save** (Guardar).

### Paso 3: ¡Listo!
En aproximadamente **1 a 2 minutos**, GitHub publicará tu portal web en:
```text
https://TU-USUARIO.github.io/TU-REPOSITORIO/
```
*(Puedes compartir este enlace con estudiantes, docentes y familias. Funciona sin instalación previa en computadoras, tabletas y celulares).*

---

## 🎮 Catálogo de los 20 Juegos

| # | Juego | Archivo | Eje Temático | Objetivo Pedagógico |
|---|-------|---------|--------------|---------------------|
| **1** | 🔢 ¿Cuántos hay? | `juego_contar_colorido 1.html` | Conteo y Cantidades | Identificación de colecciones con la misma cantidad de elementos. |
| **2** | 🍦 ¡Arrastra el helado al niño! | `juego_drag_helados 2.html` | Conteo y Correspondencia | Correspondencia uno a uno (más, menos o igual) mediante arrastre interactivo. |
| **3** | 🖐️ Representemos con los dedos | `juego_dedos_ejercicios 3.html` | Conteo y Simbolización | Lectura de configuraciones digitales con manos y escritura de números. |
| **4** | 🐾 ¿Cuántos animales hay? | `juego_cuantos_animales 4.html` | Conteo y Puntos | Conteo de animales y representación mediante constelaciones de puntos. |
| **5** | ✏️ Une los Puntos | `une_puntos 5.html` | Secuencia Numérica | Trazo consecutivo en orden ascendente sobre pizarra interactiva. |
| **6** | 🎲 ¡Paga con los dados! | `juego_dados_niveles 6.html` | Suma y Descomposición | Composición aditiva y pago exacto combinando tarjetas de dados. |
| **7** | 🚗 ¡La Gran Carrera! | `carrera_conteo 7.html` | Recta Numérica | Juego de tablero con dados; comprensión del avance y posiciones sucesivas. |
| **8** | ❌ Tacha y Resuelve | `resta_tachado_juego 8.html` | Resta Gráfica | Noción de sustracción como quitar elementos tachándolos visualmente. |
| **9** | 📊 Cuenta y Pinta la Gráfica | `cuenta_grafica 9.html` | Registro y Gráficas | Conteo de frutas en cajas, registro en tablas y coloreado de gráficas de barras. |
| **10** | 🛒 Juguemos a la Tienda | `tienda 10.html` | Monedas y Precios | Compra de artículos utilizando monedas de $1 en un mostrador interactivo. |
| **11** | 🎲 ¿Cuántos puntos tienen los dados? | `dados 11.html` | Suma Rápida | Cálculo mental rápido a partir del reconocimiento de caras de dados. |
| **12** | 🔟 Hagamos Grupos de 10 | `grupos_de_10 12.html` | Decenas y Unidades | Agrupamiento en decenas y conteo de unidades sueltas para formar números. |
| **13** | 💡 Usemos escrituras como 2⁸ | `juego_escrituras 13.html` | Descomposición Numérica | Comprensión de notaciones aditivas y paquetes de unidades. |
| **14** | 🪑 ¿Faltan o sobran? | `juego_faltan_sobran 14.html` | Comparación Lógica | Deducción lógica de cantidades faltantes o sobrantes entre conjuntos. |
| **15** | 🪜 Escaleras de números | `juego_escaleras_numeros 15.html` | Series Numéricas | Completar secuencias numéricas (20 al 50) y ordenamiento de tarjetas. |
| **16** | 🪵 La Tienda de Don Pinocho | `tienda_pinocho 16.html` | Presupuesto y Comparación | Análisis de alcance de dinero ("¿me alcanza?") y comparación de precios. |
| **17** | 🎈 ¿Cuántas hay? (Colecciones) | `cuantos_hay 17.html` | Colecciones y Suma | Estrategias de conteo en colecciones desordenadas y sumas visuales. |
| **18** | 🥢 Palotes para hacer cuentas | `palotes 18.html` | Marcas de Conteo | Registro tradicional de conteo por grupos de 5 con palotes diagonales. |
| **19** | 🧠 Seleccionemos el mejor método | `mejor_metodo 19.html` | Estrategias de Cálculo | Comparación de métodos de cálculo para seleccionar el más eficiente. |
| **20** | 🧮 Problemas de la comunidad | `juego_problemas_comunidad 20.html` | Resolución de Problemas | Comprensión lectora y resolución de problemas matemáticos en contexto social. |

---

## 💻 Uso Local (Sin Conexión a Internet)

No se requiere ningún servidor, Node.js ni paquetes externos:
1. Haz doble clic en el archivo [`index.html`](index.html).
2. Se abrirá en tu navegador predeterminado (Chrome, Edge, Firefox, Safari).
3. ¡Todo funcionará sin conexión!

---

## 🛠️ Características Técnicas

- **Cero dependencias de servidor**: Construido en HTML5, CSS3 moderno y Vanilla JavaScript.
- **Reproductor Integrado**: Permite jugar directamente en modal con pantalla completa, navegación anterior/siguiente y recarga rápida.
- **Buscador y Filtros**: Búsqueda instantánea por nombre o número y filtros por eje temático.
- **Seguimiento de Progreso**: Guarda automáticamente los juegos completados en el navegador (`localStorage`).
- **Sintetizador de Sonido**: Efectos de audio amigables generados mediante la API Web Audio nativa (con botón de silencio).
- **Archivo `.nojekyll` incluido**: Previene que GitHub Pages procese archivos con Jekyll, garantizando una entrega estática instantánea.
