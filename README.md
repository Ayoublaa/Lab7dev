# StarGallery ⭐

**StarGallery** est une application Android moderne conçue pour explorer une galerie de célébrités. Elle permet de visualiser des profils, de rechercher des acteurs par nom et de gérer leurs évaluations via une interface fluide et interactive.

---

## 📱 Démonstration Vidéo

> [!IMPORTANT]  
> **[CLIQUEZ ICI POUR VOIR LA VIDÉO DE DÉMONSTRATION]
> 


https://github.com/user-attachments/assets/71f7e577-c2a6-473f-9e94-2e9c3fd9fbc2


---

## ✨ Fonctionnalités

- **Splash Screen Animé** : Premier écran avec une étoile vectorielle (`ic_star_splash`) et une transition fluide vers la liste.
- **Gestion de Liste (RecyclerView)** : Affichage optimisé des célébrités avec portraits circulaires.
- **Recherche Dynamique** : Filtrage en temps réel via une `SearchView` intégrée dans l'ActionBar.
- **Notation Interactive** : Modification des notes (RatingBar) via une boîte de dialogue personnalisée.
- **Partage Social** : Fonctionnalité de partage intégrée pour diffuser l'application.

## 🛠️ Stack Technique & Bibliothèques

L'application repose sur les composants suivants :
- **Langage** : Java
- **Architecture** : Pattern Service/DAO pour la gestion des données.
- **UI & Design** :
    - `Google Material Components` : Pour les thèmes et composants visuels.
    - `Glide (v4.16.0)` : Chargement et mise en cache performante des images distantes.
    - `CircleImageView` : Rendu circulaire des portraits de stars.
    - `RecyclerView` : Pour une gestion de liste fluide.
- **Permissions** : 
    - `INTERNET` : Requis pour récupérer les photos des célébrités en ligne.

## 📂 Structure du Projet

```text
com.example.stargallery
├── adapter   # StarAdapter pour la liaison des données
├── dao       # StarDao (Source de données)
├── model     # Classe POJO Star
├── service   # Logique métier (Recherche, filtrage)
└── ui        # SplashActivity & ListActivity
```

## 🚀 Installation & Utilisation

1. **Clonage du repo** :
   ```bash
   git clone https://github.com/votre-compte/StarGallery.git
   ```
2. **Ouverture** : Importer le dossier dans **Android Studio**.
3. **Build** : Gradle téléchargera automatiquement les dépendances (Glide, CircleImageView).
4. **Exécution** : Lancez l'application sur un émulateur ou appareil physique (Min API 21+).

---
*Projet réalisé dans le cadre du module de développement mobile Android.*
