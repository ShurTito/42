# minitalk
Pequeño programa de comunicación entre procesos que utiliza señales de Unix para enviar mensajes carácter por carácter. Este proyecto forma parte del currículo de 42 y permite comprender cómo interactúan los procesos a bajo nivel usando el sistema de señales del kernel.

# 📚 Descripción
El proyecto minitalk tiene como objetivo implementar un sistema de mensajería entre dos procesos —cliente y servidor— utilizando exclusivamente las señales SIGUSR1 y SIGUSR2.

🔹 Servidor

<p>Recibe señales que representan bits individuales enviados desde el cliente, los interpreta y reconstruye el mensaje en texto plano.</p>
🔹 Cliente

<p>Codifica un mensaje carácter por carácter en señales binarias y las envía al proceso servidor utilizando `kill()` y `signal()`.</p>
Este ejercicio permite explorar cómo funcionan las señales en Unix, cómo controlar el flujo de datos entre procesos y cómo manejar la asincronía de manera segura.

# 🛠️ Tecnologías y Lenguajes
<ul> <li>Lenguaje C (C99)</li> <li>Makefile</li> <li>Norminette (estilo de código 42)</li> <li>Funciones del sistema Unix (`signal()`, `kill()`, `pause()`)</li> </ul>

# 💡 Conceptos Clave
<ul> <li>Manejo de Señales (SIGUSR1, SIGUSR2)</li> <li>Comunicación entre Procesos (IPC)</li> <li>Codificación y Decodificación de Bits</li> <li>Sistemas Asíncronos</li> <li>Sincronización básica entre procesos</li> <li>Resiliencia ante interrupciones o errores en la señalización</li> </ul>

# 🧪 Compilación
<p>Esto generará dos ejecutables: server y client.</p>

```bash
./server
./client <PID_del_servidor> "mensaje a enviar"
```
