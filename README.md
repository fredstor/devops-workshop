# 🚀 DevOps Workshop: Fra kode til produksjon på 60 minutter

## 🧠 Mål
Lær hvordan man setter opp en enkel CI/CD-pipeline ved å bruke Git og GitHub Actions til å deployere en enkel webside automatisk.

## ⏱ Varighet
**60 minutter**

## 👥 Gruppestørrelse
2–4 personer per gruppe

---

## 🔧 Oppgavebeskrivelse

Dere skal samarbeide som et DevOps-team for å få på plass en fungerende automatisert utviklings- og deployprosess.

### 🗂 Oppgaver:

1. **Fork prosjektet**
   - Fork dette repoet til deres egen GitHub-konto eller organisasjon.

2. **Utforsk prosjektet**
   - Se på innholdet i `index.html` og `.github/workflows/deploy.yml`.

3. **Sett opp GitHub Pages**
   - Gå til repoets **Settings → Pages**
   - Velg `gh-pages` som source (kommer etter første deploy)

4. **Simuler teamarbeid**
   - Én i gruppen gjør en endring i `index.html`
   - Lag en pull request (PR)
   - En annen person godkjenner og merger PR-en

5. **Se på CI/CD-pipelinen**
   - Gå til **Actions** i GitHub og følg med på pipeline-status
   - Når pipelinen er ferdig, sjekk nettsiden på GitHub Pages

---

## 🎯 Bonusutfordringer (hvis tid)

- Legg til en test eller validering i workflowen (f.eks. HTML-validator)
- Endre workflowen til å sende Slack-varsling
- Sett opp en Docker-container som en del av pipelinen

---

## ✅ Ferdig når...

- En endring i `index.html` automatisk blir deployert via pipeline etter merge til `main`
- Dere kan vise frem nettsiden deres via GitHub Pages
- Dere har forstått hvordan CI/CD kobles til daglig utviklingsarbeid

---

## 📦 Teknologi brukt

- Git & GitHub
- GitHub Actions
- GitHub Pages
- HTML (statisk webside)

---

## 📣 Spørsmål til refleksjon

- Hva er fordelene med å ha en automatisert pipeline?
- Hvordan kunne dette skaleres til et større team eller prosjekt?
- Hva ville vært neste steg for å profesjonalisere denne prosessen?

---

🛠 Lykke til og husk: små steg, hyppige endringer, og automatisering er veien til DevOps-suksess!
