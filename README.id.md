# Awesome Translation Tools

> Direktori terkurasi alat dan alur kerja penerjemahan untuk perjalanan, membaca web, dokumen berformat, riset akademis, mesin lokal sumber terbuka (open-source), dan pipeline pengembang.

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português (Brasil)](README.pt-BR.md) | [Italiano](README.it.md) | [Русский](README.ru.md) | [العربية](README.ar.md) | [हिन्दी](README.hi.md) | [Bahasa Indonesia](README.id.md) | [Türkçe](README.tr.md)

---

Tugas penerjemahan memiliki kebutuhan mendasar yang berbeda-beda tergantung konteks: menguraikan arti rambu jalan atau buku menu di ponsel, membaca dokumentasi berbahasa asing langsung di peramban, menerjemahkan dokumen presentasi rumit dan kontrak bisnis tanpa merusak tata letak (layout), mempertahankan formula matematika dalam makalah akademis, menjalankan penerjemahan batch secara privat di terminal, hingga mengikuti tayangan video tanpa takarir (subtitle).

Kami adalah tim **Equalang**. Direktori ini menyajikan katalog praktis dan berorientasi tugas dari berbagai produk penerjemahan terkemuka serta proyek sumber terbuka (open-source). Untuk setiap alat, kami merangkum kemampuan yang terdokumentasi, pintu masuk penggunaan, mode penerapan (deployment), dan batasan operasionalnya guna membantu Anda menentukan solusi yang tepat untuk alur kerja Anda.

---

## Daftar Isi

- [1. Perjalanan & Percakapan Lisan Saat Bepergian: Input Multimodal dan Lisan](#1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs)
  - [Google Translate](#google-translate)
  - [Apple Translate](#apple-translate)
  - [Microsoft Translator](#microsoft-translator)
  - [Papago](#papago)
  - [iTranslate](#itranslate)
- [2. Membaca Web Sesuai Konteks & Pembelajaran Bahasa: Membaca Tanpa Berpindah Halaman](#2-in-context-web-reading--language-learning-reading-without-leaving-the-page)
  - [Immersive Translate](#immersive-translate)
  - [Mate Translate](#mate-translate)
  - [Reverso](#reverso)
  - [Yandex Translate](#yandex-translate)
- [3. Tata Letak Dokumen Kompleks & Alur Kerja Perusahaan: Mempertahankan Format dan Aset](#3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets)
  - [DeepL](#deepl)
  - [O.Translator](#otranslator)
  - [SimplifyAI](#simplifyai)
  - [Lingvanex](#lingvanex)
  - [SYSTRAN](#systran)
- [4. Penulisan Akademis, Penyempurnaan & Kolaborasi Human-in-the-Loop: Memoles Hasil Terjemahan](#4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output)
  - [Youdao Translate (NetEase Youdao)](#youdao-translate-netease-youdao)
  - [Baidu Translate](#baidu-translate)
  - [TranSmart (Tencent Interactive Translation)](#transmart-tencent-interactive-translation)
  - [LingoCloud (Caiyun Xiaoyi)](#lingocloud-caiyun-xiaoyi)
  - [QuillBot Translate](#quillbot-translate)
- [5. Ekosistem Sumber Terbuka: Mesin Lokal, API, Klien Desktop & Pipeline PDF Ilmiah](#5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines)
  - [5.1 Pipeline PDF Ilmiah & Akademis](#51-scientific--academic-pdf-pipelines)
    - [PDFMathTranslate (pdf2zh)](#pdfmathtranslate-pdf2zh)
    - [BabelDOC](#babeldoc)
  - [5.2 Mesin & API yang Dapat Dihosting Mandiri (Self-Hostable)](#52-self-hostable-engines--apis)
    - [LibreTranslate](#libretranslate)
    - [Argos Translate](#argos-translate)
  - [5.3 Frontend Desktop & Terminal](#53-desktop--terminal-frontends)
    - [Pot (pot-desktop)](#pot-pot-desktop)
    - [Translate Shell](#translate-shell)
- [6. Alur Kerja Menyeluruh yang Terintegrasi (End-to-End): Equalang](#6-connected-end-to-end-workflows-equalang)
  - [1. Penerjemahan Seluruh File Dokumen dengan Mempertahankan Tata Letak](#1-whole-file-document-translation-with-layout-preservation)
  - [2. Membaca di Peramban & Pembuatan Takarir Video](#2-in-browser-reading--subtitle-generation)
  - [3. Komunikasi Lisan & Percakapan di Tempat Tanpa Perlu Memasang Aplikasi](#3-installation-free-spoken-communication--on-site-exchange)
  - [4. Integrasi untuk Agen AI dan Pengembang](#4-integration-for-ai-agents-and-developers)
- [7. Panduan Keputusan Berbasis Tugas](#7-task-based-decision-guide)
- [8. Prinsip Direktori & Kriteria Verifikasi](#8-directory-principles--verification-criteria)
- [9. Sumber Referensi](#9-sources)

---

<a id="1-on-the-go-travel--spoken-exchange-multi-modal-and-spoken-inputs"></a>
## 1. Perjalanan & Percakapan Lisan Saat Bepergian: Input Multimodal dan Lisan

Perjalanan dan tugas lapangan menuntut aktivasi cepat, pengenalan multimodal yang andal, serta kesiapan luring (offline) saat konektivitas jaringan terbatas.

<a id="google-translate"></a>
### Google Translate
[Google Translate di perangkat seluler](https://support.google.com/translate) mengintegrasikan OCR kamera instan, impor foto, input tulisan tangan, serta percakapan tatap muka layar terpisah (split-screen). Pelancong dapat mengunduh paket bahasa terlebih dahulu untuk terjemahan teks dan kamera secara luring. Terjemahan percakapan lisan mencakup beberapa tata letak tampilan, meskipun interpretasi wicara langsung secara luring dibatasi pada perangkat Pixel tertentu dan pasangan bahasa terpilih.

Pada peramban desktop, Google Translate menyediakan [portal penerjemahan dokumen](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en) khusus yang menerima file DOCX, PDF, PPTX, dan XLSX. Alat desktop ini dirancang untuk file digital; halaman PDF hasil pindaian (scan) yang hanya berisi gambar murni dipertahankan dalam file unduhan tanpa terjemahan OCR.

<p align="center"><img src="assets/google-page@2x.webp" alt="Halaman ikhtisar produk resmi Google Translate" width="640"><br><sub>Halaman ikhtisar produk resmi Google Translate dan bagian unduhan aplikasi seluler</sub></p>

<a id="apple-translate"></a>
### Apple Translate
Bagi pengguna iPhone dan iPad, [aplikasi Apple Translate](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios) tingkat sistem tidak memerlukan instalasi terpisah. Aplikasi ini menangani teks yang diketik, input suara, deteksi teks kamera, serta percakapan tatap muka layar terpisah. Mode percakapannya dapat mendeteksi secara otomatis bahasa apa yang sedang diucapkan, meniadakan kebutuhan untuk mengganti mikrofon secara manual antar-pembicara. Paket bahasa yang diunduh memungkinkan pencarian teks langsung di perangkat (on-device) tanpa koneksi seluler.

Dalam sistem operasi Apple, [fitur terjemahan langsung](https://support.apple.com/en-us/123720) juga mencakup Pesan (Messages), Telepon (Phone), dan FaceTime. Penerjemahan panggilan telepon langsung merupakan bagian dari Apple Intelligence, yang memerlukan perangkat keras dan versi sistem yang kompatibel, serta tunduk pada aturan kelayakan regional (misalnya, perangkat yang dibeli di Tiongkok daratan saat ini tidak mendukung fitur panggilan canggih Apple Intelligence ini).

<p align="center"><img src="assets/apple-page@2x.webp" alt="Panduan Dukungan Apple untuk menerjemahkan di iPhone" width="640"><br><sub>Halaman panduan Dukungan Apple untuk menerjemahkan kata dan frasa di iPhone</sub></p>

<a id="microsoft-translator"></a>
### Microsoft Translator
[Aplikasi seluler Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/) menonjol berkat [fitur percakapan multi-perangkatnya](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/). Tuan rumah (host) memulai sesi di ponsel, dan peserta bergabung menggunakan aplikasi seluler atau peramban web desktop apa pun dengan memindai kode QR atau memasukkan kode. Setiap peserta menerima transkripsi langsung dan terjemahan dalam bahasa pilihan mereka. Mode Penyaji (Presenter mode) menjaga mikrofon tuan rumah tetap aktif sembari membisukan pendengar, sangat berguna untuk tur berpemandu dan perkuliahan.

Aplikasi ini juga menyertakan buku frasa yang dapat diunduh dan terjemahan foto secara luring untuk kebutuhan perjalanan berfrekuensi tinggi. Aplikasi konsumen ini tidak mendukung penerjemahan langsung film eksternal, file video, atau rekaman media, dan sesi suara multi-perangkat memerlukan koneksi internet aktif.

<p align="center"><img src="assets/microsoft-page@2x.webp" alt="Halaman fitur resmi Microsoft Translator" width="640"><br><sub>Halaman fitur Microsoft Translator yang menyoroti fitur percakapan multi-perangkat</sub></p>

<a id="papago"></a>
### Papago
Dikembangkan oleh NAVER di Korea Selatan, [Papago](https://papago.naver.com/) menyediakan fitur-fitur praktis untuk bahasa-bahasa Asia Timur termasuk bahasa Korea, Inggris, Jepang, dan Mandarin. Pada perangkat seluler, [aplikasinya](https://play.google.com/store/apps/details?hl=en-US&id=com.naver.labs.translator) menawarkan dialog tatap muka, mode Edu untuk membuat catatan belajar dari teks cetak, serta jendela mengambang Papago Mini, menjadikannya praktis untuk bersantap, menanyakan rute transportasi, dan belajar di Korea.

Untuk penerjemahan halaman web, pintu masuk yang tersedia berbeda antar-platform: NAVER telah menghentikan alat penerjemah situs web mandiri di portal web desktop, mengarahkan pengguna PC ke [peramban Whale](https://whale.naver.com/) bertenaga Papago, sementara [aplikasi seluler Papago](https://help.naver.com/service/16448/contents/15637?lang=ko&osType=MOBILE) masih mempertahankan opsi terjemahan situs web di menu sampingnya. Ketika paket bahasa diunduh pada perangkat kompatibel yang memenuhi prasyarat sistem (seperti yang diuraikan dalam [dokumentasi luring NAVER](https://help.naver.com/service/16448/contents/10663?osType=MOBILE), yang membutuhkan setidaknya RAM 4 GB, dan Android 14+ dengan paket suara khusus untuk ucapan), terjemahan luring mendukung teks dan suara antara bahasa Korea, Inggris, Jepang, dan Mandarin Sederhana. Perlu dicatat bahwa mode luring tidak mencakup OCR foto, mode percakapan, halaman web, atau file dokumen.

<p align="center"><img src="assets/papago-page@2x.webp" alt="Antarmuka terjemahan web resmi NAVER Papago" width="640"><br><sub>Ruang kerja penerjemahan web NAVER Papago</sub></p>

<a id="itranslate"></a>
### iTranslate
[iTranslate](https://itranslate.com/) dikenal luas berkat [Ekstensi Keyboard](https://itranslate.com/features/keyboard-translations/index.html) terintegrasinya. Saat menyusun pesan di WhatsApp, iMessage, atau email, pengguna dapat menerjemahkan teks langsung di dalam antarmuka papan ketik, menghindari perpindahan aplikasi yang terus-menerus.

Aplikasi ini juga menyediakan paket yang dapat diunduh untuk ungkapan perjalanan umum dan buku frasa dasar melalui [alat luringnya](https://itranslate.com/features/offline-translations/index.html), menjadikannya praktis untuk meninjau frasa-frasa penting sebelum bepergian. Ketersediaan fitur bervariasi di berbagai sistem operasi, dan kemampuan suara luring dibatasi pada daftar bahasa utama tertentu.

<p align="center"><img src="assets/itranslate-page@2x.webp" alt="Beranda resmi iTranslate" width="640"><br><sub>Beranda iTranslate yang menampilkan pratinjau antarmuka aplikasi seluler</sub></p>

---

<a id="2-in-context-web-reading--language-learning-reading-without-leaving-the-page"></a>
## 2. Membaca Web Sesuai Konteks & Pembelajaran Bahasa: Membaca Tanpa Berpindah Halaman

Saat membaca artikel atau dokumentasi berbahasa asing, berpindah bolak-balik ke tab terjemahan eksternal mengganggu konsentrasi. Alat terjemahan sesuai konteks (in-context) menyematkan terjemahan langsung ke dalam lingkungan membaca yang sedang aktif.

<a id="immersive-translate"></a>
### Immersive Translate
[Immersive Translate](https://immersivetranslate.com/) adalah ekstensi peramban yang menyisipkan paragraf terjemahan tepat di bawah teks web asli, menghadirkan tata letak dwibahasa yang rapi. Alat ini juga mendukung pembuatan buku elektronik EPUB dwibahasa, melihat PDF, dan menerjemahkan teks di dalam bidang input peramban.

Untuk multimedia, Immersive Translate menerjemahkan trek takarir yang sudah ada di berbagai platform seperti YouTube dan Netflix. Selain itu, fitur [terjemahan video AI](https://immersivetranslate.com/video/ai-video-translator/)-nya memanfaatkan pengenalan suara untuk menghasilkan takarir dwibahasa pada video tanpa takarir di platform yang didukung seperti YouTube, bersama dengan [portal terjemahan langsung YouTube](https://livetranslate.immersivetranslate.com/zh-CN) khusus. Pembuatan takarir dari audio tanpa takarir bergantung pada kompatibilitas peramban, kejelasan audio, dan kondisi streaming platform.

<p align="center"><img src="assets/immersive-page@2x.webp" alt="Beranda resmi Immersive Translate" width="640"><br><sub>Beranda Immersive Translate dan portal unduhan ekstensi peramban</sub></p>

<a id="mate-translate"></a>
### Mate Translate
[Mate Translate](https://matetranslate.com/en) disesuaikan untuk macOS, iOS, dan peramban desktop arus utama. Saat menjelajah web, mengeklik ganda kata apa pun akan langsung menampilkan definisi pop-up, memilih teks memunculkan terjemahan kontekstual cepat, terjemahan satu halaman penuh beralih antara tampilan asli dan terjemahan, serta menyediakan utilitas bilah menu Mac yang selalu siap digunakan.

Bagi pembelajar bahasa, Mate memungkinkan pengguna mengeklik kata-kata pada halaman web atau di dalam takarir Netflix untuk menyimpannya ke Buku Frasa (Phrasebook) khusus, yang mendukung kategorisasi kustom dan ekspor CSV untuk ditinjau lebih lanjut. Di peramban desktop seperti Chrome, ekstensinya juga memungkinkan pengguna memilih teks di dalam penampil PDF bawaan untuk memicu penerjemahan langsung.

<p align="center"><img src="assets/mate-page@2x.webp" alt="Beranda resmi Mate Translate" width="640"><br><sub>Beranda Mate Translate yang menampilkan pratinjau antarmuka multi-platform</sub></p>

<a id="reverso"></a>
### Reverso
Bagi penulis dan pembelajar yang ingin memverifikasi penggunaan kata secara alami, [Reverso Context](https://context.reverso.net/translation/about) menyediakan pasangan kalimat dwibahasa yang diambil dari film, publikasi internasional, dan situs web multibahasa, disertai tabel konjugasi kata kerja dan rekomendasi sinonim. Karena contoh kalimat berasal dari korpus multibahasa publik, pengguna perlu menilai kesesuaian konteks untuk draf yang sensitif atau formal.

Portal dokumennya, [Reverso Documents](https://www.reverso.net/documents/en), menerima file PDF, Word, PowerPoint, Excel, dan file lokalisasi tertentu. Portal ini menyediakan antarmuka peninjauan segmen-demi-segmen di peramban, tempat tim dapat berkolaborasi melakukan penyuntingan sebelum mengunduh file yang sudah selesai.

<p align="center"><img src="assets/reverso-page@2x.webp" alt="Antarmuka terjemahan resmi Reverso" width="640"><br><sub>Antarmuka terjemahan web dan bilah navigasi Reverso</sub></p>

<a id="yandex-translate"></a>
### Yandex Translate
[Portal web Yandex Translate](https://yandex.com/support/translate-desktop/en/) dan aplikasi selulernya menangani teks, gambar, situs web, dan dokumen. Klien Android-nya menyertakan kamus terperinci yang menampilkan transkripsi fonetik, definisi, sinonim, serta infleksi morfologis untuk bahasa-bahasa yang didukung.

Pada perangkat seluler, aplikasi Android-nya dilengkapi [kamus luring](https://yandex.ru/support/translate-app-android/en/offline-mobile) bahasa Inggris-Rusia bawaan, sementara paket bahasa tambahan dapat diunduh untuk terjemahan teks ketik secara luring. Antarmuka desktop mengakomodasi pengunggahan file Office dan PDF standar. Perhatikan perbedaan antara Yandex Translate sebagai layanan mandiri dan Yandex Browser, yang memuat fitur pengisian suara video otomatis (voiceover) berpemilik.

<p align="center"><img src="assets/yandex-page@2x.webp" alt="Antarmuka web resmi Yandex Translate" width="640"><br><sub>Antarmuka input dan navigasi samping Yandex Translate</sub></p>

---

<a id="3-complex-document-layouts--enterprise-workflows-preserving-formats-and-assets"></a>
## 3. Tata Letak Dokumen Kompleks & Alur Kerja Perusahaan: Mempertahankan Format dan Aset

Saat menangani salindia presentasi, kontrak pemasok, atau manual teknis, tata letak yang berantakan membutuhkan banyak perbaikan manual. Alat-alat ini memprioritaskan pemeliharaan tata letak, kontrol terminologi, dan penggunaan kembali aset.

<a id="deepl"></a>
### DeepL
[DeepL Translator](https://www.deepl.com/en/features) menawarkan opsi konfigurasi terperinci untuk alur kerja teks dan dokumen. Pengguna dapat membuat [Glosarium (Glossary)](https://www.deepl.com/en/features/glossary) untuk menerapkan terjemahan istilah teknis atau perusahaan yang diinginkan, serta beralih antara register nada formal dan informal pada bahasa yang didukung.

[Layanan penerjemahan dokumen](https://www.deepl.com/en/features/document-translation)-nya menerima file Word, PDF, PPT, Excel, HTML, dan SRT (dengan akses format bervariasi berdasarkan jenis akun). Ekosistem produknya juga mencakup DeepL Write untuk memoles teks, [DeepL Voice for Online Meetings](https://support.deepl.com/hc/en-us/articles/16810100955676-About-DeepL-Voice-for-Online-Meetings) untuk takarir waktu-nyata di Teams dan Zoom (memerlukan lisensi Voice dan izin tuan rumah), serta panduan resmi Model Context Protocol (MCP) untuk agen AI.

<p align="center"><img src="assets/deepl-page@2x.webp" alt="Ruang kerja terjemahan web resmi DeepL" width="640"><br><sub>Antarmuka penerjemah web DeepL</sub></p>

<a id="otranslator"></a>
### O.Translator
[O.Translator](https://otranslator.com/en/product-info) berfokus pada penerjemahan dokumen dengan mempertahankan tata letak. Selain PDF, Word, PPT, dan Excel, alat ini mendukung format penerbitan dan lokalisasi seperti buku elektronik EPUB, InDesign (IDML), Illustrator (AI), OpenDocument, file takarir (SRT/ASS), dan arsip komik (CBZ/CBR), dengan OCR bawaan untuk halaman pindaian. Akurasi tata letak bergantung pada penyematan font (font embedding) dan ekspansi panjang teks bahasa target.

Sebelum menerjemahkan seluruh file, O.Translator memungkinkan pengguna memeriksa pratinjau sebagian tata letak. Alat ini mendukung pengimporan glosarium melalui format XLSX atau TBX, dan menyediakan [API pengembang](https://www.otranslator.com/en/developer/v1). Opsi medianya dirancang untuk mentranskripsikan file audio dan video yang diunggah menjadi file takarir, bukan untuk terjemahan streaming peramban waktu-nyata.

<p align="center"><img src="assets/otranslator-page@2x.webp" alt="Beranda produk resmi O.Translator" width="640"><br><sub>Beranda O.Translator dan bagian pengunggahan dokumen</sub></p>

<a id="simplifyai"></a>
### SimplifyAI
SimplifyAI mengoperasikan dua situs web berbeda: [Ruang Kerja Dokumen Kompleks](https://simplifyai.cn/zh/translate) (simplifyai.cn/zh) berbasis AI dan [portal Penerjemahan Dokumen Umum](https://translate.simplifyai.cn/) (translate.simplifyai.cn).

Di dalam ruang kerja, sistem dapat mengekstrak istilah berfrekuensi tinggi sebelum penerjemahan untuk ditinjau oleh pengguna pada file Word, PPTX, InDesign, PDF, dan EPUB. Ruang kerja ini juga menyediakan AI Editing untuk Word dan InDesign (mendukung pelacakan perubahan / track changes bawaan Word), ekspor data dwibahasa (Excel/XLIFF), ekstraksi terstruktur Markdown/JSON, serta pemeriksaan visual untuk teks yang meluap (overflow) dan tata letak font, menjadikannya sangat cocok untuk pracetak (prepress) dan lokalisasi aset desain. Untuk penerjemahan file sehari-hari yang sederhana, portal penerjemahan umum menawarkan alur langsung yang lebih praktis.

<p align="center"><img src="assets/simplifyai-page@2x.webp" alt="Beranda resmi SimplifyAI" width="640"><br><sub>Beranda SimplifyAI yang menampilkan modul dan ruang kerja dokumen kompleksnya</sub></p>

<a id="lingvanex"></a>
### Lingvanex
[Lingvanex](https://lingvanex.com/) menyediakan klien desktop, seluler, dan peramban di seluruh platform Windows dan macOS. [Penerjemah desktop Windows](https://lingvanex.com/products/windows-translator/)-nya mendukung pintasan di seluruh sistem (seperti mengetuk dua kali Ctrl+C pada teks yang disorot) dan memungkinkan terjemahan teks luring serta file DOCX/ODT lokal setelah mengunduh paket bahasa.

Di luar aplikasi konsumen, Lingvanex menawarkan perangkat lunak desktop [Secure Translation Software](https://lingvanex.com/products/secure-translation-software/) yang dapat diunduh untuk penggunaan perusahaan secara luring, serta solusi Terjemahan Mesin Lokal (On-premise Machine Translation) terpisah untuk lingkungan jaringan privat.

<p align="center"><img src="assets/lingvanex-page@2x.webp" alt="Beranda resmi Lingvanex" width="640"><br><sub>Beranda Lingvanex yang menampilkan solusi terjemahan perusahaan dan penerapan lokal (on-premise)</sub></p>

<a id="systran"></a>
### SYSTRAN
SYSTRAN menargetkan kebutuhan lokalisasi tingkat perusahaan dan institusi. Layanan cloud-nya, [SYSTRAN Translate Pro](https://www.systransoft.com/translation-products/translate-pro/), dapat langsung digunakan untuk file Word, PowerPoint, Excel, dan PDF, menawarkan model domain yang telah dikonfigurasi sebelumnya untuk dokumentasi hukum, keuangan, dan industri di samping glosarium kustom dan memori terjemahan (TM).

Bagi organisasi dengan persyaratan kedaulatan data, SYSTRAN menyediakan [Translate Server](https://www.systransoft.com/translation-products/translate-server/) untuk penerapan lokal di balik firewall perusahaan, lingkungan Private Cloud khusus, serta [API](https://www.systransoft.com/translation-products/translate-api/) batch untuk pipeline dokumen.

<p align="center"><img src="assets/systran-page@2x.webp" alt="Halaman produk resmi SYSTRAN Translate Pro" width="640"><br><sub>Antarmuka ikhtisar produk resmi SYSTRAN Translate Pro</sub></p>

---

<a id="4-academic-writing-refinement--human-in-the-loop-collaboration-polishing-the-output"></a>
## 4. Penulisan Akademis, Penyempurnaan & Kolaborasi Human-in-the-Loop: Memoles Hasil Terjemahan

Penerjemahan sering kali menjadi fase awal dari alur kerja penulisan atau penelitian yang lebih luas. Memeriksa definisi kamus, memoles susunan frasa, dan penyuntingan interaktif antara manusia dan mesin membantu memastikan standar ilmiah formal terpenuhi.

<a id="youdao-translate-netease-youdao"></a>
### Youdao Translate (NetEase Youdao)
Terhubung dengan ekosistem kamus NetEase Youdao, [Youdao Translate](https://fanyi.youdao.com/) mengaitkan pencarian kosakata, penerjemahan, dan bantuan penulisan. Selain penerjemahan teks dan file standar, portal webnya menawarkan pintu masuk khusus untuk "Penerjemahan Makalah arXiv" dan pemolesan teks akademis.

Setelah menerjemahkan kutipan penelitian, pengguna dapat menjalankan pemeriksaan tata bahasa, mengevaluasi pilihan sinonim, atau menyesuaikan nada akademis, membantu mahasiswa dan peneliti menelaah literatur asing serta menyusun draf naskah. Cakupan format dan bahasa untuk pemolesan makalah dan modul media berbeda dari pencarian kamus umum.

<p align="center"><img src="assets/youdao-page@2x.webp" alt="Ruang kerja web resmi NetEase Youdao Translate" width="640"><br><sub>Antarmuka web NetEase Youdao Translate dan navigasi fitur</sub></p>

<a id="baidu-translate"></a>
### Baidu Translate
[Baidu Translate](https://fanyi.baidu.com/) menyediakan cakupan klien yang luas untuk pengguna berbahasa Mandarin. Perangkat lunak desktopnya dilengkapi jendela mengambang yang ringkas dan pemilihan teks dengan pintasan di seluruh aplikasi desktop lokal, sedangkan aplikasi selulernya memadukan terjemahan foto, latihan berbicara, dan referensi kamus.

Selain itu, Baidu menyediakan [portal Penerjemahan Video Baidu](https://fanyi-video.baidu.com/) yang berdiri sendiri. Pengguna mengunggah file media untuk menghasilkan trek takarir dwibahasa yang selaras, meninjau dan menyuntingnya di editor online, serta mengekspor file takarir yang sudah final. Ini adalah alat pascaproduksi berbasis unggahan, bukan penerjemah otomatis untuk pemutaran web langsung.

<p align="center"><img src="assets/baidu-page@2x.webp" alt="Halaman situs web resmi Baidu Translate" width="640"><br><sub>Antarmuka web resmi Baidu Translate</sub></p>

<a id="transmart-tencent-interactive-translation"></a>
### TranSmart (Tencent Interactive Translation)
Dikembangkan oleh Tencent AI Lab, [TranSmart](https://transmart.qq.com/zh-CN/intro) dirancang berpusat pada kolaborasi interaktif antara manusia dan mesin. Alih-alih menghasilkan keluaran statis untuk disalin, TranSmart menyarankan pelengkapan prediktif tingkat kata dan kalimat secara waktu-nyata, mengintegrasikan pasangan dwibahasa yang telah dikonfirmasi ke dalam memori terjemahan aktif.

Penerjemah dapat menempatkan kursor di mana saja pada teks terjemahan untuk membuat penyesuaian, yang memicu sistem untuk memperbarui saran-saran berikutnya secara dinamis. Hal ini menjaga keputusan terminologi dan ritme kalimat tetap berada di tangan pengguna, beroperasi sebagai editor kolaboratif dengan fokus yang berbeda dari aplikasi seluler kamus konsumen mandiri milik Tencent.

<p align="center"><img src="assets/transmart-page@2x.webp" alt="Halaman web resmi Tencent TranSmart" width="640"><br><sub>Antarmuka web resmi Tencent TranSmart</sub></p>

<a id="lingocloud-caiyun-xiaoyi"></a>
### LingoCloud (Caiyun Xiaoyi)
[LingoCloud](https://www.caiyunapp.com/?lang=zh) digunakan secara luas untuk alur kerja bahasa Mandarin, Inggris, dan Jepang. Ekstensi perambannya menghadirkan pengalaman membaca web dwibahasa langsung di halaman dengan dukungan glosarium publik bersama dan glosarium pribadi. [Layanan penerjemahan dokumen](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)-nya (merujuk pada panduan aplikasi seluler) menerima format seperti PDF, Word, PPT, Excel, EPUB, TXT, dan SRT, dengan hasil unduhan terutama dalam format PDF atau Word tergantung pada file sumber.

Perangkat lunak desktopnya juga dilengkapi fitur [LingoCloud Interpretation](https://www.caiyunapp.com/interpretation/), yang dapat menangkap audio mikrofon atau mencegat keluaran audio sistem dari aplikasi yang sedang berjalan (seperti Zoom, Teams, atau Chrome di Windows) untuk menampilkan takarir dwibahasa langsung. Penerjemahan lisan desktop ini tunduk pada batasan perekaman audio sistem operasi: di Windows, perekaman audio sistem berfungsi di seluruh aplikasi konferensi dan media yang didukung; di macOS, jalur perekaman audio sistem internal saat ini tidak didukung karena pembaruan sistem macOS, sehingga tangkapan mikrofon menjadi satu-satunya jalur yang dapat beroperasi.

<p align="center"><img src="assets/caiyun-page@2x.webp" alt="Halaman situs web resmi LingoCloud" width="640"><br><sub>Antarmuka web resmi LingoCloud</sub></p>

<a id="quillbot-translate"></a>
### QuillBot Translate
[QuillBot Translate](https://quillbot.com/translate) beroperasi di dalam ekosistem penulisan dan penyuntingan QuillBot. Saat menerjemahkan teks, antarmukanya menyediakan opsi formalitas serta menampilkan definisi dan sinonim dalam bahasa-bahasa yang didukung.

Teks terjemahan dapat disalin dengan mulus ke Paraphraser dan Grammar Checker untuk menyempurnakan alur kalimat. Platform ini juga mengelola [halaman Translate PDF](https://quillbot.com/translate-pdf) khusus untuk mengunggah dan meninjau dokumen PDF tunggal. Bahasa yang didukung bervariasi antara alat penerjemahan, tata bahasa, dan parafrasa.

<p align="center"><img src="assets/quillbot-page@2x.webp" alt="Halaman ekstensi Chrome Web Store resmi QuillBot" width="640"><br><sub>Halaman produk resmi Chrome Web Store untuk ekstensi peramban QuillBot</sub></p>

---

<a id="5-open-source-ecosystem-local-engines-apis-desktop-clients--scientific-pdf-pipelines"></a>
## 5. Ekosistem Sumber Terbuka: Mesin Lokal, API, Klien Desktop & Pipeline PDF Ilmiah

Pengembang, tim yang mengutamakan privasi, dan peneliti akademis sering kali membutuhkan kode yang dapat diperiksa, eksekusi luring lokal, atau pipeline otomatisasi kustom. Ekosistem penerjemahan sumber terbuka mencakup beberapa lapisan arsitektur yang berbeda:

- **Alat tata letak PDF ilmiah**: Menerjemahkan makalah akademis yang kompleks dengan tetap mempertahankan tata letak multi-kolom, formula, dan gambar.
- **Layanan penerjemahan yang dapat dihosting mandiri (self-hostable)**: Menyediakan endpoint HTTP REST API dan Web UI untuk penerapan di jaringan lokal.
- **Mesin penerjemahan luring tertanam (embedded)**: Menjalankan penerjemahan mesin saraf (neural machine translation) secara lokal melalui pustaka Python tanpa ketergantungan jaringan eksternal.
- **Frontend desktop & terminal**: Mengintegrasikan pencarian multi-mesin, pemantauan papan klip, OCR, dan pipeline shell.

> [!IMPORTANT]
> Menjalankan kode sumber terbuka secara lokal tidak otomatis berarti penerjemahan bersifat luring atau privat. Suatu alat dapat berjalan secara lokal tetapi tetap meminta kueri ke API cloud secara default. Penerjemahan yang benar-benar luring memerlukan aset model lokal sekaligus mesin penerjemahan lokal.

<a id="51-scientific--academic-pdf-pipelines"></a>
### 5.1 Pipeline PDF Ilmiah & Akademis

<a id="pdfmathtranslate-pdf2zh"></a>
#### PDFMathTranslate (pdf2zh)
[PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) (GNU AGPL v3) adalah alat sumber terbuka yang dirancang khusus untuk dokumen PDF ilmiah dan akademis. Alat ini mempertahankan struktur makalah multi-kolom, notasi matematika, grafik tersemat, daftar isi, dan anotasi.

- **Keluaran Dual dan Mono**: Menghasilkan dokumen terjemahan saja (`-mono.pdf`) maupun dokumen perbandingan dwibahasa (`-dual.pdf`).
- **Antarmuka & Integrasi**: Menyediakan alat baris perintah (CLI), WebUI interaktif, penerapan kontainer Docker, dan dukungan Model Context Protocol (MCP). Plugin integrasi Zotero tertaut tersedia sebagai proyek pendamping.
- **Backend Penerjemahan**: Menggunakan arsitektur pluggable yang mendukung Google Translate (default terdokumentasi), DeepL, API yang kompatibel dengan OpenAI, dan instans Ollama lokal. Penerapan lokal melalui Docker atau WebUI tidak berarti beroperasi secara luring jika backend cloud dikonfigurasikan.
- **Dukungan OCR**: Menyertakan OCR eksperimental untuk halaman pindaian teks hitam di atas latar belakang putih (mengunduh aset model bahasa saat pertama kali digunakan, yang kemudian dapat digunakan kembali secara lokal).

<p align="center"><img src="assets/pdfmathtranslate-page.webp" alt="Halaman repositori GitHub resmi PDFMathTranslate" width="640"><br><sub>Ikhtisar repositori resmi PDFMathTranslate yang mengilustrasikan terjemahan tata letak PDF akademis dan alur kerja CLI/WebUI</sub></p>

<a id="babeldoc"></a>
#### BabelDOC
[BabelDOC](https://github.com/funstory-ai/BabelDOC) (GNU AGPL v3) adalah pustaka penerjemahan makalah ilmiah dan perbandingan dwibahasa tingkat dokumen, dirancang terutama untuk disematkan ke dalam aplikasi Python, disertai CLI untuk proses debugging.

- **Kontrol Tata Letak & Keluaran**: Mendukung keluaran mono atau dual, tampilan berdampingan pada halaman yang sama atau halaman asli/terjemahan bergantian, penerjemahan halaman selektif, pemisahan dan penggabungan PDF besar, input CSV glosarium kustom, serta pelestarian formula. Penerjemahan teks tabel secara eksplisit didokumentasikan sebagai fitur eksperimental.
- **Arsitektur Backend**: Memerlukan backend penerjemahan yang terkonfigurasi melalui endpoint yang kompatibel dengan OpenAI atau instans Ollama lokal. Sebagai mesin pemrosesan dan tata letak PDF, pustaka ini tidak menyertakan mesin penerjemahan universal bawaan secara mandiri.
- **Aset Luring & Batasan**: Menyediakan rutinitas pemanasan (warmup) serta pembuatan/pemulihan aset luring untuk font dan model tata letak dokumen. Eksekusi yang sepenuhnya luring memerlukan aset yang sudah di-cache sebelumnya dan backend penerjemahan yang berjalan secara lokal (seperti Ollama lokal). Dokumentasi menyoroti validasi utama pada alur kerja bahasa Inggris-ke-Mandarin, dengan solusi OCR eksperimental untuk teks hitam di atas latar belakang putih.

<p align="center"><img src="assets/babeldoc-page.webp" alt="Halaman repositori GitHub resmi BabelDOC" width="640"><br><sub>Ikhtisar repositori resmi BabelDOC yang mendemonstrasikan kemampuan pustaka terjemahan PDF ilmiah tingkat dokumen</sub></p>

<a id="52-self-hostable-engines--apis"></a>
### 5.2 Mesin & API yang Dapat Dihosting Mandiri (Self-Hostable)

<a id="libretranslate"></a>
#### LibreTranslate
[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) (GNU AGPL v3) adalah layanan API penerjemahan mesin gratis dan sumber terbuka yang dapat dihosting mandiri (self-hostable) dengan Web UI bawaan, dibangun di atas mesin Argos Translate.

- **API & Layanan Web**: Menyediakan endpoint REST API untuk terjemahan teks, deteksi bahasa sumber, dan penanganan HTML/markup. Alat ini berfungsi sebagai lapisan layanan independen dan bukan sebagai proksi ke API terjemahan komersial.
- **Penerapan Lokal & Privasi**: Dapat berjalan sepenuhnya pada perangkat keras lokal tanpa mengirimkan data ke pihak ketiga eksternal setelah dependensi dan model bahasa dipasang. Penggunaan instans publik yang dihosting tetap bergantung pada jaringan. Kontrol akses kunci API dapat diaktifkan atau dinonaktifkan sesuai kebutuhan host.
- **Cakupan Bahasa & Format File**: Pasangan bahasa yang tersedia bergantung pada model bahasa yang dipasang. Melalui proyek pendamping seperti argos-translate-files, penerjemahan file mendukung format termasuk TXT, ODT, ODP, DOCX, PPTX, EPUB, HTML, SRT, dan PDF.

<p align="center"><img src="assets/libretranslate-page.webp" alt="Halaman repositori GitHub resmi LibreTranslate" width="640"><br><sub>Ikhtisar repositori resmi LibreTranslate yang menampilkan API terjemahan mandiri (self-hosted) dan fitur antarmuka web</sub></p>

<a id="argos-translate"></a>
#### Argos Translate
[Argos Translate](https://github.com/argosopentech/argos-translate) (Lisensi MIT / opsi CC0 dinyatakan di README) adalah pustaka terjemahan Python luring sumber terbuka dan alat baris perintah, dengan klien GUI yang dapat dipasang secara terpisah.

- **Paket Model Modular**: Mengunduh dan mengelola paket model bahasa menggunakan ekstensi `.argosmodel`. Jika pasangan bahasa langsung tidak tersedia, alat ini dapat melakukan penerjemahan pivot melalui pasangan perantara yang terpasang (misalnya, menerjemahkan melalui bahasa Inggris).
- **Mesin Ekosistem**: Berfungsi sebagai mesin penerjemahan mesin yang mendasari LibreTranslate. Proyek-proyek pendamping memperluas kemampuannya untuk penerjemahan HTML (`translate-html`) dan pemrosesan file (`argos-translate-files`).
- **Operasi Luring**: Berjalan sepenuhnya secara luring setelah model dipasang; pengunduhan indeks paket dan model awal memerlukan konektivitas internet.

<p align="center"><img src="assets/argos-translate-page.webp" alt="Halaman repositori GitHub resmi Argos Translate" width="640"><br><sub>Ikhtisar repositori resmi Argos Translate yang merinci mesin terjemahan luring modular dan sistem paket</sub></p>

<a id="53-desktop--terminal-frontends"></a>
### 5.3 Frontend Desktop & Terminal

<a id="pot-pot-desktop"></a>
#### Pot (pot-desktop)
[Pot](https://github.com/pot-app/pot-desktop) (GNU GPL v3) adalah alat terjemahan desktop lintas platform untuk Windows, macOS, dan Linux, yang mendukung terjemahan teks yang disorot melalui tombol pintas (hotkey), input ketikan, pemantauan papan klip, OCR tangkapan layar, dan terjemahan tangkapan layar. Repositori upstream resmi telah diarsipkan oleh pemiliknya pada 7 September 2026 dan kini berstatus hanya-baca (read-only).

- **Agregasi Multi-Layanan**: Memungkinkan pengiriman kueri ke beberapa layanan terjemahan dan kamus secara bersamaan untuk membandingkan hasil secara berdampingan. Mendukung text-to-speech (TTS), ekspor kosakata ke Anki dan Eudic, serta ekstensi plugin.
- **Backend & OCR yang Dapat Disesuaikan**: Menggabungkan penyedia terjemahan cloud, API yang kompatibel dengan OpenAI, dan endpoint Ollama lokal. Pilihan OCR mencakup opsi bawaan platform (OCR sistem Windows, Apple Vision, Linux Tesseract), Tesseract.js, atau plugin lokal.
- **Jalur Eksekusi Luring**: Terjemahan teks yang disorot dan diketik hanya memerlukan backend terjemahan lokal yang terkonfigurasi (seperti instans Ollama lokal); terjemahan tangkapan layar juga memerlukan mesin OCR luring (seperti OCR bawaan platform atau Tesseract). Layanan cloud meneruskan permintaan melalui jaringan.

<p align="center"><img src="assets/pot-desktop-page.webp" alt="Halaman repositori GitHub resmi terjemahan desktop Pot" width="640"><br><sub>Ikhtisar repositori resmi klien desktop Pot yang menyoroti alur kerja penerjemahan multi-antarmuka, OCR, dan papan klip</sub></p>

<a id="translate-shell"></a>
#### Translate Shell
[Translate Shell](https://github.com/soimort/translate-shell) (The Unlicense / Domain Publik) adalah alat terjemahan baris perintah serbaguna (file biner `trans`) untuk lingkungan terminal mirip-Unix.

- **Pencarian CLI & Kamus**: Mendukung definisi kata, terjemahan frasa, mode kamus ringkas, sesi REPL interaktif, dan identifikasi bahasa langsung di dalam shell.
- **Pipeline Unix**: Terintegrasi dengan input/output standar (`stdin` / `stdout`), memproses file teks secara langsung, dan mendukung sintesis ucapan jika pemutar audio eksternal terpasang.
- **Lapisan Mesin**: Beroperasi sebagai frontend klien ringan yang terhubung ke layanan terjemahan publik (Google Translate secara default, Bing Translator, Yandex.Translate, dan Apertium).
- **Batasan**: Tidak menyertakan model terjemahan saraf lokal; operasi standar bergantung pada konektivitas jaringan eksternal ke layanan mesin yang dipilih. Penerjemahan file dirancang untuk aliran teks polos (plain text), bukan dokumen berformat.

<p align="center"><img src="assets/translate-shell-page.webp" alt="Halaman repositori GitHub resmi Translate Shell" width="640"><br><sub>Ikhtisar repositori resmi Translate Shell yang menampilkan terjemahan baris perintah terminal dan integrasi pipeline</sub></p>

---

<a id="6-connected-end-to-end-workflows-equalang"></a>
## 6. Alur Kerja Menyeluruh yang Terintegrasi (End-to-End): Equalang

Meninjau alat-alat ini menunjukkan bahwa setiap layanan telah mengembangkan kemampuan yang jelas untuk tugas-tugas tertentu. Namun, dalam pekerjaan sehari-hari, berbagai kebutuhan sering kali saling bersinggungan:

Anda mungkin membaca white paper online di peramban, mengunduh file PDF pendukung yang memuat tabel dan diagram, menonton video perkuliahan tanpa takarir, lalu menyusun ringkasan eksekutif di Word sambil berkoordinasi langsung dengan rekan kerja internasional. Beralih di antara alat perangkat lunak yang terisolasi dan konverter file memecah alur kerja Anda.

Kami merancang **Equalang** untuk menghubungkan tugas-tugas ini ke dalam alur kerja penerjemahan berdampingan (side-by-side) yang berkesinambungan, menghadirkan dukungan penerjemahan terkoordinasi untuk dokumen, halaman web, video, dan komunikasi langsung.

<p align="center"><img src="assets/equalang-en-page@2x.webp" alt="Beranda resmi bahasa Inggris Equalang" width="640"><br><sub>Beranda situs web resmi bahasa Inggris Equalang</sub></p>

<a id="1-whole-file-document-translation-with-layout-preservation"></a>
### 1. Penerjemahan Seluruh File Dokumen dengan Mempertahankan Tata Letak
Saat menerjemahkan dokumen secara utuh, Equalang berfokus pada pemeliharaan struktur dan kegunaan pascaterjemahan, menyediakan alur kerja yang disesuaikan untuk literatur penelitian, presentasi, dan file kantor sehari-hari:

- **Dokumen PDF & Membaca**: Equalang mempertahankan tata letak multi-kolom, header, footer, dan keterangan gambar (caption), menyambungkan kembali kalimat yang terputus oleh perpindahan halaman sebelum diterjemahkan, sembari tetap mempertahankan struktur tabel, formula sebaris (inline), dan tautan dokumen internal. Sebagaimana diuraikan dalam [panduan membaca PDF akademis](https://equalang.com/blog/translate-and-read-pdf-documents) kami, pembaca dapat melihat file terjemahan berdampingan dengan dokumen asli dalam tata letak side-by-side, memahami argumen inti dalam bahasa utama mereka terlebih dahulu sebelum mencocokkan silang terminologi dan data spesifik pada halaman asli.

- **Presentasi PowerPoint**: Dalam [panduan format salindia presentasi](https://equalang.com/blog/translate-powerpoint-keep-formatting) kami, file PPTX yang diterjemahkan mempertahankan tabel asli yang dapat diedit alih-alih meratakannya menjadi gambar statis. Pemformatan tingkat kata—seperti cetak tebal, miring, dan warna font dalam satu kalimat—dipetakan secara akurat ke frasa terjemahan yang sesuai. Istilah kunci dan judul tetap konsisten di seluruh salindia, dan kotak teks secara otomatis mengecilkan ukuran font saat terjemahan memanjang guna mencegah teks meluap atau menutupi grafik.

- **File Kantor Word & Excel**: Dalam [uji coba penerjemahan Word](https://equalang.com/blog/translate-word-document-keep-formatting) kami yang terverifikasi, file DOCX yang diterjemahkan mempertahankan judul, daftar poin, tabel harga, dan format cetak tebal, memungkinkan penyuntingan langsung di Microsoft Word. Dalam [validasi lembar harga Excel](https://equalang.com/blog/translate-excel-file) kami, formula dan angka tetap tidak tersentuh sementara string teks yang sama di berbagai sel hanya diterjemahkan satu kali.

- **Buku Elektronik & Media Berformat**: Buku elektronik EPUB mempertahankan navigasi daftar isi dan tautan jangkar internal. Untuk rekaman file audio dan video hingga 180 menit, tugas penerjemahan dan transkripsi dikirimkan melalui API Pengembang dan integrasi Agent Skill/MCP kami (bukan melalui portal pengunggahan dokumen web umum), menghasilkan file takarir dwibahasa SRT/VTT bertanda waktu atau transkrip teks sumber.

<a id="2-in-browser-reading--subtitle-generation"></a>
### 2. Membaca di Peramban & Pembuatan Takarir Video
Melalui [ekstensi peramban](https://equalang.com/extension) kami yang ringan (dengan panduan instalasi untuk Chrome, Edge, dan Firefox, ditambah mode Mac Safari sementara untuk Safari 18.4+), penerjemahan terintegrasi langsung ke dalam aktivitas membaca harian Anda:

- **Membaca Web Dwibahasa di Bawah Paragraf**: Paragraf terjemahan muncul tepat di bawah teks asli saat Anda menggulir halaman. Ikon mengambang dapat diaktifkan di pengaturan untuk mencari arti kata sesuai kebutuhan. Saat melihat file PDF lokal, pengguna dapat mengaktifkan "Izinkan akses ke URL file" dalam pengelolaan ekstensi untuk memilih kata yang ingin dicari.

- **Takarir Video Dwibahasa**: Kompatibel dengan YouTube, Netflix, TikTok, dan Bilibili, sebagaimana dibahas dalam [panduan menonton video dwibahasa](https://equalang.com/blog/watch-videos-with-bilingual-subtitles) kami. Selain menerjemahkan takarir yang sudah ada, ekstensi ini dapat menangkap aliran audio untuk menghasilkan takarir dwibahasa waktu-nyata untuk **video tanpa takarir** (tunduk pada lingkungan peramban dan batasan enkripsi media, terverifikasi pada siaran langsung YouTube dan cuplikan resmi), sembari menerjemahkan komentar obrolan langsung di YouTube secara bersamaan.

<a id="3-installation-free-spoken-communication--on-site-exchange"></a>
### 3. Komunikasi Lisan & Percakapan di Tempat Tanpa Perlu Memasang Aplikasi
Meminta lawan bicara memasang aplikasi seluler khusus sering kali menimbulkan kendala, terutama saat bepergian. Saat terhubung ke internet, Equalang menghadirkan terjemahan foto dan interpretasi lisan langsung di dalam peramban standar (hanya memerlukan masuk akun pertama kali dan izin kamera/mikrofon perangkat pada penggunaan awal), seperti yang diuraikan dalam [panduan komunikasi internasional](https://equalang.com/blog/talk-with-overseas-partners) kami:

- **Terjemahan Foto Seluler**: Saat menjumpai menu restoran, rambu, atau pengumuman publik yang asing saat bepergian, pengguna cukup mengambil foto di peramban seluler mereka. Terjemahan akan langsung ditampilkan di atas tata letak foto, memudahkan memesan minuman atau membaca pengumuman dengan mencocokkannya ke gambar asli, seperti yang diilustrasikan dalam [panduan terjemahan foto perjalanan](https://equalang.com/blog/photo-translation-for-travel) kami.

- **Mode Tatap Muka**: Dirancang untuk situasi langsung seperti penitipan bagasi hotel, menanyakan arah, atau interaksi di meja resepsionis. Dua pembicara dapat meletakkan satu ponsel atau tablet secara mendatar di antara mereka, menggunakan tampilan layar terpisah terbalik (inverted split-screen) atau tampilan berdampingan dengan transkripsi dua arah yang berkelanjutan serta ekspor transkrip, sebagaimana ditunjukkan dalam [panduan tatap muka perjalanan](https://equalang.com/blog/talk-face-to-face-while-traveling) kami.

- **Mendengarkan Langsung**: Buka portal web selama presentasi atau perkuliahan tatap muka untuk menerima takarir dwibahasa waktu-nyata yang ditangkap melalui mikrofon fisik perangkat, dengan opsi audio text-to-speech dan ekspor transkrip setelah selesai (berbeda dari penangkapan audio media streaming pada ekstensi peramban).

- **Panggilan Terjemahan**: Tuan rumah masuk di portal web untuk membuat tautan panggilan aman dan membagikannya melalui aplikasi perpesanan apa pun. **Tamu bergabung langsung melalui peramban mereka tanpa perlu membuat akun atau memasang perangkat lunak apa pun**—mereka cukup memasukkan nama tampilan dan tuan rumah mengizinkan mereka masuk untuk memulai panggilan. Kedua pihak berbicara dalam bahasa ibu masing-masing, mendengar audio terjemahan, dan melihat teks waktu-nyata.

<a id="4-integration-for-ai-agents-and-developers"></a>
### 4. Integrasi untuk Agen AI dan Pengembang
Untuk membantu pengembang dan tim menyematkan penerjemahan ke dalam alur kerja otomatis:

- **API Pengembang**: Menyediakan endpoint instan untuk teks serta tugas file asinkron yang mendukung percobaan ulang dengan Idempotency-Key dan pemberitahuan callback, sebagaimana dirinci dalam [panduan integrasi API penerjemahan file](https://equalang.com/blog/integrate-file-translation-api) kami.

- **Integrasi Skill & MCP**: Kami memelihara Agent Skills sumber terbuka melalui [equalang-skill](https://github.com/equalang/equalang-skill) dan dukungan resmi Model Context Protocol melalui [@equalang/mcp](https://github.com/equalang/equalang-mcp). Di lingkungan seperti Claude Code, Codex, atau WorkBuddy, menjalankan satu instruksi instalasi dan mengonfigurasi kunci API Anda akan membekali asisten AI untuk menangani penerjemahan dokumen dan transkripsi media langsung di dalam alur kerja Anda, mengikuti [panduan penerjemahan file dengan asisten AI](https://equalang.com/blog/translate-files-with-ai-assistants) kami.

---

<a id="7-task-based-decision-guide"></a>
## 7. Panduan Keputusan Berbasis Tugas

Untuk membantu Anda memilih alat yang tepat untuk tugas Anda saat ini, lihat matriks tugas berikut:

| Tugas Utama | Kebutuhan Inti | Rekomendasi Alat | Pertimbangan Utama |
| :--- | :--- | :--- | :--- |
| **Perjalanan & Dialog Lisan** | OCR foto, dialog dua arah, paket luring & alat perjalanan terhubung | Google Translate, Apple Translate, Papago, Equalang | Unduh paket bahasa luring di Google, Apple, atau Papago (perhatikan persyaratan perangkat keras) untuk area dengan sinyal lemah; saat terhubung internet, Equalang menyediakan terjemahan foto berbasis peramban dan dialog tatap muka tanpa perlu memasang aplikasi. |
| **Lokakarya Multi-Perangkat** | Presentasi satu-ke-banyak, partisipasi multi-perangkat | Microsoft Translator | Tuan rumah menjalankan mode Penyaji melalui aplikasi seluler; peserta bergabung melalui peramban standar tanpa perlu memasang perangkat lunak. |
| **Membaca Web Mendalam** | Membaca di bawah paragraf tanpa berpindah halaman | Immersive Translate, Equalang, Mate Translate | Gunakan Immersive Translate atau Equalang untuk paragraf dwibahasa; gunakan Mate Translate untuk beralih tampilan satu halaman penuh atau menyimpan kata ke Buku Frasa di Mac. |
| **Video Tanpa Takarir & Siaran Langsung** | Pembuatan takarir waktu-nyata, kompatibilitas streaming | Equalang, Immersive Translate | Kedua alat dapat menghasilkan takarir dari audio mentah pada platform yang didukung (seperti YouTube); bandingkan alur kerja ekstensi peramban untuk obrolan langsung dan penanganan streaming. |
| **Makalah Akademis & PDF Ilmiah** | Pelestarian formula, struktur kolom, teks lintas halaman | PDFMathTranslate, BabelDOC, Equalang | PDFMathTranslate dan BabelDOC menyediakan pipeline sumber terbuka dengan keluaran PDF ganda serta backend LLM lokal/cloud; Equalang menyediakan pembacaan berdampingan berbasis peramban dan pemeliharaan tata letak. |
| **Pracetak Penerbitan & Format Desain** | InDesign, Illustrator, arsip komik, QA pracetak | SimplifyAI, O.Translator | Gunakan SimplifyAI dan O.Translator untuk InDesign (IDML) dan pracetak aset desain; SimplifyAI menyertakan AI Editing dengan pelacakan perubahan bawaan Word. |
| **Presentasi & Dokumen Kantor** | Mempertahankan tabel asli, gaya, formula, dan kemampuan edit | Equalang, DeepL | Equalang mempertahankan tabel/gaya asli PPTX dengan penyesuaian ukuran font adaptif dan retensi formula Excel; gunakan DeepL untuk file Word/Office perusahaan dengan glosarium. |
| **Penulisan Akademis & Pemolesan** | Akurasi tata bahasa, register ilmiah formal | Youdao Translate, QuillBot Translate, TranSmart | Youdao dan QuillBot memadukan penerjemahan dengan penyempurnaan teks; TranSmart menyediakan penyuntingan interaktif human-in-the-loop. |
| **Pencarian Hotkey Desktop & Multi-Mesin** | Pintasan global, OCR, membandingkan beberapa mesin | Pot, Mate Translate | Pot memungkinkan kueri multi-mesin secara simultan dan OCR tangkapan layar di Windows, Mac, dan Linux; Mate menawarkan utilitas bilah menu Mac bawaan. |
| **Skrip Terminal & Pipeline Shell** | Pencarian CLI, pipeline stdin/stdout, skrip teks polos | Translate Shell, Argos Translate | Translate Shell menyediakan terjemahan CLI ringan melalui mesin jarak jauh; Argos Translate menyediakan CLI Python luring dengan model lokal. |
| **API Privat yang Dihosting Mandiri & Mesin Luring** | Jaringan terisolasi (air-gapped), tanpa pengiriman data pihak ketiga | LibreTranslate, Argos Translate, SYSTRAN, Lingvanex | LibreTranslate menyediakan layanan HTTP API dan WebUI yang dihosting mandiri; Argos Translate mentenagainya sebagai pustaka Python/mesin CLI luring dengan paket model modular; SYSTRAN dan Lingvanex menawarkan penerapan lokal (on-premise) untuk perusahaan. |
| **Alur Kerja Menyeluruh yang Terintegrasi** | Dokumen, takarir streaming, panggilan web, dan Agen AI | Equalang | Pemrosesan dokumen terpadu, takarir media tanpa takarir, panggilan berbasis peramban tanpa instalasi aplikasi, dan integrasi langsung dengan Claude Code atau WorkBuddy. |

---

<a id="8-directory-principles--verification-criteria"></a>
## 8. Prinsip Direktori & Kriteria Verifikasi

Untuk menjaga kegunaan praktis dan keakuratan faktual dari direktori ini, setiap entri mengikuti kriteria pencantuman dan peninjauan yang ketat:

1. **Fitur Terdokumentasi di Atas Klaim Pemasaran**: Deskripsi diperoleh dari dokumentasi resmi, manual pengguna, dan file sumber repositori yang terkonfirmasi. Kami tidak mengklaim pemeliharaan tata letak yang sempurna atau dukungan format yang universal.
2. **Batasan Arsitektur yang Jelas**: Kami membedakan antara frontend terjemahan, lapisan layanan yang dapat dihosting mandiri, mesin terjemahan luring, dan pustaka tata letak dokumen. Kode sumber terbuka yang berjalan secara lokal dipisahkan secara tegas dari eksekusi luring yang sebenarnya.
3. **Cakupan Berorientasi Tugas**: Alat-alat dikelompokkan berdasarkan kesesuaian praktis di berbagai alur kerja. Kami tidak mencantumkan daftar peringkat subjektif, peringkat kualitas, atau angka harga yang bersifat sementara.
4. **Identitas Pengelola yang Transparan**: Katalog ini dikurasi dan dikelola oleh tim **Equalang**. Equalang disajikan bersama alat-alat lain dengan batasan fitur yang dapat diverifikasi dan persyaratan sistem yang transparan.

**Kata kunci**: alat penerjemahan, terjemahan dokumen, membaca web dwibahasa, terjemahan PDF akademis, terjemahan sumber terbuka, API terjemahan mesin, pemeliharaan tata letak, agen AI.

---

<a id="9-sources"></a>
## 9. Sumber Referensi

1. [Pusat Bantuan Google Translate](https://support.google.com/translate)
2. [Penerjemahan Dokumen Desktop Google Translate](https://support.google.com/translate/answer/2534559?co=GENIE.Platform%3DDesktop&hl=en)
3. [Dukungan Apple: Panduan Aplikasi Terjemahkan untuk iPhone](https://support.apple.com/en-gb/guide/iphone/iphd74cb450f/ios)
4. [Dukungan Apple: Terjemahan Langsung & Ketersediaan Fitur](https://support.apple.com/en-us/123720)
5. [Fitur Seluler Microsoft Translator](https://www.microsoft.com/en-us/translator/apps/features/)
6. [Bantuan Percakapan Multi-Perangkat Microsoft Translator](https://www.microsoft.com/en-us/translator/help/multi-device-conversation/)
7. [Portal Resmi NAVER Papago](https://papago.naver.com/)
8. [Fitur Papan Ketik & Luring iTranslate](https://itranslate.com/features/keyboard-translations/index.html)
9. [Informasi Penggunaan Reverso Context](https://context.reverso.net/translation/about)
10. [Portal Dokumen Reverso](https://www.reverso.net/documents/en)
11. [Bantuan Yandex Translate untuk Desktop & Seluler](https://yandex.com/support/translate-desktop/en/)
12. [Dokumentasi Immersive Translate](https://immersivetranslate.com/)
13. [Informasi Produk & Format O.Translator](https://otranslator.com/en/product-info)
14. [Ruang Kerja Dokumen Kompleks SimplifyAI](https://simplifyai.cn/zh/translate)
15. [Penerjemahan Dokumen Umum SimplifyAI](https://translate.simplifyai.cn/)
16. [Fitur Mate Translate](https://matetranslate.com/en)
17. [Penerjemah Windows Lingvanex](https://lingvanex.com/products/windows-translator/)
18. [Secure Translation Software Lingvanex](https://lingvanex.com/products/secure-translation-software/)
19. [SYSTRAN Translate Pro & Penerapan Perusahaan](https://www.systransoft.com/translation-products/translate-pro/)
20. [NetEase Youdao Translate](https://fanyi.youdao.com/)
21. [Portal Penerjemahan Video & Baidu Translate](https://fanyi.baidu.com/)
22. [Pengenalan Produk Tencent TranSmart](https://transmart.qq.com/zh-CN/intro)
23. [Bantuan Dokumen Caiyun Xiaoyi (LingoCloud)](https://docs.caiyunapp.com/lingocloud-app/lingocloud-introduction/app-files-trans.html)
24. [Portal PDF & QuillBot Translate](https://quillbot.com/translate)
25. [Spesifikasi API & Dokumentasi Equalang](https://equalang.com/llms-full.txt)
26. [Repositori GitHub Resmi PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate)
27. [Dokumentasi Opsi Lanjutan PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/ADVANCED.md)
28. [Repositori GitHub Resmi BabelDOC](https://github.com/funstory-ai/BabelDOC)
29. [Repositori GitHub Resmi LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)
30. [Dokumentasi & Panduan API LibreTranslate](https://docs.libretranslate.com/)
31. [Repositori GitHub Resmi Argos Translate](https://github.com/argosopentech/argos-translate)
32. [Repositori GitHub Resmi Terjemahan Desktop Pot](https://github.com/pot-app/pot-desktop)
33. [Repositori GitHub Resmi Translate Shell](https://github.com/soimort/translate-shell)
