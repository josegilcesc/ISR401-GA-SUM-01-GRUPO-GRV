# GA-PE-U1 · SUM · Práctica Experimental Unidad I: Ingeniería y Proceso de Requisitos

**Universidad Técnica Estatal de Quevedo (UTEQ)**  
**Facultad de Ciencias de la Computación — Carrera de Ingeniería de Software (Rediseño)**  
**Asignatura:** Ingeniería de Requerimientos [20303 / ISR-401] — 4to Nivel Paralelo "B"  
**Docente Responsable:** Ing. Gleiston Cicerón Guerrero Ulloa, Ph.D.  
**Periodo Académico:** 2026–2027 SPA  

---

## 1. Descripción del Proyecto Fin de Curso (PFC)
El presente repositorio contiene el desarrollo integral de la **Práctica Experimental de la Unidad I**, aplicada al sistema real seleccionado para el Proyecto Fin de Curso (PFC):

> **Sistema Seleccionado:** *Plataforma de Ventas con Módulo de Recomendación basado en Inteligencia Artificial para Establecimientos Comercializadores de Suministros Eléctricos en el cantón Quevedo.*

La investigación articula los fundamentos de la Ingeniería de Requisitos con el marco normativo internacional (**ISO/IEC/IEEE 29148:2018**, **ISO/IEC/IEEE 15288:2023**, **ISO/IEC/IEEE 12207:2017**, **ISO/IEC 25010:2023**, **SWEBOK v4.0**, **PMBOK 7.ª ed.**, **IREB CPRE FL v3.1** y **Klaus Pohl 2025**). Siguiendo el principio de abstracción de la Ingeniería de Requisitos (*propiedad "Apropiado al nivel" de IEEE 29148*), todas las especificaciones del sistema han sido formuladas de manera **agnóstica a la tecnología**, enfocándose estrictamente en el *qué* debe resolver el sistema y sus umbrales verificables de calidad sin imponer diseño prematuro.

---

## 2. Nómina Oficial de Integrantes y Roles del Equipo

| Apellidos y Nombres | Cédula (CI) | Correo Institucional | Rol Asignado en el Proyecto |
| :--- | :---: | :--- | :--- |
| **Gilces Carranza José Ignacio** | `1251059240` | `jgilcesc3@uteq.edu.ec` | **Analista Líder e Investigador B:** Coordinación general, auditoría de abstracción tecnológica (eliminación de diseño prematuro), desarrollo de secciones 2.3–2.4, catálogo de 15 requisitos EARS/ISO 25010 (C1), matriz de calidad IEEE 29148 (C2) y conclusiones 1–2. |
| **Vélez Vinces Jostin Gustavo** | `1316917838` | `jvelezv10@uteq.edu.ec` | **Investigador A:** Matriz Poder/Interés de stakeholders (PMBOK), clasificación del sistema, desarrollo de secciones 2.1–2.2, definición del límite del sistema (5 interfaces externas), declaración de visión de Moore, análisis de las 8 perspectivas de contexto de Pohl, Mapa Conceptual (Figura 1) y conclusión 3. |
| **Robinson Espinoza Jeanpierre** | `1722574223` | `jrobinsone@uteq.edu.ec` | **Investigador C y Documentador:** Gestión de las 12 fuentes primarias en estilo IEEE, desarrollo de secciones 2.5–2.6, mapeo de actores y framework de IR (C3), secuencia de artefactos prácticos del proceso (`ACTA-ELI-01`, `ANA-01`, `ESP-01`, `VAL-01` para C4), conclusiones 4–5, portada UTEQ y Anexos A y B. |

---

## 3. Estructura del Repositorio

```text
GA-SUM-01_PE-U1_Proceso-de-Requisitos/
├── README.md                                 # Documentación general del repositorio
├── main.tex                                  # Código fuente LaTeX principal integrado (multipágina con ltablex)
├── referencias.bib                           # Base bibliográfica BibLaTeX con las 12 fuentes primarias obligatorias
├── PE1_U1_GILCES_VELEZ_ROBINSON.pdf          # Informe final compilado para entrega oficial en SGA
├── figura/
│   ├── mapa_conceptual.drawio                # Archivo fuente editable en draw.io (Paso 5d)
│   ├── mapa_conceptual.png                   # Figura 1: Mapa Conceptual Integrador con 4 vínculos cruzados
│   └── zotero_evidencia.png                  # Anexo B: Captura de pantalla de la biblioteca grupal IEEE
├── sections/                                 # Módulos estructurales del documento
│   ├── sec0_pfc_y_bib.tex                    # Sección 0 (Equipo, PFC, Stakeholders, Clasificación) y Paso 2
│   ├── sec2_fundamento.tex                   # Sección 2: Fundamento Teórico (Subsecciones 2.1 a 2.6)
│   ├── sec3_part1_requisitos.tex             # Sección 3 (Parte 1): Paso 4 / Criterios C1 y C2 (15 Requisitos EARS)
│   ├── sec3_part2_contexto_y_proceso.tex     # Sección 3 (Parte 2): Paso 5 y Criterios C3 y C4 (Contexto y Artefactos)
│   └── sec4_conclusiones_y_anexos.tex        # Paso 6: 5 Conclusiones, Declaración de IA y Anexos A y B
└── Aportes/                                  # Evidencia individual auditable por integrante
    ├── Gilces Carranza Jose Ignacio/
    │   ├── README.md
    │   ├── aporte_gilces.bib
    │   ├── aporte_gilces.tex
    │   └── figura/
    ├── Velez Vinces Jostin Gustavo/
    │   ├── README.md
    │   ├── aporte_velez.bib
    │   ├── aporte_velez.tex
    │   └── figura/
    └── Robinson Espinoza Jeanpierre/
        ├── README.md
        ├── aporte_robinson.bib
        ├── aporte_robinson.tex
        └── figura/
```

---

## 4. Trazabilidad de Cumplimiento de la Rúbrica SGA y Guía de Práctica

* **Gatekeepers (G1, G2, G3):** Aplicado a un sistema real del contexto comercial de Quevedo (G1), con nómina completa de integrantes en portada y Tabla I (G2), y evidencia empírica de aplicación del proceso (G3).
* **Criterio C1 (20% — Identificación y clasificación de requisitos):** Tabla III con **15 requisitos únicos** (`REQ-01` a `REQ-15`) cubriendo negocio, stakeholder, usuario, funcionales en sintaxis **EARS**, no funcionales cuantificados con **ISO/IEC 25010:2023**, interfaces (UI, HW, SW, COM), restricciones operativas y conformidad legal (SRI / LOPDP) bajo priorización **MoSCoW**.
* **Criterio C2 (20% — Propiedades de calidad IEEE 29148):** Tabla IV con evaluación individual verificable de cada requisito contra *Necesidad, Apropiado al nivel (libre de tecnologías de implementación), Inambigüedad, Completitud, Singularidad, Verificabilidad y Trazabilidad*.
* **Criterio C3 (15% — Actores y framework de IR):** Tabla VII con mapeo de actores concretos del PFC y sus responsabilidades en actividades *core* y transversales.
* **Criterio C4 (25% — Aplicación del proceso de requisitos):** Tablas VIII, IX, X y XI con los 4 artefactos secuenciales aplicados al PFC: Elicitación (`ACTA-ELI-01`), Análisis y Negociación de Conflictos (`ANA-01`), Especificación Detallada SRS (`ESP-01`) y Protocolo de Validación UAT (`VAL-01`).
* **Criterio C5 (10% — Fundamento teórico y referencias):** Secciones 2.1 a 2.6 desarrolladas con definición formal citada, explicación propia (>3 oraciones) y ejemplo del PFC, respaldadas por las 12 fuentes primarias en formato IEEE comprimido `[1-12]`.
* **Criterio C6 (10% — Calidad documental):** Maquetación profesional en LaTeX (`IEEEtran` + `ltablex` para tablas multipágina continuas), 5 conclusiones individuales (>80 palabras c/u), declaración de validación crítica de IA y Anexos A y B referenciados.

---

## 5. Instrucciones de Compilación (LaTeX + Biber)

Para compilar el documento desde cero y generar el PDF final con soporte para tablas multipágina (`ltablex`) y bibliografía IEEE (`biber`), ejecute la siguiente secuencia de comandos:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
mv main.pdf PE1_U1_GILCES_VELEZ_ROBINSON.pdf
```