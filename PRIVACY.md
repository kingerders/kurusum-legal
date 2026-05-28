---
permalink: /PRIVACY/
---

# Gizlilik Politikası

**Kuruşum** — Kişisel Finans Uygulaması  
Sürüm: 1.0  
Yürürlük Tarihi: 27 Mayıs 2026  
Geliştirici: erders  
İletişim: erders61@gmail.com

---

## Özet (TL;DR)

🔒 **Verileriniz cihazınızda kalır. Hiçbir veriniz bize veya üçüncü taraflara gönderilmez.**

- Sunucumuz yoktur.
- Analitik / kullanıcı takibi yapmıyoruz.
- Reklam göstermiyoruz.
- Reklam kimliği (IDFA) toplamıyoruz.
- Hesap oluşturma gerekmez — kayıt yok, parola yok.

---

## 1. Toplandığını Bilmeniz Gereken Veriler

### 1.1 Cihazınızda Saklanan Veriler (Bize Gönderilmez)

Uygulamaya girdiğiniz tüm finansal bilgiler **yalnızca kendi cihazınızın yerel depolama alanında** (Apple SwiftData) saklanır:

- Maaş, kira, mevduat, freelance gelir bilgileri
- Kredi kartı borcu, ekstre tarihleri (kart numarası isteme**z**)
- Fatura, vergi, taksit bilgileri
- Banka birikim ve mevduat kayıtları
- Stopaj ve kur ayarları
- Bildirim tercihleri

Bu veriler **hiçbir zaman** uzak bir sunucuya, bulut hizmetine veya geliştiriciye iletilmez. Uygulamayı sildiğinizde tüm veriler cihazınızdan kalıcı olarak silinir.

### 1.2 Apple Tarafından İşlenen Veriler

Aşağıdaki veriler Apple'ın kendi gizlilik politikası çerçevesinde işlenir; **geliştirici bu verilere erişemez**:

- **App Store satın alma bilgileri**: Pro Kilit Açma (₺99 launch fiyatı) satın alırsanız Apple satın almayı işler. Geliştiriciye yalnızca "bu Apple ID Pro hakkına sahip" bilgisi (entitlement) ulaşır; ad, e-posta, kart bilgisi vb. **gelmez**.
- **Bildirim izinleri**: Sistem bildirim izni durumu Apple'da tutulur, uygulama yalnızca "izin verildi mi" bilgisini okur.

### 1.3 Dış Servisten Çekilen Veriler

- **TCMB (Türkiye Cumhuriyet Merkez Bankası)**: Resmi USD/TRY ve EUR/TRY kurları için günde en fazla 4 kez `tcmb.gov.tr` adresine HTTPS isteği gönderilir. Bu istekte kişisel veri yoktur; yalnızca kur tablosu indirilir.

---

## 2. Toplanmayan Veriler

Kuruşum **kesinlikle** aşağıdaki verileri toplamaz, işlemez veya iletmez:

- ❌ Ad, soyad, e-posta, telefon, adres
- ❌ IP adresi, konum bilgisi
- ❌ Cihaz ID, IDFA, reklam tanımlayıcısı
- ❌ Analitik / kullanım metrikleri (Firebase, Mixpanel, vb. **yok**)
- ❌ Hata raporlama (crash reporting **yok**)
- ❌ Sosyal medya / paylaşım SDK'ları
- ❌ Banka veya hesap entegrasyonu (Open Banking yok)
- ❌ Kredi kartı numarası, CVV, son kullanma tarihi

---

## 3. Çocukların Gizliliği

Uygulama 13 yaş ve üzeri kullanıcılar için tasarlanmıştır. 13 yaş altı kullanıcılardan bilerek veri toplamıyoruz.

---

## 4. Veri Güvenliği

Veriler cihazınızda Apple'ın yerel veri koruma mekanizmaları ile saklanır. iOS'un standart cihaz şifrelemesi etkin olduğu sürece veriler cihaz parolası / Face ID / Touch ID ile korunur.

---

## 5. Kullanıcı Hakları (KVKK / GDPR)

Veri toplamadığımız için geleneksel anlamda işlenen kişisel veri yoktur.

- **Erişim**: Uygulamadaki tüm verilere zaten siz erişirsiniz.
- **Silme**: Uygulamayı silmek tüm verileri siler.
- **Dışa Aktarma**: Pro sürümde CSV/PDF dışa aktarım özelliği mevcuttur.

---

## 6. Politikanın Değiştirilmesi

Bu politikayı güncellersek yürürlük tarihini değiştiririz.

---

## 7. Apple Privacy Manifest

Kuruşum, Apple'ın App Tracking Transparency çerçevesinde **kullanıcıyı takip etmez**.

Uygulama Privacy Nutrition Labels: **Veri Toplanmaz** (Data Not Collected)

---

## 8. İletişim

Gizlilik konusunda sorularınız için:

**E-posta**: erders61@gmail.com
