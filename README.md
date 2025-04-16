# AM2S Serrurier Angers - Site Web

Site web professionnel pour AM2S Serrurier à Angers, spécialisé dans le dépannage d'urgence et l'installation de serrures.

## Structure du projet

```
SERRURIER_PROJECT/
├── index.html          # Page principale
├── merci.html         # Page de remerciement après soumission du formulaire
├── css/
│   └── style.css      # Styles du site
└── js/
    └── main.js        # JavaScript pour l'interactivité
```

## Configuration requise

1. **Configuration de FormSpree**
   - Créer un compte sur [FormSpree](https://formspree.io)
   - Créer un nouveau formulaire
   - Remplacer `YOUR_FORMSPREE_ID` dans index.html par votre ID FormSpree
   - Mettre à jour l'URL de redirection dans le formulaire (`_next`)

2. **Informations de contact**
   - Téléphone : 06 89 79 74 69
   - Adresse : 25 Rue Lenepveu, 49100 Angers

## Fonctionnalités

- Design responsive optimisé mobile
- Formulaire de contact via FormSpree
- Carte Google Maps intégrée
- Bouton d'appel flottant
- Page de remerciement personnalisée
- Optimisation SEO

## SEO

Le site est optimisé pour les mots-clés suivants :
- Serrurier Angers
- Dépannage serrure Angers
- Ouverture de porte Angers
- Installation serrure Angers

## Intégrations

### FormSpree
- Gestion des soumissions de formulaire
- Notification par email
- Page de remerciement personnalisée
- Protection anti-spam intégrée

### Google Maps
- Intégration via iframe
- Localisation précise : 25 Rue Lenepveu, Angers
- Interaction complète avec la carte

## Maintenance

Pour mettre à jour le site :
1. Modifier les fichiers HTML/CSS/JS selon les besoins
2. Tester en local avec `python3 -m http.server 8000`
3. Vérifier la compatibilité mobile
4. Déployer les modifications

## Support

Pour toute question ou modification :
1. Consulter la documentation FormSpree : https://formspree.io/docs/
2. Vérifier les paramètres du formulaire dans index.html
3. Tester le formulaire en environnement de développement
