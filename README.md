# clase2IA
Ficha de análisis
1. Nombre del Space
Nombre: Juan Pablo Parra El Masri
Enlace:
________________________________________
2. ¿Qué hace el agente?
El agente tiene la funcionalidad de editar imágenes de forma rápida usando un prompt de instrucciones y la imagen inicial a editar.________________________________________
3. Análisis PEAS
Elemento Respuesta
________________________________________
Performance: El agente no cumple correctamente su trabajo al momento de seguir las instrucciones dadas por el usuario a través del prompt, alucina y hace cosas al momento de editar una imagen que no se pidieron.
Environment: El agente interactúa con imágenes dadas por el usuario en primera instancia.
Actuators: El Agente produce una imagen editada a petición del usuario mediante las instrucciones del prompt 
Sensors: El agente recibe como entrada una imagen y un prompt dado por el usuario. 
________________________________________
4. Clasificación del entorno
Complete la siguiente tabla y justifique brevemente cada respuesta.
Propiedad Clasificación Justificación
________________________________________
Observable: Total

Determinista:  No
Episódico: Sí 

Estático: Sí 

Discreto: Sí 

Conocido: Sí 
________________________________________
5. ¿Qué tipo de programa de agente creen que es?
Seleccione la opción que consideren más adecuada y explique por qué.
•	Agente de reflejo simple <-------

•	Agente basado en modelo

•	Agente basado en objetivos

•	Agente basado en utilidad

•	Agente con aprendizaje

Importante: No existe una única respuesta correcta. Lo importante es justificar la elección a partir del comportamiento observado.
Justificación: Es un agente de reflejo simple debido a que el agente no recuerda cada acción, tampoco tiene la capacidad de tener un historial de prompts, solo tiene una única capacidad de respuesta, y para obtener otra, simplemente es necesario volver a escribir el prompt y cambiar de imagen de ser el caso.
________________________________________
