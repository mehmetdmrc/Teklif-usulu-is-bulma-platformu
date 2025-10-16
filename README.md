# Kayıp-bulma-platformu
# FindIt – Kayıp Eşya ve Sahip Bulma Platformu

Bu repository, "FindIt" projesi için hazırlanan **Proje Planı Raporu** içermektedir.

---

## 1. Proje Fikri Belirleme + Proje Planı Raporu

**Proje Tanımı:**  
FindIt, kullanıcıların kayıp veya bulunan eşyaları paylaşarak sahiplerine ulaşmasına yardımcı olan bir web platformudur. Kullanıcılar kayıp eşya ilanı oluşturabilir, kategori ve konum bilgisine göre arama yapabilir ve mesajlaşma veya iletişim formu ile ilan sahiplerine ulaşabilir.

**Projenin Amacı:**  
- Kayıp eşyaların kısa sürede sahiplerine ulaştırılmasını sağlamak  
- Toplumda yardımlaşma ve güven duygusunu artırmak  
- Kağıt ilan veya sosyal medya paylaşımlarına alternatif, dijital ve organize bir sistem oluşturmak

**Hedef Kitle:**  
- Günlük yaşamda eşyalarını sıkça kaybeden bireyler  
- Kayıp eşya bulan ve sahibine ulaştırmak isteyen kişiler  
- Belediyeler, üniversiteler, kafeler veya alışveriş merkezleri gibi yoğun alanlarda kayıp eşya yönetimi yapan kurumlar

### SMART Hedefler

| Hedef | Özellik | Ölçüt | Gerçekleşme Süresi | Ulaşılabilirlik | İlgililik |
|-------|---------|-------|------------------|----------------|-----------|
| 3 ay içinde temel web platformunu (MVP) yayına almak | MVP sürümü hazır | MVP sürümü hazır | 3 ay | Gerçekçi | Evet |
| Kullanıcıların %70’inin kayıt işlemini 2 dakikadan kısa sürede tamamlaması | Kullanıcı testleri | Başarı oranı %70 | 2. ay | Evet | Evet |
| İlk 6 ayda en az 100 aktif ilan oluşturulması | Veri takibi | 100 ilan | 6 ay | Evet | Evet |

**Ana Fonksiyonlar (MVP):**  
- Kullanıcı kaydı ve giriş sistemi  
- Kayıp / Bulunan ilanı oluşturma  
- İlanlara fotoğraf ekleme  
- Kategori ve konuma göre arama  
- Basit iletişim formu veya mesajlaşma  
- İlan düzenleme / silme  
- Yönetici paneli (ilan onayı / düzenleme)

**Zaman Planı:**

| Aşama | Açıklama | Süre |
|-------|----------|------|
| 1. Hafta | Proje planlama ve analiz | 1 hafta |
| 2–3. Hafta | Arayüz tasarımı (wireframe + mockup) | 2 hafta |
| 4–6. Hafta | Frontend geliştirme (HTML, CSS, JS) | 3 hafta |
| 7–9. Hafta | Backend geliştirme (veritabanı, ilan sistemi) | 3 hafta |
| 10. Hafta | Test, hata düzeltme, son teslim | 1 hafta |

---

## 2. Bilgi Mimarisi + Sitemap + User Flow

**Amaç:**  
Projede kullanıcıların siteyi nasıl kullanacağını anlamak ve sayfa yapısını tasarlamak.

**Sitemap:**  
Ana Sayfa, Eşya Ara, İlan Ver, Kullanıcı Profili, Yönetici Paneli, Yardım, Hakkında

**User Flow Örnekleri:**  
- Ana Sayfa → Eşya Ara → Filtreleme → İlan Detay → Mesajlaşma  
- Ana Sayfa → İlan Ver → Fotoğraf yükleme → Form doldurma → Onay

**Sayfa Hiyerarşisi:**  
- Ana Sayfa  
  - Kayıp Eşyalar  
    - İlan Detayı  
  - Bulunan Eşyalar  
    - İlan Detayı  
  - İlan Ver (Form)  
  - Profilim  
  - Mesajlar  
  - Hakkında / Yardım  
  - Yönetici Paneli

**İçerik Stratejisi:**  
Her sayfa kullanıcıya net bilgi ve işlev sunar

---

## 3. Product Backlog + Kanban Planı

**User Stories Örnekleri:**  
- Kullanıcı kayıt ve giriş  
- İlan oluşturma  
- Arama ve filtreleme  
- Mesajlaşma  
- Yönetici onayı  
- Profil düzenleme  
- Responsive tasarım  
- Bildirim sistemi  
- Yardım sayfası

**Kanban Tablosu:**

| To Do | Doing | Done |
|-------|-------|------|
| Kullanıcı kayıt & giriş | Arama ve filtreleme | Bildirim sistemi |
| İlan oluşturma modülü | Profil sayfası | Yardım sayfası |
| Mesajlaşma sistemi | | |

**WIP Limiti:** Doing sütunu için en fazla 3 görev aynı anda işlenebilir

---

## 4. Risk Analizi + Paydaş Haritası

**Olası Riskler ve Önlemler:**

| No | Risk Başlığı | Risk Açıklaması | Risk Türü | Olasılık | Etki | Risk Seviyesi | Çözüm / Önlem |
|----|--------------|----------------|-----------|----------|------|---------------|----------------|
| R01 | Sunucu hatası | Sunucu çökmesi veya barındırma hizmeti kesilmesi | Teknik | Orta | Yüksek | Yüksek | Güvenilir hosting ve yedekleme sistemi kullanmak |
| R02 | Veritabanı hatası | Verilerin yanlış veya eksik kaydedilmesi | Teknik | Düşük | Yüksek | Orta | Veritabanı yedekleme ve test senaryoları hazırlamak |
| R03 | Zaman gecikmesi | Proje teslim tarihine yetişememe | Zaman | Orta | Orta | Orta | Haftalık sprint kontrolü yapmak |
| R04 | Kullanıcı verilerinin sızması | Kişisel verilerin korunmaması | Güvenlik | Düşük | Yüksek | Yüksek | Şifreleme (SSL) ve güçlü parola politikası uygulamak |
| R05 | İletişim eksikliği | Ekip arasında bilgi akışının zayıf olması | İletişim | Orta | Orta | Orta | Düzenli toplantılar ve dijital araçlar kullanmak |
| R06 | Kullanıcı ilgisizliği | Platformun yeterli kullanıcıya ulaşamaması | Pazarlama | Orta | Orta | Orta | Sosyal medya kampanyaları ve işbirlikleri |
| R07 | Hatalı kullanıcı girişi | Eksik veya yanlış ilan verileri | Kullanıcı | Yüksek | Düşük | Orta | Form doğrulama ve hata mesajları |
| R08 | Cihaz uyumsuzluğu | Mobil cihazlarda site görünümünün bozulması | Teknik | Orta | Orta | Orta | Responsive testleri yapmak |

**Paydaş Haritası:**

| Paydaş | Rol / Katkı | İletişim Düzeyi | Öncelik |
|--------|-------------|----------------|---------|
| Proje Yöneticisi | Planlama, zaman yönetimi, görev ataması | Yüksek | Yüksek |
| Web Tasarımcı | Arayüz (UI/UX) tasarımı | Orta | Orta |
| Yazılım Geliştirici | Backend & frontend kodlama | Yüksek | Yüksek |
| Sistem Yöneticisi | Sunucu yönetimi ve veritabanı desteği | Orta | Orta |
| Kullanıcılar | Siteyi aktif olarak kullanan bireyler | Düşük | Yüksek |
| Kurumlar | Platformun tanıtımı ve kullanımı | Düşük | Orta |
| Sosyal Medya Ekibi | Tanıtım, duyuru ve kullanıcı etkileşimi | Orta | Orta |

---

## Sonuç

Bu rapor, **FindIt platformunun fikir, planlama, bilgi mimarisi, backlog ve risk analiz aşamalarını detaylı şekilde** sunar. Proje yönetimi, kullanıcı deneyimi ve risk yönetimi becerilerini geliştirmeye yöneliktir.
