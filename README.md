# Prototipo de comunicación CAN para sistemas embebidos

Este repositorio documenta el desarrollo de un prototipo de comunicación basado en el protocolo CAN (Controller Area Network), orientado al estudio e implementación de intercambio de datos confiable entre sistemas embebidos. El proyecto combina un análisis teórico del protocolo con una implementación práctica en hardware y firmware.

El documento asociado presenta una descripción estructurada de los fundamentos de CAN, incluyendo su contexto histórico, las características de la capa física, el funcionamiento de la capa de enlace de datos, el mecanismo de arbitraje, la detección de errores y sus principales casos de uso. El análisis se basa en el estándar ISO 11898 y se centra en cómo las decisiones de diseño del protocolo contribuyen a la robustez, el determinismo y la tolerancia a fallos en redes embebidas.

La implementación práctica demuestra un prototipo básico de red CAN, en el cual múltiples nodos intercambian mensajes sobre un bus compartido sin la existencia de un controlador central. El sistema permite observar aspectos clave del protocolo, como el arbitraje de mensajes basado en prioridad de identificadores, la señalización diferencial y la transmisión confiable de tramas.

Una demostración del prototipo en funcionamiento se encuentra en el siguiente video:  
https://www.youtube.com/watch?v=HthmyCX7gJU

## Alcance del proyecto

- Estudio y análisis de las capas física y de enlace de datos del protocolo CAN  
- Implementación de una red CAN básica entre nodos embebidos  
- Validación experimental del comportamiento de transmisión y arbitraje  

## Notas

Este proyecto tiene un enfoque educativo y experimental. No pretende ser una implementación lista para producción ni certificada para aplicaciones de seguridad crítica, sino una demostración práctica de comprensión del protocolo y de los principios de comunicación en sistemas embebidos.
