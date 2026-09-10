---
icon: house-blank
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/V0wnnNldc0tX2hQVrVxU/instrucciones-de-uso/crear-una-instalacion
---

# Créer un Établissement

{% hint style="info" %}
La première étape pour effectuer un calcul d'écart de salaire vital est de créer un Établissement.&#x20;
{% endhint %}

#### **Directives pour les installations multi-sites**

La règle générale est de créer une installation pour chaque site de production.

Plusieurs sites de production ne peuvent être combinés sous une seule installation que lorsque TOUS les sites sont gérés sous le même système de paie et :

* produire les mêmes produits, et
* les salaires ou les salaires unitaires sont les mêmes, et
* le nombre moyen d'unités travaillées sur une période donnée est le même (sans grandes variations de productivité), et
* Les régimes de bonus et d'avantages en nature sont les mêmes, et
* Ils sont tous situés dans la même région et partagent la même estimation du salaire vital.&#x20;

#### Instructions pour créer une installation

Allez dans la vue Installations et cliquez sur le bouton _+ Créer une installation_ en haut à droite.

{% hint style="info" %}
Le menu horizontal supérieur vous indique l'étape en cours et l'état de chaque phase du processus.
{% endhint %}

{% stepper %}
{% step %}
### Informations sur la localisation

Vous devrez d'abord fournir des informations sur l'emplacement de l'établissemetn en sélectionnant un pays et une région dans les listes déroulantes. Ces informations permettront à l'outil de proposer les bonnes estimations du salaire vital.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.44.53.png" alt=""><figcaption></figcaption></figure>

Entrer le nom de la ville ou du village est optionnel.

Cliquez sur Suivant pour passer à l'étape 2.
{% endstep %}

{% step %}
### Étape 2 : Informations sur l'installation

L'étape suivante consiste à entrer le nom de l'Établissement et à choisir la monnaie.

La liste déroulante Devise vous permettra de sélectionner la monnaie locale ou le dollar américain. Il est fortement recommandé de choisir la monnaie locale puisqu'elle est celle utilisée pour calculer les estimations du salaire vital. Choisir un autre devise réduira la précision de vos calculs en raison de l'impact des taux de change variables.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.48.37.png" alt=""><figcaption></figcaption></figure>

Vous avez également la possibilité d'inclure toute information supplémentaire que vous jugez pertinente dans le champ _Description_. Par exemple, vous pouvez noter ici que certains employés de la paie sont partagés avec un autre établissement.

Notez qu'une fois sauvegardées, les informations des étapes 1 et 2 ne peuvent pas être modifiées pour préserver l'intégrité des données.

Cliquez sur Suivant pour passer à l'étape 3.
{% endstep %}

{% step %}
### Étape 3 : Secteur et produits     &#x20;

Ensuite, on vous demandera de choisir un secteur dans une liste déroulante. Si vous ne trouvez pas votre secteur dans la liste, sélectionnez _Autre_. Veuillez noter qu'une fois sauvegardé, vous ne pourrez plus changer de secteur.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.49.12.png" alt=""><figcaption></figcaption></figure>

Pour saisir les produits fabriqués sur l'usine, tapez le nom du produit, sélectionnez le produit dans la liste déroulante, puis appuyez sur _Entrée_ ou sur le  bouton _+ Ajouter_ à droite. Vous pouvez inclure autant de produits que vous le souhaitez.

{% hint style="info" %}
La liste déroulante de _Produits_ est uniquement disponible une fois que vous avez sélectionné un _Secteur_.
{% endhint %}

Une fois les produits saisis, cliquez sur _Suivant_ pour passer à l'étape 4.

### Étape 4 : Aperçu

Vous verrez un aperçu des informations saisies jusqu'à présent. Veuillez examiner attentivement les informations car, une fois l'établissement sauvegardée, la plupart des détails ne peuvent pas être modifiés pour préserver l'intégrité des données. Vous ne pourrez modifier que la liste des produits et la description.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.51.51.png" alt=""><figcaption></figcaption></figure>

Cliquez sur Enregistrer l'ëtablissement pour créer l'installation.

Une fois l'établissement créée, un menu apparaîtra avec un aperçu des données saisies et trois boutons en haut à droite, vous permettant de _Modifier_ ou _Supprimer_ l'établissement ou de _Créer un Calcul d'écart du salaire vital._
{% endstep %}
{% endstepper %}
