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
