# Little Lemon Restaurant - Proyecto Django (Coursera)

[![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.x-092E20?logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-3.x-A30000?logo=django&logoColor=white)](https://www.django-rest-framework.org/)
[![SQLite](https://img.shields.io/badge/SQLite-3-003B57?logo=sqlite&logoColor=white)](https://www.sqlite.org/index.html)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Proyecto web desarrollado como parte del curso "Django Web Framework" de Meta en Coursera. Implementa funcionalidades básicas para un sistema de restaurante ficticio llamado Little Lemon, utilizando el framework Django.

## 📸 Screenshots

Aquí puedes ver algunas capturas de pantalla de la aplicación:

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/drbv27/CourseraDjangoWebFramework/main/restaurant/static/img/screenshots/Screenshot1.jpeg" alt="Screenshot 1" width="400"/></td>
    <td><img src="https://raw.githubusercontent.com/drbv27/CourseraDjangoWebFramework/main/restaurant/static/img/screenshots/Screenshot2.jpeg" alt="Screenshot 2" width="400"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/drbv27/CourseraDjangoWebFramework/main/restaurant/static/img/screenshots/Screenshot3.jpeg" alt="Screenshot 3" width="400"/></td>
    <td><img src="https://raw.githubusercontent.com/drbv27/CourseraDjangoWebFramework/main/restaurant/static/img/screenshots/Screenshot4.jpeg" alt="Screenshot 4" width="400"/></td>
  </tr>
</table>

## 🚀 Cómo Ejecutar el Proyecto Localmente

Sigue estos pasos para poner en marcha el proyecto en tu máquina local. Estas instrucciones asumen que tienes Python 3.x y Git instalados y estás usando una terminal tipo Bash (como Git Bash en Windows).

**1. Clonar el Repositorio**

Primero, clona este repositorio en tu máquina local:

```bash
git clone [https://github.com/drbv27/CourseraDjangoWebFramework.git](https://github.com/drbv27/CourseraDjangoWebFramework.git)
cd CourseraDjangoWebFramework
```

**2. Crear y Activar un entorno Virtual**

Es altamente recomendable usar un entorno virtual para aislar las dependencias del proyecto.

**_-Crear el entorno(dentro de la carpeta del proyecto):_**

```bash
python -m venv venv
```

**_-Activar el entorno (para Git Bash en Windows):_**

```bash
Source venv/Scripts/activate
```

(Deberías ver `(venv)` al inicio de tu prompt en la terminal si se activó correctamente)

**3. Instalar Dependencias**

Instala todas las librerías necesarias listadas en `requirements.txt`:

```bash
pip install -r requirements.txt
```

**4. Aplicar Migraciones de Base de Datos**

Django necesita configurar la base de datos. Ejecuta el comando de migración:

```bash
python manage.py migrate
```

**5. Crear un Superusuario (Opcional)**

Si deseas acceder al panel de administración de Django (`/admin/`), crea un superusuario:

```bash
python manage.py createsuperuser
```

Sigue las instrucciones para crear tu nombre de usuario y contraseña.

**6. Ejecutar el Servidor de Desarrollo**

¡Ahora puedes iniciar el servidor!

```bash
python manage.py runserver
```

**7. Abrir en el Navegador**

Una vez que el servidor esté corriendo, abre tu navegador web y ve a:

http://127.0.0.1:8000/

Deberías ver la página principal de Little Lemon.
Para detener el servidor, vuelve a la terminal y presiona `Ctrl + C`.

📚 Origen del Proyecto
Este proyecto se basa en el material y los ejercicios del curso:

[Meta Django Web Framework en Coursera](https://www.coursera.org/learn/django-web-framework-es)

## 📫 Contacto

[![GitHub](https://img.shields.io/badge/GitHub-drbv27-181717?logo=github)](https://github.com/drbv27)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-DiegoBonilla-0A66C2?logo=linkedin)](https://www.linkedin.com/in/diego-ricardo-bonilla-villa-7179254a/) [![Email](https://img.shields.io/badge/Email-DiegoBonilla-D14836?logo=gmail)](mailto:drbv27@gmail.com)
