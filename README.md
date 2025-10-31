# Trabajo-Practico-Integrador-Gestion-de-Datos-de-Paises-en-Python

Descripción del Proyecto

El proyecto consiste en el desarrollo de una aplicación en Python destinada a gestionar información sobre países del mundo.
Nombre del pais , Poblacion(habitantes) , Superficie , Continente.

El programa ofrece funcionalidades como:

1-Búsqueda de países por nombre (coincidencia parcial o exacta).

2-Filtrado por continente, rango de población o superficie.

3-Ordenamiento por nombre, población o superficie.

4-Cálculo de estadísticas básicas (promedios, país con mayor/menor población, etc.).

5-Agregado y edición de países desde consola.

6-Actualización automática del dataset desde la API REST Countries.

El objetivo del proyecto es aplicar conceptos fundamentales de programación estructurada: listas, diccionarios, funciones, condicionales, manejo de archivos CSV y uso de librerías externas.

🎓 Datos de la Universidad y la Cátedra

  ° Universidad Tecnologica Nacional Mendoza (UTN)
  
  ° Carrera: Tecnicatura Universitaria en Programación
  
  ° Cátedra: Programación I
  
  ° Año: 2025

  ° Comisión 4 

  ° Integrantes: Ignacio Sanchez, Fernando Torrez, Nicolas Valdez

  ° Datos de Profesores: Cinthia Rigoni, Ramiro Hualpa

🧱 Estructura del proyecto

📁 Proyecto_Paises/
│
├── fcs_paises.py         # Módulo principal con las funciones del sistema
├── paises.py             # Archivo ejecutable con el menú principal
├── paises.csv            # Archivo CSV con datos de los países
├── Informe_Teorico.pdf   # Informe teórico con fundamentos del trabajo
├── README.md             # Este archivo
└── 📂 ejecución_codigo/           # Capturas de pantalla de la ejecución del codigo 

⚙️ Instrucciones de ejecución

Clonar el repositorio o descargar los archivos del proyecto.

Asegurarse de tener instalado Python 3.10 o superior.

Instalar la librería necesaria (solo una externa):
pip install requests

Ejecutar el programa principal: python paises.py

Seguir las opciones del menú en consola para navegar entre las funcionalidades.

📚 Uso de librerías de terceros

requests → para conectarse con la API REST Countries.

unicodedata → para normalizar texto y quitar acentos.

csv, os → librerías estándar de Python (no requieren instalación).

🔗 Links

https://github.com/ignacioexesanchez-droid/Trabajo-practico-Integrador-Gesti-n-de-Datos-de-Pa-ses-en-Python/edit/main/README.md

💡 Ejemplo de entrada y salida

Entrada (usuario):

Seleccione una opción: 1
Ingrese el nombre del país a buscar: argentina

Salida (programa):

País(es) encontrado(s):
- Argentina: 45,808,747 habitantes, 2,780,400 km², Americas


