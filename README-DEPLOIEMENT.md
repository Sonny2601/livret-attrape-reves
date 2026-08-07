# Livret d'accueil — L'Attrape-Rêves · déploiement de démonstration

Contenu : `index.html` (livret autonome, 5 langues) + `assets/` (photos — actuellement
des visuels provisoires, à remplacer par les vraies photos EN GARDANT LES MÊMES NOMS).

## Option A — Vercel sans GitHub (2 minutes)
1. https://vercel.com → se connecter (compte gratuit).
2. « Add New… → Project » puis onglet « Deploy manually » / glisser-déposer :
   déposer CE DOSSIER entier (index.html + assets/).
3. Vercel donne une URL https://….vercel.app → c'est l'URL de préproduction.

## Option B — GitHub + Vercel (recommandé pour itérer)
1. Créer un dépôt GitHub PRIVÉ, p. ex. `attrape-reves-livret`.
2. Y déposer index.html, assets/ et ce README (upload web : glisser-déposer les fichiers,
   ne PAS coller le code dans l'éditeur web de GitHub — il corrompt les crochets).
3. https://vercel.com → Add New → Project → Import Git Repository → choisir le dépôt.
   Framework preset : « Other ». Aucun réglage. Deploy.
4. Chaque mise à jour du dépôt redéploie automatiquement.

## Remplacer les photos
Écraser les fichiers de `assets/` par les vraies photos (mêmes noms) :
accueil.jpg · bienvenue.jpg · arrivee.jpg · chambres.jpg · repas.jpg · maison.jpg ·
securite.jpg · depart.jpg · autour.jpg — format paysage ~15:8, idéalement ≤ 300 Ko chacune.

⚠️ Le QR code de test ne sera généré qu'une fois l'URL Vercel connue, et il ne
s'imprime jamais en série : le QR définitif viendra après la migration WordPress.
