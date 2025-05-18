Práctica de Automatización
¡Aquí practico la automatización de pruebas!

Los principales frameworks incluidos en el proyecto:
Selenium Webdriver
Rest-Assured
TestNG
Allure Report
Extent Reports
Apachi POI
Diseño del proyecto:
Patrón de diseño del Modelo de Objetos de Página (POM)
Marco basado en datos
Enfoque de diseño fluido (encadenamiento de métodos)
Contar con un paquete de utilidades de soporte en la ruta del archivo src/main/java, llamado "Utils", que incluye numerosos métodos de contenedor en clases estáticas que funcionan como motor principal del proyecto.
Implementar la Pirámide de Automatización de Pruebas con dos niveles de automatización de pruebas diferentes: las capas de SERVICIO y GUI.
Cómo consultar los registros de ejecución y abrir los últimos informes de ejecución desde GitHub Actions:
Es necesario iniciar sesión en GitHub como requisito previo.
Abrir la pestaña GitHub Actions.
Abrir la última ejecución del flujo de trabajo de la lista.
Para consultar los registros de ejecución, haga clic en el trabajo "Prueba en Ubuntu" y abra el paso "Ejecutar pruebas - Chrome Headless". Allí podrá ver y comprobar. Registros de ejecución
Para abrir el informe Allure, en la sección Artefactos, haga clic en "Informe Allure", descomprima el archivo comprimido y abra el archivo "index.html" (si usa Windows y el informe se abrió sin datos, debe abrir el archivo "allow-file-access_open-report_chrome_windows.bat" para ver los datos).
Para abrir el informe Extent, en la sección Artefactos, haga clic en "Informe Extent", descomprima el archivo comprimido y abra el archivo "ExtentReports.html".
Cómo ejecutar los casos de prueba principales del proyecto localmente:
El archivo de propiedades "automationPractice.properties" se encuentra en la ruta src/main/resources, que incluye todas las configuraciones necesarias para la ejecución.
Los casos de prueba se encuentran en la carpeta src/test/java, principalmente en los paquetes phptravels.tests y restfulbooker.tests.
El conjunto de pruebas para todos los casos de prueba principales se encuentra en Carpeta src/test/resources/TestSuits en el archivo automationPractice.xml.
Para iniciar la ejecución, asegúrese de que la propiedad "execution.type" esté configurada como "Local". Si la ejecución es local, haga clic derecho en el archivo XML del conjunto de pruebas y seleccione "Ejecutar como >> TestNG Suit".
Tras la ejecución, puede generar fácilmente el informe Allure abriendo una terminal de línea de comandos en la ruta raíz del proyecto y escribiendo "mvn allure:serve" (debe poder ejecutar comandos mvn). También puede buscar el informe de extensión "ExtentReports.html" en la ruta raíz del proyecto para la última ejecución.
