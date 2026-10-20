# Awesome Translation Tools

> 旅行・出張、Web閲覧、レイアウト維持文書、学術研究、オープンソースのローカルエンジン、開発者向けパイプラインまでを網羅した、翻訳ツールとワークフローの厳選カタログ。

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

翻訳タスクに求められる要件は、利用シーンによって根本から異なります。スマートフォンで街中の案内標識やメニューを読み取る、ブラウザ上で外国語の技術ドキュメントを読み進める、レイアウトを崩さずに複雑なプレゼンスライドや契約書を翻訳する、学術論文の数式をそのまま保持する、ターミナル上で非公開のバッチ翻訳を実行する、あるいは字幕のない動画ストリームの内容を追うなど、状況に応じて重視すべき点は多岐にわたります。

私たちは **[Equalang](https://equalang.com/?utm_source=github)** チームです。本カタログは、定評のある商用翻訳プロダクトとオープンソースプロジェクトを、タスク指向の実践的な視点で整理したディレクトリです。各ツールについて、公式ドキュメントに基づく機能特性、利用エントリーポイント、デプロイ形態、および運用上の制約をまとめ、日々のワークフローに最適なソリューションを見極める手助けとなることを目的としています。

---

## 目次

- [1. 移動・旅行と対面会話：マルチモーダル認識と音声入力](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. 文脈に沿ったWeb閲覧と語学学習：ページを離れずに読む](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. 複雑な文書レイアウトとエンタープライズワークフロー：書式と資産の保持](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. 学術執筆・推敲と協調型編集：出力の精度を高める](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. オープンソースエコシステム：ローカルエンジン、API、デスクトップクライアント、学術PDFパイプライン](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 学術論文・科学PDF処理パイプライン](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 セルフホスト対応エンジンとAPI](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 デスクトップ＆ターミナルフロントエンド](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. シームレスにつながるエンドツーエンドワークフロー：](#6-connected-end-to-end-workflows-equalang)[Equalang](https://equalang.com/?utm_source=github)
  - [1. レイアウトを保持したファイル全体の文書翻訳](#1-whole-file-document-translation-with-layout-preservation)
  - [2. ブラウザ内での閲覧と字幕生成](#2-in-browser-reading--subtitle-generation)
  - [3. アプリインストール不要の音声コミュニケーションと現場での対話](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. AIエージェントと開発者のための統合環境](#4-integration-for-ai-agents-and-developers)
- [7. タスク別選定ガイド](#7-task-based-decision-guide)
- [8. ディレクトリの編集方針と検証基準](#8-directory-principles--verification-criteria)
- [9. 出典・参考資料](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>
## 1. 移動・旅行と対面会話：マルチモーダル認識と音声入力

旅行や現地調査では、即座に起動できる操作性、信頼性の高いマルチモーダル認識、そして通信環境が制限された状況でも機能するオフライン対応が求められます。

<a id="google-translate"></a>
### Google Translate
[モバイル版 Google 翻訳](https://support.google.com/translate)は、リアルタイムカメラOCR、写真のインポート、手書き入力、画面分割による対面会話機能を統合しています。旅行者は事前に言語パックをダウンロードしておくことで、オフラインでのテキスト翻訳やオフラインカメラ翻訳を利用できます。音声による会話翻訳には複数の表示レイアウトが用意されていますが、オフラインでのリアルタイム音声通訳は特定のPixel端末および一部の言語ペアに限定されています。

デスクトップのブラウザでは、DOCX、PDF、PPTX、XLSXファイルに対応した専用の[ドキュメント翻訳ポータル](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)を提供しています。このデスクトップツールはデジタルファイル向けに設計されており、画像のみで構成されるスキャン済みPDFページは、OCR翻訳されずにそのままダウンロードファイルに残されます。

<p align="center"><img src="assets/google-page@2x.webp" alt="Google 翻訳 公式製品概要ページ" width="640"><br><sub>Google 翻訳の公式製品概要ページとモバイルアプリのダウンロードセクション</sub></p>

<a id="apple-translate"></a>
### Apple Translate
iPhoneやiPadのユーザー向けには、システム標準の[Apple 翻訳アプリ](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)が提供されており、別途インストールする必要がありません。テキスト入力、音声入力、カメラによるテキスト検出、画面分割による対面会話に対応しています。会話モードでは話されている言語を自動検出できるため、話者が交代するたびにマイクを手動で切り替える必要がありません。ダウンロード済みの言語パックを利用すれば、モバイル通信がない環境でもデバイス上でテキストを検索・翻訳できます。

AppleのOS内では、[リアルタイム翻訳機能](https://support.apple.com/en-us/123720)が「メッセージ」「電話」「FaceTime」にも拡張されています。通話中のリアルタイム翻訳はApple Intelligenceの一部として提供されており、対応するハードウェアおよびシステムバージョンが必要で、利用可能な地域にも制限があります（例えば、中国本土で購入されたデバイスでは、現在これらの高度なApple Intelligence通話機能はサポートされていません）。

<p align="center"><img src="assets/apple-page@2x.webp" alt="iPhone での翻訳に関する Apple サポートガイド" width="640"><br><sub>iPhone での単語や語句の翻訳に関する Apple サポートガイドページ</sub></p>

<a id="microsoft-translator"></a>
### Microsoft Translator
[Microsoft Translator モバイルアプリ](https://www.microsoft.com/en-us/translator/apps/features/)は、100+の言語でのテキスト翻訳、リアルタイム音声翻訳、および画像翻訳を提供しています。そのマルチデバイス会話機能（プレゼンターモード、ルームコード、ブラウザからの参加を含む）は、[iOS App Store リリースノート](https://apps.apple.com/us/app/microsoft-translator/id1018949559)および[Microsoft Speech SDK リリースノート](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/releasenotes)に記載されているとおり、廃止されました。

コンシューマー向けアプリでは外部の映画、動画ファイル、メディア録音の直接翻訳には対応していません。[Microsoftの機能紹介](https://www.microsoft.com/en-us/translator/apps/features/)には単一デバイスでの画面分割翻訳、オフライン言語パック、会話集が記載されているものの、現在のApp Storeの説明にはテキスト、音声、画像翻訳が記載されているため、オフラインパックや会話集に頼る前にアプリ内で確認してください。

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Microsoft Translator 公式機能紹介ページ" width="640"><br><sub>このスクリーンショットは2026年10月にキャプチャされたMicrosoftの機能紹介ページを示しており、同ページにはMicrosoftが廃止したマルチデバイス会話機能が現在も記載されています。</sub></p>

<a id="papago"></a>
### Papago
韓国のNAVERが開発した[Papago](https://papago.naver.com/)は、韓国語、英語、日本語、中国語などの東アジア言語において実用的な機能を提供しています。モバイル端末向け[アプリ](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator)では、対面対話、印刷物から学習ノートを作成するEduモード、フローティングウィンドウのPapago Miniなどを備えており、韓国での食事、交通機関の利用、語学学習などに重宝します。

Webページ翻訳については、プラットフォームによって利用可能な導線が異なります。NAVERはデスクトップWebポータル上の単独Webサイト翻訳ツールの提供を終了しており、PCユーザーにはPapagoを統合した[Whale ブラウザ](https://whale.naver.com/)の利用を案内しています。一方、[Papago モバイルアプリ](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE)ではサイドメニュー内にWebサイト翻訳オプションが引き続き維持されています。[NAVERのオフライン関連ドキュメント](https://help.naver.com/service/16448/contents/10663?osType=MOBILE)に記載されたシステム要件（4GB以上のRAM、音声認識には専用の音声パッケージを備えたAndroid 14以降が必要）を満たす対応端末で言語パックをダウンロードした場合、オフライン翻訳は韓国語、英語、日本語、簡体字中国語間のテキストおよび音声に対応します。なお、オフラインモードは写真OCR、対話モード、Webページ、文書ファイルには対応していません。

<p align="center"><img src="assets/papago-page@2x.webp" alt="NAVER Papago 公式 Web 翻訳インターフェース" width="640"><br><sub>NAVER Papago の Web 翻訳ワークスペース</sub></p>

<a id="itranslate"></a>
### iTranslate
[iTranslate](https://itranslate.com/)は、統合された[キーボード拡張機能](https://itranslate.com/features/keyboard-translations/index.html)で知られています。WhatsApp、iMessage、メールなどでメッセージを作成する際、キーボード画面内で直接テキストを翻訳できるため、別々のアプリを行き来する手間を省けます。

また、[オフラインツール](https://itranslate.com/features/offline-translations/index.html)を通じて頻出の旅行表現パックや基本的な会話集をダウンロードでき、出発前に必須フレーズを確認するのに実用的です。利用できる機能はOSによって異なり、オフラインでの音声機能は一部の主要言語に限定されています。

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="iTranslate 公式ホームページ" width="640"><br><sub>モバイルアプリのインターフェースプレビューを掲載した iTranslate のホームページ</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>
## 2. 文脈に沿ったWeb閲覧と語学学習：ページを離れずに読む

外国語の記事やドキュメントを読む際、外部の翻訳タブを何度も往復すると集中力が途切れてしまいます。インコンテキスト（文脈埋め込み型）のツールは、翻訳を閲覧中の画面に直接組み込むことで、そのストレスを解消します。

<a id="immersive-translate"></a>
### Immersive Translate
[Immersive Translate（没入型翻訳）](https://immersivetranslate.com/)は、Web上の元の段落の直下に訳文を挿入し、見やすい二言語並行レイアウトを表示するブラウザ拡張機能です。二言語対応のEPUB電子書籍の作成、PDFの閲覧、ブラウザの入力欄内でのテキスト翻訳にも対応しています。

マルチメディア分野では、YouTubeやNetflixなどのプラットフォームで既存の字幕トラックを翻訳できます。さらに、その[AI動画翻訳](https://immersivetranslate.com/video/ai-video-translator/)機能は音声認識を活用し、YouTubeなどの対応プラットフォーム上で字幕のない動画に対して二言語字幕を生成できるほか、専用の[YouTube ライブ翻訳ポータル](https://livetranslate.immersivetranslate.com/zh-CN)も提供しています。字幕のない音声からの字幕生成は、ブラウザの互換性、音声の明瞭さ、プラットフォームの配信状態に依存します。

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Immersive Translate 公式ホームページ" width="640"><br><sub>Immersive Translate のホームページおよびブラウザ拡張機能ダウンロードポータル</sub></p>

<a id="mate-translate"></a>
### Mate Translate
[Mate Translate](https://matetranslate.com/en)は、macOS、iOS、および主要なデスクトップブラウザ向けに設計されています。ブラウジング中に単語をダブルクリックすると即座にポップアップ定義が表示され、テキストを選択すると素早くコンテキスト翻訳が行われます。ページ全体の翻訳では原文と訳文の表示を切り替えることができ、Mac用の常駐メニューバーユーティリティも備わっています。

語学学習者向けには、Webページ上やNetflixの字幕内の単語をクリックして独自のフレーズ集（Phrasebook）に保存する機能があり、自由なカテゴリ分類や外部復習用のCSVエクスポートに対応しています。Chromeなどのデスクトップブラウザでは、内蔵PDFビューア内でテキストを選択して直接翻訳を呼び出すことも可能です。

<p align="center"><img src="assets/mate-page@2x.webp" alt="Mate Translate 公式ホームページ" width="640"><br><sub>マルチプラットフォームのインターフェースプレビューを表示した Mate Translate ホームページ</sub></p>

<a id="reverso"></a>
### Reverso
自然な単語の用法を確認したい執筆者や学習者向けに、[Reverso Context](https://context.reverso.net/translation/about)は映画、国際的な刊行物、多言語Webサイトから抽出された対訳例文を提供し、動詞の活用表や類語の提案もあわせて表示します。例文は公開されている多言語コーパスに由来するため、機密性の高い文書や改まったフォーマルな原稿を作成する際は、文脈の適切さを慎重に判断する必要があります。

ドキュメントポータルの[Reverso Documents](https://www.reverso.net/documents/en)は、PDF、Word、PowerPoint、Excel、および一部のローカライズ用ファイルに対応しています。ブラウザ上でセグメント単位のレビューインターフェースを提供しており、完成ファイルをダウンロードする前にチームで編集作業を共同で行うことができます。

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Reverso 公式翻訳インターフェース" width="640"><br><sub>Reverso の Web 翻訳インターフェースとナビゲーションバー</sub></p>

<a id="yandex-translate"></a>
### Yandex Translate
[Yandex Translate Web ポータル](https://yandex.com/support/translate-desktop/en/)およびモバイルアプリは、テキスト、画像、Webサイト、文書に対応しています。Androidクライアントには詳細な辞書機能が含まれており、対応言語の発音記号、定義、類語、語形変化を表示できます。

モバイル版では、Androidアプリに英語—ロシア語の[オフライン辞書](https://yandex.ru/support/translate-app-android/en/offline-mobile)があらかじめ組み込まれているほか、追加の言語パックをダウンロードすることで入力テキストのオフライン翻訳が可能です。デスクトップ画面では標準的なOfficeファイルやPDFのアップロードを受け付けています。なお、独立したサービスとしてのYandex Translateと、独自の自動動画吹き替え機能を備えたYandex Browserとは区別される点に留意してください。

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Yandex Translate 公式 Web インターフェース" width="640"><br><sub>Yandex Translate の入力インターフェースとサイドナビゲーション</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>
## 3. 複雑な文書レイアウトとエンタープライズワークフロー：書式と資産の保持

プレゼンテーションスライド、取引先との契約書、技術マニュアルなどを扱う際、レイアウトの崩れは膨大な手動修正の手間を引き起こします。以下のツールは、レイアウトの保持、用語の統一、翻訳資産の再利用を重視しています。

<a id="deepl"></a>
### DeepL
[DeepL 翻訳（DeepL Translator）](https://www.deepl.com/en/features)は、テキストおよび文書ワークフロー向けにきめ細かい設定オプションを提供しています。ユーザーは[用語集（Glossary）](https://www.deepl.com/en/features/glossary)を作成して社内規定の訳語や技術用語を適用できるほか、対応言語では敬称・親称（フォーマル／インフォーマル）のトーンを切り替えることができます。

その[ドキュメント翻訳サービス](https://www.deepl.com/en/features/document-translation)は、Word、PDF、PPT、Excel、HTML、SRTファイルに対応しています（利用可能な形式はアカウントの種類によって異なります）。プロダクトのエコシステムには、文章推敲のためのDeepL Write、TeamsやZoomでのリアルタイム字幕を実現する[DeepL Voice for Online Meetings](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings)（Voiceライセンスおよび主催者の権限が必要）、さらにはAIエージェント向けの公式Model Context Protocol（MCP）ガイドも含まれています。

<p align="center"><img src="assets/deepl-page@2x.webp" alt="DeepL 公式 Web 翻訳ワークスペース" width="640"><br><sub>DeepL の Web 翻訳インターフェース</sub></p>

<a id="otranslator"></a>
### O.Translator
[O.Translator](https://otranslator.com/en/product-info)は、レイアウトを保持する文書翻訳に特化しています。PDF、Word、PPT、Excelに加えて、EPUB電子書籍、InDesign（IDML）、Illustrator（AI）、OpenDocument、字幕ファイル（SRT/ASS）、コミックアーカイブ（CBZ/CBR）などの出版・ローカライズ形式に対応し、スキャンページ向けのOCR機能も内蔵しています。レイアウトの再現性は、フォントの埋め込み状況や訳文のテキスト拡張量に左右されます。

ファイル全体を翻訳する前に、O.Translatorでは一部のレイアウトプレビューを確認できます。XLSXやTBX経由での用語集インポートに対応し、[開発者向けAPI](https://www.otranslator.com/en/developer/v1)も提供されています。メディア向けオプションは、アップロードされた音声・動画ファイルを字幕ファイルに文字起こし・翻訳する用途向けに設計されており、ブラウザ内のリアルタイムストリーム翻訳ではありません。

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="O.Translator 公式製品ホームページ" width="640"><br><sub>O.Translator のホームページとドキュメントアップロードセクション</sub></p>

<a id="simplifyai"></a>
### SimplifyAI
SimplifyAIは2つの異なるWebサイトを運営しています。AIを活用した[複雑文書ワークベンチ（Complex Document Workbench）](https://simplifyai.cn/zh/translate)（simplifyai.cn/zh）と、[一般文書翻訳ポータル（General Document Translation portal）](https://translate.simplifyai.cn/)（translate.simplifyai.cn）です。

ワークベンチ内では、Word、PPTX、InDesign、PDF、EPUBファイルを対象に、翻訳前に高頻度の用語を抽出してユーザーが確認できます。また、WordやInDesign向けのAI編集機能（Wordネイティブの変更履歴記録に対応）、二言語データのエクスポート（Excel/XLIFF）、構造化Markdown/JSONの抽出、テキストのあふれやフォントレイアウトの目視チェック機能を備えており、DTP印刷前処理（プリプレス）やデザイン資産のローカライズに適しています。日常的なシンプルなファイル翻訳には、一般翻訳ポータルがより手軽な直接フローを提供します。

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="SimplifyAI 公式ホームページ" width="640"><br><sub>複雑文書ワークベンチとモジュールを紹介する SimplifyAI ホームページ</sub></p>

<a id="lingvanex"></a>
### Lingvanex
[Lingvanex](https://lingvanex.com/)は、WindowsおよびmacOS向けにデスクトップ、モバイル、ブラウザの各クライアントを提供しています。[Windows デスクトップ翻訳アプリ](https://lingvanex.com/products/windows-translator/)はシステム全体のショートカット（選択テキストに対するCtrl+Cの2回押しなど）に対応し、言語パックのダウンロード後はオフラインテキストおよびローカルのDOCX/ODTファイルの翻訳が可能です。

一般向けアプリにとどまらず、Lingvanexはオフラインの企業利用向けにダウンロード可能なデスクトップソフトウェア[Secure Translation Software](https://lingvanex.com/products/secure-translation-software/)を提供するほか、プライベートネットワーク環境向けのオンプレミス機械翻訳ソリューションも別途用意しています。

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Lingvanex 公式ホームページ" width="640"><br><sub>エンタープライズ翻訳およびオンプレミスソリューションを掲載した Lingvanex ホームページ</sub></p>

<a id="systran"></a>
### SYSTRAN
SYSTRANは、企業や公共機関のローカライズ要件を対象としています。クラウドサービスの[SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/)は、Word、PowerPoint、Excel、PDFファイルに即時対応し、カスタム用語集や翻訳メモリ（TM）とともに、法務、財務、製造などの業界向けに事前構成された特化ドメインモデルを提供します。

データ主権の要件を持つ組織向けに、SYSTRANは企業ファイアウォール内へのオンプレミス導入が可能な[Translate Server](https://www.systransoft.com/translation-products/translate-server/)、専用プライベートクラウド環境、および文書パイプライン用のバッチ[API](https://www.systransoft.com/translation-products/translate-api/)を提供しています。

<p align="center"><img src="assets/systran-page@2x.webp" alt="SYSTRAN Translate Pro 公式製品ページ" width="640"><br><sub>SYSTRAN Translate Pro の公式製品概要インターフェース</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>
## 4. 学術執筆・推敲と協調型編集：出力の精度を高める

翻訳は、より広範な執筆や研究ワークフローにおける初期フェーズにすぎないことがよくあります。辞書の定義を確認し、表現を推敲し、人間と機械が対話的に共同編集を行うことで、格式ある学術的基準を満たす成果物へと仕上げることができます。

<a id="youdao-translate-netease-youdao"></a>
### Youdao Translate (NetEase Youdao)
網易有道（NetEase Youdao）の辞書エコシステムと連携する[有道翻訳（Youdao Translate）](https://fanyi.youdao.com/)は、単語検索、翻訳、文章作成支援をシームレスにつなげています。標準的なテキストやファイルの翻訳に加え、Webポータルでは「arXiv論文翻訳」や学術論文の文章推敲専用のエントリーポイントが用意されています。

研究論文の抜粋を翻訳した後、ユーザーは文法チェックを実行したり、類語の選択肢を比較検討したり、学術的なトーンを調整したりできるため、学生や研究者が外国語文献を精読し、論文を執筆する際に役立ちます。なお、論文推敲機能やメディア関連モジュールで対応するファイル形式や言語の範囲は、一般的な辞書検索とは異なります。

<p align="center"><img src="assets/youdao-page@2x.webp" alt="網易有道翻訳 公式 Web ワークスペース" width="640"><br><sub>網易有道翻訳の Web インターフェースと機能ナビゲーション</sub></p>

<a id="baidu-translate"></a>
### Baidu Translate
[百度翻訳（Baidu Translate）](https://fanyi.baidu.com/)は、中国語圏のユーザーに向けて幅広いクライアント環境を提供しています。デスクトップソフトウェアにはコンパクトなフローティングウィンドウやローカルアプリ上でのショートカット選択翻訳機能が備わっており、モバイルアプリには写真翻訳、会話練習、辞書参照機能が統合されています。

さらに、Baiduは独立した[百度動画翻訳ポータル（Baidu Video Translation portal）](https://fanyi-video.baidu.com/)も運営しています。ユーザーはメディアファイルをアップロードしてタイムコードの同期した二言語字幕トラックを生成し、オンラインエディタ上で確認・編集して完成した字幕ファイルをエクスポートできます。これはアップロードベースのポストプロダクション向けツールであり、Web上のリアルタイム再生に対する自動通訳ではありません。

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Baidu Translate 公式 Web サイトページ" width="640"><br><sub>Baidu Translate の公式 Web インターフェース</sub></p>

<a id="transmart-tencent-interactive-translation"></a>
### TranSmart (Tencent Interactive Translation)
テンセントAIラボ（Tencent AI Lab）が開発した[TranSmart（腾讯交互翻译）](https://transmart.qq.com/zh-CN/intro)は、人間と機械の対話型コラボレーションを軸に設計されています。静的な訳文を生成して単にコピーさせるのではなく、TranSmartは単語レベルおよび文レベルの予測補完をリアルタイムで提示し、確定した対訳ペアをアクティブな翻訳メモリに統合していきます。

翻訳者は訳文内の任意の位置にカーソルを置いて修正を加えることができ、システムはそれに応じて後続の候補予測を動的に更新します。これにより、訳語の決定や文章のリズムをユーザー自身がコントロールでき、テンセントが提供する単体のコンシューマー向け辞書モバイルアプリとは明確に焦点を異にする協調型エディタとして機能します。

<p align="center"><img src="assets/transmart-page@2x.webp" alt="テンセント TranSmart 公式 Web ページ" width="640"><br><sub>テンセント TranSmart の公式 Web インターフェース</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>
### LingoCloud (Caiyun Xiaoyi)
[彩雲小訳（LingoCloud）](https://www.caiyunapp.com/?lang=zh)は、中国語、英語、日本語のワークフローで広く利用されています。そのブラウザ拡張機能は、公開共有用語集および個人用語集に対応し、Webページ内での二言語並行閲覧を実現します。[ドキュメント翻訳サービス](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)（モバイルアプリの案内準拠）は、PDF、Word、PPT、Excel、EPUB、TXT、SRTなどの形式を受け付け、元のファイルに応じて主にPDFまたはWord形式でダウンロード成果物を提供します。

デスクトップソフトウェアには[彩雲小訳同声伝訳（LingoCloud Interpretation）](https://www.caiyunapp.com/interpretation/)も搭載されており、マイク音声の集音や、起動中のアプリケーション（Windows上のZoom、Teams、Chromeなど）からのシステム音声出力を傍受して、リアルタイムの二言語字幕を表示できます。デスクトップ同声伝訳にはOSの音声キャプチャ仕様による制限があります。Windowsでは対応する会議アプリやメディアアプリでシステム音声キャプチャが機能しますが、macOSではOSのシステムアップデートの影響により現在内部システム音声の録音ルートがサポートされておらず、マイク集音のみが実用的な手段となります。

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="LingoCloud 公式 Web サイトページ" width="640"><br><sub>LingoCloud の公式 Web インターフェース</sub></p>

<a id="quillbot-translate"></a>
### QuillBot Translate
[QuillBot Translate](https://quillbot.com/translate)は、QuillBotの文章作成・編集エコシステム内で動作します。テキスト翻訳時、インターフェース上でフォーマル度の選択肢が提供され、対応言語では定義や類語が表示されます。

翻訳されたテキストは、言い換えツール（Paraphraser）や文法チェッカー（Grammar Checker）へとスムーズにコピーして文の流れを洗練させることができます。また、単一のPDFドキュメントをアップロードして確認するための専用[Translate PDF ページ](https://quillbot.com/translate-pdf)も用意されています。なお、翻訳ツール、文法チェック、言い換えツールの間で対応言語の範囲が異なる点には注意が必要です。

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="QuillBot 公式 Chrome ウェブストア拡張機能ページ" width="640"><br><sub>QuillBot ブラウザ拡張機能の公式 Chrome ウェブストア製品ページ</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>
## 5. オープンソースエコシステム：ローカルエンジン、API、デスクトップクライアント、学術PDFパイプライン

開発者、プライバシーを重視するチーム、学術研究者は、検証可能なコード、ローカルでのオフライン実行、あるいは独自の自動化パイプラインを必要とすることが多くあります。オープンソースの翻訳エコシステムは、いくつかの明確に異なるアーキテクチャ層に分かれています。

- **科学・学術PDFレイアウトツール**：段組構造、数式、図版を保持しながら複雑な学術論文を翻訳。
- **セルフホスト対応翻訳サービス**：ローカルネットワーク導入向けにHTTP REST APIエンドポイントとWeb UIを提供。
- **組み込み型オフライン翻訳エンジン**：外部ネットワークへの依存なしに、Pythonライブラリを介してローカル環境でニューラル機械翻訳を実行。
- **デスクトップ＆ターミナルフロントエンド**：マルチエンジン検索、クリップボード監視、OCR、シェルパイプラインを統合。

> [!IMPORTANT]
> オープンソースのコードをローカルで動かしているからといって、翻訳が自動的にオフラインかつプライベートになるわけではありません。ツール自体がローカルで動作していても、デフォルトでクラウドAPIにリクエストを送信している場合があります。真のオフライン翻訳を実現するには、ローカルモデル資産とローカル翻訳エンジンの両方が不可欠です。

<a id="51-scientific--academic-pdf-pipelines"></a>
### 5.1 学術論文・科学PDF処理パイプライン

<a id="pdfmathtranslate-pdf2zh"></a>
#### PDFMathTranslate (pdf2zh)
[PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate)（GNU AGPL v3）は、科学・学術分野のPDF文書向けに設計されたオープンソースツールです。論文の複数段組構造、数学記号・数式、埋め込み図版、目次、注釈を保持します。

- **デュアル（対照）およびモノ（単一）出力**：訳文のみのドキュメント（`-mono.pdf`）と二言語対訳ドキュメント（`-dual.pdf`）の両方を生成。
- **インターフェースと統合**：コマンドラインツール（CLI）、対話型WebUI、Dockerコンテナデプロイ、Model Context Protocol（MCP）サポートを提供。連携プロジェクトとしてZotero統合プラグインも利用可能。
- **翻訳バックエンド**：Google 翻訳（ドキュメント上のデフォルト）、DeepL、OpenAI互換API、ローカルのOllamaインスタンスなどをサポートするプラグイン型アーキテクチャを採用。DockerやWebUIでローカルデプロイしていても、クラウドバックエンドが設定されている場合はオフライン動作にはなりません。
- **OCRサポート**：白背景に黒文字のスキャンページ向けに実験的なOCR機能を搭載（初回使用時に言語モデル資産をダウンロードし、以降はローカルで再利用可能）。

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="PDFMathTranslate 公式 GitHub リポジトリページ" width="640"><br><sub>学術 PDF のレイアウト翻訳と CLI/WebUI ワークフローを示す公式 PDFMathTranslate リポジトリの概要</sub></p>

<a id="babeldoc"></a>
#### BabelDOC
[BabelDOC](https://github.com/funstory-ai/BabelDOC)（GNU AGPL v3）は、主にPythonアプリケーションへの組み込みを想定して設計された、デバッグ用CLIを備えたドキュメントレベルの学術論文翻訳・二言語対訳ライブラリです。

- **レイアウトと出力の制御**：モノまたはデュアル出力、同一ページ内での左右並置または原文／訳文の交互ページ配置、特定ページの選択翻訳、大規模PDFの分割と結合、カスタム用語集CSVの入力、数式の保持に対応。表内のテキスト翻訳は実験的機能として明記されています。
- **バックエンドアーキテクチャ**：OpenAI互換エンドポイントまたはローカルのOllamaインスタンスを介した翻訳バックエンドの設定が必要です。PDFの処理およびレイアウトエンジンであるため、それ自体には汎用翻訳エンジンはバンドルされていません。
- **オフライン資産と適用境界**：ドキュメントレイアウトモデルやフォント向けのウォームアップルーチン、オフライン資産の生成・復元機能を提供。完全なオフライン実行には、事前キャッシュされた資産と、ローカルで動作する翻訳バックエンド（ローカルのOllamaなど）の両方が必要です。ドキュメントでは英語から中国語へのワークフローを中心に検証されていることが明記されており、白背景に黒文字向けの実験的なOCR回避策も含まれています。

<p align="center"><img src="assets/babeldoc-page.webp" alt="BabelDOC 公式 GitHub リポジトリページ" width="640"><br><sub>ドキュメントレベルの学術 PDF 翻訳ライブラリ機能を示す公式 BabelDOC リポジトリの概要</sub></p>

<a id="52-self-hostable-engines--apis"></a>
### 5.2 セルフホスト対応エンジンとAPI

<a id="libretranslate"></a>
#### LibreTranslate
[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)（GNU AGPL v3）は、Argos Translateエンジンをベースに構築された、Web UI付属の無料かつオープンソースのセルフホスト対応機械翻訳APIサービスです。

- **APIとWebサービス**：テキスト翻訳、原文言語検出、HTML/マークアップ処理のためのREST APIエンドポイントを公開。商用翻訳APIのプロキシではなく、独立したサービスレイヤーとして機能します。
- **ローカルデプロイとプライバシー**：依存関係と言語モデルがインストールされていれば、外部のサードパーティにデータを送信することなく、完全にローカルハードウェア上で動作可能です。パブリックなホストインスタンスを利用する場合は引き続きネットワーク接続が必要です。APIキーによるアクセス制御はホストの要件に応じて有効化または無効化できます。
- **言語カバー範囲とファイル形式**：利用可能な言語ペアはインストールされた言語モデルに依存します。argos-translate-filesなどの関連プロジェクトを通じて、TXT、ODT、ODP、DOCX、PPTX、EPUB、HTML、SRT、PDFなどのファイル翻訳に対応します。

<p align="center"><img src="assets/libretranslate-page.webp" alt="LibreTranslate 公式 GitHub リポジトリページ" width="640"><br><sub>セルフホスト翻訳 API と Web インターフェース機能を示す公式 LibreTranslate リポジトリの概要</sub></p>

<a id="argos-translate"></a>
#### Argos Translate
[Argos Translate](https://github.com/argosopentech/argos-translate)（MIT License / READMEにてCC0オプションを明記）は、オープンソースのオフラインPython翻訳ライブラリおよびコマンドラインツールであり、個別にインストール可能なGUIクライアントも提供されています。

- **モジュール式モデルパッケージ**：`.argosmodel`拡張子の言語モデルパッケージをダウンロードして管理。直接の言語ペアが存在しない場合、インストール済みの言語ペアを経由してピボット翻訳（例：英語を経由した翻訳）を行うことができます。
- **エコシステムの中核エンジン**：LibreTranslateの基盤機械翻訳エンジンとして機能。関連プロジェクトによってHTML翻訳（`translate-html`）やファイル処理（`argos-translate-files`）へと機能が拡張されています。
- **オフライン動作**：モデルがインストールされた後は完全にオフラインで動作します。パッケージインデックスの取得と初期モデルのダウンロードにはインターネット接続が必要です。

<p align="center"><img src="assets/argos-translate-page.webp" alt="Argos Translate 公式 GitHub リポジトリページ" width="640"><br><sub>モジュール式オフライン翻訳エンジンとパッケージシステムを解説する公式 Argos Translate リポジトリの概要</sub></p>

<a id="53-desktop--terminal-frontends"></a>
### 5.3 デスクトップ＆ターミナルフロントエンド

<a id="pot-pot-desktop"></a>
#### Pot (pot-desktop)
[Pot](https://github.com/pot-app/pot-desktop)（GNU GPL v3）は、Windows、macOS、Linuxに対応したクロスプラットフォームのデスクトップ翻訳ツールで、ホットキーによる選択テキスト翻訳、テキスト入力、クリップボード監視、スクリーンショットOCR、スクリーンショット翻訳をサポートしています。なお、公式リポジトリは2026年9月7日付でアーカイブされ、読み取り専用（read-only）となっています。

- **マルチサービスの統合**：複数の翻訳サービスや辞書サービスを同時に検索し、結果を並べて比較することが可能。音声合成（TTS）、Ankiや欧路詞典（Eudic）への単語帳エクスポート、プラグイン拡張に対応。
- **プラグイン型バックエンドとOCR**：クラウド翻訳プロバイダー、OpenAI互換API、ローカルのOllamaエンドポイントを集約。OCRの選択肢には、プラットフォームネイティブの機能（WindowsシステムOCR、Apple Vision、Linux Tesseract）、Tesseract.js、またはローカルプラグインが含まれます。
- **オフライン実行ルート**：選択テキストおよび入力テキストの翻訳には、設定済みのローカル翻訳バックエンド（ローカルのOllamaインスタンスなど）のみが必要です。スクリーンショット翻訳には、さらにオフラインOCRエンジン（プラットフォームネイティブのOCRやTesseractなど）が必要となります。クラウドサービスを利用する場合はネットワーク経由でリクエストが送信されます。

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Pot デスクトップ翻訳 公式 GitHub リポジトリページ" width="640"><br><sub>マルチインターフェース翻訳、OCR、クリップボードワークフローを強調した公式 Pot デスクトップクライアントリポジトリの概要</sub></p>

<a id="translate-shell"></a>
#### Translate Shell
[Translate Shell](https://github.com/soimort/translate-shell)（The Unlicense / パブリックドメイン）は、Unix系ターミナル環境向けの多機能なコマンドライン翻訳ツール（実行ファイル `trans`）です。

- **CLI検索と辞書機能**：シェル上で直接、単語の定義、フレーズ翻訳、簡潔な辞書モード、対話型REPLセッション、言語識別を実行可能。
- **Unixパイプライン**：標準入出力（`stdin` / `stdout`）と連携し、テキストファイルを直接処理可能。外部オーディオプレーヤーがインストールされている場合は音声合成もサポート。
- **エンジン層**：公開翻訳サービス（デフォルトは Google 翻訳、その他 Bing Translator、Yandex.Translate、Apertium）に接続する軽量クライアントフロントエンドとして動作。
- **適用境界**：ローカルのニューラル翻訳モデルは内包していません。標準的な動作は選択したエンジンサービスへの外部ネットワーク接続に依存します。ファイル翻訳は書式付きドキュメントではなく、プレーンテキストストリーム向けに設計されています。

<p align="center"><img src="assets/translate-shell-page.webp" alt="Translate Shell 公式 GitHub リポジトリページ" width="640"><br><sub>ターミナルのコマンドライン翻訳とパイプライン統合を示す公式 Translate Shell リポジトリの概要</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>
## 6. シームレスにつながるエンドツーエンドワークフロー：[Equalang](https://equalang.com/?utm_source=github)

ここまで見てきた各ツールは、それぞれ特定のタスクに対して明確な強みを発揮しています。しかし、日々の業務においては、これらの要件が複雑に交差することが珍しくありません。

ブラウザでオンラインのホワイトペーパーを読み、表や図版を含む付属のPDFをダウンロードし、字幕のない動画講義を視聴し、海外の共同作業者と直接連絡を取りながらWordでエグゼクティブサマリーをまとめる——。分断されたソフトウェアツールやファイルコンバータの間を行き来していると、作業フローが断片化してしまいます。

私たちは、こうした多様なタスクを途切れのない対訳（side-by-side）ワークフローへと統合し、文書、Webページ、動画、そして対面・音声コミュニケーションにわたって一貫した翻訳体験を提供するために **[Equalang](https://equalang.com/?utm_source=github)** を設計しました。

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Equalang 公式英語版ホームページ" width="640"><br><sub><a href="https://equalang.com/?utm_source=github">Equalang</a> 公式英語版ウェブサイトのホームページ</sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>
### 1. レイアウトを保持したファイル全体の文書翻訳
ファイル全体の文書を翻訳する際、[Equalang](https://equalang.com/?utm_source=github)は構造の保持と翻訳後の使い勝手を重視し、研究文献、プレゼンテーション、日常的なオフィスファイルに合わせたワークフローを提供します。

- **PDF文書と閲覧**：[Equalang](https://equalang.com/?utm_source=github)は複数段組のレイアウト、ヘッダー、フッター、図表キャプションを保持し、改ページで分断された文章を翻訳前に結合した上で、表構造、文中の数式、ドキュメント内部リンクを維持します。[学術PDF閲覧ガイド](https://equalang.com/blog/translate-and-read-pdf-documents?utm_source=github)で解説しているとおり、読者は原文と訳文を並べた左右対照レイアウトで閲覧でき、まずは母国語で大筋の内容を把握した上で、元のページの特定の専門用語やデータを照らし合わせて確認できます。

- **PowerPointプレゼンテーション**：[スライド書式設定ガイド](https://equalang.com/blog/translate-powerpoint-keep-formatting?utm_source=github)にあるように、翻訳されたPPTXファイルは編集可能なネイティブの表構造を保持し、静止画像に変換してしまうことがありません。一文の中にある太字、斜体、文字色などの単語レベルのスタイルも、対応する翻訳フレーズに正確に反映されます。スライド全体で重要用語や見出しの一貫性が保たれ、訳文が長くなった場合でもテキストボックスのフォントサイズが自動縮小されるため、文字あふれや図版の遮蔽を防ぎます。

- **Word＆Excelオフィスファイル**：実証済みの[Word翻訳テスト](https://equalang.com/blog/translate-word-document-keep-formatting?utm_source=github)において、翻訳後のDOCXファイルは見出し、箇条書きリスト、価格表、太字の書式を維持し、Microsoft Wordで直接編集できる状態を保ちました。また、[Excel価格表の検証](https://equalang.com/blog/translate-excel-file?utm_source=github)では、数式や数値を一切変更せず、セル間で重複する同一テキスト文字列を一度だけ翻訳して処理を最適化しました。

- **電子書籍とメディアファイル**：EPUB電子書籍では目次ナビゲーションや内部アンカーリンクが保持されます。最長180分までの録音音声および動画ファイルについては、一般的なWeb文書アップロードポータルではなく、開発者向けAPIおよびAgent Skill/MCP連携を通じて翻訳・文字起こしタスクを送信でき、タイムスタンプ付きの二言語SRT/VTT字幕ファイルや原文の文字起こしテキストを出力します。

<a id="2-in-browser-reading--subtitle-generation"></a>
### 2. ブラウザ内での閲覧と字幕生成
軽量な[ブラウザ拡張機能](https://equalang.com/extension?utm_source=github)（Chrome、Edge、Firefox向けのインストールガイドに加え、Safari 18.4以降向けのMac Safari一時モードを提供）を通じて、日々のブラウジングに翻訳が自然に溶け込みます。

- **段落直下の二言語並行Web閲覧**：スクロールに合わせて、原文の直下に訳文段落が表示されます。設定によりフローティングアイコンを有効にして、必要に応じた単語検索も行えます。ローカルのPDFを閲覧する際は、拡張機能の管理画面で「ファイルの URL へのアクセスを許可する」を有効にすることで、単語を選択して意味を調べることができます。

- **二言語動画字幕**：[二言語動画視聴ガイド](https://equalang.com/blog/watch-videos-with-bilingual-subtitles?utm_source=github)で紹介しているように、YouTube、Netflix、TikTok、Bilibiliに対応しています。既存の字幕を翻訳するだけでなく、音声ストリームをキャプチャして**字幕のない動画**に対してもリアルタイムで二言語字幕を生成できます（ブラウザ環境やメディアの暗号化制限に依存し、YouTubeのライブ配信や公式予告編で検証済み）。さらに、YouTubeのライブチャットコメントも同時に翻訳可能です。

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>
### 3. アプリインストール不要の音声コミュニケーションと現場での対話
会話の相手に専用のモバイルアプリをインストールしてもらうことは、特に旅行や出張中には大きな心理的・操作的ハードルとなります。インターネット接続があれば、[Equalang](https://equalang.com/?utm_source=github)は標準的なブラウザ上でそのままモバイル写真翻訳や音声通訳を提供します（初回のみサインインと端末のカメラ・マイクの許可が必要）。詳細は[国際コミュニケーションガイド](https://equalang.com/blog/talk-with-overseas-partners?utm_source=github)で解説しています。

- **モバイル写真翻訳**：旅行中に見知らぬ飲食店のメニュー、看板、公共の案内表示に遭遇した際、モバイルブラウザから写真を撮影できます。訳文が写真のレイアウト上に直接オーバーレイ表示されるため、[旅行向け写真翻訳ガイド](https://equalang.com/blog/photo-translation-for-travel?utm_source=github)に示すとおり、元の画像と見比べながら注文や内容確認がスムーズに行えます。

- **対面会話モード**：ホテルの荷物預かり、道案内、フロントでのやり取りなど、対面でのやり取りを想定して設計されています。1台のスマートフォンやタブレットを2人の間に平置きし、反転画面分割や左右並置ビューを用いて、双方向の連続文字起こしと会話ログのエクスポートが可能です（[旅行向け対面対話ガイド](https://equalang.com/blog/talk-face-to-face-while-traveling?utm_source=github)参照）。

- **リアルタイム傾聴（ライブリスニング）**：対面でのプレゼンテーションや講義中にWebポータルを開くと、端末の物理マイクを通じて集音した音声からリアルタイムの二言語字幕が表示されます。聴取中はオプションでリアルタイムの音声読み上げを利用できるほか、終了後には文字起こし記録のエクスポートが可能です（ブラウザ拡張機能によるストリーミングメディア音声キャプチャとは区別されます）。

- **リアルタイム翻訳通話**：ホストがWebポータルにログインして安全な通話リンクを生成し、任意のメッセージングアプリで共有します。**ゲスト側はアカウント作成もソフトウェアのインストールも不要で、ブラウザから直接参加できます**。表示名を入力し、ホストが入室を許可するだけで通話が始まります。双方が母国語で話すと、相手には翻訳された音声が再生され、リアルタイムのテキストも画面に表示されます。

<a id="4-integration-for-ai-agents-and-developers"></a>
### 4. AIエージェントと開発者のための統合環境
開発者やチームが自動化ワークフローに翻訳を組み込めるよう、以下のインターフェースを提供しています。

- **開発者向けAPI**：テキスト用の即時エンドポイントに加え、Idempotency-Key（冪等性キー）によるリトライやコールバック通知に対応した非同期ファイルジョブを提供（詳細は[ファイル翻訳API統合ガイド](https://equalang.com/blog/integrate-file-translation-api?utm_source=github)を参照）。

- **Skill＆MCP連携**：オープンソースのAgent Skill（[equalang-skill](https://github.com/equalang/equalang-skill)）および公式Model Context Protocolサポート（[@equalang/mcp](https://github.com/equalang/equalang-mcp)）を保守・公開しています。Claude Code、Codex、WorkBuddyなどの環境において、1行のインストールプロンプトを実行してAPIキーを設定するだけで、[AIアシスタント向けファイル翻訳ガイド](https://equalang.com/blog/translate-files-with-ai-assistants?utm_source=github)に沿って、お使いのAIアシスタントが文書翻訳やメディア文字起こしをワークフロー内で直接処理できるようになります。

---

<a id="7-task-based-decision-guide"></a>
## 7. タスク別選定ガイド

現在のタスクに最適なツールを選択するための対照表です。

| 主なタスク | 中核となる要件 | 推奨ツール | 主な検討事項 |
| :--- | :--- | :--- | :--- |
| **旅行・対面対話** | 写真OCR、双方向対話、オフラインパック、オンライン旅行ツール | Google Translate、Apple Translate、Papago、[Equalang](https://equalang.com/?utm_source=github) | 電波の届きにくい場所向けにGoogle、Apple、またはPapagoでオフライン言語パックを事前にダウンロード（ハードウェア要件に留意）。通信環境がある場合、[Equalang](https://equalang.com/?utm_source=github)はアプリのインストール不要でブラウザ上の写真翻訳や対面対話を提供。 |
| **マルチデバイスワークショップ** | 1対多のプレゼンテーション、複数端末での参加 | 本ディレクトリでは現在、このシナリオに対応するツールを掲載していません。 | Microsoftは2026年にマルチデバイス会話機能とプレゼンターモードを廃止しており（詳細は上記のMicrosoft Translatorセクションを参照）、これが現在本ディレクトリにツールが掲載されていない理由です。 |
| **Webページの精読** | ページを離れない段落直下での閲覧 | Immersive Translate、[Equalang](https://equalang.com/?utm_source=github)、Mate Translate | 二言語並行の段落表示にはImmersive Translateまたは[Equalang](https://equalang.com/?utm_source=github)を使用。ページ全体の表示切り替えやMacでの単語帳（Phrasebook）保存にはMate Translateを活用。 |
| **字幕のない動画・ライブ配信** | リアルタイム字幕生成、ストリーミング互換性 | [Equalang](https://equalang.com/?utm_source=github)、Immersive Translate | 両ツールとも対応プラットフォーム（YouTubeなど）で生音声から字幕を生成可能。ライブチャットの翻訳や配信処理のブラウザ拡張ワークフローを比較して選択。 |
| **学術論文・科学PDF** | 数式の保持、段組構造、ページまたぎテキストの結合 | PDFMathTranslate、BabelDOC、[Equalang](https://equalang.com/?utm_source=github) | PDFMathTranslateとBabelDOCは二言語対照PDF出力とローカル/クラウドLLMバックエンドを備えたオープンソースパイプラインを提供。[Equalang](https://equalang.com/?utm_source=github)はブラウザ上での左右対照閲覧とレイアウト保持を提供。 |
| **DTP・デザイン形式** | InDesign、Illustrator、コミックアーカイブ、プリプレスQA | SimplifyAI、O.Translator | InDesign（IDML）やデザイン資産のプリプレスにはSimplifyAIとO.Translatorを活用。SimplifyAIはWordネイティブの変更履歴記録に対応したAI編集機能を搭載。 |
| **プレゼン・オフィス文書** | ネイティブ表、スタイル、数式の保持と編集可能性 | [Equalang](https://equalang.com/?utm_source=github)、DeepL | [Equalang](https://equalang.com/?utm_source=github)はフォントサイズの自動調整を伴うPPTXネイティブ表・スタイルの保持やExcel数式の維持に対応。用語集を活用した企業向けWord/OfficeファイルにはDeepLを使用。 |
| **学術執筆・推敲** | 文法の正確さ、格式ある学術的文体 | Youdao Translate、QuillBot Translate、TranSmart | YoudaoとQuillBotは翻訳から文章推敲への移行を効率化。TranSmartは対話型の人間・機械協調編集を提供。 |
| **デスクトップショートカット検索・複数エンジン比較** | グローバルショートカット、OCR、複数エンジンの比較 | Pot、Mate Translate | PotはWindows、Mac、Linuxで複数エンジンの同時検索やスクリーンショットOCRに対応。MateはMacネイティブのメニューバーユーティリティを提供。 |
| **ターミナルスクリプト・シェルパイプライン** | CLI検索、stdin/stdoutパイプライン、プレーンテキストスクリプト | Translate Shell、Argos Translate | Translate Shellはリモートエンジンを介した軽量なCLI翻訳を提供。Argos Translateはローカルモデルを備えたオフラインPython CLIを提供。 |
| **セルフホスト専用API・オフラインエンジン** | エアギャップ（閉域網）環境、第三者へのデータ送信遮断 | LibreTranslate、Argos Translate、SYSTRAN、Lingvanex | LibreTranslateはセルフホスト対応のHTTP APIサービスとWebUIを提供。Argos Translateはその基盤としてモジュール式モデルパッケージを備えたオフラインPythonライブラリ/CLIエンジンを提供。SYSTRANとLingvanexは企業のオンプレミスデプロイに対応。 |
| **統合エンドツーエンドワークフロー** | 文書、ストリーミング字幕、Web通話、AIエージェント連携 | [Equalang](https://equalang.com/?utm_source=github) | 一元的な文書処理、字幕なしメディアの字幕生成、アプリ不要のブラウザ通話、Claude CodeやWorkBuddyとの直接連携を提供。 |

---

<a id="8-directory-principles--verification-criteria"></a>
## 8. ディレクトリの編集方針と検証基準

本カタログの実用性と事実に基づく正確性を維持するため、掲載ツールの選定およびレビューは以下の厳格な基準に従っています。

1. **宣伝文句ではなく公式ドキュメントに基づく記述**：各ツールの説明は、公式ドキュメント、ユーザーマニュアル、確認済みのリポジトリソースファイルに基づいています。「完全なレイアウト保持」や「あらゆる形式への万能な対応」といった根拠のない過度の主張は行いません。
2. **明確なアーキテクチャ境界の提示**：翻訳フロントエンド、セルフホスト対応サービス層、オフライン翻訳エンジン、文書レイアウト処理ライブラリを明確に区別しています。ローカルで動作するオープンソースコードと、真のオフライン実行との違いを厳密に区別して記載しています。
3. **タスク指向の構成**：ツールはワークフローにおける実用的な適合性に基づいて分類されています。主観的なランキング、優劣の格付け、変動しやすい料金情報の記載は行いません。
4. **透明性のある運営元の明示**：本カタログは **[Equalang](https://equalang.com/?utm_source=github)** チームによって企画・保守されています。[Equalang](https://equalang.com/?utm_source=github)についても他のツールと同様に、検証可能な機能の境界と明確なシステム要件を提示しています。

**キーワード**：翻訳ツール、ドキュメント翻訳、二言語Web閲覧、学術PDF翻訳、オープンソース翻訳、機械翻訳API、レイアウト保持、AIエージェント

---

<a id="9-sources"></a>
## 9. 出典・参考資料

1. [Google 翻訳 ヘルプセンター](https://support.google.com/translate)
2. [Google 翻訳 デスクトップ版ドキュメント翻訳](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Apple サポート：iPhone 翻訳アプリガイド](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Apple サポート：リアルタイム翻訳と利用可能な機能](https://support.apple.com/en-us/123720)
5. [Microsoft Translator モバイル機能紹介](https://www.microsoft.com/en-us/translator/apps/features/)
6. [iOS App StoreのMicrosoft Translator](https://apps.apple.com/us/app/microsoft-translator/id1018949559)
7. [Microsoft Speech SDK リリースノート](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/releasenotes)
8. [NAVER Papago 公式ポータル](https://papago.naver.com/)
9. [iTranslate キーボード＆オフライン機能](https://itranslate.com/features/keyboard-translations/index.html)
10. [Reverso Context 利用案内](https://context.reverso.net/translation/about)
11. [Reverso Documents ポータル](https://www.reverso.net/documents/en)
12. [Yandex Translate デスクトップ＆モバイルヘルプ](https://yandex.com/support/translate-desktop/en/)
13. [Immersive Translate ドキュメント](https://immersivetranslate.com/)
14. [O.Translator 製品情報と対応形式](https://otranslator.com/en/product-info)
15. [SimplifyAI 複雑文書ワークベンチ](https://simplifyai.cn/zh/translate)
16. [SimplifyAI 一般文書翻訳ポータル](https://translate.simplifyai.cn/)
17. [Mate Translate 機能一覧](https://matetranslate.com/en)
18. [Lingvanex Windows 翻訳アプリ](https://lingvanex.com/products/windows-translator/)
19. [Lingvanex Secure Translation Software](https://lingvanex.com/products/secure-translation-software/)
20. [SYSTRAN Translate Pro とエンタープライズデプロイ](https://www.systransoft.com/translation-products/translate-pro/)
21. [網易有道翻訳](https://fanyi.youdao.com/)
22. [百度翻訳＆動画翻訳ポータル](https://fanyi.baidu.com/)
23. [テンセント TranSmart 製品紹介](https://transmart.qq.com/zh-CN/intro)
24. [彩雲小訳（LingoCloud）ドキュメントヘルプ](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
25. [QuillBot Translate＆PDFポータル](https://quillbot.com/translate)
26. [Equalang API 仕様書とドキュメント](https://equalang.com/llms-full.txt?utm_source=github)
27. [PDFMathTranslate 公式 GitHub リポジトリ](https://github.com/PDFMathTranslate/PDFMathTranslate)
28. [PDFMathTranslate 詳細設定オプションドキュメント](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
29. [BabelDOC 公式 GitHub リポジトリ](https://github.com/funstory-ai/BabelDOC)
30. [LibreTranslate 公式 GitHub リポジトリ](https://github.com/LibreTranslate/LibreTranslate)
31. [LibreTranslate ドキュメント＆APIガイド](https://docs.libretranslate.com/)
32. [Argos Translate 公式 GitHub リポジトリ](https://github.com/argosopentech/argos-translate)
33. [Pot デスクトップ翻訳 公式 GitHub リポジトリ](https://github.com/pot-app/pot-desktop)
34. [Translate Shell 公式 GitHub リポジトリ](https://github.com/soimort/translate-shell)
