# Manisa Strateji Haritasi

Bu klasor GitHub Pages'e dogrudan yuklenmeye hazirdir.

Icerik:
- `index.html`: parola giris ekrani
- `manisa_strateji_haritasi.html`: asil harita sayfasi
- `rehber.html`: oturum kontrolunden sonra PDF rehbere yonlendirir
- `manisa_strateji_haritasi_kullanim_rehberi.pdf`: rehber dosyasi
- `.nojekyll`: GitHub Pages icin statik yayin yardimci dosyasi

Kullanim:
1. Bu klasordeki dosyalari bir GitHub reposunun kokune koy.
2. Repo ayarlarinda `Pages` altindan `main` ve `/ (root)` sec.
3. Yayin adresi acildiginda once `index.html` uzerindeki parola ekrani gelir.

Not:
- Bu yontem gercek bir sunucu tarafli guvenlik saglamaz. Yalnizca rastgele ziyaretleri filtrelemek icin istemci tarafli bir giris kapisidir.
- `index.html`, `manisa_strateji_haritasi.html` ve `rehber.html` dosyalarinda ayni `PASSWORD_HASH` sabiti kullanilir.
- Harita internet baglantisi ister; taban harita ve kutuphane dosyalari CDN uzerinden cagirilir.
