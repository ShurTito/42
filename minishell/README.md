# minishell

<p>Pequeña implementación de un intérprete de comandos (shell) básico en Unix. Este proyecto forma parte del currículo de 42 y permite comprender cómo funcionan los shells a nivel básico, cómo interpretar comandos, gestionar procesos y redireccionar entradas y salidas.</p>

# 📚 Descripción

<p>El proyecto minishell tiene como objetivo crear un shell simple que sea capaz de interpretar y ejecutar comandos introducidos por el usuario, manejando tuberías, redirecciones, variables de entorno y comandos internos.</p>

## 🔹 Funcionalidades principales

<ul>
<li>Interpretación y ejecución de comandos externos y internos (<code>cd</code>, <code>echo</code>, <code>exit</code>, <code>env</code>, <code>unset</code>, <code>export</code>, etc.)</li>  
<li>Manejo de tuberías (<code>|</code>) para encadenar múltiples comandos</li>  
<li>Soporte para redirección de entrada (<code>&lt;</code>) y salida (<code>&gt;</code>, <code>&gt;&gt;</code>)</li>  
<li>Gestión de variables de entorno</li>  
<li>Manejo de señales para controlar procesos (como Ctrl+C para cancelar la ejecución)</li>  
<li>Parsing robusto para interpretar correctamente comillas simples y dobles, espacios y caracteres especiales</li>
</ul>

<p>Este proyecto permite entender en profundidad cómo funcionan los shells a nivel usuario y kernel, la gestión de procesos y la manipulación de la entrada y salida estándar.</p>

# 🛠️ Tecnologías y Lenguajes

<ul>
<li>Lenguaje C (C99)</li>  
<li>Makefile</li>  
<li>Norminette (estilo de código 42)</li>  
<li>Funciones y llamadas del sistema Unix (<code>fork()</code>, <code>execve()</code>, <code>pipe()</code>, <code>dup2()</code>, <code>waitpid()</code>, etc.)</li>
</ul>

# 💡 Conceptos Clave

<ul>
<li>Parsing y tokenización de cadenas</li>  
<li>Gestión de procesos y creación de hijos</li>  
<li>Tuberías y redirección de entrada/salida</li>  
<li>Señales Unix (control de interrupciones y estados)</li>  
<li>Variables de entorno y manejo de contexto del shell</li>  
<li>Comandos internos vs externos</li>  
<li>Control de flujo y estado del shell</li>
</ul>

# 🧪 Compilación

<p>Para compilar el minishell, simplemente ejecutar:</p>

```bash
make
```

<p>Esto generará el ejecutable <code>minishell</code> que podrá ser ejecutado desde la terminal.</p> <p>Ejemplo de uso:</p>

```bash
./minishell
```

<p>Luego podrás escribir comandos como:</p>

```bash
ls -l | grep minishell > salida.txt
cd ..
echo "Hola mundo"
```
