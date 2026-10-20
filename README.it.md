# Awesome Translation Tools

> Una directory curata di strumenti e flussi di lavoro per la traduzione: viaggi, lettura sul web, documenti impaginati, ricerca accademica, motori open source locali e pipeline per sviluppatori.

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

Le esigenze di traduzione variano profondamente in base al contesto: decifrare un cartello stradale o un menu da smartphone, consultare documentazione tecnica straniera nel browser, tradurre contratti e presentazioni complesse senza alterarne il layout, preservare le formule matematiche negli articoli scientifici, eseguire traduzioni batch riservate da terminale oppure seguire contenuti video privi di sottotitoli.

Siamo il team di **[Equalang](https://equalang.com/?utm_source=github)**. Questa directory propone una guida pratica e orientata alle attività per orientarsi tra i principali prodotti commerciali e progetti open source. Per ciascuno strumento abbiamo riassunto funzionalità documentate, modalità di accesso, opzioni di distribuzione e vincoli operativi, così da aiutarti a individuare la soluzione più adatta al tuo flusso di lavoro.

---

## Indice

- [1. Viaggi e conversazione in mobilità: input vocali e multimodali](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. Lettura contestuale sul web e apprendimento linguistico: leggere senza lasciare la pagina](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. Layout di documenti complessi e flussi aziendali: preservare formati e risorse](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. Scrittura accademica, revisione e collaborazione uomo-macchina: perfezionare i testi](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. Ecosistema open source: motori locali, API, client desktop e pipeline per PDF scientifici](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 Pipeline per PDF scientifici e accademici](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 Motori e API self-hostable](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 Frontend per desktop e terminale](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. Flussi di lavoro completi e integrati:](#6-connected-end-to-end-workflows-equalang) [Equalang](https://equalang.com/?utm_source=github)
  - [1. Traduzione di interi documenti con conservazione del layout](#1-whole-file-document-translation-with-layout-preservation)
  - [2. Lettura nel browser e generazione di sottotitoli](#2-in-browser-reading--subtitle-generation)
  - [3. Conversazione dal vivo e comunicazione sul posto senza installazione](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. Integrazione per agenti AI e sviluppatori](#4-integration-for-ai-agents-and-developers)
- [7. Guida alle decisioni basata sulle attività](#7-task-based-decision-guide)
- [8. Criteri della directory e requisiti di verifica](#8-directory-principles--verification-criteria)
- [9. Fonti](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>

## 1. Viaggi e conversazione in mobilità: input vocali e multimodali

I viaggi e le attività sul campo richiedono avvio rapido, riconoscimento multimodale affidabile e piena operatività offline quando la connessione di rete è assente o instabile.

<a id="google-translate"></a>

### Google Translate
L'[app mobile di Google Translate](https://support.google.com/translate) integra OCR istantaneo tramite fotocamera, importazione di immagini, inserimento della scrittura a mano libera e modalità di conversazione faccia a faccia con schermo diviso. Chi viaggia può scaricare in anticipo i pacchetti lingua per tradurre testi e inquadrature con la fotocamera anche offline. La modalità di conversazione vocale offre diversi layout di visualizzazione, sebbene l'interpretazione vocale simultanea offline sia limitata a specifici dispositivi Pixel e a una selezione di coppie linguistiche.

Sui browser desktop, Google Translate mette a disposizione un [portale dedicato alla traduzione di documenti](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en) che supporta file DOCX, PDF, PPTX e XLSX. Questo strumento desktop è progettato per documenti digitali nativi; le pagine PDF scansionate contenenti esclusivamente immagini vengono conservate nel file scaricato senza estrazione OCR del testo.

<p align="center"><img src="assets/google-page@2x.webp" alt="Pagina ufficiale di presentazione di Google Translate" width="640"><br><sub>Pagina ufficiale di presentazione di Google Translate e sezione per il download dell'app mobile</sub></p>

<a id="apple-translate"></a>

### Apple Translate
Per gli utenti di iPhone e iPad, l'applicazione di sistema [Apple Translate](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios) non richiede alcuna installazione separata. Gestisce digitazione di testo, input vocale, rilevamento del testo tramite fotocamera e conversazioni faccia a faccia su schermo condiviso. La modalità di conversazione è in grado di rilevare automaticamente quale lingua viene parlata, evitando di dover passare manualmente il microfono tra gli interlocutori. I pacchetti lingua scaricati consentono la consultazione testuale direttamente sul dispositivo, senza bisogno di connessione dati cellulare.

All'interno del sistema operativo Apple, le [funzionalità di traduzione in tempo reale](https://support.apple.com/en-us/123720) si estendono anche a Messaggi, Telefono e FaceTime. La traduzione in tempo reale delle telefonate fa parte di Apple Intelligence, richiede hardware e versioni di sistema compatibili ed è soggetta a criteri di disponibilità geografica (ad esempio, i dispositivi acquistati nella Cina continentale attualmente non supportano queste funzionalità avanzate di Apple Intelligence per le chiamate).

<p align="center"><img src="assets/apple-page@2x.webp" alt="Guida di supporto Apple per la traduzione su iPhone" width="640"><br><sub>Guida ufficiale del supporto Apple per la traduzione di parole e frasi su iPhone</sub></p>

<a id="microsoft-translator"></a>

### Microsoft Translator
L'[applicazione mobile di Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/) offre la traduzione del testo in 100+ lingue, la traduzione vocale in tempo reale e la traduzione di immagini. La sua funzionalità di conversazione multidispositivo (inclusi la modalità Relatore, i codici stanza e l'accesso da browser) è stata ritirata, come documentato nelle [note di rilascio di iOS App Store](https://apps.apple.com/us/app/microsoft-translator/id1018949559) e nelle [note di rilascio di Microsoft Speech SDK](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/releasenotes).

L'app per utenti finali non supporta la traduzione diretta di filmati, file video o registrazioni multimediali esterne. Mentre la [panoramica delle funzionalità di Microsoft](https://www.microsoft.com/en-us/translator/apps/features/) elenca la traduzione split-screen su un singolo dispositivo, i pacchetti linguistici offline e un frasario, l'attuale descrizione dell'App Store elenca la traduzione di testo, voce e immagini, quindi verifica all'interno dell'app prima di fare affidamento sui pacchetti offline o sul frasario.

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Pagina ufficiale delle funzionalità di Microsoft Translator" width="640"><br><sub>Lo screenshot mostra la pagina delle funzionalità di Microsoft acquisita a ottobre 2026, e la pagina descrive ancora la funzionalità di conversazione multidispositivo, che Microsoft ha ritirato.</sub></p>

<a id="papago"></a>

### Papago
Sviluppato da NAVER in Corea del Sud, [Papago](https://papago.naver.com/) offre funzionalità mirate per le lingue dell'Asia orientale, tra cui coreano, inglese, giapponese e cinese. Sui dispositivi mobili, l'[applicazione](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator) mette a disposizione il dialogo faccia a faccia, una modalità Edu per creare schede di studio a partire da testi cartacei e la finestra mobile Papago Mini, risultando molto pratica per ristoranti, trasporti e studio in Corea.

Per la traduzione delle pagine web, le modalità di accesso variano in base alla piattaforma: NAVER ha rimosso lo strumento indipendente di traduzione siti web dal portale desktop, indirizzando gli utenti PC verso il proprio browser [Whale](https://whale.naver.com/) basato su Papago, mentre l'[app mobile Papago](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE) mantiene l'opzione di traduzione dei siti web nel menu laterale. Scaricando i pacchetti lingua sui dispositivi compatibili con i requisiti di sistema (come specificato nella [documentazione offline di NAVER](https://help.naver.com/service/16448/contents/10663?osType=MOBILE), che richiede almeno 4 GB di RAM e Android 14+ con pacchetti vocali dedicati per l'audio), la modalità offline supporta testo e voce tra coreano, inglese, giapponese e cinese semplificato. Va notato che la modalità offline non include OCR da foto, modalità conversazione, pagine web o file di documenti.

<p align="center"><img src="assets/papago-page@2x.webp" alt="Interfaccia ufficiale di traduzione web di NAVER Papago" width="640"><br><sub>Area di lavoro per la traduzione web di NAVER Papago</sub></p>

<a id="itranslate"></a>

### iTranslate
[iTranslate](https://itranslate.com/) è noto soprattutto per l'integrazione della sua [estensione tastiera](https://itranslate.com/features/keyboard-translations/index.html). Durante la digitazione di messaggi su WhatsApp, iMessage o via email, gli utenti possono tradurre il testo direttamente all'interno dell'interfaccia della tastiera, evitando di passare continuamente da un'app all'altra.

Offre inoltre pacchetti scaricabili per le espressioni di viaggio più frequenti e frasari essenziali tramite i suoi [strumenti offline](https://itranslate.com/features/offline-translations/index.html), utili per ripassare i termini fondamentali prima di partire. La disponibilità delle funzioni varia a seconda del sistema operativo e le funzionalità vocali offline sono limitate a un numero ristretto di lingue principali.

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="Homepage ufficiale di iTranslate" width="640"><br><sub>Homepage di iTranslate con anteprime dell'interfaccia dell'applicazione mobile</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>

## 2. Lettura contestuale sul web e apprendimento linguistico: leggere senza lasciare la pagina

Quando si consultano articoli o documentazione in lingua straniera, passare continuamente a una scheda di traduzione esterna spezza la concentrazione. Gli strumenti contestuali integrano la traduzione direttamente nell'ambiente di lettura attivo.

<a id="immersive-translate"></a>

### Immersive Translate
[Immersive Translate](https://immersivetranslate.com/) è un'estensione per browser che inserisce i paragrafi tradotti direttamente sotto il testo originale, offrendo un'ordinata impaginazione bilingue a confronto. Supporta inoltre la generazione di e-book bilingui in formato EPUB, la visualizzazione di PDF e la traduzione del testo digitato nei campi di inserimento del browser.

Per i contenuti multimediali, Immersive Translate traduce le tracce di sottotitoli già presenti su piattaforme come YouTube e Netflix. Inoltre, la sua [traduzione video basata su AI](https://immersivetranslate.com/video/ai-video-translator/) impiega il riconoscimento vocale per generare sottotitoli bilingui per video privi di sottotitoli su piattaforme compatibili come YouTube, affiancata da un [portale dedicato alla traduzione live di YouTube](https://livetranslate.immersivetranslate.com/zh-CN). La generazione di sottotitoli da flussi audio non sottotitolati dipende dalla compatibilità del browser, dalla chiarezza dell'audio e dalle condizioni di streaming della piattaforma.

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Homepage ufficiale di Immersive Translate" width="640"><br><sub>Homepage di Immersive Translate e portale di download dell'estensione per browser</sub></p>

<a id="mate-translate"></a>

### Mate Translate
[Mate Translate](https://matetranslate.com/en) è sviluppato su misura per macOS, iOS e i principali browser desktop. Durante la navigazione, un doppio clic su una parola mostra una definizione istantanea in un pop-up, la selezione del testo attiva traduzioni contestuali rapide, la traduzione dell'intera pagina consente di alternare la vista originale e quella tradotta, ed è disponibile una comoda utility per la barra dei menu di Mac.

Per chi studia le lingue, Mate consente di fare clic sulle parole nelle pagine web o all'interno dei sottotitoli di Netflix per salvarle in un Frasario personalizzato, che supporta la suddivisione per categorie e l'esportazione in CSV per il ripasso esterno. Nei browser desktop come Chrome, l'estensione consente inoltre di selezionare il testo all'interno del visualizzatore PDF integrato per avviare direttamente la traduzione.

<p align="center"><img src="assets/mate-page@2x.webp" alt="Homepage ufficiale di Mate Translate" width="640"><br><sub>Homepage di Mate Translate con anteprime dell'interfaccia multipiattaforma</sub></p>

<a id="reverso"></a>

### Reverso
Per scrittori e studenti che desiderano verificare l'uso naturale dei vocaboli, [Reverso Context](https://context.reverso.net/translation/about) propone coppie di frasi bilingui tratte da dialoghi di film, testate internazionali e siti web multilingue, corredate da tabelle di coniugazione verbale e suggerimenti di sinonimi. Poiché le frasi di esempio provengono da corpora multilingui pubblici, è opportuno valutare l'adeguatezza del contesto per testi formali o specialistici.

Il suo portale per documenti, [Reverso Documents](https://www.reverso.net/documents/en), accetta file PDF, Word, PowerPoint, Excel e alcuni formati di localizzazione. Offre un'interfaccia di revisione segmento per segmento nel browser in cui i team possono collaborare alle modifiche prima di scaricare il file finale.

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Interfaccia di traduzione ufficiale di Reverso" width="640"><br><sub>Interfaccia di traduzione web e barra di navigazione di Reverso</sub></p>

<a id="yandex-translate"></a>

### Yandex Translate
Il [portale web di Yandex Translate](https://yandex.com/support/translate-desktop/en/) e le sue applicazioni mobili gestiscono testi, immagini, siti web e documenti. Il client per Android include un dizionario dettagliato che riporta trascrizioni fonetiche, definizioni, sinonimi e flessioni morfologiche per le lingue supportate.

Sui dispositivi mobili, l'app Android include un [dizionario offline](https://yandex.ru/support/translate-app-android/en/offline-mobile) preinstallato per la combinazione inglese-russo, mentre altri pacchetti lingua possono essere scaricati per la traduzione offline di testi digitati. L'interfaccia desktop supporta i formati Office standard e i PDF. È opportuno distinguere tra il servizio autonomo Yandex Translate e Yandex Browser, che integra invece funzionalità proprietarie di doppiaggio vocale automatico dei video.

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Interfaccia web ufficiale di Yandex Translate" width="640"><br><sub>Interfaccia di inserimento e navigazione laterale di Yandex Translate</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>

## 3. Layout di documenti complessi e flussi aziendali: preservare formati e risorse

Nel trattamento di presentazioni commerciali, contratti di fornitura o manuali tecnici, i layout alterati richiedono pesanti correzioni manuali. Questi strumenti danno priorità alla conservazione dell'impaginazione, al controllo terminologico e al riutilizzo delle risorse.

<a id="deepl"></a>

### DeepL
[DeepL Traduttore](https://www.deepl.com/en/features) offre opzioni di configurazione dettagliate per i flussi di lavoro su testi e documenti. Gli utenti possono creare [Glossari](https://www.deepl.com/en/features/glossary) per imporre la terminologia aziendale o tecnica preferita e alternare tra registri formali e informali nelle lingue supportate.

Il suo [servizio di traduzione documenti](https://www.deepl.com/en/features/document-translation) accetta file Word, PDF, PPT, Excel, HTML e SRT (la disponibilità dei formati varia in base al tipo di account). L'ecosistema di prodotti comprende anche DeepL Write per il perfezionamento stilistico, [DeepL Voice for Online Meetings](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings) per i sottotitoli in tempo reale su Teams e Zoom (che richiede licenza Voice e autorizzazioni dell'organizzatore) e una guida ufficiale al Model Context Protocol (MCP) per agenti AI.

<p align="center"><img src="assets/deepl-page@2x.webp" alt="Area di lavoro ufficiale per la traduzione web di DeepL" width="640"><br><sub>Interfaccia del traduttore web di DeepL</sub></p>

<a id="otranslator"></a>

### O.Translator
[O.Translator](https://otranslator.com/en/product-info) è focalizzato sulla traduzione di documenti con conservazione della struttura grafica. Oltre a PDF, Word, PPT ed Excel, supporta formati editoriali e di localizzazione come e-book EPUB, InDesign (IDML), Illustrator (AI), OpenDocument, file di sottotitoli (SRT/ASS) e archivi di fumetti (CBZ/CBR), con OCR integrato per le pagine scansionate. La precisione del layout dipende dall'incorporamento dei caratteri e dall'espansione del testo nella lingua di arrivo.

Prima di procedere alla traduzione dell'intero file, O.Translator consente di esaminare un'anteprima parziale dell'impaginazione. Supporta l'importazione di glossari tramite file XLSX o TBX e fornisce un'[API per sviluppatori](https://www.otranslator.com/en/developer/v1). L'opzione multimediale è concepita per la trascrizione di file audio e video caricati in formato sottotitoli, non per la traduzione in tempo reale di flussi nel browser.

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="Homepage ufficiale del prodotto O.Translator" width="640"><br><sub>Homepage di O.Translator e sezione di caricamento documenti</sub></p>

<a id="simplifyai"></a>

### SimplifyAI
SimplifyAI gestisce due siti web distinti: un [Workbench per documenti complessi](https://simplifyai.cn/zh/translate) (simplifyai.cn/zh) basato su AI e un [portale generale per la traduzione di documenti](https://translate.simplifyai.cn/) (translate.simplifyai.cn).

All'interno del workbench, il sistema può estrarre i termini ad alta frequenza prima della traduzione per sottoporli a revisione, operando su file Word, PPTX, InDesign, PDF ed EPUB. Il workbench offre inoltre funzioni di AI Editing per Word e InDesign (con supporto alle revisioni native di Word), esportazione di dati bilingui (Excel/XLIFF), estrazione strutturata in Markdown/JSON e verifiche visive su overflow di testo e impaginazione dei font, rendendolo particolarmente adatto alla prestampa e alla localizzazione di risorse grafiche. Per traduzioni quotidiane e dirette, il portale di traduzione generale offre un flusso più lineare.

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="Homepage ufficiale di SimplifyAI" width="640"><br><sub>Homepage di SimplifyAI che illustra il workbench per documenti complessi e i relativi moduli</sub></p>

<a id="lingvanex"></a>

### Lingvanex
[Lingvanex](https://lingvanex.com/) fornisce client desktop, mobili e per browser compatibili con Windows e macOS. Il suo [traduttore desktop per Windows](https://lingvanex.com/products/windows-translator/) supporta scorciatoie di sistema (come la doppia pressione di Ctrl+C sul testo selezionato) e consente la traduzione offline di testi e file locali DOCX/ODT previo download dei pacchetti lingua.

Accanto alle applicazioni consumer, Lingvanex offre il software desktop scaricabile [Secure Translation Software](https://lingvanex.com/products/secure-translation-software/) per l'uso aziendale offline, nonché soluzioni dedicate di traduzione automatica on-premise per ambienti di rete privati.

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Homepage ufficiale di Lingvanex" width="640"><br><sub>Homepage di Lingvanex con soluzioni di traduzione aziendale e on-premise</sub></p>

<a id="systran"></a>

### SYSTRAN
SYSTRAN si rivolge alle esigenze di localizzazione di aziende e istituzioni. Il suo servizio cloud, [SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/), è immediatamente utilizzabile per file Word, PowerPoint, Excel e PDF, offrendo modelli di dominio preconfigurati per la documentazione legale, finanziaria e industriale, oltre a glossari personalizzati e memorie di traduzione (TM).

Per le organizzazioni con requisiti stringenti di sovranità dei dati, SYSTRAN propone [Translate Server](https://www.systransoft.com/translation-products/translate-server/) per la distribuzione on-premise protetta da firewall aziendali, ambienti Private Cloud dedicati e [API](https://www.systransoft.com/translation-products/translate-api/) batch per pipeline di documenti.

<p align="center"><img src="assets/systran-page@2x.webp" alt="Pagina ufficiale del prodotto SYSTRAN Translate Pro" width="640"><br><sub>Interfaccia di presentazione ufficiale del prodotto SYSTRAN Translate Pro</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>

## 4. Scrittura accademica, revisione e collaborazione uomo-macchina: perfezionare i testi

La traduzione costituisce spesso la fase iniziale di un più ampio processo di stesura o ricerca. La verifica delle definizioni da dizionario, il perfezionamento del fraseggio e l'editing interattivo uomo-macchina contribuiscono a garantire standard formali e accademici rigorosi.

<a id="youdao-translate-netease-youdao"></a>

### Youdao Translate (NetEase Youdao)
Integrato con l'ecosistema di dizionari di NetEase Youdao, [Youdao Translate](https://fanyi.youdao.com/) collega ricerca lessicale, traduzione e assistenza alla scrittura. Oltre alla traduzione standard di testi e file, il suo portale web offre sezioni dedicate per la "Traduzione di paper arXiv" e il perfezionamento stilistico di testi accademici.

Dopo aver tradotto estratti di ricerca, gli utenti possono eseguire controlli grammaticali, valutare varianti sinonimiche o calibrare il registro accademico, aiutando studenti e ricercatori ad analizzare la letteratura scientifica internazionale e redigere manoscritti. I formati e le lingue supportate per il polishing dei paper e i moduli multimediali differiscono da quelli della consultazione generale del dizionario.

<p align="center"><img src="assets/youdao-page@2x.webp" alt="Area di lavoro web ufficiale di NetEase Youdao Translate" width="640"><br><sub>Interfaccia web e menu delle funzionalità di NetEase Youdao Translate</sub></p>

<a id="baidu-translate"></a>

### Baidu Translate
[Baidu Translate](https://fanyi.baidu.com/) garantisce un'ampia copertura di client per l'utenza sinofona. Il software desktop include una finestra mobile compatta e la traduzione rapida da tastiera su qualsiasi applicazione desktop locale, mentre l'app mobile unisce traduzione da fotocamera, esercitazione orale e consultazione di dizionari.

Inoltre, Baidu ospita un [portale autonomo di traduzione video](https://fanyi-video.baidu.com/). Gli utenti possono caricare file multimediali per generare tracce di sottotitoli bilingui allineate, revisionarle in un editor online ed esportare i file dei sottotitoli definitivi. Si tratta di uno strumento di post-produzione basato sul caricamento di file, non di un interprete automatico per la riproduzione in streaming dal vivo sul web.

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Pagina del sito web ufficiale di Baidu Translate" width="640"><br><sub>Interfaccia web ufficiale di Baidu Translate</sub></p>

<a id="transmart-tencent-interactive-translation"></a>

### TranSmart (Tencent Interactive Translation)
Sviluppato da Tencent AI Lab, [TranSmart](https://transmart.qq.com/zh-CN/intro) è strutturato attorno alla collaborazione interattiva tra uomo e macchina. Anziché limitarsi a generare un risultato statico da copiare, TranSmart suggerisce completamenti predittivi in tempo reale a livello di singola parola e di intera frase, integrando le coppie bilingui confermate nella memoria di traduzione attiva.

I traduttori possono posizionare il cursore in qualsiasi punto del testo tradotto per apportare modifiche, inducendo il sistema ad aggiornare dinamicamente i suggerimenti successivi. Questo approccio lascia le decisioni terminologiche e il ritmo della frase sotto il controllo diretto dell'utente, configurandosi come un editor collaborativo nettamente distinto dalle app mobili di consultazione di dizionari per il grande pubblico di Tencent.

<p align="center"><img src="assets/transmart-page@2x.webp" alt="Pagina web ufficiale di Tencent TranSmart" width="640"><br><sub>Interfaccia web ufficiale di Tencent TranSmart</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>

### LingoCloud (Caiyun Xiaoyi)
[LingoCloud](https://www.caiyunapp.com/?lang=zh) è ampiamente utilizzato nei flussi di lavoro in cinese, inglese e giapponese. La sua estensione per browser consente la lettura bilingue delle pagine web con supporto a glossari personali e pubblici condivisi. Il suo [servizio di traduzione documenti](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html) (secondo le indicazioni dell'app mobile) supporta formati quali PDF, Word, PPT, Excel, EPUB, TXT e SRT, restituendo i file elaborati principalmente in formato PDF o Word a seconda dell'estensione del documento originale.

Il software desktop include inoltre [LingoCloud Interpretation](https://www.caiyunapp.com/interpretation/), in grado di acquisire l'audio dal microfono o intercettare l'audio di sistema proveniente dalle applicazioni in esecuzione (come Zoom, Teams o Chrome su Windows) per mostrare sottotitoli bilingui in tempo reale. L'interpretazione su desktop è soggetta ai limiti di acquisizione audio del sistema operativo: su Windows l'acquisizione dell'audio di sistema funziona con le applicazioni multimediali e di videoconferenza supportate; su macOS, le modalità di registrazione interna dell'audio di sistema non sono attualmente supportate a causa degli aggiornamenti di sistema di macOS, lasciando l'acquisizione da microfono come unico canale operativo.

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="Pagina del sito web ufficiale di LingoCloud" width="640"><br><sub>Interfaccia web ufficiale di LingoCloud</sub></p>

<a id="quillbot-translate"></a>

### QuillBot Translate
[QuillBot Translate](https://quillbot.com/translate) opera all'interno dell'ecosistema di scrittura ed editing di QuillBot. Durante la traduzione del testo, l'interfaccia offre opzioni di formalità e mostra definizioni e sinonimi per le lingue supportate.

Il testo tradotto può essere trasferito direttamente agli strumenti Paraphraser e Grammar Checker per rifinire la scorrevolezza dei periodi. La piattaforma mette inoltre a disposizione una [pagina dedicata alla traduzione di PDF](https://quillbot.com/translate-pdf) per caricare ed esaminare singoli documenti PDF. Le lingue supportate variano tra gli strumenti di traduzione, grammatica e parafrasi.

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="Pagina ufficiale dell'estensione QuillBot sul Chrome Web Store" width="640"><br><sub>Pagina ufficiale del prodotto per l'estensione browser QuillBot sul Chrome Web Store</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>

## 5. Ecosistema open source: motori locali, API, client desktop e pipeline per PDF scientifici

Sviluppatori, team attenti alla privacy e ricercatori accademici hanno spesso bisogno di codice ispezionabile, esecuzione locale offline o pipeline di automazione personalizzate. L'ecosistema di traduzione open source si articola su diversi livelli architetturali ben distinti:

- **Strumenti di layout per PDF scientifici**: traducono paper accademici complessi preservando strutture a più colonne, formule e figure.
- **Servizi di traduzione self-hostable**: forniscono endpoint API REST HTTP e interfacce web per la distribuzione su reti locali.
- **Motori di traduzione offline integrabili**: eseguono la traduzione automatica neurale in locale tramite librerie Python, senza dipendenze da reti esterne.
- **Frontend per desktop e terminale**: integrano query multi-motore, monitoraggio degli appunti, OCR e pipeline per la shell.

> [!IMPORTANT]
> L'esecuzione di codice open source in locale non implica automaticamente che le traduzioni siano offline o private. Uno strumento può essere eseguito localmente pur interrogando API cloud per impostazione predefinita. Una traduzione realmente offline richiede sia le risorse del modello in locale sia un motore di traduzione locale.

<a id="51-scientific--academic-pdf-pipelines"></a>

### 5.1 Pipeline per PDF scientifici e accademici

<a id="pdfmathtranslate-pdf2zh"></a>

#### PDFMathTranslate (pdf2zh)
[PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) (GNU AGPL v3) è uno strumento open source progettato per documenti PDF scientifici e accademici. Conserva la struttura a più colonne degli articoli, la notazione matematica, le immagini incorporate, l'indice dei contenuti e le annotazioni.

- **Output doppi e singoli**: genera sia documenti nella sola lingua tradotta (`-mono.pdf`) sia file di confronto bilingue a fronte (`-dual.pdf`).
- **Interfacce e integrazioni**: fornisce strumenti da riga di comando (CLI), una WebUI interattiva, distribuzione in container Docker e supporto al Model Context Protocol (MCP). È disponibile anche un plugin collegato per l'integrazione con Zotero come progetto correlato.
- **Backend di traduzione**: adotta un'architettura modulare che supporta Google Translate (impostazione predefinita documentata), DeepL, API compatibili con OpenAI e istanze locali di Ollama. La distribuzione locale tramite Docker o WebUI non implica un funzionamento offline se sono configurati backend cloud.
- **Supporto OCR**: include OCR sperimentale per pagine scansionate con testo nero su sfondo bianco (al primo utilizzo scarica le risorse del modello linguistico, che possono poi essere riutilizzate localmente).

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="Pagina ufficiale del repository GitHub di PDFMathTranslate" width="640"><br><sub>Panoramica del repository ufficiale di PDFMathTranslate che illustra la traduzione del layout di PDF accademici e i flussi CLI/WebUI</sub></p>

<a id="babeldoc"></a>

#### BabelDOC
[BabelDOC](https://github.com/funstory-ai/BabelDOC) (GNU AGPL v3) è una libreria per la traduzione a livello di documento e il confronto bilingue di paper scientifici, progettata principalmente per essere integrata in applicazioni Python, accompagnata da una CLI di debug.

- **Controllo di layout e output**: supporta output singoli o doppi, confronto a fronte sulla stessa pagina o pagine originali e tradotte alternate, traduzione selettiva di pagine, divisione e unione di PDF di grandi dimensioni, importazione di glossari personalizzati in CSV e conservazione delle formule. La traduzione del testo delle tabelle è esplicitamente documentata come sperimentale.
- **Architettura del backend**: richiede la configurazione di un backend di traduzione tramite endpoint compatibili con OpenAI o un'istanza locale di Ollama. Trattandosi di un motore di elaborazione e impaginazione PDF, non include al proprio interno un motore di traduzione universale.
- **Risorse offline e limiti operativi**: fornisce procedure di pre-riscaldamento (warmup) e generazione/ripristino offline delle risorse per i modelli di layout del documento e i font. L'esecuzione completamente offline richiede sia le risorse pre-memorizzate nella cache sia un backend di traduzione in esecuzione locale (come un'istanza Ollama locale). La documentazione evidenzia una validazione mirata principalmente ai flussi dall'inglese al cinese, con una soluzione OCR sperimentale per testo nero su sfondo bianco.

<p align="center"><img src="assets/babeldoc-page.webp" alt="Pagina ufficiale del repository GitHub di BabelDOC" width="640"><br><sub>Panoramica del repository ufficiale di BabelDOC che mostra le funzionalità della libreria per la traduzione a livello di documento di PDF scientifici</sub></p>

<a id="52-self-hostable-engines--apis"></a>

### 5.2 Motori e API self-hostable

<a id="libretranslate"></a>

#### LibreTranslate
[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) (GNU AGPL v3) è un servizio API di traduzione automatica self-hostable, gratuito e open source, dotato di un'interfaccia web integrata e sviluppato sul motore Argos Translate.

- **API e servizio web**: espone endpoint API REST per la traduzione di testi, il rilevamento della lingua di partenza e la gestione di markup/HTML. Funziona come livello di servizio indipendente anziché come semplice proxy verso API di traduzione commerciali.
- **Distribuzione locale e privacy**: può essere eseguito interamente su hardware locale senza inviare dati a terze parti esterne una volta installate le dipendenze e i modelli linguistici. L'utilizzo di un'istanza pubblica ospitata online resta invece vincolato alla connessione di rete. Il controllo di accesso tramite chiave API può essere attivato o disattivato in base alle esigenze dell'host.
- **Copertura linguistica e formati di file**: le coppie di lingue disponibili dipendono dai modelli linguistici installati. Grazie a progetti complementari come argos-translate-files, la traduzione di file supporta formati tra cui TXT, ODT, ODP, DOCX, PPTX, EPUB, HTML, SRT e PDF.

<p align="center"><img src="assets/libretranslate-page.webp" alt="Pagina ufficiale del repository GitHub di LibreTranslate" width="640"><br><sub>Panoramica del repository ufficiale di LibreTranslate con le funzionalità dell'API di traduzione self-hosted e dell'interfaccia web</sub></p>

<a id="argos-translate"></a>

#### Argos Translate
[Argos Translate](https://github.com/argosopentech/argos-translate) (licenza MIT / opzione CC0 indicata nel README) è una libreria Python di traduzione offline open source e strumento a riga di comando, con un client GUI installabile separatamente.

- **Pacchetti di modelli modulari**: scarica e gestisce pacchetti di modelli linguistici con estensione `.argosmodel`. Quando non è disponibile una coppia linguistica diretta, può effettuare una traduzione a perno sfruttando coppie intermedie installate (ad esempio traducendo attraverso l'inglese).
- **Motore per l'ecosistema**: funge da motore di traduzione automatica sottostante per LibreTranslate. Progetti complementari ne estendono le capacità alla traduzione HTML (`translate-html`) e all'elaborazione di file (`argos-translate-files`).
- **Funzionamento offline**: funziona completamente offline una volta installati i modelli; il download iniziale dell'indice dei pacchetti e dei modelli richiede invece connettività Internet.

<p align="center"><img src="assets/argos-translate-page.webp" alt="Pagina ufficiale del repository GitHub di Argos Translate" width="640"><br><sub>Panoramica del repository ufficiale di Argos Translate con dettagli sul motore di traduzione offline modulare e sul sistema dei pacchetti</sub></p>

<a id="53-desktop--terminal-frontends"></a>

### 5.3 Frontend per desktop e terminale

<a id="pot-pot-desktop"></a>

#### Pot (pot-desktop)
[Pot](https://github.com/pot-app/pot-desktop) (GNU GPL v3) è uno strumento di traduzione desktop multipiattaforma per Windows, macOS e Linux, che supporta la traduzione del testo selezionato tramite scorciatoie, l'inserimento digitato, il monitoraggio degli appunti, l'OCR da screenshot e la traduzione di screenshot. Il repository GitHub ufficiale è stato archiviato dal proprietario il 7 settembre 2026 ed è ora in sola lettura.

- **Aggregazione multi-servizio**: consente di interrogare contemporaneamente più servizi di traduzione e dizionari per confrontare i risultati fianco a fianco. Supporta sintesi vocale (TTS), esportazione del lessico su Anki ed Eudic ed estensioni tramite plugin.
- **Backend modulari e OCR**: aggrega provider di traduzione cloud, API compatibili con OpenAI ed endpoint locali di Ollama. Le opzioni OCR includono soluzioni native del sistema operativo (OCR di sistema Windows, Apple Vision, Tesseract Linux), Tesseract.js o plugin locali.
- **Modalità di esecuzione offline**: la traduzione del testo digitato o selezionato richiede solo la configurazione di un backend di traduzione locale (come un'istanza locale di Ollama); la traduzione di screenshot richiede inoltre un motore OCR offline (come l'OCR nativo di sistema o Tesseract). I servizi cloud instradano invece le richieste attraverso la rete.

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Pagina ufficiale del repository GitHub per la traduzione desktop con Pot" width="640"><br><sub>Panoramica del repository ufficiale del client desktop Pot con evidenza di flussi di traduzione su più interfacce, OCR e appunti</sub></p>

<a id="translate-shell"></a>

#### Translate Shell
[Translate Shell](https://github.com/soimort/translate-shell) (The Unlicense / Dominio Pubblico) è un versatile strumento di traduzione a riga di comando (eseguibile `trans`) per ambienti di terminale Unix-like.

- **Consultazione CLI e dizionario**: supporta definizioni di vocaboli, traduzione di frasi, modalità dizionario concisa, sessioni REPL interattive e identificazione della lingua direttamente dalla shell.
- **Pipeline Unix**: si integra con i canali standard di input e output (`stdin` / `stdout`), elabora direttamente file di testo e supporta la sintesi vocale se è installato un riproduttore audio esterno.
- **Livello del motore**: funziona come frontend client leggero che si collega a servizi di traduzione pubblici (Google Translate per impostazione predefinita, Bing Translator, Yandex.Translate e Apertium).
- **Limiti operativi**: non include modelli neurali di traduzione locali; il funzionamento standard dipende dalla connettività di rete verso i servizi dei motori selezionati. La traduzione di file è pensata per flussi di testo semplice, non per documenti impaginati.

<p align="center"><img src="assets/translate-shell-page.webp" alt="Pagina ufficiale del repository GitHub di Translate Shell" width="640"><br><sub>Panoramica del repository ufficiale di Translate Shell con esempi di traduzione da riga di comando nel terminale e integrazione in pipeline</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>

## 6. Flussi di lavoro completi e integrati: [Equalang](https://equalang.com/?utm_source=github)

L'esame di questi strumenti evidenzia come ciascun servizio abbia sviluppato competenze ben definite per compiti specifici. Nel lavoro di ogni giorno, tuttavia, le esigenze finiscono spesso per intersecarsi:

Può capitare di leggere un white paper online nel browser, scaricare un PDF correlato ricco di tabelle e diagrammi, seguire una conferenza video senza sottotitoli e poi redigere una sintesi in Word coordinandosi direttamente con colleghi internazionali. Passare continuamente da un'applicazione all'altra e usare convertitori di file separati finisce per frammentare il flusso di lavoro.

Abbiamo progettato **[Equalang](https://equalang.com/?utm_source=github)** per unire queste attività in un'esperienza di traduzione fluida e con visualizzazione a fronte, fornendo un supporto coordinato tra documenti, pagine web, video e comunicazione dal vivo.

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Homepage ufficiale in inglese di Equalang" width="640"><br><sub>Homepage ufficiale del sito web in inglese di <a href="https://equalang.com/?utm_source=github">Equalang</a></sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>

### 1. Traduzione di interi documenti con conservazione del layout
Nella traduzione di documenti completi, [Equalang](https://equalang.com/?utm_source=github) si concentra sulla preservazione strutturale e sulla fruibilità post-traduzione, offrendo flussi di lavoro su misura per letteratura scientifica, presentazioni e file d'ufficio quotidiani:

- **Documenti PDF e lettura**: [Equalang](https://equalang.com/?utm_source=github) conserva l'impaginazione a più colonne, intestazioni, piè di pagina e didascalie, ricongiungendo le frasi spezzate dalle interruzioni di pagina prima della traduzione, mantenendo intatte strutture di tabelle, formule incorporate e collegamenti ipertestuali interni al documento. Come descritto nella nostra [guida alla lettura di PDF accademici](https://equalang.com/blog/translate-and-read-pdf-documents?utm_source=github), i lettori possono consultare il file tradotto accanto all'originale in un layout affiancato, cogliendo i passaggi chiave nella propria lingua prima di confrontare la terminologia specifica e i dati nella pagina originale.

- **Presentazioni PowerPoint**: Nella nostra [guida alla formattazione delle presentazioni](https://equalang.com/blog/translate-powerpoint-keep-formatting?utm_source=github), i file PPTX tradotti mantengono tabelle native completamente modificabili invece di convertirle in immagini statiche. Gli stili a livello di singola parola — come grassetto, corsivo e colori del testo all'interno di una stessa frase — vengono mappati con precisione sulle locuzioni tradotte corrispondenti. I termini chiave e le intestazioni rimangono coerenti tra le diapositive, mentre le caselle di testo ridimensionano automaticamente i caratteri in caso di espansione del testo tradotto, evitando sovrapposizioni su immagini o bordi.

- **File d'ufficio Word ed Excel**: Nel nostro [test di traduzione verificato su Word](https://equalang.com/blog/translate-word-document-keep-formatting?utm_source=github), i file DOCX tradotti hanno conservato intestazioni, elenchi puntati, tabelle di prezzi e formattazione in grassetto, consentendo la modifica diretta in Microsoft Word. Nella nostra [verifica su fogli di calcolo Excel con listini prezzi](https://equalang.com/blog/translate-excel-file?utm_source=github), formule e numeri sono rimasti intatti, mentre le stringhe di testo duplicate tra più celle sono state tradotte una sola volta.

- **E-book e media formattati**: Gli e-book in formato EPUB mantengono l'indice navigabile e i collegamenti di ancoraggio interni. Per i file audio e video registrati fino a 180 minuti, le richieste di traduzione e trascrizione vengono inoltrate tramite la nostra API per sviluppatori e l'integrazione con Agent Skill/MCP (anziché attraverso un generico portale di caricamento documenti sul web), producendo file di sottotitoli bilingui SRT/VTT con timestamp o trascrizioni del testo di partenza.

<a id="2-in-browser-reading--subtitle-generation"></a>

### 2. Lettura nel browser e generazione di sottotitoli
Attraverso la nostra [estensione per browser](https://equalang.com/extension?utm_source=github) leggera (con guide all'installazione per Chrome, Edge e Firefox, oltre a una modalità temporanea per Mac Safari su Safari 18.4+), la traduzione si inserisce con naturalezza nella lettura quotidiana:

- **Lettura bilingue con traduzione sotto il paragrafo**: I paragrafi tradotti compaiono direttamente sotto il testo originale durante lo scorrimento della pagina. Nelle impostazioni è possibile attivare un'icona mobile per la consultazione istantanea dei singoli vocaboli. Durante la visualizzazione di PDF locali, gli utenti possono abilitare l'opzione "Consenti l'accesso agli URL dei file" nella gestione delle estensioni per selezionare le parole da consultare.

- **Sottotitoli bilingui per video**: Compatibile con YouTube, Netflix, TikTok e Bilibili, come illustrato nella nostra [guida alla visione di video con sottotitoli bilingui](https://equalang.com/blog/watch-videos-with-bilingual-subtitles?utm_source=github). Oltre a tradurre i sottotitoli già esistenti, l'estensione è in grado di acquisire i flussi audio per generare sottotitoli bilingui in tempo reale per **video privi di sottotitoli** (compatibilmente con l'ambiente del browser e i vincoli di crittografia dei media, verificato su live stream e trailer ufficiali di YouTube), traducendo contestualmente anche i commenti della chat dal vivo su YouTube.

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>

### 3. Conversazione dal vivo e comunicazione sul posto senza installazione
Chiedere agli interlocutori di installare applicazioni mobili dedicate crea inutili attriti, soprattutto in viaggio. Con una connessione a Internet attiva, [Equalang](https://equalang.com/?utm_source=github) mette a disposizione la traduzione fotografica e l'interpretazione vocale direttamente nei browser standard (richiedendo soltanto un accesso iniziale e le autorizzazioni per fotocamera e microfono al primo utilizzo), come descritto nella nostra [guida alla comunicazione internazionale](https://equalang.com/blog/talk-with-overseas-partners?utm_source=github):

- **Traduzione di foto da mobile**: Di fronte a menu di ristoranti, cartelli o avvisi pubblici sconosciuti durante un viaggio, gli utenti possono scattare una foto direttamente dal browser dello smartphone. Le traduzioni vengono sovrapposte sull'immagine mantenendone l'impostazione grafica, rendendo semplice ordinare piatti o verificare avvisi a confronto con l'originale, come descritto nella nostra [guida alla traduzione fotografica in viaggio](https://equalang.com/blog/photo-translation-for-travel?utm_source=github).

- **Modalità faccia a faccia**: Concepita per situazioni dal vivo come il deposito bagagli in hotel, la richiesta di informazioni stradali o l'interazione alla reception. Due persone possono posizionare un unico smartphone o tablet tra loro, sfruttando la vista a schermo diviso invertito o affiancato con trascrizione bidirezionale continua ed esportazione della conversazione, come illustrato nella nostra [guida al dialogo faccia a faccia in viaggio](https://equalang.com/blog/talk-face-to-face-while-traveling?utm_source=github).

- **Ascolto dal vivo**: È possibile aprire il portale web durante una conferenza o presentazione dal vivo per ricevere sottotitoli bilingui in tempo reale acquisiti tramite il microfono fisico del dispositivo, con sintesi vocale opzionale ed esportazione della trascrizione al termine (funzionalità distinta dall'acquisizione dell'audio in streaming dell'estensione per browser).

- **Chiamate tradotte**: Gli organizzatori effettuano l'accesso al portale web per generare un link di chiamata protetto e condividerlo tramite qualsiasi app di messaggistica. **Gli ospiti partecipano direttamente dal browser senza dover creare un account o installare alcun software**—basta inserire un nome visualizzato e attendere che l'organizzatore li ammetta per avviare la chiamata. Ciascun interlocutore parla nella propria lingua madre, ascolta l'audio tradotto e legge il testo in tempo reale.

<a id="4-integration-for-ai-agents-and-developers"></a>

### 4. Integrazione per agenti AI e sviluppatori
Per aiutare sviluppatori e team a inserire la traduzione nei propri flussi di automazione:

- **API per sviluppatori**: Offre endpoint istantanei per il testo e processi asincroni per i file con supporto a tentativi basati su Idempotency-Key e notifiche via callback, come illustrato in dettaglio nella nostra [guida all'integrazione dell'API di traduzione file](https://equalang.com/blog/integrate-file-translation-api?utm_source=github).

- **Integrazione con Skill e MCP**: Manteniamo Agent Skill open source tramite [equalang-skill](https://github.com/equalang/equalang-skill) e supporto ufficiale al Model Context Protocol tramite [@equalang/mcp](https://github.com/equalang/equalang-mcp). In ambienti come Claude Code, Codex o WorkBuddy, inviando una sola istruzione di installazione e configurando la propria chiave API, il proprio assistente AI è pronto a gestire traduzione di documenti e trascrizione multimediale direttamente nel flusso di lavoro, seguendo la nostra [guida alla traduzione di file con assistenti AI](https://equalang.com/blog/translate-files-with-ai-assistants?utm_source=github).

---

<a id="7-task-based-decision-guide"></a>

## 7. Guida alle decisioni basata sulle attività

Per orientarti nella scelta dello strumento più adatto alle tue esigenze attuali, consulta questa matrice operativa:

| Attività principale | Requisito fondamentale | Strumenti consigliati da valutare | Considerazioni chiave |
| :--- | :--- | :--- | :--- |
| **Viaggi e dialogo vocale** | OCR da fotocamera, dialogo bidirezionale, pacchetti offline e strumenti di viaggio connessi | Google Translate, Apple Translate, Papago, [Equalang](https://equalang.com/?utm_source=github) | Scarica in anticipo i pacchetti lingua offline su Google, Apple o Papago (verificando i requisiti hardware) per le zone con scarsa copertura; in presenza di rete, [Equalang](https://equalang.com/?utm_source=github) offre traduzione fotografica e dialogo faccia a faccia direttamente nel browser senza installare app. |
| **Workshop e presentazioni multidispositivo** | Presentazioni uno-a-molti, partecipazione da più dispositivi | Attualmente la directory non elenca alcuno strumento per questo scenario. | Microsoft ha ritirato la funzionalità di conversazione multidispositivo e la modalità Relatore nel 2026 (vedere la sezione Microsoft Translator sopra per i dettagli), ed è per questo che la directory non elenca alcuno strumento qui al momento. |
| **Lettura approfondita sul web** | Lettura sotto il paragrafo senza abbandonare la pagina | Immersive Translate, [Equalang](https://equalang.com/?utm_source=github), Mate Translate | Usa Immersive Translate o [Equalang](https://equalang.com/?utm_source=github) per la visualizzazione a paragrafi bilingui; usa Mate Translate per alternare viste complete della pagina o salvare vocaboli nel Frasario su Mac. |
| **Video non sottotitolati e live stream** | Generazione di sottotitoli in tempo reale, compatibilità con lo streaming | [Equalang](https://equalang.com/?utm_source=github), Immersive Translate | Entrambi gli strumenti sono in grado di generare sottotitoli direttamente dall'audio grezzo sulle piattaforme compatibili (come YouTube); confronta i flussi delle rispettive estensioni browser per chat dal vivo e gestione dello streaming. |
| **Articoli accademici e PDF scientifici** | Conservazione delle formule, strutture a colonne, testo a cavallo di pagina | PDFMathTranslate, BabelDOC, [Equalang](https://equalang.com/?utm_source=github) | PDFMathTranslate e BabelDOC mettono a disposizione pipeline open source con output a doppio PDF e backend LLM locali o cloud; [Equalang](https://equalang.com/?utm_source=github) offre lettura affiancata nel browser e conservazione accurata del layout. |
| **Prestampa editoriale e formati grafici** | InDesign, Illustrator, archivi di fumetti, controllo qualità di prestampa | SimplifyAI, O.Translator | Usa SimplifyAI e O.Translator per InDesign (IDML) e prestampa di risorse grafiche; SimplifyAI include funzioni di AI Editing con tracciamento delle modifiche nativo per Word. |
| **Presentazioni e documenti d'ufficio** | Conservazione di tabelle native, stili, formule e modificabilità | [Equalang](https://equalang.com/?utm_source=github), DeepL | [Equalang](https://equalang.com/?utm_source=github) mantiene tabelle e stili nativi nei file PPTX con adattamento automatico dei font e conserva le formule in Excel; usa DeepL per documenti aziendali Word/Office con glossari. |
| **Scrittura e revisione accademica** | Correttezza grammaticale, registro scientifico formale | Youdao Translate, QuillBot Translate, TranSmart | Youdao e QuillBot collegano direttamente la traduzione al perfezionamento del testo; TranSmart fornisce un ambiente di editing collaborativo uomo-macchina. |
| **Ricerca rapida con scorciatoia desktop e multi-motore** | Scorciatoie globali, OCR, confronto tra più motori | Pot, Mate Translate | Pot consente interrogazioni simultanee su più motori e OCR da screenshot su Windows, Mac e Linux; Mate offre un'utility nativa integrata nella barra dei menu di Mac. |
| **Scripting da terminale e pipeline per la shell** | Consultazione CLI, pipeline stdin/stdout, script per testo semplice | Translate Shell, Argos Translate | Translate Shell offre traduzione leggera da CLI appoggiandosi a motori remoti; Argos Translate fornisce una CLI Python offline basata su modelli locali. |
| **API privata self-hosted e motori offline** | Reti isolate (air-gapped), nessun transito di dati verso terzi | LibreTranslate, Argos Translate, SYSTRAN, Lingvanex | LibreTranslate fornisce un servizio API HTTP self-hosted e una WebUI; Argos Translate ne costituisce il motore offline come libreria/CLI Python con pacchetti di modelli modulari; SYSTRAN e Lingvanex propongono installazioni on-premise per ambienti enterprise. |
| **Flussi di lavoro completi e integrati** | Documenti, sottotitoli in streaming, chiamate web e agenti AI | [Equalang](https://equalang.com/?utm_source=github) | Gestione unificata di documenti, sottotitoli multimediali da audio privo di testo, chiamate via browser senza installazione e integrazione diretta con Claude Code o WorkBuddy. |

---

<a id="8-directory-principles--verification-criteria"></a>

## 8. Criteri della directory e requisiti di verifica

Per preservare l'utilità pratica e l'accuratezza fattuale di questa directory, le schede rispettano rigorosi criteri di inclusione e revisione:

1. **Funzionalità documentate prima dei claim promozionali**: Le descrizioni derivano da documentazione ufficiale, manuali utente e codice sorgente verificato dei repository. Non vengono dichiarate conservazioni perfette dell'impaginazione né compatibilità universali con qualsiasi formato.
2. **Confini architetturali ben definiti**: Viene tracciata una netta distinzione tra frontend di traduzione, livelli di servizio self-hostable, motori di traduzione offline e librerie di impaginazione per documenti. L'esecuzione locale di codice open source è chiaramente distinta dall'effettivo funzionamento offline.
3. **Approccio orientato alle attività**: Gli strumenti sono raggruppati in base all'adeguatezza pratica rispetto ai vari flussi di lavoro. Non vengono stilate classifiche soggettive a livelli, graduatorie qualitative né indicazioni tariffarie temporanee.
4. **Identità trasparente dei curatori**: Questa directory è curata e mantenuta dal team di **[Equalang](https://equalang.com/?utm_source=github)**. [Equalang](https://equalang.com/?utm_source=github) è presentata accanto agli altri strumenti specificando con chiarezza i limiti operativi delle funzionalità e i requisiti di sistema necessari.

**Parole chiave**: strumenti di traduzione, traduzione documenti, lettura web bilingue, traduzione PDF accademici, traduzione open source, API traduzione automatica, conservazione del layout, agenti AI.

---

<a id="9-sources"></a>

## 9. Fonti

1. [Centro assistenza di Google Translate](https://support.google.com/translate)
2. [Traduzione documenti desktop di Google Translate](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Supporto Apple: Guida all'app Traduci per iPhone](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Supporto Apple: Traduzione in tempo reale e disponibilità delle funzionalità](https://support.apple.com/en-us/123720)
5. [Funzionalità mobili di Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/)
6. [Microsoft Translator su iOS App Store](https://apps.apple.com/us/app/microsoft-translator/id1018949559)
7. [Note di rilascio di Microsoft Speech SDK](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/releasenotes)
8. [Portale ufficiale di NAVER Papago](https://papago.naver.com/)
9. [Funzionalità tastiera e offline di iTranslate](https://itranslate.com/features/keyboard-translations/index.html)
10. [Informazioni sull'utilizzo di Reverso Context](https://context.reverso.net/translation/about)
11. [Portale per documenti Reverso Documents](https://www.reverso.net/documents/en)
12. [Guida di Yandex Translate per desktop e mobile](https://yandex.com/support/translate-desktop/en/)
13. [Documentazione di Immersive Translate](https://immersivetranslate.com/)
14. [Informazioni sul prodotto e formati supportati di O.Translator](https://otranslator.com/en/product-info)
15. [Workbench per documenti complessi di SimplifyAI](https://simplifyai.cn/zh/translate)
16. [Traduzione generale documenti di SimplifyAI](https://translate.simplifyai.cn/)
17. [Funzionalità di Mate Translate](https://matetranslate.com/en)
18. [Lingvanex Traduttore per Windows](https://lingvanex.com/products/windows-translator/)
19. [Software di traduzione protetta Lingvanex Secure Translation](https://lingvanex.com/products/secure-translation-software/)
20. [SYSTRAN Translate Pro e soluzioni enterprise](https://www.systransoft.com/translation-products/translate-pro/)
21. [NetEase Youdao Translate](https://fanyi.youdao.com/)
22. [Baidu Translate e portale di traduzione video](https://fanyi.baidu.com/)
23. [Presentazione del prodotto Tencent TranSmart](https://transmart.qq.com/zh-CN/intro)
24. [Guida ai documenti di Caiyun Xiaoyi (LingoCloud)](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
25. [QuillBot Translate e portale PDF](https://quillbot.com/translate)
26. [Specifiche API e documentazione di Equalang](https://equalang.com/llms-full.txt?utm_source=github)
27. [Repository GitHub ufficiale di PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate)
28. [Documentazione delle opzioni avanzate di PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
29. [Repository GitHub ufficiale di BabelDOC](https://github.com/funstory-ai/BabelDOC)
30. [Repository GitHub ufficiale di LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
31. [Documentazione e guida alle API di LibreTranslate](https://docs.libretranslate.com/)
32. [Repository GitHub ufficiale di Argos Translate](https://github.com/argosopentech/argos-translate)
33. [Repository GitHub ufficiale per la traduzione desktop con Pot](https://github.com/pot-app/pot-desktop)
34. [Repository GitHub ufficiale di Translate Shell](https://github.com/soimort/translate-shell)
