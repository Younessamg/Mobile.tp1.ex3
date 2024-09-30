# Application Quiz Android

Cette application Android permet de répondre à un quiz avec des questions utilisant des **CheckBox** et des **RadioButton**. L'utilisateur peut sélectionner des réponses, puis naviguer vers une autre activité pour afficher ses réponses, ou quitter l'application en appuyant sur un bouton.

## Fonctionnalités

- Interface graphique simple pour un quiz.
- Utilisation de **CheckBox** pour permettre plusieurs sélections.
- Utilisation de **RadioButton** pour des sélections uniques.
- Un bouton **Suivant** qui permet de passer à une nouvelle activité et afficher les réponses sélectionnées.
- Un bouton **Quitter** pour fermer l'application.

## Structure

### Fichier XML (interface graphique)

- Contient des **TextView** pour afficher les questions.
- Des **CheckBox** pour permettre des réponses multiples sur certaines questions.
- Des **RadioButton** pour permettre des réponses uniques.
- Deux boutons : 
  - **Suivant** : Passe à une autre activité pour afficher les réponses.
  - **Quitter** : Ferme l'application.

### Activités Java

1. **MainActivity.java** : Contient la logique principale pour capturer les réponses de l'utilisateur.
   - Gère les boutons **Suivant** et **Quitter**.
   - Capture les réponses des **CheckBox** et des **RadioButton**.

2. **ResultActivity.java** : Affiche les réponses sélectionnées par l'utilisateur dans une nouvelle activité.

## Instructions d'utilisation

1. L'utilisateur répond aux questions en sélectionnant des réponses avec des **CheckBox** et des **RadioButton**.
2. En appuyant sur le bouton **Suivant**, une nouvelle activité s'ouvre, affichant les réponses sélectionnées.
3. En appuyant sur le bouton **Quitter**, l'application se ferme.


##Auteur
younes Amerga
## Installation

1. Clonez ce dépôt dans Android Studio :
   ```bash
   git clone https://github.com/votre_nom_utilisateur/quiz-android-app.git
