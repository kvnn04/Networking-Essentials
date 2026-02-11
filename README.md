# 🌐 Fundamentos de Redes: De la Teoría a la Práctica

Bienvenido a mi repositorio de documentación técnica sobre infraestructura y redes. Aquí analizo los pilares que permiten la interconexión de sistemas modernos.

---

## 📖 Documentación Principal
He consolidado mi aprendizaje en guías detalladas con diagramas y casos de uso prácticos:

* 📘 **[Modelo OSI: Guía de Referencia Teórica](https://docs.google.com/document/d/1mdpatcrNHZTnOpC1pIucI_53_1fOd2rn0WHk5S9eU64/edit?usp=sharing)**
* 📗 **[Modelo TCP/IP: La Arquitectura de Internet](https://docs.google.com/document/d/1Czebr4TyMqVkIZMpNTHY27LP6xFV5pqm_hTRb1_j2WQ/edit?usp=sharing)**

---

## 🚀 Conceptos Dominados

### 1. El Modelo OSI
Análisis de la pila teórica para entender el flujo de datos desde el hardware hasta el usuario final:

* **Capa 7 - Aplicación:** Interfaz de servicios de red para el usuario final. (Protocolos: **HTTP, DNS, FTP, SSH, SMTP**).
* **Capa 6 - Presentación:** Formateo, cifrado y compresión de datos. Asegura que la información sea legible. (**SSL/TLS, JSON, JPEG**).
* **Capa 5 - Sesión:** Establecimiento, gestión y finalización de sesiones entre aplicaciones.
* **Capa 4 - Transporte:** Segmentación, control de flujo y entrega confiable de datos punto a punto. (**TCP, UDP**).
* **Capa 3 - Red:** Determinación de rutas (Enrutamiento) y direccionamiento lógico. (**IPv4/IPv6, ICMP, Routers**).
* **Capa 2 - Enlace de Datos:** Transferencia de datos nodo a nodo y direccionamiento físico. (**MAC, Switches, Ethernet, ARP**).
* **Capa 1 - Física:** Transmisión binaria y especificaciones eléctricas/mecánicas del medio. (Cables, Fibra, Señal de Radio).


### 2. El Modelo TCP/IP (Arquitectura de Internet)
A diferencia del modelo OSI, el modelo TCP/IP es el estándar práctico que rige las comunicaciones actuales. Se organiza en 4 capas funcionales donde cada una añade información crítica (encabezados) para asegurar que los datos lleguen a su destino.



* **Capa de Aplicación:** Es el nivel superior donde residen los protocolos que las aplicaciones utilizan para intercambiar datos. Define cómo el software interactúa con la red, gestionando desde la visualización web (**HTTP/S**) hasta la resolución de nombres (**DNS**) y la transferencia de archivos. Es la capa donde se gestiona el cifrado de datos extremo a extremo.

* **Capa de Transporte:** Responsable de la comunicación host-a-host. Su función principal es la segmentación de datos y el control de errores. 

* **Capa de Internet:** Es el núcleo del enrutamiento. Aquí se definen las direcciones lógicas (**IP**) y se decide el mejor camino para que un paquete atraviese múltiples redes. Es la capa encargada de la fragmentación de paquetes y del direccionamiento global, permitiendo la existencia de subredes aisladas y seguras.

* **Capa de Acceso a la Red:** Define cómo se transmiten físicamente los datos a través del medio. Se encarga del direccionamiento físico (**MAC**) y de convertir los paquetes de datos en señales eléctricas o pulsos de luz para su transporte real.

---

## 🛠️ Stack Tecnológico & Certificaciones
![Redes](https://img.shields.io/badge/Networking-Theoretical-blue)
![TCP/IP](https://img.shields.io/badge/Model-TCP%2FIP-orange)
![OSI](https://img.shields.io/badge/Model-OSI-darkgreen)
![AWS](https://img.shields.io/badge/AWS-Infrastructure-FF9900?logo=amazon-aws&logoColor=white)

---

## 💡 ¿Por qué esta documentación?
Como **Analista de Sistemas**, mi enfoque no es solo escribir código, sino entender la infraestructura que lo sostiene. Dominar estos modelos me permite optimizar el rendimiento de servidores, asegurar las comunicaciones y resolver problemas complejos de conectividad en entornos Dockerizados.
