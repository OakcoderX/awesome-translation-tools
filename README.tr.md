# Awesome Translation Tools

> Seyahat, web okuması, formatlı belgeler, akademik araştırma, açık kaynaklı yerel motorlar ve geliştirici iş akışlarını kapsayan, özenle derlenmiş çeviri araçları ve iş akışları dizini.

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

Çeviri görevleri bağlama göre temelden farklılık gösterir: cep telefonunda bir sokak tabelasını veya menüyü çözmek, tarayıcıda yabancı dildeki teknik belgeleri okumak, karmaşık sunum slaytlarını ve sözleşmeleri sayfa düzenini bozmadan çevirmek, akademik makalelerdeki matematiksel formülleri korumak, uçbirimde gizli toplu çeviriler çalıştırmak veya altyazısız video akışlarını takip etmek.

Biz **[Equalang](https://equalang.com/?utm_source=github)** ekibiyiz. Bu dizin, köklü çeviri ürünlerinin ve önde gelen açık kaynaklı projelerin pratik ve görev odaklı bir kataloğunu sunar. Kendi iş akışınız için doğru çözümü belirlemenize yardımcı olmak amacıyla her bir araç için belgelenmiş yetenekleri, erişim noktalarını, dağıtım modellerini ve operasyonel kısıtlamaları özetliyoruz.

---

<a id="contents"></a>

## İçindekiler

- [1. Seyahat ve Sözlü İletişim: Çok Modlu ve Sözlü Girdiler](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. Sayfa İçi Web Okuma ve Dil Öğrenme: Sayfadan Ayrılmadan Okuma](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. Karmaşık Belge Düzenleri ve Kurumsal İş Akışları: Formatları ve Varlıkları Koruma](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. Akademik Yazım, Metin İyileştirme ve İnsan Denetimli İş Birliği: Çıktıyı Kusursuzlaştırma](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. Açık Kaynak Ekosistemi: Yerel Motorlar, API'ler, Masaüstü İstemcileri ve Bilimsel PDF İş Akışları](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 Bilimsel ve Akademik PDF İş Akışları](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 Kendi Sunucunda Barındırılabilir Motorlar ve API'ler](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 Masaüstü ve Uçbirim Arayüzleri](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. Uçtan Uca Entegre İş Akışları:](#6-connected-end-to-end-workflows-equalang) [Equalang](https://equalang.com/?utm_source=github)
  - [1. Sayfa Düzenini Koruyarak Tam Belge Çevirisi](#1-whole-file-document-translation-with-layout-preservation)
  - [2. Tarayıcı İçi Okuma ve Altyazı Oluşturma](#2-in-browser-reading--subtitle-generation)
  - [3. Kurulum Gerektirmeyen Sözlü İletişim ve Yüz Yüze Görüşme](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. Yapay Zekâ Ajanları ve Geliştiriciler İçin Entegrasyon](#4-integration-for-ai-agents-and-developers)
- [7. Görev Odaklı Karar Rehberi](#7-task-based-decision-guide)
- [8. Dizin İlkeleri ve Doğrulama Kriterleri](#8-directory-principles--verification-criteria)
- [9. Kaynaklar](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>

## 1. Seyahat ve Sözlü İletişim: Çok Modlu ve Sözlü Girdiler

Seyahat ve saha çalışmaları; hızlı başlatma, güvenilir çok modlu tanıma ve ağ bağlantısının sınırlı olduğu durumlarda çevrimdışı kullanıma hazır olma gerektirir.

<a id="google-translate"></a>

### Google Translate
[Mobil cihazlarda Google Çeviri](https://support.google.com/translate); anlık kamera OCR'ı, fotoğraf içe aktarma, el yazısı girişi ve bölünmüş ekranda yüz yüze konuşma özelliklerini bir araya getirir. Gezginler, çevrimdışı metin ve çevrimdışı kamera çevirisi için dil paketlerini önceden indirebilir. Sözlü karşılıklı konuşma çevirisi birden fazla ekran düzeni sunar; ancak çevrimdışı canlı konuşma tercümesi belirli Pixel cihazları ve seçili dil çiftleriyle sınırlıdır.

Masaüstü tarayıcılarda Google Çeviri, DOCX, PDF, PPTX ve XLSX dosyalarını kabul eden özel bir [belge çeviri portalı](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en) sağlar. Bu masaüstü aracı dijital dosyalar için tasarlanmıştır; salt görüntü içeren taranmış PDF sayfaları, OCR çevirisi yapılmadan indirilen dosyada olduğu gibi korunur.

<p align="center"><img src="assets/google-page@2x.webp" alt="Google Çeviri resmî ürün genel bakış sayfası" width="640"><br><sub>Resmî Google Çeviri ürün genel bakış sayfası ve mobil uygulama indirme bölümü</sub></p>

<a id="apple-translate"></a>

### Apple Translate
iPhone ve iPad kullanıcıları için sistem düzeyindeki [Apple Çeviri uygulaması](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios) ayrı bir kurulum gerektirmez. Yazılı metin, ses girişi, kamera ile metin algılama ve bölünmüş ekranda yüz yüze konuşma özelliklerini destekler. Sohbet modu hangi dilin konuşulduğunu otomatik olarak algılayabilir; böylece mikrofonu konuşmacılar arasında manuel olarak değiştirme zorunluluğunu ortadan kaldırır. İndirilen dil paketleri, hücresel bağlantı olmadan cihaz üzerinde metin araması yapılmasını sağlar.

Apple işletim sistemi içinde [canlı çeviri özellikleri](https://support.apple.com/en-us/123720) Mesajlar, Telefon ve FaceTime uygulamalarını da kapsar. Canlı telefon görüşmesi çevirisi Apple Intelligence'ın bir parçasıdır; uyumlu donanım ve sistem sürümleri gerektirir ve bölgesel uygunluk kurallarına tabidir (örneğin, Çin anakarasından satın alınan cihazlar şu anda bu gelişmiş Apple Intelligence arama özelliklerini desteklememektedir).

<p align="center"><img src="assets/apple-page@2x.webp" alt="iPhone'da çeviri yapma konulu Apple Destek kılavuzu" width="640"><br><sub>iPhone'da sözcük ve ifadeleri çevirme konulu Apple Destek kılavuzu sayfası</sub></p>

<a id="microsoft-translator"></a>

### Microsoft Translator
[Microsoft Translator mobil uygulaması](https://www.microsoft.com/en-us/translator/apps/features/), [çok cihazlı konuşma özelliği](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/) ile öne çıkar. Bir oturum sahibi mobilde oturum başlatır ve katılımcılar QR kod tarayarak veya bir kod girerek mobil uygulama ya da herhangi bir masaüstü web tarayıcısı üzerinden katılır. Her katılımcı kendi seçtiği dilde canlı döküm ve çeviri alır. Sunucu modu, oturum sahibinin mikrofonunu açık tutarken dinleyicileri sessize alır; bu da rehberli turlar ve konferanslar için oldukça kullanışlıdır.

Uygulama ayrıca sık kullanılan seyahat sorguları için indirilebilir konuşma kılavuzları ve çevrimdışı fotoğraf çevirisi içerir. Tüketiciye yönelik uygulama doğrudan harici filmleri, video dosyalarını veya medya kayıtlarını çevirmeyi desteklemez ve çok cihazlı sesli oturumlar aktif bir internet bağlantısı gerektirir.

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Microsoft Translator resmî özellikler sayfası" width="640"><br><sub>Çok cihazlı konuşma özelliğini öne çıkaran Microsoft Translator özellikler sayfası</sub></p>

<a id="papago"></a>

### Papago
Güney Kore'de NAVER tarafından geliştirilen [Papago](https://papago.naver.com/), Korece, İngilizce, Japonca ve Çince dahil olmak üzere Doğu Asya dilleri için pratik özellikler sunar. Mobil cihazlarda [uygulaması](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator); yüz yüze diyalog, basılı metinlerden çalışma notları oluşturmaya yarayan Edu modu ve Papago Mini kayan penceresini sunarak Kore'de yemek yeme, toplu taşıma sorguları ve ders çalışma süreçlerinde kolaylık sağlar.

Web sayfası çevirisinde kullanılabilir erişim noktaları platformlar arasında farklılık gösterir: NAVER, masaüstü web portalındaki bağımsız web sitesi çeviri aracını sonlandırarak PC kullanıcılarını Papago destekli [Whale tarayıcısına](https://whale.naver.com/) yönlendirirken, [Papago mobil uygulaması](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE) yan menüsünde web sitesi çevirisi seçeneğini korumaktadır. Dil paketleri sistem önkoşullarını karşılayan uyumlu cihazlara indirildiğinde ([NAVER'ın çevrimdışı belgelerinde](https://help.naver.com/service/16448/contents/10663?osType=MOBILE) belirtildiği üzere en az 4 GB RAM ve ses için özel ses paketlerine sahip Android 14+ gerekir), çevrimdışı çeviri Korece, İngilizce, Japonca ve Basitleştirilmiş Çince arasında metin ve sesi destekler. Çevrimdışı modun fotoğraf OCR'ını, konuşma modunu, web sayfalarını veya belge dosyalarını kapsamadığını unutmayın.

<p align="center"><img src="assets/papago-page@2x.webp" alt="NAVER Papago resmî web çeviri arayüzü" width="640"><br><sub>NAVER Papago web çeviri çalışma alanı</sub></p>

<a id="itranslate"></a>

### iTranslate
[iTranslate](https://itranslate.com/), entegre [Klavye Uzantısı](https://itranslate.com/features/keyboard-translations/index.html) ile tanınır. Kullanıcılar WhatsApp, iMessage veya e-postada mesaj yazarken ayrı uygulamalar arasında sürekli geçiş yapmaktan kaçınarak metinleri doğrudan klavye arayüzü içinde çevirebilir.

Ayrıca [çevrimdışı araçları](https://itranslate.com/features/offline-translations/index.html) aracılığıyla yaygın seyahat ifadeleri ve temel konuşma kılavuzları için indirilebilir paketler sunar; bu da seyahate çıkmadan önce temel ifadeleri gözden geçirmeyi pratik hale getirir. Özelliklerin kullanılabilirliği işletim sistemlerine göre değişir ve çevrimdışı ses yetenekleri belirli başlıca dillerden oluşan seçili bir listeyle sınırlıdır.

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="iTranslate resmî ana sayfası" width="640"><br><sub>Mobil uygulama arayüzü önizlemelerini içeren iTranslate ana sayfası</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>

## 2. Sayfa İçi Web Okuma ve Dil Öğrenme: Sayfadan Ayrılmadan Okuma

Yabancı dildeki makaleleri veya belgeleri incelerken harici bir çeviri sekmesine gidip gelmek odaklanmayı bozar. Bağlam içi araçlar, çeviriyi doğrudan aktif okuma ortamına yerleştirir.

<a id="immersive-translate"></a>

### Immersive Translate
[Immersive Translate](https://immersivetranslate.com/), çevrilmiş paragrafları doğrudan orijinal web metninin hemen altına ekleyerek düzenli bir iki dilli düzen sunan bir tarayıcı uzantısıdır. Ayrıca iki dilli EPUB e-kitapları oluşturmayı, PDF'leri görüntülemeyi ve tarayıcı giriş alanlarındaki metinleri çevirmeyi de destekler.

Multimedya tarafında Immersive Translate; YouTube ve Netflix gibi platformlardaki mevcut altyazı parçalarını çevirir. Buna ek olarak, [yapay zekâ video çevirisi](https://immersivetranslate.com/video/ai-video-translator/) özelliği, YouTube gibi desteklenen platformlarda altyazısız videolar için iki dilli altyazı oluşturmak üzere konuşma tanımadan yararlanır ve özel bir [YouTube canlı çeviri portalı](https://livetranslate.immersivetranslate.com/zh-CN) sunar. Altyazısız seslerden altyazı oluşturulması; tarayıcı uyumluluğuna, ses netliğine ve platformun yayın koşullarına bağlıdır.

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Immersive Translate resmî ana sayfası" width="640"><br><sub>Immersive Translate ana sayfası ve tarayıcı uzantısı indirme portalı</sub></p>

<a id="mate-translate"></a>

### Mate Translate
[Mate Translate](https://matetranslate.com/en); macOS, iOS ve yaygın masaüstü tarayıcılar için özel olarak tasarlanmıştır. Web'de gezinirken herhangi bir sözcüğe çift tıklamak anında bir açılır pencere tanımı gösterir, metin seçmek hızlı bağlamsal çeviriler getirir, tam sayfa çevirisi orijinal ve çevrilmiş görünümler arasında geçiş yapar ve kalıcı bir Mac menü çubuğu aracı sağlanır.

Dil öğrenenler için Mate, kullanıcıların web sayfalarındaki veya Netflix altyazılarındaki sözcüklere tıklayarak bunları özel bir Konuşma Kılavuzuna (Phrasebook) kaydetmelerine olanak tanır; bu kılavuz özel kategorizasyonu ve harici inceleme için CSV dışa aktarımını destekler. Chrome gibi masaüstü tarayıcılarda uzantısı, kullanıcıların çevirileri doğrudan tetiklemek için yerleşik PDF görüntüleyicisi içinde metin seçmesine de olanak tanır.

<p align="center"><img src="assets/mate-page@2x.webp" alt="Mate Translate resmî ana sayfası" width="640"><br><sub>Çoklu platform arayüz önizlemelerini gösteren Mate Translate ana sayfası</sub></p>

<a id="reverso"></a>

### Reverso
Doğal sözcük kullanımını doğrulamak isteyen yazarlar ve dil öğrenenler için [Reverso Context](https://context.reverso.net/translation/about); filmlerden, uluslararası yayınlardan ve çok dilli web sitelerinden derlenen iki dilli cümle çiftleri sunar ve bunlara fiil çekim tabloları ile eş anlamlı önerileri eşlik eder. Örnek cümleler halka açık çok dilli derlemlerden kaynaklandığı için kullanıcılar hassas veya resmî taslaklar için bağlam uygunluğunu değerlendirmelidir.

Belge portalı olan [Reverso Documents](https://www.reverso.net/documents/en); PDF, Word, PowerPoint, Excel ve seçili yerelleştirme dosyalarını kabul eder. Ekiplerin tamamlanan dosyayı indirmeden önce düzenlemeler üzerinde iş birliği yapabileceği tarayıcı içi segment segment inceleme arayüzü sağlar.

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Reverso resmî çeviri arayüzü" width="640"><br><sub>Reverso web çeviri arayüzü ve gezinme çubuğu</sub></p>

<a id="yandex-translate"></a>

### Yandex Translate
[Yandex Çeviri web portalı](https://yandex.com/support/translate-desktop/en/) ve mobil uygulamaları; metin, görsel, web sitesi ve belgeleri işler. Android istemcisi, desteklenen diller için fonetik transkripsiyonları, tanımları, eş anlamlıları ve morfolojik çekimleri gösteren ayrıntılı bir sözlük içerir.

Mobilde Android uygulaması önceden yüklenmiş bir İngilizce-Rusça [çevrimdışı sözlük](https://yandex.ru/support/translate-app-android/en/offline-mobile) ile gelirken, çevrimdışı yazılı metin çevirisi için ek dil paketleri indirilebilir. Masaüstü arayüzü standart Office ve PDF yüklemelerini barındırır. Bağımsız bir hizmet olarak Yandex Çeviri ile özel otomatik video seslendirme özelliklerini barındıran Yandex Browser arasındaki ayrıma dikkat edilmelidir.

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Yandex Çeviri resmî web arayüzü" width="640"><br><sub>Yandex Çeviri giriş arayüzü ve yan gezinme paneli</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>

## 3. Karmaşık Belge Düzenleri ve Kurumsal İş Akışları: Formatları ve Varlıkları Koruma

Sunum slaytları, tedarikçi sözleşmeleri veya teknik kılavuzlarla çalışırken bozulan sayfa düzenleri ciddi düzeyde manuel düzeltme gerektirir. Bu araçlar; düzenin korunmasına, terminoloji kontrolüne ve varlıkların yeniden kullanımına öncelik verir.

<a id="deepl"></a>

### DeepL
[DeepL Translator](https://www.deepl.com/en/features), metin ve belge iş akışları için ayrıntılı yapılandırma seçenekleri sunar. Kullanıcılar, şirkete özel veya teknik çevirileri zorunlu kılmak için [Sözlükler (Glossaries)](https://www.deepl.com/en/features/glossary) oluşturabilir ve desteklenen dillerde resmî ve samimi ton kayıtları arasında geçiş yapabilir.

[Belge çeviri hizmeti](https://www.deepl.com/en/features/document-translation); Word, PDF, PPT, Excel, HTML ve SRT dosyalarını kabul eder (format erişimi hesap türüne göre değişir). Ürün ekosistemi ayrıca metin parlatma için DeepL Write'ı, Teams ve Zoom'da gerçek zamanlı altyazılar için [Çevrim İçi Toplantılar İçin DeepL Voice](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings) özelliğini (Voice lisansı ve oturum sahibi izinleri gerektirir) ve yapay zekâ ajanları için resmî bir Model Context Protocol (MCP) kılavuzunu içerir.

<p align="center"><img src="assets/deepl-page@2x.webp" alt="DeepL resmî web çeviri çalışma alanı" width="640"><br><sub>DeepL web çevirici arayüzü</sub></p>

<a id="otranslator"></a>

### O.Translator
[O.Translator](https://otranslator.com/en/product-info), sayfa düzenini koruyan belge çevirisine odaklanır. PDF, Word, PPT ve Excel'e ek olarak; taranmış sayfalar için yerleşik OCR ile birlikte EPUB e-kitapları, InDesign (IDML), Illustrator (AI), OpenDocument, altyazı dosyaları (SRT/ASS) ve çizgi roman arşivleri (CBZ/CBR) gibi yayıncılık ve yerelleştirme formatlarını destekler. Düzen doğruluğu, yazı tipi gömülmesine ve hedef metnin genişlemesine bağlıdır.

Tüm bir dosyayı çevirmeden önce O.Translator, kullanıcıların kısmi bir düzen önizlemesini incelemesine olanak tanır. XLSX veya TBX aracılığıyla terimler sözlüğü içe aktarmayı destekler ve bir [geliştirici API'si](https://www.otranslator.com/en/developer/v1) sunar. Medya seçeneği, gerçek zamanlı tarayıcı yayını çevirisinden ziyade yüklenen ses ve video dosyalarını altyazı dosyalarına dönüştürmek için tasarlanmıştır.

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="O.Translator resmî ürün ana sayfası" width="640"><br><sub>O.Translator ana sayfası ve belge yükleme bölümü</sub></p>

<a id="simplifyai"></a>

### SimplifyAI
SimplifyAI iki ayrı web sitesi işletir: yapay zekâ odaklı bir [Karmaşık Belge Çalışma Alanı](https://simplifyai.cn/zh/translate) (simplifyai.cn/zh) ve bir [Genel Belge Çeviri portalı](https://translate.simplifyai.cn/) (translate.simplifyai.cn).

Çalışma alanında sistem; Word, PPTX, InDesign, PDF ve EPUB dosyalarında kullanıcı incelemesi için çeviri öncesinde yüksek frekanslı terimleri çıkarabilir. Çalışma alanı ayrıca Word ve InDesign için Yapay Zekâ ile Düzenleme (yerel Word değişiklikleri izleme desteği ile), iki dilli veri dışa aktarma (Excel/XLIFF), yapılandırılmış Markdown/JSON çıkarma ile metin taşması ve yazı tipi düzeni için görsel kontroller sunarak baskı öncesi ve tasarım varlığı yerelleştirmesi için son derece uygun hale gelir. Doğrudan günlük dosya çevirisi için genel çeviri portalı daha yalın ve doğrudan bir akış sunar.

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="SimplifyAI resmî ana sayfası" width="640"><br><sub>SimplifyAI ana sayfası, karmaşık belge çalışma alanını ve modüllerini gösteriyor</sub></p>

<a id="lingvanex"></a>

### Lingvanex
[Lingvanex](https://lingvanex.com/); Windows ve macOS üzerinde masaüstü, mobil ve tarayıcı istemcileri sunar. [Windows masaüstü çevirmeni](https://lingvanex.com/products/windows-translator/), sistem genelinde kısayolları destekler (vurgulanan metin üzerinde Ctrl+C'ye çift basmak gibi) ve dil paketlerini indirdikten sonra çevrimdışı metin ve yerel DOCX/ODT dosya çevirisine izin verir.

Tüketici uygulamalarının ötesinde Lingvanex, çevrimdışı kurumsal kullanım için indirilebilir [Güvenli Çeviri Yazılımı](https://lingvanex.com/products/secure-translation-software/) masaüstü yazılımının yanı sıra özel ağ ortamları için ayrı Şirket İçi (On-premise) Makine Çevirisi çözümleri sunar.

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Lingvanex resmî ana sayfası" width="640"><br><sub>Kurumsal çeviri ve şirket içi çözümleri öne çıkaran Lingvanex ana sayfası</sub></p>

<a id="systran"></a>

### SYSTRAN
SYSTRAN, kurumsal ve kurumsal düzeydeki yerelleştirme gereksinimlerini hedefler. Bulut hizmeti [SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/); özel terim sözlükleri ve çeviri belleğinin (TM) yanı sıra hukuk, finans ve endüstriyel belgeler için önceden yapılandırılmış alan modelleri sunarak Word, PowerPoint, Excel ve PDF dosyaları için anında kullanıma hazırdır.

Veri egemenliği gereksinimleri olan kuruluşlar için SYSTRAN; kurumsal güvenlik duvarlarının arkasında şirket içi dağıtım için [Translate Server](https://www.systransoft.com/translation-products/translate-server/), özel Özel Bulut ortamları ve belge iş akışları için toplu [API'ler](https://www.systransoft.com/translation-products/translate-api/) sağlar.

<p align="center"><img src="assets/systran-page@2x.webp" alt="SYSTRAN Translate Pro resmî ürün sayfası" width="640"><br><sub>SYSTRAN Translate Pro resmî ürün genel bakış arayüzü</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>

## 4. Akademik Yazım, Metin İyileştirme ve İnsan Denetimli İş Birliği: Çıktıyı Kusursuzlaştırma

Çeviri, genellikle daha geniş bir yazım veya araştırma iş akışının ilk aşamasıdır. Sözlük tanımlarını kontrol etmek, ifadeleri iyileştirmek ve etkileşimli insan-makine düzenlemesi yapmak, resmî akademik standartların sağlanmasına yardımcı olur.

<a id="youdao-translate-netease-youdao"></a>

### Youdao Translate (NetEase Youdao)
NetEase Youdao'nun sözlük ekosistemiyle bağlantı kuran [Youdao Translate](https://fanyi.youdao.com/); sözcük arama, çeviri ve yazma yardımını birbirine bağlar. Web portalı, standart metin ve dosya çevirisine ek olarak "arXiv Makale Çevirisi" ve akademik metin parlatma için özel girişler sunar.

Kullanıcılar araştırma alıntılarını çevirdikten sonra dilbilgisi denetimleri yapabilir, eş anlamlı seçimlerini değerlendirebilir veya akademik tonu ayarlayabilir; bu da öğrencilerin ve araştırmacıların yabancı literatürü incelemesine ve taslaklar hazırlamasına yardımcı olur. Makale parlatma ve medya modüllerinin format ve dil kapsamları genel sözlük aramasından farklıdır.

<p align="center"><img src="assets/youdao-page@2x.webp" alt="NetEase Youdao Translate resmî web çalışma alanı" width="640"><br><sub>NetEase Youdao Translate web arayüzü ve özellik gezinimi</sub></p>

<a id="baidu-translate"></a>

### Baidu Translate
[Baidu Translate](https://fanyi.baidu.com/), Çince konuşan kullanıcılar için geniş istemci kapsamı sağlar. Masaüstü yazılımı yerel masaüstü uygulamalarında kompakt bir kayan pencere ve kısayolla metin seçimi sunarken, mobil uygulaması fotoğraf çevirisini, sözlü pratiği ve sözlük referanslarını birleştirir.

Buna ek olarak Baidu, bağımsız bir [Baidu Video Çeviri portalına](https://fanyi-video.baidu.com/) ev sahipliği yapar. Kullanıcılar, hizalanmış iki dilli altyazı parçaları oluşturmak, bunları çevrim içi bir düzenleyicide inceleyip düzenlemek ve kesinleşen altyazı dosyalarını dışa aktarmak için medya dosyaları yükler. Bu, canlı web oynatımı için otomatik bir tercümandan ziyade yükleme tabanlı bir yapım sonrası (post-prodüksiyon) aracıdır.

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Baidu Translate resmî web sitesi sayfası" width="640"><br><sub>Baidu Translate resmî web arayüzü</sub></p>

<a id="transmart-tencent-interactive-translation"></a>

### TranSmart (Tencent Interactive Translation)
Tencent AI Lab tarafından geliştirilen [TranSmart](https://transmart.qq.com/zh-CN/intro), etkileşimli insan-makine iş birliği etrafında tasarlanmıştır. Kopyalamak için statik bir çıktı üretmek yerine TranSmart, onaylanan iki dilli çiftleri aktif çeviri belleğine entegre ederek gerçek zamanlı olarak sözcük ve cümle düzeyinde tahmine dayalı tamamlamalar önerir.

Çevirmenler ayarlamalar yapmak için imleçlerini çevrilen metinde herhangi bir yere yerleştirebilir ve bu da sistemin sonraki önerileri dinamik olarak yenilemesini sağlar. Bu, Tencent'in bağımsız tüketici sözlüğü mobil uygulamalarından odak olarak farklı bir işbirlikçi düzenleyici olarak çalışarak terminoloji kararlarını ve cümle akışını kullanıcının kontrolünde tutar.

<p align="center"><img src="assets/transmart-page@2x.webp" alt="Tencent TranSmart resmî web sayfası" width="640"><br><sub>Tencent TranSmart resmî web arayüzü</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>

### LingoCloud (Caiyun Xiaoyi)
[LingoCloud](https://www.caiyunapp.com/?lang=zh); Çince, İngilizce ve Japonca iş akışlarında yaygın olarak kullanılmaktadır. Tarayıcı uzantısı, paylaşılan herkese açık ve kişisel terim sözlüğü desteğiyle sayfa içi iki dilli web okuması sunar. [Belge çeviri hizmeti](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html) (mobil uygulama kılavuzlarına atıfta bulunarak); PDF, Word, PPT, Excel, EPUB, TXT ve SRT gibi formatları kabul eder ve kaynak dosyaya bağlı olarak indirilen çıktıları öncelikle PDF veya Word formatında sunar.

Masaüstü yazılımı ayrıca canlı çift dilli altyazılar oluşturmak için mikrofon sesini yakalayabilen veya çalışan uygulamalardan (Windows'ta Zoom, Teams veya Chrome gibi) sistem ses çıkışını yakalayabilen [LingoCloud Sözlü Çeviri](https://www.caiyunapp.com/interpretation/) özelliğine sahiptir. Masaüstü sözlü çeviri, işletim sistemi ses yakalama sınırlarına tabidir: Windows'ta sistem sesi yakalama desteklenen konferans ve medya uygulamalarında çalışır; macOS'te ise macOS sistem güncellemeleri nedeniyle dahili sistem sesi kayıt yolları şu anda desteklenmemekte olup mikrofon yakalamayı tek işlevsel yol olarak bırakmaktadır.

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="LingoCloud resmî web sitesi sayfası" width="640"><br><sub>LingoCloud resmî web arayüzü</sub></p>

<a id="quillbot-translate"></a>

### QuillBot Translate
[QuillBot Translate](https://quillbot.com/translate), QuillBot'un yazma ve düzenleme ekosistemi içinde çalışır. Metin çevirirken arayüz resmîlik seçenekleri sunar ve desteklenen dillerde tanımları ve eş anlamlıları görüntüler.

Çevrilen metin, cümle akışını iyileştirmek için Paraphraser (Yeniden İfade Edici) ve Dilbilgisi Denetleyicisine sorunsuzca kopyalanabilir. Platform ayrıca tekil PDF belgelerini yüklemek ve incelemek için özel bir [Translate PDF sayfasına](https://quillbot.com/translate-pdf) sahiptir. Desteklenen diller çeviri, dilbilgisi ve yeniden ifade etme araçları arasında farklılık gösterir.

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="QuillBot resmî Chrome Web Mağazası uzantı sayfası" width="640"><br><sub>QuillBot tarayıcı uzantısı için resmî Chrome Web Mağazası ürün sayfası</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>

## 5. Açık Kaynak Ekosistemi: Yerel Motorlar, API'ler, Masaüstü İstemcileri ve Bilimsel PDF İş Akışları

Geliştiriciler, gizliliğe önem veren ekipler ve akademik araştırmacılar genellikle incelenebilir koda, yerel çevrimdışı yürütmeye veya özel otomasyon işlem hatlarına ihtiyaç duyar. Açık kaynaklı çeviri ekosistemi birkaç farklı mimari katmanı kapsar:

- **Bilimsel PDF düzen araçları**: Çok sütunlu düzenleri, formülleri ve şekilleri korurken karmaşık akademik makaleleri çevirir.
- **Kendi sunucunda barındırılabilir çeviri hizmetleri**: Yerel ağ dağıtımı için HTTP REST API uç noktaları ve web arayüzleri sunar.
- **Gömülü çevrimdışı çeviri motorları**: Harici ağ bağımlılıkları olmadan Python kütüphaneleri aracılığıyla sinirsel makine çevirisini yerel olarak çalıştırır.
- **Masaüstü ve uçbirim arayüzleri**: Çoklu motor aramalarını, pano izlemeyi, OCR'ı ve kabuk (shell) boru hatlarını entegre eder.

> [!IMPORTANT]
> Açık kaynaklı kodu yerel olarak çalıştırmak, çevirilerin otomatik olarak çevrimdışı veya gizli olduğu anlamına gelmez. Bir araç yerel olarak çalışırken varsayılan olarak bulut API'lerini sorgulayabilir. Gerçek anlamda çevrimdışı çeviri, hem yerel model varlıklarını hem de yerel bir çeviri motorunu gerektirir.

<a id="51-scientific--academic-pdf-pipelines"></a>

### 5.1 Bilimsel ve Akademik PDF İş Akışları

<a id="pdfmathtranslate-pdf2zh"></a>

#### PDFMathTranslate (pdf2zh)
[PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) (GNU AGPL v3), bilimsel ve akademik PDF belgeleri için uyarlanmış açık kaynaklı bir araçtır. Çok sütunlu makale yapılarını, matematiksel gösterimleri, gömülü grafikleri, içindekiler tablolarını ve ek açıklamaları korur.

- **Çift ve Tek Çıktılar**: Hem yalnızca çevrilmiş (`-mono.pdf`) hem de iki dilli karşılaştırma (`-dual.pdf`) belgeleri oluşturur.
- **Arayüzler ve Entegrasyonlar**: Komut satırı araçları (CLI), etkileşimli bir WebUI, Docker konteyner dağıtımı ve Model Context Protocol (MCP) desteği sağlar. Bağlantılı bir Zotero entegrasyon eklentisi kardeş proje olarak mevcuttur.
- **Çeviri Arka Uçları**: Google Çeviri (belgelenmiş varsayılan), DeepL, OpenAI uyumlu API'ler ve yerel Ollama örneklerini destekleyen takılabilir bir mimari kullanır. Bulut arka uçları yapılandırılmışsa Docker veya WebUI aracılığıyla yerel dağıtım çevrimdışı çalışma anlamına gelmez.
- **OCR Desteği**: Beyaz arka plan üzerine siyah metin içeren taranmış sayfalar için deneysel OCR içerir (ilk kullanımda yerel olarak yeniden kullanılabilen dil modeli varlıklarını indirir).

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="PDFMathTranslate resmî GitHub depo sayfası" width="640"><br><sub>Akademik PDF düzen çevirisini ve CLI/WebUI iş akışlarını gösteren resmî PDFMathTranslate depo genel bakışı</sub></p>

<a id="babeldoc"></a>

#### BabelDOC
[BabelDOC](https://github.com/funstory-ai/BabelDOC) (GNU AGPL v3); temel olarak bir hata ayıklama CLI'ı eşliğinde Python uygulamalarına gömülmek üzere tasarlanmış, belge düzeyinde bilimsel makale çevirisi ve iki dilli karşılaştırma kütüphanesidir.

- **Düzen ve Çıktı Kontrolü**: Tek veya çift çıktıları, aynı sayfada yan yana veya dönüşümlü orijinal/çevrilmiş sayfaları, seçici sayfa çevirisini, büyük PDF'leri bölme ve birleştirmeyi, özel terimler sözlüğü CSV girişini ve formül korumayı destekler. Tablo metni çevirisi açıkça deneysel olarak belgelenmiştir.
- **Arka Uç Mimarisi**: OpenAI uyumlu uç noktalar veya yerel bir Ollama örneği aracılığıyla yapılandırılmış bir çeviri arka ucu gerektirir. Bir PDF işleme ve düzen motoru olarak kendi içinde evrensel bir çeviri motoru barındırmaz.
- **Çevrimdışı Varlıklar ve Sınırlar**: Belge düzen modelleri ve yazı tipleri için ısınma (warmup) rutinleri ve çevrimdışı varlık oluşturma/geri yükleme sağlar. Tamamen çevrimdışı yürütme, hem önbelleğe alınmış varlıkları hem de yerel olarak çalışan bir çeviri arka ucunu (yerel Ollama gibi) gerektirir. Belgeler, beyaz arka planlar üzerindeki siyah metin için deneysel bir OCR geçici çözümüyle birlikte, öncelikli doğrulamanın İngilizce-Çince iş akışlarında yapıldığını vurgular.

<p align="center"><img src="assets/babeldoc-page.webp" alt="BabelDOC resmî GitHub depo sayfası" width="640"><br><sub>Belge düzeyinde bilimsel PDF çeviri kütüphanesi yeteneklerini gösteren resmî BabelDOC depo genel bakışı</sub></p>

<a id="52-self-hostable-engines--apis"></a>

### 5.2 Kendi Sunucunda Barındırılabilir Motorlar ve API'ler

<a id="libretranslate"></a>

#### LibreTranslate
[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) (GNU AGPL v3), Argos Translate motoru üzerine inşa edilmiş, dahili web arayüzüne sahip, ücretsiz ve açık kaynaklı, kendi sunucunuzda barındırabileceğiniz bir makine çevirisi API hizmetidir.

- **API ve Web Hizmeti**: Metin çevirisi, kaynak dil algılama ve HTML/biçimlendirme işleme için REST API uç noktaları sunar. Ticari çeviri API'lerine bir proxy olmaktan ziyade bağımsız bir hizmet katmanı olarak işlev görür.
- **Yerel Dağıtım ve Gizlilik**: Bağımlılıklar ve dil modelleri kurulduktan sonra, harici üçüncü taraflara veri göndermeden tamamen yerel donanımda çalışabilir. Herkese açık barındırılan bir örneği kullanmak ağa bağlı kalmaya devam eder. API anahtarı erişim denetimi, sunucu sahibinin gereksinimlerine göre etkinleştirilebilir veya devre dışı bırakılabilir.
- **Dil Kapsamı ve Dosya Formatları**: Kullanılabilir dil çiftleri kurulu dil modellerine bağlıdır. argos-translate-files gibi kardeş projeler aracılığıyla dosya çevirisi TXT, ODT, ODP, DOCX, PPTX, EPUB, HTML, SRT ve PDF gibi formatları destekler.

<p align="center"><img src="assets/libretranslate-page.webp" alt="LibreTranslate resmî GitHub depo sayfası" width="640"><br><sub>Kendi sunucunda barındırılan çeviri API'sini ve web arayüzü özelliklerini gösteren resmî LibreTranslate depo genel bakışı</sub></p>

<a id="argos-translate"></a>

#### Argos Translate
[Argos Translate](https://github.com/argosopentech/argos-translate) (MIT Lisansı / README'de belirtilen CC0 seçeneği), ayrıca kurulabilen bir GUI istemcisine sahip açık kaynaklı, çevrimdışı bir Python çeviri kütüphanesi ve komut satırı aracıdır.

- **Modüler Model Paketleri**: `.argosmodel` uzantısını kullanarak dil modeli paketlerini indirir ve yönetir. Doğrudan bir dil çifti mevcut olmadığında, kurulu ara çiftler üzerinden çeviri yapabilir (örneğin İngilizce üzerinden köprü kurarak çevirme).
- **Ekosistem Motoru**: LibreTranslate için temel makine çevirisi motoru olarak hizmet eder. Kardeş projeler yeteneklerini HTML çevirisine (`translate-html`) ve dosya işlemeye (`argos-translate-files`) genişletir.
- **Çevrimdışı Çalışma**: Modeller yüklendikten sonra tamamen çevrimdışı çalışır; paket dizinlerini ve ilk modelleri indirmek internet bağlantısı gerektirir.

<p align="center"><img src="assets/argos-translate-page.webp" alt="Argos Translate resmî GitHub depo sayfası" width="640"><br><sub>Modüler çevrimdışı çeviri motorunu ve paket sistemini ayrıntılandıran resmî Argos Translate depo genel bakışı</sub></p>

<a id="53-desktop--terminal-frontends"></a>

### 5.3 Masaüstü ve Uçbirim Arayüzleri

<a id="pot-pot-desktop"></a>

#### Pot (pot-desktop)
[Pot](https://github.com/pot-app/pot-desktop) (GNU GPL v3); kısayol tuşlarıyla seçim çevirisi, metin girişi, pano izleme, ekran görüntüsü OCR ve ekran görüntüsü çevirisini destekleyen, Windows, macOS ve Linux için platformlar arası bir masaüstü çeviri aracıdır. Resmî GitHub deposu 7 Eylül 2026 tarihinde sahibi tarafından arşivlendi ve salt okunur durumdadır.

- **Çoklu Hizmet Birleştirme**: Sonuçları yan yana karşılaştırmak için birden fazla çeviri ve sözlük hizmetini aynı anda sorgulamaya olanak tanır. Metin okuma (TTS), Anki ve Eudic'e kelime dağarcığı aktarımı ve eklenti genişletmelerini destekler.
- **Takılabilir Arka Uçlar ve OCR**: Bulut çeviri sağlayıcılarını, OpenAI uyumlu API'leri ve yerel Ollama uç noktalarını bir araya getirir. OCR seçenekleri arasında platforma özgü yerel seçenekler (Windows sistem OCR, Apple Vision, Linux Tesseract), Tesseract.js veya yerel eklentiler yer alır.
- **Çevrimdışı Yürütme Yolları**: Seçim ve yazılı metin çevirisi yalnızca yapılandırılmış bir yerel çeviri arka ucu gerektirir (yerel bir Ollama örneği gibi); ekran görüntüsü çevirisi ek olarak çevrimdışı bir OCR motoru gerektirir (platforma özgü yerel OCR veya Tesseract gibi). Bulut hizmetleri istekleri ağ üzerinden yönlendirir.

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Pot masaüstü çeviri resmî GitHub depo sayfası" width="640"><br><sub>Çoklu arayüz çevirisini, OCR'ı ve pano iş akışlarını vurgulayan resmî Pot masaüstü istemcisi depo genel bakışı</sub></p>

<a id="translate-shell"></a>

#### Translate Shell
[Translate Shell](https://github.com/soimort/translate-shell) (The Unlicense / Kamu Malı), Unix benzeri uçbirim ortamları için çok yönlü bir komut satırı çeviri aracıdır (yürütülebilir dosya: `trans`).

- **CLI Araması ve Sözlük**: Doğrudan kabuk içinde kelime tanımlarını, ifade çevirisini, kısa sözlük modunu, etkileşimli REPL oturumlarını ve dil tanımlamayı destekler.
- **Unix Boru Hatları (Pipelines)**: Standart girdi/çıktı (`stdin` / `stdout`) ile entegre olur, düz metin dosyalarını doğrudan işler ve harici bir ses oynatıcısı yüklendiğinde konuşma sentezini destekler.
- **Motor Katmanı**: Genel çeviri hizmetlerine bağlanan hafif bir istemci ön ucu olarak çalışır (varsayılan olarak Google Çeviri'nin yanı sıra Bing Translator, Yandex.Translate ve Apertium).
- **Sınırlar**: Yerel sinirsel çeviri modellerini bünyesinde barındırmaz; standart çalışma, seçilen motor hizmetlerine harici ağ bağlantısına bağlıdır. Dosya çevirisi, biçimlendirilmiş belgeler için değil, düz metin akışları için tasarlanmıştır.

<p align="center"><img src="assets/translate-shell-page.webp" alt="Translate Shell resmî GitHub depo sayfası" width="640"><br><sub>Uçbirim komut satırı çevirisini ve boru hattı entegrasyonunu gösteren resmî Translate Shell depo genel bakışı</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>

## 6. Uçtan Uca Entegre İş Akışları: [Equalang](https://equalang.com/?utm_source=github)

Bu araçları incelemek, her bir hizmetin belirli görevler için belirgin yetenekler geliştirdiğini göstermektedir. Ancak günlük çalışmalarda gereksinimler sıklıkla birbiriyle kesişir:

Tarayıcınızda çevrim içi bir tanıtım belgesi (white paper) okuyabilir, tablolara ve şemalara sahip ekteki bir PDF'i indirebilir, altyazısız bir video dersi izleyebilir ve ardından uluslararası iş ortaklarıyla doğrudan koordinasyon kurarken Word'de bir yönetici özeti hazırlayabilirsiniz. Yalıtılmış yazılım araçları ve dosya dönüştürücüler arasında geçiş yapmak iş akışını böler.

**[Equalang](https://equalang.com/?utm_source=github)**'i, bu görevleri kesintisiz, yan yana bir çeviri iş akışında birleştirmek; belgeler, web sayfaları, videolar ve canlı iletişim genelinde koordineli çeviri desteği sunmak için tasarladık.

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Equalang resmî İngilizce ana sayfası" width="640"><br><sub><a href="https://equalang.com/?utm_source=github">Equalang</a> resmî İngilizce web sitesi ana sayfası</sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>

### 1. Sayfa Düzenini Koruyarak Tam Belge Çevirisi
Tüm belgeleri çevirirken [Equalang](https://equalang.com/?utm_source=github); araştırma literatürü, sunumlar ve günlük ofis dosyaları genelinde uyarlanmış iş akışları sağlayarak yapısal korumaya ve çeviri sonrası kullanılabilirliğe odaklanır:

- **PDF Belgeleri ve Okuma**: [Equalang](https://equalang.com/?utm_source=github) çok sütunlu düzenleri, üstbilgileri, altbilgileri ve resim yazılarını korur; sayfa sonlarında bölünen cümleleri çevirmeden önce yeniden birleştirirken tablo yapılarını, satır içi formülleri ve belge içi bağlantıları muhafaza eder. [Akademik PDF okuma rehberimizde](https://equalang.com/blog/translate-and-read-pdf-documents?utm_source=github) açıklandığı üzere okuyucular, çevrilmiş dosyayı orijinalin yanında yan yana bir düzende görüntüleyebilir; orijinal sayfadaki belirli terminolojiye ve verilere çapraz referans vermeden önce temel argümanları öncelikle kendi ana dillerinde kavrayabilirler.

- **PowerPoint Sunumları**: [Slayt sunumu biçimlendirme kılavuzumuzda](https://equalang.com/blog/translate-powerpoint-keep-formatting?utm_source=github) belirtildiği gibi, çevrilen PPTX dosyaları yerel tabloları statik görüntülere dönüştürmek yerine düzenlenebilir olarak korur. Tek bir cümle içindeki kalınlaştırma, italik ve yazı tipi renkleri gibi sözcük düzeyindeki stiller, karşılık gelen çevrilmiş ifadelere doğru bir şekilde eşlenir. Anahtar terimler ve başlıklar slaytlar arasında tutarlı kalır ve metin kutuları, çeviriler genişlediğinde metin taşmasını veya grafiklerin üzerinin kapanmasını önlemek için yazı tipi boyutlarını otomatik olarak küçültür.

- **Word ve Excel Ofis Dosyaları**: Doğrulanmış [Word çeviri testimizde](https://equalang.com/blog/translate-word-document-keep-formatting?utm_source=github), çevrilen DOCX dosyaları başlıkları, madde işaretli listeleri, fiyat tablolarını ve kalın biçimlendirmeyi koruyarak Microsoft Word'de doğrudan düzenlemeye olanak sağladı. [Excel fiyat listesi doğrulamamızda](https://equalang.com/blog/translate-excel-file?utm_source=github), hücrelerdeki yinelenen metin dizeleri yalnızca bir kez çevrilirken formüller ve sayılar el değmeden kaldı.

- **E-Kitaplar ve Formatlı Medya**: EPUB e-kitapları içindekiler tablosu gezinimini ve dahili bağlantıları korur. 180 dakikaya kadar kaydedilmiş ses ve video dosyaları için çeviri ve deşifre görevleri (genel bir web belgesi yükleme portalı yerine) Geliştirici API'miz ve Agent Skill/MCP entegrasyonumuz aracılığıyla gönderilir; zaman damgalı iki dilli SRT/VTT altyazı dosyaları veya kaynak dökümleri çıktılanır.

<a id="2-in-browser-reading--subtitle-generation"></a>

### 2. Tarayıcı İçi Okuma ve Altyazı Oluşturma
Hafif [tarayıcı uzantımız](https://equalang.com/extension?utm_source=github) aracılığıyla (Chrome, Edge ve Firefox için kurulum kılavuzları ile Safari 18.4+ için geçici bir Mac Safari modu dahil), çeviri doğrudan günlük okumanıza entegre olur:

- **Paragraf Altı İki Dilli Web Okuma**: Siz sayfayı kaydırdıkça çevrilmiş paragraflar doğrudan orijinal metnin hemen altında görünür. İsteğe bağlı kelime aramaları için ayarlardan kayan bir simge açılıp kapatılabilir. Yerel PDF'leri görüntülerken kullanıcılar, kelimeleri seçip aratabilmek için uzantı yönetiminde "Dosya URL'lerine erişime izin ver" seçeneğini etkinleştirebilir.

- **İki Dilli Video Altyazıları**: [İki dilli video izleme kılavuzumuzda](https://equalang.com/blog/watch-videos-with-bilingual-subtitles?utm_source=github) incelendiği üzere YouTube, Netflix, TikTok ve Bilibili ile uyumludur. Uzantı, mevcut altyazıları çevirmenin ötesinde, ses akışlarını yakalayarak **altyazısız videolar** için gerçek zamanlı iki dilli altyazılar oluşturabilir (tarayıcı ortamına ve ortam şifreleme sınırlarına tabidir, YouTube canlı yayınlarında ve resmî fragmanlarda doğrulanmıştır) ve aynı zamanda YouTube'daki canlı sohbet yorumlarını eş zamanlı olarak çevirir.

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>

### 3. Kurulum Gerektirmeyen Sözlü İletişim ve Yüz Yüze Görüşme
Konuşma ortaklarının özel mobil uygulamalar yüklemesini zorunlu kılmak, özellikle seyahat ederken sürtünme yaratır. İnternete bağlıyken [Equalang](https://equalang.com/?utm_source=github), [uluslararası iletişim kılavuzumuzda](https://equalang.com/blog/talk-with-overseas-partners?utm_source=github) özetlendiği gibi, doğrudan standart tarayıcılar içinde hareket halindeyken fotoğraf çevirisi ve sözlü tercüme sunar (yalnızca ilk kullanımda bir kerelik oturum açma ve cihaz kamera/mikrofon izni gerektirir):

- **Mobil Fotoğraf Çevirisi**: Seyahat ederken alışılmadık restoran menüleri, tabelalar veya kamu duyuruları ile karşılaşıldığında, kullanıcılar mobil tarayıcılarında fotoğraf çekebilir. [Seyahat fotoğraf çevirisi kılavuzumuzda](https://equalang.com/blog/photo-translation-for-travel?utm_source=github) gösterildiği gibi çeviriler doğrudan fotoğraf düzeninin üzerine bindirilerek içecek sipariş etmeyi veya bildirimleri orijinal görsele göre incelemeyi kolaylaştırır.

- **Yüz Yüze Modu**: Otelde bagaj bırakma, yol sorma veya resepsiyon etkileşimleri gibi yüz yüze durumlar için tasarlanmıştır. [Seyahat yüz yüze iletişim kılavuzumuzda](https://equalang.com/blog/talk-face-to-face-while-traveling?utm_source=github) gösterildiği gibi iki konuşmacı, ters çevrilmiş bölünmüş ekran veya sürekli iki yönlü transkripsiyon ve döküm dışa aktarımı içeren yan yana görünümü kullanarak tek bir telefonu veya tableti aralarına düz bir şekilde koyabilir.

- **Canlı Dinleme**: Cihazın fiziksel mikrofonu aracılığıyla yakalanan gerçek zamanlı iki dilli altyazıları almak için yüz yüze bir sunum veya ders sırasında web portalını açın; işlem tamamlandığında isteğe bağlı metin okuma sesi ve döküm dışa aktarımı sağlanır (tarayıcı uzantısının akış medyası ses yakalamasından farklıdır).

- **Çevrilmiş Aramalar**: Oturum sahipleri güvenli bir arama bağlantısı oluşturmak ve bunu herhangi bir mesajlaşma uygulaması üzerinden paylaşmak için web portalında oturum açar. **Konuklar bir hesap oluşturmadan veya herhangi bir yazılım yüklemeden doğrudan tarayıcıları üzerinden katılır**—yalnızca bir görünen ad girerler ve oturum sahibi aramayı başlatmak için onları kabul eder. Her iki taraf da kendi ana dilini konuşur, çevrilmiş sesi duyar ve gerçek zamanlı metni görüntüler.

<a id="4-integration-for-ai-agents-and-developers"></a>

### 4. Yapay Zekâ Ajanları ve Geliştiriciler İçin Entegrasyon
Geliştiricilerin ve ekiplerin çeviriyi otomatik iş akışlarına yerleştirmelerine yardımcı olmak için:

- **Geliştirici API'si**: [Dosya çevirisi API entegrasyonu kılavuzumuzda](https://equalang.com/blog/integrate-file-translation-api?utm_source=github) ayrıntılı olarak açıklandığı üzere, Idempotency-Key yeniden denemelerini ve geri arama (callback) bildirimlerini destekleyen eşzamansız dosya işlerinin yanı sıra metin için anlık uç noktalar sunar.

- **Skill ve MCP Entegrasyonu**: [equalang-skill](https://github.com/equalang/equalang-skill) aracılığıyla açık kaynaklı Agent Skill'leri ve [@equalang/mcp](https://github.com/equalang/equalang-mcp) aracılığıyla resmî Model Context Protocol desteğini sürdürüyoruz. Claude Code, Codex veya WorkBuddy gibi ortamlarda, tek bir kurulum talimatı (prompt) vermek ve API anahtarınızı yapılandırmak, [yapay zekâ asistanı dosya çevirisi kılavuzumuzu](https://equalang.com/blog/translate-files-with-ai-assistants?utm_source=github) izleyerek yapay zekâ asistanınızı doğrudan iş akışınız içinde belge çevirisi ve medya dökümünü işleyecek şekilde donatır.

---

<a id="7-task-based-decision-guide"></a>

## 7. Görev Odaklı Karar Rehberi

Mevcut göreviniz için doğru aracı seçmenize yardımcı olmak amacıyla bu görev matrisine başvurabilirsiniz:

| Birincil Görev | Temel Gereksinim | Denenmesi Önerilen Araçlar | Önemli Değerlendirmeler |
| :--- | :--- | :--- | :--- |
| **Seyahat ve Sözlü Diyalog** | Fotoğraf OCR'ı, iki yönlü diyalog, çevrimdışı paketler ve bağlantılı seyahat araçları | Google Translate, Apple Translate, Papago, [Equalang](https://equalang.com/?utm_source=github) | Zayıf sinyal alanları için Google, Apple veya Papago'da (donanım gereksinimlerine dikkat ederek) çevrimdışı dil paketlerini indirin; internete bağlıyken [Equalang](https://equalang.com/?utm_source=github), uygulama yüklemeden tarayıcı tabanlı fotoğraf çevirisi ve yüz yüze diyalog sağlar. |
| **Çok Cihazlı Çalıştaylar** | Bire çok sunumlar, çok cihazlı katılım | Microsoft Translator | Oturum sahibi mobil uygulama aracılığıyla Sunucu modunu çalıştırır; katılımcılar yazılım yüklemeden standart tarayıcı üzerinden katılır. |
| **Derinlemesine Web Okuma** | Sayfadan ayrılmadan paragraf altı okuma | Immersive Translate, [Equalang](https://equalang.com/?utm_source=github), Mate Translate | İki dilli paragraflar için Immersive Translate veya [Equalang](https://equalang.com/?utm_source=github) kullanın; Mac'te tam sayfa görünümleri arasında geçiş yapmak veya kelimeleri Konuşma Kılavuzlarına kaydetmek için Mate Translate kullanın. |
| **Altyazısız Video ve Canlı Yayınlar** | Gerçek zamanlı altyazı oluşturma, akış uyumluluğu | [Equalang](https://equalang.com/?utm_source=github), Immersive Translate | Her iki araç da desteklenen platformlarda (YouTube gibi) ham sesten altyazı oluşturabilir; canlı sohbet ve yayın işleme için tarayıcı uzantısı iş akışlarını karşılaştırın. |
| **Akademik Makaleler ve Bilimsel PDF'ler** | Formül koruma, sütun yapıları, sayfalar arası metin | PDFMathTranslate, BabelDOC, [Equalang](https://equalang.com/?utm_source=github) | PDFMathTranslate ve BabelDOC, çift PDF çıktısı ve yerel/bulut LLM arka uçları içeren açık kaynaklı işlem hatları sağlar; [Equalang](https://equalang.com/?utm_source=github), tarayıcı tabanlı yan yana okuma ve sayfa düzeni koruması sunar. |
| **Yayıncılık Baskı Öncesi ve Tasarım Formatları** | InDesign, Illustrator, çizgi roman arşivleri, baskı öncesi kalite kontrolü | SimplifyAI, O.Translator | InDesign (IDML) ve tasarım varlığı baskı öncesi için SimplifyAI ve O.Translator kullanın; SimplifyAI, yerel Word değişiklikleri izleme özelliğine sahip Yapay Zekâ ile Düzenleme içerir. |
| **Sunumlar ve Ofis Belgeleri** | Yerel tabloları, stilleri, formülleri ve düzenlenebilirliği koruma | [Equalang](https://equalang.com/?utm_source=github), DeepL | [Equalang](https://equalang.com/?utm_source=github), uyarlanabilir yazı tipi boyutlandırması ve Excel formül koruması ile PPTX yerel tablolarını/stillerini korur; sözlükler içeren kurumsal Word/Office dosyaları için DeepL kullanın. |
| **Akademik Yazım ve İyileştirme** | Dilbilgisi doğruluğu, resmî akademik üslup | Youdao Translate, QuillBot Translate, TranSmart | Youdao ve QuillBot çeviriyi metin iyileştirmeye doğru akıcı hale getirir; TranSmart etkileşimli insan denetimli düzenleme sağlar. |
| **Masaüstü Kısayol Tuşuyla Arama ve Çoklu Motor** | Genel kısayollar, OCR, birden çok motoru karşılaştırma | Pot, Mate Translate | Pot; Windows, Mac ve Linux genelinde eşzamanlı çoklu motor sorgularına ve ekran görüntüsü OCR'ına izin verir; Mate yerel bir Mac menü çubuğu aracı sunar. |
| **Uçbirim Komut Dosyaları ve Kabuk İşlem Hatları** | CLI araması, stdin/stdout işlem hatları, düz metin komut dosyaları | Translate Shell, Argos Translate | Translate Shell, uzak motorlar aracılığıyla hafif CLI çevirisi sağlar; Argos Translate, yerel modellerle çevrimdışı bir Python CLI'ı sunar. |
| **Kendi Sunucunda Barındırılan Özel API ve Çevrimdışı Motorlar** | Hava boşluklu (air-gapped) ağlar, üçüncü taraf veri iletimi olmaması | LibreTranslate, Argos Translate, SYSTRAN, Lingvanex | LibreTranslate, kendi sunucunuzda barındırılan bir HTTP API hizmeti ve WebUI sağlar; Argos Translate, modüler model paketlerine sahip çevrimdışı bir Python kütüphanesi/CLI motoru olarak buna güç verir; SYSTRAN ve Lingvanex kurumsal şirket içi dağıtımlar sunar. |
| **Uçtan Uca Entegre İş Akışları** | Belgeler, yayın altyazıları, web aramaları ve Yapay Zekâ Ajanları | [Equalang](https://equalang.com/?utm_source=github) | Birleşik belge işleme, altyazısız medya altyazıları, uygulama kurulumu gerektirmeyen tarayıcı tabanlı aramalar ve Claude Code veya WorkBuddy ile doğrudan entegrasyon. |

---

<a id="8-directory-principles--verification-criteria"></a>

## 8. Dizin İlkeleri ve Doğrulama Kriterleri

Bu dizinin pratik yararını ve olgusal doğruluğunu korumak için girdiler katı dahil etme ve inceleme kriterlerini takip eder:

1. **Pazarlama İddiaları Yerine Belgelenmiş Özellikler**: Açıklamalar resmî belgelerden, kullanım kılavuzlarından ve doğrulanmış depo kaynak dosyalarından türetilmiştir. Mükemmel sayfa düzeni koruması veya evrensel format desteği iddia etmiyoruz.
2. **Net Mimari Sınırlar**: Çeviri ön uçları, kendi sunucunuzda barındırılabilir hizmet katmanları, çevrimdışı çeviri motorları ve belge düzeni kütüphaneleri arasında ayrım yapıyoruz. Yerel olarak çalışan açık kaynaklı kod, gerçek çevrimdışı yürütmeden açıkça ayrılmıştır.
3. **Görev Odaklı Kapsam**: Araçlar, iş akışları genelindeki pratik uygunluklarına göre gruplandırılmıştır. Öznel seviye listeleri, kalite sıralamaları veya değişken fiyatlandırma rakamları tutmuyoruz.
4. **Şeffaf Sorumlu Kimliği**: Bu katalog, **[Equalang](https://equalang.com/?utm_source=github)** ekibi tarafından derlenmekte ve sürdürülmektedir. [Equalang](https://equalang.com/?utm_source=github), doğrulanabilir özellik sınırları ve şeffaf sistem gereksinimleri ile diğer araçların yanında sunulmaktadır.

**Anahtar Kelimeler**: çeviri araçları, belge çevirisi, iki dilli web okuması, akademik PDF çevirisi, açık kaynaklı çeviri, makine çevirisi API'si, sayfa düzenini koruma, yapay zekâ ajanları.

---

<a id="9-sources"></a>

## 9. Kaynaklar

1. [Google Çeviri Yardım Merkezi](https://support.google.com/translate)
2. [Google Çeviri Masaüstü Belge Çevirisi](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Apple Destek: iPhone İçin Çeviri Uygulaması Kılavuzu](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Apple Destek: Canlı Çeviri ve Özellik Kullanılabilirliği](https://support.apple.com/en-us/123720)
5. [Microsoft Translator Mobil Özellikleri](https://www.microsoft.com/en-us/translator/apps/features/)
6. [Microsoft Translator Çok Cihazlı Konuşma Yardımı](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/)
7. [NAVER Papago Resmî Portalı](https://papago.naver.com/)
8. [iTranslate Klavye ve Çevrimdışı Özellikleri](https://itranslate.com/features/keyboard-translations/index.html)
9. [Reverso Context Kullanım Bilgileri](https://context.reverso.net/translation/about)
10. [Reverso Documents Portalı](https://www.reverso.net/documents/en)
11. [Masaüstü ve Mobil İçin Yandex Çeviri Yardımı](https://yandex.com/support/translate-desktop/en/)
12. [Immersive Translate Belgeleri](https://immersivetranslate.com/)
13. [O.Translator Ürün Bilgileri ve Formatlar](https://otranslator.com/en/product-info)
14. [SimplifyAI Karmaşık Belge Çalışma Alanı](https://simplifyai.cn/zh/translate)
15. [SimplifyAI Genel Belge Çevirisi](https://translate.simplifyai.cn/)
16. [Mate Translate Özellikleri](https://matetranslate.com/en)
17. [Lingvanex Windows Çevirmeni](https://lingvanex.com/products/windows-translator/)
18. [Lingvanex Güvenli Çeviri Yazılımı](https://lingvanex.com/products/secure-translation-software/)
19. [SYSTRAN Translate Pro ve Kurumsal Dağıtımlar](https://www.systransoft.com/translation-products/translate-pro/)
20. [NetEase Youdao Translate](https://fanyi.youdao.com/)
21. [Baidu Translate ve Video Çeviri Portalı](https://fanyi.baidu.com/)
22. [Tencent TranSmart Ürün Tanıtımı](https://transmart.qq.com/zh-CN/intro)
23. [Caiyun Xiaoyi (LingoCloud) Belge Yardımı](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
24. [QuillBot Translate ve PDF Portalı](https://quillbot.com/translate)
25. [Equalang API Belirtimleri ve Belgeleri](https://equalang.com/llms-full.txt?utm_source=github)
26. [PDFMathTranslate Resmî GitHub Deposu](https://github.com/PDFMathTranslate/PDFMathTranslate)
27. [PDFMathTranslate Gelişmiş Seçenekler Belgeleri](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
28. [BabelDOC Resmî GitHub Deposu](https://github.com/funstory-ai/BabelDOC)
29. [LibreTranslate Resmî GitHub Deposu](https://github.com/LibreTranslate/LibreTranslate)
30. [LibreTranslate Belgeleri ve API Kılavuzu](https://docs.libretranslate.com/)
31. [Argos Translate Resmî GitHub Deposu](https://github.com/argosopentech/argos-translate)
32. [Pot Masaüstü Çeviri Resmî GitHub Deposu](https://github.com/pot-app/pot-desktop)
33. [Translate Shell Resmî GitHub Deposu](https://github.com/soimort/translate-shell)
