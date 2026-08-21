# 🏮 Lentera Pasar — Template Website Etalase Publik UMKM

Repository ini berisi kumpulan kode sumber **Template Website Etalase Publik (Multi-Page)** siap pakai yang dirancang khusus untuk 5 bidang utama pelaku UMKM di ekosistem platform **Lentera Pasar**.

Setiap template dibangun dengan standar **UI/UX Modern, Mobile-First, Fast-Loading, dan Conversion-Focused**, terintegrasi langsung dengan fitur pemesanan instan WhatsApp (*Direct WhatsApp Booking*) serta siap dihubungkan ke Admin Panel & Meta Ads Engine Lentera Pasar.

---

## 🏛️ Arsitektur 5 Bidang Utama UMKM

```text
template-website-umkm/
│
├── 📁 01-fnb-kuliner/                   # [SELESAI - 12 Sub-Bidang Lengkap]
│   ├── fnb-ricebowl-pop/               # Makanan Berat / Rice Bowl / Dine-in (Mangkok Juara)
│   ├── fnb-coffee-dark/                # Kopi & Specialty Coffee Roastery (Obsidian Coffee)
│   ├── fnb-catering-clean/             # Katering Harian, Bento & Tumpeng (Sedap Laras)
│   ├── fnb-dessert-pastel/             # Dessert, Es Krim & Gelato (Gelato Velveto)
│   ├── fnb-frozen-clean/               # Frozen Food Siap Masak & Dimsum (Sedap Beku Nusantara)
│   ├── fnb-snack-crunchy/              # Snack Kering & Keripik Oleh-Oleh (Kriuk Juara)
│   ├── fnb-sambal-nusantara/           # Sambal Kemasan & Bumbu Masak (Sambal Warisan Oma)
│   ├── fnb-meat-butcher/               # Daging / Seafood Olahan & BBQ Grill (Prime Cuts Artisan)
│   ├── fnb-bakery-artisan/             # Bakery, Roti Sobek & Sourdough Pastry (Le Levain Bakery)
│   ├── fnb-cake-celebration/           # Cake, Tart & Kue Ulang Tahun Mewah (Aurélia Cake Atelier)
│   ├── fnb-healthy-diet/               # Makanan Sehat, Diet & Salad Organik (Verdant Health Lab)
│   └── fnb-tradisional-tampah/         # Jajanan Pasar & Kue Tampah Basah (Tampah Ayu Nusantara)
│
├── 📁 02-fashion-skincare/             # [BIDANG 2 - Fashion & Skincare]
│   ├── skincare-clinical-lab/          # Skincare Clinical Lab & Derm-Cosmetics BPOM (Aetheria Lab)
│   ├── makeup-glam-studio/             # Kosmetik & Make-up Dekoratif Runway Glam (Velvet Runway)
│   ├── perfume-luxury-atelier/         # Parfum, Wewangian & Extrait Dark Luxury (Noir Sillage)
│   ├── fashion-muslim-gamis/           # Hijab, Gamis Syar'i & Abaya Modern
│   ├── fashion-streetwear-apparel/     # Kaos Distro, Hoodie & Urban Oversize
│   ├── fashion-batik-etnik/            # Batik Tulis/Cap, Tenun & Kebaya Modern
│   ├── fashion-kids-baby/              # Pakaian Anak, Bayi & Perlengkapan Ibu
│   ├── fashion-footwear-shoes/         # Sepatu Lokal Kulit, Sneakers & Sandal
│   ├── beauty-skincare-serum/          # Skincare Glowing, Serum & Sunscreen BPOM
│   └── beauty-bodycare-herbal/         # Sabun Organik, Body Scrub & Lulur Alami
│
├── 📁 03-ritel-gadget-hobi/            # [BIDANG 3 - Segera Hadir]
│   ├── gadget-phone-accessories/       # Case Hp, TWS, Charger & Gadget Acc
│   ├── hobby-plant-monstera/           # Tanaman Hias, Pot Keramik & Pupuk Urban
│   ├── hobby-aquatic-aquascape/        # Ikan Hias, Aquascape & Pakan Hewan
│   ├── hobby-diecast-actionfigure/     # Komunitas Diecast, Model Kit & Mainan Hobi
│   ├── auto-care-motorcycle/           # Perawatan Motor/Mobil & Detailing Kit
│   └── sport-active-gym/               # Jersey Olahraga, Botol Tumbler & Matras Yoga
│
├── 📁 04-kriya-dekorasi/               # [BIDANG 4 - Segera Hadir]
│   ├── kriya-rotan-anyaman/            # Furniture Rotan, Keranjang & Tas Anyam
│   ├── kriya-keramik-pottery/          # Mug Keramik Handmade, Piring & Vas Estetik
│   ├── kriya-leather-goods/            # Dompet Kulit Nabati, Sabuk & Pouch Custom
│   ├── decor-wooden-home/              # Talenan Kayu Jati, Hiasan Dinding & Rak
│   └── decor-candle-scented/           # Lilin Aromaterapi Soywax & Home Fragrance
│
└── 📁 05-supplier-grosir-b2b/          # [BIDANG 5 - Segera Hadir]
    ├── b2b-packaging-box/              # Dus Box Makanan, Paper Bag & Kemasan Sablon
    ├── b2b-bahan-kue-resto/            # Supplier Tepung, Mentega, Cokelat & Syrup
    ├── b2b-konveksi-kaos-polos/        # Grosir Kaos Polos Combed, Bordir & Sablon
    ├── b2b-frozen-horeca/              # Supplier Frozen Daging Resto, Hotel & Kafe
    └── b2b-sembako-distributor/        # Distributor Beras, Minyak Goreng & Gula Pasir
```

---

## 🌟 Fitur Utama Setiap Template

- **🎨 Multi-Design Archetype (Non-Bento Grid)**: Desain khusus yang disesuaikan dengan psikologi visual tiap niche industri (Bold Pop, Dark Industrial, Clean Minimalist, Warm Artisan, French Luxury Boutique, Scandinavian Health, Warm Heritage).
- **📱 100% Mobile-Responsive**: Tampilan responsif sempurna di semua perangkat (Smartphone, Tablet, Laptop, Desktop).
- **⚡ Direct WhatsApp Checkout & Order Compiler**: Form dan customizer pesanan secara otomatis menyusun pesan WhatsApp rapi ke Admin / Customer Service.
- **🏷️ Interactive Product Customizer**: Pilihan varian rasa, diameter kue, level pedas, ukuran kemasan, porsi, kalkulator kuantitas/harga otomatis, serta link toko marketplace (Shopee, Tokopedia, TikTok Shop).
- **🔍 Live Search & Category Filtering**: Filter instan tanpa reload halaman dan pengurutan kategori dinamis.
- **🏮 Sticky Demo & Sales Bar**: Komponen promosi terpadu Lentera Pasar yang menempel di bagian bawah layar (`fixed bottom-4`).
- **💬 Floating WhatsApp Call-to-Action**: Tombol aksi cepat WhatsApp melayang dengan ping animation (`fixed bottom-24`).
- **🚀 SEO-Ready & Semantic HTML5**: Struktur heading hierarchy yang rapi, meta description, Open Graph ready, dan performa tinggi.

---

## 📂 Bidang 1: F&B / Kuliner (12 Niche Lengkap)

| No | Folder Path | Niche / Sub-Bidang | Brand Demo | Visual Archetype & Style |
|:---:|:---|:---|:---|:---|
| 1 | `01-fnb-kuliner/fnb-ricebowl-pop/` | Makanan Berat / Rice Bowl / Dine-in | **Mangkok Juara** | *Bold & Vibrant Food Pop* (Kuning, Merah, Charcoal) |
| 2 | `01-fnb-kuliner/fnb-coffee-dark/` | Kopi & Specialty Coffee Roastery | **Obsidian Coffee** | *Dark Industrial & Modern Coffee* (Dark Slate, Warm Gold) |
| 3 | `01-fnb-kuliner/fnb-catering-clean/` | Katering Harian, Bento & Tumpeng | **Sedap Laras** | *Clean Minimalist & Trustworthy* (Fresh Green, Clean White) |
| 4 | `01-fnb-kuliner/fnb-dessert-pastel/` | Dessert, Es Krim & Gelato | **Gelato Velveto** | *Soft Pastel & Playful Elegance* (Pastel Pink, Cream Berry) |
| 5 | `01-fnb-kuliner/fnb-frozen-clean/` | Frozen Food Siap Masak & Dimsum | **Sedap Beku Nusantara** | *Clean Frozen & Fresh Trust* (Frost Cyan, Clean White) |
| 6 | `01-fnb-kuliner/fnb-snack-crunchy/` | Snack Kering & Keripik Oleh-Oleh | **Kriuk Juara** | *Energetic Crunchy & Snack Delight* (Golden Yellow, Fiery Orange) |
| 7 | `01-fnb-kuliner/fnb-sambal-nusantara/` | Sambal & Bumbu Masak Kemasan | **Sambal Warisan Oma** | *Fiery Red & Heritage Nusantara* (Chili Red, Warm Terracotta) |
| 8 | `01-fnb-kuliner/fnb-meat-butcher/` | Daging / Seafood Olahan & BBQ Grill | **Prime Cuts Artisan** | *Dark Butcher & Premium Steakhouse* (Charcoal, Ruby Red) |
| 9 | `01-fnb-kuliner/fnb-bakery-artisan/` | Bakery, Roti Sobek & Sourdough Pastry | **Le Levain Bakery** | *Warm Earthy & French Artisan* (Warm Butter, Toasted Crust) |
| 10 | `01-fnb-kuliner/fnb-cake-celebration/` | Cake, Tart & Kue Ulang Tahun Mewah | **Aurélia Cake Atelier** | *Editorial Magazine & Luxury Boutique* (Champagne, Plum Velvet, Gold) |
| 11 | `01-fnb-kuliner/fnb-healthy-diet/` | Makanan Sehat, Diet & Salad Organik | **Verdant Health Lab** | *Clean Scandinavian Health* (Sage Green, Leaf Emerald, Pure Snow) |
| 12 | `01-fnb-kuliner/fnb-tradisional-tampah/` | Jajanan Pasar & Kue Tampah Basah | **Tampah Ayu Nusantara** | *Warm Heritage & Festive Nusantara* (Banana Leaf Green, Bamboo Wood) |

---

## 📑 Struktur Halaman Multi-Page per Template

Setiap template memiliki 6 file HTML mandiri:

1. `index.html` — **Beranda Utama**: Hero section spesifik niche, Value proposition strip, Highlight produk terlaris, Peta rasa/kategori, Testimoni pelanggan, Footer, Floating WhatsApp (`bottom-24`), dan Sticky Demo Bar (`bottom-4`).
2. `katalog.html` — **Katalog Lengkap**: Daftar seluruh menu/produk dengan *live search*, filter kategori tombol dinamis, badge atribut, dan tombol pesan instan WA.
3. `detail.html` — **Detail Produk & Kustomisasi**: Galeri multi-angle foto, customizer varian/diameter/level/gramasi, kalkulator harga otomatis, dan *WhatsApp Order Compiler*.
4. `tentang.html` — **Profil & Cerita Brand**: Sejarah brand, filosofi bahan baku, standar dapur higienis, sertifikasi Halal / P-IRT, dan profil chef/petani mitra.
5. `kontak.html` — **Pusat Pemesanan & Pengiriman**: Jadwal layanan (termasuk pengiriman subuh / car-chill AC), info outlet/dapur, form pemesanan interaktif via WA, dan peta lokasi.
6. `artikel.html` — **Edukasi & Jurnal Niche**: Kumpulan artikel tips praktis, panduan penyimpanan, sains nutrisi, atau filosofi tradisi.

---

## 🛠️ Tech Stack & Standar Koding

- **HTML5** (Struktur Semantik, SEO Tags & Aksesibilitas)
- **Tailwind CSS CDN** (Modern Utility-First CSS Framework dengan Custom Extended Palette)
- **Google Fonts** (Plus Jakarta Sans, Playfair Display, Cormorant Garamond, Outfit, Inter)
- **Font Awesome 6.5.1** & **Lucide SVG Icons**
- **Vanilla JavaScript** (State Management, Quantity Stepper, Dynamic Price Calculator, Live Search, WA URL Encoder)
- **Zero Heavy Dependencies** (Sangat ringan, instan loading tanpa proses build yang rumit)

---

## 🚀 Cara Menjalankan Template Secara Lokal

1. **Buka folder template pilihan di workspace**:
   ```bash
   cd 01-fnb-kuliner/fnb-tradisional-tampah
   ```

2. **Jalankan via Live Server (VS Code / Browser)**:
   - Buka file `index.html` langsung di browser Chrome / Firefox / Edge, atau
   - Gunakan extension **"Live Server"** di VS Code untuk *hot-reloading*.

---

## 💼 Tentang Lentera Pasar

**Lentera Pasar** adalah platform digitalisasi UMKM Indonesia yang menyediakan solusi menyeluruh:
- 🌐 **Website Etalase Publik** yang cepat, responsif, dan konversi tinggi.
- ⚙️ **Admin Panel Mandiri** untuk kelola katalog, stok, dan harga tanpa perlu paham koding.
- 📈 **Jasa Pengelolaan Iklan Digital (Meta Ads & TikTok Ads)** yang ditangani tim profesional berpengalaman.

---

## 📄 Lisensi & Hak Cipta

&copy; 2026 **Lentera Pasar** & **Tech Journey Mad People**. Seluruh hak cipta dilindungi undang-undang.
