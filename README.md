🤖 Kit Educativo Pequeños Ingenieros — Placa BMX-01 & Ecosistema Abierto
Hardware Open Source License: CERN-OHL-P

Ecosistema abierto de Hardware y Software Libre desarrollado para la plataforma educativa de robótica y electrónica BMX-01. El objetivo de este proyecto es democratizar el acceso a la tecnología, la programación y la robótica educativa.

📋 Contenido del Repositorio
├── 📂 hardware/       # Diseños de PCB (Archivos KiCad, Esquemáticos, Gerbers y BOM)
├── 📂 enclosure/      # Plantillas de corte láser y planos 3D para la caja Pequeños Ingenieros
├── 📂 docs/           # Manuales de usuario, guías pedagógicas y fichas técnicas
├── 📂 web/            # Código fuente de la plataforma web interactiva
└── 📂 firmware/       # Códigos de ejemplo (Arduino IDE / MicroPython / mBlock)

🛠️ 1. Características de la Placa PCB (BMX-01)
La tarjeta de desarrollo BMX-01 está integrada alrededor del módulo ESP32-WROOM-32D (Wi-Fi + Bluetooth) e incluye periféricos directamente en la placa para facilitar las prácticas:

Control Central: ESP32-WROOM-32D con puerto Micro-USB/USB-C para programación.

Actuadores y Salidas:

Driver L293D para motores DC (Borneras P1 / P2).

Array ULN2003 para motor paso a paso.

Relé electromecánico de 5V (NO/COM/NC).

Conector dedicado para Servomotor (PWM).

Matriz RGB de 16 LEDs direccionables (WS2812B / Neopixel en rejilla 4x4).

Display de 7 segmentos de 4 dígitos (Controlador TM1637).

Puerto de expansión I2C para pantalla OLED.

Buzzer/Bocina integrados y LEDs de estado.

Sensores y Entradas:

Header para sensor de ultrasonido HC-SR04.

Sensor de Luz (LDR) y Sensor de Inclinación.

Sensor de Temperatura.

Receptor Infrarrojo (IR).

Matriz de botones y potenciómetro analógico.

📦 2. Caja "Pequeños Ingenieros"
Incluye los planos vectoriales y modelos tridimensionales para la fabricación del chasis contenedor:

Corte Láser (.DXF, .SVG): Diseños para acrílico o MDF de 3mm / 4mm.

Impresión 3D (.STL, .STEP): Soportes, botones y protecciones suplementarias.

📚 3. Manuales y Software
Manuales: Guías paso a paso clasificadas por nivel (Básico, Intermedio y Avanzado) ubicadas en la carpeta /docs.

Plataforma Web: Portal interactivo con documentación en línea y recursos descargables en la carpeta /web.

⚖️ Licencias
Hardware: CERN Open Hardware Licence Permissive (CERN-OHL-P).

Documentación y Diseños 3D: Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0).

Software y Firmware: MIT License.
