ENLACE DEL PROYECTO DE TINKERCAD: https://www.tinkercad.com/things/01dKPdWPvW7-kanne-pcb

El proyecto consiste en el diseño e implementación de un sistema de control automático para el llenado de un tanque de agua utilizando un controlador PID y microcontroladores. Componentes principales del sistema:
1. Tanque de agua: El objeto principal a ser controlado. El objetivo es mantener el nivel de agua dentro de un rango específico.
2. Válvula de agua: Controla el flujo de agua hacia el tanque. La apertura y cierre de la válvula se controla mediante el microcontrolador.
3. Sensor de nivel de agua: Mide el nivel actual de agua en el tanque y envía esta información al microcontrolador.
4. Microcontrolador: Recibe la información del sensor de nivel de agua y utiliza un algoritmo de control PID para ajustar la posición de la válvula de agua.
Funcionamiento del sistema: El sensor de nivel de agua mide continuamente el nivel de agua en el tanque y envía esta información al microcontrolador. El microcontrolador, utilizando un algoritmo de control PID, calcula la diferencia entre el nivel de agua deseado y el nivel de agua actual (error). Luego, ajusta la posición de la válvula de agua para minimizar este error, es decir, para acercar el nivel de agua al nivel deseado.
 El controlador PID es una técnica de control de retroalimentación ampliamente utilizada en sistemas de control industrial. Los parámetros P (proporcional), I (integral) y D (derivativo) del controlador PID se ajustan para obtener un rendimiento óptimo.
Este proyecto proporciona una solución eficiente y automática para el control del nivel de agua en un tanque, minimizando la intervención humana y asegurando un control preciso del nivel de agua. Además, la implementación con microcontroladores hace que el sistema sea económico y fácilmente escalable para aplicaciones más grandes.


DOCUMENTO:
