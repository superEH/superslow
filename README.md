# slowloris
Un DDoS, siglas en inglés de Distributed Denial of Service o ataque de denegación de servicio, es un ciberataque masivo a un servidor que provoca una sobrecarga en las webs a las cual provee por la enorme cantidad de entradas que reciben en un espacio reducido de tiempo, lo que hace que las páginas asaltadas se ralenticen, en el mejor de los casos, o que simplemente dejen de funcionar.
DDoS son las siglas de Distributed Denial of Service. La traducción es “ataque distribuido denegación de servicio”, y traducido de nuevo significa que se ataca al servidor desde muchos ordenadores para que deje de funcionar.

Pero aun así esto no nos guía mucho sobre lo que es un DDoS. Para explicarlo voy a recurrir a una simple analogía en la que nuestro servidor es un auxiliar que atiende a personas en una ventanilla.

Nuestro auxiliar es muy eficiente y es capaz de atender a varias personas a la vez sin despeinarse: es su carga normal. Pero un día empiezan a llegar cientos de personas a la ventanilla a pedirle cosas a nuestro auxiliar. Y como cualquier humano normal, cuando hay mucha gente dándole la lata no puede atender a todos y empieza a atender más lento de lo normal. Si viene todavía más gente probablemente acabe hasta las narices, se marchará de la ventanilla y ya no atenderá a nadie más.

En el servidor pasa lo mismo: cuando hay demasiadas peticiones se queda sin recursos, se cuelga y deja de funcionar. Puede que se apague directamente o que sólo deje de responder conexiones. De cualquiera de las dos formas, el servidor no volverá a la normalidad hasta que el ataque pare, ya sea porque los atacantes han parado o porque se logrado bloquear las conexiones ilegítimas (veremos más adelante cómo), y se rearranque todo lo que haya dejado de funcionar.

Este es el concepto básico del DDoS, aunque se puede modificar para que sea más efectivo. Por ejemplo, se pueden enviar los datos muy lentamente haciendo que el servidor consuma más recursos por cada conexión (Slow Read es un ejemplo de ataque de este tipo), o alterar los paquetes para que el servidor se quede esperando indefinidamente una respuesta de una IP falsa

