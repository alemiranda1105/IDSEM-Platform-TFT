# Sistema Web para la Evaluación de Métodos de Extracción de Información a partir de Facturas

Este es el código para la creación de mi proyecto de final de grado.

---

## ¿Cómo probar?
El proyeto se divide en dos partes, lado servidor y lado cliente.

### Lado cliente
Para probar este sitio web hay que ejecutar los siguientes comandos:
1. Primero instalamos los paquetes necesarios:
`npm install`
2. Ejecutamos:
`npm start`
3. Abrimos la siguiente URL: [localhost:3000](http://localhost:3000/)

### Lado servidor
<b>¡Atención!:</b> Es necesario tener instaladas las dependencias necesarias para MongoDB. El link para su instalación es el siguiente: [MongoDB](https://www.mongodb.com/try/download/community).

Para probar esta api hay que ejecutar los siguientes comandos:
1. Primero instalamos los paquetes necesarios (Se recomienda hacer uso de un entorno virtual para la instalación de los paquetes, por ejemplo: `virtualenv venv`):
`pip install -r requirements.txt` o `pip3 install -r requirements.txt`.
2. Se debe actualizar el fichero `.env` con la localización del modelo base (BASE_MODEL_FOLDER), la carpeta donde se guardarán los métodos evaluados (UPLOADED_METHODS_FOLDER) y en caso de necesitar ejecutar los tests, actualizar la localización de los resultados de prueba (TEST_FILE_ZIP), el resto de campos no es necesario actualizarlos. En este repositorio se encuentra un ejemplo de este fichero y los archivos mencionados, [carpeta](./tfg-backend/evaluation_examples/).
3. Ejecutamos:
`python3 app/main.py`
4. Y ya podremos hacer solicitudes al localhost:8000

---

## Test
Dentro de cada carpeta encontrá los detalles de como ejecutar los tests para probar la plataforma

---

## Tecnologías usadas
* React
* Typescript
* Tailwind
* Python
* FastAPI
* MongoDB

---

## Manual de usuario
En esta misma carpeta encontrará el manual de usuario de la plataforma: [Manual de usuario](Manual_Usuario.pdf)

---

## Repositorios
Para una mejor organización, durante el desarrollo de este proyecto se usaron dos respositorios distintos, uno para el frontend y otro para el backend. En caso de que quiera consultar los detalles de cada uno de ellos, se puede encontrar en los siguientes repositorios:
1. [FrontEnd](https://github.com/alemiranda1105/tfg-frontend)
2. [BackEnd](https://github.com/alemiranda1105/tfg-backend)

---

## Autor
__Alejandro Miranda López__

_4º Grado de Ingeniería Informática, Universidad de Las Palmas de Gran Canaria_
