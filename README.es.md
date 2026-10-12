# Awesome Translation Tools

> Un directorio curado de herramientas y flujos de trabajo de traducción que abarca viajes, lectura web, documentos formateados, investigación académica, motores locales de código abierto y canalizaciones para desarrolladores.

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

Las tareas de traducción difieren fundamentalmente según el contexto: descifrar una señal de tráfico o un menú en un teléfono móvil, leer documentación extranjera dentro del navegador, traducir presentaciones complejas y contratos sin alterar el diseño visual, conservar fórmulas matemáticas en artículos académicos, ejecutar traducciones privadas por lotes en un terminal o seguir transmisiones de video sin subtítulos.

Somos el equipo de **Equalang**. Este directorio ofrece un catálogo práctico y orientado a tareas de productos de traducción consolidados y proyectos de código abierto. Para cada herramienta, resumimos las funciones documentadas, los puntos de acceso, los modos de despliegue y las restricciones operativas con el fin de ayudarte a identificar la solución adecuada para tu flujo de trabajo.

---

<a id="contents"></a>
## Contenido

- [1. Viajes y comunicación sobre la marcha: Entradas multimodales y voz](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. Lectura web contextual y aprendizaje de idiomas: Leer sin salir de la página](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. Diseños complejos de documentos y flujos empresariales: Preservación de formatos y recursos](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. Redacción académica, perfeccionamiento y colaboración persona-máquina: Pulido del resultado final](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. Ecosistema de código abierto: Motores locales, API, clientes de escritorio y procesamiento de PDF científicos](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 Procesamiento de PDF científicos y académicos](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 Motores autoalojables y API](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 Interfaces de escritorio y terminal](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. Flujos de trabajo integrados de extremo a extremo: Equalang](#6-connected-end-to-end-workflows-equalang)
  - [1. Traducción de documentos completos con preservación del diseño](#1-whole-file-document-translation-with-layout-preservation)
  - [2. Lectura en el navegador y generación de subtítulos](#2-in-browser-reading--subtitle-generation)
  - [3. Comunicación por voz e intercambios in situ sin instalación](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. Integración para agentes de IA y desarrolladores](#4-integration-for-ai-agents-and-developers)
- [7. Guía de decisión orientada a tareas](#7-task-based-decision-guide)
- [8. Principios del directorio y criterios de verificación](#8-directory-principles--verification-criteria)
- [9. Fuentes](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>
## 1. Viajes y comunicación sobre la marcha: Entradas multimodales y voz

Los viajes y el trabajo de campo exigen una activación rápida, un reconocimiento multimodal fiable y disponibilidad sin conexión cuando la conectividad de red es limitada.

<a id="google-translate"></a>
### Google Translate
[Google Translate en dispositivos móviles](https://support.google.com/translate) integra OCR instantáneo mediante cámara, importación de fotos, entrada manuscrita y conversación cara a cara en pantalla dividida. Los viajeros pueden descargar paquetes de idiomas con anticipación para realizar traducciones de texto y traducciones mediante cámara sin conexión. La traducción de conversaciones habladas incluye múltiples disposiciones de pantalla, aunque la interpretación de voz en directo y sin conexión está limitada a dispositivos Pixel específicos y pares de idiomas seleccionados.

En los navegadores de escritorio, Google Translate ofrece un [portal dedicado a la traducción de documentos](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en) que admite archivos DOCX, PDF, PPTX y XLSX. Esta herramienta de escritorio está diseñada para archivos digitales; las páginas de PDF escaneados que contienen imágenes puras se conservan en el archivo descargado sin traducción por OCR.

<p align="center"><img src="assets/google-page@2x.webp" alt="Página oficial de descripción del producto Google Translate" width="640"><br><sub>Página oficial de descripción general del producto Google Translate y sección de descarga de la aplicación móvil</sub></p>

<a id="apple-translate"></a>
### Apple Translate
Para los usuarios de iPhone y iPad, la aplicación a nivel de sistema [Apple Translate](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios) no requiere ninguna instalación independiente. Gestiona texto escrito, entrada de voz, detección de texto con la cámara y conversación cara a cara en pantalla dividida. Su modo de conversación puede detectar automáticamente qué idioma se está hablando, eliminando la necesidad de cambiar manualmente el micrófono entre los interlocutores. Los paquetes de idiomas descargados permiten realizar consultas de texto en el propio dispositivo sin necesidad de conexión móvil.

Dentro del sistema operativo de Apple, las [funciones de traducción en directo](https://support.apple.com/en-us/123720) también se extienden a Mensajes, Teléfono y FaceTime. La traducción de llamadas telefónicas en directo forma parte de Apple Intelligence, requiere hardware y versiones de sistema compatibles, y está sujeta a normativas de disponibilidad regional (por ejemplo, los dispositivos adquiridos en China continental no admiten actualmente estas funciones avanzadas de llamadas de Apple Intelligence).

<p align="center"><img src="assets/apple-page@2x.webp" alt="Guía de soporte de Apple para traducir en iPhone" width="640"><br><sub>Página de la guía de soporte de Apple para traducir palabras y frases en iPhone</sub></p>

<a id="microsoft-translator"></a>
### Microsoft Translator
La [aplicación móvil Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/) destaca por su [función de conversación multidispositivo](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/). Un anfitrión inicia una sesión en el móvil y los participantes se unen usando la aplicación móvil o cualquier navegador web de escritorio escaneando un código QR o introduciendo un código. Cada participante recibe transcripción y traducción en directo en el idioma que elija. Su modo Presentador mantiene abierto el micrófono del anfitrión mientras silencia a los oyentes, lo cual resulta útil en visitas guiadas y conferencias.

La aplicación también incluye libros de frases descargables y traducción de fotos sin conexión para consultas frecuentes de viaje. La aplicación para usuarios individuales no admite la traducción directa de películas externas, archivos de video ni grabaciones multimedia, y las sesiones de voz multidispositivo requieren una conexión activa a internet.

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Página oficial de funciones de Microsoft Translator" width="640"><br><sub>Página de funciones de Microsoft Translator que destaca la característica de conversación multidispositivo</sub></p>

<a id="papago"></a>
### Papago
Desarrollado por NAVER en Corea del Sur, [Papago](https://papago.naver.com/) ofrece funciones prácticas para idiomas de Asia oriental como coreano, inglés, japonés y chino. En dispositivos móviles, su [aplicación](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator) proporciona diálogo cara a cara, un modo Edu para crear notas de estudio a partir de texto impreso y la ventana flotante Papago Mini, lo que resulta muy práctico para comer fuera, consultar transporte y estudiar en Corea.

En cuanto a la traducción de páginas web, los puntos de acceso disponibles difieren según la plataforma: NAVER ha descontinuado la herramienta independiente de traducción de sitios web en su portal web de escritorio, dirigiendo a los usuarios de PC a su navegador [Whale](https://whale.naver.com/) impulsado por Papago, mientras que la [aplicación móvil Papago](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE) aún conserva la opción de traducción de sitios web en su menú lateral. Cuando se descargan los paquetes de idiomas en dispositivos compatibles que cumplen los requisitos del sistema (según se detalla en la [documentación de funcionamiento sin conexión de NAVER](https://help.naver.com/service/16448/contents/10663?osType=MOBILE), que requiere al menos 4 GB de RAM y Android 14+ con paquetes de voz específicos para el habla), la traducción sin conexión admite texto y voz entre coreano, inglés, japonés y chino simplificado. Cabe destacar que el modo sin conexión no cubre OCR de fotos, modo de conversación, páginas web ni archivos de documentos.

<p align="center"><img src="assets/papago-page@2x.webp" alt="Interfaz oficial de traducción web de NAVER Papago" width="640"><br><sub>Espacio de trabajo de traducción web de NAVER Papago</sub></p>

<a id="itranslate"></a>
### iTranslate
[iTranslate](https://itranslate.com/) es reconocido por su [extensión de teclado](https://itranslate.com/features/keyboard-translations/index.html) integrada. Al redactar mensajes en WhatsApp, iMessage o correo electrónico, los usuarios pueden traducir texto directamente dentro de la interfaz del teclado, evitando cambiar constantemente entre aplicaciones separadas.

También ofrece paquetes descargables para expresiones de viaje comunes y libros de frases básicos a través de sus [herramientas sin conexión](https://itranslate.com/features/offline-translations/index.html), lo que resulta práctico para repasar frases esenciales antes de viajar. La disponibilidad de funciones varía según el sistema operativo, y las capacidades de voz sin conexión están limitadas a una lista selecta de idiomas principales.

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="Página de inicio oficial de iTranslate" width="640"><br><sub>Página de inicio de iTranslate con vistas previas de la interfaz de la aplicación móvil</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>
## 2. Lectura web contextual y aprendizaje de idiomas: Leer sin salir de la página

Al consultar artículos o documentación en lenguas extranjeras, alternar continuamente con una pestaña externa de traducción interrumpe la concentración. Las herramientas contextuales integran la traducción directamente en el entorno de lectura activo.

<a id="immersive-translate"></a>
### Immersive Translate
[Immersive Translate](https://immersivetranslate.com/) es una extensión de navegador que inserta párrafos traducidos directamente debajo del texto web original, presentando un diseño bilingüe limpio. También admite la creación de libros electrónicos EPUB bilingües, la visualización de PDF y la traducción de texto dentro de campos de entrada del navegador.

En el ámbito multimedia, Immersive Translate traduce pistas de subtítulos existentes en plataformas como YouTube y Netflix. Además, su función de [traducción de video por IA](https://immersivetranslate.com/video/ai-video-translator/) incorpora reconocimiento de voz para generar subtítulos bilingües en videos sin subtítulos en plataformas compatibles como YouTube, junto con un [portal dedicado a la traducción en directo de YouTube](https://livetranslate.immersivetranslate.com/zh-CN). La generación de subtítulos a partir de audio sin subtítulos depende de la compatibilidad del navegador, la claridad del audio y las condiciones de transmisión de la plataforma.

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Página de inicio oficial de Immersive Translate" width="640"><br><sub>Página de inicio de Immersive Translate y portal de descarga de la extensión del navegador</sub></p>

<a id="mate-translate"></a>
### Mate Translate
[Mate Translate](https://matetranslate.com/en) está diseñado para macOS, iOS y los principales navegadores de escritorio. Durante la navegación, hacer doble clic en cualquier palabra muestra una definición emergente inmediata, seleccionar texto abre traducciones contextuales rápidas, la traducción de página completa alterna entre las vistas original y traducida, y se incluye una utilidad persistente para la barra de menús de Mac.

Para quienes aprenden idiomas, Mate permite hacer clic en palabras de páginas web o en subtítulos de Netflix para guardarlas en un Phrasebook personalizado, que admite categorización a medida y exportación a CSV para su revisión externa. En navegadores de escritorio como Chrome, su extensión también permite seleccionar texto dentro del visor de PDF integrado para activar traducciones directamente.

<p align="center"><img src="assets/mate-page@2x.webp" alt="Página de inicio oficial de Mate Translate" width="640"><br><sub>Página de inicio de Mate Translate con vistas previas de la interfaz multiplataforma</sub></p>

<a id="reverso"></a>
### Reverso
Para escritores y estudiantes que desean comprobar el uso natural de las palabras, [Reverso Context](https://context.reverso.net/translation/about) proporciona pares de oraciones bilingües extraídas de películas, publicaciones internacionales y sitios web multilingües, acompañadas de tablas de conjugación verbal y recomendaciones de sinónimos. Dado que los ejemplos proceden de corpus multilingües públicos, los usuarios deben evaluar la idoneidad del contexto en borradores sensibles o formales.

Su portal de documentos, [Reverso Documents](https://www.reverso.net/documents/en), admite archivos PDF, Word, PowerPoint, Excel y determinados formatos de localización. Ofrece una interfaz de revisión segmento por segmento en el navegador donde los equipos pueden colaborar en la edición antes de descargar el archivo completado.

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Interfaz oficial de traducción de Reverso" width="640"><br><sub>Interfaz de traducción web y barra de navegación de Reverso</sub></p>

<a id="yandex-translate"></a>
### Yandex Translate
El [portal web de Yandex Translate](https://yandex.com/support/translate-desktop/en/) y sus aplicaciones móviles admiten texto, imágenes, sitios web y documentos. Su cliente de Android incluye un diccionario detallado que muestra transcripciones fonéticas, definiciones, sinónimos y flexiones morfológicas para los idiomas admitidos.

En dispositivos móviles, la aplicación para Android incluye un [diccionario sin conexión](https://yandex.ru/support/translate-app-android/en/offline-mobile) inglés-ruso preinstalado, y es posible descargar paquetes de idiomas adicionales para la traducción de texto escrito sin conexión. La interfaz de escritorio admite la carga de archivos estándar de Office y PDF. Conviene distinguir entre el servicio independiente Yandex Translate y Yandex Browser, que incorpora funciones propietarias de locución automática de video.

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Interfaz web oficial de Yandex Translate" width="640"><br><sub>Interfaz de entrada y navegación lateral de Yandex Translate</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>
## 3. Diseños complejos de documentos y flujos empresariales: Preservación de formatos y recursos

Al manejar presentaciones, contratos con proveedores o manuales técnicos, los diseños deformados exigen una notable corrección manual. Estas herramientas priorizan la preservación del diseño visual, el control terminológico y la reutilización de recursos.

<a id="deepl"></a>
### DeepL
[DeepL Translator](https://www.deepl.com/en/features) ofrece opciones de configuración detalladas para flujos de trabajo con texto y documentos. Los usuarios pueden crear [glosarios](https://www.deepl.com/en/features/glossary) para aplicar traducciones corporativas o técnicas preferidas, y alternar entre registros de tono formal e informal en los idiomas admitidos.

Su [servicio de traducción de documentos](https://www.deepl.com/en/features/document-translation) admite archivos Word, PDF, PPT, Excel, HTML y SRT (el acceso a los formatos varía según el tipo de cuenta). El ecosistema del producto también incluye DeepL Write para el pulido de textos, [DeepL Voice for Online Meetings](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings) para subtítulos en tiempo real en Teams y Zoom (requiere licencia Voice y permisos de anfitrión), y una guía oficial del Model Context Protocol (MCP) para agentes de IA.

<p align="center"><img src="assets/deepl-page@2x.webp" alt="Espacio de trabajo oficial de traducción web de DeepL" width="640"><br><sub>Interfaz del traductor web de DeepL</sub></p>

<a id="otranslator"></a>
### O.Translator
[O.Translator](https://otranslator.com/en/product-info) se enfoca en la traducción de documentos con preservación del diseño visual. Además de PDF, Word, PPT y Excel, admite formatos de publicación y localización como libros electrónicos EPUB, InDesign (IDML), Illustrator (AI), OpenDocument, archivos de subtítulos (SRT/ASS) y archivos de cómics (CBZ/CBR), con OCR integrado para páginas escaneadas. La precisión del diseño depende de las fuentes incrustadas y de la expansión del texto de destino.

Antes de traducir un archivo completo, O.Translator permite inspeccionar una vista previa parcial del diseño. Admite la importación de glosarios mediante XLSX o TBX y proporciona una [API para desarrolladores](https://www.otranslator.com/en/developer/v1). Su opción multimedia está diseñada para transcribir archivos de audio y video cargados a archivos de subtítulos, en lugar de realizar traducciones de transmisiones en tiempo real en el navegador.

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="Página de inicio oficial del producto O.Translator" width="640"><br><sub>Página de inicio de O.Translator y sección de carga de documentos</sub></p>

<a id="simplifyai"></a>
### SimplifyAI
SimplifyAI opera dos sitios web diferenciados: un [taller de documentos complejos](https://simplifyai.cn/zh/translate) (simplifyai.cn/zh) impulsado por IA y un [portal general de traducción de documentos](https://translate.simplifyai.cn/) (translate.simplifyai.cn).

Dentro del taller, el sistema puede extraer términos de alta frecuencia antes de la traducción para la revisión del usuario en archivos Word, PPTX, InDesign, PDF y EPUB. El taller también proporciona AI Editing para Word e InDesign (con soporte nativo para el control de cambios de Word), exportación de datos bilingües (Excel/XLIFF), extracción estructurada en Markdown/JSON y verificaciones visuales de desbordamiento de texto y disposición tipográfica, lo que lo hace muy adecuado para la localización de materiales de preimpresión y diseño. Para la traducción directa de archivos cotidianos, el portal general ofrece un flujo más simple.

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="Página de inicio oficial de SimplifyAI" width="640"><br><sub>Página de inicio de SimplifyAI que muestra su taller de documentos complejos y sus módulos</sub></p>

<a id="lingvanex"></a>
### Lingvanex
[Lingvanex](https://lingvanex.com/) proporciona clientes de escritorio, móviles y de navegador para Windows y macOS. Su [traductor de escritorio para Windows](https://lingvanex.com/products/windows-translator/) admite atajos globales a nivel de sistema (como pulsar dos veces Ctrl+C sobre texto resaltado) y permite la traducción de texto sin conexión y archivos locales DOCX/ODT tras descargar los paquetes de idiomas.

Más allá de las aplicaciones de consumo, Lingvanex ofrece software de escritorio descargable [Secure Translation Software](https://lingvanex.com/products/secure-translation-software/) para uso corporativo sin conexión, así como soluciones independientes On-premise Machine Translation para entornos de red privada.

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Página de inicio oficial de Lingvanex" width="640"><br><sub>Página de inicio de Lingvanex con soluciones de traducción empresarial y locales (on-premise)</sub></p>

<a id="systran"></a>
### SYSTRAN
SYSTRAN se dirige a los requisitos de localización corporativos e institucionales. Su servicio en la nube, [SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/), está disponible de forma inmediata para archivos Word, PowerPoint, Excel y PDF, ofreciendo modelos de dominio preconfigurados para documentación legal, financiera e industrial, junto con glosarios personalizados y memorias de traducción (TM).

Para organizaciones con requisitos de soberanía de datos, SYSTRAN ofrece [Translate Server](https://www.systransoft.com/translation-products/translate-server/) para despliegue local (on-premise) tras cortafuegos corporativos, entornos dedicados de nube privada y [API](https://www.systransoft.com/translation-products/translate-api/) para procesamiento por lotes en canalizaciones de documentos.

<p align="center"><img src="assets/systran-page@2x.webp" alt="Página oficial del producto SYSTRAN Translate Pro" width="640"><br><sub>Interfaz oficial de descripción general del producto SYSTRAN Translate Pro</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>
## 4. Redacción académica, perfeccionamiento y colaboración persona-máquina: Pulido del resultado final

A menudo, la traducción constituye la fase inicial de un flujo de trabajo más amplio de redacción o investigación. Verificar definiciones de diccionario, perfeccionar la redacción y contar con una edición interactiva entre personas y máquinas ayuda a garantizar los estándares académicos formales.

<a id="youdao-translate-netease-youdao"></a>
### Youdao Translate (NetEase Youdao)
Conectado con el ecosistema de diccionarios de NetEase Youdao, [Youdao Translate](https://fanyi.youdao.com/) vincula la consulta de vocabulario, la traducción y la asistencia en redacción. Además de la traducción estándar de texto y archivos, su portal web ofrece accesos específicos para "traducción de artículos de arXiv" y pulido de textos académicos.

Tras traducir fragmentos de investigación, los usuarios pueden ejecutar revisiones gramaticales, evaluar opciones de sinónimos o ajustar el tono académico, lo que ayuda a estudiantes e investigadores a revisar literatura extranjera y redactar manuscritos. La cobertura de formatos e idiomas para el pulido de artículos y los módulos multimedia difiere de la consulta general del diccionario.

<p align="center"><img src="assets/youdao-page@2x.webp" alt="Espacio de trabajo oficial de traducción web de NetEase Youdao Translate" width="640"><br><sub>Interfaz web y navegación de funciones de NetEase Youdao Translate</sub></p>

<a id="baidu-translate"></a>
### Baidu Translate
[Baidu Translate](https://fanyi.baidu.com/) ofrece una amplia cobertura de clientes para usuarios de habla china. Su software de escritorio cuenta con una ventana flotante compacta y selección de texto mediante atajos en aplicaciones locales de escritorio, mientras que su aplicación móvil combina traducción de fotos, práctica oral y referencias de diccionario.

Además, Baidu aloja un portal independiente de [traducción de video de Baidu](https://fanyi-video.baidu.com/). Los usuarios cargan archivos multimedia para generar pistas de subtítulos bilingües alineadas, revisarlas y editarlas en un editor en línea y exportar los archivos de subtítulos terminados. Se trata de una herramienta de posproducción basada en la carga de archivos y no de un intérprete automático para reproducciones web en directo.

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Página oficial del sitio web de Baidu Translate" width="640"><br><sub>Interfaz web oficial de Baidu Translate</sub></p>

<a id="transmart-tencent-interactive-translation"></a>
### TranSmart (Tencent Interactive Translation)
Desarrollado por Tencent AI Lab, [TranSmart](https://transmart.qq.com/zh-CN/intro) está diseñado en torno a la colaboración interactiva persona-máquina. En lugar de generar un resultado estático para copiar, TranSmart sugiere predicciones y autocompletados en tiempo real a nivel de palabras y oraciones, integrando pares bilingües confirmados en la memoria de traducción activa.

Los traductores pueden colocar el cursor en cualquier parte del texto traducido para hacer ajustes, lo que incita al sistema a actualizar dinámicamente las sugerencias posteriores. Esto mantiene las decisiones terminológicas y el ritmo de las oraciones en manos del usuario, operando como un editor colaborativo cuyo enfoque difiere del de las aplicaciones móviles de diccionario de consumo de Tencent.

<p align="center"><img src="assets/transmart-page@2x.webp" alt="Página web oficial de Tencent TranSmart" width="640"><br><sub>Interfaz web oficial de Tencent TranSmart</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>
### LingoCloud (Caiyun Xiaoyi)
[LingoCloud](https://www.caiyunapp.com/?lang=zh) se utiliza ampliamente para flujos de trabajo en chino, inglés y japonés. Su extensión de navegador ofrece lectura web bilingüe dentro de la página con soporte para glosarios compartidos públicos y personales. Su [servicio de traducción de documentos](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html) (que toma como referencia las directrices de la aplicación móvil) admite formatos como PDF, Word, PPT, Excel, EPUB, TXT y SRT, entregando los archivos descargados principalmente en formato PDF o Word según el archivo de origen.

Su software de escritorio también incluye [LingoCloud Interpretation](https://www.caiyunapp.com/interpretation/), que puede capturar el audio del micrófono o interceptar la salida de audio del sistema desde aplicaciones en ejecución (como Zoom, Teams o Chrome en Windows) para renderizar subtítulos bilingües en directo. La interpretación en el escritorio está sujeta a los límites de captura de audio del sistema operativo: en Windows, la captura de audio del sistema funciona en aplicaciones de conferencias y multimedia compatibles; en macOS, las rutas de grabación de audio interno del sistema no son compatibles actualmente debido a actualizaciones del sistema macOS, por lo que la captura a través de micrófono es la única vía operativa.

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="Página oficial del sitio web de LingoCloud" width="640"><br><sub>Interfaz web oficial de LingoCloud</sub></p>

<a id="quillbot-translate"></a>
### QuillBot Translate
[QuillBot Translate](https://quillbot.com/translate) opera dentro del ecosistema de redacción y edición de QuillBot. Al traducir texto, la interfaz ofrece opciones de formalidad y muestra definiciones y sinónimos en los idiomas admitidos.

El texto traducido se puede copiar fluidamente en su Paraphraser y Grammar Checker para perfeccionar la fluidez de las oraciones. La plataforma también mantiene una [página dedicada a la traducción de PDF](https://quillbot.com/translate-pdf) para cargar y revisar documentos PDF individuales. Los idiomas admitidos varían entre las herramientas de traducción, gramática y paráfrasis.

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="Página oficial de la extensión de QuillBot en Chrome Web Store" width="640"><br><sub>Página oficial del producto en Chrome Web Store para la extensión de navegador QuillBot</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>
## 5. Ecosistema de código abierto: Motores locales, API, clientes de escritorio y procesamiento de PDF científicos

Desarrolladores, equipos preocupados por la privacidad e investigadores académicos a menudo necesitan código inspeccionable, ejecución local sin conexión o canalizaciones de automatización personalizadas. El ecosistema de traducción de código abierto abarca varios niveles arquitectónicos bien diferenciados:

- **Herramientas de diseño para PDF científicos**: Traducen artículos académicos complejos preservando diseños multicolumna, fórmulas y figuras.
- **Servicios de traducción autoalojables**: Proporcionan puntos de conexión de API REST HTTP e interfaces web para su despliegue en redes locales.
- **Motores integrados de traducción sin conexión**: Ejecutan traducción automática neuronal localmente mediante bibliotecas de Python sin dependencias de redes externas.
- **Interfaces de escritorio y terminal**: Integran consultas multimotor, monitorización del portapapeles, OCR y canalizaciones de shell.

> [!IMPORTANT]
> Ejecutar código de código abierto de forma local no implica automáticamente que las traducciones sean sin conexión o privadas. Una herramienta puede ejecutarse localmente mientras consulta API en la nube de forma predeterminada. Una traducción verdaderamente sin conexión requiere tanto recursos de modelos locales como un motor de traducción local.

<a id="51-scientific--academic-pdf-pipelines"></a>
### 5.1 Procesamiento de PDF científicos y académicos

<a id="pdfmathtranslate-pdf2zh"></a>
#### PDFMathTranslate (pdf2zh)
[PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) (GNU AGPL v3) es una herramienta de código abierto adaptada para documentos PDF científicos y académicos. Preserva estructuras de artículos en varias columnas, notación matemática, gráficos incrustados, tablas de contenido y anotaciones.

- **Salidas bilingües y monolingües**: Genera documentos únicamente traducidos (`-mono.pdf`) y documentos de comparación bilingüe (`-dual.pdf`).
- **Interfaces e integraciones**: Ofrece herramientas de línea de comandos (CLI), una WebUI interactiva, despliegue en contenedores Docker y compatibilidad con Model Context Protocol (MCP). Como proyecto complementario se encuentra disponible un plugin vinculado de integración con Zotero.
- **Motores de traducción**: Emplea una arquitectura conectable que admite Google Translate (predeterminado documentado), DeepL, API compatibles con OpenAI e instancias locales de Ollama. El despliegue local mediante Docker o WebUI no implica un funcionamiento sin conexión si se configuran motores en la nube.
- **Soporte de OCR**: Incluye OCR experimental para páginas escaneadas con texto negro sobre fondo blanco (descarga los recursos de modelos de lenguaje en el primer uso, que luego pueden reutilizarse localmente).

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="Página oficial del repositorio de GitHub de PDFMathTranslate" width="640"><br><sub>Descripción general del repositorio oficial de PDFMathTranslate que ilustra la traducción de diseños de PDF académicos y los flujos de trabajo con CLI/WebUI</sub></p>

<a id="babeldoc"></a>
#### BabelDOC
[BabelDOC](https://github.com/funstory-ai/BabelDOC) (GNU AGPL v3) es una biblioteca de traducción y comparación bilingüe de artículos científicos a nivel de documento, diseñada principalmente para integrarse en aplicaciones de Python, acompañada de una CLI de depuración.

- **Control de diseño y salidas**: Admite salidas monolingües o bilingües, páginas originales y traducidas en paralelo en la misma página o alternas, traducción selectiva de páginas, división y combinación de PDF grandes, entrada de glosarios personalizados en CSV y preservación de fórmulas. La traducción de texto en tablas está documentada explícitamente como experimental.
- **Arquitectura de motores**: Requiere un motor de traducción configurado a través de puntos de conexión compatibles con OpenAI o una instancia local de Ollama. Al ser un motor de procesamiento y composición de PDF, no incluye por sí mismo un motor de traducción universal.
- **Recursos sin conexión y límites**: Proporciona rutinas de precalentamiento (warmup) y generación/restauración de recursos sin conexión para modelos de diseño de documentos y fuentes. La ejecución completamente sin conexión requiere tanto recursos previamente almacenados en caché como un motor de traducción en ejecución local (como Ollama local). La documentación destaca su validación principal en flujos de trabajo de inglés a chino, con una solución de OCR experimental para texto negro sobre fondos blancos.

<p align="center"><img src="assets/babeldoc-page.webp" alt="Página oficial del repositorio de GitHub de BabelDOC" width="640"><br><sub>Descripción general del repositorio oficial de BabelDOC que muestra las capacidades de la biblioteca de traducción de PDF científicos a nivel de documento</sub></p>

<a id="52-self-hostable-engines--apis"></a>
### 5.2 Motores autoalojables y API

<a id="libretranslate"></a>
#### LibreTranslate
[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) (GNU AGPL v3) es un servicio de API de traducción automática gratuito y de código abierto que se puede autoalojar, con una interfaz web incluida, construido sobre el motor Argos Translate.

- **API y servicio web**: Expone puntos de conexión de API REST para traducción de texto, detección de idioma de origen y gestión de HTML/marcado. Funciona como una capa de servicio independiente y no como un proxy hacia API comerciales de traducción.
- **Despliegue local y privacidad**: Puede ejecutarse por completo en hardware local sin enviar datos a terceros una vez instaladas las dependencias y los modelos de idiomas. El uso de una instancia pública alojada sigue dependiendo de la red. El control de acceso por clave de API se puede habilitar o deshabilitar según los requisitos del anfitrión.
- **Cobertura de idiomas y formatos de archivo**: Los pares de idiomas disponibles dependen de los modelos de idiomas instalados. A través de proyectos complementarios como argos-translate-files, la traducción de archivos admite formatos como TXT, ODT, ODP, DOCX, PPTX, EPUB, HTML, SRT y PDF.

<p align="center"><img src="assets/libretranslate-page.webp" alt="Página oficial del repositorio de GitHub de LibreTranslate" width="640"><br><sub>Descripción general del repositorio oficial de LibreTranslate que muestra las funciones de la API de traducción autoalojada y la interfaz web</sub></p>

<a id="argos-translate"></a>
#### Argos Translate
[Argos Translate](https://github.com/argosopentech/argos-translate) (licencia MIT / opción CC0 declarada en el README) es una biblioteca de traducción en Python y herramienta de línea de comandos de código abierto para uso sin conexión, con un cliente GUI que se puede instalar por separado.

- **Paquetes modulares de modelos**: Descarga y gestiona paquetes de modelos de idiomas con la extensión `.argosmodel`. Cuando un par de idiomas directo no está disponible, puede pivotar a través de pares intermedios instalados (por ejemplo, traduciendo a través del inglés).
- **Motor del ecosistema**: Sirve como motor subyacente de traducción automática para LibreTranslate. Los proyectos complementarios amplían sus capacidades a la traducción de HTML (`translate-html`) y el procesamiento de archivos (`argos-translate-files`).
- **Funcionamiento sin conexión**: Se ejecuta completamente sin conexión una vez instalados los modelos; la descarga de índices de paquetes y modelos iniciales requiere conectividad a internet.

<p align="center"><img src="assets/argos-translate-page.webp" alt="Página oficial del repositorio de GitHub de Argos Translate" width="640"><br><sub>Descripción general del repositorio oficial de Argos Translate detallando el motor de traducción modular sin conexión y el sistema de paquetes</sub></p>

<a id="53-desktop--terminal-frontends"></a>
### 5.3 Interfaces de escritorio y terminal

<a id="pot-pot-desktop"></a>
#### Pot (pot-desktop)
[Pot](https://github.com/pot-app/pot-desktop) (GNU GPL v3) es una herramienta de traducción de escritorio multiplataforma para Windows, macOS y Linux que admite traducción de selecciones mediante atajos de teclado, entrada escrita, monitorización del portapapeles, OCR de capturas de pantalla y traducción de capturas de pantalla. El repositorio oficial de GitHub fue archivado el 7 de septiembre de 2026 y ahora está en modo de solo lectura (read-only).

- **Agregación multiservicio**: Permite consultar múltiples servicios de traducción y diccionarios de forma simultánea para comparar resultados en paralelo. Admite síntesis de voz (TTS), exportación de vocabulario a Anki y Eudic, y extensiones mediante plugins.
- **Motores y OCR configurables**: Agrega proveedores de traducción en la nube, API compatibles con OpenAI y puntos de conexión locales de Ollama. Las opciones de OCR incluyen alternativas nativas de la plataforma (OCR del sistema Windows, Apple Vision, Tesseract en Linux), Tesseract.js o plugins locales.
- **Rutas de ejecución sin conexión**: La traducción de selecciones y texto escrito solo requiere un motor de traducción local configurado (como una instancia local de Ollama); la traducción de capturas de pantalla requiere además un motor de OCR sin conexión (como el OCR nativo de la plataforma o Tesseract). Los servicios en la nube enrutan las solicitudes a través de la red.

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Página oficial del repositorio de GitHub del cliente de traducción de escritorio Pot" width="640"><br><sub>Descripción general del repositorio oficial del cliente de escritorio Pot destacando la traducción multi-interfaz, OCR y flujos de trabajo con el portapapeles</sub></p>

<a id="translate-shell"></a>
#### Translate Shell
[Translate Shell](https://github.com/soimort/translate-shell) (The Unlicense / Dominio público) es una versátil herramienta de traducción en línea de comandos (ejecutable `trans`) para entornos de terminal tipo Unix.

- **Consultas y diccionario en CLI**: Admite definiciones de palabras, traducción de frases, modo de diccionario conciso, sesiones interactivas REPL e identificación de idioma directamente en el shell.
- **Canalizaciones de Unix**: Se integra con la entrada/salida estándar (`stdin` / `stdout`), procesa archivos de texto directamente y admite síntesis de voz cuando hay un reproductor de audio externo instalado.
- **Capa del motor**: Opera como una interfaz ligera de cliente que se conecta a servicios de traducción públicos (Google Translate de forma predeterminada; asimismo admite Bing Translator, Yandex.Translate y Apertium como opciones adicionales).
- **Límites y restricciones**: No incluye modelos locales de traducción neuronal; el funcionamiento estándar depende de la conectividad de red externa hacia los servicios de motores seleccionados. La traducción de archivos está diseñada para flujos de texto plano, no para documentos formateados.

<p align="center"><img src="assets/translate-shell-page.webp" alt="Página oficial del repositorio de GitHub de Translate Shell" width="640"><br><sub>Descripción general del repositorio oficial de Translate Shell que muestra la traducción en línea de comandos en la terminal y la integración en canalizaciones</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>
## 6. Flujos de trabajo integrados de extremo a extremo: Equalang

El examen de estas herramientas demuestra que cada servicio ha desarrollado capacidades claras para tareas específicas. En el trabajo diario, sin embargo, los requisitos se cruzan con frecuencia:

Es posible que leas un libro blanco en línea en tu navegador, descargues un PDF adjunto con tablas y diagramas, mires una conferencia en video sin subtítulos y luego prepares un resumen ejecutivo en Word mientras coordinas directamente con colaboradores internacionales. Alternar entre herramientas de software aisladas y convertidores de archivos fragmenta el flujo de trabajo.

Diseñamos **Equalang** para conectar estas tareas en un flujo de traducción continuo y bilingüe, ofreciendo soporte coordinado de traducción en documentos, páginas web, videos y comunicación en directo.

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Página de inicio oficial en inglés de Equalang" width="640"><br><sub>Página de inicio del sitio web oficial en inglés de Equalang</sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>
### 1. Traducción de documentos completos con preservación del diseño
Al traducir documentos completos, Equalang se enfoca en la preservación estructural y la usabilidad posterior a la traducción, ofreciendo flujos de trabajo adaptados para literatura de investigación, presentaciones y archivos de oficina cotidianos:

- **Documentos PDF y lectura**: Equalang preserva diseños de varias columnas, encabezados, pies de página y pies de ilustración, reconectando oraciones divididas por saltos de página antes de traducir, a la vez que mantiene estructuras de tablas, fórmulas en línea y enlaces internos del documento. Como se detalla en nuestra [guía práctica de lectura de PDF académicos](https://equalang.com/blog/translate-and-read-pdf-documents), los lectores pueden visualizar el archivo traducido junto con el original en un diseño en paralelo, asimilando primero los argumentos centrales en su idioma principal antes de cotejar la terminología y los datos específicos en la página original.

- **Presentaciones de PowerPoint**: En nuestra [guía de formato para presentaciones de diapositivas](https://equalang.com/blog/translate-powerpoint-keep-formatting), los archivos PPTX traducidos conservan tablas editables nativas en lugar de aplanarlas en imágenes estáticas. El estilo a nivel de palabra —como negrita, cursiva y colores de fuente dentro de una sola oración— se asigna con precisión a las frases traducidas correspondientes. Los términos clave y los encabezados se mantienen coherentes en todas las diapositivas, y los cuadros de texto reducen automáticamente el tamaño de la fuente cuando las traducciones se expanden para evitar el desbordamiento de texto o cubrir gráficos.

- **Archivos de oficina de Word y Excel**: En nuestra [prueba verificada de traducción de Word](https://equalang.com/blog/translate-word-document-keep-formatting), los archivos DOCX traducidos conservaron encabezados, listas con viñetas, tablas de precios y formato en negrita, permitiendo la edición directa en Microsoft Word. En nuestra [validación de hojas de precios de Excel](https://equalang.com/blog/translate-excel-file), las fórmulas y los números se mantuvieron intactos, mientras que las cadenas de texto duplicadas en distintas celdas se tradujeron solo una vez.

- **Libros electrónicos y medios formateados**: Los libros electrónicos EPUB conservan la navegación de la tabla de contenidos y los enlaces de anclaje internos. Para archivos de audio y video grabados de hasta 180 minutos, las tareas de traducción y transcripción se envían a través de nuestra API para desarrolladores y la integración de Agent Skill/MCP (en lugar de un portal general de carga de documentos web), generando archivos de subtítulos bilingües con marcas de tiempo en formato SRT/VTT o transcripciones originales.

<a id="2-in-browser-reading--subtitle-generation"></a>
### 2. Lectura en el navegador y generación de subtítulos
A través de nuestra ligera [extensión de navegador](https://equalang.com/extension) (con guías de instalación para Chrome, Edge y Firefox, además de un modo temporal para Mac Safari en Safari 18.4+), la traducción se integra directamente en tu lectura diaria:

- **Lectura web bilingüe debajo del párrafo**: Los párrafos traducidos aparecen directamente debajo del texto original a medida que te desplazas. Se puede alternar un icono flotante en la configuración para consultas de palabras bajo demanda. Al visualizar PDF locales, los usuarios pueden habilitar "Permitir acceso a URL de archivo" en la administración de extensiones para seleccionar palabras y consultar su significado.

- **Subtítulos bilingües en video**: Compatible con YouTube, Netflix, TikTok y Bilibili, tal como se explora en nuestra [guía de visualización de videos bilingües](https://equalang.com/blog/watch-videos-with-bilingual-subtitles). Más allá de traducir subtítulos existentes, la extensión puede capturar transmisiones de audio para generar subtítulos bilingües en tiempo real para **videos sin subtítulos** (sujeto al entorno del navegador y a los límites de cifrado de medios, verificado en transmisiones en directo de YouTube y avances oficiales), traduciendo simultáneamente los comentarios del chat en directo en YouTube.

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>
### 3. Comunicación por voz e intercambios in situ sin instalación
Exigir a los interlocutores que instalen aplicaciones móviles dedicadas genera fricciones, especialmente al viajar. Con conexión a internet, Equalang ofrece traducción de fotos y traducción hablada sobre la marcha directamente dentro de navegadores estándar (requiriendo solo un inicio de sesión inicial y permisos de cámara/micrófono del dispositivo en el primer uso), según se describe en nuestra [guía de comunicación internacional](https://equalang.com/blog/talk-with-overseas-partners):

- **Traducción de fotos en el móvil**: Al encontrarse con menús de restaurantes, letreros o avisos públicos desconocidos durante un viaje, los usuarios pueden tomar una foto en su navegador móvil. Las traducciones se superponen directamente sobre el diseño de la foto, facilitando pedir consumiciones o revisar avisos frente a la imagen original, como se ilustra en nuestra [guía de traducción de fotos para viajes](https://equalang.com/blog/photo-translation-for-travel).

- **Modo cara a cara**: Diseñado para situaciones presenciales como consignas de equipaje en hoteles, pedir indicaciones o trámites en recepción. Dos interlocutores pueden colocar un único teléfono o tableta plano entre ellos, utilizando una vista dividida invertida o en paralelo con transcripción bidireccional continua y exportación de la transcripción, como se muestra en nuestra [guía de conversación cara a cara durante viajes](https://equalang.com/blog/talk-face-to-face-while-traveling).

- **Escucha en directo**: Abre el portal web durante una presentación o conferencia presencial para recibir subtítulos bilingües en tiempo real capturados a través del micrófono físico del dispositivo, con síntesis de voz opcional y exportación de transcripciones al finalizar (a diferencia de la captura de audio de medios de transmisión de la extensión del navegador).

- **Llamadas traducidas**: El anfitrión inicia sesión en el portal web para generar un enlace de llamada seguro y compartirlo a través de cualquier aplicación de mensajería. **Los invitados se unen directamente desde su navegador sin crear una cuenta ni instalar software alguno**; simplemente introducen un nombre visible y el anfitrión les da acceso para comenzar la llamada. Ambas partes hablan en su lengua materna, escuchan el audio traducido y leen el texto en tiempo real.

<a id="4-integration-for-ai-agents-and-developers"></a>
### 4. Integración para agentes de IA y desarrolladores
Para ayudar a desarrolladores y equipos a integrar la traducción en flujos de trabajo automatizados:

- **API para desarrolladores**: Cuenta con puntos de conexión instantáneos para texto junto con tareas asíncronas de archivos que admiten reintentos con Idempotency-Key y notificaciones de callback, como se detalla en nuestra [guía de integración de la API de traducción de archivos](https://equalang.com/blog/integrate-file-translation-api).

- **Integración con Skill y MCP**: Mantenemos Agent Skills de código abierto mediante [equalang-skill](https://github.com/equalang/equalang-skill) y soporte oficial de Model Context Protocol a través de [@equalang/mcp](https://github.com/equalang/equalang-mcp). En entornos como Claude Code, Codex o WorkBuddy, enviar una única instrucción (prompt) de instalación y configurar tu clave de API permite que tu asistente de IA gestione la traducción de documentos y la transcripción de medios directamente dentro de tu flujo de trabajo, siguiendo nuestra [guía de traducción de archivos con asistentes de IA](https://equalang.com/blog/translate-files-with-ai-assistants).

---

<a id="7-task-based-decision-guide"></a>
## 7. Guía de decisión orientada a tareas

Para ayudarte a elegir la herramienta adecuada para tu tarea actual, consulta esta matriz de tareas:

| Tarea principal | Requisito fundamental | Herramientas recomendadas para probar | Consideraciones clave |
| :--- | :--- | :--- | :--- |
| **Viajes y diálogo hablado** | OCR de fotos, diálogo bidireccional, paquetes sin conexión y herramientas de viaje conectadas | Google Translate, Apple Translate, Papago, Equalang | Descarga paquetes de idiomas sin conexión en Google, Apple o Papago (teniendo en cuenta los requisitos de hardware) para zonas con poca cobertura; cuando hay conexión, Equalang ofrece traducción de fotos en el navegador y diálogo cara a cara sin instalar aplicaciones. |
| **Talleres multidispositivo** | Presentaciones de uno a muchos, participación multidispositivo | Microsoft Translator | El anfitrión activa el modo Presentador desde la aplicación móvil; los asistentes se unen mediante un navegador estándar sin instalar software. |
| **Lectura web en profundidad** | Lectura debajo del párrafo sin salir de la página | Immersive Translate, Equalang, Mate Translate | Usa Immersive Translate o Equalang para párrafos bilingües; usa Mate Translate para alternar vistas de página completa o guardar palabras en Phrasebooks en Mac. |
| **Videos y transmisiones en vivo sin subtítulos** | Generación de subtítulos en tiempo real, compatibilidad con streaming | Equalang, Immersive Translate | Ambas herramientas pueden generar subtítulos a partir de audio sin procesar en plataformas compatibles (como YouTube); compara los flujos de las extensiones de navegador para chat en directo y gestión de transmisiones. |
| **Artículos académicos y PDF científicos** | Conservación de fórmulas, estructuras de columnas, texto entre páginas | PDFMathTranslate, BabelDOC, Equalang | PDFMathTranslate y BabelDOC ofrecen canalizaciones de código abierto con salida de PDF dual y motores LLM locales/en la nube; Equalang proporciona lectura en paralelo basada en el navegador y preservación del diseño visual. |
| **Formatos de preimpresión editorial y diseño** | InDesign, Illustrator, archivos de cómics, control de calidad de preimpresión | SimplifyAI, O.Translator | Usa SimplifyAI y O.Translator para InDesign (IDML) y preimpresión de recursos de diseño; SimplifyAI incluye AI Editing con control de cambios nativo de Word. |
| **Presentaciones y documentos de oficina** | Conservación de tablas nativas, estilos, fórmulas y editabilidad | Equalang, DeepL | Equalang preserva tablas y estilos nativos de PPTX con escalado adaptativo de fuentes y retención de fórmulas en Excel; usa DeepL para archivos Word/Office corporativos con glosarios. |
| **Redacción académica y pulido** | Precisión gramatical, registro académico formal | Youdao Translate, QuillBot Translate, TranSmart | Youdao y QuillBot agilizan la transición de la traducción al perfeccionamiento del texto; TranSmart proporciona edición interactiva persona-máquina. |
| **Consulta por atajo de escritorio y multimotor** | Atajos globales, OCR, comparación de múltiples motores | Pot, Mate Translate | Pot permite consultas simultáneas en múltiples motores y OCR de capturas de pantalla en Windows, Mac y Linux; Mate ofrece una utilidad nativa para la barra de menús de Mac. |
| **Scripts de terminal y canalizaciones de shell** | Consultas en CLI, canalizaciones stdin/stdout, scripts de texto plano | Translate Shell, Argos Translate | Translate Shell proporciona traducción ligera en CLI mediante motores remotos; Argos Translate proporciona una CLI de Python sin conexión con modelos locales. |
| **API privada autoalojada y motores sin conexión** | Redes aisladas (air-gapped), sin transmisión de datos a terceros | LibreTranslate, Argos Translate, SYSTRAN, Lingvanex | LibreTranslate proporciona un servicio de API HTTP autoalojado y WebUI; Argos Translate lo impulsa como una biblioteca de Python/CLI sin conexión con paquetes modulares de modelos; SYSTRAN y Lingvanex ofrecen despliegues locales empresariales. |
| **Flujos de trabajo integrados de extremo a extremo** | Documentos, subtítulos de streaming, llamadas web y agentes de IA | Equalang | Procesamiento unificado de documentos, subtítulos para medios sin subtítulos, llamadas basadas en navegador sin instalación de aplicaciones e integración directa con Claude Code o WorkBuddy. |

---

<a id="8-directory-principles--verification-criteria"></a>
## 8. Principios del directorio y criterios de verificación

Para mantener la utilidad práctica y la precisión factual de este directorio, las entradas siguen estrictos criterios de inclusión y revisión:

1. **Funciones documentadas por encima de afirmaciones de marketing**: Las descripciones proceden de la documentación oficial, manuales de usuario y archivos fuente confirmados de los repositorios. No afirmamos una conservación perfecta del diseño visual ni compatibilidad universal de formatos.
2. **Límites arquitectónicos claros**: Distinguimos con claridad entre interfaces de traducción, capas de servicios autoalojables, motores de traducción sin conexión y bibliotecas de diseño documental. El código abierto que se ejecuta localmente se separa explícitamente de la verdadera ejecución sin conexión.
3. **Cobertura orientada a tareas**: Las herramientas se agrupan según su adecuación práctica en distintos flujos de trabajo. No mantenemos clasificaciones subjetivas por niveles, calificaciones de calidad ni tarifas transitorias.
4. **Identidad transparente del equipo de mantenimiento**: Este catálogo está seleccionado y mantenido por el equipo de **Equalang**. Equalang se presenta junto a las demás herramientas con límites de características verificables y requisitos de sistema transparentes.

**Palabras clave**: herramientas de traducción, traducción de documentos, lectura web bilingüe, traducción de PDF académicos, traducción de código abierto, API de traducción automática, preservación del diseño visual, agentes de IA.

---

<a id="9-sources"></a>
## 9. Fuentes

1. [Centro de ayuda de Google Translate](https://support.google.com/translate)
2. [Traducción de documentos en escritorio de Google Translate](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Soporte de Apple: Guía de la aplicación Traducir para iPhone](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Soporte de Apple: Traducción en directo y disponibilidad de funciones](https://support.apple.com/en-us/123720)
5. [Funciones móviles de Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/)
6. [Ayuda para conversaciones multidispositivo de Microsoft Translator](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/)
7. [Portal oficial de NAVER Papago](https://papago.naver.com/)
8. [Funciones de teclado y sin conexión de iTranslate](https://itranslate.com/features/keyboard-translations/index.html)
9. [Información de uso de Reverso Context](https://context.reverso.net/translation/about)
10. [Portal de Reverso Documents](https://www.reverso.net/documents/en)
11. [Ayuda de Yandex Translate para escritorio y móviles](https://yandex.com/support/translate-desktop/en/)
12. [Documentación de Immersive Translate](https://immersivetranslate.com/)
13. [Información del producto y formatos de O.Translator](https://otranslator.com/en/product-info)
14. [Taller de documentos complejos de SimplifyAI](https://simplifyai.cn/zh/translate)
15. [Traducción general de documentos de SimplifyAI](https://translate.simplifyai.cn/)
16. [Funciones de Mate Translate](https://matetranslate.com/en)
17. [Traductor de Windows de Lingvanex](https://lingvanex.com/products/windows-translator/)
18. [Software de traducción segura de Lingvanex (Secure Translation Software)](https://lingvanex.com/products/secure-translation-software/)
19. [SYSTRAN Translate Pro y despliegues empresariales](https://www.systransoft.com/translation-products/translate-pro/)
20. [NetEase Youdao Translate](https://fanyi.youdao.com/)
21. [Portal de traducción de video y Baidu Translate](https://fanyi.baidu.com/)
22. [Presentación del producto Tencent TranSmart](https://transmart.qq.com/zh-CN/intro)
23. [Ayuda de documentos de Caiyun Xiaoyi (LingoCloud)](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
24. [Portal de traducción y PDF de QuillBot](https://quillbot.com/translate)
25. [Especificaciones y documentación de la API de Equalang](https://equalang.com/llms-full.txt)
26. [Repositorio oficial de GitHub de PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate)
27. [Documentación de opciones avanzadas de PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
28. [Repositorio oficial de GitHub de BabelDOC](https://github.com/funstory-ai/BabelDOC)
29. [Repositorio oficial de GitHub de LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
30. [Documentación y guía de API de LibreTranslate](https://docs.libretranslate.com/)
31. [Repositorio oficial de GitHub de Argos Translate](https://github.com/argosopentech/argos-translate)
32. [Repositorio oficial de GitHub del cliente de escritorio Pot](https://github.com/pot-app/pot-desktop)
33. [Repositorio oficial de GitHub de Translate Shell](https://github.com/soimort/translate-shell)
