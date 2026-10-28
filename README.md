# Hermes – informationssider

Offentlige, statiske informationssider til den personlige Hermes-integration. Ingen Google-loginfunktion, server, database, analyseværktøjer eller afhængigheder.

## Aktivér hjemmesiden

1. Åbn https://github.com/Hamzitouppal/hermes-info/settings/pages
2. Vælg **Deploy from a branch**.
3. Vælg **main** og **/(root)**.
4. Klik **Save**. Vent på, at GitHub Pages melder siden klar.

## Adresser til Google Auth Platform → Branding

| Felt | Værdi |
|---|---|
| Application home page | https://hamzitouppal.github.io/hermes-info/ |
| Application privacy policy link | https://hamzitouppal.github.io/hermes-info/privacy.html |
| Application terms of service link | https://hamzitouppal.github.io/hermes-info/terms.html |
| Authorized domains | hamzitouppal.github.io |

Kontrollér først, at alle sider åbner. Gem derefter Branding og gå tilbage til Audience → Publish app. Google kan kræve yderligere oplysninger eller kontrol af domænet.

## Databrug

Privatlivspolitikken beskriver en personlig integration, hvor oplysninger kan sendes til den valgte AI-udbyder. Den lover ikke, at alle data bliver på ejerens computer. Hermes' konkrete opsætning skal følge politikken, herunder begrænsningerne for brug af Google-data. Tilpas politikken, hvis databehandlingen ændres.

## Filer, som ikke hører til her

Dette repository er offentligt. Gem ikke Google-data, OAuth JSON-filer, tokens, adgangskoder, agentlogfiler eller private noter her. .gitignore hjælper mod visse utilsigtede lokale Git-tilføjelser, men erstatter ikke kontrol af indholdet.
