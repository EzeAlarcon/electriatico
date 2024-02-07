# electriatico
Dashboard Automatizado Tec Python Django + React 


# Descripción del Proyecto

Este proyecto consiste en el desarrollo de una API en Python para la Empresa de Energía de la Costa. La API permite alimentar una base de datos utilizando diferentes medios para cargar la información, incluyendo archivos CSV y JSON.

# Características Principales

* Lectura de Datos: La API puede leer conjuntos de datos tanto de archivos CSV como JSON. Se han proporcionado vistas en views.py que pueden leer datos de estos formatos.

* Autenticación y Protección de Rutas: Se ha implementado la autenticación JWT (JSON Web Tokens) y la protección de rutas en el archivo views.py. Se utiliza el decorador @api_view junto con JSONWebTokenAuthentication y IsAuthenticated para proteger las rutas que requieren autenticación.

* Análisis Básico de Datos: Se ha creado una ruta en views.py que permite realizar un análisis básico del conjunto de datos. La vista basic_analysis calcula la media, desviación estándar y correlación entre dos variables, como se especifica en los requisitos del proyecto.

# Procesos de instalacion y ejecucion 

*
