# LetraShqipApps

Programe për LetraShqip.

## Çfarë është

`LetraShqipApps` përmban aplikacionet zyrtare të LetraShqip për leximin dhe dëgjimin e librave dixhitalë.

Versioni aktual publik është aplikacioni për **Windows**.

## Shkarkimi për Windows

Shkarkimi aktual ndodhet te `Releases`:

- `LetraShqip-win-x64.msix`
- `LetraShqip-msix.cer`

Lidhje:

- [Releases](https://github.com/letrashqip/LetraShqipApps/releases)
- [Versioni v1.0.0](https://github.com/letrashqip/LetraShqipApps/releases/tag/v1.0.0)

## Si të instaloni versionin Windows

1. Shkarkoni skedarin `LetraShqip-msix.cer`.
2. Hapeni certifikatën dhe instalojeni në `Trusted Root Certification Authorities`.
3. Shkarkoni skedarin `LetraShqip-win-x64.msix`.
4. Hapeni paketën `.msix` dhe vazhdoni me instalimin.

Nëse Windows nuk lejon instalimin, arsyeja më e zakonshme është që certifikata `.cer` nuk është instaluar ende.

## Si të përdorni aplikacionin

Pas instalimit:

1. Hapni aplikacionin `LetraShqip`.
2. Nëse përdorni libra të blerë dhe të enkriptuar, vendosni në `Settings` të njëjtin email që përdorni në LetraShqip.
3. Shtoni libra në bibliotekë duke importuar:
   - skedarë `.sqi`
   - skedarë `.md`
4. Hapni librin dhe zgjidhni:
   - `Read` për lexim
   - `Listen` për dëgjim me zë
5. Përdorni `Settings` për të ndryshuar:
   - zërin
   - shpejtësinë e leximit
   - gjuhën e ndërfaqes
   - pamjen e bibliotekës

## Funksionet kryesore

- bibliotekë lokale librash
- kërkim dhe renditje e librave
- lexim i tekstit
- dëgjim me zë neural
- rifillim nga pozicioni i fundit
- kontroll i zërit dhe shpejtësisë
- mbështetje për libra `.sqi` dhe `.md`

## Shënime të rëndësishme

- Aplikacioni nuk është dyqan i integruar. Për të marrë libra të rinj, përdorni [letrashqip.com](https://www.letrashqip.com).
- Për libra `.sqi` të enkriptuar, emaili në aplikacion duhet të përputhet me emailin e blerjes.
- Pas importimit, leximi dhe dëgjimi funksionojnë lokalisht në pajisje.

## Platformat e ardhshme

- **Android**: synohet shpërndarje kryesisht përmes Google Play.
- **Linux**: do të shtohet në një version të ardhshëm.
- **macOS / iOS**: në plan për më vonë.

## Mbështetje

Për pyetje ose probleme:

- [https://www.letrashqip.com](https://www.letrashqip.com)
- `support@letrashqip.com`
