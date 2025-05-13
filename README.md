# 🚀 DevOps Workshop: Fra kode til produksjon på 60 minutter

Velkommen til en praktisk workshop hvor du og teamet ditt lærer å sette opp en komplett DevOps-pipeline med GitHub Actions og GitHub Pages. Målet er å bygge, validere, og deploye en statisk nettside – helt automatisk!

## 📚 Innhold

- Fork og utforsk prosjektet
- Sett opp GitHub Pages
- Lag endringer og simuler teamarbeid
- Legg til validering og varslinger i CI/CD-pipelinen
- (Bonus) Docker og tilgjengelighetstesting

---

## 🔧 Oppgaver

1. **Fork dette repoet**  
   Trykk på “Fork” øverst til høyre for å lage deres egen kopi.

2. **Se på prosjektet**  
   - Åpne `index.html` – dette er startsiden som skal vises på GitHub Pages.
   - Gå gjennom `.github/workflows/deploy.yml` for å forstå workflowen.

3. **Sett opp GitHub Pages**  
   - Gå til `Settings → Pages` og velg `gh-pages` som source etter første deploy.

4. **Simuler teamarbeid**  
   - Én person gjør en endring i `index.html` og lager en Pull Request.
   - En annen person reviewer og merger PR-en.

5. **Utvid workflowen**
   - Legg til HTML-validering (f.eks. med [HTMLHint](https://github.com/htmlhint/HTMLHint)).
   - Send varsel ved feil (Slack, Discord, eller GitHub-comment).
   - Sørg for at workflowen feiler hvis det oppdages feil.

6. **Versjonskontroll**
   - Legg til `version.txt` og `CHANGELOG.md` i repoet.
   - Oppdater versjon manuelt for hver release.

---

## ✅ Mål for å være “ferdig”

- [ ] Automatisk deploy til GitHub Pages etter merge til `main`
- [ ] Workflow inkluderer HTML-validering og feilhåndtering
- [ ] Automatisk varsel hvis noe feiler
- [ ] Nettsiden viser versjon og er tilgjengelig på GitHub Pages
- [ ] Teamet forstår hvordan CI/CD fungerer og gir verdi

---

## 📦 Teknologi brukt

- Git & GitHub
- GitHub Actions
- GitHub Pages
- HTML
- HTMLHint (eller annen validator)
- (Bonus) Docker, Pa11y, Slack

---

## 💡 Bonusutfordringer

- Sett opp en enkel Docker-container som serverer `index.html`
- Kjør tilgjengelighetstesting med [Pa11y](https://github.com/pa11y/pa11y)
- Bruk GitHub Secrets for sikker håndtering av nøkler og tokens

---

## 🤔 Refleksjonsspørsmål

- Hva er fordelene med en automatisert pipeline?
- Hvordan påvirker dette samarbeidet i teamet?
- Hva må til for å gjøre systemet produksjonsklart?
- Hvordan ville dere utvidet dette for staging og rollback?

---

🛠 Husk: Små steg, hyppige endringer og kontinuerlig automatisering gir raskere og tryggere utvikling!
