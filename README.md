# LocalPDF

LocalPDF, PDF işlemlerini yalnızca tarayıcı içinde gerçekleştiren statik bir web uygulamasıdır. Dosyalarınız uzak bir sunucuya yüklenmez.

## Kullanım

`index.html` dosyasını bir statik sunucuyla açın veya GitHub Pages üzerinde yayınlayın. CDN bağımlılıkları nedeniyle ilk açılışta internet bağlantısı gerekir.

Sunucu olmadan hızlı önizleme için herhangi bir statik dosya sunucusu kullanabilirsiniz. GitHub Pages, `main` dalındaki kök klasörü yayınlayacak şekilde yapılandırılabilir.

## Araçlar

PDF.js, pdf-lib ve Fabric.js v5 ile çalışan PDF Studio; sürükle-bırak sayfa sıralama, döndürme, kopyalama, silme ve boş sayfa ekleme, yakınlaştırma/pan, sayfa bazlı nesne durumu, seçim/düzenleme, undo/redo ve klavye kısayolları sunar. Metin, şekil, serbest çizim, vurgu, redaksiyon, görsel ve imza katmanları PDF sayfalarına PNG olarak gömülerek dışa aktarılır. Ek istemci tarafı araçlar arasında Türkçe+İngilizce Tesseract OCR, gri tonlama, 2/4-up yerleşim, QR PDF, DOCX→PDF ve metadata düzenleme/sıfırlama bulunur.

Studio kısayolları: `Ctrl/Cmd+Z` geri al, `Ctrl/Cmd+Y` yinele, `Ctrl/Cmd+Shift+Z` yinele, `Delete/Backspace` seçili nesneyi sil, `Esc` seçim aracına dön.

Tüm CDN kütüphaneleri yalnızca tarayıcıda çalışır; dosyalar sunucuya gönderilmez.
