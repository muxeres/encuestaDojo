# Asignación: Encuesta Dojo

## Objetivos

* Practicar la creación de un servidor con Flask desde cero
* Practicar agregar rutas a una aplicación Flask
* Hacer que el cliente envíe datos al servidor con un formulario
* Practicar la redirección después de la solicitud POST.
* Utiliza sesión para mostrar los datos del formulario en la página de resultados.

---


Crea una nueva aplicación Flask que acepte el envío de un formulario y presente los datos enviados en una página de resultados.

El objetivo es ayudarte a familiarizarte con el envío de solicitudes POST a través de un formulario y mostrar esa información. Considera el siguiente ejemplo como guía.


Cuando crees esto, asegúrate de que tu programa cumpla con los siguientes criterios:

* http://localhost:5000: haz que esto muestre un formulario HTML atractivo. El formulario debe enviarse a '/process'
* Guarda los datos del formulario en la sesión.
* http://localhost:5000/result: haz que esto muestre un HTML con la información enviada por POST

**¡No olvides que cualquier entrada a la que queramos poder acceder desde el envío del formulario debe tener un nombre!**

Siempre es una buena idea imprimir request.form para ver si el formulario entrega toda la información que necesitas en tu método de enrutamiento.

* Crear una aplicación Flask
* Haz que la ruta raíz ("/") muestre una página con el formulario
* Haz que la ruta "/result" muestre la información del formulario en una nueva página HTML
* Pon los datos del formulario en la sesión
* BONUS NINJA: usa un marco CSS para diseñar tu formulario
* BONUS NINJA: incluye un conjunto de botones de opción en el formulario
* BONUS SENSEI: incluye un conjunto de casillas de verificación en el formulario
