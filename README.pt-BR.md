# Awesome Translation Tools

> Um diretório selecionado de ferramentas e fluxos de trabalho de tradução que abrange viagens, leitura na web, documentos formatados, pesquisa acadêmica, motores locais de código aberto e pipelines para desenvolvedores.

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

As tarefas de tradução diferem fundamentalmente conforme o contexto: decifrar uma placa de trânsito ou um cardápio no celular, ler documentação técnica estrangeira no navegador, traduzir apresentações complexas e contratos sem desconfigurar o layout, preservar fórmulas matemáticas em artigos acadêmicos, executar traduções privadas em lote no terminal ou acompanhar transmissões de vídeo sem legendas.

Somos a equipe do **[Equalang](https://equalang.com/?utm_source=github)**. Este diretório oferece um catálogo prático e orientado a tarefas com produtos consolidados de tradução e projetos de destaque em código aberto. Para cada ferramenta, resumimos recursos documentados, pontos de entrada, modos de implantação e restrições operacionais para ajudar você a identificar a solução ideal para o seu fluxo de trabalho.

---

<a id="contents"></a>
## Conteúdo

- [1. Viagens e comunicação em tempo real: Entradas multimodais e voz](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. Leitura web contextual e aprendizado de idiomas: Leitura sem sair da página](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. Layouts complexos de documentos e fluxos de trabalho corporativos: Preservação de formatos e ativos](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. Redação acadêmica, aprimoramento e colaboração humano-computador: Polimento do resultado](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. Ecossistema de código aberto: Motores locais, APIs, clientes desktop e pipelines para PDFs científicos](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 Pipelines para PDFs científicos e acadêmicos](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 Motores e APIs auto-hospedáveis](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 Interfaces para desktop e terminal](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. Fluxos de trabalho integrados de ponta a ponta:](#6-connected-end-to-end-workflows-equalang) [Equalang](https://equalang.com/?utm_source=github)
  - [1. Tradução de documentos completos com preservação de layout](#1-whole-file-document-translation-with-layout-preservation)
  - [2. Leitura no navegador e geração de legendas](#2-in-browser-reading--subtitle-generation)
  - [3. Comunicação por voz e trocas presenciais sem instalação](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. Integração para agentes de IA e desenvolvedores](#4-integration-for-ai-agents-and-developers)
- [7. Guia de decisão orientado a tarefas](#7-task-based-decision-guide)
- [8. Princípios do diretório e critérios de verificação](#8-directory-principles--verification-criteria)
- [9. Fontes](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>
## 1. Viagens e comunicação em tempo real: Entradas multimodais e voz

Viagens e trabalhos em campo exigem ativação rápida, reconhecimento multimodal confiável e disponibilidade offline quando a conectividade com a rede é limitada.

<a id="google-translate"></a>
### Google Translate
O [Google Translate em dispositivos móveis](https://support.google.com/translate) integra OCR instantâneo pela câmera, importação de fotos, entrada por escrita manual e conversa face a face em tela dividida. Os viajantes podem baixar pacotes de idiomas com antecedência para tradução offline de texto e pela câmera. A tradução de conversas faladas oferece múltiplos layouts de exibição, embora a interpretação de voz ao vivo e offline seja restrita a dispositivos Pixel específicos e pares de idiomas selecionados.

Nos navegadores desktop, o Google Translate oferece um [portal dedicado à tradução de documentos](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en) compatível com arquivos DOCX, PDF, PPTX e XLSX. Esta ferramenta para desktop foi projetada para arquivos digitais; páginas digitalizadas em PDF contendo apenas imagens são preservadas no arquivo baixado sem tradução por OCR.

<p align="center"><img src="assets/google-page@2x.webp" alt="Página oficial de visão geral do produto Google Translate" width="640"><br><sub>Página oficial de visão geral do Google Translate e seção de download do aplicativo móvel</sub></p>

<a id="apple-translate"></a>
### Apple Translate
Para usuários de iPhone e iPad, o aplicativo integrado ao sistema [Apple Translate](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios) dispensa instalação separada. Ele suporta digitação de texto, entrada por voz, detecção de texto pela câmera e conversas face a face em tela dividida. Seu modo de conversa consegue detectar automaticamente qual idioma está sendo falado, eliminando a necessidade de alternar manualmente o microfone entre os interlocutores. Os pacotes de idiomas baixados permitem consultas de texto diretamente no dispositivo, sem conexão celular.

Dentro do ecossistema Apple, os [recursos de tradução em tempo real](https://support.apple.com/en-us/123720) também se estendem aos apps Mensagens, Telefone e FaceTime. A tradução ao vivo de chamadas telefônicas faz parte do Apple Intelligence, exigindo hardware e versões de sistema compatíveis, e está sujeita a regras de disponibilidade regional (por exemplo, aparelhos adquiridos na China continental não oferecem suporte atual a esses recursos avançados de chamada do Apple Intelligence).

<p align="center"><img src="assets/apple-page@2x.webp" alt="Guia do Suporte da Apple para tradução no iPhone" width="640"><br><sub>Página do guia do Suporte da Apple para tradução de palavras e frases no iPhone</sub></p>

<a id="microsoft-translator"></a>
### Microsoft Translator
O [aplicativo móvel Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/) se destaca por seu [recurso de conversa multidispositivo](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/). O anfitrião inicia uma sessão no celular, e os participantes entram usando o app móvel ou qualquer navegador web no desktop, escaneando um código QR ou inserindo um código. Cada participante recebe transcrição e tradução em tempo real no idioma de sua escolha. Seu modo Apresentador mantém o microfone do anfitrião aberto enquanto silencia os ouvintes, o que é ideal para visitas guiadas e palestras.

O app também conta com livros de frases para download e tradução offline de fotos para dúvidas recorrentes de viagem. O aplicativo para usuários finais não oferece suporte à tradução direta de filmes externos, arquivos de vídeo ou gravações de mídia, e as sessões de voz multidispositivo exigem conexão ativa com a internet.

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Página oficial de recursos do Microsoft Translator" width="640"><br><sub>Página de recursos do Microsoft Translator destacando a funcionalidade de conversa multidispositivo</sub></p>

<a id="papago"></a>
### Papago
Desenvolvido pela NAVER na Coreia do Sul, o [Papago](https://papago.naver.com/) disponibiliza funções práticas para idiomas do Leste Asiático, incluindo coreano, inglês, japonês e chinês. Em dispositivos móveis, seu [aplicativo](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator) oferece diálogo face a face, um modo Edu para criar notas de estudo a partir de textos impressos e a janela flutuante Papago Mini, sendo conveniente para refeições, transporte público e estudos na Coreia.

Quanto à tradução de páginas web, os pontos de entrada variam conforme a plataforma: a NAVER descontinuou a ferramenta independente de tradução de sites no portal web desktop, direcionando usuários de PC ao navegador [Whale](https://whale.naver.com/), que opera com a tecnologia Papago; enquanto isso, o [aplicativo móvel do Papago](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE) ainda mantém a opção de tradução de sites em seu menu lateral. Ao baixar pacotes de idiomas em aparelhos compatíveis que atendem aos pré-requisitos do sistema (conforme detalhado na [documentação de operação offline da NAVER](https://help.naver.com/service/16448/contents/10663?osType=MOBILE), que exige pelo menos 4 GB de RAM e Android 14+ com pacotes de voz dedicados para fala), a tradução offline funciona para texto e voz entre coreano, inglês, japonês e chinês simplificado. Vale destacar que o modo offline não abrange OCR de fotos, modo de conversa, páginas da web nem arquivos de documentos.

<p align="center"><img src="assets/papago-page@2x.webp" alt="Interface oficial de tradução web do NAVER Papago" width="640"><br><sub>Área de trabalho de tradução web do NAVER Papago</sub></p>

<a id="itranslate"></a>
### iTranslate
O [iTranslate](https://itranslate.com/) é conhecido por sua [Extensão de Teclado](https://itranslate.com/features/keyboard-translations/index.html) integrada. Ao redigir mensagens no WhatsApp, iMessage ou e-mail, os usuários podem traduzir textos diretamente na interface do teclado, evitando a alternância constante entre aplicativos distintos.

A ferramenta também fornece pacotes para download de expressões comuns de viagem e livros de frases básicos por meio de seus [recursos offline](https://itranslate.com/features/offline-translations/index.html), facilitando a revisão de termos essenciais antes de viajar. A disponibilidade de recursos varia conforme o sistema operacional, e os recursos de voz offline limitam-se a uma lista selecionada de idiomas principais.

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="Página inicial oficial do iTranslate" width="640"><br><sub>Página inicial do iTranslate exibindo prévias da interface do aplicativo móvel</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>
## 2. Leitura web contextual e aprendizado de idiomas: Leitura sem sair da página

Ao consultar artigos ou documentações técnicas em outros idiomas, alternar continuamente para uma aba externa de tradução quebra o fluxo de foco. As ferramentas contextuais inserem a tradução diretamente no ambiente de leitura ativo.

<a id="immersive-translate"></a>
### Immersive Translate
O [Immersive Translate](https://immersivetranslate.com/) é uma extensão de navegador que insere parágrafos traduzidos diretamente abaixo do texto web original, apresentando um layout bilíngue limpo. Ele também oferece suporte à criação de e-books bilíngues em EPUB, visualização de PDFs e tradução de textos em campos de digitação no navegador.

Para conteúdo multimídia, o Immersive Translate traduz faixas de legendas existentes em plataformas como YouTube e Netflix. Além disso, seu recurso de [tradução de vídeo com IA](https://immersivetranslate.com/video/ai-video-translator/) utiliza reconhecimento de voz para gerar legendas bilíngues para vídeos sem legendas em plataformas compatíveis, como o YouTube, além de disponibilizar um [portal dedicado de tradução ao vivo do YouTube](https://livetranslate.immersivetranslate.com/zh-CN). A geração de legendas a partir de áudios sem legenda depende da compatibilidade do navegador, clareza do áudio e condições de streaming da plataforma.

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Página inicial oficial do Immersive Translate" width="640"><br><sub>Página inicial do Immersive Translate e portal de download da extensão de navegador</sub></p>

<a id="mate-translate"></a>
### Mate Translate
O [Mate Translate](https://matetranslate.com/en) foi feito sob medida para macOS, iOS e os principais navegadores desktop. Durante a navegação, clicar duas vezes em qualquer palavra abre uma definição pop-up instantânea; selecionar texto exibe traduções contextuais rápidas; a tradução de página inteira alterna entre a exibição original e a traduzida; e há também um utilitário permanente na barra de menus do Mac.

Para estudantes de idiomas, o Mate permite clicar em palavras em páginas web ou em legendas da Netflix para salvá-las em um Phrasebook personalizado, que suporta categorização própria e exportação em CSV para revisão externa. Em navegadores desktop como o Chrome, sua extensão também permite selecionar texto dentro do leitor de PDF integrado para acionar traduções diretamente.

<p align="center"><img src="assets/mate-page@2x.webp" alt="Página inicial oficial do Mate Translate" width="640"><br><sub>Página inicial do Mate Translate com prévias de interface multiplataforma</sub></p>

<a id="reverso"></a>
### Reverso
Para redatores e estudantes que desejam verificar o uso natural das palavras, o [Reverso Context](https://context.reverso.net/translation/about) fornece pares de frases bilíngues extraídos de filmes, publicações internacionais e sites multilíngues, acompanhados de tabelas de conjugação verbal e sugestões de sinônimos. Como os exemplos de frases se originam de corpora multilíngues públicos, os usuários devem avaliar a adequação do contexto para rascunhos confidenciais ou formais.

Seu portal de documentos, o [Reverso Documents](https://www.reverso.net/documents/en), aceita arquivos em PDF, Word, PowerPoint, Excel e formatos selecionados de localização. Ele oferece uma interface de revisão segmento por segmento no navegador, onde equipes podem colaborar em edições antes de baixar o arquivo finalizado.

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Interface oficial de tradução do Reverso" width="640"><br><sub>Interface de tradução web do Reverso e barra de navegação</sub></p>

<a id="yandex-translate"></a>
### Yandex Translate
O [portal web do Yandex Translate](https://yandex.com/support/translate-desktop/en/) e seus aplicativos móveis processam textos, imagens, sites e documentos. O cliente para Android inclui um dicionário abrangente que exibe transcrições fonéticas, definições, sinônimos e flexões morfológicas para os idiomas suportados.

Em dispositivos móveis, o aplicativo para Android já vem com um [dicionário offline](https://yandex.ru/support/translate-app-android/en/offline-mobile) inglês-russo pré-instalado, e outros pacotes de idiomas podem ser baixados para tradução de texto digitado offline. A interface desktop suporta uploads comuns de arquivos do Office e PDF. Vale distinguir o Yandex Translate como serviço independente do Yandex Browser, que inclui recursos proprietários de dublagem automática de vídeos.

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Interface web oficial do Yandex Translate" width="640"><br><sub>Interface de entrada do Yandex Translate e navegação lateral</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>
## 3. Layouts complexos de documentos e fluxos de trabalho corporativos: Preservação de formatos e ativos

Ao lidar com apresentações executivas, contratos com fornecedores ou manuais técnicos, layouts distorcidos exigem correções manuais demoradas. Estas ferramentas priorizam a fidelidade visual, o controle terminológico e a reutilização de ativos.

<a id="deepl"></a>
### DeepL
O [DeepL Translator](https://www.deepl.com/en/features) traz opções avançadas de configuração para fluxos de trabalho com textos e documentos. Os usuários podem criar [Glossários](https://www.deepl.com/en/features/glossary) para garantir o uso de termos corporativos ou técnicos de sua preferência, além de alternar entre registros de tom formal e informal nos idiomas compatíveis.

Seu [serviço de tradução de documentos](https://www.deepl.com/en/features/document-translation) aceita arquivos Word, PDF, PPT, Excel, HTML e SRT (com formatos variando pelo tipo de conta). O ecossistema do produto também inclui o DeepL Write para aprimoramento de textos, o [DeepL Voice for Online Meetings](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings) para legendas em tempo real no Teams e Zoom (exigindo licença do Voice e permissões do anfitrião), e um guia oficial de Model Context Protocol (MCP) voltado a agentes de IA.

<p align="center"><img src="assets/deepl-page@2x.webp" alt="Área de trabalho de tradução web oficial do DeepL" width="640"><br><sub>Interface do tradutor web do DeepL</sub></p>

<a id="otranslator"></a>
### O.Translator
O [O.Translator](https://otranslator.com/en/product-info) concentra-se na tradução de documentos com preservação de layout. Além de PDF, Word, PPT e Excel, suporta formatos editoriais e de localização como e-books EPUB, InDesign (IDML), Illustrator (AI), OpenDocument, arquivos de legenda (SRT/ASS) e arquivos de quadrinhos (CBZ/CBR), com OCR integrado para páginas digitalizadas. A precisão do layout depende da incorporação de fontes e da expansão do texto de destino.

Antes de traduzir o arquivo completo, o O.Translator permite visualizar uma prévia parcial do layout. O sistema suporta importação de glossários via XLSX ou TBX e oferece uma [API para desenvolvedores](https://www.otranslator.com/en/developer/v1). Sua opção de mídia foi desenvolvida para transcrever arquivos gravados de áudio e vídeo em legendas, e não para tradução em tempo real de streams no navegador.

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="Página inicial oficial do produto O.Translator" width="640"><br><sub>Página inicial do O.Translator e seção de envio de documentos</sub></p>

<a id="simplifyai"></a>
### SimplifyAI
O SimplifyAI mantém dois sites distintos: uma [Bancada de Trabalho para Documentos Complexos](https://simplifyai.cn/zh/translate) (simplifyai.cn/zh) baseada em IA e um [portal geral de Tradução de Documentos](https://translate.simplifyai.cn/) (translate.simplifyai.cn).

Na bancada de trabalho, o sistema extrai termos de alta frequência antes da tradução para conferência do usuário em arquivos Word, PPTX, InDesign, PDF e EPUB. A bancada também oferece Edição com IA para Word e InDesign (com suporte ao controle de alterações nativo do Word), exportação de dados bilíngues (Excel/XLIFF), extração estruturada em Markdown/JSON e verificações visuais de estouro de texto e layout tipográfico, sendo muito adequada para pré-impressão e localização de ativos de design. Para traduções cotidianas e diretas, o portal de tradução geral oferece um fluxo mais simplificado.

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="Página inicial oficial do SimplifyAI" width="640"><br><sub>Página inicial do SimplifyAI apresentando sua bancada de trabalho para documentos complexos e módulos</sub></p>

<a id="lingvanex"></a>
### Lingvanex
O [Lingvanex](https://lingvanex.com/) disponibiliza clientes para desktop, celular e navegador no Windows e macOS. Seu [tradutor desktop para Windows](https://lingvanex.com/products/windows-translator/) oferece atalhos globais no sistema (como pressionar Ctrl+C duas vezes sobre um texto selecionado) e permite traduzir textos e arquivos DOCX/ODT locais offline após o download dos pacotes de idiomas.

Além dos aplicativos de consumo, o Lingvanex disponibiliza para download o [Secure Translation Software](https://lingvanex.com/products/secure-translation-software/), um software para desktop voltado ao uso corporativo offline, bem como soluções separadas de Machine Translation On-premise para ambientes de redes privadas.

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Página inicial oficial do Lingvanex" width="640"><br><sub>Página inicial do Lingvanex destacando soluções de tradução corporativa e locais</sub></p>

<a id="systran"></a>
### SYSTRAN
A SYSTRAN atende a demandas corporativas e institucionais de localização. Seu serviço em nuvem, o [SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/), está disponível para uso imediato com arquivos Word, PowerPoint, Excel e PDF, oferecendo modelos de domínio pré-configurados para documentações jurídicas, financeiras e industriais, além de glossários personalizados e memórias de tradução (TM).

Para organizações com exigências de soberania de dados, a SYSTRAN oferece o [Translate Server](https://www.systransoft.com/translation-products/translate-server/) para implantação local (on-premise) protegida por firewalls corporativos, ambientes dedicados de Nuvem Privada e [APIs](https://www.systransoft.com/translation-products/translate-api/) em lote para pipelines de processamento de documentos.

<p align="center"><img src="assets/systran-page@2x.webp" alt="Página oficial de produto do SYSTRAN Translate Pro" width="640"><br><sub>Interface oficial de visão geral de produto do SYSTRAN Translate Pro</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>
## 4. Redação acadêmica, aprimoramento e colaboração humano-computador: Polimento do resultado

A tradução muitas vezes representa apenas a etapa inicial de um fluxo mais amplo de escrita ou pesquisa. Consultar definições de dicionário, aprimorar a redação e realizar edições interativas homem-máquina ajudam a assegurar padrões acadêmicos formais.

<a id="youdao-translate-netease-youdao"></a>
### Youdao Translate (NetEase Youdao)
Integrado ao ecossistema de dicionários da NetEase Youdao, o [Youdao Translate](https://fanyi.youdao.com/) conecta consulta de vocabulário, tradução e assistência à escrita. Além da tradução padrão de textos e arquivos, seu portal web traz abas dedicadas para «Tradução de Artigos do arXiv» e polimento acadêmico de textos.

Após traduzir trechos de pesquisas, os usuários podem executar verificações gramaticais, avaliar opções de sinônimos ou ajustar o tom acadêmico, auxiliando estudantes e pesquisadores na leitura de referências internacionais e na redação de artigos. O escopo de formatos e idiomas para o polimento de artigos e módulos de mídia difere da consulta padrão do dicionário.

<p align="center"><img src="assets/youdao-page@2x.webp" alt="Área de trabalho web oficial do NetEase Youdao Translate" width="640"><br><sub>Interface web do NetEase Youdao Translate e navegação de recursos</sub></p>

<a id="baidu-translate"></a>
### Baidu Translate
O [Baidu Translate](https://fanyi.baidu.com/) oferece ampla cobertura de clientes voltada a usuários que falam chinês. Seu software para desktop inclui uma janela flutuante compacta e seleção de texto por atalho em aplicativos locais, enquanto o app móvel combina tradução por foto, prática de conversação e consultas a dicionários.

Além disso, o Baidu mantém um [portal independente de Tradução de Vídeo](https://fanyi-video.baidu.com/). Os usuários enviam arquivos de mídia para gerar faixas alinhadas de legendas bilíngues, que podem ser revisadas e editadas em um editor online antes da exportação final dos arquivos de legenda. Trata-se de uma ferramenta de pós-produção baseada em upload, e não de um intérprete automático para transmissões web ao vivo.

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Página oficial do site do Baidu Translate" width="640"><br><sub>Interface web oficial do Baidu Translate</sub></p>

<a id="transmart-tencent-interactive-translation"></a>
### TranSmart (Tencent Interactive Translation)
Desenvolvido pelo Tencent AI Lab, o [TranSmart](https://transmart.qq.com/zh-CN/intro) foi projetado com foco na colaboração interativa humano-computador. Em vez de simplesmente gerar um texto estático para cópia, o TranSmart sugere autocompletamentos preditivos em nível de palavras e frases em tempo real, integrando pares bilíngues confirmados à memória ativa de tradução.

Os tradutores podem posicionar o cursor em qualquer ponto do texto traduzido para fazer ajustes, fazendo com que o sistema atualize as sugestões seguintes de forma dinâmica. Isso mantém o controle terminológico e o ritmo das frases sob o comando do usuário, funcionando como um editor colaborativo com proposta distinta dos aplicativos móveis convencionais de dicionário da Tencent.

<p align="center"><img src="assets/transmart-page@2x.webp" alt="Página web oficial do Tencent TranSmart" width="640"><br><sub>Interface web oficial do Tencent TranSmart</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>
### LingoCloud (Caiyun Xiaoyi)
O [LingoCloud](https://www.caiyunapp.com/?lang=zh) é amplamente utilizado em tarefas que envolvem chinês, inglês e japonês. Sua extensão de navegador oferece leitura web bilíngue na própria página com suporte a glossários compartilhados, públicos e pessoais. Seu [serviço de tradução de documentos](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html) (conforme diretrizes do aplicativo móvel) aceita formatos como PDF, Word, PPT, Excel, EPUB, TXT e SRT, entregando os arquivos baixados principalmente em PDF ou Word, dependendo do arquivo original.

Seu aplicativo para desktop também traz o [LingoCloud Interpretation](https://www.caiyunapp.com/interpretation/), capaz de capturar o áudio do microfone ou interceptar o áudio de saída do sistema em programas em execução (como Zoom, Teams ou Chrome no Windows) para exibir legendas bilíngues ao vivo. A interpretação no desktop respeita os limites de captura de áudio do sistema operacional: no Windows, a captura do áudio do sistema funciona nos apps de conferência e mídia compatíveis; no macOS, as rotas de gravação de áudio interno do sistema não são suportadas no momento devido a atualizações do próprio macOS, restando a captura via microfone como opção viável.

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="Página oficial do site do LingoCloud" width="640"><br><sub>Interface web oficial do LingoCloud</sub></p>

<a id="quillbot-translate"></a>
### QuillBot Translate
O [QuillBot Translate](https://quillbot.com/translate) opera dentro do ecossistema de escrita e edição do QuillBot. Ao traduzir textos, a interface oferece opções de formalidade e apresenta definições e sinônimos nos idiomas suportados.

O texto traduzido pode ser enviado com facilidade para as ferramentas de Paráfrase e Verificador Gramatical para aperfeiçoar a fluidez das frases. A plataforma também mantém uma [página dedicada para Tradução de PDF](https://quillbot.com/translate-pdf), voltada ao envio e à revisão de documentos PDF avulsos. Os idiomas suportados variam entre as ferramentas de tradução, gramática e paráfrase.

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="Página oficial da extensão do QuillBot na Chrome Web Store" width="640"><br><sub>Página oficial de produto da extensão de navegador QuillBot na Chrome Web Store</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>
## 5. Ecossistema de código aberto: Motores locais, APIs, clientes desktop e pipelines para PDFs científicos

Desenvolvedores, equipes atentas à privacidade e pesquisadores acadêmicos frequentemente precisam de código auditável, execução offline local ou pipelines de automação sob medida. O ecossistema de tradução em código aberto abrange várias camadas arquiteturais distintas:

- **Ferramentas de layout para PDFs científicos**: Traduzem artigos acadêmicos complexos preservando estruturas de várias colunas, fórmulas e figuras.
- **Serviços de tradução auto-hospedáveis**: Fornecem endpoints de API REST via HTTP e interfaces web para implantação em redes locais.
- **Motores de tradução offline embarcados**: Executam tradução automática neural localmente por meio de bibliotecas Python, sem dependências de rede externa.
- **Interfaces para desktop e terminal**: Integram consultas em múltiplos motores, monitoramento da área de transferência, OCR e pipelines em shell.

> [!IMPORTANT]
> Executar código de código aberto localmente não significa automaticamente que as traduções sejam offline ou privadas. Uma ferramenta pode rodar localmente enquanto faz requisições a APIs em nuvem por padrão. Uma tradução verdadeiramente offline exige tanto os ativos dos modelos locais quanto um motor de tradução local.

<a id="51-scientific--academic-pdf-pipelines"></a>
### 5.1 Pipelines para PDFs científicos e acadêmicos

<a id="pdfmathtranslate-pdf2zh"></a>
#### PDFMathTranslate (pdf2zh)
O [PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) (GNU AGPL v3) é uma ferramenta de código aberto feita sob medida para documentos científicos e acadêmicos em PDF. Ela preserva a estrutura de colunas dos artigos, notações matemáticas, figuras incorporadas, sumários e anotações.

- **Saídas duplas e individuais**: Gera documentos apenas traduzidos (`-mono.pdf`) e versões bilíngues comparativas (`-dual.pdf`).
- **Interfaces e integrações**: Oferece ferramentas em linha de comando (CLI), WebUI interativa, implantação via contêineres Docker e suporte ao Model Context Protocol (MCP). Um plugin de integração com o Zotero está disponível como projeto complementar.
- **Backends de tradução**: Utiliza uma arquitetura plugável com suporte ao Google Translate (padrão documentado), DeepL, APIs compatíveis com OpenAI e instâncias locais do Ollama. A implantação local via Docker ou WebUI não implica funcionamento offline se backends em nuvem forem configurados.
- **Suporte a OCR**: Inclui OCR experimental para páginas digitalizadas com texto preto sobre fundo branco (baixa modelos de linguagem no primeiro uso, que podem ser reutilizados localmente depois).

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="Página oficial do repositório GitHub do PDFMathTranslate" width="640"><br><sub>Visão geral do repositório oficial do PDFMathTranslate ilustrando a tradução com preservação de layout em PDFs acadêmicos e fluxos via CLI/WebUI</sub></p>

<a id="babeldoc"></a>
#### BabelDOC
O [BabelDOC](https://github.com/funstory-ai/BabelDOC) (GNU AGPL v3) é uma biblioteca de tradução e comparação bilíngue de artigos científicos em nível de documento, projetada principalmente para integração em aplicações Python e acompanhada de uma CLI para depuração.

- **Controle de layout e saída**: Suporta saídas mono ou dual, páginas originais e traduzidas lado a lado na mesma página ou em páginas alternadas, tradução seletiva de páginas, divisão e união de PDFs grandes, importação de glossários personalizados em CSV e preservação de fórmulas. A tradução de textos em tabelas está explicitamente documentada como experimental.
- **Arquitetura de backends**: Exige um backend de tradução configurado por meio de endpoints compatíveis com OpenAI ou uma instância local do Ollama. Como é um motor de processamento de PDFs e layouts, não inclui um motor universal de tradução próprio.
- **Ativos offline e limitações**: Oferece rotinas de aquecimento e geração/restauração de ativos offline para modelos de layout de documentos e fontes. A execução totalmente offline exige tanto os ativos pré-armazenados em cache quanto um backend de tradução rodando localmente (como o Ollama local). A documentação enfatiza que a validação principal foi realizada em fluxos de inglês para chinês, com uma solução paliativa experimental de OCR para texto preto em fundos brancos.

<p align="center"><img src="assets/babeldoc-page.webp" alt="Página oficial do repositório GitHub do BabelDOC" width="640"><br><sub>Visão geral do repositório oficial do BabelDOC demonstrando os recursos da biblioteca de tradução em nível de documento para PDFs científicos</sub></p>

<a id="52-self-hostable-engines--apis"></a>
### 5.2 Motores e APIs auto-hospedáveis

<a id="libretranslate"></a>
#### LibreTranslate
O [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) (GNU AGPL v3) é um serviço de API de tradução automática gratuito, de código aberto e auto-hospedável, com interface web inclusa, desenvolvido sobre o motor Argos Translate.

- **API e serviço web**: Disponibiliza endpoints de API REST para tradução de texto, identificação de idioma de origem e manipulação de HTML/marcações. Funciona como uma camada de serviço autônoma, e não como proxy para APIs comerciais de tradução.
- **Implantação local e privacidade**: Pode ser executado integralmente em hardware local sem enviar dados a terceiros externos, após a instalação das dependências e modelos de linguagem. O uso de uma instância pública hospedada continua dependente de rede. O controle de acesso por chave de API pode ser ativado ou desativado conforme a necessidade do host.
- **Cobertura de idiomas e formatos de arquivo**: Os pares de idiomas disponíveis dependem dos modelos de linguagem instalados. Por meio de projetos complementares como o argos-translate-files, a tradução de arquivos abrange formatos como TXT, ODT, ODP, DOCX, PPTX, EPUB, HTML, SRT e PDF.

<p align="center"><img src="assets/libretranslate-page.webp" alt="Página oficial do repositório GitHub do LibreTranslate" width="640"><br><sub>Visão geral do repositório oficial do LibreTranslate exibindo a API de tradução auto-hospedada e os recursos da interface web</sub></p>

<a id="argos-translate"></a>
#### Argos Translate
O [Argos Translate](https://github.com/argosopentech/argos-translate) (licença MIT / opção CC0 indicada no README) é uma biblioteca Python e ferramenta de linha de comando de tradução offline e de código aberto, com um cliente gráfico (GUI) instalável separadamente.

- **Pacotes de modelos modulares**: Baixa e gerencia pacotes de modelos de linguagem que usam a extensão `.argosmodel`. Quando não há um par direto disponível, consegue fazer a ponte por meio de pares intermediários instalados (por exemplo, traduzindo via inglês).
- **Motor do ecossistema**: Funciona como motor de tradução automática subjacente para o LibreTranslate. Projetos complementares estendem suas capacidades para tradução de HTML (`translate-html`) e processamento de arquivos (`argos-translate-files`).
- **Operação offline**: Roda completamente offline após a instalação dos modelos; o download dos índices de pacotes e dos modelos iniciais requer conexão com a internet.

<p align="center"><img src="assets/argos-translate-page.webp" alt="Página oficial do repositório GitHub do Argos Translate" width="640"><br><sub>Visão geral do repositório oficial do Argos Translate detalhando o motor de tradução offline modular e o sistema de pacotes</sub></p>

<a id="53-desktop--terminal-frontends"></a>
### 5.3 Interfaces para desktop e terminal

<a id="pot-pot-desktop"></a>
#### Pot (pot-desktop)
O [Pot](https://github.com/pot-app/pot-desktop) (GNU GPL v3) é uma ferramenta de tradução desktop multiplataforma para Windows, macOS e Linux, que oferece tradução de seleção por teclas de atalho, digitação de texto, monitoramento da área de transferência, OCR de captura de tela e tradução de imagens capturadas. O repositório original foi arquivado pelo proprietário em 7 de setembro de 2026 e está agora em modo somente leitura.

- **Agregação de múltiplos serviços**: Permite consultar simultaneamente diversos serviços de tradução e dicionários para comparar resultados lado a lado. Oferece suporte a conversão de texto em fala (TTS), exportação de vocabulário para Anki e Eudic, e extensões via plugins.
- **Backends plugáveis e OCR**: Reúne provedores de tradução em nuvem, APIs compatíveis com OpenAI e endpoints locais do Ollama. As opções de OCR incluem alternativas nativas do sistema (OCR do sistema Windows, Apple Vision, Linux Tesseract), Tesseract.js ou plugins locais.
- **Rotas de execução offline**: A tradução de texto digitado ou selecionado exige apenas um backend local de tradução configurado (como uma instância local do Ollama); a tradução de capturas de tela exige adicionalmente um motor de OCR offline (como o OCR nativo do sistema ou o Tesseract). Serviços em nuvem roteiam as requisições pela rede.

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Página oficial do repositório GitHub de tradução desktop Pot" width="640"><br><sub>Visão geral do repositório oficial do cliente desktop Pot destacando fluxos de tradução multi-interface, OCR e área de transferência</sub></p>

<a id="translate-shell"></a>
#### Translate Shell
O [Translate Shell](https://github.com/soimort/translate-shell) (The Unlicense / Domínio Público) é uma versátil ferramenta de tradução em linha de comando (executável `trans`) para ambientes de terminal Unix-like.

- **Consulta via CLI e dicionário**: Suporta definições de palavras, tradução de frases, modo de dicionário conciso, sessões interativas em REPL e identificação de idioma diretamente no shell.
- **Pipelines Unix**: Integra-se à entrada e saída padrão (`stdin` / `stdout`), processa arquivos de texto diretamente e suporta síntese de voz quando um reprodutor de áudio externo está instalado.
- **Camada de motor**: Atua como uma interface de cliente leve conectada a serviços públicos de tradução (utilizando o Google Translate como mecanismo padrão, com opções adicionais para Bing Translator, Yandex.Translate e Apertium).
- **Limitações**: Não inclui modelos neurais de tradução locais; o funcionamento padrão depende de conectividade externa com os serviços de motor escolhidos. A tradução de arquivos foi concebida para fluxos de texto puro, e não para documentos formatados.

<p align="center"><img src="assets/translate-shell-page.webp" alt="Página oficial do repositório GitHub do Translate Shell" width="640"><br><sub>Visão geral do repositório oficial do Translate Shell apresentando a tradução em linha de comando no terminal e a integração com pipelines</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>
## 6. Fluxos de trabalho integrados de ponta a ponta: [Equalang](https://equalang.com/?utm_source=github)

A análise dessas ferramentas demonstra que cada serviço desenvolveu pontos fortes claros para tarefas específicas. No trabalho diário, contudo, as necessidades frequentemente se cruzam:

Você pode estar lendo um relatório técnico online no navegador, baixar um PDF que o acompanha repleto de tabelas e diagramas, assistir a uma palestra em vídeo sem legendas e, em seguida, redigir um sumário executivo no Word enquanto coordena detalhes diretamente com parceiros internacionais. Alternar entre ferramentas isoladas e conversores de arquivos fragmenta o fluxo de trabalho.

Projetamos o **[Equalang](https://equalang.com/?utm_source=github)** para conectar essas etapas em um fluxo contínuo de tradução lado a lado, oferecendo suporte integrado de tradução entre documentos, páginas web, vídeos e comunicação em tempo real.

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Página inicial oficial em inglês do Equalang" width="640"><br><sub>Página inicial oficial do site do <a href="https://equalang.com/?utm_source=github">Equalang</a> em inglês</sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>
### 1. Tradução de documentos completos com preservação de layout
Ao traduzir documentos completos, o [Equalang](https://equalang.com/?utm_source=github) prioriza a preservação estrutural e a facilidade de uso após a tradução, disponibilizando fluxos dedicados para artigos científicos, apresentações e arquivos comuns de escritório:

- **Documentos PDF e leitura**: O [Equalang](https://equalang.com/?utm_source=github) preserva layouts de múltiplas colunas, cabeçalhos, rodapés e legendas de figuras, reunindo frases divididas por quebras de página antes de traduzi-las, mantendo estruturas de tabelas, fórmulas em linha e links internos do documento. Conforme demonstrado em nosso [guia de leitura de PDFs acadêmicos](https://equalang.com/blog/translate-and-read-pdf-documents?utm_source=github), os leitores podem visualizar o arquivo traduzido ao lado do original em um layout comparativo, compreendendo os pontos centrais no seu idioma principal antes de cruzar terminologias e dados específicos na página original.

- **Apresentações em PowerPoint**: Em nosso [guia de formatação para apresentações de slides](https://equalang.com/blog/translate-powerpoint-keep-formatting?utm_source=github), os arquivos PPTX traduzidos mantêm tabelas nativas editáveis em vez de convertê-las em imagens estáticas. A formatação em nível de palavra — como negrito, itálico e cores de fonte dentro de uma única frase — é associada com exatidão aos trechos correspondentes no texto traduzido. Termos-chave e cabeçalhos permanecem consistentes entre os slides, e as caixas de texto reduzem o tamanho da fonte automaticamente quando a tradução se expande, evitando que o texto ultrapasse limites ou cubra ilustrações.

- **Arquivos de escritório Word e Excel**: Em nosso [teste verificado de tradução de Word](https://equalang.com/blog/translate-word-document-keep-formatting?utm_source=github), os arquivos DOCX traduzidos preservaram títulos, listas com marcadores, tabelas de preços e formatação em negrito, permitindo edição direta no Microsoft Word. Em nossa [validação de planilhas de preços no Excel](https://equalang.com/blog/translate-excel-file?utm_source=github), fórmulas e números foram mantidos intactos, enquanto textos repetidos em diferentes células foram traduzidos apenas uma vez.

- **E-books e mídias formatadas**: Livros digitais em EPUB conservam a navegação pelo sumário e os links de âncora internos. Para arquivos gravados de áudio e vídeo de até 180 minutos, o envio das tarefas de tradução e transcrição é realizado via API para Desenvolvedores e integração com Agent Skill/MCP (em vez de um portal geral de upload de documentos web), gerando arquivos de legenda bilíngues com marcadores de tempo em SRT/VTT ou transcrições do áudio original.

<a id="2-in-browser-reading--subtitle-generation"></a>
### 2. Leitura no navegador e geração de legendas
Com nossa leve [extensão de navegador](https://equalang.com/extension?utm_source=github) (com guias de instalação para Chrome, Edge e Firefox, além de um modo temporário para Safari 18.4+ no Mac), a tradução se integra perfeitamente à sua leitura diária:

- **Leitura web bilíngue sob o parágrafo**: Os parágrafos traduzidos surgem logo abaixo do texto original durante a rolagem da página. Um ícone flutuante pode ser ativado nas configurações para consultas rápidas de palavras. Ao visualizar PDFs locais, os usuários podem ativar «Permitir acesso a URLs de arquivo» no gerenciamento de extensões para consultar termos ao selecionar palavras.

- **Legendas bilíngues em vídeo**: Compatível com YouTube, Netflix, TikTok e Bilibili, conforme detalhado em nosso [guia para assistir a vídeos com legendas bilíngues](https://equalang.com/blog/watch-videos-with-bilingual-subtitles?utm_source=github). Além de traduzir legendas já existentes, a extensão consegue capturar o áudio em tempo real para criar legendas bilíngues para **vídeos sem legendas** (respeitando as condições do navegador e as restrições de criptografia de mídia, verificado em transmissões ao vivo do YouTube e trailers oficiais), traduzindo simultaneamente o chat ao vivo no YouTube.

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>
### 3. Comunicação por voz e trocas presenciais sem instalação
Exigir que a outra pessoa instale aplicativos dedicados gera atrito, sobretudo durante viagens. Com conexão à internet, o [Equalang](https://equalang.com/?utm_source=github) oferece tradução de fotos e interpretação de voz diretamente no navegador convencional (bastando fazer login inicial e conceder permissões de câmera/microfone no primeiro uso), conforme abordado em nosso [guia de comunicação internacional](https://equalang.com/blog/talk-with-overseas-partners?utm_source=github):

- **Tradução móvel de fotos**: Ao se deparar com cardápios, placas ou avisos desconhecidos em viagens, basta tirar uma foto no navegador móvel. As traduções aparecem sobrepostas diretamente sobre a imagem, facilitando fazer pedidos ou conferir avisos sem perder a referência visual, conforme ilustrado em nosso [guia de tradução de fotos em viagens](https://equalang.com/blog/photo-translation-for-travel?utm_source=github).

- **Modo face a face**: Criado para interações presenciais, como guardar bagagens no hotel, pedir orientações na rua ou conversar na recepção. Duas pessoas podem apoiar um celular ou tablet entre si, utilizando uma tela dividida invertida ou visualização lado a lado com transcrição bidirecional contínua e exportação do histórico, como demonstrado em nosso [guia de diálogo face a face em viagens](https://equalang.com/blog/talk-face-to-face-while-traveling?utm_source=github).

- **Audição em tempo real**: Abra o portal web durante uma palestra ou conferência presencial para acompanhar legendas bilíngues geradas a partir do microfone físico do aparelho, com síntese de voz opcional e exportação da transcrição ao término (diferente da captura de streaming de mídia feita pela extensão de navegador).

- **Chamadas traduzidas**: O anfitrião acessa o portal web, cria um link seguro para a chamada e o envia por qualquer aplicativo de mensagens. **Os convidados entram diretamente pelo navegador, sem criar conta nem instalar aplicativos** — basta informar um nome e o anfitrião autoriza a entrada. Ambos falam no seu idioma nativo, ouvem o áudio traduzido e leem as transcrições em tempo real.

<a id="4-integration-for-ai-agents-and-developers"></a>
### 4. Integração para agentes de IA e desenvolvedores
Para desenvolvedores e equipes que buscam integrar a tradução a fluxos automatizados:

- **API para desenvolvedores**: Oferece endpoints imediatos para texto e processamento assíncrono de arquivos com suporte a novas tentativas via Idempotency-Key e notificações de callback de conclusão, conforme detalhado em nosso [guia de integração de API de tradução de arquivos](https://equalang.com/blog/integrate-file-translation-api?utm_source=github).

- **Integração com Skill e MCP**: Mantemos Agent Skills de código aberto no [equalang-skill](https://github.com/equalang/equalang-skill) e suporte oficial ao Model Context Protocol por meio de [@equalang/mcp](https://github.com/equalang/equalang-mcp). Em ambientes como Claude Code, Codex ou WorkBuddy, basta enviar um único prompt de instalação ao assistente e configurar sua chave de API para que ele passe a traduzir documentos e transcrever mídias diretamente no fluxo de trabalho, seguindo nosso [guia de tradução de arquivos com assistentes de IA](https://equalang.com/blog/translate-files-with-ai-assistants?utm_source=github).

---

<a id="7-task-based-decision-guide"></a>
## 7. Guia de decisão orientado a tarefas

Para ajudar você a escolher a ferramenta mais adequada para sua tarefa atual, consulte esta matriz:

| Tarefa principal | Requisito fundamental | Ferramentas recomendadas para testar | Considerações principais |
| :--- | :--- | :--- | :--- |
| **Viagens e diálogo falado** | OCR de fotos, diálogo bidirecional, pacotes offline e ferramentas conectadas para viagem | Google Translate, Apple Translate, Papago, [Equalang](https://equalang.com/?utm_source=github) | Baixe pacotes de idiomas offline no Google, Apple ou Papago (atentando-se aos requisitos de hardware) para áreas com sinal fraco; com conexão ativa, o [Equalang](https://equalang.com/?utm_source=github) oferece tradução de fotos no navegador e diálogo face a face sem instalação de apps. |
| **Workshops multidispositivo** | Apresentações de um para muitos, participação em múltiplos dispositivos | Microsoft Translator | O anfitrião ativa o modo Apresentador pelo app móvel; os participantes entram por qualquer navegador comum sem instalar programas. |
| **Leitura aprofundada na web** | Leitura sob o parágrafo sem sair da página | Immersive Translate, [Equalang](https://equalang.com/?utm_source=github), Mate Translate | Use o Immersive Translate ou o [Equalang](https://equalang.com/?utm_source=github) para leitura bilíngue em parágrafos; use o Mate Translate para alternar a exibição da página completa ou salvar palavras no Phrasebook no Mac. |
| **Vídeos e transmissões ao vivo sem legendas** | Geração de legendas em tempo real, compatibilidade com streaming | [Equalang](https://equalang.com/?utm_source=github), Immersive Translate | Ambas as ferramentas geram legendas a partir do áudio bruto em plataformas compatíveis (como o YouTube); compare os fluxos das extensões de navegador para chat ao vivo e gerenciamento de transmissões. |
| **Artigos acadêmicos e PDFs científicos** | Preservação de fórmulas, estrutura de colunas, texto entre páginas | PDFMathTranslate, BabelDOC, [Equalang](https://equalang.com/?utm_source=github) | PDFMathTranslate e BabelDOC oferecem pipelines de código aberto com geração de PDF duplo e backends de LLM locais/em nuvem; o [Equalang](https://equalang.com/?utm_source=github) oferece leitura comparativa no navegador e preservação visual do layout. |
| **Formatos editoriais de pré-impressão e design** | InDesign, Illustrator, arquivos de quadrinhos, controle de qualidade de pré-impressão | SimplifyAI, O.Translator | Utilize SimplifyAI e O.Translator para InDesign (IDML) e pré-impressão de ativos de design; o SimplifyAI inclui Edição com IA com controle de alterações nativo do Word. |
| **Apresentações e documentos de escritório** | Preservação de tabelas nativas, estilos, fórmulas e capacidade de edição | [Equalang](https://equalang.com/?utm_source=github), DeepL | O [Equalang](https://equalang.com/?utm_source=github) preserva tabelas e estilos nativos no PPTX com dimensionamento adaptativo de fontes e retenção de fórmulas no Excel; use o DeepL para arquivos corporativos do Word/Office com glossários. |
| **Redação acadêmica e polimento** | Precisão gramatical, registro acadêmico formal | Youdao Translate, QuillBot Translate, TranSmart | Youdao e QuillBot integram a tradução ao refinamento textual; o TranSmart oferece edição interativa com humano no circuito. |
| **Consulta via atalho no desktop e multimotor** | Atalhos globais, OCR, comparação de múltiplos motores | Pot, Mate Translate | O Pot permite consultas simultâneas em múltiplos motores e OCR de captura de tela no Windows, Mac e Linux; o Mate oferece um utilitário nativo na barra de menus do Mac. |
| **Scripts de terminal e pipelines de shell** | Consultas via CLI, pipelines stdin/stdout, scripts de texto puro | Translate Shell, Argos Translate | O Translate Shell fornece tradução leve em CLI via motores remotos; o Argos Translate oferece CLI em Python offline com modelos locais. |
| **API privada auto-hospedada e motores offline** | Redes isoladas (air-gapped), sem transmissão de dados a terceiros | LibreTranslate, Argos Translate, SYSTRAN, Lingvanex | O LibreTranslate fornece serviço de API HTTP auto-hospedável e WebUI; o Argos Translate atua como sua biblioteca/motor CLI em Python offline com modelos modulares; SYSTRAN e Lingvanex oferecem implantações corporativas on-premise. |
| **Fluxos de trabalho integrados de ponta a ponta** | Documentos, legendas em streaming, chamadas web e agentes de IA | [Equalang](https://equalang.com/?utm_source=github) | Processamento unificado de documentos, legendas para mídias sem legenda, chamadas via navegador sem instalação de apps e integração direta com Claude Code ou WorkBuddy. |

---

<a id="8-directory-principles--verification-criteria"></a>
## 8. Princípios do diretório e critérios de verificação

Para manter a utilidade prática e a precisão factual deste diretório, as entradas seguem critérios rigorosos de inclusão e revisão:

1. **Recursos documentados em vez de promessas de marketing**: As descrições baseiam-se na documentação oficial, manuais de usuário e arquivos-fonte confirmados dos repositórios. Não alegamos preservação perfeita de layout nem suporte universal a formatos.
2. **Limites arquiteturais claros**: Distinguimos entre frontends de tradução, camadas de serviço auto-hospedáveis, motores de tradução offline e bibliotecas de layout de documentos. O código aberto executado localmente é separado explicitamente da verdadeira execução offline.
3. **Cobertura orientada a tarefas**: As ferramentas são agrupadas por adequação prática entre diferentes fluxos de trabalho. Não mantemos listas subjetivas de classificação, pontuações de qualidade nem valores de preços transitórios.
4. **Identidade transparente da equipe de manutenção**: Este catálogo é organizado e mantido pela equipe do **[Equalang](https://equalang.com/?utm_source=github)**. O [Equalang](https://equalang.com/?utm_source=github) é apresentado ao lado de outras ferramentas com limites de recursos verificáveis e requisitos de sistema transparentes.

**Palavras-chave**: ferramentas de tradução, tradução de documentos, leitura web bilíngue, tradução de PDFs acadêmicos, tradução de código aberto, API de tradução automática, preservação de layout, agentes de IA.

---

<a id="9-sources"></a>
## 9. Fontes

1. [Central de Ajuda do Google Translate](https://support.google.com/translate)
2. [Tradução de documentos no desktop do Google Translate](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Suporte da Apple: Guia do aplicativo Traduzir para iPhone](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Suporte da Apple: Tradução em tempo real e disponibilidade de recursos](https://support.apple.com/en-us/123720)
5. [Recursos móveis do Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/)
6. [Ajuda para conversas multidispositivo do Microsoft Translator](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/)
7. [Portal oficial do NAVER Papago](https://papago.naver.com/)
8. [Recursos de teclado e modo offline do iTranslate](https://itranslate.com/features/keyboard-translations/index.html)
9. [Informações de uso do Reverso Context](https://context.reverso.net/translation/about)
10. [Portal do Reverso Documents](https://www.reverso.net/documents/en)
11. [Ajuda do Yandex Translate para desktop e dispositivos móveis](https://yandex.com/support/translate-desktop/en/)
12. [Documentação do Immersive Translate](https://immersivetranslate.com/)
13. [Informações sobre o produto e formatos do O.Translator](https://otranslator.com/en/product-info)
14. [Bancada de trabalho para documentos complexos do SimplifyAI](https://simplifyai.cn/zh/translate)
15. [Tradução geral de documentos do SimplifyAI](https://translate.simplifyai.cn/)
16. [Recursos do Mate Translate](https://matetranslate.com/en)
17. [Tradutor para Windows do Lingvanex](https://lingvanex.com/products/windows-translator/)
18. [Software de tradução segura do Lingvanex (Secure Translation Software)](https://lingvanex.com/products/secure-translation-software/)
19. [SYSTRAN Translate Pro e implantações corporativas](https://www.systransoft.com/translation-products/translate-pro/)
20. [NetEase Youdao Translate](https://fanyi.youdao.com/)
21. [Portal de tradução de vídeo e Baidu Translate](https://fanyi.baidu.com/)
22. [Apresentação do produto Tencent TranSmart](https://transmart.qq.com/zh-CN/intro)
23. [Ajuda de documentos do Caiyun Xiaoyi (LingoCloud)](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
24. [Portal de tradução e PDF do QuillBot](https://quillbot.com/translate)
25. [Especificações e documentação da API do Equalang](https://equalang.com/llms-full.txt?utm_source=github)
26. [Repositório oficial no GitHub do PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate)
27. [Documentação de opções avançadas do PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
28. [Repositório oficial no GitHub do BabelDOC](https://github.com/funstory-ai/BabelDOC)
29. [Repositório oficial no GitHub do LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
30. [Documentação e guia da API do LibreTranslate](https://docs.libretranslate.com/)
31. [Repositório oficial no GitHub do Argos Translate](https://github.com/argosopentech/argos-translate)
32. [Repositório oficial no GitHub do cliente desktop Pot](https://github.com/pot-app/pot-desktop)
33. [Repositório oficial no GitHub do Translate Shell](https://github.com/soimort/translate-shell)
