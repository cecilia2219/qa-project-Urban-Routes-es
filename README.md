# Pruebas para pedir un taxi en la aplicacion Urban Routes
## _Proyecto final de Sprint No. 8 "Automatización de pruebas de la aplicación web"_


## Tarea:
    Se necesita probar el servicio de Urban Routes, tendras que cubrir todo el proceso de pedir un taxi por medio
    de la aplicacion web. Las pruebas deben cubrir estas acciones:  
    1.- Configurar la dirección (esta parte se ha escrito para ti como ejemplo).
    2.- Seleccionar la tarifa Comfort.
    3.- Rellenar el número de teléfono.
    4.-Agregar una tarjeta de crédito. (Consejo: el botón 'link' (enlace) no se activa hasta que el campo CVV 
    de la tarjeta en el modal 'Agregar una tarjeta', id="code" class="card-input", pierde el enfoque. Para cambiar 
    el enfoque, puedes simular que el usuario o usuaria presiona TAB o hace clic en otro lugar de la pantalla).
    El repositorio tiene preparada la función retrieve_phone_code() que intercepta el código de confirmación requerido 
    para agregar una tarjeta.
    5.-Escribir un mensaje para el controlador.
    6.- Pedir una manta y pañuelos.
    7.- Pedir 2 helados.
    8.- Aparece el modal para buscar un taxi.
    9.- Esperar a que aparezca la información del conductor en el modal (opcional). 
    Además de los pasos anteriores, hay un paso opcional que puedes comprobar; este es un poco más complicado que los 
    demás, pero es una buena práctica, ya que es probable que en tu trayectoria profesional encuentres tareas más 
    difíciles.


## Archivos:
- main.py, 
- data.py,
- README.md. 
- .gitignore.

## Como configurar el proyecto
-   Se debera clonar el repositorio del  proyecto desde github
-   Usar PyCharm  para  correr el proyecto.
  - Instalar la configuracion Pytest
  - Instalar Selenium webdriver
  - Una vez instalado lso paquetes anteriores, para corer  el codigo de forma correcta,  se  debera de actualizar la variable "urban_routes_url", en   el  archivo daata.py, con la url de un nuevo servidor de la aplicacion Urban Routes, ya que el servidor deja de funcionar despues de un  tiempo

## Contenido de los diferentes archivos
- main.py: Se encuentra el codigo con los metodos y pruebas solicitadas.
- data.py: Se guarda los datos necesarios para ingresar en casos especificos, como el numero telefonico, numero de tarjeta, direcciones, etc.
- README.md: Breve descripción de tu proyecto
- .gitignore: Archivo especial para que no se suban en los repositorios archivos inecesarios o por temas de seguridad se deban de ignorar.

## Pasos a seguir, usando pycharm:
- Obtener un servidor para la aplicacion Urban Routes.
- Crear una ruta.
- Pedir un taxi usando el metodo flash.
- Agregar informacion necesaria, como numero telefonico y metodo de pago.
- Agregar elementos deseados a la orden.
- Finalizar el pedido esperando que nos asignen un conductor.

##  pruebas realizadas.
-	Configurar la dirección.
- 	Seleccionar la tarifa Comfort.
-   Rellenar el número de teléfono.
- 	Agregar una tarjeta de crédito. (Consejo: el botón 'link' (enlace) no se activa hasta que el campo CVV de la tarjeta en el modal 'Agregar una tarjeta', id="code" class="card-input", pierde el enfoque. Para cambiar el enfoque, puedes simular que el usuario o usuaria presiona TAB o hace clic en otro lugar de la pantalla).
- 	Escribir un mensaje para el controlador.
-   Pedir una manta y pañuelos.
- 	Pedir 2 helados.
-   Aparece el modal para buscar un taxi.
- 	Esperar a que aparezca la información del conductor en el modal (opcional). Además de los pasos anteriores, hay un paso opcional que puedes comprobar; este es un poco más complicado que los demás, pero es una buena práctica, ya que es probable que en tu trayectoria profesional encuentres tareas más difíciles.

