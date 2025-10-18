# Assistant de Maintenance 📱🔧

Une application Android complète pour gérer l'entretien de votre maison et autres avec fonctionnalité de partage WhatsApp intégrée.

## 📋 Fonctionnalités

### 🏠 Gestion des entretiens
- **Tableau de bord** : Vue d'ensemble des entretiens à venir avec statuts colorés
- **Historique complet** : Suivi de toutes les interventions passées
- **Alertes personnalisables** : Configuration des rappels par type d'entretien

### 📊 Catégories d'entretien disponibles
- Chaudière
- Filtres à eau
- Détecteurs de fumée
- VMC
- Climatisation
- Ballon d'eau chaude
- Ballon de forage
- Ramonage
- Contrôle technique
- Révision véhicule
- Autre (personnalisable)

### 🔔 Système d'alertes intelligent
- **Statuts automatiques** : 
  - 🔴 **Urgent** (moins de 7 jours)
  - 🟡 **Bientôt** (moins de 30 jours)
  - 🟢 **OK** (plus de 30 jours)
- **Rappels configurables** : Fréquence et délai d'alerte personnalisables

### 📤 Partage WhatsApp
- Partage direct du planning d'entretien
- Message pré-formaté avec tous les détails
- Ouverture automatique de WhatsApp

## 🚀 Installation

1. **Télécharger le fichier HTML**
   ```bash
   # Sauvegardez le code HTML fourni dans un fichier nommé 'assistant-maintenance.html'
   ```

2. **Ouvrir sur votre Samsung Galaxy S24+**
   - Transférez le fichier sur votre téléphone
   - Ouvrez-le avec votre navigateur (Chrome, Samsung Internet)
   - Ajoutez la page à votre écran d'accueil pour une expérience application

3. **Alternative : Développement Android**
   ```bash
   # Pour intégrer dans une application Android native :
   - Créer un nouveau projet Android Studio
   - Utiliser WebView pour charger ce HTML
   - Configurer les permissions nécessaires
   ```

## 📱 Utilisation

### Ajouter un entretien
1. Cliquez sur "Ajouter un entretien"
2. Remplissez les informations :
   - Nom de l'entretien
   - Description
   - Dates (dernière et prochaine intervention)
   - Catégorie
3. Le statut est calculé automatiquement

### Configurer les alertes
1. Allez dans l'onglet "Alertes"
2. Sélectionnez le type d'entretien
3. Définissez la fréquence (en mois)
4. Configurez le rappel (jours avant)

### Partager via WhatsApp
1. Cliquez sur "Partager via WhatsApp"
2. WhatsApp s'ouvre automatiquement avec le message
3. Choisissez votre contact et envoyez

### Supprimer un entretien
- Cliquez sur l'icône 🗑️ à côté de l'entretien
- Confirmez la suppression

## 🛠️ Structure du projet

```
assistant-maintenance/
├── index.html              # Application principale
├── README.md              # Ce fichier
└── assets/                # Ressources (le cas échéant)
    ├── icons/             # Icônes de l'application
    └── styles/            # Feuilles de style supplémentaires
```

## 🔧 Personnalisation

### Ajouter de nouvelles catégories
Modifiez les listes déroulantes dans le code HTML :

```html
<option value="nouvelle_categorie">Nouvelle Catégorie</option>
```

### Modifier les couleurs
Éditez les variables CSS dans la section `:root` :

```css
:root {
    --primary: #2E7D32;      /* Couleur principale */
    --secondary: #FF9800;    /* Couleur secondaire */
    --danger: #f44336;       /* Couleur d'alerte */
}
```

## 📊 Fonctionnalités techniques

### Stockage des données
- **Stockage local** : Données sauvegardées dans le navigateur
- **Persistance** : Les données restent après fermeture de l'application

### Compatibilité
- ✅ **Samsung Galaxy S24+** (optimisé)
- ✅ **Tous les appareils Android**
- ✅ **Responsive design** (adaptatif)

### Performance
- Interface fluide et réactive
- Chargement instantané
- Animations optimisées

## 🎨 Design

### Interface utilisateur
- **Design Material** : Interface moderne et intuitive
- **Couleurs** : Palette verte professionnelle
- **Typography** : Police Segoe UI pour une meilleure lisibilité
- **Icônes** : Font Awesome pour une cohérence visuelle

### Expérience utilisateur
- Navigation par onglets intuitive
- Feedback visuel immédiat
- États vides avec messages explicites
- Notifications contextuelles

## 🔄 Développement futur

### Fonctionnalités envisagées
- [ ] Synchronisation cloud
- [ ] Notifications push
- [ ] Export PDF des entretiens
- [ ] Statistiques avancées
- [ ] Mode hors ligne complet
- [ ] Synchronisation avec calendrier

### Améliorations techniques
- [ ] Base de données locale
- [ ] API REST pour sauvegarde
- [ Version Android native
- [ ] Version iOS

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le projet
2. Créez une branche feature (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push sur la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 📞 Support

Pour toute question ou problème :
- Créez une issue sur le repository
- Contactez-nous par email
- Consultez la documentation

---

**Développé avec ❤️ pour simplifier l'entretien domestique**
