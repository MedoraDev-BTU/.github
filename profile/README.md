<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f4c81,30:1a7fbf,70:00c2a8,100:00e5b0&height=220&section=header&text=Medora&fontSize=80&fontColor=ffffff&fontAlignY=40&desc=Akıllı%20Sağlık%20Randevu%20ve%20Yönetim%20Platformu&descAlignY=62&descSize=22&animation=fadeIn" width="100%"/>

<br/>

[![BTU](https://img.shields.io/badge/Bursa%20Teknik%20Üniversitesi-Bilgisayar%20Mühendisliği-0f4c81?style=for-the-badge&logo=graduation-cap&logoColor=white)](https://www.btu.edu.tr)
[![Proje](https://img.shields.io/badge/Yazılım%20Mühendisliği-Takım%205-00c2a8?style=for-the-badge&logo=heart&logoColor=white)]()
[![Durum](https://img.shields.io/badge/Durum-Geliştiriliyor-f59e0b?style=for-the-badge&logo=github-actions&logoColor=white)]()
[![Lisans](https://img.shields.io/badge/Lisans-MIT-green?style=for-the-badge&logo=opensourceinitiative&logoColor=white)]()

<br/>

> **"Sağlıkta dijital dönüşüm — hasta ile kliniği tek platformda buluşturuyoruz."**

</div>

---

## 📋 İçindekiler

- [🏥 Proje Hakkında](#-proje-hakkında)
- [❗ Problem Tanımı](#-problem-tanımı)
- [🎯 Proje Amacı ve Hedefler](#-proje-amacı-ve-hedefler)
- [✨ Özellikler](#-özellikler)
- [🗺️ Sistem Mimarisi](#️-sistem-mimarisi)
- [🛠️ Teknoloji Yığını](#️-teknoloji-yığını)
- [🧠 Yazılım Geliştirme Süreci](#-yazılım-geliştirme-süreci)
- [📅 Geliştirme Takvimi](#-geliştirme-takvimi)
- [👥 Takım ve Görev Dağılımı](#-takım-ve-görev-dağılımı)
- [🗄️ Veritabanı Tasarımı](#️-veritabanı-tasarımı)
- [⚠️ Risk Analizi](#️-risk-analizi)
- [📖 Kullanım Kılavuzu](#-kullanım-kılavuzu)
- [🤝 Katkı Sağlama](#-katkı-sağlama)
- [💰 Yatırım ve Destek](#-yatırım-ve-destek)
- [📢 Bağlantılar](#-bağlantılar)

---

## 🏥 Proje Hakkında

**Medora**, özel sağlık kuruluşları ile hastaları tek bir dijital platformda buluşturan, randevu süreçlerini merkezi ve akıllı bir şekilde yöneten modern bir sağlık yönetim sistemidir.

Sistem; **mobil uygulama (hasta tarafı)**, **web yönetim paneli (klinik tarafı)** ve güçlü bir **backend API** altyapısından oluşmaktadır. REST mimarisi üzerine inşa edilen Medora, ölçeklenebilir ve güvenilir bir yapı sunar.

```
👤 Hasta Mobil Uygulaması  ←→  ⚙️ Backend API  ←→  🖥️ Klinik Web Paneli
                                      ↕
                               🗄️ MongoDB / SQL
```

---

## ❗ Problem Tanımı

Mevcut özel sağlık kuruluşlarında randevu süreçleri ciddi sorunlar barındırmaktadır:

| Sorun | Etki |
|---|---|
| 📞 Telefon / WhatsApp üzerinden manuel randevu | Zaman kaybı, iletişim hataları |
| 🔀 Randevu çakışmaları | Hasta memnuniyetsizliği |
| 👁️ Müsait saatlerin görülememesi | Verimsiz planlama |
| 📊 Randevu takibinin zayıf olması | Klinik verimliliği düşüklüğü |
| 🗺️ Doğru hizmete ulaşmada güçlük | Hasta kaybı |

> 👉 **Medora bu problemlerin tamamına kalıcı, dijital çözümler sunar.**

---

## 🎯 Proje Amacı ve Hedefler

### Misyon
Sağlık sektöründeki dağınık ve manuel randevu süreçlerini dijitalleştirerek hem hastalar hem de klinikler için **verimli, kolay ve güvenilir** bir deneyim sunmak.

### Temel Hedefler

- ✅ Hastaların konumlarına göre sağlık hizmetlerine hızlı erişimini sağlamak
- ✅ Randevu oluşturma ve yönetim süreçlerini tamamen dijitalleştirmek
- ✅ Kliniklerin randevu planlamasını sistematik ve verimli hale getirmek
- ✅ Gerçek zamanlı bildirimler ile hasta–klinik iletişimini güçlendirmek
- ✅ Puanlama ve favori sistemleri ile hasta deneyimini iyileştirmek

### Kapsam

Proje aşağıdaki bileşenleri kapsamaktadır; ücretlendirme bilgisi ise bilinçli olarak sistem dışında tutulmuştur.

- 📱 Mobil uygulama (hasta tarafı — React Native / Expo)
- 🖥️ Web tabanlı yönetim paneli (klinik tarafı — React)
- ⚙️ Backend servisleri (Node.js / Express + Python)
- 🗄️ Veritabanı sistemi (MongoDB / SQL)

---

## ✨ Özellikler

<table>
<tr>
<td width="50%" valign="top">

### 📱 Hasta Tarafı (Mobil)

- 📍 Konuma göre klinik & doktor arama
- 🔍 Branş bazlı filtreleme
- 📅 Randevu oluşturma ve takibi
- 🕐 Müsait saat görüntüleme
- ⭐ Klinik & doktor puanlama sistemi
- ❤️ Favorilere ekleme
- 📜 Geçmiş randevuları görüntüleme
- 💊 Nöbetçi eczane görüntüleme

</td>
<td width="50%" valign="top">

### 🖥️ Klinik Tarafı (Web Panel)

- 🏥 Klinik & doktor yönetimi
- 🕐 Çalışma saati düzenleme
- ✅ Randevu onaylama / iptal / erteleme
- 📊 Randevu istatistikleri & analizler
- 🔔 Gerçek zamanlı bildirimler
- 👁️ Klinik puanlarını görüntüleme
- 📍 Konum bilgisi yönetimi

</td>
</tr>
</table>

### 🔄 Randevu Yaşam Döngüsü

```
⏳ Beklemede  →  ✅ Onaylandı  →  🏁 Tamamlandı
                     ↓
                ❌ İptal Edildi / 🔁 Ertelendi
```

---

## 🗺️ Sistem Mimarisi

Sistem **üç katmanlı (3-tier) mimari** ile tasarlanmıştır:

```
┌─────────────────────────────────────────────────────────┐
│                    İSTEMCİ KATMANI                      │
│                                                         │
│   📱 Expo / React Native        🖥️ React Web Paneli     │
│         (Hasta Uygulaması)         (Klinik Paneli)      │
└────────────────────────┬────────────────────────────────┘
                         │  REST API
┌────────────────────────▼────────────────────────────────┐
│                   UYGULAMA KATMANI                      │
│                                                         │
│    ⚙️ Node.js / Express          🐍 Python Servisleri   │
│    🔐 Authentication             📦 Business Logic      │
│    🔔 Bildirim Servisi           📊 Analitik Servisi    │
└────────────────────────┬────────────────────────────────┘
                         │
┌────────────────────────▼────────────────────────────────┐
│                    VERİ KATMANI                         │
│                                                         │
│              🍃 MongoDB / SQL Database                  │
│   users · clinics · doctors · appointments              │
│       ratings · favorites · pharmacy                   │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ Teknoloji Yığını

<div align="center">

### 📱 Mobil Uygulama

[![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

### 🌐 Web Paneli

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

### ⚙️ Backend

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)

### 🗄️ Veritabanı

[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)]()

### 🔧 Geliştirme Araçları

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MedoraDev-BTU)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://postman.com)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com)

</div>

---

## 🧠 Yazılım Geliştirme Süreci

Projede **Agile (Çevik) Yazılım Geliştirme Metodolojisi** benimsenmiştir.

### Neden Agile?

Sağlık teknolojisi projeleri dinamik gereksinimler içerir. Agile metodolojisi sayesinde:

- **Hızlı adaptasyon** — Gereksinim değişikliklerine hızla uyum sağlanır
- **Sürekli teslim** — Her sprint sonunda çalışan bir ürün parçası ortaya çıkar
- **Şeffaf süreç** — Tüm paydaşlar ilerlemeyi anlık takip edebilir
- **Kalite odaklılık** — Sürekli test & iyileştirme kültürü benimsenir

### Çalışma Yöntemi

```
📌 Sprint Planlaması
        ↓
📝 Görev Dağılımı (Haftalık)
        ↓
💻 Paralel Ekip Geliştirmesi
        ↓
🔍 Code Review & Test
        ↓
🚀 Sprint Demo & Retrospektif
        ↓
🔁 Bir Sonraki Sprint
```

### Sprint Yapısı

| Adım | Açıklama |
|---|---|
| 📋 Planlama | Haftalık görevler ve öncelikler belirlenir |
| 💻 Geliştirme | Backend, Mobil ve Web ekipleri paralel çalışır |
| 🧪 Test | API testleri (Postman), UI testleri ve edge case kontrolleri |
| 🔄 Entegrasyon | Tüm modüller birleştirilir, çakışmalar giderilir |
| 📊 Değerlendirme | Sprint retrospektifi ile süreç iyileştirilir |

---

## 📅 Geliştirme Takvimi

| Hafta | Aşama | Açıklama | Durum |
|:---:|---|---|:---:|
| 1 | 🔍 Analiz & Planlama | User story'ler, wireframe, ER diagram, mimari belirleme | ✅ Tamamlandı |
| 2 | 🏗️ Altyapı & Kurulum | Auth yapısı, DB şeması, proje kurulumları, navigation | ✅ Tamamlandı |
| 3 | 🔧 Temel CRUD & API | Kullanıcı/klinik/doktor API'leri, ilişki kurulumu | 🔄 Devam Ediyor |
| 4 | 📅 Randevu Sistemi | Randevu oluşturma, saat hesaplama, durum yönetimi | 🔄 Devam Ediyor |
| 5 | 🔍 Filtreleme & Ek Özellikler | Konum/branş filtresi, favori & puanlama modülleri | 🔄 Devam Ediyor |
| 6 | 💊 Eczane & Test | Eczane modülü, API & UI testleri, performans iyileştirme | ⏳ Planlı |
| 7 | 🎉 Final & Demo | Demo senaryosu, sunum, son UI düzenlemeleri | ⏳ Planlı |

---

## 👥 Takım ve Görev Dağılımı

<div align="center">

### 👑 Ekip Lideri

| Fotoğraf | İsim | Öğrenci No | GitHub | Yetkinlikler & Görevler |
|:---:|:---:|:---:|:---:|---|
| <img src="https://avatars.githubusercontent.com/ahmetymtkn" width="60" style="border-radius:50%"/> | **Ahmet Yumutkan** | 22360859056 | [@ahmetymtkn](https://github.com/ahmetymtkn) | 👑 Ekip Lideri · Web · Mobil · Backend · Veri · Proje koordinasyonu |

</div>

<br/>

<table align="center">
<tr>

<td align="center" width="25%" valign="top">

### 📱 Mobil Takım
*React Native & Expo*

---

<img src="https://avatars.githubusercontent.com/ecemino" width="65" style="border-radius:50%"/><br/>
**Ece Açar**<br/>
`23360859042`<br/>
[@ecemino](https://github.com/ecemino)<br/>
<br/>
🔹 React Native geliştirme<br/>
🔹 Hasta ekranları<br/>
🔹 Randevu alma arayüzü<br/>
🔹 UI/UX tasarımı

---

<img src="https://avatars.githubusercontent.com/rumeysaersoyy" width="65" style="border-radius:50%"/><br/>
**Rumeysa Ersoy**<br/>
`22360859070`<br/>
[@rumeysaersoyy](https://github.com/rumeysaersoyy)<br/>
<br/>
🔹 React Native geliştirme<br/>
🔹 Filtreleme & arama<br/>
🔹 Favori & puan ekranları<br/>
🔹 Nöbetçi eczane ekranı

</td>

<td align="center" width="25%" valign="top">

### ⚙️ Backend Takım
*Node.js · Python · API*

---

<img src="https://avatars.githubusercontent.com/RetcapS" width="65" style="border-radius:50%"/><br/>
**Hüseyin Acar**<br/>
`23360859070`<br/>
[@RetcapS](https://github.com/RetcapS)<br/>
<br/>
🔹 Node.js / Express API<br/>
🔹 Randevu sistemi mantığı<br/>
🔹 Authentication servisi<br/>
🔹 API endpoint geliştirme

---

<img src="https://avatars.githubusercontent.com/nermnbycn" width="65" style="border-radius:50%"/><br/>
**Nermin Baycan**<br/>
`21360859019`<br/>
[@nermnbycn](https://github.com/nermnbycn)<br/>
<br/>
🔹 Node.js / Python servisleri<br/>
🔹 Business logic geliştirme<br/>
🔹 API test & dokümantasyon<br/>
🔹 Güvenlik katmanı

</td>

<td align="center" width="25%" valign="top">

### 🌐 Web Takım
*React · HTML/CSS*

---

<img src="https://avatars.githubusercontent.com/YunS16" width="65" style="border-radius:50%"/><br/>
**Yunus Emre Nallı**<br/>
`22360859079`<br/>
[@YunS16](https://github.com/YunS16)<br/>
<br/>
🔹 React web paneli<br/>
🔹 Klinik yönetim ekranları<br/>
🔹 İstatistik & analiz görünümü<br/>
🔹 Veri görselleştirme

---

<img src="https://avatars.githubusercontent.com/Rima2002" width="65" style="border-radius:50%"/><br/>
**Rima Farah Eleuch**<br/>
`21360859216`<br/>
[@Rima2002](https://github.com/Rima2002)<br/>
<br/>
🔹 React web geliştirme<br/>
🔹 Randevu onay paneli<br/>
🔹 Klinik & doktor formları<br/>
🔹 UI bileşenleri

</td>

<td align="center" width="25%" valign="top">

### 🗄️ Veri Takımı
*MongoDB · SQL*

---

<img src="https://avatars.githubusercontent.com/KaganEM16" width="65" style="border-radius:50%"/><br/>
**Kağan Emre Meral**<br/>
`23360859059`<br/>
[@KaganEM16](https://github.com/KaganEM16)<br/>
<br/>
🔹 MongoDB şema tasarımı<br/>
🔹 Web panel desteği<br/>
🔹 Backend entegrasyonu<br/>
🔹 Veri modelleme

---

<img src="https://avatars.githubusercontent.com/Javidaann" width="65" style="border-radius:50%"/><br/>
**Safarli Javidan**<br/>
`21360859227`<br/>
[@Javidaann](https://github.com/Javidaann)<br/>
<br/>
🔹 Veri tasarımı & analizi<br/>
🔹 MongoDB yönetimi<br/>
🔹 Sorgu optimizasyonu<br/>
🔹 Veri tutarlılığı

</td>

</tr>
</table>

### 📊 Görev Özet Tablosu

| Takım Üyesi | Web | Mobil | Backend | Veri | Rol |
|---|:---:|:---:|:---:|:---:|---|
| Ahmet Yumutkan | ✅ | ✅ | ✅ | ✅ | 👑 Ekip Lideri |
| Ece Açar | | ✅ | | | 📱 Mobil Geliştirici |
| Rumeysa Ersoy | | ✅ | | | 📱 Mobil Geliştirici |
| Hüseyin Acar | | | ✅ | | ⚙️ Backend Geliştirici |
| Nermin Baycan | | | ✅ | | ⚙️ Backend Geliştirici |
| Yunus Emre Nallı | ✅ | | | ✅ | 🌐 Web & Veri |
| Rima Farah Eleuch | ✅ | | | | 🌐 Web Geliştirici |
| Kağan Emre Meral | ✅ | | ✅ | ✅ | 🗄️ Full-stack & Veri |
| Safarli Javidan | | | | ✅ | 🗄️ Veri Uzmanı |

---

## 🗄️ Veritabanı Tasarımı

Sistemde kullanılan temel tablolar ve ilişkiler:

```
users ──────────────────────────────────────────┐
  ├── id, name, email, password, phone, location │
  └──────────────────────────────────────────────┤
                                                 │ 1:N
clinics ────────────────── doctors ─────────── appointments
  ├── id, name, address       ├── id, name         ├── id
  ├── phone, rating           ├── branch           ├── user_id ──► users
  └── working_hours           ├── clinic_id ──►    ├── doctor_id ──► doctors
                              └── schedule         ├── date, time
                                                   └── status

ratings ──► appointments       favorites ──► (users × clinics/doctors)
pharmacy ──► location-based
```

**Temel İlişkiler:**
- Bir klinik → birden fazla doktor
- Bir kullanıcı → birden fazla randevu
- Bir randevu → bir kullanıcı + bir doktor
- Bir kullanıcı → birden fazla favori & puan

---

## ⚠️ Risk Analizi

| Risk | Olasılık | Etki | Önlem |
|---|:---:|:---:|---|
| 🔀 Randevu çakışmaları | Orta | Yüksek | Backend'de çakışma kontrolü, time-slot lock mekanizması |
| ⚡ API performans sorunları | Düşük | Orta | Cache katmanı, sorgu optimizasyonu, load testing |
| 🗄️ Veritabanı tutarsızlıkları | Düşük | Yüksek | Transaction yönetimi, validasyon katmanları |
| ⏰ Zaman planına uyulamaması | Orta | Orta | Haftalık sprint takibi, MVP önceliklendirme |
| 🔐 Güvenlik açıkları | Düşük | Yüksek | JWT auth, input validation, HTTPS zorunluluğu |

---

## 📖 Kullanım Kılavuzu

### 👤 Hasta — Mobil Uygulama

```
1️⃣  Kayıt Ol / Giriş Yap
         ↓
2️⃣  Konumuna Göre Klinik Ara
    (Branş, ilçe veya isimle filtrele)
         ↓
3️⃣  Doktor Profilini İncele
    (Uzmanlık, puan, yorumlar)
         ↓
4️⃣  Müsait Saatleri Gör
         ↓
5️⃣  Randevu Oluştur
         ↓
6️⃣  Onay Bildirimini Bekle
         ↓
7️⃣  Randevunu Takip Et
         ↓
8️⃣  Tamamlanan Randevuyu Değerlendir ⭐
```

### 🏥 Klinik — Web Paneli

```
1️⃣  Klinik Hesabı Oluştur / Giriş Yap
         ↓
2️⃣  Klinik Bilgilerini Düzenle
    (Adres, çalışma saatleri, branşlar)
         ↓
3️⃣  Doktor Ekle & Yönet
         ↓
4️⃣  Gelen Randevu Taleplerini İncele
         ↓
5️⃣  Randevuyu Onayla / İptal / Ertele
         ↓
6️⃣  İstatistikleri & Puanlamaları Takip Et
```

### 💊 Nöbetçi Eczane

Mobil uygulamada ana menüden **"Nöbetçi Eczane"** sekmesine giderek konumunuza en yakın nöbetçi eczaneleri görüntüleyebilirsiniz.

---

## 🤝 Katkı Sağlama

Medora açık kaynak katkılarına açıktır! Geliştirici topluluğunu projeye davet ediyoruz.

### 📦 Repolarımız

Projeye katkı sağlamak istediğiniz alana göre ilgili repoyu seçin:

| Repo | Açıklama | Link |
|---|---|:---:|
| 📱 **Medora-Mobile** | React Native / Expo hasta uygulaması | [→ Repo](https://github.com/MedoraDev-BTU/Medora-Mobile) |
| 🌐 **Medora-Web** | React tabanlı klinik web paneli | [→ Repo](https://github.com/MedoraDev-BTU/Medora-Web) |
| ⚙️ **Medora-Backend** | Node.js / migration dosyaları | [→ Repo](https://github.com/MedoraDev-BTU/Medora-Backend) |
| 🗄️ **Medora-DB** | Veritabanı şemaları / Python API servisleri | [→ Repo](https://github.com/MedoraDev-BTU/Medora-DB) |

### Nasıl Katkı Sağlarsınız?

```bash
# 1. İlgili repoyu fork edin
git clone https://github.com/MedoraDev-BTU/Medora-Mobile

# 2. Feature branch oluşturun
git checkout -b feature/yeni-ozellik

# 3. Değişikliklerinizi commit edin
git commit -m "feat: yeni özellik eklendi"

# 4. Branch'inizi push edin
git push origin feature/yeni-ozellik

# 5. Pull Request açın
```

### Katkı Alanları

- 🐛 **Bug Fix** — Tespit ettiğiniz hataları düzeltin
- ✨ **Yeni Özellik** — Yeni modüller veya iyileştirmeler önerin
- 📝 **Dokümantasyon** — README, API docs, kod yorumları
- 🌍 **Çoklu Dil Desteği** — Farklı dil lokalizasyonları
- 🎨 **UI/UX** — Arayüz iyileştirmeleri ve yeni tasarımlar
- 🧪 **Test** — Unit test, integration test yazımı

---

## 💰 Yatırım ve Destek

### 📈 Yatırımcılar İçin

Medora, Türkiye'nin büyüyen **dijital sağlık (healthtech)** ekosistemine yönelik güçlü bir çözümdür.

- 🏥 **Pazar:** Yüz binlerce özel klinik ve milyonlarca hasta potansiyeli
- 📱 **Ölçeklenebilir:** Modüler yapı ile farklı sağlık segmentlerine genişleme imkânı
- 💡 **İnovasyon:** Yapay zeka destekli öneri sistemleri yol haritada
- 🌍 **Uluslararasılaşma:** MENA bölgesi ve Avrupa pazarlarına açılım hedefi

> 📩 Yatırım görüşmeleri için: **ymtknahmet@gmail.com**

### 🤝 Destekçiler & Bağışçılar İçin

Projenin gelişimine katkı sağlamak isteyenler için çeşitli destek seçenekleri mevcuttur:

- ☕ **Küçük Destek** — Geliştirme altyapı maliyetleri
- 🚀 **Büyük Destek** — Sunucu, API ve özellik geliştirme hızlandırma
- 🏆 **Stratejik Ortaklık** — Co-branding ve özel entegrasyon imkânı

> 📩 Destek & iş birliği için: **ymtknahmet@gmail.com**

### 🌟 Bize Destek Olmanın En Kolay Yolu

Bu repoyu ⭐ **star**'layın ve çevrenizle paylaşın!

---

## 📢 Bağlantılar

<div align="center">

| Platform | Link |
|:---:|:---:|
| 🐙 GitHub Organizasyonu | [github.com/MedoraDev-BTU](https://github.com/MedoraDev-BTU) |
| 📧 İletişim | ymtknahmet@gmail.com |

</div>

---

## 🎓 Akademik Bilgi

<div align="center">

**Bursa Teknik Üniversitesi**  
Mühendislik ve Doğa Bilimleri Fakültesi · Bilgisayar Mühendisliği Bölümü  
*Yazılım Mühendisliği Dersi — Takım 5 Projesi*

| Öğrenci No | Ad Soyad |
|:---:|:---:|
| 22360859056 | Ahmet Yumutkan |
| 23360859042 | Ece Açar |
| 23360859059 | Kağan Emre Meral |
| 23360859070 | Hüseyin Acar |
| 21360859019 | Nermin Baycan |
| 22360859079 | Yunus Emre Nallı |
| 22360859070 | Rumeysa Ersoy |
| 21360859216 | Rima Farah Eleuch |
| 21360859227 | Safarli Javidan |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c2a8,50:1a7fbf,100:0f4c81&height=120&section=footer&animation=fadeIn" width="100%"/>

**✨ Medora ile sağlıkta dijital dönüşüm başlıyor ✨**


</div>
