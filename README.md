# ANGELLI — Registru evidență restaurant

Aplicație web pentru evidența restaurantului ANGELLI: pontaj, casă (cash), deconturi și rapoarte.

## Ce este

Aplicație single-file PWA (index.html) construită pentru:
- **Pontaj** — intrare / ieșire angajați, ture lungi sau schimburi duble
- **Casă** — registru cash (intrări / ieșiri / sold curent)
- **Deconturi** — avansuri către angajați + bonuri
- **Rapoarte** — ore lucrate, solduri, analize per zi/săptămână/lună

## Tehnologii

- HTML/CSS/JS vanilla (fără framework), single file
- Supabase PostgreSQL + REST API
- GitHub Pages pentru hosting

## Roluri

- **admin** — Eugen + Bogdan (văd tot)
- **user** — angajați care fac deconturi (acces limitat)

## Deploy

`git push` pe main → GitHub Pages livrează automat la
`https://arafura-store.github.io/angelli/`
