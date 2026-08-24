# 🏮 Lentera Pasar — Template Website Etalase Publik UMKM

Repository ini berisi kumpulan kode sumber **Template Website Etalase Publik (Multi-Page)** siap pakai yang dirancang khusus untuk 6 bidang utama pelaku UMKM di ekosistem platform **Lentera Pasar**.

Setiap template dibangun dengan standar **UI/UX Modern, Mobile-First, Fast-Loading, dan Conversion-Focused**, terintegrasi langsung dengan fitur pemesanan instan WhatsApp (*Direct WhatsApp Booking*) serta siap dihubungkan ke Admin Panel & Meta Ads Engine Lentera Pasar.

---

## 🏛️ Arsitektur 6 Bidang Utama UMKM (Group A, B, C)

```text
template-website-umkm/
│
├── 📁 01-fnb-kuliner/                      # [12 Sub-Bidang Lengkap]
│   ├── [Group A: Makanan Siap Saji & Olahan Ringan]
│   │   ├── fnb-ricebowl-pop/              # Makanan Berat / Rice Bowl / Dine-in (Mangkok Juara)
│   │   ├── fnb-frozen-clean/              # Frozen Food Siap Masak & Dimsum (BekuRasa)
│   │   ├── fnb-snack-crunchy/             # Snack Kering & Keripik Oleh-Oleh (KriukNusantara)
│   │   ├── fnb-sambal-nusantara/          # Sambal Kemasan & Bumbu Masak (UlegJuara)
│   ├── [Group B: Minuman, Kopi & Minuman Sehat]
│   │   ├── fnb-coffee-dark/               # Kopi & Specialty Coffee Roastery (Obsidian Coffee)
│   │   ├── fnb-catering-clean/            # Katering Harian, Bento & Diet (Sedap Laras)
│   │   ├── fnb-dessert-pastel/            # Dessert, Es Krim & Gelato (Gelato Velveto)
│   │   ├── fnb-meat-butcher/              # Daging / Seafood Olahan & BBQ Grill (WagyuPrime Butcher)
│   └── [Group C: Roti, Kue & Makanan Khusus]
│       ├── fnb-bakery-artisan/            # Bakery, Roti Sobek & Sourdough Pastry (Le Pain Artisan)
│       ├── fnb-cake-celebration/          # Cake, Tart & Kue Ulang Tahun Mewah (L'Amour Patisserie)
│       ├── fnb-healthy-diet/              # Makanan Sehat, Diet & Salad Organik (Nourish Botanica)
│       └── fnb-tradisional-tampah/        # Jajanan Pasar & Kue Tampah Basah (Tampah Nyai Warisan)
│
├── 📁 02-fashion-skincare/                 # [13 Sub-Bidang Lengkap]
│   ├── [Group A: Busana & Apparel]
│   │   ├── fashion-casual-minimal/        # Pakaian Kasual Minimalis Pria & Wanita (ATELIER NORD)
│   │   ├── fashion-modest-editorial/      # Modest Wear, Gamis Syar'i & Sarimbit (ZAYRA Modest)
│   │   ├── fashion-kids-pastel/           # Pakaian Anak, Balita & Bayi SNI (Little Blossom)
│   │   ├── fashion-activewear-kinetic/    # Pakaian Olahraga & Activewear (KINETIC Performance)
│   │   ├── fashion-loungewear-cozy/       # Piyama Sutra, Daster & Loungewear (COZY HAVEN Silk)
│   ├── [Group B: Perawatan Tubuh & Kecantikan]
│   │   ├── skincare-clinical-lab/         # Skincare Clinical Lab & BPOM (DERMACEUTICAL Lab)
│   │   ├── makeup-glam-studio/            # Kosmetik & Make-up Runway Glam (LUMINOUS Glam Studio)
│   │   ├── perfume-luxury-atelier/        # Parfum & Wewangian Dark Luxury (NOCTURNE Parfums)
│   │   └── bodycare-botanical-spa/        # Sabun Organik & Perawatan Tubuh (BOTANICA Rituals)
│   └── [Group C: Alas Kaki & Pelengkap Busana]
│       ├── footwear-sneakers-street/      # Sneakers Urban Streetwear & Sandal (KICKS VAULT Co.)
│       ├── bags-leather-atelier/          # Tas Ransel Laptop & Dompet Kulit (HERITAGE HIDE Leather)
│       ├── accessories-modern-optics/     # Kacamata UV400 & Sabuk Kulit (LUMEN Optics & Accs)
│       └── jewelry-timepiece-luxury/      # Jam Tangan Kaca Safir & Perhiasan (AURELIA Fine Jewelry)
│
├── 📁 03-ritel-gadget-hobi/                # [12 Sub-Bidang Lengkap]
│   ├── [Group A: Elektronik & Aksesoris Device]
│   │   ├── gadget-mobile-tech/            # Aksesoris HP, Charger GaN 65W & TWS (NEXUS Mobile Tech)
│   │   ├── gaming-peripherals-studio/     # Mechanical Keyboard & Desk Setup (APEX GEAR Studio)
│   │   ├── tools-hardware-pro/            # Perkakas Tukang & Bor Cordless 20V (TITAN WORKPRO)
│   │   ├── moto-garage-accessories/       # Holder HP Anti-Getar & Aksesoris Motor (APEX MOTO GARAGE)
│   ├── [Group B: Hobi, Olahraga & Outdoor]
│   │   ├── outdoor-camping-expedition/    # Tenda Badai PU 3000mm & Carrier (TERRA EXPEDITION)
│   │   ├── fitness-gym-gear/              # Dumbbell Rubber & Matras Yoga TPE (IRONFIT ATHLETICS)
│   │   ├── hobby-collector-vault/         # Gunpla, Nendoroid & Display Akrilik (VALKYRIE HOBBY VAULT)
│   │   ├── music-audio-studio/            # Gitar Akustik Solid & Aksesoris Audio (SONIC WAVE Audio)
│   └── [Group C: Kebutuhan Rumah & Hobi Hijau]
│       ├── pet-care-haven/                # Pakan Kucing/Anjing & Pasir Anabul (FURRY HAVEN PETS)
│       ├── plants-botanical-greenhouse/   # Tanaman Hias Monstera & Pot Terakota (TERRA BOTANICA)
│       ├── stationery-aesthetic-desk/     # Jurnal 120 GSM & Alat Tulis Estetik (PAPYRUS STUDIO)
│       └── baby-montessori-play/          # Mainan Kayu Montessori & Teether Bayi (LITTLE ROOTS Montessori)
│
├── 📁 04-kriya-dekorasi/                   # [12 Sub-Bidang Lengkap]
│   ├── [Group A: Furnitur & Dekorasi Ruang]
│   │   ├── furniture-teak-artisan/        # Mebel Jati Solid Japandi Living (KAYU JATI STUDIO)
│   │   ├── ceramics-clay-pottery/         # Keramik Tembikar & Tableware Handmade (TERRA KILN Studio)
│   │   ├── wall-decor-bohemian/           # Hiasan Dinding, Cermin & Makrame (BOHO VIBE Home)
│   │   ├── home-textiles-cushion/         # Karpet Tenun & Bantal Sofa Cushion (NORDIC TEXTILES)
│   ├── [Group B: Kerajinan Tangan Alami & Tekstil Tradisional]
│   │   ├── craft-natural-fiber/           # Anyaman Rotan & Serat Alami (SERAT ALAM ATELIER)
│   │   ├── batik-heritage-atelier/        # Batik Tulis Canting & Tenun Ikat (BATIK PUSAKA INDONESIA)
│   │   ├── craft-leather-workshop/        # Kerajinan Kulit Asli Handmade (SADDLE CRAFT Studio)
│   │   ├── craft-carving-sculpture/       # Seni Ukir Kayu & Pahat Batu Alam (SENI UKIR NUSANTARA)
│   └── [Group C: Hadiah, Lilin Aromaterapi & Seni Kustom]
│       ├── scent-candle-sanctuary/        # Lilin Aromaterapi Soywax & Diffuser (LUMINA AROMA Sanctuary)
│       ├── floral-preserved-keepsake/     # Bunga Kering Preserved & Pigura 3D (ETERNAL BLOOM Studio)
│       ├── resin-terrazzo-studio/         # Resin Art & Coaster Terrazzo (TERRAZZO & CO Craft)
│       └── custom-hampers-curation/       # Hampers Hari Raya & Gift Box Wax Seal (HAMPERS KASIH Curation)
│
├── 📁 05-agrobisnis-bahan-mentah/          # [12 Sub-Bidang Lengkap]
│   ├── [Group A: Hasil Tani Segar, Buah & Sayur Organik]
│   │   ├── agro-hydroponic-fresh/         # Sayur Hidroponik Bebas Pestisida (HIJAU LESTARI Hydroponic)
│   │   ├── agro-orchard-fruit/            # Buah Matang Pohon Petik Kebun (AGRO KEBUN SEGAR)
│   │   ├── agro-organic-rice/             # Beras Organik Mentik Wangi Vakum (PADI MAKMUR Organik)
│   │   ├── agro-mushroom-farm/            # Jamur Tiram Segar & Media Baglog (JAMUR TIRAM NUSANTARA)
│   ├── [Group B: Peternakan, Perikanan & Hasil Laut]
│   │   ├── poultry-fresh-egg-farm/        # Telur Segar Omega-3 & Karkas Ayam (FARM TELUR SEGAR)
│   │   ├── fishery-fresh-seafood-hub/     # Udang & Ikan Segar Rantai Dingin 0°C (SAMUDRA JAYA Seafood)
│   │   ├── livestock-fresh-meat-ranch/    # Daging Sapi/Kambing Halal Sembelih RPH (BERKAH RANCH Nusantara)
│   │   ├── dairy-raw-milk-homestead/      # Susu Sapi Murni Pasteurisasi Suhu Rendah (HOMESTEAD MILK Farm)
│   └── [Group C: Perkebunan, Rempah & Bahan Mentah Olahan]
│       ├── plantation-coffee-tea-estate/  # Green Coffee Beans & Daun Teh Kebun (NUSANTARA ESTATE Plantation)
│       ├── spices-nusantara-trading/      # Cengkeh, Kapulaga & Rempah Kering (REMPAH PUSAKA Nusantara)
│       ├── raw-honey-wild-apiary/         # Madu Hutan Liar Sialang Raw Unheated (MADU SIALANG RIMBA)
│       └── agro-nursery-organic-fertilizer/ # Bibit Buah Okulasi & Kompos Kohe (AGRO NURSERY & KOMPOS)
│
├── 📁 06-supplier-grosir-b2b/              # [12 Sub-Bidang Lengkap]
│   ├── [Group A: Pabrik Kemasan & Kardus Box]
│   │   ├── packaging-corrugated-box-factory/ # Pabrik Kardus Corrugated Flute B/C/E (PT KARTONINDO PRIMA)
│   │   ├── packaging-food-standing-pouch/    # Standing Pouch Foil Food-Grade (PT FLEXI PACK NUSANTARA)
│   │   ├── packaging-luxury-rigid-box/       # Hardbox Mewah Skincare & Parfum (LUXE BOX ATELIER)
│   │   ├── packaging-eco-kraft-paperbag/     # Paper Bag Kraft Ramah Lingkungan (ECO KRAFT BAG INDONESIA)
│   ├── [Group B: Konveksi Seragam, Garmen & Tekstil Industri]
│   │   ├── garment-corporate-uniform/        # Seragam Kerja PDH/PDL Drill (PT GARMINDO SERAGAM)
│   │   ├── garment-safety-wearpack-k3/       # Wearpack K3 Tambang & Reflektor 3M (SAFETYPRO WEARPACK K3)
│   │   ├── garment-promo-apparel-screenprint/ # Kaos Event & Sablon Plastisol/DTF (PROMO TEES APPAREL)
│   │   ├── textile-wholesale-fabric-rolls/   # Grosir Kain Rollan Katun Combed (PT MAKMUR TEKSTIL INDONESIA)
│   └── [Group C: Distributor Sembako Partai Besar & Bahan Baku Manufaktur]
│       ├── wholesale-sembako-commodity-hub/   # Distributor Sembako Tonase Sak 50kg (PT PANGAN NUSANTARA JAYA)
│       ├── food-ingredients-bakery-raw-materials/ # Bahan Baku Bakery Pail & Yeast (BAKERY INGREDIENTS HUB)
│       ├── chemical-industrial-cleaning-hygiene/ # Kimia Pembersih Laundry & Hotel (PT HYGIENE PRO NUSANTARA)
│       └── polymer-resin-plastic-pellets/     # Biji Plastik PP/HDPE Injection Sak (POLYTAMA POLYMER TECH)
│
├── index.html                              # Showcase Katalog Utama (GitHub Pages Entrypoint)
└── README.md                               # Dokumentasi Arsitektur & Panduan Repositori
```

---

## 📋 Tabel Referensi Matriks 73 Template UMKM

| No | Bidang | Group | Slug Folder | Target Industri / Niche Produk |
|:---|:---|:---|:---|:---|
| 01 | F&B / Kuliner | Group A | `fnb-ricebowl-pop` | Makanan Berat / Rice Bowl / Dine-in (*Mangkok Juara*) |
| 02 | F&B / Kuliner | Group A | `fnb-frozen-clean` | Frozen Food Siap Masak & Dimsum (*BekuRasa*) |
| 03 | F&B / Kuliner | Group A | `fnb-snack-crunchy` | Snack Kering & Keripik Oleh-Oleh (*KriukNusantara*) |
| 04 | F&B / Kuliner | Group A | `fnb-sambal-nusantara` | Sambal Kemasan & Bumbu Masak (*UlegJuara*) |
| 05 | F&B / Kuliner | Group B | `fnb-coffee-dark` | Kopi & Specialty Coffee Roastery (*Obsidian Coffee*) |
| 06 | F&B / Kuliner | Group B | `fnb-catering-clean` | Katering Harian, Bento & Diet (*Sedap Laras*) |
| 07 | F&B / Kuliner | Group B | `fnb-dessert-pastel` | Dessert, Es Krim & Gelato (*Gelato Velveto*) |
| 08 | F&B / Kuliner | Group B | `fnb-meat-butcher` | Daging / Seafood Olahan & BBQ Grill (*WagyuPrime Butcher*) |
| 09 | F&B / Kuliner | Group C | `fnb-bakery-artisan` | Bakery, Roti Sobek & Sourdough Pastry (*Le Pain Artisan*) |
| 10 | F&B / Kuliner | Group C | `fnb-cake-celebration` | Cake, Tart & Kue Ulang Tahun Mewah (*L'Amour Patisserie*) |
| 11 | F&B / Kuliner | Group C | `fnb-healthy-diet` | Makanan Sehat, Diet & Salad Organik (*Nourish Botanica*) |
| 12 | F&B / Kuliner | Group C | `fnb-tradisional-tampah` | Jajanan Pasar & Kue Tampah Basah (*Tampah Nyai Warisan*) |
| 13 | Fashion & Skincare | Group A | `fashion-casual-minimal` | Pakaian Kasual Minimalis Pria & Wanita (*ATELIER NORD*) |
| 14 | Fashion & Skincare | Group A | `fashion-modest-editorial` | Modest Wear, Gamis Syar'i & Sarimbit (*ZAYRA Modest*) |
| 15 | Fashion & Skincare | Group A | `fashion-kids-pastel` | Pakaian Anak, Balita & Bayi SNI (*Little Blossom*) |
| 16 | Fashion & Skincare | Group A | `fashion-activewear-kinetic` | Pakaian Olahraga & Activewear (*KINETIC Performance*) |
| 17 | Fashion & Skincare | Group A | `fashion-loungewear-cozy` | Piyama Sutra, Daster & Loungewear (*COZY HAVEN Silk*) |
| 18 | Fashion & Skincare | Group B | `skincare-clinical-lab` | Skincare Clinical Lab & BPOM (*DERMACEUTICAL Lab*) |
| 19 | Fashion & Skincare | Group B | `makeup-glam-studio` | Kosmetik & Make-up Runway Glam (*LUMINOUS Glam Studio*) |
| 20 | Fashion & Skincare | Group B | `perfume-luxury-atelier` | Parfum & Wewangian Dark Luxury (*NOCTURNE Parfums*) |
| 21 | Fashion & Skincare | Group B | `bodycare-botanical-spa` | Sabun Organik & Perawatan Tubuh (*BOTANICA Rituals*) |
| 22 | Fashion & Skincare | Group C | `footwear-sneakers-street` | Sneakers Urban Streetwear & Sandal (*KICKS VAULT Co.*) |
| 23 | Fashion & Skincare | Group C | `bags-leather-atelier` | Tas Ransel Laptop & Dompet Kulit (*HERITAGE HIDE Leather*) |
| 24 | Fashion & Skincare | Group C | `accessories-modern-optics` | Kacamata UV400 & Sabuk Kulit (*LUMEN Optics & Accs*) |
| 25 | Fashion & Skincare | Group C | `jewelry-timepiece-luxury` | Jam Tangan Kaca Safir & Perhiasan (*AURELIA Fine Jewelry*) |
| 26 | Ritel, Gadget & Hobi | Group A | `gadget-mobile-tech` | Aksesoris HP, Charger GaN 65W & TWS (*NEXUS Mobile Tech*) |
| 27 | Ritel, Gadget & Hobi | Group A | `gaming-peripherals-studio` | Mechanical Keyboard & Desk Setup (*APEX GEAR Studio*) |
| 28 | Ritel, Gadget & Hobi | Group A | `tools-hardware-pro` | Perkakas Tukang & Bor Cordless 20V (*TITAN WORKPRO*) |
| 29 | Ritel, Gadget & Hobi | Group A | `moto-garage-accessories` | Holder HP Anti-Getar & Aksesoris Motor (*APEX MOTO GARAGE*) |
| 30 | Ritel, Gadget & Hobi | Group B | `outdoor-camping-expedition` | Tenda Badai PU 3000mm & Carrier (*TERRA EXPEDITION*) |
| 31 | Ritel, Gadget & Hobi | Group B | `fitness-gym-gear` | Dumbbell Rubber & Matras Yoga TPE (*IRONFIT ATHLETICS*) |
| 32 | Ritel, Gadget & Hobi | Group B | `hobby-collector-vault` | Gunpla, Nendoroid & Display Akrilik (*VALKYRIE HOBBY VAULT*) |
| 33 | Ritel, Gadget & Hobi | Group B | `music-audio-studio` | Gitar Akustik Solid & Aksesoris Audio (*SONIC WAVE Audio*) |
| 34 | Ritel, Gadget & Hobi | Group C | `pet-care-haven` | Pakan Kucing/Anjing & Pasir Anabul (*FURRY HAVEN PETS*) |
| 35 | Ritel, Gadget & Hobi | Group C | `plants-botanical-greenhouse` | Tanaman Hias Monstera & Pot Terakota (*TERRA BOTANICA*) |
| 36 | Ritel, Gadget & Hobi | Group C | `stationery-aesthetic-desk` | Jurnal 120 GSM & Alat Tulis Estetik (*PAPYRUS STUDIO*) |
| 37 | Ritel, Gadget & Hobi | Group C | `baby-montessori-play` | Mainan Kayu Montessori & Teether Bayi (*LITTLE ROOTS Montessori*) |
| 38 | Kriya & Dekorasi | Group A | `furniture-teak-artisan` | Mebel Jati Solid Japandi Living (*KAYU JATI STUDIO*) |
| 39 | Kriya & Dekorasi | Group A | `ceramics-clay-pottery` | Keramik Tembikar & Tableware Handmade (*TERRA KILN Studio*) |
| 40 | Kriya & Dekorasi | Group A | `wall-decor-bohemian` | Hiasan Dinding, Cermin & Makrame (*BOHO VIBE Home*) |
| 41 | Kriya & Dekorasi | Group A | `home-textiles-cushion` | Karpet Tenun & Bantal Sofa Cushion (*NORDIC TEXTILES*) |
| 42 | Kriya & Dekorasi | Group B | `craft-natural-fiber` | Anyaman Rotan & Serat Alami (*SERAT ALAM ATELIER*) |
| 43 | Kriya & Dekorasi | Group B | `batik-heritage-atelier` | Batik Tulis Canting & Tenun Ikat (*BATIK PUSAKA INDONESIA*) |
| 44 | Kriya & Dekorasi | Group B | `craft-leather-workshop` | Kerajinan Kulit Asli Handmade (*SADDLE CRAFT Studio*) |
| 45 | Kriya & Dekorasi | Group B | `craft-carving-sculpture` | Seni Ukir Kayu & Pahat Batu Alam (*SENI UKIR NUSANTARA*) |
| 46 | Kriya & Dekorasi | Group C | `scent-candle-sanctuary` | Lilin Aromaterapi Soywax & Diffuser (*LUMINA AROMA Sanctuary*) |
| 47 | Kriya & Dekorasi | Group C | `floral-preserved-keepsake` | Bunga Kering Preserved & Pigura 3D (*ETERNAL BLOOM Studio*) |
| 48 | Kriya & Dekorasi | Group C | `resin-terrazzo-studio` | Resin Art & Coaster Terrazzo (*TERRAZZO & CO Craft*) |
| 49 | Kriya & Dekorasi | Group C | `custom-hampers-curation` | Hampers Hari Raya & Gift Box Wax Seal (*HAMPERS KASIH Curation*) |
| 50 | Agrobisnis & Bahan Mentah | Group A | `agro-hydroponic-fresh` | Sayur Hidroponik Bebas Pestisida (*HIJAU LESTARI Hydroponic*) |
| 51 | Agrobisnis & Bahan Mentah | Group A | `agro-orchard-fruit` | Buah Matang Pohon Petik Kebun (*AGRO KEBUN SEGAR*) |
| 52 | Agrobisnis & Bahan Mentah | Group A | `agro-organic-rice` | Beras Organik Mentik Wangi Vakum (*PADI MAKMUR Organik*) |
| 53 | Agrobisnis & Bahan Mentah | Group A | `agro-mushroom-farm` | Jamur Tiram Segar & Media Baglog (*JAMUR TIRAM NUSANTARA*) |
| 54 | Agrobisnis & Bahan Mentah | Group B | `poultry-fresh-egg-farm` | Telur Segar Omega-3 & Karkas Ayam (*FARM TELUR SEGAR*) |
| 55 | Agrobisnis & Bahan Mentah | Group B | `fishery-fresh-seafood-hub` | Udang & Ikan Segar Rantai Dingin 0°C (*SAMUDRA JAYA Seafood*) |
| 56 | Agrobisnis & Bahan Mentah | Group B | `livestock-fresh-meat-ranch` | Daging Sapi/Kambing Halal Sembelih RPH (*BERKAH RANCH Nusantara*) |
| 57 | Agrobisnis & Bahan Mentah | Group B | `dairy-raw-milk-homestead` | Susu Sapi Murni Pasteurisasi Suhu Rendah (*HOMESTEAD MILK Farm*) |
| 58 | Agrobisnis & Bahan Mentah | Group C | `plantation-coffee-tea-estate` | Green Coffee Beans & Daun Teh Kebun (*NUSANTARA ESTATE Plantation*) |
| 59 | Agrobisnis & Bahan Mentah | Group C | `spices-nusantara-trading` | Cengkeh, Kapulaga & Rempah Kering (*REMPAH PUSAKA Nusantara*) |
| 60 | Agrobisnis & Bahan Mentah | Group C | `raw-honey-wild-apiary` | Madu Hutan Liar Sialang Raw Unheated (*MADU SIALANG RIMBA*) |
| 61 | Agrobisnis & Bahan Mentah | Group C | `agro-nursery-organic-fertilizer` | Bibit Buah Okulasi & Kompos Kohe (*AGRO NURSERY & KOMPOS*) |
| 62 | Supplier, Grosir & B2B | Group A | `packaging-corrugated-box-factory` | Pabrik Kardus Corrugated Flute B/C/E (*PT KARTONINDO PRIMA*) |
| 63 | Supplier, Grosir & B2B | Group A | `packaging-food-standing-pouch` | Standing Pouch Foil Food-Grade (*PT FLEXI PACK NUSANTARA*) |
| 64 | Supplier, Grosir & B2B | Group A | `packaging-luxury-rigid-box` | Hardbox Mewah Skincare & Parfum (*LUXE BOX ATELIER*) |
| 65 | Supplier, Grosir & B2B | Group A | `packaging-eco-kraft-paperbag` | Paper Bag Kraft Ramah Lingkungan (*ECO KRAFT BAG INDONESIA*) |
| 66 | Supplier, Grosir & B2B | Group B | `garment-corporate-uniform` | Seragam Kerja PDH/PDL Drill (*PT GARMINDO SERAGAM*) |
| 67 | Supplier, Grosir & B2B | Group B | `garment-safety-wearpack-k3` | Wearpack K3 Tambang & Reflektor 3M (*SAFETYPRO WEARPACK K3*) |
| 68 | Supplier, Grosir & B2B | Group B | `garment-promo-apparel-screenprint` | Kaos Event & Sablon Plastisol/DTF (*PROMO TEES APPAREL*) |
| 69 | Supplier, Grosir & B2B | Group B | `textile-wholesale-fabric-rolls` | Grosir Kain Rollan Katun Combed (*PT MAKMUR TEKSTIL INDONESIA*) |
| 70 | Supplier, Grosir & B2B | Group C | `wholesale-sembako-commodity-hub` | Distributor Sembako Tonase Sak 50kg (*PT PANGAN NUSANTARA JAYA*) |
| 71 | Supplier, Grosir & B2B | Group C | `food-ingredients-bakery-raw-materials` | Bahan Baku Bakery Pail & Yeast (*BAKERY INGREDIENTS HUB*) |
| 72 | Supplier, Grosir & B2B | Group C | `chemical-industrial-cleaning-hygiene` | Kimia Pembersih Laundry & Hotel (*PT HYGIENE PRO NUSANTARA*) |
| 73 | Supplier, Grosir & B2B | Group C | `polymer-resin-plastic-pellets` | Biji Plastik PP/HDPE Injection Sak (*POLYTAMA POLYMER TECH*) |

---

## 🛠️ Standar Arsitektur File Setiap Template

Setiap sub-bidang memiliki **5 s/d 6 file HTML multi-page mandiri**:
1. `index.html` — Halaman Beranda Utama (Hero, Niche Value Strip, Interactive Section, Testimoni & CTA).
2. `katalog.html` — Halaman Katalog Produk / Menu dengan filter kategori & live search interaktif.
3. `detail.html` — Halaman Detail Produk Unggulan lengkap dengan galeri foto, spesifikasi teknis, kalkulator tier/kuantitas, & Direct Order WA.
4. `tentang.html` — Halaman Profil Bisnis / Sejarah Brand / Fasilitas Produksi / Tim & Komitmen Mutu.
5. `kontak.html` — Halaman Kontak, Peta Lokasi, Jam Buka, & Interactive Form WA Order Generator.
6. `artikel.html` *(Khusus Niche Edukasi/B2B)* — Halaman Edukasi Konsumen / Panduan Teknis Industri.

---

## 🚀 Cara Menjalankan & Preview Lokal

Karena seluruh template dibangun secara murni menggunakan **HTML5, Tailwind CSS (via CDN), dan Vanilla JavaScript**, Anda dapat langsung membuka file HTML di browser tanpa proses *build* atau *bundling*:

```bash
# Opsi 1: Menggunakan Live Server di VS Code / Antigravity
# Buka file index.html di root atau di dalam subfolder, klik "Go Live"

# Opsi 2: Menggunakan HTTP Server lokal bawaan Python
python -m http.server 8000
# Buka http://localhost:8000 di browser Anda

# Opsi 3: Menggunakan npx serve
npx serve .
```

---

&copy; 2026 **PT Lentera Pasar Digital Nusantara**. Seluruh Hak Cipta Dilindungi. Built with ❤️ for Indonesian MSMEs.
