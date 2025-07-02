# cub3d
<p>Proyecto para implementar un motor gráfico básico en 3D utilizando raycasting, inspirado en el clásico Wolfenstein 3D. Este proyecto forma parte del currículo de 42 y permite aprender sobre gráficos en tiempo real, matemáticas aplicadas, y manejo de eventos en C.</p>

# 📚 Descripción
<p>El proyecto cub3d tiene como objetivo crear un juego simple en primera persona donde el jugador puede moverse en un mapa 2D con paredes y visualizar el entorno en 3D usando técnicas de raycasting. Permite entender cómo funcionan los gráficos 3D desde cero, el renderizado y la interacción con el usuario.</p>

## 🔹 Funcionalidades principales
<li>Renderizado en 3D básico con raycasting</li> <li>Movimiento del jugador y control de cámara</li> <li>Detección de colisiones con paredes</li> <li>Mapas configurables en archivos externos</li> <li>Texturizado de paredes para mayor realismo</li> <li>Manejo de eventos de teclado para interacción</li> <p>Este proyecto profundiza en gráficos 3D, estructuras de datos, y programación en C aplicada a videojuegos simples.</p>

# 🛠️ Tecnologías y Lenguajes
<li>Lenguaje C (C99)</li> <li>Makefile</li> <li>Norminette (estilo de código 42)</li> <li>Uso de la librería gráfica MiniLibX</li> <li>Matemáticas aplicadas para raycasting</li>

# 💡 Conceptos Clave
<li>Raycasting y renderizado 3D</li> <li>Manejo de gráficos en tiempo real</li> <li>Interacción con teclado y eventos</li> <li>Colisiones y físicas básicas</li> <li>Estructuras de datos para mapas y gráficos</li>

# 🧪 Compilación
<p>Para compilar cub3d, simplemente ejecutar:</p>

```bash
make
```
<p>Esto generará el ejecutable <code>cub3d</code> que podrá ser ejecutado desde la terminal.</p> <p>Ejemplo de uso:</p>

```bash
./cub3d maps/map.cub
```
<p>Donde <code>mapa.cub</code> es un archivo de texto con la configuración del mapa del juego.</p>
