
📘 Guide de pratique des tests visuels avec Cypress + Applitools

1. 🎯 Objectifs des tests visuels

• Détecter les régressions UI non capturées par les tests fonctionnels.
• Valider la cohérence visuelle sur différents navigateurs et résolutions.
• Automatiser les vérifications de design (alignement, couleurs, polices, etc.).
• Réduire les tests manuels liés à l’apparence.


---

2. 🧭 Quand utiliser les tests visuels

Utilise les tests visuels dans les cas suivants :

Cas d’usage	Justification	
Pages avec beaucoup de contenu statique	Les changements visuels sont plus fréquents que les changements fonctionnels.	
Composants critiques (header, footer, modales)	Ils doivent rester visuellement stables pour l’expérience utilisateur.	
Refactoring CSS ou migration de design system	Pour détecter les impacts visuels involontaires.	
Responsive design	Applitools permet de tester plusieurs résolutions automatiquement.	
Pages marketing ou landing pages	L’apparence est souvent plus importante que la logique métier.	


---

3. 🚫 Quand éviter les tests visuels

• Composants très dynamiques (carrousels, animations complexes).
• Pages avec contenu personnalisé ou aléatoire (ex : recommandations).
• Tests déjà couverts par des assertions fonctionnelles précises.


---

4. 🛠 Mise en œuvre technique

• Intégration d’Applitools Eyes dans Cypress via SDK.
• Définition des points de capture visuelle (`cy.eyesCheckWindow()`).
• Gestion des baselines par branche ou environnement.
• Utilisation du Ultrafast Grid pour tester sur plusieurs navigateurs.


👉 Voir le guide officiel d’Applitools pour Cypress

---

5. 📊 Suivi et maintenance

• Définir un processus de validation des différences visuelles (acceptation ou rejet).
• Mettre en place un tableau de bord des tests visuels.
• Documenter les règles de mise à jour des baselines (quand et par qui).


---

6. 📚 Ressources complémentaires

• Tutoriel GitHub complet avec Cypress + Applitools
• Article en français sur les tests visuels automatisés


---

Si tu veux, je peux t’aider à rédiger cette documentation sous forme de guide interne ou de page Notion. Tu veux qu’on commence par un modèle ?
