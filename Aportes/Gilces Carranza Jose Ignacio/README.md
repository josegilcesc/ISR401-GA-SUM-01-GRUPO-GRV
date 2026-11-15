# Aporte Individual — Práctica Experimental Unidad I (GA-PE-U1)

## 1. Datos del Integrante
* **Apellidos y Nombres:** Gilces Carranza José Ignacio
* **Cédula de Ciudadanía:** 1251059240
* **Correo Institucional:** `jgilcesc3@uteq.edu.ec`
* **Carrera / Nivel:** Ingeniería de Software (Rediseño) — 4to Nivel "B"
* **Asignatura:** Ingeniería de Requerimientos (ISR-401)
* **Docente:** Ing. Gleiston Cicerón Guerrero Ulloa, Ph.D.
* **Rol Asignado en el Equipo:** Analista Líder e Investigador B (Secciones 2.3 – 2.4)

---

## 2. Resumen de Aportes y Responsabilidades Cumplidas por Avance

### Avance 1 (Estructura Base y Selección del PFC)
* Configuración inicial de la plantilla académica `IEEEtran` en LaTeX (`main.tex`) y definición de paquetes tipográficos.
* Definición y asignación de roles del equipo (Sección 0 / Paso 1a) y registro nominal oficial con números de cédula y correos institucionales UTEQ (Paso 1b).
* Redacción de la descripción del sistema del Proyecto Fin de Curso (PFC): *Plataforma de Ventas con Módulo de Recomendación basado en Inteligencia Artificial para establecimientos de suministros eléctricos en Quevedo* (Paso 1c).

### Avance 2 (Fundamento Teórico 2.3–2.4 y Especificación de Requisitos C1/C2)
* **Sección 2.3 (Taxonomía Detallada de Requisitos):** Desarrollo investigativo de requisitos de interfaz (UI, HW, SW, COM), rendimiento, restricciones operativas y conformidad legal, así como la sintaxis estructurada EARS (*Easy Approach to Requirements Syntax*) y priorización MoSCoW.
* **Sección 2.4 (Propiedades de Calidad según IEEE 29148):** Fundamentación de las 9 propiedades individuales de calidad (cláusula 5.2.5) y las 5 propiedades del conjunto de requisitos en la SRS (cláusula 5.2.6), incluyendo explicación propia y ejemplos aplicados al PFC.
* **Paso 4 y Criterio C1 (Catálogo de 15 Requisitos del PFC):** Especificación formal de los 15 requisitos únicos del sistema (`REQ-01` a `REQ-15`) aplicando sintaxis EARS, cuantificación de atributos de calidad bajo ISO/IEC 25010:2023 y priorización MoSCoW.
* **Criterio C2 (Matriz de Evaluación de Propiedades IEEE 29148):** Auditoría individual verificable de los 15 requisitos contra los criterios de necesidad, apropiado al nivel, inambigüedad, completitud, singularidad, verificabilidad y trazabilidad.

### Avance 3 y Cierre (Auditoría de Abstracción Tecnológica, Maquetación Multipágina y Conclusiones)
* **Corrección y Depuración de Tecnologías de Implementación (Rol de Analista Líder):** En cumplimiento estricto de las directrices de la cátedra y de la propiedad de calidad **"Apropiado al nivel / Libre de implementación"** estipulada en la cláusula 5.2.5 de la norma **ISO/IEC/IEEE 29148:2018**, se realizó una auditoría transversal de todo el documento para eliminar referencias prematuras a tecnologías de diseño, motores de bases de datos, lenguajes o marcas específicas (como *PostgreSQL, Django, Python, Docker, JWT, bcrypt, Redis o proveedores específicos de API*), sustituyéndolas por especificaciones puras del dominio del problema (*repositorio central de datos, catálogo local con existencias disponibles, servicio externo de inferencia de IA, credenciales de sesión por turno y cifrado irreversible*).
* **Corrección de Maquetación de Tablas Extensas (`ltablex`):** Se refactorizaron las tablas extensas del informe (Catálogo de 15 Requisitos, Matriz de Calidad C2 y Ocho Perspectivas de Pohl) integrando el paquete `ltablex` con `\keepXColumns` y encabezados de continuación automáticos (`\endfirsthead` / `\endhead`) para evitar cortes abruptos entre páginas.
* **Unificación Nominal del Sistema:** Se estandarizó en todo el informe el nombre oficial del sistema como *"Plataforma de Ventas con Módulo de Recomendación basado en Inteligencia Artificial"* (`The Sales Platform shall...`).
* Redacción de las **Conclusiones Individuales 1 y 2** (>80 palabras c/u) bajo estructura tripartita: *(1) Afirmación, (2) Evidencia normativa con cita IEEE y (3) Implicación para el PFC*.
* Redacción de la **Declaración Explícita de Uso Ético y Validación Crítica de IA** (Paso 6d) y compilación del entregable final `PE1_U1_GILCES_VELEZ_ROBINSON.pdf`.

---

## 3. Contenido de esta Subcarpeta
* `aporte_gilces.tex` / `aporte_gilces_avance3.tex`: Código fuente en LaTeX con los desarrollos teóricos (2.3–2.4), tablas de requisitos (C1/C2) libres de tecnologías y conclusiones elaboradas por el integrante.
* `aporte_gilces.bib`: Base de datos bibliográfica BibLaTeX con las fuentes primarias citadas en el aporte.
* `figura/`: Respaldo de recursos gráficos empleados en la validación documental.