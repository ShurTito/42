# philosophers

<p>Implementación de la clásica simulación del problema de los filósofos comensales utilizando programación concurrente en C. Este proyecto forma parte del currículo de 42 y permite comprender la sincronización de procesos y el manejo de condiciones de carrera en sistemas concurrentes.</p>

# 📚 Descripción

<p>El proyecto philosophers tiene como objetivo simular el problema de los filósofos comensales, en el que varios filósofos comparten recursos (tenedores) y deben evitar condiciones de bloqueo y hambruna, garantizando un acceso seguro y sincronizado a los recursos.</p>

## 🔹 Funcionalidades principales
<li>Creación y gestión de múltiples hilos o procesos para representar a los filósofos</li> <li>Sincronización de acceso a los tenedores mediante mutex o semáforos</li> <li>Control de tiempos para simular pensar, comer y dormir</li> <li>Detección y manejo de condiciones de bloqueo (deadlock) y hambruna (starvation)</li> <li>Salida por consola con estados actualizados de cada filósofo</li> <p>Este proyecto permite profundizar en conceptos de concurrencia, sincronización, y evitar problemas clásicos en sistemas multitarea.</p>

# 🛠️ Tecnologías y Lenguajes
<li>Lenguaje C (C99)</li> <li>Makefile</li> <li>Norminette (estilo de código 42)</li> <li>Uso de pthreads (hilos) o procesos con semáforos y mutexes</li>

# 💡 Conceptos Clave
<li>Programación concurrente y paralela</li> <li>Mutexes y semáforos para sincronización</li> <li>Condiciones de carrera y exclusión mutua</li> <li>Deadlock y starvation</li> <li>Gestión de hilos y tiempos de ejecución</li>

# 🧪 Compilación
<p>Para compilar philosophers, simplemente ejecutar:</p>

```bash
make
```
<p>Esto generará el ejecutable <code>philosophers</code> que podrá ser ejecutado desde la terminal.</p> <p>Ejemplo de uso:</p>

```bash
./philosophers number_of_philosophers time_to_die time_to_eat time_to_sleep [number_of_times_each_philosopher_must_eat]
```
<p>Donde los argumentos representan los tiempos en milisegundos para controlar la simulación.</p>
