<p align="center">
  <img src="assets/efeber2.svg" width="94" alt="EFEBER2 logo">
</p>

<h1 align="center">EFEBER2 — GLIDE MODDING STUDIO</h1>

<p align="center"><strong>GTA araçlarından Glide eklentisi oluştur • Simfphys araçlarını Glide'a dönüştür</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2064--bit-222222" alt="Windows 64 bit">
  <img src="https://img.shields.io/badge/Status-Public%20Beta-e63946" alt="Public Beta">
  <img src="https://img.shields.io/badge/Focus-Garry's%20Mod%20Glide-c0392b" alt="Glide">
</p>

<p align="center">
  <a href="https://github.com/efeberstudio/efeber2/releases"><strong>⬇ Sürümleri görüntüle</strong></a>
  · <a href="docs/KURULUM.md">Kurulum ve kullanım</a>
  · <a href="docs/SSS.md">Sık sorulan sorular</a>
  · <a href="https://github.com/efeberstudio/efeber2/issues">Hata bildir / Öneri gönder</a>
</p>

---

## Glide araç yapmak artık daha erişilebilir

**EFEBER2**, Garry's Mod için **Glide araç eklentisi üretmeye** odaklanan bağımsız bir Windows mod geliştirme uygulamasıdır. GTA San Andreas ve desteklenen GTA V Legacy araç modellerini bir stüdyo içinde düzenleyip Glide için hazırlayabilir; Steam Workshop'taki desteklenen **Simfphys araç modlarını Glide'a dönüştürmeyi** deneyebilirsiniz.

Amaç, model, kaplama, tekerlek, koltuk, ses ve fizik ayarlarını farklı araçlar arasında taşımak zorunda kalmadan tek bir iş akışında toplamaktır.

> **Public Beta — v0.6:** EFEBER2 gelişmektedir. Her kaynak araç veya özel Simfphys modunun kusursuz dönüşmesi garanti edilmez. Özellikle tekerlek yönleri, sürücü koltuğu, çarpışma modeli ve sürüş fiziği GMod içinde kontrol edilmelidir.

## 🚗 01 — GTA → Glide Araç Stüdyosu

Kendi **Glide aracınızı** tasarlamak ve Garry's Mod'a aktarmak için:

- **GTA SA DFF/TXD** ve desteklenen **GTA V Legacy** araçlarını içe aktarma
- Gerçek zamanlı **3D araç önizlemesi**, parça seçme, tümünü seçme ve grup hâlinde ölçekleme
- Tekerlek, sürücü ve yolcu koltuklarının konumlarını görüntüleme/düzenleme
- Oturan insan referanslarıyla **şeffaf araç gövdesi** üzerinden koltuk hizalama
- Kaplama/malzeme düzenleme ve GMod renk aracı için boyanabilir gövde seçimi
- **Araç adı, motor sesi ve korna** belirleme; önizleme sesini uygulama içinde ayarlama
- **Normal otomobil, spor otomobil, hafif ticari, minibüs ve ağır araç** sürüş profilleri
- Modeli derleyip Glide eklentisi olarak dışa aktarma

**Örnek:** Bir GTA aracını yükleyin → 3D görünümde ölçeğini ve tekerleklerini ayarlayın → motor/korna, kaplama ve sürüş sınıfını seçin → Glide eklentisini oluşturun.

## 🔄 02 — Simfphys → Glide Converter

Halihazırda Simfphys için hazırlanmış bir aracı **Glide'a dönüştürmek** mi istiyorsunuz?

1. Steam Workshop aracının bağlantısını kopyalayın.
2. **Simfphys → Glide** ekranına bağlantıyı yapıştırın.
3. Dönüştürmeyi başlatın.
4. Çıkan eklentiyi Garry's Mod'da test edin.

Desteklenen modlarda çok araçlı paket işleme, kaynak dosya/bağımlılık çözümleme ve tekerlek-koltuk dönüşümü bulunur.

**Beta uyarısı:** Kaynak araçların özel tekerlek sistemleri, eksenleri, attachment noktaları ve oturma konumları farklıdır. Otomatik işlem bazı araçlarda ek düzenleme gerektirebilir.

## 🧍 03 — GMod Player Model (ek modül)

EFEBER2 ayrıca desteklenen karakter modellerini **Garry's Mod Player Model** için hazırlamaya yardımcı bir bölüm içerir. Model/doku içe aktarma, UV/iskelet uyarlama ve çıktı hazırlama araçları mevcuttur. **CS2 hedef seçeneği bu sürümde bulunmaz.**

---

## İndir ve başla

**Son beta:** `efeber2_beta_0.6` · **Windows 10/11 — 64 bit**

**[→ GitHub Releases sayfasına git](https://github.com/efeberstudio/efeber2/releases)**

Release yayımlandığında **Assets** altındaki `efeber2_beta_0.6.exe` dosyasını indirin. Bu GitHub deposu belge ve duyuruları barındırır; **kaynak kodu açık kaynak lisansıyla yayımlanmamıştır.**

### Glide için hızlı başlangıç

1. EFEBER2'yi açın, **Glide Araç Stüdyosu** bölümüne girin.
2. Kaynak araç modelini içe aktarın; modelin boyutunu, tekerleklerini ve koltuklarını kontrol edin.
3. Kaplamayı ve GMod renk ayarını seçin.
4. **Araç** sekmesinden isim, motor sesi, korna ve araç sınıfını ayarlayın.
5. Garry's Mod `garrysmod` klasörünü doğrulayıp derleyin.
6. Oyunda **Glide** eklentisinin yüklü olduğundan emin olun; aracı spawnlayıp test edin.

**[→ Ayrıntılı kurulum ve Glide kullanımı](docs/KURULUM.md)**

## Sık sorulan sorular

**EFEBER2 tam olarak ne yapıyor?**  
Öncelikle GTA araçlarını Glide'a hazırlamayı ve desteklenen Simfphys modlarını Glide'a çevirmeyi kolaylaştırır.

**Her GTA aracı Glide'a dönüşür mü?**  
Hayır. Kaynak modelin formatı ve yapısına bağlıdır. Fizik, materyal, hitbox, koltuk veya tekerlek düzeltmeleri gerekebilir.

**Spor araba seçince gerçekten daha hızlı mı oluyor?**  
Sürüş sınıfları Glide Lua/fizik değerlerini etkiler; elde edilen hız ve manevra davranışı modele göre farklılık gösterir.

**Simfphys için sadece Workshop linki yeterli mi?**  
Desteklenen modlarda bağlantıyla dönüştürme amaçlanır. Workshop erişimi, bağımlılıklar ve bazı özel araç yapıları ilave adım gerektirebilir.

**Otomatik koltuklar ve tekerlekler her zaman doğru mu?**  
Hayır. Beta hesaplamaları gelişmektedir; kaynak modelin attachment bilgileri eksik olabilir.

**Oyunda Glide kurulu olmalı mı?**  
Evet. Oluşturulan Glide araçlarını GMod'da kullanabilmek için Glide gereklidir.

**Program ücretsiz mi, kaynak kodu açık mı?**  
Bu depo beta dağıtımı ve belgeleri içindir. Kaynak kodu şu an açık kaynak olarak yayımlanmamıştır.

**AI kaplama veya CS2 seçeneği var mı?**  
Hayır. AI demo kaldırılmıştır; Player Model modülü GMod odaklıdır.

**[→ Tüm sorular ve cevapları](docs/SSS.md)**

## Hata bildirimi ve geri bildirim

EFEBER2 beta olduğundan kullanıcı geri bildirimleri özellikle önemlidir. **[GitHub Issues](https://github.com/efeberstudio/efeber2/issues)** üzerinden kaynak Workshop bağlantısı, uygulama sürümü, ekran görüntüsü ve hatanın tekrarlanma adımlarıyla bildirim gönderebilirsiniz.

**[Sürüm geçmişi](CHANGELOG.md)** · **[Kurulum](docs/KURULUM.md)** · **[Beta 0.6 sürüm notları](docs/RELEASE_0.6.md)**

---

<p align="center"><strong>EFEBER2</strong> · Made for the Garry's Mod modding community</p>
<p align="center"><sub>Bağımsız topluluk projesidir; Facepunch, Valve, Rockstar veya Glide geliştiricilerinin resmî ürünü değildir. Üçüncü taraf modların haklarına ve kullanım izinlerine saygı gösterin.</sub></p>
