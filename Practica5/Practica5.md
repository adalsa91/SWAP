Práctica 5. Replicación de bases de datos MySQL
================================================

Objetivos de la práctica
------------------------
En esta práctica se pretende aportar un grado más de fiabilidad a nuestro sistema ante posibles interrupciones de servicio permanentes del servidor maestro, para ello dispondremos de un servidor de backup con MySQL actuando como esclavo de replicación, de esta forma aumentaremos la fiabilidad del sistema sin que se vea afectado el rendimiento del sistema en producción y sin consumir demasiado ancho de banda.

Los objetivos concretos de esta práctica son:  
* Copiar archivos de copia de seguridad mediante ssh.  
* Clonar manualmente BD entre máquinas.  
* Configurar la estructura maestro-esclavo entre dos máquinas para realizar el clonad automático de la información.
