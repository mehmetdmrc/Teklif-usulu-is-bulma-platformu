# 💼 Açık Artırmalı İş Platformu

## 🎯 Proje Tanımı

Bu proje, işverenlerin iş ilanı verebildiği ve işçilerin (freelancer veya hizmet sağlayıcıların) bu ilanlara teklif sunabildiği bir **açık artırma sistemi** geliştirmeyi amaçlamaktadır.
İşveren, yapılacak işi tanımlar; işçiler ise işi ne kadar ücretle yapabileceklerini teklif ederler. İşveren en uygun teklif sahibini seçerek işi başlatır.

Bu sistem, klasik iş ilan sitelerinden farklı olarak **“ters açık artırma”** mantığıyla çalışır:

* Fiyat düşürme rekabeti sağlanır.
* İşveren uygun maliyetli, kaliteli iş gücü bulur.
* İşçi kendine uygun işlere teklif vererek kazanç sağlar.

---

## 🎯 Hedef Kitle

* **İşverenler:** Kısa süreli veya proje bazlı iş yaptırmak isteyen bireyler, küçük işletmeler, ajanslar.
* **İşçiler:** Yazılım geliştiriciler, tasarımcılar, editörler, tamirciler, çevirmenler vb.
* **Platform Yöneticileri:** Sistemin güvenliğini ve doğruluğunu sağlayan admin kullanıcılar.

---

## ⚙️ Temel Özellikler

* Üyelik sistemi (işveren / işçi)
* İş ilanı oluşturma ve açıklama ekleme
* Teklif verme (işçiler tarafından)
* Teklif yönetimi ve seçim
* Mesajlaşma modülü
* Ödeme işlemleri (örnek olarak sanal cüzdan veya banka havalesi entegrasyonu)
* Yönetici paneli (kullanıcı, ilan ve şikayet yönetimi)

---

## 🧩 Teknolojiler

* **Frontend:** HTML, CSS, JavaScript (React veya Vue.js)
* **Backend:** PHP (Laravel) veya Node.js (Express)
* **Veritabanı:** MySQL veya MongoDB
* **Versiyon Kontrol:** Git & GitHub
* **Tasarım:** Figma / Wireframe (UX planlaması için)

---

## 👥 Ekip Üyeleri ve Görev Dağılımı

| Üye Adı | Görevi                                  | Açıklama                                            |
| ------- | --------------------------------------- | --------------------------------------------------- |
| Mehmet  | Proje Yöneticisi / Full Stack Developer | Genel proje yönetimi, backend & frontend geliştirme |
| Üye 2   | UI/UX Designer                          | Arayüz tasarımı, kullanıcı akışı                    |
| Üye 3   | Veri Tabanı Uzmanı                      | MySQL şema tasarımı, veri güvenliği                 |
| Üye 4   | Test Sorumlusu                          | Hata tespiti ve kullanıcı deneyimi testleri         |

---

## 📅 Zaman Çizelgesi (Tahmini)

| Aşama                             | Süre    | Açıklama                         |
| --------------------------------- | ------- | -------------------------------- |
| 1. Analiz ve planlama             | 1 hafta | Gereksinimlerin belirlenmesi     |
| 2. Wireframe & Mockup             | 1 hafta | Arayüz tasarımı                  |
| 3. Veritabanı ve backend kurulumu | 2 hafta | API geliştirme                   |
| 4. Frontend geliştirme            | 3 hafta | Sayfa yapısı, dinamik içerikler  |
| 5. Test ve hata ayıklama          | 1 hafta | Kullanıcı testleri               |
| 6. Yayına hazırlık                | 1 hafta | GitHub yükleme, final kontroller |

**Toplam Süre:** 9 hafta

---

## 💰 Bütçe Dağılımı (Tahmini)

| Gider Türü              | Tahmini Tutar          | Açıklama                      |
| ------------------ | ---------------------- | ----------------------------- |
| Domain & Hosting   | 1500 TL                | Yıllık barındırma ve alan adı |
| Yazılım Geliştirme | 0 TL (öğrenci projesi) | Kendi geliştirme katkısı      |
| Tasarım Araçları   | 500 TL                 | Figma / Adobe XD lisansı      |
| Güvenlik & SSL     | 300 TL                 | HTTPS sertifikası             |
| **Toplam**         | **2300 TL**            | —                             |

---

## ⚠️ Risk Analizi ve Çözümleri

| Risk                            | Etki   | Çözüm                                    |
| ------------------------------- | ------ | ---------------------------------------- |
| Veri güvenliği zafiyeti         | Yüksek | Şifreleme (bcrypt), SSL, güvenli giriş   |
| Kullanıcı sahteciliği           | Orta   | E-posta doğrulama, kimlik kontrolü       |
| Proje gecikmesi                 | Orta   | Agile sprint takvimi ile yönetim         |
| Hatalı teklif / ödeme sorunları | Yüksek | Manuel onay, escrow sistemi entegrasyonu |

---

## 📈 Beklenen Sonuçlar

* Güvenilir, açık artırma temelli iş bulma platformu.
* Kullanıcı dostu arayüz.
* Freelance pazarında fark yaratan bir model.
* Gerçek dünya örneklerinde (Freelancer, Upwork, Armut) benzeri işleyiş.

---

## 📦 GitHub Kullanımı

Proje GitHub’da şu şekilde yönetilecektir:

* `main` branch: Yayınlanan sürüm
* `dev` branch: Geliştirme aşaması
* Commit mesajları: `feat: yeni özellik eklendi`, `fix: hata düzeltildi` formatında tutulacak.
* README dosyası: Kurulum ve kullanım bilgilerini içerecek.

---

## 🧾 Lisans

Bu proje eğitim amaçlı geliştirilmiştir.
Ticari kullanım için geliştirici onayı gereklidir.
