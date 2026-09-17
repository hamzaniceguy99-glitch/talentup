# TalentUp — coaching carrière

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `talentup.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/talentup.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs talentup` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@talentup.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (59 / 139 / 269 €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
Coaching carrière en ligne : accompagnement individuel et en petit groupe pour la reconversion professionnelle, la recherche d’emploi (CV, LinkedIn, entretiens), la prise de poste de manager et la négociation salariale. Les clients suivent un accompagnement de 4 à 12 semaines avec séances en visioconférence et plan d’action personnalisé. Il ne s’agit pas d’un bilan de compétences et aucune garantie d’emploi n’est proposée. Les prestations sont vendues sous forme d’abonnements mensuels sans engagement, de 59 € à 269 € par mois, résiliables à tout moment. Aucun produit physique n’est vendu ni expédié. Site : talentup.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
