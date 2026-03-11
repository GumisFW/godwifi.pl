# godwifi.pl
# 🌐 godwifi.pl

> Nieoficjalna strona fanowska poświęcona polskiemu artyście **god.wifi**

![Version](https://img.shields.io/badge/version-2.2-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Platform](https://img.shields.io/badge/platform-web-lightgrey.svg)

---

## 📖 O Projekcie

**godwifi.pl** to strona internetowa stworzona przez fana, dedykowana artyście **god.wifi**. Projekt nie jest oficjalny i nie jest powiązany z artystą ani jego managementem. 

Strona została zaprojektowana jako interaktywne doświadczenie łączące elementy:
- 🖥️ Interfejsu przypominającego system operacyjny (Windows/Ubuntu style)
- 📱 Natywnego wyglądu aplikacji mobilnej (iOS/Android)
- 🎮 Mini-gier i Easter eggs
- 🎵 Odtwarzacza muzyki
- 📸 Galerii zdjęć

---

## ✨ Funkcje

### 💻 Wersja Desktop
- **Fake Browser (Freelookup)** - Google-style wyszukiwarka z linkami
- **System plików** - przeglądanie folderów i plików
- **Music Player** - odtwarzacz z pełną playlistą (9 utworów)
- **Video Player** - odtwarzacz BMX videos (6 filmów)
- **Photo Gallery** - galeria zdjęć z logowaniem
- **SMS Conversation** - interaktywna konwersacja o hasło WiFi
- **WiFi Runner** - gra w stylu Chrome Dino
- **Easter Egg** - kliknij ikonę WiFi 5x dla wyboru gier

### 📱 Wersja Mobile
- **iOS/Android Style UI** - natywny wygląd telefonu
- **Home Screen** - aplikacje w stylu systemowym
- **Status Bar** - zegar, sygnał, bateria
- **Music App** - pełny player z kontrolkami
- **Photos App** - galeria zdjęć 3x3 grid
- **Messages App** - SMS conversation z Easter egg
- **Flappy WiFi** - mini-gra (tap sygnał 5x)
- **Dock** - szybki dostęp do social media

---

## 🔗 Linki

- 📷 [Instagram god.wifi](https://instagram.com/god.wifi)
- 📷 [Instagram Gumis](https://instagram.com/tokarz_k)
- 🎵 [Spotify](https://open.spotify.com/artist/6iz52ADwFl483ghAI7NuS1)
- 🎮 [Discord](https://discord.gg/4PTQRsUq9t)
- 🎬 [YouTube - About](https://www.youtube.com/watch?v=CYNJYIguniI)

---

## 📅 Historia Wersji

### **v2.2** - 11 marca 2026
**"Wybór Gier"**
- ✨ Dodano Game Selector (wybór między grami)
- 🎮 Desktop: WiFi Runner + Flappy WiFi (coming soon)
- 📱 Mobile: Flappy WiFi + WiFi Runner (coming soon)
- 🔧 Aktywacja: 5x kliknięcie w sygnał/WiFi icon
- 📁 Pełna reorganizacja plików w foldery

### **v2.1** - 4 marca 2026
**"Wielkie Poprawki"**
- ❌ Usunięty Blue Screen (BSOD)
- 🌐 Działające linki w Freelookup (YouTube, Spotify)
- 📱 Naprawione wykrywanie iPada/tabletu
- 🎮 Naprawiona gra Flappy Bird na tabletach
- 📁 Naprawiona nawigacja po folderach mobilnych
- 🚫 Wyłączony stary mobile blocker
- 🐛 Dodane console logging do debugowania

### **v2.0** - 3 marca 2026
**"Mobile Revolution"**
- 📱 Kompletny interfejs mobilny (iOS/Android style)
- 🏠 Home Screen z aplikacjami
- 📶 Status Bar (czas, sygnał, bateria)
- 🎵 Music Player mobilny
- 📸 Photo Gallery mobilna
- 💬 SMS Conversation mobilna
- 📁 Files navigation mobilna
- 🎮 Flappy WiFi game (5x tap sygnał)
- 🔄 Auto-stop muzyki przy zamknięciu app

### **v1.5** - 2 marca 2026
**"Easter Eggs & Games"**
- 🎮 WiFi Runner game (Chrome Dino style)
- 🐦 Flappy Bird prototype
- 🎯 Easter eggs activation system
- 🔊 Auto-stop muzyki przy zamknięciu okna
- 🎨 Zaokrąglone ikony na pulpicie (14px)

### **v1.2** - 1 marca 2026
**"SMS & Login Systems"**
- 💬 SMS Conversation z hidden_user
- 🎲 3 opcje hasła (17042026 = correct)
- 🔐 Photo Gallery login (Zanzir)
- 🔐 Drive auto-login (good_wifey)
- 📱 Mobile blocking modal
- 🚫 Mobile Photo login blocked

### **v1.0** - 28 lutego 2026
**"Initial Release"**
- 🖥️ Desktop interface (Windows/Ubuntu style)
- 🌐 Fake Browser (Freelookup)
- 💀 BSOD + Safe Boot sequence
- 🎵 Music Player (9 tracks)
- 🎬 Video Player (6 BMX videos)
- 📸 Photo Gallery (6 photos)
- 📁 File Manager (Finder)
- 🎨 Splash screen animation
- ⚙️ Maintenance mode (hasło: g0dwifi)

### **v0.5** - 25 lutego 2026
**"Prototype"**
- 🎨 Podstawowy layout
- 🖼️ Logo i branding
- 📝 Struktura HTML
- 🎨 CSS styling

---

## 🛠️ Technologie

- **HTML5** - struktura strony
- **CSS3** - styling, animacje, responsive design
- **JavaScript (Vanilla)** - logika, interaktywność
- **Canvas API** - gry (Flappy WiFi, WiFi Runner)
- **Media APIs** - audio/video playback
- **Local Storage** - zapisywanie stanu (session)

**Brak frameworków** - czysta implementacja dla maksymalnej wydajności!

---

## 📂 Struktura Projektu

```
godwifi/
├── index.html                    # Główny plik strony
│
├── assets/                       # Wszystkie zasoby
│   ├── images/
│   │   ├── logo/                # Logo i favicon
│   │   ├── icons/               # Ikony aplikacji
│   │   ├── social/              # Social media icons
│   │   ├── splash/              # Splash screen
│   │   └── photos/              # Galeria zdjęć
│   ├── audio/                   # Pliki muzyczne (mix1-9.mp3)
│   └── video/                   # BMX videos (bmx1-7.mp4)
│
└── docs/                        # Dokumentacja
    ├── CODE_GUIDE.md           # Przewodnik po kodzie
    ├── FIXES_SUMMARY.md        # Podsumowanie poprawek
    └── GAME_SELECTOR.md        # Dokumentacja gier
```

---

## 🎮 Easter Eggs

### Desktop:
- 🖱️ **Kliknij ikonę WiFi (taskbar) 5x** → Game Selector
  - WiFi Runner (działa)
  - Flappy WiFi (coming soon)

### Mobile:
- 👆 **Tap sygnał (status bar) 5x** → Game Selector
  - Flappy WiFi (działa)
  - WiFi Runner (coming soon)

### SMS:
- 💬 Hasło WiFi: **17042026** ✅
- ❌ Złe hasła: 22032026, 2137420

### Loginy:
- 📁 Drive: **good_wifey** (auto-fill)
- 📸 Photos: **Zanzir**

---

## 🚀 Instalacja & Hosting

### Lokalne uruchomienie:
1. Pobierz wszystkie pliki
2. Zachowaj strukturę folderów
3. Otwórz `index.html` w przeglądarce

### Upload na hosting:
1. Użyj skryptu `organize-files.bat` (Windows) lub `organize-files.sh` (Mac/Linux)
2. Upload całego folderu `godwifi/` na serwer
3. Upewnij się że `index.html` jest w głównym katalogu
4. Gotowe!

**Wymagania hostingu:**
- HTML/CSS/JS support (każdy hosting)
- Brak wymagań PHP/Database
- ~50MB przestrzeni (dla audio/video)

---

## 🎨 Features Breakdown

### Responsywność:
- ✅ Desktop (1920x1080+)
- ✅ Laptop (1366x768)
- ✅ Tablet (iPad, Android tablets)
- ✅ Mobile (375x667 - 428x926)

### Przeglądarki:
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

### Accessibility:
- 🎨 High contrast mode support
- ⌨️ Keyboard navigation
- 📱 Touch-friendly (mobile)
- 🖱️ Mouse & keyboard (desktop)

---

## 🐛 Znane Problemy

### Mobile Safari:
- ⚠️ Audio może wymagać user interaction przed odtworzeniem
- **Fix**: Tap play przed autoplaying

### Firefox:
- ⚠️ Backdrop-filter może mieć gorszą wydajność
- **Fix**: Używaj Chrome dla najlepszej wydajności

### Stare przeglądarki:
- ❌ IE11 nie jest wspierany
- ⚠️ Safari < 14 może mieć problemy z CSS

---

## 📝 Changelog

<details>
<summary><b>v2.2 (11.03.2026)</b></summary>

**Dodane:**
- Game Selector modal (desktop + mobile)
- Wybór między grami (WiFi Runner / Flappy WiFi)
- Reorganizacja plików w foldery
- organize-files scripts (bat + sh)

**Poprawione:**
- Splash image path
- Icon paths structure
- Documentation updates
</details>

<details>
<summary><b>v2.1 (04.03.2026)</b></summary>

**Dodane:**
- Console logging dla debugowania
- Better iPad/tablet detection

**Usunięte:**
- BSOD screen (pominięty)
- Stary mobile blocker

**Poprawione:**
- Freelookup linki (YouTube, Spotify)
- Flappy Bird canvas na tabletach
- Mobile folders navigation
- Auto-stop muzyki
</details>

<details>
<summary><b>v2.0 (03.03.2026)</b></summary>

**Dodane:**
- Kompletny mobile interface
- Status bar (iOS style)
- Mobile apps (Music, Photos, Messages, Files, Videos)
- Flappy WiFi game
- Mobile game selector

**Poprawione:**
- Desktop icons (rounded, no background)
- "Galerie" → "Galeria"
</details>

---

## 💪 Contributor

**Projekt stworzony przez fana**

- 🎨 Design & Development: Fan project
- 🎵 Muzyka: god.wifi
- 📸 Materiały: od społeczności

---

## 📜 Licencja & Disclaimer

### Disclaimer:
⚠️ **To jest NIEOFICJALNY projekt fanowski**

- ❌ NIE jest powiązany z artystą god.wifi
- ❌ NIE jest oficjalną stroną
- ❌ NIE jest wspierany przez management artysty
- ✅ Stworzony przez fana dla fanów
- ✅ Non-profit, edukacyjny projekt

### Prawa autorskie:
- 🎵 Muzyka: © god.wifi - wszelkie prawa zastrzeżone
- 📸 Zdjęcia: © odpowiednie źródła
- 💻 Kod strony: Open for fans (educational purposes)

**Jeśli jesteś artystą/managementem i chcesz aby strona została usunięta, proszę o kontakt.**

---

## 🤝 Contribution

Projekt jest otwarty dla społeczności:

1. 🐛 Zgłaszaj bugi
2. 💡 Proponuj nowe funkcje
3. 🎨 Dziel się pomysłami na design
4. 📝 Poprawiaj dokumentację

**Nie przyjmuję pull requestów z muzyką/zdjęciami bez zgody artysty!**

---

## 📞 Kontakt

- 📧 Kontakt: poprzez Discord serwer god.wifi
- 🐛 Bugi: poprzez Issues (jeśli używasz GitHub)
- 💬 Społeczność: [Discord](https://discord.gg/4PTQRsUq9t)

---

## 🙏 Podziękowania

- 🎵 **god.wifi** - za niesamowitą muzykę
- 📸 **Społeczność** - za wsparcie i materiały
- 💻 **Anthropic Claude** - za pomoc w development
- ❤️ **Fani** - za wsparcie projektu

---

## 📊 Stats

- 📝 Linii kodu: ~7,500
- 📁 Plików: 36 assets + 1 HTML
- 🎵 Utworów: 9
- 🎬 Filmów: 6
- 📸 Zdjęć: 7
- 🎮 Gier: 2
- ⏱️ Czas developmentu: ~40 godzin

---

<div align="center">

**Zrobione z ❤️ przez fana dla fanów**

[Instagram](https://instagram.com/god.wifi) • [Spotify](https://open.spotify.com/artist/6iz52ADwFl483ghAI7NuS1) • [Discord](https://discord.gg/4PTQRsUq9t)

**godwifi.pl** • v2.2 • 2026

</div>
