# Gizlilik Politikası

**Son güncelleme:** 8 Haziran 2026
**Uygulama:** OkulPlus
**Geliştirici:** ŞansTech (karacacagri@gmail.com)

OkulPlus ("uygulama") gizliliğinize saygı duyar. Bu politika, uygulamayı kullandığınızda hangi verilerin toplandığını, nasıl işlendiğini, kimlerle paylaşıldığını ve haklarınızı KVKK (6698 sayılı Kişisel Verilerin Korunması Kanunu) ve GDPR çerçevesinde açıklar.

## 1. Veri sorumlusu

ŞansTech adına Çağrı Karaca, OkulPlus uygulaması ile ilgili veri sorumlusudur. İletişim: **karacacagri@gmail.com**

## 2. Hangi verileri topluyoruz?

### 2.1 Apple ile Giriş yaptığınızda
Apple, **"Sign In with Apple"** akışı ile bize şunları iletir:
- **Apple kullanıcı kimliği (sub claim):** Uygulamamıza özel, kalıcı kullanıcı tanımlayıcısı. E-postanızı değil, anonim bir hash'tir.
- **E-posta adresi (isteğe bağlı):** Apple Private Relay seçimine bağlı olarak gerçek veya yönlendirme adresi. Bu alanı bizimle paylaşmamayı seçebilirsiniz.
- **İsim (isteğe bağlı, yalnızca ilk girişte):** Yalnızca paylaşmayı tercih ederseniz alınır.

### 2.2 Yorum yazdığınızda
- **Yorum metni** (başlık ve gövde)
- **Yıldız puanları** (genel ve kategori bazlı)
- **Anonim/açık tercihi**
- **Tarih ve okul ID'si**
- **Yorum sahipliği:** Anonim yorumlar bile hesabınızla bağlanır (KVKK silme hakkı için).

### 2.3 AI öneri formunu kullandığınızda
- Çocuğunuzun yaşı, şehir/ilçe tercihi, öncelikler, opsiyonel not. Bu bilgiler hesabınıza kaydedilmez; yalnızca tek bir öneri talebi için işlenir.

### 2.4 Konum
- Konum izni verirseniz, **harita** ekranında yakındaki okulları gösterebilmek için cihazınızın konumunu **bellek içinde** kullanırız. Konum sunucularımıza gönderilmez, kaydedilmez.

### 2.5 Otomatik olarak toplanan veriler
- **Cihaz türü ve iOS sürümü** (yalnızca uygulama hatalarını ayıklamak için, sunucu logları)
- **IP adresi** (Fly.io hosting tarafından geçici olarak loglanır, ortalama 7 gün)

Reklam veya analiz amacıyla **hiçbir takip aracı** (Google Analytics, Facebook SDK vb.) kullanılmaz.

## 3. Verilerinizi nasıl ve neden işliyoruz?

| Amaç | Hukuki dayanak (KVKK m.5) |
|---|---|
| Hesap oluşturma ve girişin yönetimi | Sözleşmenin ifası |
| Yorumlarınızın yayınlanması | Açık rızanız |
| AI moderasyonu (içerik yasal/etik kontrolü) | Meşru menfaat |
| AI okul önerisi | Açık rızanız (form gönderilince) |
| KVKK silme hakkı için yorum-hesap ilişkilendirmesi | Yasal yükümlülük |
| Hata ayıklama ve güvenlik | Meşru menfaat |

## 4. Üçüncü taraflarla paylaşım

| Hizmet | Hangi veri | Nerede tutulur |
|---|---|---|
| **Apple (Sign In with Apple)** | Kimlik doğrulama | Apple'ın sunucuları |
| **Google Gemini API** | AI öneri form içeriği ve yorum metni (moderasyon için, geçici) | Google sunucuları, [Gemini API gizlilik politikası](https://ai.google.dev/gemini-api/terms) |
| **Resend** | E-posta adresi (giriş kodu gönderimi için, v1.1+ aktif) | Resend sunucuları, [resend.com/legal](https://resend.com/legal) |
| **Fly.io** | Uygulama sunucusu hosting | Frankfurt veri merkezi |
| **Neon** | PostgreSQL veritabanı | Avrupa veri merkezi |

Bu hizmet sağlayıcılar yalnızca size hizmet sunabilmek için gerekli olan kısımlara erişir; verinizi kendi pazarlama amaçları için **kullanmaz, satmaz, üçüncü taraflara aktarmaz.**

## 5. Veri saklama süresi

- **Hesap verileri ve yorumlar:** Hesabınız aktif olduğu sürece. Hesabınızı silerseniz hepsi anında ve kalıcı olarak silinir.
- **Sunucu logları:** En fazla 30 gün.
- **AI öneri formu içeriği:** Yalnızca cevap süresi boyunca işlenir, kaydedilmez.

## 6. Verilerinize ilişkin haklarınız

KVKK m.11 ve GDPR m.15-22 kapsamında:

- Hangi verilerinizin işlendiğini öğrenme
- Düzeltme talep etme
- **Silme talep etme** (uygulama içinden tek tıkla yapabilirsiniz: Profil → Hesap Bilgileri → "Hesabımı kalıcı olarak sil")
- İşlenmesine itiraz etme
- Veri taşınabilirliği (JSON formatında verinizi talep edebilirsiniz)

Bu haklarınızı kullanmak için **karacacagri@gmail.com** adresinden bizimle iletişime geçin. Cevap süresi en fazla 30 gün.

## 7. Çocukların gizliliği

OkulPlus, **13 yaş ve üzeri** kullanıcılara yöneliktir. Velilik veya çocuklar adına yorum yazdığınızda çocuğunuzun kimliğini ifşa edecek bilgi paylaşmamanız gerekir. Bunu otomatik AI moderasyonu da denetler.

## 8. Veri güvenliği

- Tüm bağlantılar TLS 1.3 ile şifrelidir.
- Şifreler saklanmaz (Sign In with Apple, parolasız e-posta OTP).
- Veritabanı erişimi yalnızca uygulama sunucusu üzerindendir.
- Yedekler şifrelenmiş olarak Neon tarafından otomatik alınır.

## 9. Politikadaki değişiklikler

Politikayı değiştirirsek, sayfanın başındaki "Son güncelleme" tarihini güncelleriz. Önemli değişikliklerde uygulama içinde bilgilendiririz.

## 10. İletişim

Soru, talep veya şikayet için: **karacacagri@gmail.com**

Veri Koruma Otoritesi başvurusu: [kvkk.gov.tr](https://www.kvkk.gov.tr)
