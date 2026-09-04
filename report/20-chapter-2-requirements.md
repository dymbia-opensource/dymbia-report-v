# Capítulo II: Requirements Elicitation & Analysis

En el presente capítulo, el equipo se dedica a investigar y comprender a fondo el contexto operativo y las carencias del sector agroalimentario antes de iniciar el desarrollo tecnológico. Más allá de definir un listado de características del software, aplicamos un riguroso proceso de educción y análisis de requisitos. Esta fase es fundamental para comprobar empíricamente que las problemáticas que SumaqAgro pretende solucionar tienen un impacto genuino en la rentabilidad y gestión diaria de los agricultores y cooperativas peruanas.

## 2.1. Competidores
### 2.1.1. Análisis competitivo

Para asegurar una captura de datos estructurada y de alto valor, se han elaborado guías de indagación personalizadas para cada uno de nuestros segmentos de mercado. Estos instrumentos de investigación están diseñados para descubrir no solo el perfil demográfico, sino también el nivel de madurez digital y los cuellos de botella que enfrentan los usuarios en la actualidad. Previo a la presentación de estas entrevistas, detallamos el panorama competitivo (Landscape) que valida la viabilidad y diferenciación estratégica de SumaqAgro en el ecosistema AgTech.


<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto; font-family: sans-serif; width: 100%;">
  <tr>
    <th colspan="6" style="text-align: center; font-size: 1.2em;">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2" style="width: 20%;"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="4">¿Cómo se posiciona SumaqAgro frente a sus competidores en cuanto a propuesta de valor, marketing, producto y estrategia?</td>
  </tr>
  <tr>
    <td colspan="4">Es un análisis comparativo que permite identificar fortalezas, debilidades, oportunidades y amenazas, así como entender mejor la posición del producto frente a otros actores relevantes del mercado agrotecnológico.</td>
  </tr>
  <tr>
    <td colspan="2" style="text-align: center;"><b>Competidores</b></td>
    <td style="text-align: center; vertical-align: middle; width: 20%;">
      <b style="display: block; margin-bottom: 6px;">SumaqAgro</b>
      <img src="../assets/img/chapter-II/sumaqagro-logo-chapter2.png" alt="SumaqAgro" width="100"/>
    </td>
    <td style="text-align: center; vertical-align: middle; width: 20%;">
      <b style="display: block; margin-bottom: 6px;">SpaceAG</b>
      <img src="../assets/img/chapter-II/spaceag-logo-chapter2.png" alt="SpaceAG" width="100"/>
    </td>
    <td style="text-align: center; vertical-align: middle; width: 20%;">
      <b style="display: block; margin-bottom: 6px;">Kilimo</b>
      <img src="../assets/img/chapter-II/kilimo-logo-chapter2.png" alt="Kilimo" width="100"/>
    </td>
    <td style="text-align: center; vertical-align: middle; width: 20%;">
      <b style="display: block; margin-bottom: 6px;">Auravant</b>
      <img src="../assets/img/chapter-II/auravant-logo-chapter2.png" alt="Auravant" width="100"/>
    </td>
  </tr>
  <tr>
    <td rowspan="2" style="writing-mode: vertical-lr; transform: rotate(180deg); text-align: center; font-weight: bold;">Perfil</td>
    <td><b>Overview</b></td>
    <td>Plataforma Web (Software-only Precision Ag) enfocada en gestión agrícola, monitoreo y calidad digital.</td>
    <td>Solución de Drone & Satellite Analytics centrada en el análisis avanzado de rendimiento.</td>
    <td>Plataforma SaaS de Water Management especializada en la gestión y ahorro de agua.</td>
    <td>Digital Agronomy Ecosystem altamente modular y configurable para agricultura de precisión.</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva</b></td>
    <td>Monitoreo satelital (NDVI/humedad) libre de sensores físicos en campo, integrando cálculo de costos unitarios y certificación digital de calidad.</td>
    <td>Monitoreo premium de ultra alta resolución (imágenes satelitales + ortofotos por drones) con inteligencia artificial.</td>
    <td>Algoritmos propietarios de balance hídrico que calculan evapotranspiración y monetizan el ahorro de agua.</td>
    <td>Ecosistema abierto con soporte para múltiples capas de información, maquinaria e integraciones de terceros.</td>
  </tr>
  <tr>
    <td rowspan="2" style="writing-mode: vertical-lr; transform: rotate(180deg); text-align: center; font-weight: bold;">Perfil de Marketing</td>
    <td><b>Mercado objetivo</b></td>
    <td>Pequeños/medianos agricultores (papa/café), cooperativas y asesores técnicos independientes en Perú.</td>
    <td>Medianas y grandes corporaciones agroexportadoras de alto valor (arándanos, uva) en la costa peruana.</td>
    <td>Productores medianos/grandes con sistemas de riego tecnificado en regiones con estrés hídrico.</td>
    <td>Empresas agropecuarias de escala extensiva, asesores agronómicos y distribuidores de agroquímicos.</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>Penetración B2B2C mediante cooperativas, modelo freemium accesible y alianzas con ONGs de desarrollo rural.</td>
    <td>Ventas B2B corporativas, demostraciones piloto en fundos industriales y presencia en congresos exportadores.</td>
    <td>Programas ESG, marketing de contenidos sobre huella hídrica y alianzas con corporaciones globales.</td>
    <td>Autoservicio SaaS, seminarios web técnicos, certificaciones gratuitas y convenios con marcas de maquinaria.</td>
  </tr>
  <tr>
    <td rowspan="3" style="writing-mode: vertical-lr; transform: rotate(180deg); text-align: center; font-weight: bold;">Perfil de Producto</td>
    <td><b>Productos & Servicios</b></td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Índices NDVI/humedad satelital</li>
        <li>Motor de costos por lote</li>
        <li>Certificados de calidad digital</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Vuelos programados con drones</li>
        <li>Conteo de plantas con IA</li>
        <li>Gestión de personal de cosecha</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Recomendaciones de riego</li>
        <li>Auditoría de ahorro de agua</li>
        <li>Reporte de huella hídrica</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Prescripción variable</li>
        <li>Integración con maquinaria</li>
        <li>Monitoreo satelital multibanda</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Precios & Costos</b></td>
    <td>Modelo Freemium: Nivel gratuito para pequeños productores y planes escalonados para cooperativas.</td>
    <td>Contratos Enterprise de alto costo (miles de dólares), inaccesibles para el pequeño productor familiar.</td>
    <td>SaaS por hectárea. Requiere riego tecnificado para justificar el retorno de inversión.</td>
    <td>Planes Freemium limitados con saltos agresivos a tiers Premium corporativos por volumen.</td>
  </tr>
  <tr>
    <td><b>Canales de distribución</b></td>
    <td>Plataforma Web responsiva (Angular) optimizada para conexiones móviles 3G/4G rurales.</td>
    <td>App Web de escritorio y Aplicación Móvil nativa para hardware de gama alta.</td>
    <td>App Web y App Móvil de consulta rápida en campo para operarios de riego.</td>
    <td>Plataforma Web integral y Aplicación Móvil multiplataforma para registro de muestras.</td>
  </tr>
  <tr>
    <td rowspan="5" style="writing-mode: vertical-lr; transform: rotate(180deg); text-align: center; font-weight: bold;">Análisis SWOT</td>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Sin hardware (100% software).</li>
        <li>Integra analítica, costos y calidad.</li>
        <li>Especialización en papa andina y café.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Alta resolución con drones.</li>
        <li>Liderazgo en sector exportador costero.</li>
        <li>Fuerza de ventas B2B corporativa.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Monetización por bonos de carbono.</li>
        <li>Plataforma técnica muy madura.</li>
        <li>Especialización total en recurso hídrico.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Alta escalabilidad internacional.</li>
        <li>Ecosistema modular mediante Add-ons.</li>
        <li>Robusta integración con hardware/tractores.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Startup nueva en el mercado.</li>
        <li>Dependencia de APIs satelitales externas.</li>
        <li>Ausencia de app móvil nativa (Sprint 1).</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Costos insostenibles para la pequeña escala.</li>
        <li>Ausencia de control financiero/costos.</li>
        <li>Rigidez operativa en sierra/selva.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Inútil en agricultura de secano (sin riego).</li>
        <li>Ignora el factor fitosanitario/plagas.</li>
        <li>Precios prohibitivos para minifundios.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Curva de aprendizaje compleja/técnica.</li>
        <li>Baja adecuación a micro-parcelas.</li>
        <li>Sin contabilidad financiera de costos.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>96% de productores sin asistencia formal.</li>
        <li>Normativa de trazabilidad de la UE.</li>
        <li>Creciente conectividad rural.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Venta de big data a aseguradoras.</li>
        <li>Expansión a corporaciones regionales.</li>
        <li>Integración con robótica agrícola.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Crisis climática y escasez de agua.</li>
        <li>Financiamiento ESG corporativo.</li>
        <li>Nuevos bonos de sostenibilidad global.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Socio técnico de marcas de tractores.</li>
        <li>Alineamiento con catastro público.</li>
        <li>Modelo "marca blanca" para agrónomos.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Fuerte resistencia al cambio digital.</li>
        <li>Extrema nubosidad en la sierra que limite visión de satélites.</li>
        <li>Clonación de modelo por empresas grandes.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Crisis de precios en la agroexportación.</li>
        <li>Regulaciones estrictas de vuelo de drones.</li>
        <li>Saturación del mercado corporativo.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Precipitaciones excesivas temporales.</li>
        <li>Sensores físicos IoT a precios de dumping.</li>
        <li>Caída en cotización de bonos hídricos.</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding-left: 15px;">
        <li>Competencia de gigantes (Bayer FieldView).</li>
        <li>Interrupciones en constelaciones satelitales gratuitas.</li>
      </ul>
    </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Una vez identificados los actores del mercado, el siguiente paso es definir cómo SumaqAgro se abrirá paso entre ellos. No basta con conocer a la competencia; necesitamos un plan de acción que aproveche nuestras ventajas y blinde nuestras debilidades. Para lograrlo, utilizamos la Matriz CAME, una herramienta que nos permite "traducir" el análisis FODA previo en decisiones estratégicas reales.

A través de este análisis, establecemos tácticas ofensivas para explotar nuestra especialización en el mercado peruano agro-exportador (papa y café), y acciones de supervivencia para mitigar los riesgos de ser una startup emergente. Este enfoque asegura que cada funcionalidad que codifiquemos cumpla un propósito estratégico en el mercado.

**Matriz CAME para el desarrollo de estrategias basándonos en el análisis FODA**

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse; font-family: sans-serif;">
  <tr>
    <th style="text-align: left; width: 30%;">Análisis FODA cruzado</th>
    <th style="text-align: left; width: 35%;">Oportunidades (O)</th>
    <th style="text-align: left; width: 35%;">Amenazas (A)</th>
  </tr>
  <tr>
    <td>
      <b>Fortalezas (F)</b><br><br>
      1. Independencia total de hardware en campo (software-only).<br>
      2. Plataforma unificada: analítica satelital, costos por lote y certificación en una sola herramienta.<br>
      3. Arquitectura web ligera optimizada para zonas de baja conectividad (3G).<br>
      4. Localización absoluta orientada al productor andino (papa) y de selva alta (café).
    </td>
    <td>
      <b>Estrategia (FO) — Estrategias Ofensivas</b><br><br>
      1. Promover el generador de certificados digitales de calidad como la solución accesible para cumplir con las nuevas normativas de trazabilidad exportadora de la UE (F2, O2).<br>
      2. Afianzar el modelo de distribución B2B2C vendiendo el motor de costos a directivos de cooperativas, capturando masivamente a agricultores desatendidos técnicamente (F1, O4).<br>
      3. Ejecutar campañas de marketing resaltando la ligereza de la web app frente a las plataformas de la competencia, que requieren descargas pesadas o computadoras de gama alta (F3, O3).
    </td>
    <td>
      <b>Estrategia (FA) — Estrategias Defensivas</b><br><br>
      1. Desplegar agresivamente el plan Freemium, permitiendo usar el satélite sin costo para 1 lote, derribando la barrera de desconfianza y resistencia al cambio rural (F1, A1).<br>
      2. Reforzar la propuesta de valor centrada en parámetros ultra-locales (alertas de gorgojo/roya, calibres del MIDAGRI) para blindar el mercado frente a la llegada de plataformas internacionales genéricas (F4, A3).<br>
      3. Implementar un módulo educativo offline en la app para capacitar sobre el valor real de digitalizar los cuadernos de campo (F2, A1).
    </td>
  </tr>
  <tr>
    <td>
      <b>Debilidades (D)</b><br><br>
      1. Marca emergente con presupuesto comercial limitado frente a transnacionales.<br>
      2. Dependencia tecnológica de APIs satelitales externas.<br>
      3. Ausencia de aplicación móvil nativa (solo web responsiva en etapas iniciales).<br>
      4. Brecha inicial de datos históricos del cultivo.
    </td>
    <td>
      <b>Estrategia (DO) — Reorientación</b><br><br>
      1. Aprovechar a las cooperativas agrícolas como un "caballo de Troya" comercial para diluir el costo de adquisición de usuarios individuales, compensando el bajo presupuesto de marketing (D1, O4).<br>
      2. Mitigar la falta de aplicación nativa implementando tecnologías de almacenamiento en caché en la Web App (Angular), permitiendo registro de jornales offline en la sierra (D3, O3).<br>
      3. Utilizar las pruebas Lean UX tempranas para generar casos de éxito y testimonios publicables que doten de autoridad y validen la herramienta frente a nuevos socios (D1, O1).
    </td>
    <td>
      <b>Estrategia (DA) — Supervivencia</b><br><br>
      1. Diseñar el backend (Spring Boot) con un patrón de adaptador (Adapter Pattern) que soporte a múltiples proveedores de imágenes satelitales como respaldo (fallback) en caso de que una API externa falle o cambie su política gratuita (D2, A4).<br>
      2. Proteger agresivamente el núcleo financiero (motor de costos) como propuesta irreemplazable, ya que incluso si hay nubosidad severa que bloquee satélites, el productor siga dependiendo de la contabilidad (D2, A2).<br>
      3. Evitar entrar a una guerra de precios directos. Posicionar la plataforma exclusivamente por su valor integrado hasta ganar madurez de datos e ingresos (D1, A3).
    </td>
  </tr>
</table>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
Para garantizar un proceso de investigación de usuarios (*User Research*) riguroso y estructurado, hemos diseñado guías de entrevista semiestructuradas divididas en dos grandes bloques. El primero recopila datos demográficos y de contexto digital aplicables a cualquier entrevistado; el segundo aborda preguntas específicas y profundas adaptadas a los dolores, responsabilidades y dinámicas operativas de cada segmento objetivo.

#### Bloque 1: Preguntas Generales 

Este cuestionario inicial estandariza la recolección de metadatos demográficos clave y evalúa la madurez digital base de los usuarios en su entorno habitual:
1. **Identificación básica:** ¿Cuál es su nombre completo, su edad y a qué se dedica principalmente en el día a día?
2. **Contexto geográfico:** ¿En qué distrito o localidad vive actualmente, y en qué zonas específicas se encuentran sus campos de cultivo u oficinas administrativas?
3. **Trayectoria:** ¿Cuántos años de experiencia tiene trabajando en el sector agrícola (ya sea en campo, gestión o asesoría)?
4. **Acceso tecnológico:** ¿Qué tipo de teléfono celular utiliza diariamente (marca/gama) y qué aplicaciones (como WhatsApp, Facebook, banca móvil) abre con mayor frecuencia?
5. **Conectividad en campo:** ¿Cómo describiría la señal de internet o datos móviles cuando se encuentra trabajando en sus parcelas o rutas habituales?


#### Bloque 2: Preguntas Específicas por Segmento Objetivo

#### 1. Pequeños y medianos agricultores independientes de papa y café:
- ¿Cómo decide qué precio inicial pedir por su cosecha antes de negociar con el acopiador o intermediario?
- ¿Alguna vez ha perdido gran parte de su cultivo por una helada o sequía, y cómo calculó la cantidad exacta de dinero que perdió?
- ¿Qué tan seguido tiene señal estable de internet o datos en su teléfono móvil mientras se encuentra trabajando dentro de su parcela?
- Si una herramienta en su celular le enviara alertas sobre su cultivo, ¿la utilizaría usted mismo o dependería de un familiar más joven para revisarla?
- ¿De dónde obtiene normalmente el financiamiento o los préstamos para comprar los fertilizantes al inicio de la campaña?


#### 2. Productores organizados y directivos de cooperativas agrícolas:
- ¿Qué canales o métodos utilizan actualmente para advertir de forma masiva y rápida a todos sus socios cuando hay una amenaza climática regional?
- ¿Cómo incentivan o penalizan económicamente a los productores basándose en la evaluación de calidad (calibre o perfil de taza) al momento del acopio?
- ¿Cuál consideran que es la mayor barrera (cultural, económica o de infraestructura) para que sus socios dejen de usar papel y adopten registros digitales?
- ¿Qué porcentaje de sus exportaciones o ventas mayoristas ha sido rechazado o castigado en precio en el último año debido a problemas de trazabilidad?
- ¿Estaría la cooperativa dispuesta a asumir el costo de una plataforma tecnológica si esta garantiza reducir el tiempo de las auditorías de certificación?

#### 3. Ingenieros agrónomos y asesores técnicos de campo:
- ¿Cuál es el límite máximo de hectáreas o productores que un solo asesor puede supervisar eficientemente con los métodos tradicionales actuales?
- ¿Qué aplicaciones genéricas (WhatsApp, Excel, Google Maps) o herramientas digitales utiliza hoy en día para intentar organizar y documentar su trabajo diario?
- ¿Cómo reporta o demuestra a la gerencia de la cooperativa que sus visitas preventivas realmente salvaron parte del rendimiento de un lote?
- ¿Qué recomendación técnica o de manejo de plagas le resulta más difícil que el agricultor empírico aplique correctamente?
- Cuando visita un campo después de un evento climático extremo, ¿cómo estima visualmente el porcentaje de daño o estrés hídrico para emitir un informe?

### 2.2.2. Registro de entrevistas

**Segmento 1: Pequeños y medianos agricultores independientes de papa y café**

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #1</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #2</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #3</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

**Segmento 2:  Productores organizados y directivos de cooperativas agrícolas**

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #1</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #2</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #3</th></tr>
  <tr><td>Nombre</td><td>  </td></tr>
  <tr><td>Apellidos</td><td>  </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-foto" alt="Entrevista - nombre" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td> .<br><br>
  <b>Comportamiento y necesidades:</b>
   .<br><br>
  <b>Tecnología, marcas y canales:</b>
   .</td></tr>
</table>

**Segmento 3: Ingenieros agrónomos y asesores técnicos de campo**

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #1</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #2</th></tr>
  <tr><td>Nombre</td><td> name </td></tr>
  <tr><td>Apellidos</td><td> apellido </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-02-nombre" alt="Entrevista - name" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td>  .<br><br>
  <b>Comportamiento y necesidades:</b>
  .<br><br>
  <b>Tecnología, marcas y canales:</b>
  .</td></tr>
</table>

<table border="1" cellpadding="8" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <tr><th colspan="2" style="text-align: left;">Entrevista #3</th></tr>
  <tr><td>Nombre</td><td>  </td></tr>
  <tr><td>Apellidos</td><td>  </td></tr>
  <tr><td>Edad</td><td>  </td></tr>
  <tr><td>Distrito</td><td> distrito </td></tr>
  <tr><td>Evidencia</td><td><img src="../assets/img/chapter-II/interview-segment-two-foto" alt="Entrevista - nombre" width="420"/></td></tr>
  <tr><td>Link</td><td> link </td></tr>
  <tr><td>Timing donde inicia la entrevista</td><td> min</td></tr>
  <tr><td>Duración de la entrevista</td><td> min</td></tr>
  <tr><td>Resumen</td><td> .<br><br>
  <b>Comportamiento y necesidades:</b>
   .<br><br>
  <b>Tecnología, marcas y canales:</b>
   .</td></tr>
</table>

### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture Event Storming

## 2.5. Ubiquitous Language