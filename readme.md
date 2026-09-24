![Foventra Launcher](https://raw.githubusercontent.com/egalgorix/foventra-launcher/main/assets/foventra-banner.png)

# Foventra Launcher

<p align="center">
  <strong>Minecraft profillerini, loader'ları, modları ve çalışma ortamını tek merkezden yöneten masaüstü launcher.</strong>
</p>

<p align="center">
  <a href="https://github.com/egalgorix/foventra-launcher/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/egalgorix/foventra-launcher?display_name=tag&sort=semver&style=flat-square&color=4f7cff"></a>
  <a href="https://github.com/egalgorix/foventra-launcher/releases"><img alt="Total downloads" src="https://img.shields.io/github/downloads/egalgorix/foventra-launcher/total?style=flat-square&color=22c55e"></a>
  <img alt="Platform: Windows" src="https://img.shields.io/badge/platform-Windows-0078D4?style=flat-square&logo=windows11&logoColor=white">
  <img alt="Architecture: 64-bit" src="https://img.shields.io/badge/architecture-64--bit-64748b?style=flat-square">
  <img alt="License: All Rights Reserved" src="https://img.shields.io/badge/license-All%20Rights%20Reserved-e11d48?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/egalgorix/foventra-launcher/releases/latest"><strong>Windows için son kararlı sürümü indir</strong></a>
  ·
  <a href="https://launcher.foventra.com">Ürün sayfası</a>
  ·
  <a href="https://github.com/egalgorix/foventra-launcher/issues">Hata bildir</a>
</p>

---

## Foventra Launcher nedir?

Foventra Launcher, farklı Minecraft sürümlerini ve mod yükleyicilerini birbirinden bağımsız profiller halinde yönetmek için geliştirilen bir masaüstü uygulamasıdır. Oyun sürümü, loader, modlar, shader'lar, kaynak paketleri, veri paketleri, eklentiler, Java çalışma zamanı ve bellek ayarları aynı çalışma alanından yönetilebilir.

Her profil kendi klasörünü ve yapılandırmasını kullanır. Böylece Vanilla, Fabric, Forge ve NeoForge kurulumları birbirine karışmadan aynı cihazda tutulabilir.

## Öne çıkan özellikler

| Alan | Özellikler |
| --- | --- |
| Profil yönetimi | Ayrı oyun klasörleri, profil oluşturma, klonlama, içe ve dışa aktarma |
| Loader desteği | Vanilla, Fabric, Forge ve NeoForge |
| Hesaplar | Microsoft hesabı ve çevrimdışı hesap desteği |
| İçerik yönetimi | Mod, shader, kaynak paketi, veri paketi ve eklenti yönetimi |
| Modrinth | Arama, uyumluluk kontrolü, bağımlılık çözümleme, toplu kurulum ve güncelleme |
| Modpack | `.mrpack` kurulumu ve bağımsız modpack profilleri |
| CurseForge | İndirilen dosya, kurulu profil klasörü ve çevrimdışı ZIP paketi içe aktarma |
| Java | Uygun Java sürümünü algılama ve gerektiğinde Eclipse Temurin kurulumu |
| Oyun dosyaları | Dosya doğrulama, eksik varlıkları tamamlama ve onarım akışı |
| Güncellemeler | Stable ve Beta kanalları, SemVer karşılaştırması ve uygulama içi güncelleme |
| Entegrasyon | İsteğe bağlı Discord Rich Presence |
| Arayüz dilleri | Türkçe, English, Azərbaycanca ve Русский |

## Profil tabanlı çalışma alanı

Foventra Launcher'da her kurulum bağımsız bir profil olarak ele alınır:

- Minecraft sürümü ve loader profil bazında seçilebilir.
- Vanilla, Fabric, Forge ve NeoForge profilleri birlikte kullanılabilir.
- Modlar, ayarlar, shader'lar ve kaynak paketleri profil klasöründe tutulur.
- Çalışan bir profil yeniden indirme gerektirmeden klonlanabilir.
- Profiller taşınabilir paketler halinde içe veya dışa aktarılabilir.
- Sürüm ya da loader değişikliğinde içerik uyumluluğu yeniden değerlendirilebilir.
- RAM sınırı cihazdaki kullanılabilir belleğe göre güvenli aralıkta tutulur.

## Mod ve içerik yönetimi

### Modrinth

Uygulama içindeki Modrinth merkezi üzerinden:

- Mod, shader, kaynak paketi, veri paketi ve eklenti aranabilir.
- Seçili Minecraft sürümü ve loader ile uyumlu dosyalar filtrelenebilir.
- Zorunlu ve isteğe bağlı bağımlılıklar çözümlenebilir.
- Birden fazla bağımlılık toplu olarak kurulabilir.
- Kurulu içerikler tek tek veya toplu şekilde güncellenebilir.
- API hız sınırları ve çakışan kurulumlar kontrollü biçimde ele alınır.

### Modpack ve manuel içe aktarma

- Modrinth `.mrpack` paketleri bağımsız profil olarak kurulabilir.
- Daha önce indirilmiş mod dosyaları manuel olarak içe aktarılabilir.
- Kurulu CurseForge profil klasörleri taşınabilir.
- Çevrimdışı ZIP paketleri içe aktarılabilir.
- Yapılandırmalar, shader'lar ve kaynak paketleri profil kapsamında korunabilir.

> CurseForge çevrimiçi arama sağlayıcısı resmi API erişimine bağlıdır. Uygulamanın içine özel API anahtarı gömülmez; manuel içe aktarma seçenekleri bu süreçten bağımsız çalışır.

## Java ve oyun başlatma

Foventra Launcher, seçilen Minecraft sürümü için uygun Java çalışma zamanını arar. Uyumlu bir kurulum bulunamazsa gereken Eclipse Temurin sürümünü uygulama veri dizinine indirip kullanıma hazırlayabilir.

Başlatma akışında:

1. Profil ve hesap bilgileri doğrulanır.
2. Gerekli Java sürümü belirlenir.
3. Oyun dosyaları ve varlıklar kontrol edilir.
4. Eksik veya bozuk dosyalar tamamlanır.
5. Bellek ve başlatma seçenekleri uygulanır.
6. Minecraft süreci başlatılır ve durum uygulama içinde izlenir.

## Hesap seçenekleri

- **Microsoft hesabı:** Microsoft kimlik doğrulama akışı üzerinden çevrimiçi hesap kullanımı.
- **Çevrimdışı hesap:** Kullanıcı adıyla yerel profil oluşturma.
- Hesap ve profil tercihleri kullanıcının cihazında saklanır.

Çevrimdışı hesap kullanımı, ücretli Minecraft içeriğine sahip olma veya çevrimiçi sunucuların kimlik doğrulama gereksinimlerini ortadan kaldırmaz.

## İndirme ve kurulum

### Windows

1. [Son kararlı sürüm](https://github.com/egalgorix/foventra-launcher/releases/latest) sayfasını açın.
2. **Assets** bölümündeki `.exe` uzantılı Foventra Launcher kurulum paketini indirin.
3. İndirdiğiniz kurulum dosyasını çalıştırın.
4. Kurulum tamamlandığında Launcher'ı Başlat menüsünden açın.

Yalnızca bu deponun resmi [Releases](https://github.com/egalgorix/foventra-launcher/releases) sayfasında yayımlanan paketleri kullanın. Farklı sitelerden dağıtılan değiştirilmiş kurulum dosyaları Foventra tarafından doğrulanmaz.

## Güncelleme kanalları

Foventra Launcher iki güncelleme kanalı sunar:

- **Stable:** Genel kullanım için yayımlanan kararlı sürümler.
- **Beta:** Yeni özellikleri daha erken denemek isteyen kullanıcılar için ön sürümler.

Güncelleme denetimi sürümleri SemVer sırasına göre karşılaştırır. Stable kanalındaki kullanıcılar beta sürümlerine otomatik geçirilmez.

## Sistem gereksinimleri

### Minimum

- 64-bit Windows 10 veya Windows 11
- 4 GB RAM
- Launcher, oyun sürümleri ve profiller için yeterli boş disk alanı
- Microsoft girişi, sürüm listeleri ve içerik indirmeleri için internet bağlantısı

### Önerilen

- 64-bit Windows 11
- 8 GB veya daha fazla RAM
- SSD depolama
- Modpack boyutuna uygun ek boş alan
- Kararlı internet bağlantısı

Java'yı önceden kurmak her zaman gerekli değildir. Launcher, uygun çalışma zamanını algılayabilir veya desteklenen Java sürümünü kendi uygulama dizinine kurabilir.

## Gizlilik ve güvenlik

- Profil, hesap tercihi ve Launcher ayarları cihaz üzerinde saklanır.
- Uygulamada davranış analizi veya reklam amaçlı telemetri bulunmaz.
- Electron renderer süreçleri sandbox ve context isolation ile çalışır.
- Harici bağlantılar izin verilen protokollerle sınırlandırılır.
- `.env`, GitHub token'ı veya özel sağlayıcı anahtarları dağıtım paketine eklenmez.
- Otomatik güncellemeler yalnızca bu public deponun resmi yayınlarından alınır.
- Oyun dosyaları başlatma sürecinde doğrulanabilir ve eksik içerikler tamamlanabilir.

Bir güvenlik açığı tespit ederseniz ayrıntıları herkese açık issue olarak paylaşmayın. Bildirimi **support@foventra.com** adresine gönderin.

## Sorun bildirme

Bir hata bildirirken mümkünse şu bilgileri ekleyin:

- Foventra Launcher sürümü
- Windows sürümü
- Seçili Minecraft sürümü ve loader
- Sorunu yeniden oluşturma adımları
- Beklenen ve gerçekleşen davranış
- Kişisel bilgi veya erişim anahtarı içermeyen hata kaydı

Yeni bildirim oluşturmak için [GitHub Issues](https://github.com/egalgorix/foventra-launcher/issues) sayfasını kullanabilirsiniz.

## Proje bağlantıları

- **Foventra:** https://foventra.com
- **Launcher sayfası:** https://launcher.foventra.com
- **Kararlı sürüm:** https://github.com/egalgorix/foventra-launcher/releases/latest
- **Tüm yayınlar:** https://github.com/egalgorix/foventra-launcher/releases
- **Destek:** support@foventra.com

## Yasal bilgi

Foventra Launcher; Mojang Studios, Microsoft, Modrinth, CurseForge, Overwolf veya Discord tarafından geliştirilmemiş, onaylanmamış ya da desteklenmemiş bağımsız bir projedir.

Minecraft adı ve ilgili varlıklar kendi hak sahiplerine aittir. Kullanıcılar Minecraft lisans koşullarına, hizmet şartlarına ve kullandıkları içerik sağlayıcılarının kurallarına uymaktan sorumludur.

## Lisans

Copyright © Foventra. Tüm hakları saklıdır.

Bu yazılım açık kaynak lisansı altında dağıtılmaz. Yazılımın veya parçalarının izinsiz kopyalanması, değiştirilmesi, yeniden dağıtılması ya da ticari kullanımı yasaktır.

---

<p align="center">
  <strong>Foventra Launcher</strong><br>
  Profillerini kur. İçeriğini düzenle. Oyuna geç.
</p>
