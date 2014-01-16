@ajouter les tags utiles pour un document Markdown.

#Zee Drupaleurs
Pendant cette réunion hebdomadaire, l'un des collaborateurs va présenter
un module utilisant sur l'un de ses derniers projets.
Et je vais commencer cette nouvelle section par la présentation de 2
modules CheckListApi et Variables.


## ChecklistAPI
[Page du module](https://drupal.org/project/checklistapi)

> Checklist API Provides a simple interface for modules to create fillable, persistent checklists that track progress with completion times and users. You don't need this unless you're a module developer or you want to use a module that calls for it.

Il permet la création des check-lists directement dans l'interface d'administration de Drupal.

Un exemple complet est celui sur le [SEO](https://drupal.org/project/seo_checklist), avec toutes les optimisations pour le référencement d'un site.

[Lien de l'API](http://drupalcode.org/project/checklistapi.git/blob/refs/heads/7.x-1.x:/checklistapi.api.php)

## Module Variable 
[Page du module](https://drupal.org/project/variable)

Présentation des variables_get dans le monde de drupal. 
Liens de documentations sur Drupal.org.

Les fonctions [variable_set](https://api.drupal.org/api/drupal/includes!bootstrap.inc/function/variable_set/7), [variable_get](https://api.drupal.org/api/drupal/includes!bootstrap.inc/function/variable_get/7) et [variable_del](https://api.drupal.org/api/drupal/includes!bootstrap.inc/function/variable_del/7)

Lancer une commande Drush pour montrer la rassignation d'une variable avec les commandes 

```
drush vset,vget,vdel NAME_VARIABLE VALUE_VARIABLE
```


### Les avantages du module Variable
- centraliser
- faciliter d'utilisation 
- création simplifier de widgets (champs de saisie+multiligne, boolean,
  link,etc.)

Des exemples
- boolean
- menu dropdown (menu déroulant)
- fichier ??? (je sais pas si cela est possbible).

@todo voir le submodule variable_views
