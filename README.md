# 🌲 Picnic Area Reservation System | Piknik ve Mesire Alanı Rezervasyon Sistemi

[🇬🇧 Read in English](#english) | [🇹🇷 Türkçe okumak için tıklayın](#türkçe)

---

## <a id="english"></a> 🇬🇧 English

A modern, full-stack reservation platform designed for municipalities and private facilities. This system allows users to seamlessly book specific picnic tables or areas using an interactive map, complete with SMS verification, dynamic pricing, and a secure admin dashboard.

> **🔒 Note on Source Code:** This repository serves as a showcase/portfolio piece. The core source code is kept private due to commercial rights and strict data security policies. The full architecture and codebase can be gladly demonstrated during technical interviews upon request.

### 🎥 System Preview & Workflow

#### 1. Interactive Booking Flow (Homepage)
Users can easily navigate the homepage, select their desired facility, pick a date, and choose a specific picnic area directly from the interactive map.
![Booking Flow](<img width="800" height="458" alt="EkranKayd2026-07-14104457-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/d22551ea-7091-467d-9bb7-d92d71d0a50d" />
)

#### 2. Admin Dashboard & Analytics
The comprehensive admin dashboard provides real-time insights, revenue analytics, and an overview of active/pending reservations.
![Admin Dashboard](<img width="800" height="406" alt="EkranKayd2026-07-14104547-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/b63b04bc-faad-4d77-b091-c801cebfd6f7" />
)

#### 3. Live Map Editor & Pricing Setup (Admin)
Admins can dynamically draw new picnic areas (polygons) directly on the map, set capacity limits, define amenities, and configure base pricing.
![Map Editor](<img width="800" height="402" alt="EkranKayd2026-07-14104745-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/75695819-6c36-4cee-9b89-271ea6421fb1" />
)

#### 4. Live Frontend View of Added Areas
Instantly after an admin creates a new area, it becomes live and bookable on the frontend interactive map for the customers.
![Live Area View](<img width="800" height="460" alt="EkranKayd2026-07-14104852-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/cb8d2025-ce9d-484a-82a0-1eeaa66eda04" />
)

### 💻 Tech Stack
**Frontend:** Next.js (App Router), React, Tailwind CSS, Shadcn UI  
**Backend:** Next.js Server Actions, Prisma ORM, SQLite  
**Mapping:** Leaflet, React-Leaflet, Nominatim API  

---

## <a id="türkçe"></a> 🇹🇷 Türkçe

Belediyeler ve özel mesire alanları için tasarlanmış modern, tam kapsamlı bir rezervasyon platformu. Kullanıcıların interaktif bir harita üzerinden belirli piknik masalarını veya alanlarını rezerve etmelerini, SMS doğrulama ve sanal POS entegrasyonu ile işlemlerini güvenle tamamlamalarını sağlar.

> **🔒 Kaynak Kod Hakkında Not:** Bu depo bir portfolyo vitrini olarak hizmet vermektedir. Ticari haklar ve katı veri güvenliği politikaları nedeniyle temel kaynak kod gizli (Private) tutulmaktadır. Sistem mimarisi ve kod yapısı, talep edildiği takdirde teknik mülakatlarda memnuniyetle sunulacaktır.

### 🎥 Sistem İşleyişi ve Önizleme

#### 1. İnteraktif Rezervasyon Akışı (Ana Sayfa)
Kullanıcıların ana sayfa üzerinden tesis seçimi yapması, tarih belirlemesi ve interaktif harita üzerinden istediği masayı/alanı rezerve etme süreci.
![Ana Sayfa Akışı](<img width="800" height="458" alt="EkranKayd2026-07-14104457-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/decca0db-15d5-4ae0-8aa9-864e1e4506f0" />
)

#### 2. Admin Yönetim Paneli ve İstatistikler
Gerçek zamanlı gelir analizleri, aktif alanların durumu ve bekleyen rezervasyonların takip edildiği kapsamlı yönetim paneli (Dashboard).
![Admin Paneli](<img width="800" height="406" alt="EkranKayd2026-07-14104547-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/48aeb131-331d-4053-8e64-9fe3810460ef" />
)

#### 3. Canlı Harita Editörü ve Tesis Ekleme (Admin)
Yöneticinin doğrudan harita üzerinde poligon çizerek yeni piknik alanları oluşturması; kapasite, özellik ve fiyatlandırmaları dinamik olarak ayarlaması.
![Harita Editörü](<img width="800" height="402" alt="EkranKayd2026-07-14104745-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/0c6ab7e4-1589-48b0-bb2a-e1bfaaf5b6b7" />
)

#### 4. Eklenen Alanın Ana Sayfada Canlı Görünümü
Admin panelinden eklenen yeni bölgenin, anında müşteri arayüzündeki interaktif haritaya yansıması ve rezerve edilebilir hale gelmesi.
![Yeni Alan Görünümü](<img width="800" height="460" alt="EkranKayd2026-07-14104852-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/6b336fc1-f7b9-427a-88df-aebb03763074" />
)

### 💻 Kullanılan Teknolojiler
**Frontend:** Next.js (App Router), React, Tailwind CSS, Shadcn UI  
**Backend:** Next.js Server Actions, Prisma ORM, SQLite  
**Harita & Konum:** Leaflet, React-Leaflet, Nominatim API  

---
*Developed by Emre Akat*
