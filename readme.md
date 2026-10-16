# Duyu Laboratuvarı

11. sınıf biyoloji "1.5 Duyu reseptörleri ve duyu organları" konusu için etkileşimli öğrenme sitesi.
Saf HTML + CSS + JavaScript; derleme (build) gerektirmez.

## Dosyalar
- `index.html` – sayfa iskeleti
- `css/style.css` – tasarım
- `js/app.js` – etkinlikler, puan/rozet sistemi, gezinme

## Bilgisayarda çalıştırma
`index.html` dosyasına çift tıkla veya VS Code'da Live Server ile aç.

## GitHub Pages ile yayımlama
1. github.com'da yeni bir depo (repository) oluştur, ör. `duyu-laboratuvari`.
2. Bu klasörün içindekileri depoya yükle (Add file → Upload files) ya da:
   ```
   git init
   git add .
   git commit -m "ilk sürüm"
   git branch -M main
   git remote add origin https://github.com/KULLANICI_ADIN/duyu-laboratuvari.git
   git push -u origin main
   ```
3. Depoda Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
4. 1-2 dakika sonra adres: `https://KULLANICI_ADIN.github.io/duyu-laboratuvari/`

## Kaynaklar ve lisans
- PhET Neuron simülasyonu: https://phet.colorado.edu/en/simulations/neuron
  (© University of Colorado Boulder, CC BY 4.0). Siteye gömülmez; ayrı sekmede açılır.
- Yazı tipi: Baloo 2 (Google Fonts, SIL Open Font License).
