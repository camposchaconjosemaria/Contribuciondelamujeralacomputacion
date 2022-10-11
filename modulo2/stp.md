# Spanning Tree Protocol

Tanto el algoritmo de ***Spanning Tree, como el protocolo (STP)***, fueron inventados por **Perlamn** mientras trabajaba como consultora en 
*Digital Equipment Corporation (DEC)* en 1984. Donde se le asignó la tarea de elaborar un protocolo sencillo que permitiera a 
los puentes de la red ubicar bucles en una red de área local **(LAN)**.Se requería que el protocolo usara una cantidad constante de memoria cuando se implementara en
los dispositivos de la red, sin importar el tamaño de la red. Construir y expandir redes puenteadas fue difícil porque los bucles, donde más de una ruta lleva al
mismo destino, podrían provocar el colapso de la red. Las rutas redundantes en la red significaban que un puente podría enviar una trama en múltiples direcciones.
Por lo tanto, los bucles podrían hacer que las tramas Ethernet no lleguen a su destino, inundando la red. Perlman utilizó el hecho de que los puentes tenían direcciones
MAC únicas de 48 bits, y diseñó un protocolo de red para que los puentes dentro de la LAN se comunicaran entre sí. El algoritmo implementado en todos los puentes de la 
red permitió que los puentes designaran un puente raíz en la red. Cada puente luego mapeo la red y determinó la ruta más corta al puente raíz, desactivando otras rutas 
redundantes. A pesar de las preocupaciones de Perlman porque el protocolo Spanning Tree tardo aproximadamente un minuto en reaccionar cuando ocurrían cambios en la 
topología de la red, en el momento en el que un bucle podía interrumpir la red, el Instituto de Ingeniería Eléctrica y Electrónica lo estandarizó como 802.1D ***(IEEE)***.
**Perlman** dijo que los beneficios del protocolo equivalen al hecho de que "no hay que preocuparse por la topología de la red" al cambiar la forma en que una LAN está 
interconectada. Sin embargo, Perlman ha criticado que se hicieron cambios en el transcurso de la estandarización del protocolo. 
