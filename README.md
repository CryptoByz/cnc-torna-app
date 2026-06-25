# CNC Torna G-Code Üretici

Teknik resim veya PDF yükleyerek CNC torna G-code otomatik üretin.

## Özellikler
- 📐 PNG / JPG / PDF teknik resim yükleme
- ✏️ Canvas üzerinde interaktif profil çizimi
- 📊 Koordinat tablosu (X çap, Z uzunluk, G00/G01/G02/G03, pah/radyus)
- ⚙️ Malzeme bazlı otomatik kesme parametreleri
- ⚡ G-Code üretimi: G71, G70, G72, G75, G76, G83
- 💾 .nc dosyası indirme
- 📋 Panoya kopyalama

## Desteklenen Kontrolcüler
- Fanuc 0i / 21i / 0i-TF
- Siemens 840D sl
- Haas NGC

## Deployment (Vercel)
1. Bu repoyu fork edin
2. Vercel'de "New Project" → GitHub repo seçin
3. Framework: **Other** (Static HTML)
4. DNS: `torna.knowledge-arena.xyz` → Vercel CNAME

## URL
`torna.knowledge-arena.xyz`
