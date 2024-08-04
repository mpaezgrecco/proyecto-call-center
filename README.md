# Proyecto Call Center

## Introducción
El análisis de datos del call center tiene como objetivo evaluar el desempeño y la eficiencia de nuestros servicios, con un enfoque particular en identificar áreas de mejora y optimizar la experiencia del cliente. A través de este estudio, se han examinado diversos indicadores clave de rendimiento (KPIs) para responder preguntas críticas sobre el nivel de servicio, la eficiencia operativa y la satisfacción del cliente. 

## Descripción de los Datos
El dataset utilizado en este análisis contiene información detallada sobre las llamadas gestionadas por el call center, incluyendo columnas como:
- **vru.line**: Código de la unidad de respuesta de voz.
- **call_id**: Código de la llamada.
- **costumer_id**: Código de cliente.
- **Priority**: Prioridad de la llamada.
- **type**: Tipo de llamada.
- **date**: Fecha de la llamada.
- **vru_entry**: Hora de entrada a la unidad de respuesta de voz.
- **vru_exit**: Hora de salida de la unidad de respuesta de voz.
- **vru_time**: Tiempo que duró la unidad de respuesta de voz.
- **q_star**: Hora de entrada a la cola.
- **q_exit**: Hora de salida de la cola.
- **q_time**: Duración en la cola.
- **outcome**: Resultado de la llamada (tomada por agente, colgaron, fantasma).
- **ser_star**: Hora en que el agente contesta.
- **ser_exit**: Hora en que el agente cuelga.
- **ser_time**: Duración de la llamada con el agente.
- **server**: Nombre del agente.

## Respuestas a las Preguntas Planteadas
- **¿Cuál es el nivel de servicio para los clientes Prioritarios?**
 El nivel de servicio para los clientes prioritarios es del 72.55%, lo cual indica un buen desempeño, aunque hay margen para mejoras.

- **¿Damos un mejor servicio que a los clientes normales?**
 Sí, el análisis muestra que los clientes prioritarios reciben un mejor servicio comparado con los clientes normales.

-**¿Qué volumen de llamadas atendemos?**
 El call center atiende un volumen de 54.47 mil llamadas por día, lo que demuestra una alta demanda de nuestros servicios.

-**¿Cuáles son los cuellos de botella? ¿En qué días? ¿En qué bandas horarias?**
 El mayor cuello de botella se observa en el tiempo de espera, especialmente cuando las personas están en espera por más de 20 minutos. En estos casos, el 58.97% de las llamadas son abandonadas y solo el 35.9% son completadas. Este problema ocurre principalmente los miércoles durante la noche, de 6 pm a 12 am. Aunque el 96.75% de las llamadas se contestan en menos de 5 minutos, el 19.92% de estas llamadas son abandonadas por los usuarios, con mayor incidencia los lunes por la tarde, de 12 pm a 6 pm.

-**¿Cómo es la eficiencia y productividad de nuestros agentes?**
 El 58.04% de los agentes superan el tiempo promedio de atención en las llamadas, y el 69.8% ha atendido menos de 10,000 llamadas. Esto indica que tenemos menos de la mitad de los agentes que son eficientes y productivos.

-**¿Hay clientes recurrentes en el uso del servicio?**
 Sí, contamos con más de 10 mil clientes recurrentes, lo cual subraya la importancia de mantener un alto nivel de servicio y satisfacción del cliente.

**¿Cuáles son los tipos de servicio más recurrentes?** El servicio más recurrente es el PS, sin embargo, el servicio que consume más tiempo de los agentes es el IN.

-**¿Podemos estimar la dotación necesaria para cumplir con una calidad de servicio determinada?**
 Para cumplir con un tiempo promedio de espera menor a 60 segundos, es necesario contar con 62 agentes. Actualmente, necesitamos contratar 9 agentes más para alcanzar este objetivo.

 ## Conclusiones Finales

 El análisis del call center ha revelado áreas críticas para la mejora en la eficiencia y productividad de los agentes, así como en la experiencia del cliente. A pesar de un buen nivel de servicio para los clientes prioritarios, existen cuellos de botella significativos que afectan la tasa de abandono de llamadas, especialmente en ciertos días y horarios. La incorporación de más agentes y la optimización de los tiempos de espera son estrategias clave para mejorar la calidad del servicio. Además, el alto número de clientes recurrentes destaca la necesidad de mantener y mejorar continuamente los estándares de atención para asegurar la lealtad del cliente y el éxito sostenido del call center.
