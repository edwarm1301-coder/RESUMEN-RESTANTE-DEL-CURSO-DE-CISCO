# RESUMEN-RESTANTE-DEL-CURSO-DE-CISCO
RESUMEN RESTANTE DEL CURSO DE CISCO

Problemas con IPv4: El agotamiento de direcciones motivó la migración a IPv6, que ofrece un espacio de 128 bits y 340 sextillones de direcciones. La transición se apoya en técnicas como doble pila, tunelización y traducción (NAT64).

Asignación de direcciones IPv6: Estas direcciones de 128 bits se escriben en hexadecimal y cuentan con reglas de simplificación, como omitir ceros iniciales y el uso de puntos dobles (::) para representar segmentos de ceros.

Direccionamiento Estático y Dinámico: La asignación estática requiere configuración manual y ofrece control, mientras que la dinámica mediante DHCP es preferida en redes grandes por su eficiencia y reducción de errores.

Configuración de DHCPv4: El proceso implica mensajes de difusión (Discover, Offer, Request y Acknowledge) para asignar una IP desde un servidor a un cliente. Los enrutadores domésticos suelen tener esta función activa por defecto.

Límites de la Red: Cada host debe conocer su puerta de enlace predeterminada (interfaz del router) para acceder a otras redes. El router actúa como frontera entre la red interna y el Internet externo proporcionado por el ISP.

Funcionamiento de NAT: Permite que múltiples direcciones IPv4 privadas de una red local se traduzcan a una única dirección pública para enviar y recibir paquetes en Internet.

MAC e IP: Los dispositivos usan direcciones físicas (MAC) para comunicación en la misma red Ethernet y direcciones lógicas (IP) para el envío de paquetes entre el origen y el destino final, sea local o remoto.

Contención de Difusiones: Para evitar tráfico excesivo, se usan enrutadores que dividen la red en diferentes dominios de difusión. Se emplea el protocolo ARP (en IPv4) o Detección de Vecinos (en IPv6) para descubrir direcciones MAC.

La Necesidad del Enrutamiento: Los enrutadores de capa 3 son necesarios para interconectar redes, mejorar la seguridad, agrupar usuarios lógicamente y controlar el tráfico entre redes locales independientes.

La Tabla de Enrutamiento: Los enrutadores consultan una tabla interna para determinar el mejor camino hacia una red de destino. Si las direcciones IP de origen y destino no coinciden en red, el router reenvía el mensaje basándose en esta información.
