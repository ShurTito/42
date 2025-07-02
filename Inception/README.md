# inception
<p>Proyecto que consiste en la creación y orquestación de un conjunto de contenedores Docker para simular una infraestructura web completa. Este proyecto forma parte del currículo de 42 y permite aprender sobre virtualización, redes, y despliegue de aplicaciones en entornos controlados.</p>

# 📚 Descripción
<p>El proyecto inception tiene como objetivo desplegar una stack web que incluya un servidor web, base de datos, PHPMyAdmin, WordPress, y otros servicios, todos ejecutándose en contenedores Docker interconectados. Permite entender el manejo de contenedores, redes y volúmenes para una arquitectura moderna y escalable.</p>

## 🔹 Funcionalidades principales
<li>Configuración y despliegue de múltiples contenedores Docker</li> <li>Orquestación de servicios web, base de datos y herramientas administrativas</li> <li>Gestión de redes y volúmenes Docker para persistencia y comunicación</li> <li>Automatización con Docker Compose</li> <li>Configuración segura y optimizada para cada servicio</li> <p>Este proyecto permite adquirir experiencia práctica en DevOps y despliegue de infraestructuras modernas.</p>

# 🛠️ Tecnologías y Lenguajes
<li>Docker y Docker Compose</li> <li>Linux (shell scripting)</li> <li>Configuración de servicios web (Nginx, Apache)</li> <li>Bases de datos MySQL/MariaDB</li> <li>PHP, WordPress</li>

# 💡 Conceptos Clave
<li>Contenerización y virtualización ligera</li> <li>Orquestación de servicios</li> <li>Redes y volúmenes en Docker</li> <li>Automatización con scripts y Docker Compose</li> <li>Seguridad y persistencia de datos</li>

# 🧪 Compilación y despliegue
<p>Para desplegar la infraestructura inception, ejecutar:</p>

```bash
make build
```
<p>Esto iniciará todos los contenedores configurados. Para detenerlos:</p>

```bash
make down
```
<p>Luego podrás acceder a los servicios web desde el navegador.</p>
