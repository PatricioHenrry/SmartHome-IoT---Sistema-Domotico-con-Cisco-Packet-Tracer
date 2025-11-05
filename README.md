## 📡 **SmartHome con IoT** 📡
##   **Sistema Domotico con Cisco Packet Tracer** 
Sistema integral de domótica y seguridad implementado en Cisco Packet Tracer con IoT para automatización residencial. Conformado por sensores, actuadores y automatización basada en reglas.

---
## 🔒 Sistema de Seguridad
- Detección de intrusión multicapa
- Alertas automáticas por diferentes vías
- Registro de eventos de seguridad
- Integración con sistemas de vigilancia (cámaras)

## 🌡️ **Control Ambiental**
- Termorregulación automática
- Protección contra condiciones extremas
- Monitoreo de calidad del aire
- Eficiencia energética integrada

## 🏠 **Confort Doméstico**
- Automatización de electrodomésticos
- Control de iluminación adaptativo
- Gestión de acceso inteligente
- Sistema de entretenimiento integrado
---
## 📡 **Sensores y Dispositivos IoT**
- **Sensor de Movimiento** - Vigilancia perimetral 
- **Cámara de Seguridad (Velocam)** - Videovigilancia 
- **Sensor de Monóxido de Carbono** - Detección de niveles peligrosos de CO
- **Sensor de Temperatura** - Monitoreo ambiental
- **Contactos de Puertas** - Estado de apertura/cierre

## 🌡️ **Actuadores y Dispositivos Controlados**
- **Puerta de Garaje** - Control automático
- **Puerta Principal** - Seguridad de acceso
- **Sistema de Calefacción** - Control climático
- **Sistema de Audio** - Entretenimiento
- **Iluminación** - Automatización lumínica
- **Cafetera** - Electrodomésticos inteligentes

## 🏠 **Dispositivos de Red**
- Router Cisco
- Servidor local
- Dispositivos cliente (PC, smartphone)
---

## 🤖 Reglas para la automatización 🤖

| Nombre | Condición  | Acción  |
|--------|----------------|---------------|
| activar sensor | Movimiento == ON | Sirena ON + Cámara ON |
| prender aire | Temp >= 17°C | Aire ON |
| apagar aire | Temp <= 10°C | Aire OFF |
| prender calefacción | Temp < 5°C | Calefacción ON |
| sirena humo | Humo >= 15 | Sirena ON + Café ON + Luz ON |
| prender luz | Puerta Casa == Abierta | Luz ON |
| sirena monóxido | CO >= 15 | Sirena ON + Café ON |
| garage | Garage == OPEN | Luz + Café ON |
| extintor incendio | Fuego == TRUE | Aspersor ON + Sirena ON |
| apagar aspersor | Fuego == FALSE | Aspersor OFF + Sirena OFF |



---
## 📋 Instrucciones de Implementación

### Configuración Inicial
1. Abrir el archivo `.pkt` en Cisco Packet Tracer
2. Verificar la conectividad de todos los dispositivos
3. Validar las configuraciones IP
4. Probar la comunicación entre sensores y actuadores

## 📋 Pruebas de Funcionalidad
1. Simular activación de sensores de movimiento
2. Verificar respuestas automáticas del sistema
3. Probar condiciones climáticas extremas
4. Validar protocolos de seguridad
---
## ⚙️
| Software | Versión |
|----------|---------|
| Cisco Packet Tracer | 7.3.1 (compatible también con 8.x) |
| Sistema operativo | Windows / Linux / Mac |
| Hardware | Cualquier PC que pueda ejecutar Packet Tracer |
