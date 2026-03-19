# Propuesta Técnica — Convocatoria Colombia Inteligente 2026

---

## Sección 1 — Identificación de las Entidades

### 1.1 Identificación de entidades participantes



### 1.2 Rol de la entidad ejecutora



---

## Sección 2 — Identificación del Proyecto

### 2.1 Título del proyecto

**Simulación Cuántica y Potenciales de Redes Neuronales para el Diseño Termodinámico de Materiales de Almacenamiento de Hidrógeno en Estado Sólido.**  

(Nota del estructurador: 147 caracteres. Cumple con la restricción de Minciencias de no superar los 250 caracteres, siendo directo, técnico y abarcando el alcance exacto).


### 2.2 Eje temático y línea temática

- **Eje Temático:** Ciencia y Tecnologías Cuánticas.
- **Línea Temática:** Energía Sostenible y Minerales Estratégicos - Simulación cuántica de materiales: Desarrollo de nuevos materiales para celdas solares, baterías, superconductores, semiconductores, termoeléctricos, entre otros

### 2.3 Justificación del eje y la línea

El almacenamiento eficiente y seguro de hidrógeno es el principal cuello de botella termodinámico para la transición hacia una economía de energía sostenible, operando como el análogo de alta densidad de las baterías químicas convencionales. Las metodologías empíricas de ensayo y error en la ciencia de materiales son insuficientes para superar la dicotomía topológica entre arquitecturas de dimensión cero (0D), como los metal carboranos, y superficies extendidas (2D), como los borofenos, requiriendo un escrutinio a escala atómica (Bora & Singh, 2013).

El presente proyecto se enmarca en la línea de _Simulación cuántica de materiales_ orientada a _Energía Sostenible_, al plantear un paradigma de simulación híbrida para el diseño in silico de nanomateriales absorbentes de hidrógeno. Históricamente, la literatura computacional ha dependido de funcionales GGA puros, subestimando la energía vibracional del punto cero (ZPE) y omitiendo factores críticos como la selectividad competitiva frente al oxígeno (Ahmad, Bora, & Singh, 2016; Singh, Sadrzadeh, & Yakobson, 2010). Para sortear estos sesgos metodológicos, este proyecto proone implementar simulaciones _ab initio_ de alto rendimiento (High-Throughput DFT) con funcionales híbridos y correcciones de dispersión acopladas, garantizando una fidelidad mecano-cuántica absoluta en la topología de la superficie de energía potencial.

No obstante, el costo computacional de la validación fonónica y la dinámica molecular a escalas macroscópicas (300 K) es inasumible mediante métodos tradicionales. Por consiguiente, el uso de las simulaciones cuánticas servirá como base fundamental para la construcción de datasets de altísima fidelidad, los cuales entrenarán Potenciales Interatómicos de Redes Neuronales (NNPs). Esta sinergia entre la mecánica-cuántica y el Deep Learning permitirá barrer el espacio químico de los clústeres dopados [^1] con metales de transición con una precisión de nivel ab initio pero a una fracción del costo temporal. De esta forma, el proyecto responde directamente al objetivo gubernamental de desarrollar nuevos materiales estratégicos, entregando una arquitectura validada computacionalmente para el almacenamiento de hidrógeno que asegure viabilidad termodinámica, cinética y resistencia a venenos ambientales, impulsando la soberanía energética de Colombia.

[^1]: Definición del cluster dopado en el contexto de simulación de química de estado sólido.



### 2.4 Duración del proyecto



### 2.5 Nivel de Madurez Tecnológica (TRL inicial y final)
- **TRL de inicio:** TRL 1 (Principios básicos observados y reportados): El proyecto parte de principios fundamentales documentados sobre la interacción de Kubas en nanoestructuras
-  **TRL de finalización:** TRL 3 (Función crítica, analítica y experimental, o prueba de concepto característica validada):  Al finalizar los 14 meses, se entregará una prueba de concepto analítica y computacional (Modelo NNP y dataset validado termodinámicamente) que demostrará la viabilidad del almacenamiento de hidrógeno en las matrices seleccionadas


### 2.6 Investigador principal



### 2.7 Equipo de trabajo técnico-científico



### 2.8 Equipo financiero-administrativo



### 2.9 Equipo con enfoque diferencial



### 2.10 Nombre de la tecnología



### 2.11 Estado de desarrollo de la tecnología/innovación



### 2.12 Monto solicitado y contrapartida



### 2.13 Grado de novedad y diferenciación



### 2.14 Aplicaciones y usuarios



### 2.15 Beneficios y ventajas para comunidades/organizaciones



### 2.16 Lugar de ejecución



### 2.17 Área OCDE



---

## Sección 3 — Generalidades y Antecedentes.

### 3.1 Resumen del proyecto



### 3.2 Descripción del problema, desafío u oportunidad

La consolidación de una economía basada en el hidrógeno verde en Colombia requiere superar un obstáculo termodinámico significativo: su almacenamiento seguro, compacto y energéticamente eficiente. Los enfoques macroscópicos convencionales, como la compresión a 700 bar o la licuefacción criogénica, imponen penalizaciones energéticas prohibitivas que limitan su viabilidad industrial y de movilidad. En consecuencia, el almacenamiento en estado sólido mediante fisisorción y quimisorción débil se erige como la alternativa óptima para cumplir con las densidades gravimétricas (_wt%_) y volumétricas exigidas por el Departamento de Energía de EE. UU. (DOE) (Xu et al., 2024).

Dentro del diseño de sustratos sólidos, los nanomateriales ricos en boro, tales como los borofenos, metalacarboranos y metaloboranos, representan la frontera del conocimiento. Históricamente, los materiales carbonosos decorados con metales de transición (TM) han fracasado debido a la alta energía cohesiva de los metales, lo que induce una aglomeración (clustering) severa y anula la capacidad de almacenamiento (Akbarzadeh, Vrinceanu, & Tymczak, 2015). El boro mitiga esta patología estructural de manera excepcional; gracias a su deficiencia electrónica, forma fuertes interacciones iónicas y redes multicéntricas con metales tempranos del bloque d (como Escandio y Titanio), previniendo la aglomeración (Huang et al., 2020; Scheifers, Zhang, & Fokwa, 2017).
En estos complejos, la transferencia de densidad electrónica desde los orbitales _d_ del metal hacia la caja de boro polariza al metal y habilita sus orbitales vacíos para aceptar electrones del enlace $\sigma$ de la molécula de $H_2$. Este fenómeno, que oscila entre la interacción de Kubas y los mecanismos tipo Niu-Rao-Jena, genera una energía de unión óptima (0.10 - 0.30 eV/ $H_2$), permitiendo una adsorción/desorción reversible a condiciones ambientales (Ray, Sahoo, & Sahu, 2018; Ray & Sahu, 2021)

A pesar del rotundo potencial de estas arquitecturas (con capacidades teóricas que superan el 11.5 wt% de $H_2$), el avance hacia niveles de madurez tecnológica aplicables (TRL 3+) se encuentra paralizado por falencias intrínsecas en la química computacional tradicional. Para evaluar con precisión la superficie de energía potencial (PES) de la interacción Boro-Metal-Hidrógeno, es imperativo el uso de la Teoría del Funcional de la Densidad (DFT) con rigurosas correcciones de dispersión de van der Waals (ej. DFT-D2/D3), evaluación de espín y correcciones por la Energía Vibracional del Punto Cero (ZPE) (Xu et al., 2024). Las simulaciones basadas en funcionales estándar (GGA) arrojan falsos positivos termodinámicos.
Aún más crítico resulta el análisis cinético. La literatura actual, como los estudios de Ray et al. (2018, 2021), se limita a simulaciones de dinámica molecular (ej. ADMP) a escalas de tiempo irrisorias (picosegundos) debido a su insostenible costo computacional. Validar la estabilidad estructural de un metalcarborano bajo ciclos de carga/descarga a 300 K o ante impurezas ambientales requiere dinámicas a escala de nanosegundos. Realizar este escrutinio para un espacio químico denso (múltiples combinaciones de metales y topologías de boro) utilizando cálculos ab initio por fuerza bruta es computacionalmente intratable (Akbarzadeh et al., 2015; Xu et al., 2024).

### 3.3 Propuesta de solución



### 3.4 Justificación

#### Necesidad de Transición Energética

El almacenamiento eficiente y compacto de hidrógeno representa el mayor cuello de botella termodinámico para viabilizar una economía basada en energías limpias. Las metodologías experimentales tradicionales de ensayo y error resultan insuficientes y altamente costosas para diseñar materiales absorbentes óptimos en estado sólido. En consecuencia, el escrutinio computacional a escala atómica es un factor imperativo para desarrollar alternativas que superen las limitaciones operativas de la compresión y la licuefacción a nivel industrial.

---

#### Alineación Estratégica Nacional

El proyecto responde directamente a los lineamientos de la convocatoria **ColombIA Inteligente 2026**, la cual exige la aplicación de Inteligencia Artificial y Tecnologías Cuánticas para solucionar problemáticas productivas. El diseño termodinámico de arquitecturas basadas en boro para la retención de hidrógeno se articula con las misiones de **reindustrialización y transición energética** del Plan Nacional de Desarrollo, fortaleciendo la capacidad científica nacional en sectores estratégicos. Esta aproximación técnica fomenta la consolidación de infraestructuras analíticas propias, disminuyendo la dependencia extranjera e impulsando la **soberanía digital y tecnológica** del país.

---

#### Viabilidad Técnica Optimizada

La validación termodinámica de configuraciones químicas complejas mediante simulación cuántica tradicional es inviable financieramente, debido a sus insostenibles requerimientos de supercómputo. La adopción de **Potenciales Interatómicos de Redes Neuronales (NNIPs)** soluciona esta barrera cinética al permitir simulaciones precisas de dinámica molecular a una fracción del costo y del tiempo convencionales. Esta innovación metodológica justifica la inversión del Estado, garantizando que el material propuesto alcance un nivel de madurez tecnológica validado **(TRL 3)** dentro de los plazos de la convocatoria.

---

#### Fortalecimiento Científico Regional

La pertinencia de la propuesta se fundamenta también en su capacidad para transferir conocimientos tecnológicos de frontera hacia el ecosistema académico y social colombiano. La inclusión obligatoria de jóvenes investigadores e innovadores y semilleros de investigación asegura que las competencias en programación avanzada e inteligencia artificial se arraiguen en el talento humano local, en cumplimiento del **Anexo 4 y Anexo 5** de la convocatoria. Esta estrategia de democratización tecnológica prepara a las comunidades para liderar los futuros desarrollos de la industria energética colombiana y garantiza la apropiación social del conocimiento generado.

---

#### Brecha Científica y Vacío de Conocimiento

La literatura internacional reporta avances fragmentados en el diseño de clústeres de boro para almacenamiento de hidrógeno, pero ninguna propuesta ha integrado simultáneamente modelos de aprendizaje profundo con dinámica molecular de alta resolución para optimizar la capacidad gravimétrica en condiciones operativas reales. Esta brecha científica constituye un **vacío de conocimiento** que justifica la inversión pública en investigación aplicada, ya que la solución no existe en el mercado nacional ni puede ser adquirida mediante transferencia tecnológica directa sin un proceso de adaptación investigativa previo.



### 3.5 Marco conceptual



### 3.6 Estado del arte



---

## Sección 4 — Componente técnico del proyecto

### 4.1 Objetivo general



### 4.2 Objetivos específicos



### 4.3 Metodología propuesta



### 4.4 Resultados esperados



### 4.5 Beneficios o productos esperados



### 4.6 Impacto ambiental



### 4.7 Impactos en comunidades/organizaciones



### 4.8 Estrategia de sostenibilidad



### 4.9 Estrategia de apropiación y uso de la tecnología



### 4.10 Propiedad intelectual



### 4.11 Riesgos del proyecto



### 4.12 Cronograma



### 4.13 Bibliografía



---

## Sección 5 — Componente de formación y fortalecimiento de capacidades

### 5.1 Estrategia de formación y fortalecimiento de capacidades



### 5.2 Población objetivo de formación



### 5.3 Metodología de formación



### 5.4 Plan de evaluación y seguimiento de la formación



### 5.5 Articulación de la formación con la sostenibilidad del proyecto



---

## Sección 6 — Componente Presupuestal

### 6.1 Presupuesto general del proyecto



### 6.2 Desagregación por rubros financiables



### 6.3 Justificación de cada rubro frente a la metodología



### 6.4 Presupuesto por vigencia fiscal



### 6.5 Contrapartida



### 6.6 Rubros obligatorios de apropiación social y formación



### 6.7 Rubros de talento humano de convocatoria

