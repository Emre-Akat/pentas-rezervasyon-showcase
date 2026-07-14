# 🌲 Picnic Area Reservation System | Piknik ve Mesire Alanı Rezervasyon Sistemi

[🇬🇧 Read in English](#english) | [🇹🇷 Türkçe okumak için tıklayın](#türkçe)

---

## <a id="english"></a> 🇬🇧 English

A modern, full-stack reservation platform designed for municipalities and private facilities. This system allows users to seamlessly book specific picnic tables or areas using an interactive map, complete with SMS verification, dynamic pricing, and a secure admin dashboard.

> **🔒 Note on Source Code:** This repository serves as a showcase/portfolio piece. The core source code is kept private due to commercial rights and strict data security policies. The full architecture and codebase can be gladly demonstrated during technical interviews upon request.

### 🎥 System Preview & Workflow

#### 1. Interactive Booking Flow (Homepage)
Users can easily navigate the homepage, select their desired facility, pick a date, and choose a specific picnic area directly from the interactive map.
<img width="800" height="458" alt="Booking Flow" src="https://github.com/user-attachments/assets/9e297601-bb5c-465c-8c93-9f00f94fdc61" />

#### 2. Admin Dashboard & Analytics
The comprehensive admin dashboard provides real-time insights, revenue analytics, and an overview of active/pending reservations.
<img width="800" height="406" alt="Admin Dashboard" src="https://github.com/user-attachments/assets/6b01ed16-326c-4b50-a023-21242b684d48" />

#### 3. Live Map Editor & Pricing Setup (Admin)
Admins can dynamically draw new picnic areas (polygons) directly on the map, set capacity limits, define amenities, and configure base pricing.
<img width="800" height="402" alt="Map Editor" src="https://github.com/user-attachments/assets/dac1e8d5-0b3f-481c-a2e7-df4a839955c8" />

#### 4. Live Frontend View of Added Areas
Instantly after an admin creates a new area, it becomes live and bookable on the frontend interactive map for the customers.
<img width="800" height="460" alt="Live Area View" src="https://github.com/user-attachments/assets/4a4d119d-7985-4e8f-b99c-9a285702f4d3" />

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
![Ana Sayfa Akışı](https://github.com/user-attachments/assets/decca0db-15d5-4ae0-8aa9-864e1e4506f0)

#### 2. Admin Yönetim Paneli ve İstatistikler
Gerçek zamanlı gelir analizleri, aktif alanların durumu ve bekleyen rezervasyonların takip edildiği kapsamlı yönetim paneli (Dashboard).
![Admin Paneli](https://github.com/user-attachments/assets/48aeb131-331d-4053-8e64-9fe3810460ef)

#### 3. Canlı Harita Editörü ve Tesis Ekleme (Admin)
Yöneticinin doğrudan harita üzerinde poligon çizerek yeni piknik alanları oluşturması; kapasite, özellik ve fiyatlandırmaları dinamik olarak ayarlaması.
![Harita Editörü](https://github.com/user-attachments/assets/0c6ab7e4-1589-48b0-bb2a-e1bfaaf5b6b7)

#### 4. Eklenen Alanın Ana Sayfada Canlı Görünümü
Admin panelinden eklenen yeni bölgenin, anında müşteri arayüzündeki interaktif haritaya yansıması ve rezerve edilebilir hale gelmesi.
![Yeni Alan Görünümü](https://github.com/user-attachments/assets/6b336fc1-f7b9-427a-88df-aebb03763074)

### 💻 Kullanılan Teknolojiler
**Frontend:** Next.js (App Router), React, Tailwind CSS, Shadcn UI  
**Backend:** Next.js Server Actions, Prisma ORM, SQLite  
**Harita & Konum:** Leaflet, React-Leaflet, Nominatim API  

---
*Developed by Emre Akat*
