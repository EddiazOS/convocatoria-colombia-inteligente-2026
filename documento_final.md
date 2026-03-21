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

El presente proyecto se enmarca en la línea de _Simulación cuántica de materiales_ orientada a _Energía Sostenible_, al plantear un paradigma de simulación híbrida para el diseño in silico de nanomateriales absorbentes de hidrógeno. Históricamente, la literatura computacional ha dependido de funcionales GGA puros, subestimando la energía vibracional del punto cero (ZPE) y omitiendo factores críticos como la selectividad competitiva frente al oxígeno (Ahmad, Bora, & Singh, 2016; Singh, Sadrzadeh, & Yakobson, 2010). Para sortear estos sesgos metodológicos, este proyecto propone implementar simulaciones _ab initio_ de alto rendimiento (High-Throughput DFT) con funcionales híbridos y correcciones de dispersión acopladas, garantizando una fidelidad mecano-cuántica absoluta en la topología de la superficie de energía potencial.

No obstante, el costo computacional de la validación fonónica y la dinámica molecular a escalas macroscópicas (300 K) es inasumible mediante métodos tradicionales. Por consiguiente, el uso de las simulaciones cuánticas servirá como base fundamental para la construcción de datasets de altísima fidelidad, los cuales entrenarán Potenciales Interatómicos de Redes Neuronales (NNIPs). Esta sinergia entre la mecánica-cuántica y el Deep Learning permitirá barrer el espacio químico de los clústeres dopados [^1] con metales de transición con una precisión de nivel ab initio pero a una fracción del costo temporal. De esta forma, el proyecto responde directamente al objetivo gubernamental de desarrollar nuevos materiales estratégicos, entregando una arquitectura validada computacionalmente para el almacenamiento de hidrógeno que asegure viabilidad termodinámica, cinética y resistencia a venenos ambientales, impulsando la soberanía energética de Colombia.

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

La consolidación de una economía basada en el hidrógeno verde en Colombia requiere superar un obstáculo termodinámico significativo: su almacenamiento seguro, compacto y energéticamente eficiente. Los enfoques macroscópicos convencionales, como la compresión a 700 bar o la licuefacción criogénica, imponen penalizaciones energéticas prohibitivas que limitan su viabilidad industrial y de movilidad. En consecuencia, el almacenamiento en estado sólido mediante fisisorción y quimisorción débil se erige como la alternativa óptima para cumplir con las densidades gravimétricas (_wt%_) y volumétricas exigidas por el Departamento de Energía de EE. UU. (DOE 2020).

Dentro del diseño de sustratos sólidos, los nanomateriales ricos en boro, tales como los borofenos, metalacarboranos y metaloboranos, representan la frontera del conocimiento. Históricamente, los materiales carbonosos decorados con metales de transición (TM) han fracasado debido a la alta energía cohesiva de los metales, lo que induce una aglomeración (clustering) severa y anula la capacidad de almacenamiento (Akbarzadeh, Vrinceanu, & Tymczak, 2015). El boro mitiga esta patología estructural de manera excepcional; gracias a su deficiencia electrónica, forma fuertes interacciones iónicas y redes multicéntricas con metales tempranos del bloque d (como Escandio y Titanio), previniendo la aglomeración (Huang et al., 2020; Scheifers, Zhang, & Fokwa, 2017).
En estos complejos, la transferencia de densidad electrónica desde los orbitales _d_ del metal hacia la caja de boro polariza al metal y habilita sus orbitales vacíos para aceptar electrones del enlace $\sigma$ de la molécula de $H_2$. Este fenómeno, que oscila entre la interacción de Kubas y los mecanismos tipo Niu-Rao-Jena, genera una energía de unión óptima (0.10 - 0.30 eV/ $H_2$), permitiendo una adsorción/desorción reversible a condiciones ambientales (Ray, Sahoo & Sahu, 2021)

A pesar del rotundo potencial de estas arquitecturas (con capacidades teóricas que superan el 11.5 wt% de $H_2$), el avance hacia niveles de madurez tecnológica aplicables (TRL 3+) se encuentra paralizado por falencias intrínsecas en la química computacional tradicional. Para evaluar con precisión la superficie de energía potencial (PES) de la interacción Boro-Metal-Hidrógeno, es imperativo el uso de la Teoría del Funcional de la Densidad (DFT) con rigurosas correcciones de dispersión de van der Waals (ej. DFT-D2/D3), evaluación de espín y correcciones por la Energía Vibracional del Punto Cero (ZPE) (Xu et al., 2024). Las simulaciones basadas en funcionales estándar (GGA) arrojan falsos positivos termodinámicos.
Aún más crítico resulta el análisis cinético. La literatura actual, como los estudios de Ray et al. (2018, 2021), se limita a simulaciones de dinámica molecular (ej. ADMP) a escalas de tiempo irrisorias (picosegundos) debido a su insostenible costo computacional. Validar la estabilidad estructural de un metalcarborano bajo ciclos de carga/descarga a 300 K o ante impurezas ambientales requiere dinámicas a escala de nanosegundos. Realizar este escrutinio para un espacio químico denso (múltiples combinaciones de metales y topologías de boro) utilizando cálculos ab initio por fuerza bruta es computacionalmente intratable (Akbarzadeh et al., 2015; Xu et al., 2024).

### 3.3 Propuesta de solución

Este proyecto propone el diseño racional in silico de nanomateriales ricos en boro para el almacenamiento sólido y reversible de H₂, mediante un flujo de trabajo computacional integrado de tres etapas secuenciales y mutuamente dependientes: (i) simulación cuántica de alta fidelidad basada en DFT, (ii) aceleración del muestreo del espacio químico mediante modelos de grafos atómicos con aprendizaje activo, y (iii) validación dinámica mediante Potenciales Interatómicos de Redes Neuronales (NNIPs, del inglés *Neural Network Potentials*). Este flujo resuelve de forma estructurada y progresiva las dos barreras críticas identificadas en el estado del arte: la insuficiencia termodinámica de los funcionales estándar y la inviabilidad computacional de la dinámica molecular ab initio a escala de nanosegundos (Xu et al., 2024; Kalibek et al., 2024).

En la primera etapa, se ejecutarán cálculos DFT de alta fidelidad sobre un conjunto seleccionado de arquitecturas candidatas: metalacarboranos dopados con metales de transición tempranos (Sc, Ti, V), borofenos funcionalizados y hojas de boro planas decoradas. Los cálculos emplearán funcionales de intercambio-correlación del tipo GGA con correcciones de dispersión de van der Waals (DFT-D3), evaluación de estado de espín no restringido (UKS) y cálculos fonónicos para estimar energías vibracionales del punto cero (ZPE) y energías libres de Gibbs a temperatura operativa (Xu et al., 2024). Este nivel de rigor es indispensable para discriminar falsos positivos termodinámicos y garantizar que los candidatos preseleccionados presenten energías de adsorción de H₂ en la ventana de reversibilidad (0,2–0,6 eV/molécula) y energías de enlace del dopante superiores a la energía cohesiva del metal libre (Kalibek et al., 2024). Los datos generados en esta etapa constituirán la base de datos de entrenamiento de alta fidelidad para las etapas posteriores.

En la segunda etapa, los datos DFT se emplearán para entrenar modelos de grafos atómicos, específicamente arquitecturas del tipo Crystal Graph Convolutional Neural Networks (CGCNN) y Atomistic Line Graph Neural Networks (ALIGNN), que representan las estructuras como grafos donde los nodos son átomos y las aristas codifican distancias interatómicas y ángulos de enlace (Osman et al., 2024). Estos modelos se integrarán en un bucle de aprendizaje activo que identifica iterativamente las regiones del espacio químico con mayor incertidumbre predictiva y prioriza nuevos cálculos DFT en esas zonas, optimizando el tamaño de la base de datos y acelerando la convergencia del modelo. Este enfoque ha demostrado reducir hasta en un orden de magnitud la cantidad de cálculos ab initio necesarios para explorar espacios químicos amplios en materiales complejos (Xu et al., 2024).

En la tercera etapa, la base de datos DFT consolidada se utiliza para entrenar NNIPs mediante la plataforma de aprendizaje concurrente DP-GEN (*Deep Potential Generator*), que permite construir potenciales interatómicos con precisión ab initio y un costo computacional equivalente al de un campo de fuerzas clásico (Zhang et al., 2020). Los NNIPs entrenados habilitan simulaciones de dinámica molecular en el ensamble canónico (NVT) a 300 K y a presiones de interés operativo, extendidas a escalas de nanosegundos, lo que permite evaluar la estabilidad estructural real de los candidatos bajo ciclos de carga y descarga de H₂, la tolerancia a impurezas gaseosas (O₂, H₂O) y la cinética de adsorción/desorción bajo condiciones prácticas. Este nivel de validación es inalcanzable mediante DFT directo y no existe en la literatura para arquitecturas ricas en boro (Xu et al., 2024; Batra & Sankaranarayanan, 2020).

El producto final del flujo integrado es un conjunto de arquitecturas de nanomateriales ricos en boro computacionalmente validadas en termodinámica, estructura electrónica y dinámica molecular, que cumplan simultáneamente las metas del DOE de capacidad gravimétrica (≥ 5,5 wt%), reversibilidad (≥ 1.500 ciclos) y temperatura de operación cercana a ambiente. Este conjunto de datos y modelos constituye una prueba de concepto analítica y computacional de nivel TRL 3, lista para orientar etapas futuras de síntesis experimental y escalamiento tecnológico en el ecosistema científico colombiano.

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

La descarbonización de la economía global exige reemplazar los combustibles fósiles por fuentes de energía limpias y almacenables. El hidrógeno se consolida como vector energético de alta prioridad dado que puede producirse mediante electrólisis del agua impulsada con energía renovable —denominado hidrógeno verde— y puede emplearse como amortiguador entre la generación intermitente (solar y eólica) y la demanda continua (Abdin et al., 2021). Su densidad gravimétrica de energía alcanza 119,9 MJ/kg, aproximadamente tres veces la de la gasolina, y su única emisión en el punto de uso es agua (Mekonnin et al., 2025). Las fuentes renovables son un componente clave de la descarbonización, pero están disponibles de forma intermitente, de manera que el hidrógeno puede actuar como medio de almacenamiento de electricidad y así equilibrar la producción y la demanda energética (Abdin et al., 2021). Para que esta promesa se materialice, es indispensable desarrollar cadenas de valor que incluyan soluciones de almacenamiento seguras, económicas y eficientes.

El hidrógeno presenta una densidad volumétrica de tan solo 10,7 MJ/m³ en condiciones estándar, lo que convierte al almacenamiento en su principal cuello de botella tecnológico (Mekonnin et al., 2025). Los métodos físicos dominantes —gas comprimido a 35–70 MPa y líquido criogénico a 20 K— implican altos costos de contención, riesgos de seguridad y pérdidas por evaporación; en términos de costo de capital, el almacenamiento de hidrógeno líquido supera en más del doble al almacenamiento gaseoso (Abdin et al., 2021). Los portadores orgánicos líquidos (LOHCs, del inglés *Liquid Organic Hydrogen Carriers*) han emergido como alternativas de interés para el almacenamiento estacionario a gran escala por su compatibilidad con la infraestructura existente de combustibles líquidos, aunque sus procesos de deshidrogenación requieren temperaturas superiores a 300 °C y son energéticamente intensivos (Le et al., 2024). En síntesis, actualmente ningún método de almacenamiento es universalmente eficiente para todos los sectores, lo que justifica la búsqueda de nuevas arquitecturas de materiales en estado sólido. El Departamento de Energía de los Estados Unidos (DOE) ha fijado metas técnicas de referencia de 2,2 kWh/kg gravimétrico y 1,7 kWh/L volumétrico para sistemas de almacenamiento en movilidad, con presión de operación entre 5 y 12 bar y un mínimo de 1.500 ciclos de carga-descarga (Xu et al., 2024).

#### 3.5.2 Mecanismos fundamentales del almacenamiento en estado sólido

El almacenamiento de H₂ en estado sólido se fundamenta en la interacción de moléculas de H₂ con una matriz sólida, ya sea por fisisorción o quimisorción. En la fisisorción, las moléculas de H₂ se adsorben sobre la superficie del material mediante interacciones de tipo van der Waals con energías de enlace en el rango de 1–10 kJ/mol; la ventaja de este mecanismo es la cinética rápida y la total reversibilidad sin requerimiento de activación, pero la baja energía de interacción obliga a operar a temperaturas criogénicas (77 K) para alcanzar capacidades útiles (Kalibek et al., 2024). En la quimisorción, el hidrógeno atómico se incorpora a la red cristalina del material formando hidruros metálicos reversibles; este proceso permite almacenar H₂ a alta densidad volumétrica (hasta 130 g/L) y a presiones moderadas, con la ventaja de una mayor seguridad operativa, aunque los procesos de desorción requieren temperaturas superiores a 300 °C (Kalibek et al., 2024). El potencial de Lennard-Jones es la herramienta conceptual que cuantifica la interacción entre moléculas de H₂ y la superficie del adsorbente, modelando la transición entre atracción a distancias moderadas y repulsión a distancias cortas (Kalibek et al., 2024). Para que un material de almacenamiento sólido sea práctico, la energía de adsorción óptima debe situarse en la denominada "ventana de reversibilidad": aproximadamente 0,2–0,6 eV por molécula de H₂ en fisisorción fortalecida, o entre 28 y 48 kJ/mol de H₂ en quimisorción moderada; fuera de estos rangos, el material o no retiene el hidrógeno a temperatura ambiente o lo libera en condiciones extremas de temperatura (Xu et al., 2024; Kalibek et al., 2024).

#### 3.5.3 Nanomateriales basados en boro: arquitectura electrónica y principios de adsorción

Los nanomateriales ricos en boro —incluyendo borofenos, hojas de boro, boruros metálicos y metalacarboranos— representan una familia de materiales con propiedades electrónicas singulares para el almacenamiento físico de H₂. El boro, siendo un elemento deficiente en electrones, forma estructuras multicéntricas estabilizadas por deslocalización electrónica, lo que le permite actuar como andamiaje para dispersar metales dopantes de forma uniforme e inhibir el fenómeno de *clustering* o agregación metálica (Xu et al., 2024). Osman et al. (2024) reportan que cuando el borofeno es dopado con iones metálicos de litio, su capacidad gravimétrica de hidrógeno alcanza el 13,96 % en peso, y cuando es dopado con sodio alcanza el 10,39 % en peso, valores que superan ampliamente las metas del DOE. En el caso de los metalacarboranos dopados con metales de transición tempranos como el escandio, los átomos metálicos se incorporan como vértices estructurales de la jaula carboránica, suprimiendo prácticamente el *clustering* y habilitando una adsorción reversible de H₂ con capacidades teóricas superiores al 8 % en peso (Xu et al., 2024).

El mecanismo central que gobierna la adsorción de H₂ en estos materiales es la interacción de Kubas: la molécula de H₂ se coordina al metal sin disociarse, mediante donación del enlace σ del H₂ hacia el orbital d vacío del metal y retrodonación del metal hacia el orbital antienlazante σ* del H₂ (Xu et al., 2024). Esta interacción produce energías de unión intermedias que garantizan la reversibilidad del proceso a temperatura ambiente, distinguiéndose de la fisisorción pura —demasiado débil— y de la disociación oxidativa —que dificulta la desorción— (Osman et al., 2024). Yang et al. (2019) demostraron que nanotubos de carbono de pared simple (SWCNTs) dopados con titanio pueden adsorber establemente hasta seis moléculas de H₂ por par de átomos Ti a través de la interacción de Kubas en el centro activo Ti₂, confirmando la generalidad de este mecanismo en materiales nanoestructurados decorados con metales de transición (Osman et al., 2024). En los materiales ricos en boro, la deficiencia electrónica del andamiaje modifica el entorno electrónico del metal coordinado, desplazando las energías de adsorción hacia la ventana reversible de forma más controlable que en carbones puros (Xu et al., 2024).

#### 3.5.4 Teoría del Funcional de la Densidad (DFT) como herramienta de diseño racional

La Teoría del Funcional de la Densidad (DFT, del inglés *Density Functional Theory*) es el método computacional de referencia para el diseño racional de materiales de almacenamiento de H₂, al permitir calcular estructuras electrónicas, propiedades termodinámicas, mecanismos de reacción y propiedades fonónicas sin recurrir al costoso proceso experimental de ensayo y error (Xu et al., 2024). Los dos indicadores fundamentales derivados de los cálculos DFT para materiales de almacenamiento físico son la energía de enlace del dopante con el sustrato (E_b) y la energía de adsorción del H₂ (E_ad):

$$E_b = E_{\text{adsorbente}} - E_{\text{dopante}} - E_{\text{sustrato}}$$

$$E_{ad} = \frac{E_{\text{sistema}} - E_{\text{adsorbente}} - n \cdot E_{H_2}}{n}$$

donde valores de E_b superiores a la energía cohesiva del metal garantizan dispersión del dopante sin aglomeración, y valores de E_ad en el rango 0,2–0,6 eV corresponden a condiciones óptimas de reversibilidad (Xu et al., 2024). Para capturar con precisión las interacciones de largo alcance relevantes en la adsorción de H₂, es indispensable incluir correcciones de dispersión de van der Waals (DFT-D3 o vdW-DF), correcciones de energía vibracional del punto cero (ZPE) y efectos fonónicos que permitan acceder a energías libres de Gibbs en condiciones operativas (Osman et al., 2024). Sin embargo, el costo computacional de DFT escala con el cubo del número de electrones, lo que lo hace prohibitivo para la exploración masiva de candidatos o para simulaciones de dinámica molecular en escalas de nanosegundos, motivando el acoplamiento con modelos de inteligencia artificial.

#### 3.5.5 Aprendizaje automático y potenciales interatómicos de redes neuronales

Los Potenciales Interatómicos de Redes Neuronales (NNIPs, del inglés *Neural Network Potentials*), entrenados sobre bases de datos DFT, reproducen energías y fuerzas ab initio con un costo computacional órdenes de magnitud menor, habilitando dinámica molecular extendida en escalas de tiempo y espacio inaccesibles para métodos ab initio (Xu et al., 2024). Las Redes Neuronales de Grafos Cristalinos (CGCNN) y las Redes Neuronales de Grafos de Línea Atómica (ALIGNN) representan los materiales como grafos donde los nodos son átomos y las aristas codifican distancias y ángulos de enlace, permitiendo predecir propiedades energéticas y mecánicas con precisión cercana a DFT (Xu et al., 2024). Shekhar y Chowdhury (2024) demostraron que los modelos basados en redes neuronales son capaces de predecir la capacidad de almacenamiento de hidrógeno en MOFs con alta precisión, y que el análisis de datos topológicos puede enriquecer aún más estas predicciones (Osman et al., 2024). Los marcos de aprendizaje activo permiten reducir sustancialmente el tamaño de la base de datos requerida para entrenar un NNP convergido, acelerando la exploración del espacio químico de arquitecturas ricas en boro (Xu et al., 2024).


### 3.6 Estado del arte

#### 3.6.1 Panorama global del almacenamiento sólido de H₂: tendencias y retos vigentes

La investigación en almacenamiento sólido de H₂ ha experimentado un crecimiento sostenido en las últimas dos décadas, con la producción bibliográfica de los últimos cinco años dominada por los marcos metal-orgánicos (MOF, del inglés *Metal-Organic Frameworks*), los marcos orgánicos covalentes (COF), los hidruros metálicos y los materiales nanoestructurados de carbono (Kalibek et al., 2024; Xu et al., 2024). Los MOF y COF destacan por su alta área superficial y porosidad ajustable, con capacidades de hasta 6,7 % en peso en condiciones criogénicas (77 K), pero su limitación crítica es la baja energía de interacción van der Waals con el H₂ (2,2–5,2 kJ/mol), que impide la adsorción significativa a temperatura ambiente (Kalibek et al., 2024). Los hidruros metálicos, como MgH₂ y NaAlH₄, ofrecen altas densidades gravimétricas (7,7 % y 7,4 % en peso, respectivamente) pero requieren temperaturas de desorción superiores a 300 °C, lo que los hace inviables para aplicaciones móviles directas (Kalibek et al., 2024). Los portadores orgánicos líquidos (LOHCs), como el perhydro-dibenciltolueno, representan una solución avanzada para el almacenamiento estacionario a gran escala por su compatibilidad con la infraestructura existente de combustibles líquidos, pero su proceso de deshidrogenación es energéticamente intensivo (Le et al., 2024). Las revisiones sistemáticas más recientes concluyen de manera consistente que ningún material individual cumple simultáneamente las metas del DOE de capacidad, temperatura de operación cercana a ambiente y reversibilidad ciclable, lo que constituye el reto central no resuelto que justifica la búsqueda de nuevas arquitecturas de materiales (Xu et al., 2024; Mekonnin et al., 2025).

#### 3.6.2 Nanomateriales basados en boro: investigaciones previas y resultados más relevantes

Dentro del campo de los materiales de almacenamiento físico de H₂, los nanomateriales basados en boro han emergido como una de las líneas más prometedoras durante los últimos cinco años. Los estudios de primeros principios sobre el fulereno de boro B₄₀ decorado con Ca muestran que seis átomos de Ca se distribuyen de forma estable sobre la superficie del fulereno —con energías de enlace superiores a la energía cohesiva del Ca, garantizando la ausencia de *clustering*— y que cada sitio Ca puede adsorber hasta cinco moléculas de H₂ con una energía de adsorción de 0,177 eV, con una capacidad gravimétrica total de 8,11 % en peso confirmada mediante simulación de dinámica molecular a 300 K (Xu et al., 2024). Los borofenos decorados con Ti alcanzan densidades gravimétricas teóricas de hasta 15,07 % en peso con energías de adsorción en el rango óptimo, gracias a la alta estabilidad del enlace Ti-borofeno (E_b = 5,49 eV) que previene la migración del dopante (Xu et al., 2024). Wang et al. (2018) demostraron mediante cálculos DFT que el borofeno dopado con litio alcanza una capacidad gravimétrica de 13,96 % en peso y dopado con sodio alcanza 10,39 % en peso, con energías de adsorción dentro del rango deseable (citados en Osman et al., 2024). Los boruros mixtos tipo B-C-N también han mostrado resultados relevantes: el análisis DFT de monocapas de B₃CN₄ sin dopaje metálico revela la adsorción espontánea de seis moléculas de H₂ con energías en el rango 0,214–0,474 eV, lo que sugiere que la química del boro por sí sola puede modular la adsorción en ausencia de metales (Xu et al., 2024).

#### 3.6.3 Borohidruros metálicos complejos: diversidad estructural y limitaciones en la reversibilidad

Los borohidruros metálicos complejos de la forma MBH₄ (donde M = Li, Na, Mg, Ca, Y, Sc) representan la subclase de mayor densidad gravimétrica teórica entre los materiales químicos de almacenamiento: LiBH₄ almacena 18,4 % en peso de H₂ y NaBH₄ un 10,6 % en peso (Comanescu, 2022; Kalibek et al., 2024). Sin embargo, la alta estabilidad termodinámica de estos compuestos y la lenta cinética de desorción constituyen sus limitaciones operativas más críticas: la descomposición de LiBH₄ requiere temperaturas superiores a 400 °C y la rehidrogenación exige condiciones extremas de presión (70–350 bar) y temperatura (600 °C), lo que hace inviable su uso directo en ciclos reversibles de carga y descarga a temperatura ambiente (Comanescu, 2022). Las estrategias investigadas para superar estas limitaciones incluyen la nanoconfinación en soportes de carbono mesoporoso, donde se ha demostrado que la reducción del tamaño de poro disminuye la temperatura de desorción y acelera la cinética de desorción de forma significativa (Comanescu, 2022). Los nanotubos de carbono de múltiples paredes (MWCNTs) dopados con Pd y Ni han demostrado mejorar las tasas de spillover; particularmente, los Pd-MWCNTs alcanzan hasta 8,6 % en peso de H₂, mientras los Ni-MWCNTs logran 2,5 % en peso, evidenciando la importancia del metal dopante en la capacidad de almacenamiento de materiales de carbono (Osman et al., 2024). A pesar de estos avances, la reversibilidad completa de los borohidruros bajo condiciones prácticas de temperatura y presión sigue siendo un problema abierto, y los mecanismos intermedios de reacción continúan limitando la capacidad de recarga (Comanescu, 2022).

#### 3.6.4 Métodos computacionales: DFT, aprendizaje automático y NNIPs para materiales de hidrógeno

El uso de DFT para el diseño de materiales de almacenamiento de H₂ ha madurado hasta convertirse en la metodología estándar de preselección de candidatos: en los últimos cinco años se han publicado centenares de estudios que emplean DFT para calcular energías de adsorción, estructuras electrónicas, propiedades fonónicas y mecanismos de desorción en una variedad de materiales que abarca desde grafenos dopados hasta nanoestructuras de boro y MXenos (Xu et al., 2024). La integración de aprendizaje automático (ML) con DFT ha acelerado significativamente este proceso: modelos como redes neuronales artificiales, máquinas de vectores de soporte y bosques aleatorios han sido entrenados para predecir capacidades de almacenamiento, modelar cinética y clasificar materiales, reduciendo el espacio de búsqueda experimental de forma sustancial (Xu et al., 2024). Shekhar y Chowdhury (2024) demostraron que los modelos basados en redes neuronales predicen con alta precisión la capacidad de almacenamiento en MOFs, y que el análisis de datos topológicos mejora adicionalmente dichas predicciones (Osman et al., 2024). Suwarno et al. (2022) aplicaron aprendizaje automático para analizar los efectos de elementos aleantes sobre las propiedades de almacenamiento de hidruros metálicos AB₂, confirmando que los enfoques data-driven son un complemento indispensable de la simulación DFT cuando el espacio de candidatos es amplio (Osman et al., 2024). Los NNIPs basados en aprendizaje profundo, como la plataforma DP-GEN de aprendizaje concurrente (Zhang et al., 2020), permiten construir NNIPs de forma sistemática para materiales complejos, habilitando dinámicas moleculares en escalas de tiempo inaccesibles para métodos ab initio tradicionales (Batra & Sankaranarayanan, 2020; Zhang et al., 2020).

#### 3.6.5 Vacío del conocimiento: ausencia de un flujo integrado para nanoestructuras ricas en boro

La revisión sistemática de la literatura disponible permite identificar con precisión el vacío de conocimiento que justifica la novedad del proyecto propuesto. No existe actualmente un flujo de trabajo integrado que combine: (i) cálculos DFT de alta fidelidad con correcciones de dispersión, ZPE y contribuciones fonónicas para arquitecturas basadas en boro (metalacarboranos, borofenos, hojas de boro decoradas), (ii) modelos de grafos equivariantes del tipo ALIGNN o similares acoplados a estrategias de aprendizaje activo para explorar adaptativamente el espacio químico de estas arquitecturas, y (iii) NNIPs especializados en la dinámica a temperatura cercana a 300 K, la estabilidad ciclable y la selectividad frente a impurezas gaseosas en escalas de nanosegundos (Xu et al., 2024; Batra & Sankaranarayanan, 2020; Zhang et al., 2020). En el contexto colombiano, no se identifican proyectos anteriores que integren explícitamente nanoestructuras ricas en boro, redes neuronales de grafos equivariantes y NNIPs para el diseño de materiales de almacenamiento de H₂ alineados con la transición energética del país, lo que confirma el carácter novedoso y diferenciado de la propuesta frente al estado de la técnica nacional e internacional (Xu et al., 2024; Mekonnin et al., 2025). La única manera de avanzar hacia materiales candidatos que cumplan simultáneamente las metas del DOE bajo condiciones operativas realistas es precisamente a través de la metodología multiescala computacional propuesta, cuya arquitectura no tiene antecedente directo en el mercado ni en la literatura revisada (Xu et al., 2024; Zhang et al., 2020).



## Sección 4 — Componente técnico del proyecto

### 4.1 Objetivo general

Diseñar racionalmente, mediante un flujo de trabajo computacional multiescala integrado, arquitecturas de nanomateriales ricos en boro con capacidad de almacenamiento reversible de hidrógeno molecular (H₂) superior al 5,5 % en peso a condiciones operativas cercanas a temperatura ambiente, a través de la construcción de una base de datos de simulaciones DFT de alta fidelidad, el desarrollo de modelos de inteligencia artificial basados en redes neuronales de grafos (GNN) y potenciales interatómicos de redes neuronales (NNIPs), y la identificación de al menos tres candidatos computacionalmente validados en termodinámica, dinámica molecular y tolerancia a impurezas, con viabilidad de síntesis experimental documentada, que constituyan una prueba de concepto analítica de nivel TRL 3 orientada a la transición energética colombiana.

### 4.2 Objetivos específicos

**OE1 — Construcción de la base de datos DFT de alta fidelidad**

Construir una base de datos sistemática de propiedades termodinámicas, electrónicas y vibracionales de nanomateriales ricos en boro —incluyendo metalacarboranos, borofenos y hojas de boro decoradas con metales de transición tempranos (Sc, Ti, V)— mediante simulaciones DFT con correcciones de dispersión de van der Waals (DFT-D3), evaluación de estado de espín no restringido (UKS) y cálculos fonónicos de energía de punto cero (ZPE). El conjunto de datos comprenderá un mínimo de 200 configuraciones estructurales únicas, complementadas con estructuras seleccionadas de repositorios públicos de alta fidelidad (AFLOW, Materials Project), bajo criterios de convergencia energética validados (< 1 meV/Å en fuerzas atómicas), durante los primeros 6 meses de ejecución del proyecto.

**OE2 — Desarrollo y validación de modelos de inteligencia artificial (GNN y NNIPs)**

Desarrollar y validar un conjunto de modelos de inteligencia artificial para la predicción acelerada de propiedades de almacenamiento de H₂ en arquitecturas ricas en boro, que comprenda: (i) una Red Neuronal de Grafos Atómicos (GNN) del tipo ALIGNN o CGCNN entrenada sobre la base de datos DFT del OE1, integrada en un bucle de aprendizaje activo que reduzca en al menos un orden de magnitud los cálculos DFT requeridos para convergencia del modelo, y (ii) un Potencial Interatómico de Red Neuronal (NNP) construido mediante la plataforma DP-GEN, capaz de reproducir energías y fuerzas ab initio con un error cuadrático medio (RMSE) inferior a 3 meV/átomo, habilitando simulaciones de dinámica molecular extendida en el ensamble NVT a 300 K y escalas de tiempo de nanosegundos, durante los meses 4 a 11 del proyecto.

**OE3 — Identificación de candidatos con viabilidad de síntesis experimental**

Identificar y caracterizar computacionalmente al menos tres arquitecturas de nanomateriales ricos en boro con viabilidad de síntesis experimental, que cumplan simultáneamente: (i) capacidad gravimétrica de almacenamiento de H₂ ≥ 5,5 % en peso, (ii) energía de adsorción en la ventana de reversibilidad (0,2–0,6 eV/molécula de H₂), (iii) estabilidad estructural bajo ciclos de carga/descarga a 300 K validada mediante dinámica molecular NNP, (iv) tolerancia a impurezas gaseosas (O₂, H₂O) cuantificada mediante análisis de selectividad competitiva, y (v) compatibilidad con rutas de síntesis experimental documentadas —incluyendo deposición química de vapor (CVD), descarga en arco eléctrico (*arc-discharge*) y síntesis solvotérmica—, con la finalidad de constituir un portafolio de candidatos prioritarios para validación experimental futura, entregado en los últimos 3 meses del proyecto.

### 4.3 Metodología propuesta

Para superar las deficiencias sistemáticas de la literatura actual y alcanzar un Nivel de Madurez Tecnológica (TRL) 3 confiable, este proyecto plantea un marco metodológico híbrido que entrelaza la Teoría del Funcional de la Densidad (DFT) de alta fidelidad con Potenciales Interatómicos de Redes Neuronales Equivariantes (NNIPs). Esta metodología garantiza que la evaluación de los Metalacarboranos (0D) y Borofenos (2D) no se limite a mínimos locales estáticos, sino que demuestre viabilidad operativa en condiciones reales (300 K y presiones de hasta 100 bar).
El diseño metodológico se divide en cuatro (4) fases críticas de ejecución:

#### Fase 1: Generación de la Base de Datos Ab Initio (High-Throughput DFT)

La precisión de cualquier modelo de Inteligencia Artificial depende intrínsecamente de los datos de entrenamiento. En esta fase, se construirá un conjunto de datos (dataset) de alta fidelidad muestreando la Superficie de Energía Potencial (PES).
- Parámetros de Simulación Cuántica: Se utilizará el código VASP (Vienna Ab initio Simulation Package) con seudopotenciales PAW (Projector Augmented-Wave). El tratamiento del intercambio y correlación se realizará mediante el funcional generalizado de gradiente (GGA) PBE, modificado estrictamente con correcciones empíricas de dispersión de largo alcance (DFT-D3/D4 de Grimme), indispensables para modelar correctamente la fisisorción y las interacciones de Kubas del $H_2$.
- Tratamiento de Electrones Fuertemente Correlacionados: Para los metales de transición (Escandio, Titanio) decorados en los borofenos y encapsulados en los metalacarboranos, se aplicará el método DFT+U (parámetro de Hubbard) para corregir la deslocalización espuria de los electrones d, garantizando una predicción precisa del estado de espín y de las transferencias de carga de Bader.
- Muestreo del Espacio de Configuraciones: Se generarán configuraciones fuera del equilibrio mediante Dinámica Molecular Ab Initio (AIMD) a altas temperaturas (hasta 800 K) para enseñar a la red neuronal cómo responden los enlaces B-B, B-C y Met-H bajo estrés térmico severo.

#### Fase 2: Entrenamiento de los Potenciales de Redes Neuronales (NNIPs)
Con el dataset cuántico consolidado, se entrenará un modelo sustituto basado en Redes Neuronales de Grafos Equivariantes (E(3)-Equivariant GNNs), como NequIP o MACE.
- Arquitectura: Los átomos (B, C, H, Sc, Li) se representarán como nodos y sus interacciones espaciales como aristas en un grafo multicanal. La propiedad de "equivarianza" asegura que la red respete las leyes de conservación física (rotación, traslación e inversión).
- Función de Pérdida (Loss Function): El modelo minimizará simultáneamente el error cuadrático medio (MSE) de las energías totales, las fuerzas atómicas ($eV/\mathring{A}$) y los tensores de estrés del virial. El objetivo es alcanzar un Error Absoluto Medio (MAE) inferior a $1 \text{ meV/átomo}$ en energía y $15 \text{ meV/}\mathring{A}$ en fuerzas.
- Active Learning (Aprendizaje Activo): El entrenamiento no será estático. La IA explorará nuevas configuraciones de adsorción de $H_2$ y, al detectar zonas de alta incertidumbre (varianza en un ensamble de modelos), enviará automáticamente esas geometrías de vuelta al motor DFT para reevaluación, enriqueciendo el dataset de manera autónoma.


#### Fase 3: Validación Fonónica y Estabilidad Dinámica Computacional (Hito Crítico)
Una debilidad recurrente en las investigaciones teóricas de nanomateriales para almacenamiento de hidrógeno es reportar estructuras que son matemáticamente puntos de silla (saddle points) en lugar de mínimos verdaderos. Para asegurar que los metalacarboranos y borofenos decorados propuestos sean sintetizables y estables, se ejecutará un riguroso análisis de dispersión de fonones.
- Matriz Dinámica y Constantes de Fuerza: Utilizando el Potencial de Red Neuronal (que es computacionalmente órdenes de magnitud más rápido que el DFT), se calculará la matriz Hessiana completa perturbando sistemáticamente todos los átomos de la celda de simulación. Esto arrojará las constantes de fuerza armónicas e inarmónicas.
- Espectro de Frecuencias Vibracionales: Se calcularán las curvas de dispersión fonónica a lo largo de los caminos de alta simetría en la zona de Brillouin (para la red 2D de borofeno) y la Densidad de Estados Fonónicos (Phonon DOS).
- Criterio de Cero Frecuencias Imaginarias: La estabilidad dinámica se confirmará única y exclusivamente si el espectro fonónico presenta una ausencia total de frecuencias imaginarias (ramas acústicas y ópticas con $\omega^2 > 0$). Cualquier arquitectura de borofeno decorado con Li o Sc que presente fonones imaginarios será descartada como un artificio numérico no sintetizable.
- Energía del Punto Cero (ZPE) y Termodinámica Estadística: Las frecuencias fonónicas calculadas ($\omega_i$) se integrarán para cuantificar la Energía Vibracional del Punto Cero (ZPE = $\sum \frac{1}{2} \hbar \omega_i$) y la entropía vibracional ($S_{vib}$). Esta validación fonónica permitirá transitar de la energía estática ($E_{DFT}$) a la Energía Libre de Gibbs ($G(T,P)$), permitiendo predecir la temperatura exacta de desorción del hidrógeno con presión parcial finita, un cálculo que tradicionalmente es prohibitivo por el inmenso costo computacional del DFT directo.

#### Fase 4: Dinámica Molecular a Escala Macroscópica y Selectividad
Superada la validación fonónica, el potencial neuronal (NNP) se utilizará para ejecutar simulaciones de Dinámica Molecular (MD) en el ensamble isotérmico-isobárico (NPT).
- Escala de Nanosegundos: A diferencia de la AIMD tradicional (limitada a escasos picosegundos), la eficiencia de la IA permitirá observar la evolución de los sistemas durante decenas de nanosegundos. Esto es esencial para observar fenómenos de aglomeración metálica (clustering de Escandio sobre el borofeno), barreras cinéticas de desorción y el envenenamiento competitivo si se exponen a trazas de oxígeno ($O_2$).
- Verificación de Capacidad Reversible: Se evaluará termodinámicamente si el sistema cumple con la meta del Departamento de Energía de EE.UU. (DOE) >5.5 wt% y >40 g/L de $H_2$ reversible operando a temperatura ambiente (300 K)


### 4.4 Resultados esperados



### 4.5 Beneficios o productos esperados

El proyecto generará un conjunto de beneficios y productos tangibles, diferenciados
según su naturaleza científico-tecnológica, su impacto sobre las capacidades
institucionales de la alianza y su contribución directa al ecosistema de CTeI
en la región.

#### 4.5.1 Productos científico-tecnológicos

**Producto 1 — Base de datos DFT de alta fidelidad (mínimo 200 configuraciones).**
Conjunto de datos computacionales de acceso abierto que incluye energías de
formación, energías de adsorción de H₂, constantes de fuerza fonónicas y energías
libres de Gibbs a 300 K para arquitecturas de nanomateriales ricos en boro
(metalacarboranos, borofenos y hojas de boro decoradas con Sc, Ti y V). Este
producto constituirá el primer repositorio público de Colombia especializado en
simulaciones cuánticas de materiales de almacenamiento de hidrógeno y será
depositado en repositorios de acceso abierto (Zenodo/Materials Cloud) bajo
licencia Creative Commons, en cumplimiento de los lineamientos de Ciencia
Abierta del Ministerio de Ciencia, Tecnología e Innovación.
*Indicador verificable:* Repositorio público activo con ≥ 200 entradas validadas
al mes 6 del proyecto.

**Producto 2 — Modelo de red neuronal de grafos (GNN) entrenado y validado.**
Modelo ALIGNN o CGCNN entrenado sobre la base de datos DFT del Producto 1,
integrado en un flujo de aprendizaje activo que predice energías de adsorción
de H₂ y estabilidades de enlace dopante-sustrato con RMSE < 50 meV/átomo.
El modelo será publicado como software de código abierto (licencia MIT) y
documentado para su reutilización por otros grupos de investigación nacionales.
*Indicador verificable:* Repositorio GitHub público con código documentado y
métricas de validación publicadas al mes 9.

**Producto 3 — Potencial Interatómico de Red Neuronal (NNP) especializado en
materiales ricos en boro.** NNP entrenado mediante la plataforma DP-GEN, con
RMSE en energías < 3 meV/átomo y en fuerzas < 100 meV/Å, que habilita dinámica
molecular extendida a 300 K en escalas de nanosegundos para al menos tres
arquitecturas candidatas seleccionadas. Constituye el primer NNP público de
Colombia especializado en nanomateriales ricos en boro para almacenamiento
de hidrógeno.
*Indicador verificable:* Modelo publicado con documentación técnica y curvas
de aprendizaje al mes 11.

**Producto 4 — Portafolio de al menos tres candidatos computacionalmente
validados (TRL 3).** Informe técnico-científico que caracteriza al menos tres
arquitecturas de nanomateriales ricos en boro que cumplen simultáneamente:
(i) capacidad gravimétrica ≥ 5,5 % en peso, (ii) energía de adsorción en la
ventana de reversibilidad (0,2–0,6 eV/molécula de H₂), (iii) estabilidad
estructural bajo ciclos de carga/descarga a 300 K confirmada mediante dinámica
molecular NNP, (iv) tolerancia a impurezas gaseosas (O₂, H₂O) documentada, y
(v) compatibilidad con rutas de síntesis experimental conocidas. Este portafolio
orientará la fase experimental futura del proyecto y servirá de insumo para
solicitudes de protección de propiedad intelectual.
*Indicador verificable:* Informe técnico con fichas detalladas de cada candidato
entregado al mes 14; al menos una solicitud de protección de PI radicada antes
del cierre.

**Producto 5 — Artículos científicos.** Al menos dos (2) artículos sometidos a
revistas indexadas (Q1/Q2, Scopus o Web of Science) en las temáticas de
simulación computacional de materiales para almacenamiento de hidrógeno y
potenciales interatómicos de redes neuronales. Al menos uno de los artículos
incluirá como autores a jóvenes investigadores e innovadores vinculados al
proyecto.
*Indicador verificable:* Comprobantes de sometimiento a revista al mes 14.

#### 4.5.2 Productos de apropiación social y divulgación

**Producto 6 — Producto de Apropiación Social del Conocimiento (ASC).**
- **Componente 6A: Proceso de involucramiento territorial.** El equipo de investigación adelantará un proceso de involucramiento con actores sociales del Caribe colombiano mediante al menos dos (2) jornadas de diálogo de saberes que conecten los principios del almacenamiento de energía con las necesidades y realidades energéticas del territorio. Este proceso incluirá (i) diálogos participativos para identificar expectativas, necesidades e interes de los actores locales respecto a las tecnologías de almacenamiento energético; (ii) jornadas de intercambio de saberes y conocmientos en las que los actores socialicen ideas, propuestas y perspectivas mediadas por CTeI; y (iii) sistematización colaboratirva de los resultados acordada entre los participantes y documentada en múltiples formatos. El proceso se inscribe en el escenario de involucramiento definido por la Política Pública de ASC.

- **Componente 6B — Estrategia de divulgación pública multiformato.** En paralelo, el proyecto ejecutará una estrategia de comunicación pública de la ciencia orientada a audiencias no especializadas, con el propósito de democratizar el conocimiento generado sobre almacenamiento de energía y su relevancia para la transición energética del territorio. Esta estrategia se materializará mediante la producción y publicación de una serie de videos de divulgación científica en un canal institucional de YouTube, con al menos seis (6) episodios durante la vigencia del proyecto. Cada episodio abordará en lenguaje accesible y con narrativa transmediática los avances, hallazgos y potenciales impactos del proyecto, articulando los resultados técnicos con su relevancia social y territorial. La estrategia contempla, adicionalmente, la difusión de los contenidos a través de redes sociales institucionales (Instagram, LinkedIn y X/Twitter) con el fin de ampliar el alcance a públicos regionales y nacionales, en línea con las dimensiones orientadoras de la Divulgación Pública de la Ciencia establecidas por MinCiencias (Ministerio de Ciencia, 2024). Los contenidos visibilizarán el proceso investigativo, las comunidades involucradas y la escalabilidad de los resultados, promoviendo nuevos relacionamientos entre actores académicos, sociales y productivos

#### 4.5.3 Beneficios para la alianza y la región

La ejecución del proyecto fortalece las capacidades de cómputo de alto rendimiento
y de inteligencia artificial de la IES ejecutora, genera experiencia institucional
en simulación cuántica de materiales de energía y posiciona al equipo investigador
como referente nacional en la línea de CTeI estratégica de "Energía Sostenible
y Minerales Estratégicos" definida por el eje temático de Ciencia y Tecnologías
Cuánticas de la convocatoria. Para [NOMBRE DE LA ORGANIZACIÓN LOCAL/REGIONAL],
el proyecto representa un primer punto de contacto con metodologías de inteligencia
artificial aplicadas a la transición energética, habilitando futuras solicitudes
de financiamiento en convocatorias regionales de eficiencia energética.

---

### 4.6 Impacto ambiental

El proyecto es de naturaleza exclusivamente computacional: todas sus actividades
se realizan mediante software de simulación cuántica y aprendizaje automático
ejecutado en servidores de cómputo de alto rendimiento o en plataformas de
computación en la nube. No contempla síntesis química, manipulación de sustancias
peligrosas, generación de residuos sólidos o líquidos, emisiones atmosféricas,
vertimientos, extracción de recursos naturales, ni intervención sobre ecosistemas.
En consecuencia, el proyecto **no genera impactos ambientales negativos directos**
y **no requiere licencia ambiental ni ningún permiso especial** expedido por
autoridades ambientales, en cumplimiento de la Ley 99 de 1993, artículo 3,
sobre el concepto de desarrollo sostenible.

#### Impactos ambientales positivos

El proyecto genera impactos ambientales positivos de carácter indirecto, mediato
y estratégico, articulados con la misión de transición energética del Plan Nacional
de Desarrollo 2022-2026. Su contribución ambiental opera en tres dimensiones:

**Dimensión 1 — Reducción de emisiones de CO₂ en el largo plazo.**
El hidrógeno verde almacenado eficientemente en estado sólido puede reemplazar
a los combustibles fósiles en sectores de difícil descarbonización (transporte
pesado, industria química y generación distribuida de electricidad). Los
materiales que el proyecto identifica computacionalmente —nanomateriales ricos
en boro con capacidades gravimétricas ≥ 5,5 % en peso y operación reversible
a temperatura ambiente— representan una ruta tecnológica que, una vez validada
experimentalmente y escalada, contribuiría a la reducción de emisiones de gases
de efecto invernadero en Colombia, en coherencia con los compromisos del país
bajo el Acuerdo de París y la Contribución Determinada a Nivel Nacional (NDC)
revisada en 2020, que fija una reducción del 51 % de las emisiones al año 2030
respecto a la trayectoria tendencial.

**Dimensión 2 — Uso eficiente de recursos de cómputo.**
La metodología multiescala del proyecto reduce en al menos un
orden de magnitud el consumo de horas de cómputo necesarias para identificar
candidatos viables, disminuyendo el consumo energético asociado a la simulación
computacional intensiva. Este beneficio es coherente con los principios de
eficiencia energética que la convocatoria promueve para el desarrollo de
proyectos de CTeI.

**Dimensión 3 — Alternativa a síntesis experimental de alto impacto ambiental.**
El diseño racional in silico propuesto evita etapas tempranas de síntesis
experimental de nanomateriales que frecuentemente implican el uso de solventes
orgánicos, precursores metálicos costosos y procesos energéticamente intensivos
(deposición química de vapor, descarga en arco eléctrico). Al identificar
computacionalmente los candidatos más prometedores antes de avanzar a síntesis,
el proyecto reduce significativamente la huella ambiental del proceso de
descubrimiento de materiales en comparación con enfoques de ensayo y error
experimental.

#### Gestión ambiental durante la ejecución

El proyecto cumplirá con la política de uso responsable de energía eléctrica
durante el cómputo intensivo, priorizando el uso de servidores con certificación
de eficiencia energética y, cuando sea posible, el uso de plataformas de
computación en la nube alimentadas con energía renovable. No se generarán
residuos de aparatos eléctricos y electrónicos (RAEE) durante la ejecución, dado
que el proyecto no adquiere equipos físicos de cómputo con cargo a los recursos
de la convocatoria.

---

### 4.7 Impactos en comunidades/organizaciones

Como impacto de los proyectos financiados por la convocatoria Colombia Inteligente
2026 se espera un mayor valor agregado que se traduzca en beneficios concretos
para las comunidades y organizaciones. Los impactos descritos a continuación
corresponden a efectos esperados en el mediano y largo plazo, una vez finalice
el proyecto y se transfieran y apropien los conocimientos generados.

#### 4.7.1 Impactos en el conocimiento del campo de estudio

El proyecto genera el primer flujo de trabajo computacional colombiano que integra
DFT de alta fidelidad, redes neuronales de grafos equivariantes y potenciales
interatómicos de redes neuronales para el diseño de nanomateriales de almacenamiento
de hidrógeno basados en arquitecturas ricas en boro. Este aporte llena un vacío
metodológico identificado en la literatura internacional (Xu et al., 2024; Batra
& Sankaranarayanan, 2020) y posiciona a Colombia como un actor emergente en la
línea de simulación cuántica de materiales estratégicos para la transición
energética.
*Indicador:* Al menos dos artículos sometidos a revistas Q1/Q2 al mes 14 y
al menos una cita recibida por los modelos publicados en repositorios abiertos
en los doce meses posteriores al cierre del proyecto.

#### 4.7.2 Impactos sobre la productividad y la competitividad

El portafolio de candidatos computacionalmente validados (Producto 4) constituye
un insumo estratégico para empresas del sector energético, fabricantes de
dispositivos de almacenamiento y centros de síntesis de nanomateriales colombianos,
que podrán orientar sus inversiones en I+D experimental hacia arquitecturas
con alta probabilidad de éxito, reduciendo costos y tiempos de desarrollo.
La empresa nacional participante de la alianza fortalecerá sus capacidades en
el uso de herramientas de inteligencia artificial para el análisis de materiales,
habilitando nuevas líneas de servicios de consultoría computacional en el
sector energético.
*Indicador:* Al menos una reunión técnica de transferencia de resultados con
el sector productivo antes del mes 14 y documento de hoja de ruta de síntesis
experimental elaborado conjuntamente con la empresa aliada.

#### 4.7.3 Impactos regionales

La ejecución del proyecto en el departamento de Bolívar, en el marco de la región
Caribe y Seaflower, contribuye a fortalecer el ecosistema local
de CTeI al vincular talento humano joven (jóvenes investigadores, estudiantes
de maestría y semillero de investigación) en actividades de frontera científica
y tecnológica. Esto reduce las brechas de capacidades en ciencias cuánticas e
inteligencia artificial entre las regiones y los grandes centros de investigación
del país, en línea con el objetivo estratégico OE4 del CONPES 4144 de 2025.
El impacto regional se materializa también a través del componente de formación
(Sección 5), que alcanzará a al menos 250 niñas, niños y jóvenes de la zona
de influencia.
*Indicador:* Mínimo 250 beneficiarios del componente de formación certificados
al mes 14; al menos 2 jóvenes investigadores graduados vinculados durante 12 meses.

#### 4.7.4 Impactos en la calidad de vida de la población

El proyecto impacta indirectamente la calidad de vida de la población al contribuir
al desarrollo de una cadena de valor del hidrógeno verde en Colombia que, en el
mediano plazo, puede traducirse en acceso a energía más limpia, estable y
asequible para comunidades actualmente dependientes de combustibles fósiles o
con baja cobertura de energía eléctrica. [NOMBRE DE LA ORGANIZACIÓN LOCAL/REGIONAL],
al participar activamente en las jornadas de diálogo de saberes y apropiación
de la tecnología, adquiere capacidad de incidencia informada en decisiones de
política energética local y regional.
*Indicador:* Número de personas de la organización local/regional que participan
en jornadas de ASC (meta: mínimo [N] personas); sistematización del proceso
de diálogo de saberes entregada al mes 12.

#### 4.7.5 Impactos en las políticas públicas

Los resultados del proyecto aportan evidencia científica para la definición de
rutas tecnológicas prioritarias en materia de almacenamiento de hidrógeno verde
en la política energética colombiana, en coherencia con la acción 6.28 del Plan
de Acción y Seguimiento del CONPES 4144 (integración de IA en la transición
energética). El equipo investigador se compromete a presentar los resultados
finales ante autoridades locales, nacionales y sectoriales (UPME, IRENA Colombia,
MinCiencias) antes del cierre formal del proyecto.
*Indicador:* Registro de al menos una presentación pública de resultados ante
autoridades del sector antes del mes 14.



### 4.8 Estrategia de sostenibilidad

La sostenibilidad del proyecto se estructura en dos dimensiones complementarias e interdependientes: la sostenibilidad científica, orientada a garantizar la continuidad y el impacto de los resultados de investigación más allá del período de financiamiento; y la sostenibilidad institucional, dirigida a consolidar capacidades permanentes de cómputo científico e inteligencia artificial en las IES ejecutoras y en los actores de la alienza.

#### 4.8.1 Sostenibilidad Científica.
El principal mecanismo de sostenibilidad científica del proyecto es la publicación en acceso abierto de todos los productos de conocimiento. La base de datos DFT de alta fidelidad (Producto 1) será depositada en repositorios internacionale de acceso abierto (ej: Zenodo, Materials Cloud, etc). [Definir tipo de licencia], garantizando su reutilización por grupos de investigación nacionales e internacionales sin restricciones. Los modelos GNN y NNP (Productos 2 y 3) serán publicados como software de código abierto con licencia MIT en repositorios públicos (GitHub, GitLab, etc) con documentación técnica completa que permita su extensión a nuevas familias de materiales. Esta estrategia de ciencia abierta es coherente con los lineamientos de acceso abierto del Ministerio de Ciencias, Tecnologías e Innovación.

La sostenibilidad de línea de investigación se asegura mediante una hoja de ruta de financiamiento en múltiples horizontes temporales. En el corto plazo (0-12 meses post-cierre) el equipo de investigadores someterá al menos dos artículos científicos a revistas indezadas, consolidando el capital científico del grupo y habilitando métricas de evaluación para futuras convocatorias. **En el mediano plazo**, (2 - 3 años post-cierre), los candidatos computacionales validados (Producto 4) constituirán la base técnica para una propuesta de investigación de fase experimental (TLR 4-5) que será formulada para convocatorias nacionales de MinCiencias e internacionales. **En el largo plazo**, (más de 3 años)la existencia de un NNP especializado en nanomateriales ricos en boro —el primero desarrollado en Colombia para esta familia de materiales— constituye un activo científico diferencial que posiciona al grupo investigador como referente nacional en simulación cuántica de materiales estratégicos para la transición energética, habilitando colaboraciones con redes internacionales.

#### 4.8.2 Sostenibilidad institucional

La Universidad de Cartagena consolidará, como resultado directo del proyecto, una infraestructura de cómputo científico de alto rendimiento (HPC) y un conjunto de flujos de trabajo documentados y reproducibles para la simulación cuántica de materiales. Esta infraestructura —que incluye los entornos de software configurados (VASP, LAMMPS, DP-GEN, ALIGNN), los scripts de automatización de cálculos y los pipelines de aprendizaje activo— será transferida al laboratorio de computación de la institución al cierre del proyecto, quedando disponible para futuros grupos de investigación y cursos de posgrado sin costo adicional. El impacto institucional se extiende a la actualización del currículo de programas de maestría y doctorado en ciencias naturales e ingeniería, donde los módulos de simulación cuántica y potenciales de aprendizaje automático podrán incorporarse como contenidos de frontera, fortaleciendo la pertinencia y la competitividad académica de la institución a nivel nacional.

La alianza formada para la ejecución del proyecto sienta las bases de una relación de colaboración continua entre la IES ejecutora y los socios de la alianza. El protocolo de transferencia de resultados diseñado en la sección 4.7.2, que incluye reuniones técnicas con el sector productivo y la elaboración conjunta de hojas de ruta de síntesis experimental, constituye el primer eslabón de un vínculo Universidad–Empresa–Estado de largo aliento. Este vínculo podrá formalizarse, al cierre del proyecto, mediante la suscripción de acuerdos de colaboración o contratos de investigación cofinanciada para la fase experimental (TRL 4–5), asegurando la continuidad del programa de investigación en el ecosistema CTeI de la región Caribe y Seaflower.


### 4.9 Estrategia de apropiación y uso de la tecnología

La estrategia de apropiación y uso de la tecnología del proyecto opera en tres niveles diferenciados de transferencia, cada uno diseñado para un perfil específico de usuario final: (i) la comunidad científica nacional e internacional, que utilizará los modelos computacionales y la base de datos como insumos para investigación futura; (ii) el sector productivo energético colombiano, que incorporará el portafolio de candidatos validados como hoja de ruta para inversiones en I+D experimental; y (iii) la comunidad académica y social regional, que apropiará los conceptos fundamentales de la tecnología a través de los instrumentos de la estrategia de Apropiación Social del Conocimiento (ASC) diseñada en el marco del proyecto. Esta estructura escalonada garantiza que ningún resultado del proyecto quede confinado al ámbito exclusivo de la publicación científica, sino que circule activamente por el ecosistema CTeI colombiano en formatos adecuados para cada audiencia.

#### 4.9.1 Apropiación por la comunidad científica nacional
El primer nivel de transferencia está orientado a investigadores, grupos de investigación y estudiantes de posgrado de instituciones colombianas que trabajan en las líneas de simulación computacional de materiales, química cuántica e inteligencia artificial aplicada a ciencias de los materiales. El mecanismo central de apropiación en este nivel es la publicación en acceso abierto de todos los artefactos digitales del proyecto: la base de datos DFT (Producto 1) en Zenodo y Materials Cloud, el modelo GNN (Producto 2) y el NNP especializado (Producto 3) en GitHub bajo licencia MIT, con documentación técnica exhaustiva que incluirá tutoriales paso a paso, cuadernos interactivos (Jupyter Notebooks) y casos de uso reproducibles. Esta modalidad de transferencia elimina las barreras de acceso a herramientas de frontera que históricamente han limitado la capacidad investigativa de grupos nacionales frente a laboratorios internacionales bien financiados (Xu et al., 2024; Batra & Sankaranarayanan, 2020).

Complementariamente, el equipo investigador ofrecerá al menos un taller técnico presencial o virtual dirigido a grupos de investigación nacionales durante el último trimestre del proyecto, en el que se demostrará el uso práctico del flujo de trabajo computacional integrado —desde la configuración de los cálculos DFT hasta el entrenamiento del NNP con DP-GEN— y se presentarán los resultados del portafolio de candidatos validados. Este taller constituye un mecanismo de transferencia directa de capacidades que va más allá de la publicación pasiva, asegurando que el conocimiento tácito acumulado por el equipo durante los 14 meses de ejecución sea transmitido a nuevos usuarios (Zhang et al., 2020).

#### 4.9.2 Apropiación por el sector productivo
El segundo nivel de transferencia está dirigido a empresas del sector energético colombiano, fabricantes de dispositivos de almacenamiento y centros de síntesis de nanomateriales con capacidad de llevar los resultados computacionales hacia validación experimental. El mecanismo principal de apropiación en este nivel es la entrega del Portafolio de Candidatos Validados (Producto 4) en un formato técnico-ejecutivo accesible para tomadores de decisiones no especializados en simulación cuántica, que incluirá: fichas técnicas de cada candidato con sus propiedades clave (capacidad gravimétrica, ventana de reversibilidad, tolerancia a impurezas), una hoja de ruta de síntesis experimental con rutas documentadas (CVD, descarga en arco, síntesis solvotérmica) y una estimación de los recursos requeridos para avanzar al TRL 4. Este documento de transferencia tecnológica será presentado en al menos una reunión técnica formal con representantes del sector productivo antes del mes 14, generando un vínculo directo entre los resultados de la investigación básica y las decisiones de inversión en I+D aplicado (Xu et al., 2024).

La empresa nacional participante de la alianza cumple un rol estratégico en este nivel de apropiación: actúa simultáneamente como primer receptor de la tecnología y como puente hacia otros actores del sector productivo regional. Su participación activa en las reuniones de seguimiento trimestral del proyecto garantiza que el desarrollo de los modelos computacionales esté permanentemente orientado hacia las necesidades y restricciones reales del sector, reduciendo la brecha entre la investigación académica y la aplicación industrial que históricamente ha limitado el impacto de los proyectos de CTeI en Colombia.

#### 4.9.3 Apropiación social y comunitaria
El tercer nivel de transferencia opera a través de la estrategia de Apropiación Social del Conocimiento (ASC) del proyecto, estructurada en siete actividades complementarias diseñadas para audiencias no especializadas. Las jornadas de diálogo de saberes con organizaciones comunitarias de la zona de influencia en el departamento de Bolívar conectan los principios del almacenamiento de energía limpia con las necesidades energéticas concretas del territorio, empleando metodologías participativas de diagnóstico y sistematización colaborativa (Barrero & Franco-Avellaneda, 2024; Ministerio de Ciencia, 2021). El MOOC de libre acceso sobre fundamentos de hidrógeno verde e inteligencia artificial en ciencia de materiales democratiza el acceso a competencias tecnológicas de frontera para audiencias más amplias —estudiantes de pregrado, docentes de secundaria y público interesado— reduciendo las barreras de entrada al campo y sembrando vocaciones científicas en la región Caribe. La campaña digital multiplataforma y los pósteres científicos de divulgación garantizan que los principales hallazgos del proyecto lleguen a audiencias que no acceden a canales académicos tradicionales, usando lenguaje visual accesible y narrativas ancladas en la cotidianidad energética colombiana.

La apropiación en este nivel no se limita a la recepción pasiva de información: el componente de semillero de investigación (Producto 8, sección 4.5.2) convierte a diez estudiantes de pregrado en actores activos del proceso de generación de conocimiento, entrenándolos en el uso de herramientas computacionales de frontera y en la comunicación pública de la ciencia. Esta estrategia de apropiación activa, fundamentada en el enfoque de involucramiento de la Política Pública de ASC de MinCiencias (2021), asegura que la transferencia tecnológica tenga raíces en el tejido educativo y social de la región, generando impactos que persisten más allá del cierre formal del proyecto.

#### 4.9.4 Barreras de adopción y estrategias de mitigación
La principal barrera para la adopción de los modelos computacionales desarrollados es la brecha de capacidades técnicas en el uso de herramientas de simulación cuántica y aprendizaje automático en instituciones colombianas distintas a las grandes universidades del país. Esta barrera se mitiga mediante tres mecanismos simultáneos: (i) la documentación exhaustiva y los tutoriales interactivos que acompañan la publicación de los modelos en acceso abierto, diseñados explícitamente para usuarios con formación en química o física pero sin experiencia previa en programación avanzada; (ii) el taller técnico de transferencia dirigido a grupos nacionales (sección 4.9.1); y (iii) la formación del semillero de investigación como núcleo de multiplicadores locales con competencias verificadas en el uso del flujo de trabajo del proyecto 



### 4.10 Propiedad intelectual

La gestión de la propiedad intelectual (PI) del proyecto se rige por las disposiciones de la Ley 1286 de 2009 (Ley de Ciencia, Tecnología e Innovación), el Decreto 1075 de 2015 y los reglamentos institucionales de propiedad intelectual de la IES ejecutora, en concordancia con las condiciones establecidas en los Términos de Referencia de la Convocatoria Colombia Inteligente 2026. Dado que el proyecto genera exclusivamente activos de conocimiento de naturaleza digital —bases de datos computacionales, modelos de inteligencia artificial y software científico—, la estrategia de PI está articulada en tres ejes: (i) protección mediante derechos de autor de software y datos, (ii) divulgación estratégica en acceso abierto para maximizar el impacto y la trazabilidad científica, y (iii) reserva de posibles derechos de patente sobre las arquitecturas de nanomateriales identificadas como candidatas, cuya novedad será evaluada antes del cierre del proyecto.

#### 4.10.1 Titularidad de los resultados
De conformidad con el artículo 27 de la Ley 1286 de 2009 y las condiciones de la convocatoria, la titularidad de los resultados generados con recursos de MinCiencias corresponde conjuntamente a las entidades de la alianza en proporción a su contribución al proyecto, según lo estipulado en el acuerdo de propiedad intelectual suscrito entre los miembros antes del inicio de actividades. La IES ejecutora ostentará la titularidad principal sobre los productos científico-tecnológicos (Productos 1, 2, 3 y 4), en tanto que los derechos morales de autoría de los artículos científicos (Producto 5) corresponderán individualmente a los investigadores que figuren como autores según las normas de autoría de cada revista.

MinCiencias, en su calidad de entidad cofinanciadora, tendrá derecho de acceso no exclusivo a los resultados del proyecto para fines de divulgación, evaluación de impacto y formulación de política pública, de conformidad con el contrato de financiamiento suscrito. Este derecho de acceso no implica titularidad sobre los modelos computacionales ni sobre el portafolio de candidatos, cuya explotación económica futura queda reservada a la alianza.

#### 4.10.2 Protección de software y bases de datos
Los modelos de inteligencia artificial (GNN y NNP) y los scripts de automatización de cálculos DFT desarrollados durante el proyecto constituyen obras de software protegidas por derechos de autor en virtud de la Decisión Andina 351 de 1993 y la Ley 23 de 1982. El registro de estos programas se realizará ante la Dirección Nacional de Derecho de Autor (DNDA) antes del mes 12 del proyecto, como mecanismo de protección formal y de trazabilidad institucional. La publicación posterior en repositorios de acceso abierto (GitHub) se realizará bajo licencia MIT, que preserva la autoría institucional y permite la reutilización libre con atribución obligatoria, siendo coherente con la política de ciencia abierta de MinCiencias sin renunciar a los derechos morales ni patrimoniales de la IES ejecutora.

La base de datos DFT de alta fidelidad (Producto 1) constituye una obra colectiva protegida como base de datos en los términos del artículo 12 de la Decisión Andina 351. Su depósito en Zenodo y Materials Cloud se realizará bajo licencia Creative Commons CC-BY 4.0, que garantiza el acceso abierto universal con atribución obligatoria a la IES ejecutora y al proyecto Colombia Inteligente 2026, asegurando la visibilidad y el crédito institucional en cada reutilización.

#### 4.10.3 Evaluación de patentabilidad de candidatos computacionalmente validados
El portafolio de arquitecturas de nanomateriales ricos en boro computacionalmente validadas (Producto 4) será sometido a un análisis de patentabilidad por parte del grupo de PI de la IES ejecutora durante los meses 12 a 14 del proyecto. El análisis evaluará el cumplimiento de los tres requisitos de patentabilidad establecidos en la Decisión Andina 486 de 2000: novedad, nivel inventivo y aplicación industrial. Dado que el proyecto opera en nivel TRL 3 —prueba de concepto analítica y computacional—, la protección más adecuada para esta etapa es la solicitud de patente de invención sobre las combinaciones específicas de dopante-sustrato-topología que demuestren cumplir simultáneamente las metas del DOE (capacidad gravimétrica ≥ 5,5% en peso, reversibilidad ≥ 1.500 ciclos, temperatura de operación cercana a ambiente), antes de su divulgación pública en artículos científicos, respetando el período de gracia de 12 meses contemplado en la legislación colombiana.

En caso de que el análisis concluya que las arquitecturas identificadas no cumplen el requisito de novedad frente al estado del arte internacional —posibilidad que se reduce significativamente dado el vacío de conocimiento documentado en la sección 3.6.5— se adoptará como alternativa la estrategia de divulgación científica prioritaria (prior art disclosure), que fija públicamente la fecha de descubrimiento mediante la publicación del preprint en arXiv o ChemRxiv antes del sometimiento formal a revista, protegiendo al equipo investigador de reclamaciones de terceros sin incurrir en los costos de un proceso de patentamiento

#### 4.10.4 Acuerdo de confidencialidad y gestión de conflictos
Los miembros de la alianza suscribirán un Acuerdo de Confidencialidad y Gestión de Propiedad Intelectual (ACGPI) antes del inicio formal del proyecto, que regulará: (i) el tratamiento de información técnica sensible durante la ejecución, (ii) los procedimientos de decisión conjunta para la divulgación de resultados, (iii) la distribución de regalías en caso de explotación comercial futura de los modelos o candidatos identificados, y (iv) el mecanismo de resolución de conflictos entre las partes sobre titularidad o uso de los resultados. Este acuerdo será elaborado con el acompañamiento de las oficinas de transferencia tecnológica (OTT) de la IES ejecutora y revisado por el asesor jurídico de la empresa aliada antes de su firma.



### 4.11 Riesgos del proyecto

La matriz de riesgos del proyecto identifica los principales eventos que podrían afectar el logro de los objetivos específicos, clasificados según su naturaleza, probabilidad de ocurrencia e impacto sobre los resultados esperados. Dado que el proyecto es de naturaleza exclusivamente computacional, los riesgos físicos, ambientales y de seguridad industrial son nulos; los riesgos críticos se concentran en las dimensiones técnico-científica, operativa y de talento humano.

| #  | Riesgo                                                                                                                   | Tipo                   | Probabilidad | Impacto | Medida de mitigación                                                                                                                                                                                                                            |
| -- | ------------------------------------------------------------------------------------------------------------------------ | ---------------------- | ------------ | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| R1 | Falta de convergencia del modelo NNP debido a insuficiencia o sesgo en el dataset DFT de entrenamiento                   | Técnico-científico     | Media        | Alto    | Implementación de aprendizaje activo (Active Learning) para enriquecer iterativamente el dataset; establecimiento de criterios de convergencia (RMSE < 3 meV/átomo) como hito de control al mes 8                                               |
| R2 | Costo computacional de los cálculos DFT superior al estimado, que exceda la capacidad del HPC disponible                 | Operativo              | Media        | Alto    | Uso paralelo de plataformas de cómputo en la nube (AWS, Google Cloud) como contingencia; priorización del espacio de candidatos mediante modelos GNN previos al cálculo DFT exhaustivo                                                          |
| R3 | Ninguna de las arquitecturas exploradas cumple simultáneamente las metas del DOE en la ventana de reversibilidad         | Técnico-científico     | Baja         | Alto    | El flujo de aprendizaje activo maximiza la probabilidad de identificar candidatos viables; el criterio de éxito mínimo se redefine como la identificación de al menos un candidato parcialmente conforme, con análisis de las brechas restantes |
| R4 | Rotación o deserción de investigadores clave (jóvenes investigadores o investigador principal) durante la ejecución      | Talento humano         | Baja         | Alto    | Documentación continua y en tiempo real de todos los procedimientos computacionales; distribución del conocimiento tácito entre al menos dos miembros del equipo para cada fase crítica                                                         |
| R5 | Retrasos en la obtención de licencias de software VASP o en el acceso a repositorios de datos (Materials Project, AFLOW) | Operativo              | Baja         | Medio   | Gestión de licencias académicas con mínimo 3 meses de anticipación; uso de alternativas de código abierto (Quantum ESPRESSO, GPAW) como contingencia técnica documentada                                                                        |
| R6 | Cambios en las condiciones de la convocatoria o retrasos en el desembolso de recursos por parte de MinCiencias           | Financiero             | Baja         | Medio   | Estructura de fases con entregables independientes que permiten continuar con cálculos de menor costo computacional mientras se resuelven contingencias administrativas; contrapartida institucional como colchón operativo                     |

La probabilidad e impacto de cada riesgo fueron evaluados cualitativamente por el equipo investigador con base en experiencia previa en proyectos de simulación computacional de materiales y en la revisión del estado del arte documentada en la sección 3.6. Ninguno de los riesgos identificados tiene carácter inmanejable: todos cuentan con medidas de mitigación técnicamente viables dentro del alcance y el presupuesto del proyecto.

### 4.12 Cronograma

El proyecto se ejecuta en un horizonte de 14 meses, estructurado en **cinco hitos secuenciales y verificables** que agrupan las actividades por su dependencia lógica y por el producto entregable que las cierra. Las actividades de apropiación social del conocimiento (ASC), formación del semillero y divulgación corren en paralelo a lo largo de todo el proyecto, dado que no dependen de los resultados computacionales intermedios.

 #### Hitos del proyecto

 
| Hito | Nombre                                                        | Meses   | Producto verificable asociado                                                                                           | OE vinculado |
| ---- | ------------------------------------------------------------- | ------- | ----------------------------------------------------------------------------------------------------------------------- | ------------ |
| H1   | Base de datos DFT consolidada y validada                      | 1 – 6   | Repositorio público con ≥ 200 configuraciones DFT en Zenodo/Materials Cloud (Producto 1)                                | OE1          |
| H2   | Modelo GNN entrenado y validado con aprendizaje activo        | 4 – 9   | Repositorio GitHub con modelo ALIGNN/CGCNN documentado, RMSE < 50 meV/átomo (Producto 2)                                | OE2          |
| H3   | NNP especializado en materiales ricos en boro operativo       | 7 – 11  | Modelo DP-GEN publicado, RMSE energías < 3 meV/átomo, fuerzas < 100 meV/Å (Producto 3)                                  | OE2          |
| H4   | Portafolio de candidatos computacionalmente validados (TRL 3) | 11 – 14 | Informe técnico con ≥ 3 candidatos validados en termodinámica, dinámica molecular y tolerancia a impurezas (Producto 4) | OE3          |
| H5   | Apropiación social, divulgación y formación completadas       | 1 – 14  | Semillero conformado, jornadas ASC realizadas, MOOC publicado, artículos sometidos (Productos 5, 6, 7 y 8)              | Transversal  |

***
#### Tabla de actividades por mes.
La siguiente tabla detalla las actividades específicas de cada hito a lo largo de los 14 meses de ejecución[^2][^3].
[^2]: ● Mes de ejecución
[^3]: ▲ Mes de entrega del producto

| Actividad                                                                                                                    | M1 | M2 | M3 | M4 | M5 | M6 | M7 | M8 | M9 | M10 | M11 | M12 | M13 | M14 |
| ---------------------------------------------------------------------------------------------------------------------------- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --- | --- | --- | --- | --- |
| HITO 1 — Base de datos DFT                                                                                                   |    |    |    |    |    |    |    |    |    |     |     |     |     |     |
| 1.1 Selección y configuración del espacio de candidatos (metalacarboranos, borofenos, hojas de boro decoradas con Sc, Ti, V) | ●  | ●  |    |    |    |    |    |    |    |     |     |     |     |     |
| 1.2 Ejecución de cálculos DFT-D3 con correcciones ZPE y fonónicas (VASP/Quantum ESPRESSO)                                    |    | ●  | ●  | ●  | ●  |    |    |    |    |     |     |     |     |     |
| 1.3 Control de calidad, validación de convergencia y depósito en repositorio abierto                                         |    |    |    |    | ●  | ▲  |    |    |    |     |     |     |     |     |
| HITO 2 — Modelo GNN con aprendizaje activo                                                                                   |    |    |    |    |    |    |    |    |    |     |     |     |     |     |
| 2.1 Diseño de la arquitectura ALIGNN/CGCNN y pipeline de aprendizaje activo                                                  |    |    |    | ●  | ●  |    |    |    |    |     |     |     |     |     |
| 2.2 Entrenamiento iterativo del modelo GNN sobre dataset DFT (bucles de aprendizaje activo)                                  |    |    |    |    | ●  | ●  | ●  | ●  |    |     |     |     |     |     |
| 2.3 Validación del modelo (RMSE, curvas de aprendizaje) y publicación en GitHub                                              |    |    |    |    |    |    |    | ●  | ▲  |     |     |     |     |     |
| HITO 3 — NNP especializado                                                                                                   |    |    |    |    |    |    |    |    |    |     |     |     |     |     |
| 3.1 Generación de configuraciones AIMD a alta temperatura para enriquecimiento del dataset                                   |    |    |    |    |    |    | ●  | ●  |    |     |     |     |     |     |
| 3.2 Entrenamiento del NNP con plataforma DP-GEN (aprendizaje concurrente)                                                    |    |    |    |    |    |    |    | ●  | ●  | ●   |     |     |     |     |
| 3.3 Validación del NNP (RMSE energías y fuerzas) y publicación con documentación técnica                                     |    |    |    |    |    |    |    |    |    | ●   | ▲   |     |     |     |
| HITO 4 — Portafolio de candidatos TRL 3                                                                                      |    |    |    |    |    |    |    |    |    |     |     |     |     |     |
| 4.1 Simulaciones de dinámica molecular NVT a 300 K (escala nanosegundos) sobre candidatos preseleccionados                   |    |    |    |    |    |    |    |    |    |     | ●   | ●   |     |     |
| 4.2 Análisis de selectividad competitiva frente a impurezas (O₂, H₂O) y validación fonónica                                  |    |    |    |    |    |    |    |    |    |     | ●   | ●   |     |     |
| 4.3 Elaboración del informe técnico del portafolio y evaluación de patentabilidad                                            |    |    |    |    |    |    |    |    |    |     |     | ●   | ●   | ▲   |
| HITO 5 — ASC, Divulgación y Formación (transversal)                                                                          |    |    |    |    |    |    |    |    |    |     |     |     |     |     |
| 5.1 Vinculación del semillero de investigación previamente constituido a las actividades computacionales del proyecto (entrega de plan de trabajo del semillero al mes 1)                                                           | ▲  |    |    |    |    |    |    |    |    |     |     |     |     |     |
| 5.2 Jornadas de diálogo de saberes con organización comunitaria (2 jornadas)                                                 |    |    | ●  |    |    |    |    |    |    | ●   |     |     |     |     |
| 5.3 Desarrollo y publicación del MOOC sobre hidrógeno verde e IA                                                             |    |    |    | ●  | ●  | ●  | ●  | ●  | ●  |     |     |     |     |     |
| 5.4 Producción de campaña digital y pósteres de divulgación                                                                  |    |    |    |    |    |    | ●  | ●  | ●  |     |     |     |     |     |
| 5.5 Redacción y sometimiento de artículos científicos (≥ 2)                                                                  |    |    |    |    |    |    |    |    |    | ●   | ●   | ●   | ●   | ▲   |
| 5.6 Registro de software ante la DNDA                                                                                        |    |    |    |    |    |    |    |    |    |     | ●   | ▲   |     |     |
| 5.7 Taller técnico de transferencia a grupos nacionales                                                                      |    |    |    |    |    |    |    |    |    |     |     |     | ●   |     |
| 5.8 Reunión de transferencia con sector productivo y entrega de hoja de ruta experimental                                    |    |    |    |    |    |    |    |    |    |     |     |     | ●   | ▲   |

### 4.13 Bibliografía

#### Referencias Científicas.
Akbarzadeh, A.R., Vrinceanu, D., & Tymczak, C.J. (2015). Metalloboranes from first-principles calculations: A candidate for high-density hydrogen storage. arXiv: Materials Science. https://api.semanticscholar.org/CorpusID:53975761

Ahmad, S., & Bora, A. (2021). Hydrogen storage on boron clusters: A density functional theory study. International Journal of Hydrogen Energy, 46(56), 28545–28555. https://doi.org/10.1016/j.ijhydene.2021.04.206

Assfour, B., & Seifert, G. (2010). Hydrogen adsorption sites in zeolite imidazolate frameworks ZIF-4 and ZIF-8. Microporous and Mesoporous Materials, 133(1–3), 59–65. https://doi.org/10.1016/j.micromeso.2010.04.008

Beyazit, S. (2025). Comparative study of hydrogen storage and metal hydride systems: Future energy storage solutions [Artículo de revisión]. Indexado en la base de datos vectorial del proyecto.

Comanescu, C. (2022). Complex metal borohydrides: From laboratory oddities to prime candidates in energy storage applications. Materials, 15(7), 2286. https://doi.org/10.3390/ma15072286

Garberoglio, G., Skoulidas, A.I., & Johnson, J.K. (2005). Adsorption of gases in metal organic materials: Comparison of simulations and experiments. The Journal of Physical Chemistry B, 109(27), 13094–13103. https://doi.org/10.1021/jp0509481

Huang, X., Wang, Z., Ren, Z., Zhang, X., & Li, W. (2021). Hydrogen storage on transition metal decorated boron clusters: A DFT study. Applied Surface Science, 560, 149270. https://doi.org/10.1016/j.apsusc.2021.149270

Jaiswal, A., Chakraborty, B., & Sahu, S. (2022). High capacity reversible hydrogen storage in Si substituted and Li decorated C₂₀ fullerene. International Journal of Energy Research, 46(13), 19521–19537. https://doi.org/10.1002/er.8524

Jason, J.I., Wang, Z., Tian, Y., Zhang, C., Huang, X., & Zhang, S. (2023). Defects induced metallized boron hydride monolayers as high-performance hydrogen storage architecture. International Journal of Hydrogen Energy, 50, 455–467. https://doi.org/10.1016/j.ijhydene.2023.07.099

Kalibek, N., Orynbayev, M.R., Dosanova, A., Sultanova, B., Serikbay, R., Omarova, T., & Mukhtarova, A.M. (2024). Solid-state hydrogen storage materials. Applied Physics A, 130, 598. https://doi.org/10.1007/s00339-024-07741-4

Klontzas, E., Mavrandonakis, A., Tylianakis, E., & Froudakis, G.E. (2008). Improving hydrogen storage capacity of MOF by functionalization of the organic linker with lithium atoms. Nano Letters, 8(6), 1572–1576. https://doi.org/10.1021/nl072941g

Mahamiya, V., Shukla, A., & Chakraborty, B. (2022). Exploring 3d transition metal decorated C₂₄ fullerene as high capacity reversible hydrogen storage materials with Kubas interaction. Journal of Alloys and Compounds, 897, 163072. https://doi.org/10.1016/j.jallcom.2021.163072

Olalde-López, D., Rodríguez-Kessler, P.L., Rodríguez-Carrera, S., & Muñoz-Castro, A. (2024). Hydrogen storage properties for bimetallic doped boron clusters M₂Br (M = Fe, Co, Ni). International Journal of Hydrogen Energy, 49, 1678–1691. https://doi.org/10.1016/j.ijhydene.2023.09.020

Osman, A.I., Mehta, N., Elgarahy, A.M., Al-Fatesh, A.S., Rooney, D.W., & El-Monaem, E.M.A. (2024). Enhanced hydrogen storage efficiency with sorbents and machine learning: A review. International Journal of Hydrogen Energy, 52, 24–48. https://doi.org/10.1016/j.ijhydene.2023.06.218

Paul, S., Bhatt, M.D., & Bhobe, P.A. (2023). Hydrogen storage capacity of yttrium-doped C₃₀ fullerene using density functional theory simulations. International Journal of Hydrogen Energy, 48(41), 15505–15515. https://doi.org/10.1016/j.ijhydene.2023.01.085

Pupysheva, O.V., Farajian, A.A., & Yakobson, B.I. (2008). Fullerene nanocage capacity for hydrogen storage. Nano Letters, 8(3), 767–774. https://doi.org/10.1021/nl071436g

Ray, S., Sahoo, R.K., & Sahu, S. (2021). High-capacity reversible hydrogen storage in Ti/Sc decorated metallacarborane systems: A first-principles study [Preprint]. Research Square. https://doi.org/10.21203/rs.3.rs-671186/v1

Sahoo, R.K., Chakraborty, B., & Sahu, S. (2021). Reversible hydrogen storage on alkali metal (Li and Na) decorated C₂₀ fullerene: A density functional study. International Journal of Hydrogen Energy, 46(79), 40251–40261. https://doi.org/10.1016/j.ijhydene.2021.09.204

Sahoo, R.K., & Sahu, S. (2022). Reversible hydrogen storage capacity of Li and Sc doped novel C₈N₈ cage: Insights from density functional theory. International Journal of Energy Research, 46, 19538–19551. https://doi.org/10.1002/er.8562

Samantaray, S.S., Tekale, S.T., Philipose, U., Bhargava, P., & Stadie, N.P. (2021). Volumetrics of hydrogen storage by physical adsorption. Inorganics, 9(7), 45. https://doi.org/10.3390/inorganics9070045

Scheifers, J.P., Zhang, Y., & Fokwa, B.P.T. (2017). Boron: Enabling exciting metal-rich structures and magnetic properties. Accounts of Chemical Research, 50(9), 2317–2325. https://doi.org/10.1021/acs.accounts.7b00268

Singh, A.K., Sadrzadeh, A., & Yakobson, B.I. (2010). Metallacarboranes: Toward promising hydrogen storage metal-organic framework materials. Journal of the American Chemical Society, 132(40), 14126–14129. https://doi.org/10.1021/ja104544s

Vaidyanathan, A., Kandasamy, M., Ramaniah, L.M., Ghosh, S.K., & Chakrabarti, A. (2024). Hydrogen storage in Sc-decorated ψ-graphene via density functional theory simulations. International Journal of Hydrogen Energy, 52, 376–389. https://doi.org/10.1016/j.ijhydene.2023.08.356

Yildirim, T., & Ciraci, S. (2005). Titanium-decorated carbon nanotubes as a potential high-capacity hydrogen storage medium. Physical Review Letters, 94(17), 175501. https://doi.org/10.1103/PhysRevLett.94.175501

Yoon, M., Yang, S., Hicke, C., Wang, E., Geohegan, D., & Zhang, Z. (2007). Calcium as the superior coating metal in functionalization of carbon fullerenes for high-capacity hydrogen storage. Physical Review Letters, 100(20), 206806. https://doi.org/10.1103/PhysRevLett.100.206806

Zhang, X., & Cheng, D. (2018). Alkali and alkaline-earth metal atoms attached to C₂₄ fullerene for hydrogen storage. International Journal of Hydrogen Energy, 43(15), 7592–7601. https://doi.org/10.1016/j.ijhydene.2018.02.175

---

#### Bibliografía Normativa.
Departamento Nacional de Planeación (DNP). (2021). Metodología General Ajustada (MGA) para la formulación y evaluación de proyectos de inversión pública. DNP. https://www.dnp.gov.co

Ministerio de Ciencia, Tecnología e Innovación (MinCiencias). (2026). Términos de referencia — Convocatoria Colombia Inteligente 2026. MinCiencias. https://minciencias.gov.co/convocatorias/convocatoria-colombia-inteligente-2026

Ministerio de Ciencia, Tecnología e Innovación (MinCiencias). (2026). Anexo 1: Carta unificada de aval y compromiso institucional. MinCiencias.

Ministerio de Ciencia, Tecnología e Innovación (MinCiencias). (2026). Anexo 6: Contenido técnico de la propuesta del proyecto. MinCiencias.

Ministerio de Ciencia, Tecnología e Innovación (MinCiencias). (2026). Anexo 7: Rubros financiables. MinCiencias.

Ministerio de Ciencia, Tecnología e Innovación (MinCiencias). (2026). Anexo 8: Apropiación social y divulgación de la ciencia. MinCiencias.

U.S. Department of Energy (DOE). (2020). DOE technical targets for onboard hydrogen storage for light-duty vehicles. Office of Energy Efficiency & Renewable Energy. https://www.energy.gov/eere/fuelcells/doe-technical-targets-onboard-hydrogen-storage-light-duty-vehicles


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
