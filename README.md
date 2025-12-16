# 🎲 D&D Teningakast

Íslenskt vefapp fyrir D&D teningakast með öllum helstu teningum og eiginleikum.

## ✨ Eiginleikar

- **Allir D&D teningar**: D4, D6, D8, D10, D12, D20, D100
- **Margir teningar í einu**: Kastaðu 1-10 teningum samtímis
- **Modifier**: Bættu við bónus eða refsi (-20 til +20)
- **Advantage/Disadvantage**: Fyrir D20 kast
- **Critical Detection**: Sjálfvirk tilkynning fyrir Natural 20 og Natural 1
- **Saving Throws & Ability Checks**: 23+ valmöguleikar með DC stillingu
- **Hljóðeffektar**: Raunverulegt teningahljóð og sérstakir hljóðir fyrir criticals
- **6 þema**: Dark Red, Light, Purple, Green, Blue, Orange
- **Saga**: Sjáðu síðustu 15 köstin þín
- **Responsive**: Virkar á desktop og mobile
- **PWA stuðningur**: Hægt að setja upp sem app

## 🚀 Notkun

### Einfaldasta leiðin (ein skrá)
1. Hladdu niður `dnd-dice.html`
2. Opnaðu í vafra
3. Byrjaðu að kasta! 🎲

### Fyrir GitHub Pages
1. Hladdu niður öllum skránum:
   - `index.html` (aðalskrá)
   - `manifest.json`
   - `sw.js`
2. Settu í GitHub repository
3. Virkjaðu GitHub Pages
4. Farðu á `https://username.github.io/repo-name/`

### Fyrir PWA á síma
1. Opnaðu síðuna í vafra (Safari/Chrome)
2. Smelltu á "Add to Home Screen" / "Bæta við heimaskjá"
3. Appið setur sig upp sem standalone app
4. Virkar offline!

## 📱 Progressive Web App

Appið styður PWA eiginleika:
- ✅ Virkar offline
- ✅ Hægt að setja upp á heimaskjá
- ✅ Fullscreen viðmót
- ✅ Fljótvirkt caching

## 🎨 Þemu

Veldu úr 6 fallegum litaþemum:
- **Dark Red** - Klassískur D&D stíll
- **Light** - Ljós útgáfa fyrir daginn
- **Purple** - Töfra og mystík
- **Green** - Náttúrulegur og rólegur
- **Blue** - Kaldur og cool
- **Orange** - Eldheitur og kraftmikill

Þemað þitt er sjálfkrafa vistað í vafra!

## 🔊 Hljóð

- Raunverulegt teningahljóð þegar kastað er
- Sérstakir hljóðir fyrir Critical Success/Fail
- Sérstakir hljóðir fyrir Saving Throw árangur/misheppni
- Slökkt/kveikt með einum smelli

## 📊 Helstu eiginleikar

### Teningakast
- Veldu fjölda teninga (1-10)
- Bættu við modifier
- Sjáðu summu og einstök kast

### Advantage/Disadvantage
- Kastar tveimur D20
- Tekur hærra/lægra gildið
- Sýnir bæði köstin

### Saving Throws
- 6 Saving Throws (STR, DEX, CON, INT, WIS, CHA)
- 18 Ability Checks
- Stillanleg DC (1-30)
- Sjálfvirk samanburður

### Saga
- Sjáðu síðustu 15 köstin
- Tímastimpill á hverju kasti
- Hreinsa sögu með staðfestingu

## 🛠️ Tæknilegir upplýsingar

- **Engar dependencies**: Allt er standalone
- **Innbyggt hljóð**: Base64 encoded MP3
- **Web Audio API**: Fyrir hámarks samhæfni
- **LocalStorage**: Vistar þema val
- **Responsive CSS**: Mobile-first design
- **PWA ready**: Service Worker og Manifest

## 📄 Skrár

### Fyrir standalone notkun:
- **dnd-dice.html** - Aðalskráin (64KB) - Þetta er allt sem þú þarft!

### Fyrir GitHub Pages / PWA:
- **index.html** - Aðalskráin (sama og dnd-dice.html)
- **manifest.json** - PWA metadata
- **sw.js** - Service Worker fyrir offline

**Athugið:** `index.html` og `dnd-dice.html` eru sama skráin. GitHub Pages notar `index.html` sjálfkrafa.

## 🎯 Notkunardæmi

**Venjulegt kast:**
1. Veldu teninga (t.d. D20)
2. Smelltu á hnappinn
3. Sjáðu niðurstöðu!

**Með modifier:**
1. Stilltu modifier (t.d. +5)
2. Veldu teninga
3. Sjáðu heildarniðurstöðu

**Advantage:**
1. Veldu "Advantage"
2. Smelltu á D20
3. Sjáðu bæði köstin og valið

**Saving Throw:**
1. Virkjaðu "Save/Check"
2. Veldu tegund (t.d. Dexterity Save)
3. Stilltu DC (t.d. 15)
4. Kastaðu D20
5. Sjáðu hvort þú náðir!

## 💡 Fyrir þróunaraðila

Öll kóðinn er í einni HTML skrá fyrir einfaldleika:
- CSS í `<style>` tagi
- JavaScript í `<script>` tagi
- Hljóð embedded sem base64

Til að breyta:
1. Opnaðu `dnd-dice.html` í textaritli
2. Gerðu breytingar
3. Vistaðu og endurnýjaðu í vafra

## 🇮🇸 Íslenska

Allt viðmót er á íslensku með réttri málfræði.

---

**Gaman að spila!** 🎲🐉
