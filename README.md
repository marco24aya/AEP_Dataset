# DATASET POWERLIFTING AEP - ESPAÑA (2015 - 2025)

El presente proyecto representa un documento CSV que se dedica a recopilar los levantamientos de todos los atletas que ha habido en los campeonatos provincionales (AEP 3), autonómico (AEP 2)  y nivel nacional (AEP 1) desde 2015 hasta la actualidad, cuyo propósito es la continua actualización. Este documento se encuentra en la carpeta correspondiente.

La recogida de los datos han sido a través de los archivos tanto HTML como XLS de la página oficial de Asociación Española de Powerlifting (AEP). Asociación única reconcocida a nivel nacional por la International Powerlifting Federetion (IPF). 

# ¿Qué contiene?

Este documento CSV contiene varias columnas, como el sexo, nombre, apellidos, año de nacimiento del atleta, el club que pertenece, la categoría de edad, de peso, peso registrado en dicha competición, los 9 intentos de cada movimeinto y su total. Además de eso, se comeplementa con el sistema de clasificación utilizado durante esta década, como son los WILKS Points, IPF Points y GL Points, este último sistema es el que se usa actualmente. Asimismo, en base a los puntos que hayan obtenido, se creó dos columnas de clasificación, una según la categoría de peso (pos_cat) y otra en función del sexo (pos_abs). 

Por último, Las últimas columnas del dataset tratan sobre el tipo de modalidad, es decir, si es Raw, donde se utilizan cinturón, rodilleras y muñequeras, o Equipado, donde utilizan otro tipo de equipamiento que ayuda a levantar más kilos; si el tipo de competición ha sido de Powerlfiting (3 movimientos), Banca o Peso Muerto. Continuando, destacamos las columnas que dan información sobre el nombre de la competición, el club organizador, provincia, mes y año que se produjo el campeonato. Como extra, cree una columna llamada _anotación_, para aclarar el motivo de Descalificación, y otra información relativa del atleta que haya sido importante en dicha competición.

# Práctica
El documento original (data raw) tiene varios datos nulos. Es por eso que, como **ejercicio práctico**, dejo los datos crudos para que podais rellenar:
- IPF Points
- WILKS Points
- Categoría de edad a la que pertenece el atleta (Sub-Junior [SBJ], Junior [JUN], Open [SNR], Master I [M1], Master II [M2], Master III [M3] y Master IV [M4])
- Crear el sistema de puntos en cada competición
- Estandarizar nombres de club a abreviaturas o viceversa

La información para realizar el ejercicio se encuentra en el siguiente enlace:
- https://www.powerlifting.sport/fileadmin/ipf/data/ipf-formula/Models_Evaluation-I-2020_01.pdf 

# Actualización - Información
Se han recogido los últimos campeonatos de diciembre de 2025 (I Campeonato de Euskal Herria - II Copa SBD). En este CSV se ha finalizado la recopilación de una década de este deporte de las competiciones que se han realizado en España, no se incluyen los campeonatos a nivel continental ni internacional.

# Contacto
- LinkedIn: https://www.linkedin.com/in/marco-vinicio-ayala-sierra-84a1b431b/
- Email: vinicioayala1999@gmail.com
