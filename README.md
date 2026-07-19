# CoTime

**Notez vos heures de travail et exportez un PDF récapitulatif.** Simple, sans compte, sans base de données.

Pensé pour les métiers payés à l'heure (ouvrier agricole, saisonnier, intérim, freelance…) qui doivent justifier leurs heures auprès de leur employeur.

## Fonctionnalités

- ⏱️ **Saisie rapide** — une date, un ou plusieurs créneaux (début → fin), une description optionnelle. Les durées et le total du jour se calculent tout seuls (créneaux de nuit gérés).
- 💾 **Sauvegarde automatique** — tout est stocké dans le navigateur (localStorage). On ferme, on revient : rien n'est perdu.
- 🏢 **Multi-employeur** — un sélecteur pour gérer plusieurs employeurs, chacun avec ses heures et son propre récapitulatif.
- 💶 **Taux horaire optionnel** — renseignez un taux pour voir une estimation de vos revenus par mois.
- 📄 **Export PDF** — un tableau récapitulatif propre, mois par mois, prêt à imprimer ou envoyer.
- 📤 **Sauvegarde / restauration** — export JSON complet (transfert entre appareils) et import/export CSV.
- 📱 **Responsive** — utilisable indifféremment sur téléphone et ordinateur.

## Utilisation

C'est un **fichier statique unique** : aucun build, aucune installation.

- **En local** : ouvrez simplement `index.html` dans votre navigateur.
- **En ligne** : déposez `index.html` à la racine de n'importe quel hébergement web (Apache, Nginx, mutualisé, GitHub Pages, Netlify…).

> Les données vivent dans le navigateur de chaque appareil. Pour passer du téléphone à l'ordinateur (ou éviter toute perte), utilisez la **Sauvegarde** (JSON) dans les Réglages.

## Technique

HTML + [React](https://react.dev/) (via CDN) + Babel standalone, le tout dans un seul fichier. Polices Inter & JetBrains Mono. Aucune dépendance à installer.

## Licence

[MIT](LICENSE) — libre d'utilisation, de modification et de distribution.

---

Propulsé par [codepp](https://codepp.fr)
