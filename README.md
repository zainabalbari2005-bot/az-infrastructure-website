# AZ Infrastructure - Site Web Professionnel

## À propos du projet

Site web professionnel pour **AZ Infrastructure**, une entreprise belge polyvalente dans les secteurs de la construction, rénovation, installations techniques, génie civil et nettoyage professionnel.

## 🎯 Objectifs du site

- Présenter l'entreprise et ses services de manière professionnelle
- Attirer de nouveaux clients (particuliers et entreprises)
- Faciliter les demandes de devis en ligne
- Showcaser les réalisations et projets
- Optimiser la visibilité sur les moteurs de recherche (SEO)

## 📋 Structure du site

### Pages principales

1. **Accueil** (`index.html`)
   - Hero section avec appel à l'action
   - Présentation des services principaux
   - Pourquoi nous choisir
   - Aperçu des réalisations

2. **Services** (`services.html`)
   - Détail complet de 9 domaines de services :
     - Installations sanitaires et techniques
     - Électricité et électrotechnique
     - Chauffage, climatisation et ventilation
     - Isolation et étanchéité
     - Construction et maçonnerie
     - Sols, murs et finitions
     - Aménagement extérieur et génie civil
     - Nettoyage professionnel
     - Solutions pour professionnels

3. **Réalisations** (`realisations.html`)
   - Galerie de projets par catégories
   - Section avant/après pour les transformations
   - 12 catégories de travaux

4. **À Propos** (`a-propos.html`)
   - Présentation de l'entreprise
   - Mission et vision
   - Valeurs fondamentales
   - Approche professionnelle

5. **Contact** (`contact.html`)
   - Coordonnées complètes (à remplir)
   - Formulaire de contact
   - Intégration carte (à ajouter)
   - Horaires d'ouverture

6. **Demande de Devis** (`devis.html`)
   - Formulaire détaillé pour les demandes de devis
   - Sélection des services
   - Upload de fichiers (photos, documents)
   - Informations de contact

## 🎨 Design & Responsive

- **Design moderne et professionnel**
- **Fully responsive** : Mobile, Tablet, Desktop
- **Palette de couleurs** :
  - Bleu principal (#1e40af)
  - Vert secondaire (#0f766e)
  - Orange/Amber accent (#f59e0b)
- **Typographie** : Segoe UI, polices système
- **CSS Grid & Flexbox** pour les layouts

## 📁 Structure des fichiers

```
az-infrastructure-website/
├── index.html              # Page d'accueil
├── services.html           # Page des services
├── realisations.html       # Galerie de réalisations
├── a-propos.html          # À propos de l'entreprise
├── contact.html           # Page de contact
├── devis.html             # Formulaire de demande de devis
├── styles.css             # Feuille de styles responsive
├── script.js              # Fonctionnalités JavaScript
├── images/                # Dossier pour les images
│   ├── hero-construction.jpg
│   ├── service-*.jpg
│   ├── project-*.jpg
│   ├── about-company.jpg
│   ├── before-*.jpg
│   ├── after-*.jpg
│   └── ...
├── README.md              # Ce fichier
└── .gitignore            # Fichiers à ignorer
```

## 🚀 Fonctionnalités

### Frontend
- ✅ Navigation responsive avec menu mobile
- ✅ Formulaires de contact et de devis
- ✅ Galerie d'images avec catégories
- ✅ Sections "Avant/Après"
- ✅ CTA (Call To Action) visibles sur toutes les pages
- ✅ Scroll smooth et animations CSS
- ✅ Optimisation SEO (meta tags, titles, descriptions)

### À implémenter (Backend)
- 📝 Traitement des formulaires (Contact & Devis)
- 📧 Envoi d'emails
- 💾 Stockage des demandes de devis
- 🔒 Sécurité (CSRF, validation côté serveur)

## 🔍 SEO

Le site est optimisé pour les recherches Google belges :

- Mots-clés naturellement intégrés :
  - Construction belgique
  - Rénovation bâtiment
  - Installations techniques
  - Travaux électriques
  - Isolation bâtiment
  - Maçonnerie
  - Nettoyage industriel
  - etc.

- Meta descriptions et titles pour chaque page
- Structure HTML sémantique
- Images avec alt text descriptifs
- Schema.org markup (à implémenter)

## 📝 À compléter

Les éléments suivants doivent être personnalisés :

### Informations de l'entreprise
- [ ] Numéro de téléphone
- [ ] Adresse email
- [ ] Adresse physique complète
- [ ] Zone d'intervention exacte
- [ ] Horaires d'ouverture
- [ ] Numéro d'entreprise (TVA)

### Contenu multimédia
- [ ] Remplacer les images placeholders par des vraies photos
- [ ] Logo de l'entreprise
- [ ] Photos des réalisations (12+ projets)
- [ ] Photos avant/après (3+ exemples)
- [ ] Photo de l'équipe/entreprise

### Backend
- [ ] Mise en place d'un serveur/backend pour traiter les formulaires
- [ ] Configuration des emails
- [ ] Base de données pour stocker les demandes
- [ ] Système de gestion admin (optionnel)
- [ ] Intégration de Google Maps pour la localisation
- [ ] Google Analytics pour le suivi

### Marketing
- [ ] Certificats SSL (HTTPS)
- [ ] Soumission à Google Search Console
- [ ] Soumission aux annuaires locaux
- [ ] Google My Business
- [ ] Réseaux sociaux (liens)

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Responsive design, animations, grid/flexbox
- **JavaScript Vanilla** - Interactions, formulaires
- **No dependencies** - Zéro framework externe

## 📱 Compatibilité

- ✅ Chrome / Edge (Chromium)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers
- ✅ IE11+ (avec fallbacks)

## 🚀 Déploiement

### Options recommandées

1. **GitHub Pages** (gratuit, statique)
   ```bash
   git push origin main
   # Les fichiers seront automatiquement déployés
   ```

2. **Vercel** (gratuit, fullstack)
   - Connecter le repo GitHub
   - Les déploiements sont automatiques

3. **Netlify** (gratuit, fullstack)
   - Drag & drop ou connecter GitHub
   - Déploiement automatique

## 📧 Support formulaires

Pour que les formulaires fonctionnent, vous devez :

1. **Option 1** : Utiliser un service tiers (Formspree, Netlify Forms)
2. **Option 2** : Développer un backend Node.js/PHP/Python
3. **Option 3** : Utiliser un CMS avec backend (WordPress, etc.)

## 📄 Licence

Ce projet est la propriété d'AZ Infrastructure. Tous droits réservés.

## 👤 Auteur

Créé pour AZ Infrastructure - Belgique

---

**Dernière mise à jour** : 8 septembre 2026
**Statut** : En développement - Structure complète, contenu à remplir