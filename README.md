# 🚀 Golang_IDE

W założeniu ma to być lekki i nowoczesny IDE napisany w Go, 
dla języka GO, Prosty i wygodny, z ewentualną możliwością podłączenia innych jezyków
---

## Opis

**Golang_IDE** w tej chwili to desktopowe środowisko programistyczne dla języka Go, które łączy:

- **Wails** – framework do tworzenia aplikacji desktopowych w Go z interfejsem webowym.
- **CodeMirror** – nowoczesny edytor kodu z kolorowaniem składni, autouzupełnianiem i wtyczkami.
- **xterm.js** – wbudowany terminal do uruchamiania komend Go i narzędzi CLI.

lekkie i łatwe w rozbudowie – idealne do nauki Go i szybkiego prototypowania.

---

## Funkcje ✨

- Edycja kodu z kolorowaniem składni dla **Go, JS, HTML** i innych języków   
- Wbudowany terminal **xterm.js**.
- Uruchamianie projektów Go bezpośrednio z IDE.
- Możliwość dodawania wtyczek i rozszerzeń.
- **Cross-platform:** Windows, macOS, Linux dzięki Wails. 

---

W tej chwili jest kompletny Frontend , oraz czesćowo działający backend 

### Zrobione 

-- Tworzenie domyslnego folderu Workspace,
-- Tworzenie Nowego Projektu ,  w tym generowanie plików main.go i go.mod 
-- otwieranie plików w edytorze i mozliwość ich edycji 

###  Do zrobienia !!!!

-- Uruchomienie terminala      
-- Tworzenie plików i ich zapis      
-- podłaczenie kompilatora      
-- wiele innych .....     

## Zrzuty ekranu 📸

### Edytor

![Screenshot Edytor](https://forum.lothar-team.pl//ext/dmzx/imageupload/img-files/48/cff7ff1/f1d4a60/eb5787aa69ceb1445c669029a9ba2d8a.png)
![Screenshot Edytor](https://forum.lothar-team.pl//ext/dmzx/imageupload/img-files/48/4053a84/7d34967/32a3f8fba6368acab713631bad2ba437.png)



---

## Instalacja ⚙️

### Wymagania

- Go      >= 1.24.1  
- Node.js >= 24.11.0
- Wails   >=  2.11.0
- npm lub yarn

### Kroki

1. Zainstaluj Wails CLI:

```bash
go install github.com/wailsapp/wails/v2/cmd/wails@latest
```

2. Sklonuj repozytorium:

```bash
git clone https://github.com/TWOJE_KONTO/GoIDE.git
cd GoIDE
```

3. Zainstaluj zależności frontendu:

```bash
npm install
# lub
yarn
```

4. Uruchom w trybie deweloperskim:

```bash
wails dev
```


Wkład 🤝

Każdy wkład jest mile widziany! Możesz:

Dodawać funkcje.
Poprawiać błędy.
Ulepszać dokumentację.
Proponować integracje i wtyczki.

Instrukcja:

Fork repozytorium
Stwórz nową gałąź: git checkout -b feature/nazwa-funkcji

Wprowadź zmiany
Zrób commit: git commit -m 'Dodano nową funkcję'

Wyślij Pull Request


Licencja 📄

Projekt dostępny na licencji MIT. Szczegóły w pliku LICENSE.
