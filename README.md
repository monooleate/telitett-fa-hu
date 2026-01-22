# 🌲 Telített Fa Weboldal - AstroWind Alapon

Modern, SEO-optimalizált weboldal nagynyomáson kezelt borovifa termékek bemutatására. Magyar nyelven, dark mode támogatással, B2B célközönségnek.

## ✨ Főbb Jellemzők

- 🎨 **Modern UI/UX**: Tailwind CSS, dark mode, responsive design
- 📊 **Interaktív Összehasonlítások**: Animated comparison charts
- 🚀 **SEO Optimalizált**: Meta tags, structured data, semantic HTML
- 📱 **Mobile-First**: Tökéletes megjelenés minden eszközön
- ⚡ **Gyors Betöltés**: Astro SSG, optimalizált képek
- 🌍 **Multilingual Ready**: Könnyen bővíthető román, horvát, szlovák nyelvvel

## 📁 Projekt Struktúra

```
telitett-fa-fooldal/
├── src/
│   ├── components/
│   │   ├── widgets/
│   │   │   ├── Comparison.astro    # Új összehasonlító widget
│   │   │   ├── Stats.astro          # Új statisztika widget
│   │   │   └── ...                  # AstroWind alap widgetek
│   │   └── ui/
│   ├── pages/
│   │   └── index.astro              # Főoldal
│   ├── types.d.ts                   # TypeScript típusok
│   └── ...
└── README.md
```

## 🎯 Tartalom Stratégia

### Főoldal Szekciók:

1. **Hero Section** - Impaktus első benyomás
   - Főcím: "Nagynyomáson Kezelt Borovifa"
   - CTA gombok: Árajánlat + Termékek
   - Placeholder termék vizualizáció

2. **Stats Section** - Gyors számok
   - 15-25 év élettartam
   - 100% nehézfém-mentes
   - UC4 minősítés
   - 0% króm & arzén

3. **Comparison Section** - Interaktív összehasonlítás
   - **Keményfa vs Telített Borovi**
     * Ár: 100% vs 45% (telített nyeri)
     * Élettartam: 100% vs 70%
     * Megmunkálhatóság: 50% vs 100% (telített nyeri)
     * Teljes költség: 95% vs 52% (telített nyeri)
   
   - **Mártott vs Telített Borovi**
     * Ár: 35% vs 48%
     * Élettartam: 20% vs 100% (telített nyeri)
     * Karbantartás: 100% vs 15% (telített nyeri)
     * Teljes költség: 100% vs 45% (telített nyeri)

4. **Features Section** - 9 fő előny
   - Mély védelem, Gyermekbarát, Tartósság
   - Könnyű megmunkálás, Fenntarthatóság, B2B árak
   - Nem korrodál, Festhető, Méretválaszték

5. **Content Section** - Miért Borovi?
   - Sejtszerkezet magyarázat
   - Összehasonlítás más fenyőkkel

6. **Steps Section** - Gyártási folyamat
   - 5 lépés vizuálisan

7. **FAQs** - 8 gyakori kérdés
   - Élettartam, biztonság, árak, karbantartás, stb.

8. **Call to Action** - Záró felhívás
   - B2B kapcsolatfelvétel

## 🎨 Design Rendszer

### Színek:
- **Primary**: Blue/Teal (természet, megbízhatóság)
- **Secondary**: Green (környezetbarát, fenntarthatóság)
- **Accent**: Amber (figyelem, kiemelés)
- **Highlight**: Emerald (ajánlott, pozitív)

### Komponensek:
- Glassmorphism effect-ek
- Smooth scroll animations
- Hover interactions
- Dark mode kompatibilis

## 🔧 Használat

### Telepítés:

```bash
# Klónozd az AstroWind template-et
npm create astro@latest -- --template onwidget/astrowind

# Másold be a komponenseket
cp -r telitett-fa-fooldal/src/* your-project/src/

# Telepítsd a függőségeket
npm install

# Indítsd el a dev servert
npm run dev
```

### Testreszabás:

1. **config.yaml** - Alap beállítások
2. **Képek** - Cseréld le a placeholder képeket termék fotókra
3. **Tartalom** - Frissítsd az árajánlat linkeket
4. **Blog** - Hozz létre összehasonlító cikkeket

## 📝 Blog Ötletek

Készítendő blog cikkek SEO-hoz:

1. **"Keményfa vs Telített Borovifa - Melyiket Válaszd 2025-ben?"**
   - Részletes összehasonlítás
   - Költségelemzés (TCO)
   - Projekt esettanulmányok

2. **"Mártott vs Telített Fa - A Valódi Különbség"**
   - Felületi vs mély védelem
   - Élettartam összehasonlítás
   - Karbantartási költségek

3. **"UC4 Minősítés - Mit Jelent és Miért Fontos?"**
   - Minősítési rendszer magyarázat
   - Alkalmazási területek
   - Tanúsítványok

4. **"Tanalith Kezelés - Gyermekbarát Faanyagvédelem"**
   - Nehézfém-mentesség
   - EN 71-3 szabvány
   - Játszótér alkalmazások

5. **"Telített Fa Élettartama - 15-25 Év Garantált Védelem"**
   - Tényezők befolyásoló hatása
   - Karbantartási tippek
   - Esettanulmányok

## 🌍 Nemzetköziesítés

### Következő lépések:

1. **Román verzió** (lemn tratat sub presiune)
2. **Horvát verzió** (impregnirano drvo pod tlakom)
3. **Szlovák verzió** (impregnované drevo pod tlakom)

Minden nyelv:
- Külön `/ro/`, `/hr/`, `/sk/` mappa
- Hreflang tag-ek
- Lokalizált tartalom

## 📊 SEO Checklist

- ✅ Meta title & description
- ✅ Open Graph tags
- ✅ Structured data (Product, Organization)
- ✅ Semantic HTML
- ✅ Alt text képeken
- ✅ Internal linking
- ✅ Mobile-friendly
- ✅ Page speed optimized
- ✅ XML sitemap
- ✅ Robots.txt

## 🎯 Konverzió Optimalizálás

### CTA Helyek:
1. Hero section - 2 gomb
2. Comparison után - "Árajánlat kérése"
3. Features után - "Termékek böngészése"
4. FAQ után - "Kérdésed van?"
5. Footer CTA - Záró felhívás

### Lead Capture:
- `/kapcsolat` oldal email form
- Google Sheets integráció
- Automatikus email válasz

## 🚀 Telepítés és Hostolás

### Javasolt platformok:
- **Netlify** - Ingyenes SSL, automatikus deploy
- **Vercel** - Edge functions, analytics
- **Cloudflare Pages** - CDN, DDoS védelem

### Deploy parancsok:

```bash
# Build
npm run build

# Preview
npm run preview

# Deploy (Netlify példa)
netlify deploy --prod
```

## 📞 Kapcsolat és Support

- **Email**: kapcsolat@gigawood.hu
- **Telefon**: +36 30 531 9050
- **Cím**: 2030 Érd, Elvira utca 33.

## 📄 Licenc

MIT License - Szabadon használható és módosítható

---

**Készítve**: 2025 Január - AstroWind + Tailwind CSS + Astro 5.0
**Verzió**: 1.0.0
**Status**: Production Ready 🚀
