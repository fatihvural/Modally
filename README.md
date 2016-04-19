# Modally

[Modally Anasayfa]

Modally javascript jquery vb. yüklü ve karmaşık eklentiler kurmadan sadece Html ve Css
ile animasyonlu şık modallar yani sayfa açılışında popup bir pencere göstermeyi sağlar.

Kullanımı oldukça basittir.

### Neden Kullanayım Ki
 - Sadece 4 kb
 - Gelişmiş animasyon seçenekleri mevcut
 - Html ve Css tabanlı olduğu için herhangi bir ekstra yükleme gerektirmez
 - Tüm tarayıcılarda çalışmaktadır

### 1. Adım
Css dosyasını web sitenize dahil edin.

> <link rel="stylesheet" href="modally-min.css" />

### 2. Adım
Gösterilen yere popup içeriğinizi yazın.

    <div class="modally">
        <input type="checkbox" id="mdly">
        
        <div class="mdly-overlay left b">
            <div class="mdly-content">
                <div class="mdly-c">
                
                Buraya Modal Yani Popup İçeriğiniz Gelecek.
                
                <label for="mdly" class="mdly-cls">KAPAT</label>
                </div>
            </div>
        </div>
    </div>

### Gelişmiş Özellikler

### Background Ekleme

    <div class="mdly-overlay b"></div> Siyah Transparan Background
    <div class="mdly-overlay y"></div> Yeşil Transparan Background
    <div class="mdly-overlay s"></div> Sarı Transparan Background
    <div class="mdly-overlay m"></div> Mavi Transparan Background
    <div class="mdly-overlay k"></div> Kırmızı Transparan Background

### Animasyon Ekleme

     <div class="mdly-overlay fadein b"></div> Kararma Efekti
     <div class="mdly-overlay up b"></div> Üstten Gelme Efekti
     <div class="mdly-overlay down b"></div> Alltan Gelme Efekti
     <div class="mdly-overlay left b"></div> Soldan Gelme Efekti
     <div class="mdly-overlay right b"></div> Sağdan Gelme Efekti
     <div class="mdly-overlay scale b"></div> Büyüme Efekti
     <div class="mdly-overlay rotate b"></div> Dönme Efekti
     <div class="mdly-overlay shake-x b"></div> X Ekseninde Titreme Efekti
     <div class="mdly-overlay shake-y b"></div> Y Ekseninde Titreme Efekti

### # Örnek Kullanımlar
    
    <div class="mdly-overlay scale y"></div> Büyüme Efektli Yeşil Arkaplanlı Modal
    <div class="mdly-overlay rotate m"></div> Dönme Efektli Mavi Arkaplanlı Modal
    
### Version Bilgisi : V1

### Modally Sayfası
[Modally Sayfası]

### Profilim
[Github Profilim]




Lisans
----

MIT

[Modally Anasayfa]: <https://github.com/ysoftaoglu>
[Github Profilim]: <https://github.com/ysoftaoglu>
[Modally Sayfası]: <https://github.com/ysoftaoglu/Modally>
