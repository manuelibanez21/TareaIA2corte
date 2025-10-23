# Vigilancia Tecnológica de Protocolos de Comunicación Industrial

## 1. Protocolo Modbus  
**Descripción:**  
Modbus es un protocolo de comunicación industrial ampliamente utilizado, desarrollado por Modicon en 1979 para los controladores lógicos programables (PLCs).  
Opera bajo una arquitectura **maestro/esclavo**, donde un maestro consulta a uno o varios esclavos a través de líneas serie (RS-232, RS-485) o redes Ethernet (Modbus TCP).

**Características técnicas:**  
- Comunicación basada en registros (lectura y escritura).  
- Admite hasta 247 dispositivos esclavos por red Modbus RTU.  
- Compatible con múltiples plataformas industriales.  
- Bajo costo y alta interoperabilidad.  
- Limitado en velocidad y determinismo frente a protocolos modernos.

**Tendencias tecnológicas:**  
- Integración con redes Ethernet industriales (Modbus TCP/IP).  
- Uso combinado con RS-485 en sistemas híbridos.  
- Ampliación hacia entornos IIoT y sistemas SCADA conectados.

---

## 2. Protocolo AS-Interface (AS-i)  
**Descripción:**  
AS-Interface es un sistema de bus de campo diseñado para conectar sensores y actuadores al nivel de campo mediante un cable plano de dos hilos que transmite tanto energía como datos.  
Fue concebido como una solución simple y económica para sustituir cableado punto a punto.

**Características técnicas:**  
- Arquitectura maestro-esclavo.  
- Un maestro puede gestionar hasta 62 dispositivos esclavos.  
- Transmisión de datos y energía en un solo cable.  
- Topología flexible: línea, estrella o árbol.  
- Ideal para sensores y actuadores simples.  

**Tendencias tecnológicas:**  
- Integración con redes de nivel superior (Profinet, Profibus).  
- Ampliación hacia AS-i Safe para aplicaciones de seguridad industrial.  
- Persistencia en entornos donde se busca bajo costo y simplicidad.

---

## 3. Ethernet Industrial y Nuevas Categorías  
**Descripción:**  
El Ethernet industrial adapta la tecnología Ethernet tradicional a entornos industriales, proporcionando **robustez, determinismo, redundancia y alta velocidad**.  
Permite integrar dispositivos de campo, control y supervisión en una misma red.

**Características técnicas:**  
- Uso de cables blindados y conectores industriales (M12, RJ45 reforzados).  
- Soporte de protocolos industriales: **Profinet, EtherNet/IP, EtherCAT, POWERLINK, CC-Link IE**.  
- Mayor inmunidad al ruido y tolerancia a condiciones extremas.  
- Compatible con cableado de **categorías Cat5e, Cat6, Cat6a, Cat7 y Cat8**.

**Nuevas categorías y tendencias:**  
- Adopción de **Cat6a, Cat7 y Cat8** para mayores velocidades y distancias más largas.  
- Creciente uso de **fibra óptica** en redes industriales de alto rendimiento.  
- Avance hacia redes **convergentes IT/OT**.  
- Implementación de **TSN (Time Sensitive Networking)** para comunicaciones en tiempo real.  
- Enfoque en **ciberseguridad y segmentación de red** para sistemas industriales.

---

## 4. IPv4 vs IPv6

### 4.1 ¿Qué es IPv4?  
IPv4 (Internet Protocol version 4) es la versión más antigua y extendida del protocolo IP, usada para direccionar y enrutar dispositivos en una red.  
Utiliza direcciones de **32 bits**, con un espacio de aproximadamente **4,3 mil millones de direcciones**.  

**Características:**  
- Formato decimal separado por puntos (ejemplo: `192.168.0.1`).  
- Usa **NAT** para reutilizar direcciones privadas.  
- Encabezado sencillo y soporte universal.  
- Limitaciones en el número de direcciones y escalabilidad.

---

### 4.2 ¿Qué es IPv6?  
IPv6 (Internet Protocol version 6) es la evolución de IPv4, creada para resolver el agotamiento de direcciones y mejorar la eficiencia de red.  
Usa direcciones de **128 bits**, equivalentes a aproximadamente `3.4 × 10^38` combinaciones posibles.

**Características:**  
- Formato hexadecimal separado por dos puntos (ejemplo: `2001:db8::1`).  
- No requiere NAT gracias a su enorme espacio de direccionamiento.  
- Autoconfiguración mediante **SLAAC** y soporte integrado para **IPsec**.  
- Encabezado más eficiente y soporte para QoS (Calidad de Servicio).  
- Mejora la seguridad y escalabilidad de las redes.

---

### 4.3 Diferencias entre IPv4 e IPv6  

| Característica | IPv4 | IPv6 |
|----------------|------|------|
| Longitud de dirección | 32 bits | 128 bits |
| Espacio de direcciones | 4.3 mil millones | 3.4 × 10^38 |
| Formato | Decimal con puntos (192.168.1.1) | Hexadecimal con dos puntos (2001:db8::1) |
| NAT | Necesario | No necesario |
| Autoconfiguración | DHCP | SLAAC o DHCPv6 |
| Seguridad | Opcional | Integrada (IPsec nativo) |
| Velocidad de procesamiento | Menor | Mayor (encabezado optimizado) |
| Soporte QoS | Limitado | Mejorado |
| Uso actual | Amplio, en declive progresivo | En adopción global creciente |

---

## 5. Aplicación en Redes Industriales  
- **IPv4** sigue siendo predominante en redes industriales y sistemas SCADA.  
- **IPv6** se está integrando progresivamente para habilitar redes con gran cantidad de dispositivos IoT y sensores distribuidos.  
- La coexistencia **dual-stack (IPv4 + IPv6)** permite compatibilidad entre sistemas nuevos y antiguos.  
- En la industria, IPv6 facilita la escalabilidad, el monitoreo remoto y la gestión directa de dispositivos en la nube.

---

## 6. Conclusión  
La **vigilancia tecnológica** en los protocolos de comunicación industrial demuestra una tendencia hacia la **convergencia digital y la automatización inteligente**:  
- **Modbus** continúa siendo una tecnología esencial por su simplicidad e integración en sistemas SCADA.  
- **AS-i** mantiene relevancia en el nivel de sensores y actuadores por su bajo costo y cableado optimizado.  
- **Ethernet industrial** lidera la transformación hacia redes rápidas, seguras y con soporte para IIoT.  
- La transición de **IPv4 a IPv6** marca un cambio estructural hacia un ecosistema más conectado, escalable y seguro.

En conjunto, estas tecnologías son la base de la **Industria 4.0**, donde la conectividad, la interoperabilidad y la ciberseguridad definen el nuevo estándar de la automatización industrial.
