---
name: User Story
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

### 1. Créer un produit dans le catalogue  
**En tant que** administrateur  
**J'ai besoin de** pouvoir créer un produit dans le catalogue  
**Pour que** les utilisateurs puissent voir et acheter le produit  

#### Détails et hypothèses  
* Le produit doit inclure un nom, une description, un prix, et une image.  
* Les informations du produit doivent être validées avant d'être enregistrées.  
* Le produit doit être enregistré dans la base de données du catalogue.  

#### Critères d'acceptation  

```gherkin
Étant donné que je suis un administrateur connecté  
Quand j'accède à la page de création de produit  
Et que je remplis le formulaire avec des informations valides  
Alors le produit est ajouté au catalogue  
Et il devient visible pour les utilisateurs
