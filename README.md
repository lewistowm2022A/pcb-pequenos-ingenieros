# 🤖 Kit Educativo Pequeños Ingenieros — Placa BMX-01 & Ecosistema Abierto

[![Hardware License](https://img.shields.io/badge/Hardware_License-CERN--OHL--P-blue.svg)](https://ohwr.org/cernohl)
[![Software License](https://img.shields.io/badge/Software_License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Documentation License](https://img.shields.io/badge/Docs_License-CC_BY--SA_4.0-orange.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

Ecosistema abierto de Hardware y Software Libre desarrollado para la plataforma educativa de robótica y electrónica **BMX-01**. El objetivo principal de este proyecto es democratizar el acceso a la tecnología, la programación y la robótica educativa.

---

## 📋 Contenido del Repositorio

```text
.
├── 📂 hardware/       # Diseños de PCB (Archivos KiCad, Esquemáticos, Gerbers y BOM)
├── 📂 enclosure/      # Plantillas de corte láser y planos 3D para la caja Pequeños Ingenieros
├── 📂 docs/           # Manuales de usuario, guías pedagógicas y fichas técnicas
├── 📂 web/            # Código fuente de la plataforma web interactiva
└── 📂 firmware/       # Códigos de ejemplo (Arduino IDE / MicroPython / mBlock)

🛠️ 1. Características de la Placa PCB (BMX-01)
La tarjeta de desarrollo BMX-01 está integrada alrededor del módulo ESP32-WROOM-32D (Wi-Fi + Bluetooth) e incluye periféricos directamente soldados en la placa para facilitar las prácticas sin necesidad de cables extra:

Control Central: ESP32-WROOM-32D con puerto Micro-USB/USB-C para programación.
🔌 Actuadores y Salidas:
Driver L293D para control de motores DC (Borneras P1 / P2).
Array ULN2003 dedicado para motor paso a paso.
Relé electromecánico de 5V (NO/COM/NC).
Conector dedicado para Servomotor (PWM).
Matriz RGB de 16 LEDs direccionables (WS2812B / Neopixel en rejilla 4x4).
Display de 7 segmentos de 4 dígitos (Controlador TM1637).
Puerto de expansión I2C (ideal para pantalla OLED).
Buzzer/Bocina integrados y LEDs indicadores de estado.
📡 Sensores y Entradas:
Header directo para sensor de ultrasonido HC-SR04.
Sensor de Luz (LDR) y Sensor de Inclinación integrados.
Sensor de Temperatura.
Receptor Infrarrojo (IR).
Matriz de botones y potenciómetro analógico.
📦 2. Caja "Pequeños Ingenieros"
Incluye los planos vectoriales y modelos tridimensionales para la fabricación del chasis contenedor:

Corte Láser (.DXF, .SVG): Diseños optimizados para corte en acrílico o MDF de 3mm y 4mm.
Impresión 3D (.STL, .STEP): Soportes estructurales, botones y protecciones suplementarias.
📚 3. Manuales y Software
Manuales: Guías pedagógicas paso a paso clasificadas por nivel de dificultad (Básico, Intermedio y Avanzado) ubicadas en la carpeta /docs.
Plataforma Web: Portal interactivo con documentación en línea y recursos descargables disponibles en la carpeta /web.
⚖️ Licencias
Este proyecto promueve la filosofía del conocimiento libre. Los componentes se distribuyen bajo las siguientes licencias:

Hardware: CERN Open Hardware Licence Permissive (CERN-OHL-P)
Documentación y Diseños 3D: Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)
Software y Firmware: MIT License
