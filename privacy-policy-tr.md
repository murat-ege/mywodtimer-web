# Gizlilik Politikası — MyWOD Timer

**Yürürlük / Son Güncelleme Tarihi:** 30 Ekim 2026  
**Uygulama Adı:** MyWOD Timer  
**Geliştirici:** Murat Ege  
**Uygulama Kimliği (Bundle / Package ID):** `com.mege.mywodtimer`  
**Web Sitesi:** [https://murat-ege.github.io/mywodtimer-web](https://murat-ege.github.io/mywodtimer-web)

[🇬🇧 Click here for the English Privacy Policy](privacy-policy)

---

## 1. Genel Bakış

**MyWOD Timer** ("Uygulama"), Murat Ege tarafından iOS ve Android cihazlar için geliştirilen, tüm hakları saklı bir antrenman ve interval sayaç uygulamasıdır. Bu Gizlilik Politikası, Uygulamanın Ücretsiz (Free) ve PRO sürümlerini kullandığınızda verilerin nasıl işlendiğini ve korunduğunu açıklar.

---

## 2. Yerel Antrenman Verileri ve Cihaz İçi Depolama

MyWOD Timer'ı kullanmak için **üyelik oluşturmanız veya oturum açmanız gerekmez**.

Uygulama içinde oluşturduğunuz tüm antrenman verileri yalnızca **kendi cihazınızın dahili hafızasında** (`Hive` ve `SharedPreferences` yerel veritabanları kullanılarak) saklanır:
- Özel antrenman sayaçları, interval şablonları ve ana ekran klasör düzenleri
- Antrenman geçmişi (Workout Log), tur (split) süreleri, round/tekrar sayıları ve antrenman notları
- Uygulama tercihleri (ses temaları, sesli koç ayarları, dil ve ekran tercihleri)
- Kaydedilen antrenman videoları ve sayaç katmanlı (HUD) video çıktıları

Antrenman kayıtlarınız, kişisel notlarınız ve kaydettiğiniz videolar tarafımıza ait herhangi bir sunucuya yüklenmez. Tüm kayıtlarınızı, önbellek dosyalarınızı ve videolarınızı istediğiniz zaman **Ayarlar → Depolama ve Medya** menüsünden veya Uygulamayı cihazınızdan kaldırarak kalıcı olarak silebilirsiniz.

---

## 3. Cihaz İzinleri ve Kullanım Amaçları

MyWOD Timer yalnızca temel uygulama işlevlerini yerine getirmek için aşağıdaki izinleri talep eder:

1. **Kamera (`NSCameraUsageDescription` / `android.permission.CAMERA`):** Yalnızca **Antrenman Video Kamerası (Kayıtlar)** sekmesinde antrenmanlarınızı ekranda canlı dijital sayaç katmanı (HUD) ile kaydetmeniz için kullanılır. Video işleme tamamen cihazınızda gerçekleşir.
2. **Mikrofon (`NSMicrophoneUsageDescription` / `android.permission.RECORD_AUDIO`):** Yalnızca antrenman videosu kaydederken ortam sesinin videoya eklenmesi için kullanılır (kamera ekranından istediğiniz an kapatılabilir).
3. **Fotoğraf Galerisi / Medya Depolama (`NSPhotoLibraryUsageDescription` / `NSPhotoLibraryAddUsageDescription`):** Yalnızca kaydettiğiniz antrenman videolarını cihaz galerisine kaydetmek veya sistem paylaşım ekranı üzerinden dışa aktarmak istediğinizde kullanılır.
4. **Arka Plan Ses ve Ekran Açık Tutma (`UIBackgroundModes: audio` / `WAKE_LOCK`):** Antrenman sırasında ekranın kapanmasını önler, ekran kilitliyken geri sayım bip seslerini ve Sesli Koç (`TTS`) anonslarını zamanında çalar ve uyarı sırasında arka plan müzik sesini yumuşakça kısar (ducking).
5. **Bildirimler ve Titreşim (`POST_NOTIFICATIONS` / `VIBRATE`):** Antrenman aralık geçişlerinde haptik titreşim ve yerel bildirim sağlar.

---

## 4. Uygulama İçi Reklamlar (Ücretsiz Sürüm) ve Reklam Kimlikleri

MyWOD Timer'ın Ücretsiz (Free) sürümünde uygulama içi reklam gösterimi (Google AdMob vb. yetkili reklam ağları aracılığıyla) yapılmaktadır.

- **Reklam İçin İşlenebilen Veriler:** Üçüncü taraf reklam SDK'ları; reklam göstermek, sıklığı sınırlamak ve performansı ölçmek amacıyla cihaz reklam kimliğini (iOS'ta `IDFA`, Android'de `AAID`), yaklaşık konum (IP tabanlı ülke/şehir), cihaz modeli/işletim sistemi bilgisi ve reklam etkileşim verilerini kullanabilir.
- **İzin ve Takip Kontrolü:**
  - **iOS (App Tracking Transparency - ATT):** iOS 14.5 ve üzeri cihazlarda kişiselleştirilmiş reklamlar için Apple'ın sistem izin penceresi üzerinden açık onayınız sorulur. İzin vermemeniz halinde yalnızca bağlamsal (kişiselleştirilmemiş) reklamlar gösterilir.
  - **KVKK / GDPR Rıza Yönetimi:** Yürürlükteki veri koruma mevzuatına uygun olarak reklam tercihlerinizi yönetebilirsiniz.
- **Reklamları Kaldırma (MyWOD Timer PRO):** **MyWOD Timer PRO** sürümüne geçiş yaptığınızda uygulama içi reklamlar tamamen kaldırılır.

Google'ın iş ortağı uygulamalardaki verileri nasıl kullandığı hakkında detaylı bilgi için [Google Gizlilik ve Şartlar](https://policies.google.com/technologies/partner-sites) sayfasını inceleyebilirsiniz.

---

## 5. Uygulama İçi Satın Alımlar ve Abonelikler (MyWOD Timer PRO)

MyWOD Timer; kısıtlı özellikleri açmak, videolardaki filigranı (watermark) kaldırmak ve reklamları devre dışı bırakmak için **MyWOD Timer PRO** ücretli geçiş seçenekleri sunar.

- Tüm ödeme işlemleri iOS'ta **Apple (App Store / StoreKit)**, Android'de ise **Google (Google Play Faturalandırma)** altyapısı üzerinden güvenli şekilde gerçekleştirilir.
- MyWOD Timer kredi kartı numaranıza, banka bilgilerinize veya fatura adresinize erişmez ve bunları saklamaz; yalnızca PRO haklarınızı doğrulamak için mağaza tarafından sağlanan anonim işlem makbuzunu kontrol eder.

---

## 6. Çökme Raporları ve Performans Tanılama

Uygulamanın kararlılığını artırmak amacıyla mağaza platformları (Apple App Store / Google Play) tarafından sağlanan anonim çökme kayıtları (cihaz modeli, işletim sistemi sürümü ve hata izi) incelenebilir. Bu veriler kişisel kimlik bilgisi veya antrenman videosu içermez.

---

## 7. KVKK ve GDPR Kapsamındaki Haklarınız

Antrenman kayıtlarınız, özel rutinleriniz ve videolarınız doğrudan cihazınızda saklandığı için bunları görüntüleme, dışa aktarma (CSV/video) ve kalıcı olarak silme kontrolü tamamen sizdedir. Reklam kimliği izinlerinizi cihazınızın sistem ayarlarından (**iOS:** *Ayarlar → Gizlilik ve Güvenlik → Takip*; **Android:** *Ayarlar → Google → Reklamlar*) dilediğiniz zaman sıfırlayabilir veya kapatabilirsiniz.

---

## 8. Değişiklikler ve İletişim

Bu Gizlilik Politikası zaman zaman güncellenebilir. Güncel metin her zaman [https://murat-ege.github.io/mywodtimer-web/privacy-policy-tr](https://murat-ege.github.io/mywodtimer-web/privacy-policy-tr) adresinde yayınlanır.

Sorularınız için [Destek Sayfamızı](support-tr) ziyaret edebilirsiniz:
- **Geliştirici:** Murat Ege
- **Destek Portalı:** [https://murat-ege.github.io/mywodtimer-web/support-tr](https://murat-ege.github.io/mywodtimer-web/support-tr)

