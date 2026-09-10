---
icon: arrows-down-to-people
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
---

# Demandes de collaboration

La collaboration est essentielle pour garantir un salaire vital aux travailleurs du monde entier.

La fonctionnalité Collaboration permet un partage de données sécurisé, évitant ainsi le téléchargement et le partage de calculs via des processus externes. Ce gain de temps est précieux et garantit la confidentialité des données.

Les acheteurs peuvent envoyer des invitations aux fournisseurs directement depuis l'outil. Les fournisseurs ne reçoivent une demande de connexion et de partage de données qu'après avoir donné leur consentement explicite.

<details>

<summary><strong>Protection des données</strong></summary>

Nous avons développé cette fonctionnalité avec des mesures de protection des données renforcées afin de garantir un processus d'échange de données sécurisé, transparent et contrôlé par l'utilisateur :

* Les acheteurs doivent fournir deux informations valides : soit l'identifiant de l'Établissement et l'adresse e-mail de l'utilisateur, soit l'identifiant de l'établissement et l'identifiant Matrice, tous deux fournis par le fournisseur. Si ces informations ne correspondent pas, la requête ne peut être envoyée, garantissant ainsi que seules les connexions autorisées sont tentées.
* Un consentement explicite est requis avant tout partage de données : cette demande de consentement est intégrée à la requête d'invitation. Les données brutes ne sont jamais partagées sans l'accord préalable de l'utilisateur.
* Le fournisseur reste pleinement propriétaire des données : l'utilisateur a le droit d'accorder ou de révoquer l'accès à tout moment, même après avoir donné son consentement initial.

</details>

<details>

<summary><strong>Processus de collaboration</strong></summary>

Le processus de collaboration comprend quatre étapes :

{% stepper %}
{% step %}
### Réception d’une invitation

Si vous avez été invité par un acheteur, vous recevrez une notification par courriel.

En cliquant sur le lien, vous serez redirigé vers la Matrice Salariale, où vous devrez vous connecter.
{% endstep %}

{% step %}
### Accès à l’onglet « Collaborations »

Si vous avez reçu une invitation d’un acheteur, une nouvelle section « Collaborations » apparaîtra dans le panneau de navigation de gauche, avec un compteur indiquant le nombre de nouvelles demandes reçues.

Cliquez sur « Collaborations » pour accéder aux détails des demandes reçues.
{% endstep %}

{% step %}
### Vérification de la demande

Vérifiez que l’acheteur fait bien partie de la chaîne d’approvisionnement et la période pour laquelle il a demandé la collaboration.

Cliquez sur la flèche à côté de « Ce que l’acheteur verra » pour accéder aux autorisations incluses dans la demande :

* Visibilité complète des données de l’établissement ou des moyennes uniquement.
* Consentement au partage avec les auditeurs (demandé ou non).
* Consentement au partage des données de contribution au salaire minimum vital (demandé ou non).
{% endstep %}

{% step %}
### Approuver ou refuser

Après avoir examiné les détails de la demande, vous pouvez sélectionner « Approuver » ou « Refuser ».

En cas de refus, il vous sera demandé d'indiquer le motif afin de fournir un contexte à l'acheteur. Si vous êtes globalement d'accord avec la demande, à l'exception d'un point précis, il est recommandé de la refuser en précisant le motif, afin que l'acheteur puisse formuler une demande mise à jour.
{% endstep %}
{% endstepper %}

</details>
