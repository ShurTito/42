# irc
<p>Implementación básica de un servidor y cliente de chat IRC (Internet Relay Chat) en C. Este proyecto forma parte del currículo de 42 y permite aprender sobre programación en red, comunicación entre procesos y gestión de múltiples conexiones concurrentes.</p>

# 📚 Descripción
<p>El proyecto irc tiene como objetivo crear un servidor que permita a múltiples clientes conectarse y comunicarse en canales de chat, gestionando usuarios, mensajes y comandos típicos de un entorno IRC. Se profundiza en sockets, concurrencia y protocolos de comunicación.</p>

## 🔹 Funcionalidades principales
<li>Implementación de un servidor TCP que maneja múltiples conexiones concurrentes</li> <li>Cliente IRC capaz de conectarse y comunicarse con el servidor</li> <li>Gestión de múltiples canales y usuarios</li> <li>Soporte para comandos básicos (join, part, msg, quit, etc.)</li> <li>Sincronización y manejo de mensajes entre usuarios</li> <p>Este proyecto permite comprender cómo funcionan los sistemas de mensajería en tiempo real y la programación de redes en C.</p>

# 🛠️ Tecnologías y Lenguajes
<li>Lenguaje C++ </li> <li>Makefile</li>  <li>Sockets TCP/IP</li>

# 💡 Conceptos Clave
<li>Programación en red con sockets</li> <li>Concurrencia y multiplexación de conexiones</li> <li>Protocolos de comunicación y formatos de mensajes</li> <li>Gestión de usuarios y canales</li>

# 🧪 Compilación
<p>Para compilar irc, ejecutar:</p>

```bash
make
```
<p>Esto generará los ejecutables <code>server</code> y <code>client</code> que podrán ser usados desde la terminal.</p> <p>Ejemplo de uso:</p>

```bash
./server <puerto>
./client <ip_del_servidor> <puerto>
```
