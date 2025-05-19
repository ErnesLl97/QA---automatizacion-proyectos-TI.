.... Automation-Practice-master....

Frameworks included in the project:
Selenium Webdriver
Rest-Assured
TestNG


Diseño del proyecto:
Patrón de diseño del Modelo de Objetos de Página (POM)
Marco de trabajo basado en datos
Enfoque de diseño fluido (encadenamiento de métodos)
Contar con un paquete de utilidades de soporte en la ruta del archivo src/main/java, llamado "Utils", que incluye numerosos métodos de contenedor en clases estáticas que funcionan como motor principal del proyecto.
Implementar la Pirámide de Automatización de Pruebas mediante dos niveles de automatización de pruebas diferentes: las capas de SERVICIO y GUI.


Diseño del proyecto: Implementa el patrón Page Object Model (POM), pruebas basadas en datos y un enfoque de diseño fluido (method chaining).
Cobertura de pruebas: Incluye pruebas tanto a nivel de servicio como de interfaz gráfica de usuario (GUI), siguiendo la pirámide de automatización de pruebas.
Informes y registros: Genera informes detallados utilizando Allure y Extent Reports, con integración en GitHub Actions para la ejecución continua.


....automatizacion_python_selenium....

Este proyecto es una prueba técnica que automatiza la navegación en un sitio web, completando un formulario de contacto con un correo electrónico falso y verificando la validación del mismo. Utiliza Python, Selenium WebDriver, unittest y HtmlTestRunner para generar informes de prueba


....Automatización de sitios web de comercio electrónico con Selenium  (Python) ....

Sitio web de comercio electrónico ficticio: http://tutorialsninja.com/demo/
Patrón de diseño: Modelo de Objetos de Página (POM)
Informes: HTML-testrunner

Se han automatizado los siguientes requisitos:

Abrir el sitio web de comercio electrónico.
Seleccionar un producto con una cantidad superior a 1 y añadirlo al carrito.
Seleccionar un producto, actualizar la fecha de entrega y añadirlo al carrito.
Ver el carrito y finalizar la compra como invitado.
Ingresar todos los datos de entrega y finalización de la compra.
Confirmar el pedido y comprobar el mensaje de confirmación
