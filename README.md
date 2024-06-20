# Django-CRUD-SQLite3

CRUD completo con Python, Django y una base de datos SQLite3, usando el patrón de arquitectura MTV (Modelo - Plantilla - Vista), el ORM de Django, el framework CSS Bootstrap y control de eventos con JavaScript.


## Tecnologías utilizadas

<ul>
    <li><a href="https://www.python.org/">Python <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" target="_blank" width="15px" > </a></li>
    <li><a href="https://www.djangoproject.com/">Django <img src="https://www.svgrepo.com/show/353657/django-icon.svg" target="_blank" width=15px></a></li>
    <li><a href="https://getbootstrap.com/">Bootstrap <img src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Bootstrap_logo.svg" target="_blank" width="15px"></a></li>
    <li><a href=https://sqlite.org/">SQLite <img src="![image](https://github.com/anibalCApaza/programacion_web_2/assets/92649656/13596f28-bcdc-41a2-8749-95a97beb13df)
" target="_blank" width="50px"></a></li>
    
</ul>

## Manual de Instalación del proyecto en local (requiere tener instalado Python y Git previamente)

<ul>
<li>
<p> Clonación del repositorio<br>
<code> git clone https://github.com/anibalCApaza/webII_django.git </code> </p> 
</li>
<li>
<p> Creación del entorno virtual <br>
<code>python -m venv venv</code></p>
</li>
<li>
<p> Acceso al entorno virtual <br>
<span>Windows: <code>.\venv\Scripts\activate</code></p></span>
<span>Linux: <code>source venv/bin/activate</code></p></span>
</li>
<li>
<p> Instalación de dependencias <br>
    <code>pip install -r requirements.txt </code>
</p>
</li>
</ul>

## Ejecución

<ul> 
  <li><code> python manage.py runserver </code></li>
</ul>

## Consideraciones para la base de datos

<ul>
  <li>En su equipo debe existir una base de datos llamada "sistemaventas"</li>
  <li>Ejecutar el comando 
    <ul>
      <li>
         <code>python manage.py makemigrations sistema_ventas</code>
      </li>
      <li>
        <code>python manage.py migrate sistema_ventas</code>
      </li>
    </ul>
  
  </li>
</ul>
