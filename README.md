# [cite_start]Diseño de Driver de Semiconductor de Potencia (Altium Designer) [cite: 1074]

**Estado del Proyecto:** Diseño completado. El informe técnico completo está finalizado y disponible en este repositorio.

---

## 1. Resumen del Proyecto

[cite_start]Este repositorio contiene todos los archivos de diseño y la documentación técnica del rediseño y optimización de un **driver de semiconductor de potencia**[cite: 1097]. [cite_start]El proyecto fue desarrollado íntegramente en **Altium Designer** [cite: 1086] [cite_start]con el objetivo de mejorar la funcionalidad, seguridad y eficiencia de un diseño base [cite: 1097][cite_start], enfocado en aplicaciones de alta fiabilidad como las energías renovables[cite: 1094].

[cite_start]Las mejoras clave incluyen la **integración de compuertas lógicas** para la protección de la etapa de control [cite: 1102] [cite_start]y una optimización robusta del layout para manejar altas corrientes y minimizar interferencias (EMI)[cite: 1087, 1104].

### ➡️ Informe Técnico Completo
Para un análisis detallado de la metodología, los cálculos de la norma IPC, la lista de materiales (BOM) y la discusión técnica, consulte el informe completo:

**[Ver Informe Técnico (PDF)](./JARH_Proyecto_Final.pdf)**

---

## 2. Herramientas y Metodología

* [cite_start]**Software Principal:** Altium Designer [cite: 1108]
* **Actividades Clave:**
    * [cite_start]Creación de Bibliotecas Personalizadas (Símbolos, Footprints y Modelos 3D)[cite: 1112, 1114, 1115].
    * [cite_start]Diseño de Esquemático y Layout de PCB (2 Capas)[cite: 1110, 1225].
    * Generación de Archivos de Fabricación.

---

## 3. Características Técnicas Destacadas

* [cite_start]**Diseño para Alta Corriente (IPC-2221):** Cálculo y aplicación de anchos de pista específicos para manejar hasta **9A** [cite: 1421][cite_start], basados en la norma IPC-2221 para pistas externas[cite: 1413, 1414].
* [cite_start]**Integridad de Señal y Aislamiento:** Implementación de **planos de tierra (GND) sólidos** [cite: 1268, 1283] [cite_start]y ruteo estratégico para mantener el aislamiento galvánico[cite: 1087].
* [cite_start]**Diseño para Fabricación (DFM):** Verificación del diseño contra las capacidades del fabricante [cite: 1326] [cite_start]y uso de reglas de diseño (DRC) para validación[cite: 1411].

## 4. Vistas del Proyecto (Renders 3D)

*Inserte aquí sus mejores imágenes del proyecto. Recomiendo las Imágenes 12, 13 y 14 de su PDF.*

[cite_start]**(Imagen 12: Vista Superior 3D)** [cite: 1440]
<img src="./Img/TopView_Driver.jpg" alt="Vista Superior del PCB" width="700" />

[cite_start]**(Imagen 13: Vista Inferior 3D)** [cite: 1468]
<img src="./Img/BottomView_Driver.jpg" alt="Vista Inferior del PCB" width="700" />
