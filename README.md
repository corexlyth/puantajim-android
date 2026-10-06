# Puantajım
### Emeğinin Hesabı · CoreXlyth

Yevmiye, mesai, kazanç ve ödemelerini takip etmek için geliştirilen, koyu temalı Android uygulaması.

![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-2.4%20Beta-35d7ba)
![Android](https://img.shields.io/badge/Android-8.0%2B-35d7ba)
![Paket](https://img.shields.io/badge/Paket-com.corexlyth.puantaj.crx-152333)

## Özellikler

- Günlük yevmiye ve mesai kaydı; düzenleme ve silme.
- Kayıt ekledikten sonra tarihin otomatik olarak sonraki güne geçmesi.
- Aylık kazanç, alınan ödeme/avans ve kalan alacak özeti.
- Aylık kazanç grafiği ve kayıt bulunan aylar/yıllar arasında gezinme.
- Şirket ve şantiye bazında kazanç dökümü.
- Yevmiye tutarı ile şirket/şantiye ayarlarının ayrı yönetilmesi. Yevmiye değişikliği, kaydedilmiş günlerin ücretini değiştirmez.
- Ödeme kayıtları ve ödeme tamamlandığında ayı kilitleme.
- JSON veri yedeğini dışa aktarma ve geri yükleme.
- Seçilen ay veya tüm zamanlar için Excel ve PDF raporları.
- İsteğe bağlı ay sonu yedek hatırlatması.
- Özel açılış animasyonu ve CoreXlyth marka tasarımı.

## Kurulum ve Güncellemeler

APK yayımlandığında [Releases](https://github.com/corexlyth/puantajim-android/releases) bölümünden indirilebilir. Şu an bu sayfa tek başına bir APK indirme bağlantısı değildir.

1. Yayımlanan APK dosyasını telefonuna indir.
2. Android isterse APK'yı açtığın uygulama için yükleme izni ver.
3. Uygulamayı kur ve Ayarlar'dan yevmiye tutarını belirle. Şirket ve şantiye isteğe bağlıdır.
4. Daha önce aldığın veri yedeğin varsa **Verileri İçe Aktar** ile yükle.

Güncellemeden önce **Verileri Dışa Aktar** ile yedek al. Aynı paket ve aynı imzayla yayımlanan güncellemeler mevcut uygulamanın üzerine kurulabilir. JSON yedeğiyle veri aktarılır.

## Yedekleme ve Raporlar

**Verileri Dışa Aktar** geri yüklenebilen JSON yedeğini oluşturur. **Verileri İçe Aktar**, onay sonrasında mevcut kayıtların yerine seçilen yedeğin verilerini yükler.

Excel ve PDF dosyaları rapordur; veri yedeği olarak geri yüklenmez. Uygulamayı kaldırmadan veya telefon değiştirmeden önce JSON yedeğini uygulama dışında güvenli bir yerde sakla.

## Ay Sonu Hatırlatması

**Ayarlar → Bildirimler → Ay Sonu Yedek Hatırlatması** seçeneğiyle açılır. Android bildirim izni gerekebilir. Ayın son günü Türkiye saatiyle 20:00 civarında yedek almayı hatırlatır; Android ve pil tasarrufu nedeniyle gecikebilir.

Bu özellik otomatik yedek oluşturmaz. Test bildirimi doğrulandı; aylık otomatik bildirimin gerçek tarihindeki teslimi henüz doğrulanmadı.

## Veriler

Çalışma kayıtları cihazda tutulur. Temel kayıt ve hesaplama işlemleri internet gerektirmez. GitHub düğmesi bağlantıyı tarayıcıda açar.

## Sürüm

| Bilgi | Değer |
| --- | --- |
| Sürüm | 2.4(Beta) |
| Sürüm Kodu | 2 |
| Paket | `com.corexlyth.puantaj.crx` |
| Minimum Android | Android 8.0 · API 26 |
| Marka | CoreXlyth |

[Sürüm notları](CHANGELOG.md) · [Hata Bildir](https://github.com/corexlyth/puantajim-android/issues) · [Güncellemeler](https://github.com/corexlyth/puantajim-android/releases)

Hata bildirirken sürümü, telefon/Android bilgisini ve sorunu oluşturan adımları yaz. Ekran görüntülerinde kişisel kayıtlarını gizle; kişisel JSON yedeğini herkese açık bir issue'ya yükleme.

---

**CoreXlyth · Puantajım — Emeğinin Hesabı**
