# burrata — site public Burrata Records

> Créé le 04/08/2026. Contexte commun : `claude-burrata/CLAUDE.md`.

## But

Le **site public** de Burrata Records : une page HTML statique, autonome, qui présente la soirée
en cours (à ce jour : *Rotonde XXL 10.08 — Lauer & Jordan Nocturne*). Tout tient dans
`index.html` — structure, styles et contenu dans le même fichier. Pas de build, pas de
framework, pas de dépendances.

C'est volontaire : la page change à chaque event, elle doit rester modifiable en trente secondes
et ne jamais dépendre d'une chaîne d'outils qui aura pourri d'ici la prochaine soirée.

## ⚠️ Le push EST la mise en ligne

Hébergé sur **GitHub Pages** (`Chuoby/burrata`) : `git push origin main` publie immédiatement.
Il n'y a **pas** d'étape de validation, pas de préprod, et c'est une page **publique** — une
faute de frappe sur un nom d'artiste ou une date est en ligne tout de suite.

→ Relire le rendu avant de pousser (ouvrir `index.html` dans le navigateur suffit, il n'y a
rien à compiler).

## Points d'attention

- **Les dates et les noms d'artistes** sont ce qui se voit le plus et ce qui se vérifie le
  moins : les recouper avec la page Shotgun / Resident Advisor de l'event.
- Page consultée **majoritairement au téléphone** (lien depuis Instagram) → vérifier le rendu
  mobile, pas seulement desktop.
- Les textes d'annonce se rédigent avec la skill `mini-description-burrata` (côté claude.ai),
  qui porte le ton du collectif.
