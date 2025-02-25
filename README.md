# Tareas y requerimientos
**Una empresa multinacional desea implementar un sistema de videoconferencia para conectar sus oficinas en diferentes ciudades. Este sistema debe garantizar la transmisión de video en alta definición en tiempo real, integrar dispositivos IoT (como cámaras inteligentes y sistemas de audio en las salas de reuniones) y ofrecer altos niveles de seguridad para proteger el tráfico contra amenazas y accesos no autorizados.**

## 1. Diseño de Arquitectura (Modelos OSI/TCP‑IP y Comunicación):
### Esquematizar la arquitectura lógica de la red utilizando los modelos OSI y TCP/IP.
**Repasen los modelos OSI y TCP/IP.**
**En un documento, expliquen brevemente las funciones de cada capa (física, red, transporte, aplicación, etc.) y cómo se integran en la solución.**
### Incluir dispositivos de videoconferencia, servidores de aplicaciones y equipos de red.
**Realicen un diagrama conceptual (a mano o con herramientas de diagramación) que muestre la interconexión entre las sedes de la empresa, los dispositivos de videoconferencia, servidores y equipos de red.**
**Indiquen qué dispositivos (routers, switches, servidores, etc.) se utilizarán y cómo se segmentará la red (por ejemplo, mediante VLANs para separar tráfico de videoconferencia del resto).**

## 2. Capa Física:
### Calcular la tasa de transmisión máxima necesaria utilizando la fórmula de Shannon para un canal con un ancho de banda y SNR definidos.
**Utilicen la fórmula de Shannon:
C=B×log2​(1+SNR) para calcular la tasa de transmisión necesaria en función del ancho de banda disponible y la relación señal a ruido (SNR) definida para la red.**
**Documenten el proceso de conversión de la SNR (por ejemplo, de dB a escala lineal) y muestren el cálculo.**
### Seleccionar la modulación adecuada para los enlaces cableados e inalámbricos.
**Revisen las opciones de modulación (BPSK, QPSK, 16-QAM, etc.) y determinen cuál es la más adecuada para los enlaces cableados e inalámbricos, justificando su elección en función de la eficiencia y la robustez ante interferencias.**

## 3. Capa de Red:
### Diseñar el esquema de direccionamiento IP para las oficinas (subneteo, cálculo de broadcast, rangos de hosts).
**Definan el esquema de direccionamiento para las sedes. Por ejemplo, diseñen subredes para cada oficina, calculen direcciones de red, direcciones de broadcast y rangos de hosts.**
**Incluyan cálculos y ejemplos prácticos (por ejemplo, utilizando una red tipo 10.0.0.0/24 para una oficina).**
### Aplicar el algoritmo de Dijkstra para determinar rutas óptimas entre sedes; mencionar cómo se usaría el enrutamiento por inundación en caso de contingencia.
**Implementen en el diagrama el algoritmo de Dijkstra para definir las rutas óptimas entre sedes.**
**Describan brevemente cómo se configuraría el enrutamiento por inundación para situaciones de contingencia.**

## 4. Capa de Transporte:
### Justificar la elección de UDP para el tráfico de videoconferencia (por latencia) y TCP para datos críticos.
**Expliquen por qué utilizarán UDP para el tráfico de videoconferencia (por menor latencia) y TCP para otros datos críticos (por fiabilidad).**
### Calcular el tamaño de ventana óptimo para los enlaces de videoconferencia considerando RTT y MSS.
**Utilicen parámetros como RTT y MSS para calcular el tamaño de ventana óptimo en los enlaces de videoconferencia.**
**Muestren el desarrollo del cálculo y expliquen cómo este valor ayuda a controlar la congestión.**

## 5. Capa de Aplicación y Multimedia:
### Seleccionar protocolos de aplicación (por ejemplo, SIP, H.323 o WebRTC) y definir cómo se gestionará el control de calidad (QoS) y adaptive streaming.
**Decidan qué protocolos usarán (por ejemplo, SIP, H.323 o WebRTC) y expliquen cómo gestionarán la resolución de nombres (DNS) para la localización de servidores.**
### Implementar la resolución de nombres (DNS) para la localización de servidores.
**Describan los mecanismos que permitirán el control de calidad (QoS) y la adaptación del streaming (adaptive streaming) en función del ancho de banda.**

## 6. Seguridad:
### Diseñar políticas de seguridad, incluyendo VPN y firewalls.
**Elaboren un plan que incluya el uso de VPN para conexiones seguras entre sedes y firewalls para el filtrado de tráfico.**
**Indiquen cómo se configurarán las ACLs (listas de control de acceso) para proteger la red.**
### Especificar el uso de cifrado (TLS/SSL) y autenticación (certificados, 2FA).
**Especificar el uso de TLS/SSL para cifrar el tráfico de videoconferencia y detallar mecanismos de autenticación (por ejemplo, certificados digitales y autenticación de dos factores).**

## 7. Implementación en Cisco Packet Tracer:
### Configurar routers, switches, servidores y dispositivos finales simulados en Cisco Packet Tracer.
**Utilicen Cisco Packet Tracer para construir la topología diseñada. Configuren routers, switches, servidores, dispositivos de videoconferencia y dispositivos IoT.**
**Asegúrense de simular la conectividad, la segmentación de la red (VLANs) y las rutas de enrutamiento configuradas.**
### Simular las rutas, la segmentación y la conectividad segura (uso de VPN, ACLs en firewalls, etc.).
**Configuren VPN, ACLs y firewalls en Packet Tracer para simular las medidas de seguridad propuestas.**
### Pruebas y verificación.
**Realicen pruebas de conectividad, enrutamiento y calidad del servicio (QoS) en Packet Tracer.**
**Documenten los resultados y capturen capturas de pantalla de la configuración y las pruebas exitosas.**
