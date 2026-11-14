# LocalPDF

LocalPDF, PDF işlemlerini yalnızca tarayıcı içinde gerçekleştiren statik bir web uygulamasıdır. Dosyalarınız uzak bir sunucuya yüklenmez.

## Kullanım

`index.html` dosyasını bir statik sunucuyla açın veya GitHub Pages üzerinde yayınlayın. CDN bağımlılıkları nedeniyle ilk açılışta internet bağlantısı gerekir.

Sunucu olmadan hızlı önizleme için herhangi bir statik dosya sunucusu kullanabilirsiniz. GitHub Pages, `main` dalındaki kök klasörü yayınlayacak şekilde yapılandırılabilir.

## Araçlar

PDF.js, pdf-lib ve Fabric.js v5 ile çalışan PDF Studio; sayfa küçük resimleri, canvas üstü metin/vurgu/redaksiyon nesneleri ve PDF dışa aktarımı sunar. Ek istemci tarafı araçlar arasında imza, redaksiyon, Türkçe+İngilizce Tesseract OCR, gri tonlama, 2/4-up yerleşim, QR PDF, DOCX→PDF ve metadata düzenleme/sıfırlama bulunur.

Tüm CDN kütüphaneleri yalnızca tarayıcıda çalışır; dosyalar sunucuya gönderilmez.
