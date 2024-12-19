### README - CV en ligne

---

#### **Aperçu**
Ce projet a été conçu pour permettre à toute personne de mettre son CV en ligne de manière élégante et accessible. Il s'agit d'une application statique facile à déployer et personnalisable.

#### **Technologies utilisées**
- **HTML5** : Pour la structure sémantique du contenu.
- **CSS3** : Pour le style, avec un accent sur la mise en page flexible et le responsive design.
- **Font Awesome** : Pour les icônes utilisées dans la navigation et les sections du CV.
- **Google Fonts (Poppins)** : Pour une typographie moderne et lisible.

---

#### **Fonctionnalités**
- **Responsive Design** : Le CV est optimisé pour s'afficher parfaitement sur tous les types d'appareils (desktop, tablette, mobile).
- **Accessibilité** : Des attributs `aria` et des balises sémantiques sont utilisés pour rendre le CV navigable par des lecteurs d'écran.
- **Section Contact Dynamique** : Chaque lien de contact intègre un effet visuel au survol et est optimisé pour un accès rapide (téléphone, email, géolocalisation, etc.).
- **Barres de Compétences Animées** : Visualisation intuitive des compétences professionnelles.
- **Facilité de Téléchargement** : Un bouton permet de télécharger une version PDF du CV.

---

#### **Comment personnaliser ce projet**
1. **Modifier le contenu texte** :
   - Ouvrez le fichier `index.html`.
   - Remplacez les sections existantes par vos informations (nom, titre, expériences, etc.).
   - Exemple :
     ```html
     <h1>Votre Nom</h1>
     <h2>Votre Poste</h2>
     ```

2. **Changer les styles** :
   - Ouvrez le fichier `main.css`.
   - Mettez à jour les couleurs, polices ou tout autre style en fonction de vos besoins.
   - Par exemple, pour modifier le thème de couleur :
     ```css
     :root {
       --primary-color: #f39c12;
       --secondary-color: #211e25;
     }
     ```

3. **Ajouter ou supprimer des sections** :
   - Les sections comme `Compétences`, `Langues`, `Activités extra-pro` peuvent être personnalisées ou supprimées.
   - Exemple pour ajouter une nouvelle section :
     ```html
     <section class="projects">
       <h3>Projets</h3>
       <p>Décrivez vos projets ici.</p>
     </section>
     ```

4. **Mise à jour des icônes** :
   - Consultez la bibliothèque [Font Awesome](https://fontawesome.com/) pour ajouter ou modifier des icônes.

---

#### **Déploiement**
- **Local** :
  - Ouvrez le fichier `index.html` directement dans un navigateur.
- **Hébergement en ligne** :
  - Hébergez les fichiers sur des plateformes comme [GitHub Pages](https://pages.github.com/), [Netlify](https://www.netlify.com/), ou [Vercel](https://vercel.com/).

---

#### **À propos**
- **Auteur** : Maxime Lenfant
- **Site web** : [maxime-lenfant.fr](https://maxime-lenfant.fr)
- **Année** : 2024
- **Version** : 1.0

---

#### **Contribuer**
Toute amélioration ou idée supplémentaire est la bienvenue. Pour contribuer :
1. Forkez ce projet.
2. Créez une nouvelle branche (`feature/nouvelle-section`).
3. Soumettez une pull request.

---

#### **Licence**
Ce projet est sous licence libre. Vous êtes encouragé à le personnaliser, à le partager ou à l'améliorer.

---

Si vous avez des questions ou besoin d'aide, contactez l'auteur via [maxmaxph@gmail.com](mailto:maxmaxph@gmail.com).
