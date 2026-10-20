# Awesome Translation Tools

> Un répertoire sélectionné d'outils et de flux de travail de traduction couvrant les voyages, la lecture web, les documents mis en page, la recherche académique, les moteurs locaux open source et les chaînes de développement.

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

Les tâches de traduction diffèrent fondamentalement selon le contexte : déchiffrer un panneau de signalisation ou un menu sur un téléphone mobile, consulter une documentation étrangère au sein d'un navigateur, traduire des présentations complexes et des contrats sans altérer leur mise en page, préserver les formules mathématiques dans des articles académiques, exécuter des traductions privées par lots dans un terminal ou encore suivre des flux vidéo dépourvus de sous-titres.

Nous sommes l'équipe **[Equalang](https://equalang.com/?utm_source=github)**. Ce répertoire propose un catalogue pratique, orienté tâches, de produits de traduction reconnus et de projets open source. Pour chaque outil, nous synthétisons les fonctionnalités documentées, les points d'accès, les modes de déploiement et les contraintes opérationnelles afin de vous aider à identifier la solution adaptée à votre flux de travail.

---

<a id="contents"></a>
## Sommaire

- [1. Déplacements et échanges oraux : entrées multimodales et vocales](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. Lecture web en contexte et apprentissage des langues : lire sans quitter la page](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. Documents à mise en page complexe et flux d'entreprise : préserver formats et actifs](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. Rédaction académique, révision et collaboration homme-machine : peaufiner le texte final](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. Écosystème open source : moteurs locaux, API, clients de bureau et chaînes de traitement pour PDF scientifiques](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 Chaînes de traitement pour PDF scientifiques et académiques](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 Moteurs auto-hébergeables et API](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 Interfaces de bureau et de terminal](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. Flux de travail de bout en bout connectés :](#6-connected-end-to-end-workflows-equalang) [Equalang](https://equalang.com/?utm_source=github)
  - [1. Traduction de documents intégraux avec préservation de la mise en page](#1-whole-file-document-translation-with-layout-preservation)
  - [2. Lecture dans le navigateur et génération de sous-titres](#2-in-browser-reading--subtitle-generation)
  - [3. Communication orale et échanges sur place sans installation](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. Intégration pour les agents IA et les développeurs](#4-integration-for-ai-agents-and-developers)
- [7. Guide de décision basé sur les tâches](#7-task-based-decision-guide)
- [8. Principes du répertoire et critères de vérification](#8-directory-principles--verification-criteria)
- [9. Sources](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>
## 1. Déplacements et échanges oraux : entrées multimodales et vocales

Les déplacements et le travail sur le terrain exigent une activation rapide, une reconnaissance multimodale fiable et une disponibilité hors ligne lorsque la connectivité réseau est limitée.

<a id="google-translate"></a>
### Google Translate
[Google Translate sur mobile](https://support.google.com/translate) intègre la reconnaissance optique de caractères (OCR) instantanée via la caméra, l'importation de photos, la saisie manuscrite et un mode de conversation face à face en écran partagé. Les voyageurs peuvent télécharger des packs linguistiques à l'avance pour la traduction hors ligne de textes et d'images via l'appareil photo. La traduction de conversations orales propose plusieurs configurations d'affichage, bien que l'interprétation vocale directe hors ligne soit limitée à certains appareils Pixel et à une sélection de paires de langues.

Sur les navigateurs d'ordinateurs de bureau, Google Translate propose un [portail dédié à la traduction de documents](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en) qui prend en charge les fichiers DOCX, PDF, PPTX et XLSX. Cet outil bureautique est conçu pour les fichiers numériques natifs ; les pages de PDF numérisés composées de pures images sont conservées telles quelles dans le fichier téléchargé, sans traduction par OCR.

<p align="center"><img src="assets/google-page@2x.webp" alt="Page officielle de présentation du produit Google Translate" width="640"><br><sub>Page officielle de présentation de Google Translate et section de téléchargement de l'application mobile</sub></p>

<a id="apple-translate"></a>
### Apple Translate
Pour les utilisateurs d'iPhone et d'iPad, l'application intégrée au système [Apple Translate](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios) ne nécessite aucune installation séparée. Elle prend en charge la saisie de texte, la commande vocale, la détection de texte par la caméra et la conversation face à face en écran partagé. Son mode conversation peut détecter automatiquement la langue parlée, évitant ainsi d'avoir à basculer manuellement le microphone entre les intervenants. Les packs de langues téléchargés permettent d'effectuer des recherches textuelles directement sur l'appareil sans connexion cellulaire.

Au sein de l'écosystème d'exploitation Apple, les [fonctionnalités de traduction en direct](https://support.apple.com/en-us/123720) s'étendent également à Messages, Téléphone et FaceTime. La traduction en direct des appels téléphoniques fait partie d'Apple Intelligence, requiert du matériel et des versions de système compatibles, et reste soumise à des critères d'éligibilité régionaux (par exemple, les appareils achetés en Chine continentale ne prennent actuellement pas en charge ces fonctionnalités avancées d'appel d'Apple Intelligence).

<p align="center"><img src="assets/apple-page@2x.webp" alt="Guide de l'assistance Apple pour traduire sur iPhone" width="640"><br><sub>Page du guide de l'assistance Apple pour traduire des mots et des expressions sur iPhone</sub></p>

<a id="microsoft-translator"></a>
### Microsoft Translator
L'[application mobile Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/) propose la traduction de texte dans 100+ langues, la traduction vocale en temps réel et la traduction d'images. Sa fonctionnalité de conversation multi-appareils (y compris le mode Présentateur, les codes de salle et la participation via un navigateur) a été retirée, comme documenté dans les [notes de version de l'iOS App Store](https://apps.apple.com/us/app/microsoft-translator/id1018949559) et les [notes de version de Microsoft Speech SDK](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/releasenotes).

L'application grand public ne prend pas en charge la traduction directe de films externes, de fichiers vidéo ou d'enregistrements multimédias. Alors que la [présentation des fonctionnalités de Microsoft](https://www.microsoft.com/en-us/translator/apps/features/) mentionne la traduction sur écran partagé sur un seul appareil, des packs linguistiques hors ligne et un recueil d'expressions, la description actuelle de l'App Store mentionne la traduction de texte, vocale et d'images ; vérifiez donc dans l'application avant de compter sur les packs hors ligne ou le recueil d'expressions.

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Page officielle des fonctionnalités de Microsoft Translator" width="640"><br><sub>La capture d'écran montre la page des fonctionnalités de Microsoft telle que capturée en octobre 2026, et la page décrit toujours la fonctionnalité de conversation multi-appareils, que Microsoft a retirée.</sub></p>

<a id="papago"></a>
### Papago
Développé par NAVER en Corée du Sud, [Papago](https://papago.naver.com/) propose des fonctionnalités pratiques pour les langues d'Asie de l'Est, notamment le coréen, l'anglais, le japonais et le chinois. Sur les appareils mobiles, son [application](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator) offre le dialogue face à face, un mode Edu pour créer des notes d'étude à partir de textes imprimés et la fenêtre flottante Papago Mini, facilitant la restauration, les déplacements en transports et l'apprentissage en Corée.

Pour la traduction de pages web, les points d'accès diffèrent selon les plateformes : NAVER a interrompu l'outil autonome de traduction de sites web sur son portail web de bureau, orientant les utilisateurs de PC vers son [navigateur Whale](https://whale.naver.com/) propulsé par Papago, tandis que l'[application mobile Papago](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE) conserve une option de traduction de sites web dans son menu latéral. Lorsque les packs linguistiques sont téléchargés sur des appareils compatibles respectant les prérequis système (comme indiqué dans la [documentation hors ligne de NAVER](https://help.naver.com/service/16448/contents/10663?osType=MOBILE), exigeant au moins 4 Go de RAM et Android 14+ avec des packs vocaux dédiés pour la parole), la traduction hors ligne prend en charge le texte et la voix entre le coréen, l'anglais, le japonais et le chinois simplifié. Notez que le mode hors ligne ne prend pas en charge l'OCR photo, le mode conversation, les pages web ni les fichiers de documents.

<p align="center"><img src="assets/papago-page@2x.webp" alt="Interface officielle de traduction web de NAVER Papago" width="640"><br><sub>Espace de travail de traduction web de NAVER Papago</sub></p>

<a id="itranslate"></a>
### iTranslate
[iTranslate](https://itranslate.com/) est réputé pour son [extension de clavier intégrée](https://itranslate.com/features/keyboard-translations/index.html). Lors de la rédaction de messages dans WhatsApp, iMessage ou par e-mail, les utilisateurs peuvent traduire du texte directement dans l'interface du clavier, évitant ainsi de basculer constamment entre différentes applications.

Le service propose également des packs téléchargeables pour les expressions de voyage courantes et des guides de conversation de base via ses [outils hors ligne](https://itranslate.com/features/offline-translations/index.html), facilitant la révision des phrases essentielles avant un départ. La disponibilité des fonctionnalités varie selon les systèmes d'exploitation, et les capacités vocales hors ligne sont limitées à une sélection de langues majeures.

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="Page d'accueil officielle d'iTranslate" width="640"><br><sub>Page d'accueil d'iTranslate présentant un aperçu de l'interface de l'application mobile</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>
## 2. Lecture web en contexte et apprentissage des langues : lire sans quitter la page

Lors de la lecture d'articles ou de documentations techniques en langue étrangère, faire des allers-retours vers un onglet de traduction externe interrompt la concentration. Les outils en contexte intègrent la traduction directement au sein de l'environnement de lecture actif.

<a id="immersive-translate"></a>
### Immersive Translate
[Immersive Translate](https://immersivetranslate.com/) est une extension de navigateur qui insère les paragraphes traduits directement sous le texte web original, offrant une mise en page bilingue claire. Elle prend également en charge la création d'e-books EPUB bilingues, la visualisation de PDF et la traduction de texte dans les champs de saisie du navigateur.

Côté multimédia, Immersive Translate traduit les pistes de sous-titres existantes sur des plateformes comme YouTube et Netflix. De plus, ses fonctionnalités de [traduction vidéo par IA](https://immersivetranslate.com/video/ai-video-translator/) s'appuient sur la reconnaissance vocale pour générer des sous-titres bilingues pour les vidéos non sous-titrées sur les plateformes compatibles telles que YouTube, parallèlement à un [portail dédié à la traduction en direct de YouTube](https://livetranslate.immersivetranslate.com/zh-CN). La génération de sous-titres à partir d'un flux audio sans sous-titres dépend de la compatibilité du navigateur, de la clarté audio et des conditions de diffusion de la plateforme.

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Page d'accueil officielle d'Immersive Translate" width="640"><br><sub>Page d'accueil d'Immersive Translate et portail de téléchargement de l'extension de navigateur</sub></p>

<a id="mate-translate"></a>
### Mate Translate
[Mate Translate](https://matetranslate.com/en) est conçu pour macOS, iOS et les principaux navigateurs de bureau. Durant la navigation, un double-clic sur un mot affiche une définition instantanée en pop-up, la sélection de texte déclenche des traductions contextuelles rapides, la traduction de page entière permet de basculer entre vue originale et vue traduite, et un utilitaire persistant est accessible dans la barre des menus de Mac.

Pour les apprenants d'une langue, Mate permet de cliquer sur des mots sur des pages web ou dans les sous-titres Netflix pour les enregistrer dans un guide d'expressions personnalisé (Phrasebook), qui prend en charge la catégorisation sur mesure et l'exportation CSV pour des révisions externes. Dans les navigateurs d'ordinateurs comme Chrome, son extension permet également de sélectionner du texte dans la visionneuse PDF intégrée pour déclencher directement des traductions.

<p align="center"><img src="assets/mate-page@2x.webp" alt="Page d'accueil officielle de Mate Translate" width="640"><br><sub>Page d'accueil de Mate Translate montrant des aperçus de l'interface multiplateforme</sub></p>

<a id="reverso"></a>
### Reverso
Pour les rédacteurs et les apprenants cherchant à vérifier l'usage naturel des mots, [Reverso Context](https://context.reverso.net/translation/about) fournit des paires de phrases bilingues extraites de films, de publications internationales et de sites web multilingues, accompagnées de tableaux de conjugaison des verbes et de suggestions de synonymes. Étant donné que les phrases d'exemple proviennent de corpus multilingues publics, les utilisateurs doivent évaluer l'adéquation du contexte pour les ébauches sensibles ou formelles.

Son portail documentaire, [Reverso Documents](https://www.reverso.net/documents/en), prend en charge les fichiers PDF, Word, PowerPoint, Excel et certains formats de localisation. Il fournit une interface de révision segment par segment dans le navigateur où les équipes peuvent collaborer sur les modifications avant de télécharger le fichier finalisé.

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Interface officielle de traduction de Reverso" width="640"><br><sub>Interface de traduction web et barre de navigation de Reverso</sub></p>

<a id="yandex-translate"></a>
### Yandex Translate
Le [portail web Yandex Translate](https://yandex.com/support/translate-desktop/en/) et ses applications mobiles prennent en charge le texte, les images, les sites web et les documents. Son client Android intègre un dictionnaire détaillé affichant transcriptions phonétiques, définitions, synonymes et flexions morphologiques pour les langues prises en charge.

Sur mobile, l'application Android est livrée avec un [dictionnaire hors ligne](https://yandex.ru/support/translate-app-android/en/offline-mobile) anglais-russe préinstallé, tandis que d'autres packs de langues peuvent être téléchargés pour la traduction hors ligne de texte saisi. L'interface de bureau gère les téléversements standards Office et PDF. Il convient de distinguer Yandex Translate en tant que service autonome et Yandex Browser, qui héberge des fonctionnalités propriétaires de doublage vocal automatique de vidéos.

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Interface web officielle de Yandex Translate" width="640"><br><sub>Interface de saisie et navigation latérale de Yandex Translate</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>
## 3. Documents à mise en page complexe et flux d'entreprise : préserver formats et actifs

Lors du traitement de diaporamas de présentation, de contrats de fournisseurs ou de manuels techniques, des mises en page altérées exigent d'importantes corrections manuelles. Ces outils privilégient la préservation de la disposition, le contrôle terminologique et la réutilisation des actifs.

<a id="deepl"></a>
### DeepL
[DeepL Translator](https://www.deepl.com/en/features) offre des options de configuration précises pour les flux de travail textuels et documentaires. Les utilisateurs peuvent élaborer des [Glossaires](https://www.deepl.com/en/features/glossary) afin d'imposer des traductions d'entreprise ou techniques privilégiées, et basculer entre des registres de ton formels ou informels dans les langues compatibles.

Son [service de traduction de documents](https://www.deepl.com/en/features/document-translation) accepte les fichiers Word, PDF, PPT, Excel, HTML et SRT (la prise en charge des formats variant selon le type de compte). L'écosystème du produit comprend également DeepL Write pour peaufiner le texte, [DeepL Voice pour les réunions en ligne](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings) pour les sous-titres en temps réel sur Teams et Zoom (nécessitant une licence Voice et les autorisations de l'hôte), ainsi qu'un guide officiel Model Context Protocol (MCP) pour les agents IA.

<p align="center"><img src="assets/deepl-page@2x.webp" alt="Espace officiel de traduction web de DeepL" width="640"><br><sub>Interface du traducteur web de DeepL</sub></p>

<a id="otranslator"></a>
### O.Translator
[O.Translator](https://otranslator.com/en/product-info) se concentre sur la traduction de documents avec préservation de la mise en page. Outre PDF, Word, PPT et Excel, il prend en charge des formats d'édition et de localisation tels que les e-books EPUB, InDesign (IDML), Illustrator (AI), OpenDocument, les fichiers de sous-titres (SRT/ASS) et les archives de bandes dessinées (CBZ/CBR), avec un OCR intégré pour les pages numérisées. La fidélité de la mise en page dépend de l'incorporation des polices et de l'expansion du texte cible.

Avant de traduire un fichier complet, O.Translator permet aux utilisateurs d'examiner un aperçu partiel de la mise en page. Il prend en charge l'importation de glossaires via XLSX ou TBX et fournit une [API développeur](https://www.otranslator.com/en/developer/v1). Son option multimédia est conçue pour transcrire des fichiers audio et vidéo téléversés en fichiers de sous-titres, plutôt que pour la traduction en direct de flux de navigateur en temps réel.

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="Page d'accueil officielle d'O.Translator" width="640"><br><sub>Page d'accueil d'O.Translator et section de téléversement de documents</sub></p>

<a id="simplifyai"></a>
### SimplifyAI
SimplifyAI exploite deux sites web distincts : un [atelier de documents complexes](https://simplifyai.cn/zh/translate) piloté par l'IA (simplifyai.cn/zh) et un [portail général de traduction de documents](https://translate.simplifyai.cn/) (translate.simplifyai.cn).

Au sein de l'atelier, le système peut extraire les termes à haute fréquence avant la traduction pour validation par l'utilisateur sur les fichiers Word, PPTX, InDesign, PDF et EPUB. L'atelier propose également l'édition par IA pour Word et InDesign (prenant en charge le suivi des modifications natif de Word), l'exportation de données bilingues (Excel/XLIFF), l'extraction structurée en Markdown/JSON et des contrôles visuels des débordements de texte et de disposition des polices, ce qui le rend particulièrement adapté au prépresse et à la localisation d'actifs graphiques. Pour les traductions courantes et directes de fichiers au quotidien, le portail général de traduction propose un flux plus simple et direct.

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="Page d'accueil officielle de SimplifyAI" width="640"><br><sub>Page d'accueil de SimplifyAI présentant son atelier de documents complexes et ses modules</sub></p>

<a id="lingvanex"></a>
### Lingvanex
[Lingvanex](https://lingvanex.com/) fournit des clients pour ordinateur de bureau, mobile et navigateur sur Windows et macOS. Son [traducteur de bureau pour Windows](https://lingvanex.com/products/windows-translator/) prend en charge des raccourcis globaux à l'échelle du système (comme un double appui sur Ctrl+C sur le texte surligné) et permet la traduction hors ligne de texte et de fichiers locaux DOCX/ODT après avoir téléchargé les packs linguistiques.

Au-delà des applications grand public, Lingvanex propose le logiciel de bureau téléchargeable [Secure Translation Software](https://lingvanex.com/products/secure-translation-software/) pour un usage d'entreprise hors ligne, ainsi que des solutions distinctes de traduction automatique sur site (On-premise) pour les environnements de réseaux privés.

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Page d'accueil officielle de Lingvanex" width="640"><br><sub>Page d'accueil de Lingvanex présentant les solutions de traduction d'entreprise et sur site</sub></p>

<a id="systran"></a>
### SYSTRAN
SYSTRAN répond aux exigences de localisation des entreprises et des institutions. Son service cloud, [SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/), est directement accessible pour les fichiers Word, PowerPoint, Excel et PDF, offrant des modèles spécialisés préconfigurés pour la documentation juridique, financière et industrielle, aux côtés de glossaires personnalisés et de mémoires de traduction (TM).

Pour les organisations ayant des exigences strictes en matière de souveraineté des données, SYSTRAN propose [Translate Server](https://www.systransoft.com/translation-products/translate-server/) pour un déploiement sur site derrière les pare-feu d'entreprise, des environnements dédiés de cloud privé et des [API](https://www.systransoft.com/translation-products/translate-api/) de traitement par lots pour les chaînes documentaires.

<p align="center"><img src="assets/systran-page@2x.webp" alt="Page officielle du produit SYSTRAN Translate Pro" width="640"><br><sub>Interface officielle de présentation du produit SYSTRAN Translate Pro</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>
## 4. Rédaction académique, révision et collaboration homme-machine : peaufiner le texte final

La traduction n'est souvent que la phase initiale d'un flux de rédaction ou de recherche plus vaste. Vérifier les définitions de dictionnaires, peaufiner les formulations et procéder à une édition interactive homme-machine contribuent à garantir le respect des normes académiques formelles.

<a id="youdao-translate-netease-youdao"></a>
### Youdao Translate (NetEase Youdao)
Connecté à l'écosystème de dictionnaires de NetEase Youdao, [Youdao Translate](https://fanyi.youdao.com/) associe consultation de vocabulaire, traduction et assistance rédactionnelle. En plus de la traduction standard de textes et de fichiers, son portail web propose des rubriques dédiées à la « Traduction d'articles arXiv » et au polissage de textes académiques.

Après avoir traduit des extraits de recherche, les utilisateurs peuvent lancer des vérifications grammaticales, évaluer le choix des synonymes ou ajuster le ton académique, ce qui aide les étudiants et les chercheurs à analyser la littérature étrangère et à rédiger des manuscrits. Les formats et les langues pris en charge pour le polissage d'articles et les modules multimédias diffèrent de la simple recherche dans le dictionnaire général.

<p align="center"><img src="assets/youdao-page@2x.webp" alt="Espace de travail web officiel de NetEase Youdao Translate" width="640"><br><sub>Interface web de NetEase Youdao Translate et navigation des fonctionnalités</sub></p>

<a id="baidu-translate"></a>
### Baidu Translate
[Baidu Translate](https://fanyi.baidu.com/) offre une large couverture applicative pour les utilisateurs sinophones. Son logiciel de bureau propose une fenêtre flottante compacte et la sélection de texte par raccourci dans les applications de bureau locales, tandis que son application mobile associe traduction photo, pratique orale et références de dictionnaires.

De plus, Baidu héberge un [portail autonome de traduction vidéo](https://fanyi-video.baidu.com/). Les utilisateurs téléversent des fichiers multimédias pour générer des pistes de sous-titres bilingues synchronisées, les réviser et les modifier dans un éditeur en ligne, puis exporter les fichiers de sous-titres finalisés. Il s'agit d'un outil de post-production basé sur le téléversement plutôt que d'un interprète automatique pour la lecture web en direct.

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Page officielle du site web de Baidu Translate" width="640"><br><sub>Interface web officielle de Baidu Translate</sub></p>

<a id="transmart-tencent-interactive-translation"></a>
### TranSmart (Tencent Interactive Translation)
Développé par Tencent AI Lab, [TranSmart](https://transmart.qq.com/zh-CN/intro) est conçu autour d'une collaboration interactive homme-machine. Plutôt que de générer une sortie statique à copier, TranSmart suggère en temps réel des complétions prédictives au niveau du mot et de la phrase, intégrant les paires bilingues validées dans la mémoire de traduction active.

Les traducteurs peuvent placer leur curseur n'importe où dans le texte traduit pour effectuer des modifications, ce qui incite le système à actualiser dynamiquement les suggestions en aval. Cela laisse les décisions terminologiques et le rythme des phrases entre les mains de l'utilisateur, opérant comme un éditeur collaboratif dont l'orientation se distingue des applications mobiles grand public de dictionnaire autonome de Tencent.

<p align="center"><img src="assets/transmart-page@2x.webp" alt="Page web officielle de Tencent TranSmart" width="640"><br><sub>Interface web officielle de Tencent TranSmart</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>
### LingoCloud (Caiyun Xiaoyi)
[LingoCloud](https://www.caiyunapp.com/?lang=zh) est largement utilisé pour les flux de travail en chinois, anglais et japonais. Son extension de navigateur offre une lecture web bilingue dans la page avec prise en charge de glossaires publics partagés et personnels. Son [service de traduction de documents](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html) (faisant référence aux directives de l'application mobile) accepte des formats tels que PDF, Word, PPT, Excel, EPUB, TXT et SRT, fournissant des fichiers téléchargés principalement au format PDF ou Word selon le fichier source.

Son logiciel de bureau intègre également [LingoCloud Interpretation](https://www.caiyunapp.com/interpretation/), qui peut capturer l'audio du microphone ou intercepter la sortie audio système des applications en cours d'exécution (comme Zoom, Teams ou Chrome sous Windows) pour afficher des sous-titres bilingues en temps réel. L'interprétation sur ordinateur est soumise aux limites de capture audio du système d'exploitation : sous Windows, la capture audio système fonctionne sur les applications de conférence et multimédias prises en charge ; sous macOS, les canaux d'enregistrement audio système interne ne sont actuellement pas pris en charge en raison des mises à jour du système macOS, laissant la capture par microphone comme seule méthode opérationnelle.

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="Page officielle du site web de LingoCloud" width="640"><br><sub>Interface web officielle de LingoCloud</sub></p>

<a id="quillbot-translate"></a>
### QuillBot Translate
[QuillBot Translate](https://quillbot.com/translate) fonctionne au sein de l'écosystème de rédaction et d'édition de QuillBot. Lors de la traduction de texte, l'interface propose des options de niveau de formalité et affiche les définitions et synonymes dans les langues prises en charge.

Le texte traduit peut être copié directement dans son paraphraseur (Paraphraser) et son vérificateur grammatical (Grammar Checker) pour améliorer la fluidité des phrases. La plateforme propose également une page dédiée [Translate PDF](https://quillbot.com/translate-pdf) pour téléverser et réviser des documents PDF uniques. Les langues prises en charge varient entre les outils de traduction, de grammaire et de paraphrase.

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="Page officielle de l'extension QuillBot sur le Chrome Web Store" width="640"><br><sub>Page officielle du produit sur le Chrome Web Store pour l'extension de navigateur QuillBot</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>
## 5. Écosystème open source : moteurs locaux, API, clients de bureau et chaînes de traitement pour PDF scientifiques

Les développeurs, les équipes soucieuses de la confidentialité et les chercheurs universitaires ont souvent besoin de code inspectable, d'une exécution locale hors ligne ou de flux d'automatisation personnalisés. L'écosystème de traduction open source s'articule autour de plusieurs couches architecturales distinctes :

- **Outils de mise en page pour PDF scientifiques** : Traduire des articles universitaires complexes tout en préservant les dispositions multicolonnes, les formules et les figures.
- **Services de traduction auto-hébergeables** : Fournir des points de terminaison d'API REST HTTP et des interfaces web pour un déploiement sur réseau local.
- **Moteurs de traduction hors ligne intégrés** : Exécuter la traduction automatique neuronale localement via des bibliothèques Python sans dépendances réseau externes.
- **Interfaces de bureau et de terminal** : Intégrer la consultation multi-moteurs, la surveillance du presse-papiers, l'OCR et les pipelines shell.

> [!IMPORTANT]
> Exécuter du code open source localement ne garantit pas automatiquement que les traductions s'effectuent hors ligne ou de manière privée. Un outil peut très bien tourner en local tout en interrogeant des API cloud par défaut. Une traduction véritablement hors ligne requiert à la fois des modèles locaux et un moteur de traduction local.

<a id="51-scientific--academic-pdf-pipelines"></a>
### 5.1 Chaînes de traitement pour PDF scientifiques et académiques

<a id="pdfmathtranslate-pdf2zh"></a>
#### PDFMathTranslate (pdf2zh)
[PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) (GNU AGPL v3) est un outil open source taillé pour les documents PDF scientifiques et académiques. Il préserve la structure des articles en plusieurs colonnes, la notation mathématique, les graphiques intégrés, les tables des matières et les annotations.

- **Sorties bilingues et unilingues** : Génère à la fois des documents traduits seuls (`-mono.pdf`) et des documents comparatifs bilingues (`-dual.pdf`).
- **Interfaces et intégrations** : Propose des outils en ligne de commande (CLI), une interface Web interactive, un déploiement en conteneur Docker et la prise en charge du Model Context Protocol (MCP). Un plugin d'intégration avec Zotero est disponible sous forme de projet connexe.
- **Moteurs de traduction dorsaux** : Utilise une architecture modulaire prenant en charge Google Translate (valeur par défaut documentée), DeepL, les API compatibles OpenAI et les instances locales d'Ollama. Un déploiement local via Docker ou WebUI n'implique pas un fonctionnement hors ligne si des backends cloud sont configurés.
- **Prise en charge de l'OCR** : Comprend un OCR expérimental pour les pages numérisées avec texte noir sur fond blanc (télécharge les ressources du modèle linguistique lors de la première utilisation, qui peuvent ensuite être réutilisées localement).

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="Page officielle du dépôt GitHub de PDFMathTranslate" width="640"><br><sub>Présentation officielle du dépôt PDFMathTranslate illustrant la traduction de PDF académiques avec mise en page et les flux CLI/WebUI</sub></p>

<a id="babeldoc"></a>
#### BabelDOC
[BabelDOC](https://github.com/funstory-ai/BabelDOC) (GNU AGPL v3) est une bibliothèque de traduction et de comparaison bilingue d'articles scientifiques au niveau document, conçue principalement pour être intégrée dans des applications Python, accompagnée d'un CLI de débogage.

- **Contrôle de la disposition et de la sortie** : Prend en charge les sorties unilingues ou bilingues, la comparaison côte à côte sur la même page ou l'alternance de pages originales/traduites, la traduction sélective de pages, le découpage et la fusion de PDF volumineux, l'importation de glossaires personnalisés en CSV et la préservation des formules. La traduction du texte des tableaux est explicitement documentée comme expérimentale.
- **Architecture dorsale** : Nécessite la configuration d'un backend de traduction via des points de terminaison compatibles OpenAI ou une instance locale d'Ollama. En tant que moteur de traitement de PDF et de mise en page, il n'intègre pas de moteur de traduction universel en soi.
- **Ressources hors ligne et périmètre** : Propose des routines de préchauffage (warmup) ainsi que la génération et la restauration de ressources hors ligne pour les modèles de mise en page et les polices. Une exécution entièrement hors ligne requiert à la fois des ressources pré-mises en cache et un backend de traduction exécuté localement (comme Ollama en local). La documentation souligne une validation principale sur les flux de travail anglais-chinois, avec une solution OCR expérimentale pour le texte noir sur fond blanc.

<p align="center"><img src="assets/babeldoc-page.webp" alt="Page officielle du dépôt GitHub de BabelDOC" width="640"><br><sub>Présentation officielle du dépôt BabelDOC démontrant les capacités de la bibliothèque de traduction de PDF scientifiques au niveau document</sub></p>

<a id="52-self-hostable-engines--apis"></a>
### 5.2 Moteurs auto-hébergeables et API

<a id="libretranslate"></a>
#### LibreTranslate
[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) (GNU AGPL v3) est un service d'API de traduction automatique libre et open source, auto-hébergeable, doté d'une interface web intégrée et conçu sur le moteur Argos Translate.

- **API et service web** : Expose des points de terminaison d'API REST pour la traduction de texte, la détection de la langue source et la gestion du HTML/balisage. Il fonctionne comme une couche de service indépendante plutôt que comme un proxy vers des API de traduction commerciales.
- **Déploiement local et confidentialité** : Peut fonctionner intégralement sur du matériel local sans envoyer de données à des tiers une fois les dépendances et les modèles linguistiques installés. L'utilisation d'une instance hébergée publique reste tributaire du réseau. Le contrôle d'accès par clé API peut être activé ou désactivé selon les exigences de l'hôte.
- **Couverture linguistique et formats de fichiers** : Les paires de langues disponibles dépendent des modèles linguistiques installés. Grâce à des projets complémentaires comme argos-translate-files, la traduction de fichiers prend en charge des formats tels que TXT, ODT, ODP, DOCX, PPTX, EPUB, HTML, SRT et PDF.

<p align="center"><img src="assets/libretranslate-page.webp" alt="Page officielle du dépôt GitHub de LibreTranslate" width="640"><br><sub>Présentation officielle du dépôt LibreTranslate montrant les fonctionnalités de l'API de traduction auto-hébergée et de l'interface web</sub></p>

<a id="argos-translate"></a>
#### Argos Translate
[Argos Translate](https://github.com/argosopentech/argos-translate) (Licence MIT / option CC0 déclarée dans le README) est une bibliothèque Python de traduction hors ligne et un outil en ligne de commande open source, doté d'un client graphique (GUI) installable séparément.

- **Paquets de modèles modulaires** : Télécharge et gère les paquets de modèles linguistiques utilisant l'extension `.argosmodel`. Lorsqu'une paire de langues directe n'est pas disponible, il peut utiliser une langue pivot intermédiaire installée (par exemple, traduire en passant par l'anglais).
- **Moteur de l'écosystème** : Sert de moteur de traduction automatique sous-jacent pour LibreTranslate. Des projets associés étendent ses capacités à la traduction HTML (`translate-html`) et au traitement de fichiers (`argos-translate-files`).
- **Fonctionnement hors ligne** : Fonctionne entièrement hors ligne une fois les modèles installés ; le téléchargement des index de paquets et des modèles initiaux requiert une connexion Internet.

<p align="center"><img src="assets/argos-translate-page.webp" alt="Page officielle du dépôt GitHub d'Argos Translate" width="640"><br><sub>Présentation officielle du dépôt Argos Translate détaillant le moteur de traduction hors ligne modulaire et le système de paquets</sub></p>

<a id="53-desktop--terminal-frontends"></a>
### 5.3 Interfaces de bureau et de terminal

<a id="pot-pot-desktop"></a>
#### Pot (pot-desktop)
[Pot](https://github.com/pot-app/pot-desktop) (GNU GPL v3) est un outil de traduction de bureau multiplateforme pour Windows, macOS et Linux, prenant en charge la traduction de sélection via des raccourcis clavier, la saisie tapée, la surveillance du presse-papiers, l'OCR de capture d'écran et la traduction de capture d'écran. Le dépôt GitHub officiel a été archivé le 7 septembre 2026 et est désormais en lecture seule (read-only).

- **Agrégation multi-services** : Permet d'interroger simultanément plusieurs services de traduction et de dictionnaires pour comparer les résultats côte à côte. Prend en charge la synthèse vocale (TTS), l'exportation de vocabulaire vers Anki et Eudic, ainsi que des extensions de plugins.
- **Backends et OCR modulaires** : Agrège des fournisseurs de traduction cloud, des API compatibles OpenAI et des points de terminaison locaux Ollama. Les choix d'OCR incluent des options natives de la plateforme (OCR système Windows, Apple Vision, Tesseract sous Linux), Tesseract.js ou des plugins locaux.
- **Modes d'exécution hors ligne** : La traduction de texte sélectionné ou saisi ne nécessite qu'un backend de traduction local configuré (tel qu'une instance locale d'Ollama) ; la traduction de capture d'écran requiert en outre un moteur OCR hors ligne (tel que l'OCR natif de la plateforme ou Tesseract). Les services cloud acheminent les requêtes via le réseau.

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Page officielle du dépôt GitHub du client de traduction de bureau Pot" width="640"><br><sub>Présentation officielle du dépôt du client de bureau Pot mettant en avant la traduction multi-interfaces, l'OCR et les flux liés au presse-papiers</sub></p>

<a id="translate-shell"></a>
#### Translate Shell
[Translate Shell](https://github.com/soimort/translate-shell) (The Unlicense / Domaine public) est un outil de traduction polyvalent en ligne de commande (exécutable `trans`) pour les environnements de terminaux de type Unix.

- **Recherche CLI et dictionnaire** : Prend en charge les définitions de mots, la traduction d'expressions, le mode dictionnaire concis, les sessions interactives REPL et l'identification de la langue directement dans le shell.
- **Pipelines Unix** : S'intègre aux flux d'entrée/sortie standard (`stdin` / `stdout`), traite directement les fichiers texte brut et prend en charge la synthèse vocale lorsqu'un lecteur audio externe est installé.
- **Couche moteur** : Fonctionne comme une interface client légère se connectant à des services de traduction publics (Google Translate par défaut, avec Bing Translator, Yandex.Translate et Apertium comme options supplémentaires).
- **Périmètre et limites** : N'embarque aucun modèle de traduction neuronale local ; le fonctionnement standard dépend d'une connectivité réseau externe vers les services moteurs sélectionnés. La traduction de fichiers est conçue pour les flux de texte brut et non pour les documents mis en page.

<p align="center"><img src="assets/translate-shell-page.webp" alt="Page officielle du dépôt GitHub de Translate Shell" width="640"><br><sub>Présentation officielle du dépôt Translate Shell montrant la traduction en ligne de commande dans le terminal et l'intégration aux pipelines</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>
## 6. Flux de travail de bout en bout connectés : [Equalang](https://equalang.com/?utm_source=github)

L'examen de ces outils montre que chaque service a développé des atouts indéniables pour des tâches spécifiques. Dans le travail quotidien, cependant, les exigences s'entrecroisent constamment :

Vous pouvez lire un livre blanc en ligne dans votre navigateur, télécharger le document PDF associé contenant tableaux et graphiques, visionner une conférence vidéo sans sous-titres, puis préparer une synthèse dans Word tout en échangeant directement avec des collaborateurs internationaux. Basculer entre des outils logiciels isolés et des convertisseurs de fichiers morcelle le flux de travail.

Nous avons conçu **[Equalang](https://equalang.com/?utm_source=github)** pour relier ces tâches au sein d'un flux de traduction continu et bilingue, offrant une assistance coordonnée sur les documents, les pages web, les vidéos et la communication directe.

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Page d'accueil officielle en anglais d'Equalang" width="640"><br><sub>Page d'accueil officielle du site web en anglais d'<a href="https://equalang.com/?utm_source=github">Equalang</a></sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>
### 1. Traduction de documents intégraux avec préservation de la mise en page
Lors de la traduction de documents complets, [Equalang](https://equalang.com/?utm_source=github) privilégie la préservation structurelle et l'utilisabilité après traduction, en proposant des flux de travail adaptés à la littérature de recherche, aux présentations et aux fichiers bureautiques quotidiens :

- **Documents PDF et lecture** : [Equalang](https://equalang.com/?utm_source=github) préserve les mises en page multicolonnes, les en-têtes, les pieds de page et les légendes, en réunissant les phrases scindées par des sauts de page avant de les traduire, tout en conservant la structure des tableaux, les formules intégrées et les liens internes du document. Comme détaillé dans notre [guide pratique de lecture de PDF académiques](https://equalang.com/blog/translate-and-read-pdf-documents?utm_source=github), les lecteurs peuvent consulter le fichier traduit aux côtés de l'original dans une disposition côte à côte, appréhendant d'abord les arguments clés dans leur langue principale avant de recouper la terminologie et les données spécifiques sur la page originale.

- **Présentations PowerPoint** : Dans notre [guide de mise en forme de diaporamas](https://equalang.com/blog/translate-powerpoint-keep-formatting?utm_source=github), les fichiers PPTX traduits conservent des tableaux éditables natifs au lieu de les convertir en images statiques. Le style au niveau des mots — comme le gras, l'italique et les couleurs de police au sein d'une même phrase — est fidèlement reporté sur les segments traduits correspondants. Les termes clés et les titres restent cohérents d'une diapositive à l'autre, et les zones de texte réduisent automatiquement la taille des polices lorsque le texte traduit s'allonge, afin d'éviter tout débordement ou chevauchement sur les éléments graphiques.

- **Fichiers bureautiques Word et Excel** : Lors de notre [test vérifié de traduction Word](https://equalang.com/blog/translate-word-document-keep-formatting?utm_source=github), les fichiers DOCX traduits ont conservé les titres, les listes à puces, les tableaux tarifaires et la mise en forme en gras, permettant une édition directe dans Microsoft Word. Dans notre [validation de grille tarifaire Excel](https://equalang.com/blog/translate-excel-file?utm_source=github), les formules et les valeurs numériques sont restées intactes tandis que les chaînes de texte en doublon réparties sur plusieurs cellules n'ont été traduites qu'une seule fois.

- **E-books et formats multimédias** : Les e-books EPUB conservent la navigation de la table des matières et les liens d'ancrage internes. Pour les fichiers audio et vidéo enregistrés jusqu'à 180 minutes, les tâches de traduction et de transcription sont soumises via notre API Développeur et l'intégration Agent Skill/MCP (plutôt que par un portail de téléversement documentaire général), produisant des fichiers de sous-titres bilingues horodatés SRT/VTT ou des transcriptions sources.

<a id="2-in-browser-reading--subtitle-generation"></a>
### 2. Lecture dans le navigateur et génération de sous-titres
Grâce à notre [extension de navigateur](https://equalang.com/extension?utm_source=github) légère (avec des guides d'installation pour Chrome, Edge et Firefox, ainsi qu'un mode temporaire Mac Safari pour Safari 18.4+), la traduction s'intègre directement à votre lecture quotidienne :

- **Lecture web bilingue sous les paragraphes** : Les paragraphes traduits s'affichent directement sous le texte original au fil du défilement. Une icône flottante peut être activée dans les paramètres pour la recherche de mots à la demande. Lors de la consultation de PDF locaux, les utilisateurs peuvent activer « Autoriser l'accès aux URL de fichiers » dans la gestion des extensions pour sélectionner des mots et obtenir leur traduction.

- **Sous-titres vidéo bilingues** : Compatible avec YouTube, Netflix, TikTok et Bilibili, comme abordé dans notre [guide de visionnage de vidéos bilingues](https://equalang.com/blog/watch-videos-with-bilingual-subtitles?utm_source=github). Au-delà de la traduction des sous-titres existants, l'extension peut capturer les flux audio pour générer en temps réel des sous-titres bilingues pour les **vidéos sans sous-titres** (sous réserve de l'environnement du navigateur et des limites de chiffrement des médias, validé sur les flux en direct et les bandes-annonces officielles de YouTube), tout en traduisant simultanément les commentaires du chat en direct sur YouTube.

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>
### 3. Communication orale et échanges sur place sans installation
Exiger de vos interlocuteurs qu'ils installent des applications mobiles dédiées crée des frictions, en particulier lors des déplacements. Lorsqu'il est connecté à Internet, [Equalang](https://equalang.com/?utm_source=github) assure la traduction de photos et l'interprétation vocale directement dans les navigateurs standards (ne nécessitant qu'une connexion initiale et l'autorisation de la caméra/du microphone de l'appareil lors de la première utilisation), comme présenté dans notre [guide de communication internationale](https://equalang.com/blog/talk-with-overseas-partners?utm_source=github) :

- **Traduction de photos sur mobile** : Face à des menus de restaurant, des panneaux ou des avis publics inconnus en voyage, les utilisateurs peuvent prendre une photo dans leur navigateur mobile. Les traductions se superposent directement sur la mise en page de la photo, ce qui facilite les commandes de repas ou la consultation d'avis par rapport à l'image originale, comme illustré dans notre [guide de traduction de photos en voyage](https://equalang.com/blog/photo-translation-for-travel?utm_source=github).

- **Mode face à face** : Conçu pour les situations en personne telles que la consigne de bagages à l'hôtel, la demande d'itinéraires ou les échanges à la réception. Deux interlocuteurs peuvent poser un téléphone ou une tablette à plat entre eux, en utilisant une vue inversée en écran partagé ou côte à côte avec transcription bidirectionnelle continue et exportation de la transcription, comme présenté dans notre [guide du face-à-face en voyage](https://equalang.com/blog/talk-face-to-face-while-traveling?utm_source=github).

- **Écoute en direct** : Ouvrez le portail web pendant une présentation ou une conférence en personne pour recevoir des sous-titres bilingues en temps réel captés par le microphone physique de l'appareil, avec synthèse vocale audio facultative et exportation de la transcription une fois terminé (à distinguer de la capture audio de médias en streaming par l'extension de navigateur).

- **Appels avec traduction** : Les hôtes se connectent sur le portail web pour générer un lien d'appel sécurisé et le partager via n'importe quelle application de messagerie. **Les invités rejoignent l'appel directement depuis leur navigateur sans créer de compte ni installer de logiciel** — ils saisissent simplement un nom d'affichage et l'hôte les admet pour commencer l'appel. Les deux parties parlent dans leur langue maternelle, entendent l'audio traduit et visualisent le texte en temps réel.

<a id="4-integration-for-ai-agents-and-developers"></a>
### 4. Intégration pour les agents IA et les développeurs
Pour aider les développeurs et les équipes à intégrer la traduction dans leurs flux automatisés :

- **API Développeur** : Propose des points de terminaison instantanés pour le texte ainsi que des traitements asynchrones de fichiers prenant en charge les nouvelles tentatives avec Idempotency-Key et les notifications par callback, comme détaillé dans notre [guide d'intégration de l'API de traduction de fichiers](https://equalang.com/blog/integrate-file-translation-api?utm_source=github).

- **Intégration Skill et MCP** : Nous maintenons des Agent Skills open source via [equalang-skill](https://github.com/equalang/equalang-skill) et la prise en charge officielle du Model Context Protocol via [@equalang/mcp](https://github.com/equalang/equalang-mcp). Dans des environnements tels que Claude Code, Codex ou WorkBuddy, transmettre une simple invite d'installation (prompt) et configurer votre clé API permettent à votre assistant IA de prendre en charge la traduction de documents et la transcription de médias directement dans votre flux de travail, conformément à notre [guide de traduction de fichiers avec les assistants IA](https://equalang.com/blog/translate-files-with-ai-assistants?utm_source=github).

---

<a id="7-task-based-decision-guide"></a>
## 7. Guide de décision basé sur les tâches

Pour vous aider à choisir l'outil adapté à votre travail actuel, reportez-vous à cette matrice des tâches :

| Tâche principale | Exigence fondamentale | Outils recommandés à essayer | Considérations clés |
| :--- | :--- | :--- | :--- |
| **Voyages et dialogue oral** | OCR photo, dialogue bidirectionnel, packs hors ligne et outils de voyage connectés | Google Translate, Apple Translate, Papago, [Equalang](https://equalang.com/?utm_source=github) | Téléchargez les packs linguistiques hors ligne dans Google, Apple ou Papago (en tenant compte des exigences matérielles) pour les zones à faible réseau ; en ligne, [Equalang](https://equalang.com/?utm_source=github) propose la traduction de photos et le dialogue face à face dans le navigateur sans installer d'application. |
| **Ateliers multi-appareils** | Présentations un-à-plusieurs, participation multi-appareils | Le répertoire ne répertorie actuellement aucun outil pour ce scénario. | Microsoft a retiré sa fonctionnalité de conversation multi-appareils et le mode Présentateur en 2026 (voir la section Microsoft Translator ci-dessus pour plus de détails), et c'est pourquoi le répertoire ne répertorie aucun outil ici actuellement. |
| **Lecture web approfondie** | Lecture sous les paragraphes sans quitter la page | Immersive Translate, [Equalang](https://equalang.com/?utm_source=github), Mate Translate | Utilisez Immersive Translate ou [Equalang](https://equalang.com/?utm_source=github) pour les paragraphes bilingues ; utilisez Mate Translate pour basculer entre les affichages de page entière ou enregistrer des mots dans les Phrasebooks sur Mac. |
| **Vidéos sans sous-titres et flux en direct** | Génération de sous-titres en temps réel, compatibilité de diffusion | [Equalang](https://equalang.com/?utm_source=github), Immersive Translate | Les deux outils peuvent générer des sous-titres à partir de l'audio brut sur les plateformes compatibles (comme YouTube) ; comparez les flux des extensions de navigateur pour le chat en direct et la gestion des flux. |
| **Articles académiques et PDF scientifiques** | Préservation des formules, structures en colonnes, texte entrecoupé par les sauts de page | PDFMathTranslate, BabelDOC, [Equalang](https://equalang.com/?utm_source=github) | PDFMathTranslate et BabelDOC fournissent des chaînes de traitement open source avec sortie PDF bilingue et backends LLM locaux/cloud ; [Equalang](https://equalang.com/?utm_source=github) propose une lecture côte à côte dans le navigateur et la préservation de la mise en page. |
| **Prépresse d'édition et formats graphiques** | InDesign, Illustrator, archives de bandes dessinées, contrôle qualité prépresse | SimplifyAI, O.Translator | Utilisez SimplifyAI et O.Translator pour InDesign (IDML) et le prépresse des actifs graphiques ; SimplifyAI intègre l'édition par IA avec le suivi des modifications natif de Word. |
| **Présentations et documents bureautiques** | Préservation des tableaux natifs, styles, formules et éditabilité | [Equalang](https://equalang.com/?utm_source=github), DeepL | [Equalang](https://equalang.com/?utm_source=github) préserve les tableaux et styles natifs PPTX avec ajustement adaptatif de la taille de police et maintien des formules Excel ; utilisez DeepL pour les fichiers Word/Office d'entreprise avec des glossaires. |
| **Rédaction académique et révision de texte** | Précision grammaticale, registre académique formel | Youdao Translate, QuillBot Translate, TranSmart | Youdao et QuillBot facilitent l'enchaînement de la traduction vers le perfectionnement du texte ; TranSmart propose une édition interactive avec l'humain dans la boucle. |
| **Recherche par raccourci clavier sur bureau et multi-moteurs** | Raccourcis globaux, OCR, comparaison de multiples moteurs | Pot, Mate Translate | Pot permet des requêtes simultanées sur plusieurs moteurs et l'OCR de captures d'écran sur Windows, Mac et Linux ; Mate offre un utilitaire natif dans la barre des menus de Mac. |
| **Scripts de terminal et pipelines shell** | Recherche CLI, pipelines stdin/stdout, scripts de texte brut | Translate Shell, Argos Translate | Translate Shell propose une traduction CLI légère via des moteurs distants ; Argos Translate fournit un CLI Python hors ligne avec des modèles locaux. |
| **API privée auto-hébergée et moteurs hors ligne** | Réseaux isolés (air-gap), aucune transmission de données à des tiers | LibreTranslate, Argos Translate, SYSTRAN, Lingvanex | LibreTranslate fournit un service d'API HTTP auto-hébergé et une interface WebUI ; Argos Translate lui sert de moteur sous-jacent sous forme de bibliothèque Python/CLI hors ligne avec des paquets de modèles modulaires ; SYSTRAN et Lingvanex proposent des déploiements sur site pour les entreprises. |
| **Flux de travail de bout en bout connectés** | Documents, sous-titres en streaming, appels web et agents IA | [Equalang](https://equalang.com/?utm_source=github) | Traitement documentaire unifié, sous-titres de médias non sous-titrés, appels via navigateur sans installation d'application et intégration directe avec Claude Code ou WorkBuddy. |

---

<a id="8-directory-principles--verification-criteria"></a>
## 8. Principes du répertoire et critères de vérification

Afin de préserver l'utilité pratique et l'exactitude factuelle de ce répertoire, les entrées respectent des critères stricts d'inclusion et d'évaluation :

1. **Fonctionnalités documentées plutôt qu'arguments marketing** : Les descriptions sont issues de la documentation officielle, des manuels d'utilisation et des fichiers sources confirmés des dépôts. Nous ne revendiquons aucune conservation parfaite de la mise en page ni prise en charge universelle des formats.
2. **Démarcations architecturales claires** : Nous distinguons nettement interfaces de traduction, couches de services auto-hébergeables, moteurs de traduction hors ligne et bibliothèques de mise en page documentaire. L'exécution locale de code open source est explicitement dissociée d'une véritable exécution hors ligne.
3. **Couverture orientée tâches** : Les outils sont regroupés selon leur pertinence pratique au sein des flux de travail. Nous ne tenons aucun classement subjectif par niveaux (tier lists), ni notation qualitative, ni tarification éphémère.
4. **Identité transparente de l'équipe de maintenance** : Ce catalogue est sélectionné et maintenu par l'équipe **[Equalang](https://equalang.com/?utm_source=github)**. [Equalang](https://equalang.com/?utm_source=github) y est présenté aux côtés d'autres outils avec des délimitations de fonctionnalités vérifiables et des prérequis système transparents.

**Mots-clés** : outils de traduction, traduction de documents, lecture web bilingue, traduction de PDF académiques, traduction open source, API de traduction automatique, préservation de la mise en page, agents IA.

---

<a id="9-sources"></a>
## 9. Sources

1. [Centre d'aide Google Translate](https://support.google.com/translate)
2. [Traduction de documents sur ordinateur de bureau Google Translate](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Assistance Apple : Guide de l'application Traduire pour iPhone](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Assistance Apple : Traduction en direct et disponibilité des fonctionnalités](https://support.apple.com/en-us/123720)
5. [Fonctionnalités mobiles de Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/)
6. [Microsoft Translator sur l'iOS App Store](https://apps.apple.com/us/app/microsoft-translator/id1018949559)
7. [Notes de version de Microsoft Speech SDK](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/releasenotes)
8. [Portail officiel NAVER Papago](https://papago.naver.com/)
9. [Fonctionnalités de clavier et hors ligne d'iTranslate](https://itranslate.com/features/keyboard-translations/index.html)
10. [Informations d'utilisation de Reverso Context](https://context.reverso.net/translation/about)
11. [Portail Reverso Documents](https://www.reverso.net/documents/en)
12. [Aide Yandex Translate pour ordinateur et mobile](https://yandex.com/support/translate-desktop/en/)
13. [Documentation d'Immersive Translate](https://immersivetranslate.com/)
14. [Informations sur le produit et formats d'O.Translator](https://otranslator.com/en/product-info)
15. [Atelier de documents complexes SimplifyAI](https://simplifyai.cn/zh/translate)
16. [Traduction générale de documents SimplifyAI](https://translate.simplifyai.cn/)
17. [Fonctionnalités de Mate Translate](https://matetranslate.com/en)
18. [Traducteur Windows de Lingvanex](https://lingvanex.com/products/windows-translator/)
19. [Logiciel de traduction sécurisée Lingvanex (Secure Translation Software)](https://lingvanex.com/products/secure-translation-software/)
20. [SYSTRAN Translate Pro et déploiements d'entreprise](https://www.systransoft.com/translation-products/translate-pro/)
21. [NetEase Youdao Translate](https://fanyi.youdao.com/)
22. [Portail Baidu Translate et traduction vidéo](https://fanyi.baidu.com/)
23. [Présentation du produit Tencent TranSmart](https://transmart.qq.com/zh-CN/intro)
24. [Aide documentaire de Caiyun Xiaoyi (LingoCloud)](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
25. [Portail de traduction et PDF de QuillBot](https://quillbot.com/translate)
26. [Spécifications et documentation de l'API Equalang](https://equalang.com/llms-full.txt?utm_source=github)
27. [Dépôt GitHub officiel de PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate)
28. [Documentation des options avancées de PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
29. [Dépôt GitHub officiel de BabelDOC](https://github.com/funstory-ai/BabelDOC)
30. [Dépôt GitHub officiel de LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
31. [Documentation et guide d'API de LibreTranslate](https://docs.libretranslate.com/)
32. [Dépôt GitHub officiel d'Argos Translate](https://github.com/argosopentech/argos-translate)
33. [Dépôt GitHub officiel du client de bureau Pot](https://github.com/pot-app/pot-desktop)
34. [Dépôt GitHub officiel de Translate Shell](https://github.com/soimort/translate-shell)
