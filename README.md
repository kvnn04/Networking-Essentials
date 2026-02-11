# 🌐 Fundamentos de Redes: De la Teoría a la Práctica

Bienvenido a mi repositorio de documentación técnica sobre infraestructura y redes. Aquí analizo los pilares que permiten la interconexión de sistemas modernos.

---

## 📖 Documentación Principal
He consolidado mi aprendizaje en guías detalladas y usos prácticos:

* 📘 **[Modelo OSI: Guía de Referencia Teórica](https://docs.google.com/document/d/1mdpatcrNHZTnOpC1pIucI_53_1fOd2rn0WHk5S9eU64/edit?usp=sharing)**
* 📗 **[Modelo TCP/IP: La Arquitectura de Internet](https://docs.google.com/document/d/1Czebr4TyMqVkIZMpNTHY27LP6xFV5pqm_hTRb1_j2WQ/edit?usp=sharing)**
* 📒 **[Direccionamiento IPv4: Máscaras, Subredes y Lógica Binaria](https://docs.google.com/document/d/1IB7W-QQVlQWOg4Nz5m7P6MaKiziQVBwDze7H90iQt3w/edit?usp=sharing)**

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

* **Capa de Aplicación:** Define cómo el software interactúa con la red, gestionando desde la visualización web (**HTTP/S**) hasta la resolución de nombres (**DNS**). Es donde reside la lógica de intercambio de datos y el cifrado extremo a extremo.
* **Capa de Transporte:** Responsable de la comunicación host-a-host. Su función principal es la segmentación de datos y el control de errores, diferenciando transmisiones fiables (**TCP**) de transmisiones rápidas (**UDP**).
* **Capa de Internet:** Es el núcleo del enrutamiento. Aquí se definen las direcciones lógicas (**IP**) y se decide el mejor camino para que un paquete atraviese múltiples redes, permitiendo la segmentación mediante subredes.
* **Capa de Acceso a la Red:** Define cómo se transmiten físicamente los datos a través del medio. Gestiona el direccionamiento físico (**MAC**) y la conversión de datos en señales para el transporte real.


### 3. Direccionamiento IPv4 y Subnetting
Fundamentos de segmentación lógica y el aprovechamiento del espacio de direcciones mediante la comprensión de la máscara de subred y el sistema binario.

* **La Máscara como Delimitador:** Comprensión de la máscara de subred no solo como un número, sino como el parámetro que define el alcance de búsqueda local. Determina cuándo un equipo puede comunicarse directamente y cuándo requiere de un Gateway (Router).
* **Lógica Binaria y Pesos de Bit:** Capacidad de descomponer octetos para entender el peso de cada bit. Esta base matemática permite comprender por qué las máscaras se llenan de izquierda a derecha y cómo se forman los valores decimales.
* **Ingeniería CIDR (Classless Inter-Domain Routing):** Implementación de esquemas de red modernos donde la máscara manda sobre la "Clase" de la IP. Uso de prefijos (ej. `/22`, `/24`) para crear redes de tamaño personalizado, optimizando recursos y mejorando la seguridad mediante el aislamiento de tráfico.
* **Cálculo de Rangos y Saltos:** Identificación del "Octeto Crítico" para calcular instantáneamente la dirección de red, el broadcast y el rango de hosts disponibles, asegurando que los servicios operen en los segmentos correctos.

---

## 🛠️ Stack Tecnológico & Certificaciones
![Redes](https://img.shields.io/badge/Networking-Theoretical-blue)
![TCP/IP](https://img.shields.io/badge/Model-TCP%2FIP-orange)
![OSI](https://img.shields.io/badge/Model-OSI-darkgreen)
![IPv4](https://img.shields.io/badge/IPv4-Subnetting-blueviolet)
![CIDR](https://img.shields.io/badge/CIDR-Engineering-red)
![AWS](https://img.shields.io/badge/AWS-Infrastructure-FF9900?logo=amazon-aws&logoColor=white)

---

## 💡 ¿Por qué esta documentación?
Como **Analista de Sistemas**, mi enfoque no es solo escribir código, sino entender la infraestructura que lo sostiene. Entender estos modelos y practicas me permite optimizar el rendimiento de servidores, diseñar redes escalables y resolver problemas de conectividad.
