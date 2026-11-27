# LetraShqip Apps

Aplikacione desktop dhe web për [LetraShqip](https://www.letrashqip.com), një
platformë librash dixhitalë dhe audiolibrash për lexuesit shqiptarë.

## 🌐 Aplikacioni web (PWA)

**App që funksionon:** https://letrashqip.github.io/LetraShqipApps/

Lexues Markdown pa server, me tekst-në-të-folur në shqip që ekzekutohet vetë
në pajisje, i instalueshëm në iPad/iPhone/desktop me «Shto në Ekranin e
Familjes». Ndërtimi i përkthyer publikohet te dega `gh-pages`.

## 💻 Aplikacionet desktop

### macOS

Shkarkoni skedarin `LetraShqip-macOS-v1.0.0.dmg` nga
[Releases](https://github.com/letrashqip/LetraShqipApps/releases). Pasi ta
shkarkoni, hapeni atë dhe tërhiqni aplikacionin **LetraShqip** brenda dosjes
**Applications**. Herën e parë mos e hapni me dy klikime — bëni **klik me të
djathtën (ose Control-klik)** mbi aplikacionin, zgjidhni **«Open»** dhe më
pas përsëri **«Open»**, sepse aplikacioni nuk është i certifikuar nga Apple
dhe ndryshe macOS do ta bllokojë me mesazhin "cannot be opened". Aplikacioni
kërkon **macOS 14 (Sonoma)** ose më të ri.

### Windows

Shkarkoni `LetraShqip-win-x64.msix` (ose `LetraShqip-Windows-MSIX-v1.0.0.zip`)
nga [Releases](https://github.com/letrashqip/LetraShqipApps/releases) dhe
instaloni certifikatën `LetraShqip-msix.cer` përpara se ta hapni paketën
MSIX, nëse Windows e kërkon.

### Linux

Shkarkoni paketën `LetraShqip-desktop_0.2.0_amd64.deb` nga
[Releases](https://github.com/letrashqip/LetraShqipApps/releases) dhe
instalojeni në Ubuntu/Debian:

```bash
sudo apt install ./LetraShqip-desktop_0.2.0_amd64.deb
```

Nëse përdorni `dpkg`:

```bash
sudo dpkg -i LetraShqip-desktop_0.2.0_amd64.deb
sudo apt -f install
```

## Mbështetje

Për pyetje ose probleme:

- [https://www.letrashqip.com](https://www.letrashqip.com)
- `support@letrashqip.com`
