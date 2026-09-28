# Site T.LEC PRO

Site vitrine de **T.LEC PRO**, entreprise générale du bâtiment à Montpellier :
maçonnerie, électricité, plomberie, plâtrerie et rénovation.

- **Téléphone** : 06 09 69 79 00
- **E-mail** : kibir3@gmail.com
- **Siège social** : 47 rue Vivienne, 75002 Paris (RCS Paris 109 492 512)
- **Zone d'intervention** : Montpellier et son agglomération

## Contenu du dossier

| Fichier | Rôle |
|---|---|
| `tlec-pro-site.html` | Le site complet (HTML, CSS et JavaScript dans un seul fichier, logo inclus) |
| `README.md` | Ce guide |

## Mettre le site en ligne

Le site est un simple fichier HTML. Il suffit de le déposer chez un hébergeur
(OVH, IONOS, GitHub Pages, Netlify, etc.) et de le renommer `index.html`
pour qu'il s'ouvre à l'adresse principale de votre domaine.

## Modifier le site

Ouvrez `tlec-pro-site.html` dans un éditeur de texte (Bloc-notes, VS Code…).

**Changer le téléphone ou l'e-mail** : utilisez la fonction « Rechercher et remplacer »
pour `0609697900`, `06 09 69 79 00` et `kibir3@gmail.com`.

**Ajouter un chantier dans « Nos réalisations »** : cherchez `CHANTIERS` vers la fin
du fichier, copiez un bloc `{ ... }` et remplissez :

- `titre`, `ville`, `date`, `texte`
- `metier` : Électricité, Maçonnerie, Plomberie, Plâtrerie ou Rénovation
- `img` : chemin de la photo (ex. `"photos/cuisine.jpg"`), ou `""` s'il n'y en a pas

Les photos doivent être déposées sur l'hébergement, à côté du fichier HTML.
Les 3 chantiers présents par défaut sont des **exemples à remplacer**.

**Changer les couleurs** : elles sont définies au début du fichier, dans le bloc `:root`
(`--navy`, `--steel`, `--amber`).

## Formulaires

Le site contient deux formulaires : **demande de devis** (clients) et
**candidature sous-traitant**.

Dans la version actuelle, un clic sur « Envoyer » ouvre la messagerie du visiteur avec
le message déjà rédigé, adressé à kibir3@gmail.com. Le visiteur doit ensuite cliquer
sur « Envoyer » dans son logiciel de messagerie.

**Pour un envoi automatique** (sans passer par la messagerie du visiteur), il faut un
service d'envoi de formulaires, par exemple [Formspree](https://formspree.io) (gratuit) :

1. Créer un compte et deux formulaires (devis et sous-traitants).
2. Récupérer les deux adresses de type `https://formspree.io/f/xxxxxxx`.
3. Les intégrer dans le code du site (à la place de l'envoi par messagerie).

Cela ne fonctionne qu'une fois le site hébergé sur votre propre hébergement.

## Référencement (SEO)

- Titre de la page : `T.LEC PRO — Maçonnerie, Électricité, Plomberie, Plâtrerie, Rénovation à Montpellier`
- Description conseillée pour Google (balise `<meta name="description">`) :
  > T.LEC PRO, entreprise du bâtiment à Montpellier : électricité, maçonnerie, plomberie,
  > plâtrerie et rénovation. Devis gratuit, interlocuteur unique, intervention rapide
  > dans toute l'agglomération.

## Mentions légales

Le site affiche la raison sociale, le siège social et le numéro RCS.
Pensez à ajouter une page « Mentions légales » complète (nom du dirigeant,
hébergeur, politique de confidentialité) avant la mise en ligne définitive.
