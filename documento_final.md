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

#### 3.5.1 El hidrógeno como vector energético y el reto del almacenamiento

El hidrógeno molecular (H₂) es reconocido globalmente como un vector energético de alta densidad gravimétrica: la combustión completa de 1 kg de H₂ libera 1,43 × 10⁸ J, equivalente energético a 3 kg de gasolina, sin producir emisiones de CO₂ ni compuestos nitrogenados como subproductos (Xu et al., 2024). Sin embargo, la baja densidad volumétrica del H₂ en condiciones ambientales constituye el principal cuello de botella tecnológico para su adopción masiva. Actualmente existen tres tecnologías de almacenamiento de referencia: almacenamiento gaseoso a alta presión (35–70 MPa), almacenamiento líquido criogénico (20 K) y almacenamiento en estado sólido; las dos primeras presentan riesgos inherentes de fuga y elevadas pérdidas energéticas en el ciclo de compresión o licuefacción, mientras que el almacenamiento sólido permite condiciones de operación más seguras y compactas (Xu et al., 2024; Kalibek et al., 2024). El Departamento de Energía de los Estados Unidos (DOE, por sus siglas en inglés) ha fijado metas técnicas para vehículos de celda de combustible de 2,2 kWh/kg gravimétrico y 1,7 kWh/L volumétrico, con presión de operación entre 5 y 12 bar y un mínimo de 1.500 ciclos de carga-descarga (Xu et al., 2024). Estas metas constituyen el referente cuantitativo para el diseño racional de nuevos materiales de almacenamiento sólido de H₂ en el contexto de la presente propuesta.

#### 3.5.2 Mecanismos fundamentales del almacenamiento en estado sólido

El almacenamiento de H₂ en estado sólido se realiza por dos mecanismos físico-químicos distintos: fisisorción y quimisorción. En la fisisorción, las moléculas de H₂ se adsorben sobre la superficie del material mediante interacciones de tipo van der Waals, con energías de enlace en el rango de 1–10 kJ/mol; la ventaja de este mecanismo es la cinética rápida y la total reversibilidad sin requerimiento de activación, pero la baja energía de interacción obliga a operar a temperaturas criogénicas (77 K) para alcanzar capacidades útiles (Kalibek et al., 2024). En la quimisorción, el hidrógeno atómico se incorpora a la red cristalina del material formando hidruros metálicos reversibles; este proceso permite almacenar H₂ a alta densidad volumétrica (hasta 130 g/L) y a presiones moderadas, con la ventaja de una mayor seguridad operativa (Kalibek et al., 2024). Para que un material de almacenamiento sólido sea práctico, la energía de adsorción óptima debe situarse en la denominada "ventana de reversibilidad": aproximadamente 0,2–0,6 eV por molécula de H₂ en fisisorción fortalecida, o entre 28 y 48 kJ/mol de H₂ en quimisorción moderada; fuera de estos rangos, el material o no retiene el hidrógeno a temperatura ambiente o lo libera en condiciones extremas de temperatura (Xu et al., 2024; Kalibek et al., 2024).

#### 3.5.3 Nanomateriales basados en boro: arquitectura electrónica y principios de adsorción

Los nanomateriales basados en boro (B-based) —incluyendo borofenos, hojas de boro, boruros metálicos y metalacarboranos— representan una categoría de materiales con propiedades electrónicas únicas para el almacenamiento físico de H₂. El boro es un elemento deficiente en electrones que forma estructuras multicéntricas estabilizadas por deslocalización electrónica, lo que le permite actuar como andamiaje para dispersar metales dopantes de forma uniforme, evitando el fenómeno de *clustering* o agregación metálica que destruye los sitios activos de adsorción (Xu et al., 2024). En estos sistemas, la interacción con el H₂ se basa en el mecanismo de Kubas, donde el enlace σ de la molécula de H₂ dona densidad electrónica hacia los orbitales d vacíos o semi-ocupados del metal dopante, mientras ocurre simultáneamente retrodonación del metal hacia el orbital antienlazante de H₂; el resultado es una energía de adsorción intermedia entre fisisorción pura y quimisorción, denominada adsorción de tipo Kubas, que cae dentro de la ventana óptima de reversibilidad (Xu et al., 2024). El análisis de carga de Bader confirma en estos sistemas la polarización electrostática de la molécula de H₂ adsorbida, lo que incrementa la capacidad de adsorción por sitio metálico, permitiendo que materiales como el Ca-B₄₀ o el borofeno decorado con Ti alcancen densidades gravimétricas teóricas superiores al 8–15 % en peso (Xu et al., 2024).

#### 3.5.4 Teoría del Funcional de la Densidad (DFT) como herramienta de diseño racional

La Teoría del Funcional de la Densidad (DFT, del inglés *Density Functional Theory*) es el método computacional de referencia para el diseño racional de materiales de almacenamiento de H₂, dado que permite calcular estructuras electrónicas, propiedades termodinámicas, mecanismos de reacción y propiedades fonónicas sin recurrir al costoso proceso experimental de prueba y error (Xu et al., 2024; Kalibek et al., 2024). Los dos indicadores fundamentales derivados de los cálculos DFT para materiales de almacenamiento físico son la energía de enlace del dopante con el sustrato (E_b) y la energía de adsorción del H₂ (E_ad):

$$E_b = E_{\text{adsorbente}} - E_{\text{dopante}} - E_{\text{sustrato}}$$

$$E_{ad} = \frac{E_{\text{sistema}} - E_{\text{adsorbente}} - n \cdot E_{H_2}}{n}$$

donde valores de E_b superiores a la energía cohesiva del metal garantizan que el dopante no se agrega, y valores de E_ad en el rango 0,2–0,6 eV corresponden a condiciones óptimas de reversibilidad (Xu et al., 2024). Para capturar con precisión las interacciones de largo alcance relevantes en la adsorción de H₂ sobre nanoestructuras de boro, es indispensable incluir correcciones de dispersión de van der Waals (DFT-D3 o vdW-DF), correcciones de energía vibracional del punto cero (ZPE) y efectos fonónicos para acceder a energías libres de Gibbs en condiciones operativas, aspectos que los cálculos DFT estándar subestiman sistemáticamente (Xu et al., 2024).

#### 3.5.5 Aprendizaje automático y potenciales interatómicos de redes neuronales

El costo computacional de los cálculos DFT escala con el cubo del número de electrones del sistema, lo que los hace prohibitivos para la exploración de miles de estructuras candidatas o para simulaciones de dinámica molecular en escalas de nanosegundos. Para resolver esta limitación, en la última década han emergido los Potenciales Interatómicos de Redes Neuronales (NNPs, del inglés *Neural Network Potentials*), que se entrenan sobre bases de datos DFT y reproducen energías y fuerzas ab initio con un costo computacional órdenes de magnitud menor, habilitando dinámica molecular extendida (Batra & Sankaranarayanan, 2020; Zhang et al., 2020). Los modelos de grafos atómicos, como las *Crystal Graph Convolutional Neural Networks* (CGCNN) y las *Atomistic Line Graph Neural Networks* (ALIGNN), representan los materiales como grafos donde los nodos son átomos y las aristas codifican distancias y ángulos de enlace, permitiendo predecir propiedades energéticas, mecánicas y fonónicas con precisión cercana a DFT (Xu et al., 2024). Los modelos equivariantes de última generación con representaciones de largo alcance y los NNPs escalables para dinámica molecular paralela representan el estado más avanzado de esta metodología, capaz de manejar sistemas con miles de átomos y escalas de tiempo de nanosegundos, cerrando así la brecha entre la fidelidad cuántica y la escala temporal de los fenómenos de interés experimental (Batra & Sankaranarayanan, 2020; Zhang et al., 2020).


### 3.6 Estado del arte

#### 3.6.1 Panorama global del almacenamiento sólido de H₂: tendencias y retos vigentes

La investigación en almacenamiento sólido de H₂ ha experimentado un crecimiento sostenido en las últimas dos décadas, con la producción bibliográfica de los últimos cinco años dominada por los marcos metal-orgánicos (MOF, del inglés *Metal-Organic Frameworks*), los marcos orgánicos covalentes (COF), los hidruros metálicos y los materiales nanoestructurados de carbono (Kalibek et al., 2024; Xu et al., 2024). Los MOF y COF destacan por su alta área superficial y porosidad ajustable, con capacidades de hasta 6,7 % en peso en condiciones criogénicas (77 K), pero su limitación crítica es la baja energía de interacción van der Waals con el H₂ (2,2–5,2 kJ/mol), que impide la adsorción significativa a temperatura ambiente (Kalibek et al., 2024). Los hidruros metálicos, como MgH₂ y NaAlH₄, ofrecen altas densidades gravimétricas (7,7 % y 7,4 % en peso, respectivamente) pero requieren temperaturas de desorción superiores a 300 °C, lo que los hace inviables para aplicaciones móviles directas (Kalibek et al., 2024). Las revisiones sistemáticas más recientes concluyen de manera consistente que ningún material individual cumple simultáneamente las metas del DOE de capacidad, temperatura de operación cercana a ambiente y reversibilidad ciclable, lo que constituye el reto central no resuelto que justifica la búsqueda de nuevas arquitecturas de materiales (Xu et al., 2024).

#### 3.6.2 Nanomateriales basados en boro: investigaciones previas y resultados más relevantes

Dentro del campo de los materiales de almacenamiento físico de H₂, los nanomateriales basados en boro han emergido como una de las líneas más prometedoras durante los últimos cinco años. Los estudios de primeros principios sobre el fulereno de boro B₄₀ decorado con Ca muestran que seis átomos de Ca se distribuyen de forma estable sobre la superficie del fulereno —con energías de enlace superiores a la energía cohesiva del Ca, garantizando la ausencia de *clustering*— y que cada sitio Ca puede adsorber hasta cinco moléculas de H₂ con una energía de adsorción de 0,177 eV, con una capacidad gravimétrica total de 8,11 % en peso confirmada mediante simulación de dinámica molecular a 300 K (Xu et al., 2024). Los borofenos decorados con Ti alcanzan densidades gravimétricas teóricas de hasta 15,07 % en peso con energías de adsorción en el rango óptimo, gracias a la alta estabilidad del enlace Ti-borofeno (E_b = 5,49 eV) que previene la migración del dopante (Xu et al., 2024). Los boruros mixtos tipo B-C-N también han mostrado resultados relevantes: el análisis DFT de monocapas de B₃CN₄ sin dopaje metálico revela la adsorción espontánea de seis moléculas de H₂ con energías en el rango 0,214–0,474 eV, lo que sugiere que la química del boro por sí sola puede modular la adsorción en ausencia de metales (Xu et al., 2024).

#### 3.6.3 Borohidruros metálicos complejos: diversidad estructural y limitaciones en la reversibilidad

Los borohidruros metálicos complejos de la forma MBH₄ (donde M = Li, Na, Mg, Ca, Y, Sc) representan la subclase de mayor densidad gravimétrica teórica entre los materiales químicos de almacenamiento: LiBH₄ almacena 18,4 % en peso de H₂ y NaBH₄ un 10,6 % en peso (Comanescu, 2022; Kalibek et al., 2024). Sin embargo, la alta estabilidad termodinámica de estos compuestos y la lenta cinética de desorción constituyen sus limitaciones operativas más críticas: la descomposición de LiBH₄ requiere temperaturas superiores a 400 °C y la rehidrogenación exige condiciones extremas de presión (70–350 bar) y temperatura (600 °C), lo que hace inviable su uso directo en ciclos reversibles de carga y descarga a temperatura ambiente (Comanescu, 2022). Las estrategias investigadas para superar estas limitaciones incluyen la nanoconfinación en soportes de carbono mesoporoso (CMK-3, SBA-15), donde se ha demostrado que la reducción del tamaño de poro de 24 nm a 13 nm disminuye la temperatura de desorción en ~111 °C y acelera la cinética de desorción en un factor de 10⁶ (Comanescu, 2022), y la formación de sistemas reactivos compositos como el 2LiBH₄-MgH₂, con entalpía de desorción reducida a 45,7 kJ/mol de H₂ y reversibilidad parcial a 315–450 °C (Comanescu, 2022). A pesar de estos avances, la reversibilidad completa de los borohidruros bajo condiciones prácticas de temperatura y presión sigue siendo un problema abierto, y los mecanismos intermedios de reacción —especialmente la formación de especies B₁₂H₁₂²⁻ como productos secundarios estables— continúan limitando la capacidad de recarga (Comanescu, 2022).

#### 3.6.4 Métodos computacionales: DFT, aprendizaje automático y NNPs para materiales de hidrógeno

El uso de DFT para el diseño de materiales de almacenamiento de H₂ ha madurado hasta convertirse en la metodología estándar de preselección de candidatos: en los últimos cinco años se han publicado centenares de estudios que emplean DFT para calcular energías de adsorción, estructuras electrónicas, propiedades fonónicas y mecanismos de desorción en una variedad de materiales que abarca desde grafenos dopados hasta nanoestructuras de boro y MXenos (Xu et al., 2024). La integración de aprendizaje automático (ML) con DFT ha acelerado significativamente este proceso: modelos como redes neuronales artificiales, máquinas de vectores de soporte y bosques aleatorios han sido entrenados para predecir capacidades de almacenamiento, modelar cinética y clasificar materiales, reduciendo el espacio de búsqueda experimental de forma sustancial (Xu et al., 2024). Los NNPs basados en aprendizaje profundo han demostrado capacidad para reproducir superficies de energía potencial ab initio con una fracción del costo computacional: la plataforma DP-GEN de aprendizaje concurrente (Zhang et al., 2020) permite construir NNPs de forma sistemática para materiales complejos, habilitando dinámicas moleculares en escalas de tiempo inaccesibles para métodos ab initio tradicionales (Zhang et al., 2020). Los modelos de grafos equivariantes con interacciones de largo alcance y los algoritmos de MD paralela escalable representan los avances más recientes en la infraestructura computacional que hace factible la exploración a gran escala de materiales complejos como las nanoestructuras ricas en boro (Batra & Sankaranarayanan, 2020; Zhang et al., 2020).

#### 3.6.5 Vacío del conocimiento: ausencia de un flujo integrado para nanoestructuras ricas en boro

La revisión sistemática de la literatura disponible permite identificar con precisión el vacío de conocimiento que justifica la novedad del proyecto propuesto. No existe actualmente un flujo de trabajo integrado que combine: (i) cálculos DFT de alta fidelidad con correcciones de dispersión, ZPE y contribuciones fonónicas para arquitecturas basadas en boro (metalacarboranos, borofenos, hojas de boro decoradas), (ii) modelos de grafos equivariantes del tipo ALIGNN o similares acoplados a estrategias de aprendizaje activo para explorar adaptativamente el espacio químico de estas arquitecturas, y (iii) NNPs especializados en la dinámica a temperatura cercana a 300 K, la estabilidad ciclable y la selectividad frente a impurezas gaseosas en escalas de nanosegundos (Xu et al., 2024; Batra & Sankaranarayanan, 2020; Zhang et al., 2020). En el contexto colombiano, no se identifican en la Plataforma ScienTI ni en bases de datos internacionales proyectos anteriores que integren explícitamente nanoestructuras ricas en boro, redes neuronales de grafos equivariantes y NNPs para el diseño de materiales de almacenamiento de H₂ alineados con la transición energética del país, lo que confirma el carácter novedoso y diferenciado de la propuesta frente al estado de la técnica nacional e internacional (Xu et al., 2024). La única manera de avanzar hacia materiales candidatos que cumplan simultáneamente las metas del DOE bajo condiciones operativas realistas es precisamente a través de la metodología multiescala computacional propuesta, cuya arquitectura no tiene antecedente directo en el mercado ni en la literatura revisada (Xu et al., 2024; Zhang et al., 2020).

**Referencias (secciones 3.5 y 3.6)**

> Batra, R., & Sankaranarayanan, S. (2020). Machine learning for multi-fidelity scale bridging and dynamical simulations of materials. *Journal of Physics: Materials, 3*(3), 031002. https://doi.org/10.1088/2515-7639/ab8c2d

> Comanescu, C. (2022). Complex metal borohydrides: From laboratory oddities to prime candidates in energy storage. *Materials, 15*(7), 2286. https://doi.org/10.3390/ma15072286

> Kalibek, M. R., Ospanova, A. D., Suleimenova, B., Soltan, R., Orazbek, T., Makhmet, A. M., Rafikova, K. S., & Nuraje, N. (2024). Solid-state hydrogen storage materials. *Discover Nano, 19*, 195. https://doi.org/10.1186/s11671-024-04137-y

> Xu, Y., Zhou, Y., Li, C., Dong, S., Liu, H., Yang, W., Li, Y., Jiang, H., Ding, Z., Li, H., & Shaw, L. L. (2024). Unraveling the potential of solid-state hydrogen storage materials: Insights from first principle calculations. *Fuel, 373*, 132340. https://doi.org/10.1016/j.fuel.2024.132340

> Zhang, L., Wang, H., Car, R., & E, W. (2020). Phase diagram of a deep potential water model. *Physical Review Letters, 126*(23), 236001. https://doi.org/10.1103/PhysRevLett.126.236001

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

