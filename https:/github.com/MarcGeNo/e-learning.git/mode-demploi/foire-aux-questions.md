---
description: Réponses aux questions fréquemment posées reçues au service d'assistance
icon: seal-question
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
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
      https://app.gitbook.com/s/V0wnnNldc0tX2hQVrVxU/instrucciones-de-uso/preguntas-frecuentes
---

# Foire aux questions

{% hint style="info" %}
Utilisez le moteur de recherche pour trouver la réponse à votre question !
{% endhint %}

<details>

<summary> <strong>1 INFORMATIONS DE BASE</strong></summary>

#### 1.1  Qu'est-ce que l'identifiant de l'installation ?

Pour faciliter l'identification des établissements dans la Matrice Salariale, l'outil génère automatiquement un code (ID d'installation) pour chaque nouvelle installation créée (par exemple #CR001776). Les deux premières lettres correspondent au code pays

#### 1.2  Pourquoi la Matrice Salariale fonctionne-t-elle avec l'année civile complète précédente ?

Utilisation des données de paie d'une année civile complète :

1. Garantit que les données couvrent toutes les saisons de production. Cela signifie capturer la main-d'œuvre saisonnière et migratoire, qui tend à être la plus vulnérable.
2. Cela correspond à la plupart des exercices fiscaux et fiscaux.
3. Est en accord avec la plupart des conventions collectives basées sur l'année civile.
4. Est en accord avec la plupart des contrats de travail basés sur l'année civile.
5. Correspond à la plupart des cycles de certification et à la référence des années civiles.
6. Est en accord avec la plupart des méthodologies d'estimation du salaire vital (référence basée sur l'année civile).

#### 1.3 Notre exercice fiscal s'étend d'avril à mai. Puis-je saisir les données de paie en fonction de l'exercice fiscal, au lieu de l'année civile ?

L'IDH recommande de saisir les données de paie pour l'année civile complète, car les estimations des salaires vitaux sont basées sur les années civiles. Cependant, certains systèmes de certification peuvent permettre la saisie de données en fonction de l'exercice fiscal, donc si vous prévoyez d'utiliser ces calculs pour la certification, nous recommandons de vérifier cela auprès de l'organisme de certification.

#### 1.4 Dans notre établissement, selon la convention collective, tous les travailleurs bénéficient de 6 jours de congés payés en plus de ceux requis par la loi. Comment la rémunération pour ces 6 jours supplémentaires de congés payés devrait-elle être inscrite ?

a) Si tous les employés ont droit à ces jours de congé supplémentaires, ajouter les heures correspondantes pour ces 6 jours dans le champ « Nombre minimum d'heures de congé annuel payé pour un travailleur » sur la page « Informations de base ». Dans ce cas, le nombre total de semaines de vacances est de 3, donc vous devez entrer = 3\* heures de travail hebdomadaires régulières. Ajoutez à cela le salaire de ces jours de congés payés ainsi que le reste du salaire.

b) Si seuls certains employés ont droit à ces jours de congé supplémentaires, pour garantir des calculs précis, ces jours supplémentaires doivent être considérés comme des congés personnels payés, et les heures correspondantes doivent être inscrites comme heures régulières travaillées et le salaire comme salaire perçu.

#### 1.5 L'établissement a subi une inondation et a été contraint de suspendre l'emploi de 25 % des effectifs pendant deux mois. Comment cette situation devrait-elle être reflétée dans la Matrice Salariale ?

La période d'inactivité doit affecter tous les travailleurs de l'établissement pour être considérée comme un congé obligatoire non payé, car ce point de données sert à calculer le nombre maximal d'heures annuelles ordinaires de l'ensemble de la main-d'œuvre.

Puisque l'établissement n'a pas mis tous les contrats en suspens, mais seulement certains travailleurs, ces heures ne doivent PAS être considérées comme des « heures de congé obligatoire non payé ». Si les congés pour ces travailleurs étaient inscrits dans le champ des « heures de congé obligatoire non payé », la matrice considérerait que le temps maximal de travail de l'année pour tous les travailleurs de l'établissement était de 10 mois et ajusterait donc les salaires de tous les travailleurs qui n'ont pas travaillé l'année complète ou à temps partiel à ce qu'ils auraient gagné s'ils avaient travaillé 10 mois,  diviser par douze pour calculer le salaire mensuel à temps plein comparable à la valeur de référence.

Pour garantir des calculs corrects, pour les 25 % de la main-d'œuvre concernée, inscrivez les heures de travail suspendu comme des heures travaillées à 0 salaire. Ces travailleurs présenteront probablement un écart salarial décent reflétant leur situation particulière.

#### 1.6 Notre exploitation est fermée pendant 9 mois durant la basse saison. Devons-nous considérer ces 9 mois comme une période de congé obligatoire non rémunéré  ?

Non. La période de fermeture des exploitations et de mise à pied des employés jusqu’à la saison suivante n’est pas considérée comme un « congé obligatoire non rémunéré ».

Si ces heures étaient enregistrées comme congé obligatoire non rémunéré, l’outil les traiterait comme des heures non travaillées lors du calcul du salaire à l’équivalent temps plein, et le salaire correspondant serait inférieur à ce qu’il devrait être.&#x20;

Par exemple, si la saison de production dure 3 mois, l’outil utilise le salaire enregistré pour ces 3 mois afin de calculer le salaire pour 12 mois de travail, puis le divise par 12 pour obtenir le salaire mensuel équivalent. Si les heures correspondant aux 9 mois étaient saisies comme congé sans solde obligatoire, l’outil considérerait que les travailleurs ont déjà effectué toutes leurs heures de travail annuelles et diviserait simplement le salaire des 3 mois par 12.&#x20;

Le congé obligatoire non rémunéré s’applique uniquement aux situations où tous les travailleurs sont employés par un établissement et ne sont pas autorisés à travailler.

</details>

<details>

<summary><strong>2 ESTIMATIONS DU SALAIRE VITAL</strong></summary>

#### 2.1 Quelle estimation du salaire vital devrais-je choisir ?

IDH recommande de n'utiliser que des salaires vitaux estimés selon des méthodologies reconnues par IDH. Vous pouvez utiliser le [chercheur d'estimations de salaire vital](https://salarymatrix.idhtrade.org/benchmark-finder/) IDH pour trouver les estimations disponibles pour votre région. Veuillez vous assurer de sélectionner l'estimation correspondant à la région de l'établissement et à l'année de rapport. Dans le cas où la valeur de référence choisie ne soit pas une donnée publique, vous devrez acheter l'accès à cette valeur.

#### 2.2 Que faire si aucune estimation du salaire vital n'est disponible pour ma région et l'année qui m'intéresse ?

Veuillez noter que l'IDH ne calcule pas d'estimations du salaire vital.

Si l'outil ne propose aucune estimation pour votre région et l'année concernée, veuillez contacter les [méthodologies d'estimation du salaire vital reconnues par l'IDH](https://www.idhsustainabletrade.com/idh-living-wage-identifier/) afin de vérifier leur disponibilité pour effectuer l'estimation.

</details>

<details>

<summary><strong>3 PAIE. SAISIE DES TRAVAILLEURS</strong></summary>

#### 3.1 Dois-je inscrire tous les travailleurs, ou puis-je inclure un échantillon d'ouvriers ?

L'IDH recommande d'inscrire tous les travailleurs de l'établissement. Cela inclut :

* Tous les travailleurs de l'établissement paient, y compris les employés de bureau et les superviseurs. Une exception peut être faite pour la haute direction, si leur salaire est bien supérieur au salaire vital (c'est-à-dire plus de deux fois).
* Travailleurs employés via des prestataires de main-d'œuvre ou des intermédiaires (par exemple, agences de travail temporaire, recruteurs, courtiers en main-d'œuvre...).
* Les travailleurs effectuant des activités dans l'établissement, de façon permanente ou régulière, sont externalisés à des prestataires de services (par exemple, cantine, sécurité, maintenance).

Cependant, certains programmes de certification peuvent avoir des exigences différentes, alors assurez-vous de vérifier auprès de votre auditeur

IDH recomienda inscribir a todos los trabajadores de la instalación. Esto incluye:

* Todos los trabajadores en nómina, incluidos los empleados de oficina y supervisores. Se puede hacer una excepción para la alta dirección, si su salario está muy por encima del salario vital (es decir, más del doble).
* Trabajadores empleados a través de proveedores de mano de obra o intermediarios (por ejemplo, agencias de trabajo temporal, reclutadores, intermediarios de mano de obra...).
* Los trabajadores que realizan actividades en la instalación, de forma permanente o rutinaria, subcontratados a proveedores de servicios (por ejemplo, cantina, seguridad, mantenimiento).

Sin embargo, algunos programas de certificación pueden tener requisitos diferentes, así que asegúrese de consultarlo con la certificadora.

#### 3.2 Devons-nous inclure les apprentis et étudiants universitaires dans les stages industriels dans la matrice salariale ?

Les apprentissages qui font partie d'un programme de formation formel (tels que les parcours académiques, les programmes d'intégration ou les initiatives de développement des compétences dans le cadre de programmes sociaux) et/ou qui ont lieu dans le cadre d'accords de formation tripartites plutôt que des contrats de travail classiques peuvent être exclus de la Matrice Salariale. Ces rôles sont considérés comme des formations et, selon la méthodologie du salaire vital, ne sont pas censés couvrir le salaire vital, leur objectif principal étant l'apprentissage et le développement des compétences plutôt que le plein emploi.

Cela dit, appliquer les principes du salaire vital aux apprentissages est considéré comme une bonne pratique recommandée. Dans de nombreux cas, les entreprises qui l'ont fait ont constaté des rendements positifs, notamment des taux de rétention plus élevés, un engagement plus fort et des transitions plus fluides vers le marché du travail régulier.

Cependant, si le poste fait partie d'un parcours de progression professionnelle et relève d'un contrat de travail classique, ces travailleurs doivent être inclus dans la Matrice Salariale.&#x20;

#### 3.3 Un travailleur indépendant, comme un formateur en premiers secours, qui visite occasionnellement la ferme (peut-être une fois par an) devrait-il être inclus dans la Matrice Salariale ?

Non. Les travailleurs indépendants qui fournissent des services occasionnels, comme un cours de premiers secours une fois par an, n'ont pas besoin d'être inclus. L'outil est axé sur les services qui participent régulièrement à l'exploitation de l'établissement, pendant une certaine période chaque année ou de manière soutenue. Ce type de services ponctuels, non opérationnels, dépasse le cadre de l'outil, bien qu'ils puissent être importants pour la gestion globale de l'établissement

#### 3.4 Que se passe-t-il lorsque deux centres de production partagent des travailleurs, c'est-à-dire que la paie est unifiée, mais que les travailleurs travaillent dans deux lieux différents ? Quels impacts auraient la regroupement des travailleurs en une seule installation lorsque chaque centre de production vend à différents acheteurs ?

Lorsque deux centres de production sont sous le même système de paie, ont la même structure salariale et la même productivité, et sont situés dans la même région (partagent la même estimation du salaire vital), ils peuvent être considérés comme une seule installation.

Si un client achète uniquement dans l'un de ces deux centres de production et souhaite calculer l'écart salarial décent correspondant à cet emplacement spécifique, le pourcentage de temps passé par chaque travailleur dans chaque lieu doit être connu et les calculs correspondants doivent être effectués en dehors de l'outil.

L'autre option est de créer deux établissements distincts et de répartir les heures travaillées et la rémunération reçues entre les deux, en fonction du temps travaillé sur chaque site. Dans ce cas, la Matrice Salariale ajustera la rémunération à l'équivalent à temps plein et calculera l'écart de salaire vital par établissement.

#### 3.5 Comment devons-nous procéder lorsque le même nom d'entreprise possède plusieurs centres de production mais une seule usine d'emballage, fournissant le service d'emballage à toutes les installations ? Comment allons-nous entrer les ouvriers de l'emballage ?

Les travailleurs de l'emballage doivent être inclus dans les calculs de l'installation où se trouve l'usine d'emballage. Les autres installations doivent seulement inclure le personnel non partagé et indiquer, dans le champ « Description » de l'onglet « Informations de base », que le personnel de l'usine d'emballage a été enregistré dans une autre installation, indiquant le numéro d'identification correspondant..

#### 3.6 Que dois-je faire si je ne trouve pas une zone de travail existante dans mon établissement dans le menu déroulant des zones de travail ?

Si vous ne trouvez pas un espace de travail qui vous convient, il vous suffit de sélectionner « autre » dans le menu déroulant.

#### 3.7 Pourquoi dois-je séparer les hommes et les femmes pour chaque catégorie professionnelle ?

Cela permet une analyse spécifique au genre, permettant d'identifier les écarts de salaire vital qui peuvent affecter un seul genre et qui pourraient autrement passer inaperçus. Elle permet également d'identifier les écarts salariaux potentiels entre hommes et femmes.

#### 3.8 Si je décide d'inscrire tous les travailleurs individuellement dans la Matrice Salariale au lieu de les classer par catégories de postes, dois-je lister les personnes par leur nom ?

Non. Merci de ne pas lister les personnes par leur nom. Nous recommandons d'attribuer à chaque travailleur un code interne (par exemple un numéro unique) à l'avance et d'utiliser ces codes dans cet outil.

#### 3.9 Dois-je inscrire des travailleurs qui sont sur la paie de l'établissement mais qui ne travaillent pas en raison d'un statut d'invalidité ?

Vous pouvez les exclure s'ils n'ont pas travaillé durant l'année de référence, puisqu'ils n'ont pas participé à l'exploitation de l'établissement.

#### 3.10 Comment devons-nous gérer les effets d'un fort roulement de l'outil ?

En cas de fort taux de rotation, vous pouvez inclure tous les employés individuellement ou les regrouper par poste, en additionnant les heures travaillées et la rémunération versée pour un poste occupé par plusieurs employés au cours de l'année. Si vous optez pour le regroupement par poste, toute rémunération supplémentaire résultant de ce regroupement doit être exclue (par exemple, si trois employés ont été regroupés et que tous trois ont reçu une prime d'embauche, cette prime ne peut être saisie qu'une seule fois).

</details>

<details>

<summary><strong>4 SALAIRES ET HEURES</strong></summary>

#### 4.1 Comment devrais-je inclure les déductions légales sur la salaire dans la matrice salariale ?

Les déductions légales de la rémunération correspondant à un salaire vital sont déjà prises en compte dans l'estimation du salaire vital. Par conséquent, les salaires bruts doivent être inscrits dans la Matrice Salariale.

#### 4.2 Comment dois-je saisir les paiements légaux, tels que les assurances ou les cotisations aux régimes de sécurité sociale et aux fonds de pension, versés par l'employeur dans la Matrice Salariale ?

Les cotisations de l'employeur exigées par la loi, telles que pour les programmes de sécurité sociale, l'assurance chômage et l'assurance accidents du travail/blessure, ne devraient pas être incluses comme rémunération car elles n'augmentent pas le revenu disponible des travailleurs dans un délai d'un an.

De plus, l'impact de ces contributions sur le coût de la vie est déjà pris en compte dans l'estimation du salaire vital.

#### 4.3 Les Fumigator ont des horaires de travail quotidiens plus courts en raison des réglementations sanitaires et de sécurité. Comment devrais-je gérer cela ?

Pour garantir des calculs corrects, ajustez les heures ordinaires de travailleurs de ces travailleurs aux heures de travail régulières comme suit : Heures normales travaillées = heures de travail régulières quotidiennes \* nombre de jours travaillés. Sinon, l'outil gonflerait la rémunération de ces travailleurs à l'équivalent temps plein.

#### 4.4 Comment la Matrice Salariale calcule-t-elle la rémunération des travailleurs à temps partiel et saisonniers/temporaires ?

La Matrice Salariale estime la rémunération mensuelle qu'un travailleur à temps partiel ou saisonnier/temporaire gagnerait s'il travaillait à temps plein, toute l'année, en proratalant sa rémunération à la semaine de travail régulière ou à 48 heures par semaine, selon la moindre hypothèse.

Vous pouvez trouver plus d'informations sur les calculs[ ici](../a-propos-de-la-matrice-salariale/formules-de-calcul.md).

#### 4.5 Certains travailleurs de l'établissement se portaient volontaires pour travailler pendant leurs congés annuels payés afin d'obtenir un revenu supplémentaire. Comment cette rémunération supplémentaire sera-t-elle inscrite dans la matrice salariale ?

Les travailleurs devraient pouvoir gagner un salaire vital sans avoir à travailler pendant leurs congés annuels payés ou leurs jours fériés. Par conséquent, les heures travaillées et la rémunération obtenues lors des congés annuels payés des jours fériés doivent être considérées comme des heures supplémentaires.&#x20;

Cela s'applique également dans la situation où la législation prévoit la compensation totale ou partielle des congés annuels payés et des jours fériés avec rémunération.

#### 4.6 Certains travailleurs en équipes doivent travailler les week-ends ou les jours fériés. La rémunération générée durant ces jours doit-elle être comptée comme des heures supplémentaires ?

Si le travail pendant les week-ends ou jours fériés est rémunéré par un congé payé, les salaires/heures sont considérés comme ordinaires.&#x20;

Si les week-ends ou jours fériés travaillés ne sont pas rémunérés par des congés payés mais par une rémunération (avec ou sans prime), les heures/rémunération seront considérées comme des heures supplémentaires.

#### 4.7  Peut-on inclure le coût des jours de repos compensatoires pour les travailleurs ayant travaillé le week-end comme rémunération des travailleurs ?

Non, les jours de repos compensatoires sont une forme de compensation qui n'augmente pas le revenu du travailleur, ne réduit pas non plus le coût de la vie, et ne peut donc pas être considérée comme une rémunération pour un salaire vital.

#### 4.8  Si les salaires augmentent à un mois précis de l'année, comment cela devrait-il être reflété dans la matrice salariale ? Devons-nous utiliser la valeur la plus élevée ? Ou la moyenne ?

La Matrice Salariale utilise la rémunération totale perçue au cours d'une année civile, il n'est donc pas nécessaire de refléter d'éventuels changements de rémunération. Il suffit d'entrer le montant total reçu par le travailleur au cours de l'année.

#### 4.9 Comment dois-je procéder si la rémunération varie en fonction des années de service ?

Dans ce cas, vous pouvez séparer les travailleurs par catégories de poste selon le type de poste et les années de service selon leur variation salariale. Par exemple, vous pouvez regrouper les travailleurs ayant moins d'un an de service, entre 1 an et 3 ans de service, entre 3 ans et 5 ans de service, etc.

#### 4.10 Certains travailleurs sont payés à la pièce plutôt qu'au temps travaillé, et effectuent différentes tâches rémunérées à différents taux au cours de la journée. Comment dois-je saisir les salaires versés à ces travailleurs ?

La matrice salariale n'est pas conçue pour fonctionner avec des taux horaires, journaliers, hebdomadaires ou à la pièce. Au lieu de cela, elle utilise la rémunération totale reçue au cours d'une année civile complète et le total des heures travaillées cette année-là, par travailleur (ou la moyenne par catégorie de poste), pour calculer la rémunération mensuelle comparable à l'estimation du salaire vital.

Ainsi, vous n'avez pas besoin d'entrer des taux à la pièce ni d'effectuer des calculs complexes pour estimer les salaires annuels à partir de différents taux de rémunération. Il suffit d'entrer les salaires payés et les heures travaillées durant l'année de rapport pour chaque travailleur (ou la moyenne d'une catégorie de poste) obtenus à partir du système de paiement ou des registres de paie, sans tenir compte de la manière dont ces salaires ont été obtenus.

Pour les travailleurs à la pièce, cela signifie qu'il est nécessaire d'enregistrer à la fois le nombre d'heures supplémentaires et les salaires générés pendant ces heures supplémentaires, car, selon la méthodologie Anker qui exige que les salaires vitaux soient perçus pendant les heures de travail ordinaires, à un rythme normal, seule la rémunération générée pendant les heures de travail régulières est prise en compte.

#### 4.11 Taux de rémunération par pièce : Comment dois-je prendre en compte les différents niveaux de productivité lorsque les travailleurs sont payés « par pièce » ?

Intervenez individuellement des travailleurs pour évaluer la différence de productivité entre eux.&#x20;

Si cela est trop difficile, vous pouvez regrouper les travailleurs en plusieurs groupes différents de « travailleurs à la pièce » selon leur productivité moyenne – c'est-à-dire la moissonneuse à la pièce A ; moissonneuse à la pièce B ; etc. La productivité n'a pas besoin d'être exactement la même pour les travailleurs de chaque groupe. Vous pouvez regrouper les travailleurs ayant une fourchette de productivité similaire puis prendre une moyenne.

Il est toutefois important de rappeler que, selon la méthodologie Anker, la rémunération doit être acquise pendant les heures normales de travail, à un rythme normal ; par conséquent, la rémunération acquise à un rythme extraordinaire doit être écartée.

#### 4.12 Certains travailleurs à temps plein payés à la pièce travaillent volontairement moins que les heures de travail régulières légales hebdomadaires. Comment devons-nous gérer cela dans la Matrice Salariale ?

Les taux à la pièce, permettant de gagner un salaire vital en travaillant moins que les heures normales de travail, sont généralement liées à des tâches très exigeantes ou à des tâches comportant un risque associé à la santé et à la sécurité. De plus, la méthodologie exige que seule la rémunération perçue à un rythme de travail normal soit prise en compte. Il serait donc incorrect d'extrapoler la rémunération des travailleurs exceptionnellement productifs qui terminent leur journée de travail plus tôt.

Pour ces travailleurs, entrez les heures de travail régulières légales correspondantes au lieu des heures réellement travaillées (heures de travail régulières standard \* nombre de jours travaillés).&#x20;

#### 4.13 Peut-on inclure la rémunération correspondante aux congés payés (par exemple, deuil, maladie, invalidité, congés parentaux et de soins, jours d'ancienneté, représentation syndicale...) exigés par la loi ou convenus dans une convenrion collective de travail ?

Oui. Considérez les heures de ces congés personnels statutaires comme des « heures régulières travaillées » et incluez leur rémunération comme « Salaire gagné ».&#x20;

#### 4.14 Certains travailleurs étaient en congé maladie, payés en partie par l'établissement et en partie par la sécurité sociale. Comment devons-nous inclure cette rémunération dans le calcul ?

Inclure toute indemnisation reçue par les travailleurs, versée par l'employeur et par les systèmes de sécurité sociale, sous forme de « Salaire gagné ».

#### 4.15 Certains travailleurs reçoivent un revenu généré en une année au début de l'année suivante. Dans quelle année des données ces revenus devraient-ils être inclus ?

Pour les besoins de la matrice salariale, l'important est l'année où le travailleur a reçu l'argent et a donc pu l'utiliser pour couvrir les frais d'une vie décente. Par conséquent, quelle que soit l'année de la génération du revenu, il doit être inclus dans l'année où le paiement effectif a été effectué au travailleur.

#### 4.16 Certains employés, notamment ceux occupant des postes de direction, ne sont pas éligibles aux heures supplémentaires. Comment cela doit-il être pris en compte dans la grille salariale ?

Selon la méthodologie Anker, les employés doivent percevoir un salaire décent sans avoir à effectuer d'heures supplémentaires. Par conséquent, les heures supplémentaires non rémunérées doivent être saisies comme des heures normales non rémunérées, afin que l'outil puisse les intégrer au calcul de la rémunération comparable.

#### 4.17 La limite de temps de travail est-elle hebdomadaire ou journalière ? En Colombie, certains employés travaillent moins d'heures certains jours et plus d'autres, sans toutefois dépasser la limite hebdomadaire légale. Autrement dit, les heures supplémentaires effectuées un jour sont compensées par des heures non travaillées un autre jour, mais la durée hebdomadaire du travail ne dépasse pas la limite légale de 44 heures.

Généralement, la limite est hebdomadaire, dans les limites de la loi. En d'autres termes, si la limite légale de temps de travail journalier est dépassée et donne lieu à des heures supplémentaires, ces heures doivent être considérées comme telles. Elles doivent donc être inscrites comme telles.

#### 4.18 Pourquoi est-il nécessaire de déclarer les heures supplémentaires et leur rémunération correspondante si ces informations ne servent pas au calcul de l'écart de salaire vital ? À quoi servent ces informations ?

La définition d'un salaire vital indique que la rémunération doit correspondre à la durée normale du travail. L'outil n'utilise pas les heures supplémentaires et leur rémunération correspondante pour les calculs, mais ces informations :

* garantissent le suivi précis des heures supplémentaires effectuées ;
* facilitent la distinction entre la rémunération des heures supplémentaires et le salaire horaire normal ;
* facilitent la vérification, par les auditeurs, de la bonne mise en œuvre de l'outil.

#### <mark style="color:$primary;">4.19 Certains établissments calculent le temps de travail effectif en fonction des heures de pointage, et non du temps réellement travaillé. Cette méthode peut inclure les pauses prises pendant la journée de travail. Ces pauses doivent-elles être considérées comme faisant partie du temps de travail effectif ?</mark>

<mark style="color:$primary;">Les pauses prises pendant le poste de travail sont comptabilisées comme du temps de travail. En revanche, la pause déjeuner prise en dehors des heures de travail n'est pas comptabilisée comme du temps de travail.</mark>

</details>

<details>

<summary><strong>5 PRIMES</strong></summary>

#### 5.1 Comment savoir si un bonus donné peut ou non être inscrit dans le calcul ? Quelles caractéristiques doivent-ils avoir pour être éligibles ?

Pour qu'un bonus soit éligible, il doit être un bonus régulièrement attribué. La prime doit être attendue par les travailleurs au début de la saison et ne pas être à la discrétion de l'employeur. Le travailleur doit pouvoir anticiper le montant de la prime auquel il ou elle a droit. La prime doit être versée en espèces. Ces principes guidant la matrice salariale sont tirés de la méthodologie® Anker. Plus d'informations sur la manière dont la méthodologie Anker aborde les bonus sont disponibles ici : https://www.elgaronline.com/view/9781786431455/chapter15.xhtml&#x20;

* Exemple de prime qualifiante qui ne change pas : les travailleurs de la catégorie A reçoivent une prime de fin d'année chaque année. La prime est toujours de 10 % du salaire annuel du travailleur.
* Exemple de bonus de qualification qui change : les bonus de production, qualité et assistance peuvent varier d'un jour à l'autre. Cependant, les taux et les conditions des primes ne varient pas et sont compris à l'avance par les employés.
* Exemple de prime éligible (en plus de l'exigence légale) : Un employeur propose un indemnité de départ pour les travailleurs. L'employeur contribue 10 % de plus que ce qui est légalement requis ET les travailleurs peuvent accéder au compte à tout moment et dépenser l'argent comme ils le souhaitent, sans intérêts ni pénalités. Le package de départ est une obligation légale nationale. Dans ce cas, tant que les travailleurs peuvent accéder à l'argent et dépenser librement, comme décrit, la contribution de 10 % au-delà de l'exigence légale peut être incluse comme bonus dans le calcul.
* Exemple de prime non éligible (exigence légale) : Indemnités de départ telles que requises par la loi.
* Exemple de prime non éligible (à la discrétion de l'employeur) : À la fin de l'année dernière, l'établissement a décidé d'accorder à tous les travailleurs une prime surprise équivalente à 10 % de leur salaire.
* Exemple de prime partiellement qualifiante : Les travailleurs reçoivent des primes de productivité qui varient selon les ressources disponibles, mais qui sont garanties d'être au moins 5 % des salaires lorsque les objectifs de productivité sont atteints. Les objectifs de productivité sont atteints chaque année mais ont été dépassés cette année. Dans ce cas, la prime de qualification est de 5 % seulement.

#### 5.2 Que devons-nous faire lorsqu'une prime non liée à la dépendance du temps est versée dans un mois précis et que le travailleur a rejoint après ou est parti avant le paiement de la prime ? Peut-on quand même l'inclure ?

Non. Les primes doivent être saisies uniquement pour les travailleurs qui les ont reçues (le montant total ou une partie proportionnelle). Sinon, ces primes pourraient être attribuées à des travailleurs qui n'auront jamais le droit de les recevoir. Par exemple, les travailleurs saisonniers embauchés pendant la haute saison ne recevront jamais les primes fixes versées pendant la basse saison.

La même directive s'applique aux prestations en nature accordées à un moment précis, comme les allocations de matériel scolaire.

#### 5.3 L'établissement offre des incitations aux employés dont les enfants ont la meilleure moyenne scolaire. Ce sont des récompenses financières versées à environ 60 étudiants chaque année. Ces récompenses peuvent-elles être incluses dans les primes ?

Non, ces récompenses ne doivent pas être saisies dans les calculs. Selon les principes du salaire vital, pour qu'une prime soit considérée comme faisant partie de la rémunération comparable à un salaire vital, elle doit être attendue et garantie. Les récompenses liées aux résultats scolaires des enfants ne répondent pas à cette exigence car la récompense n'est pas garantie puisqu'elle ne dépend pas uniquement des efforts de l'employé.

#### 5.4 Peut-on inclure des primes pour les fêtes ?

Les primes de congé ne peuvent être incluses que s'il s'agit de paiements supplémentaires au salaire de base pour des congés, accordés chaque année coïncidant avec une période de vacances.

La rémunération correspondant aux jours de congé payés doit être inscrite sous forme de salaire.

Les congés non payés ne devraient pas être inclus en prime puisqu'ils n'augmentent pas le salaire net par rapport à ce que gagnent les travailleurs à temps plein.

#### 5.5 Pouvons-nous inclure des bons comme bonus, et si oui, comment ?

Les bons ne peuvent être inclus en bonus que s'ils sont essentiellement équivalents à ceux de l'argent et peuvent facilement être utilisés pour couvrir n'importe quel coût choisi par le travailleur (par exemple, logement, loisirs, nourriture, etc.).

#### 5.6 Les prêts à faible taux d'intérêt, qui bénéficient aux employés, peuvent-ils être inclus en prime ?

Non. Les prêts ne sont pas éligibles. Les travailleurs doivent pouvoir couvrir les coûts d'un niveau de vie basique mais décent au cours d'une année donnée, et d'une année après l'autre, sans avoir à dépendre des prêts.

#### 5.7 Notre établissement est certifié Fairtrade et nous offrons une prime annuelle aux employés. Peut-on inscrire cette prime en bonus ?

Non, la prime Fairtrade ne fait pas partie intégrante de la rémunération des travailleurs et ne peut donc pas être considérée comme une prime. La prime annuelle peut être détaillée dans la section Suppléments/Contributions, pour information uniquement.

#### 5.8 Les contributions aux fonds de retraite ou de départ peuvent-elles être incluses comme bonus ?

En général, non. Cela repose sur le principe du salaire vital selon lequel les travailleurs devraient pouvoir gagner un salaire suffisant pour atteindre un niveau de vie basique et décent en une année civile, sans avoir à contracter de prêts. Ils devraient aussi pouvoir planifier l'année.

Le seul cas où les pensions, fonds de départ et autres paiements similaires peuvent être comptabilisés est lorsqu'un employeur contribue à ces fonds supérieurs à ce qui est exigé par la loi. Dans ce cas, le montant supérieur au montant légalement requis peut être inclus _SI_ les travailleurs peuvent accéder à ces fonds chaque année, sans pénalités, paiements d'intérêts ou restrictions sur la façon dont l'argent est dépensé ET que les travailleurs et leurs représentants conviennent que cela doit compter pour les salaires.

#### 5.9 Les indemnités de départ anticipées peuvent-elles être incluses comme une prime dans la matrice salariale ?

IDH recommande que les indemnités de départ (qu'elles soient payées à l'avance ou non) ne soient pas incluses comme primes en espèces pour les raisons suivantes :

1\)     Les indemnités de départ sont en principe créées pour soutenir les travailleurs lors de la résiliation de leur contrat. Ces paiements sont classés comme des paiements différés qui, selon la méthodologie® d'Anker, ne doivent pas être inclus dans le calcul de la rémunération en vigueur à comparer aux estimations du salaire vital.

2\)     Les indemnités de départ anticipées doivent s'ajouter à la capacité des travailleurs à couvrir les frais de subsistance. En raison d'un manque de salaires, les travailleurs peuvent être contraints de retirer leurs fonds de départ, ce qui pourrait les rendre financièrement vulnérables en cas de perte d'emploi. Même si la législation du pays permet aux travailleurs de pouvoir encaisser leurs indemnités de départ à l'avance s'ils le souhaitent (pour des fins spécifiques prévues par la loi ou pour tout usage qu'ils souhaitent), et que sa mise en œuvre est conforme au dialogue social et aux conventions collectives, les travailleurs devraient tout de même pouvoir couvrir leurs dépenses mensuelles,  sans avoir à encaisser leurs indemnités de départ à l'avance.

3\)     Inclure les indemnités de départ (qu'elles soient anticipées ou non) dans la rémunération mensuelle pour la comparaison avec les salaires vitaux est considéré comme non conforme, selon les directives d'audit de l'IDH pour la vérification des écarts de salaire vital. De plus, dans le secteur bananier par exemple, des dispositifs comme Fairtrade et Rainforest Alliance considèrent l'inclusion de l'indemnité de départ dans le calcul de la rémunération en vigueur comparée aux salaires vitaux comme un non-respect.

Ce qui précède est une recommandation. En fin de compte, il sera important que l'utilisateur décide avec ses alliés (partenaires de la chaîne d'approvisionnement, syndicats, organismes d'audit et programmes de conformité sociale applicables) de la manière de procéder.

Pour plus d'informations concernant ces directives, veuillez lire ce [rapport](https://idh.org/resources/recommendation-about-advanced-severance-payments).

#### 5.10 Les travailleurs saisonniers de notre site ont droit à une indemnité de départ à la fin de leur contrat saisonnier, même s'ils sont réembauchés dans quelques mois. Ce paiement est une obligation légale. Peut-on compter cela comme une rémunération pour le calcul des écarts de salaire vital ?

Non. L'indemnité de départ ne devrait jamais être incluse dans les calculs comme un paiement vers un salaire vital. Cela s'explique par le fait que les indemnités de départ sont destinées à couvrir les coûts pendant les périodes où les travailleurs sont sans emploi ou entre deux emplois. Le processus d'embauche et de licenciement réguliers crée un environnement de travail instable et épuise les fonds de départ disponibles pour ces travailleurs dans le cas malheureux où les travailleurs seraient effectivement licenciés indéfiniment (par exemple, si l'établissement devait fermer, ou si le travailleur ne pouvait plus exercer ses fonctions).

#### 5.11 Le partage des bénéfices peut-il être inclus en primes ?

En général, non, car ce n'est pas un paiement annuel garanti. Cependant, certaines exceptions peuvent être faites si le bénéfice a été réalisé de manière constante et partagé avec les employés pendant plusieurs années (par exemple, 5 ans). Dans ce cas, le montant le plus faible de la part des bénéfices sur une période convenue pourrait potentiellement être inclus, si les travailleurs et leurs représentants l'acceptent comme rémunération convenu..

#### 5.12 Prime liée à l'affluence : est-ce compté pour un salaire vital ?

Oui, cela compte et peut être inclus comme bonus dépendant du temps dans la section bonus.

#### 5.13 Certains ouvriers travaillent de nuit. Le supplément de salaire de nuit peut-il être inclus en prime ?

Un salaire vital doit être gagné en semaine de travail standard ; par conséquent, le supplément de rémunération du service de nuit ne peut être compté comme rémunération ordinaire que si les équipes de nuit se situent dans leurs heures de travail contractuelles habituelles (sans heures supplémentaires). Dans ces cas, le supplément doit être inclus sous forme de salaire, plutôt que de prime.&#x20;

Cela s'applique à tout autre supplément salarial issu de circonstances particulières pendant les heures de travail normales (par exemple, supplément de salaire pour travail sale).

#### 5.14 L'établissement offre un paiement en espèces en cas de naissance, de décès d'un membre de la famille ou de mariage. Ces montants peuvent-ils être inclus dans d'autres bonus ?

Non. Les prestations ne peuvent être incluses dans les calculs que si elles sont accordées chaque année. Ce n'est pas le cas des subventions de naissance, de décès ou de mariage, et elles ne peuvent donc pas être considérées comme une rémunération.

#### 5.15 L'établissement verse une prime rétroactive lors de la signature d'une convention collective qui est versée tous les deux ou quatre ans. Ce paiement peut-il être inclus comme une prime dans l'année où il a été versé ?

Si cela est une pratique courante dans l'établissement, ce paiement peut être considéré comme attendu et garanti, et par conséquent, le montant peut être inclus comme une prime pour l'année où il a été versé, pour les travailleurs qui le perçoivent.

#### 5.16  Les allocations en espèces sont-elles un bonus ou un bénéfice en nature ?

Si les travailleurs reçoivent des allocations en espèces au lieu d'avantages sociaux, et qu'ils peuvent dépenser cette allocation comme il le souhaite (même si elle peut être destinée à un but spécifique), alors l'allocation en espèces devrait être considérée comme une prime

Cependant, si le travailleur doit fournir une preuve que l'allocation a été utilisée pour payer à un certain but (par exemple, des reçus de loyer ou des contrats doivent être fournis pour recevoir l'allocation en espèces), alors le montant reçu par le travailleur doit être inscrit comme un bénéfice en nature.

Les indemnités en espèces peuvent être incluses en primes si elles respectent les principes généraux, c'est-à-dire qu'elles sont garanties, versées au cours de l'année et ne nécessitent pas de travail au-delà des heures de travail légales ordinaires. Les indemnités versées uniquement lors d'occasions spéciales, telles que les funérailles, les mariages, la paternité et autres, ne seront donc pas incluses.

#### 5.17 Dans notre exploitation, les ouvriers perçoivent une prime de productivité mensuelle dont le montant varie en fonction de la production de moules du mois. Comment devons-nous intégrer ce versement dans l'outil ?

Pour être comptabilisée comme rémunération, la prime doit être prévisible et garantie. S'agissant d'une prime variable liée à la production et donc non complétement garantie, nous recommandons d'inclure le montant annuel le plus bas versé au cours des 5 dernières années, à titre de prime non liée à la durée du travail.

#### 5.18 Si l'on saisit les données des employés individuellement, est-il possible d'ajouter les indemnités en espèces perçues par un employé donné au cours de l'année ?

Les indemnités spécifiques versées périodiquement, telles que l'aide à la garde d'enfants calculée en fonction du nombre d'enfants, peuvent être ajoutées. Cependant, le montant total versé par l'employeur doit être réparti entre tous les employés.

En effet, les montants inclus dans le salaire de subsistance estimé correspondent à ceux d'une famille type et, par conséquent, pour le calcul de l'écart de salaire vital, les revenus dépendant de la situation familiale doivent être répartis entre tous les employés.

#### <mark style="color:$primary;">5.19 Nous offrons à tous nos travaillleurs un bon annuel d'un montant fixe. Devons-nous saisir cela comme une prime, ou comme un avantage en nature ?</mark>

<mark style="color:$primary;">Si le bon peut être échangé contre tout type de bien sans restriction, alors il équivaut à un paiement en espèces et sera comptabilisé comme une prime.</mark>

<mark style="color:$primary;">Si le bon ne peut être échangé que contre des types restreints de biens, il peut alors être inclus comme avantage en nature, à condition que les biens soient inclus dans la liste des coûts pris en compte pour l'estimation du salaire vital (nourriture, transport...).</mark>

<mark style="color:$primary;">Gardez à l’esprit que, dans tous les cas, le bon doit être facilement échangeable, et appréciée et utilisée par la majorité des travailleurs.</mark>

</details>

<details>

<summary><strong>6 AVANTAGES EN NATURE: ELIGIBILITÉ</strong></summary>

#### 6.1 Que faire si un avantage en nature conforme aux exigences est proposé dans mon établissement, mais que je ne le vois pas dans l'outil ?

En principe, tous les avantages en nature éligibles sont listés dans l'outil. Cependant, certaines organisations peuvent offrir des prestations en nature réduisant le coût d'une vie décente qui ne relèvent pas des 6 catégories proposées par l'outil. Par exemple, ils peuvent fournir des vêtements pour un usage personnel ou certaines assurances considérées comme coût dans l'estimation du salaire vital.&#x20;

Si l'IKB en question respecte tous les principes de la rémunération, il peut être inclus dans l'une des catégories prévues pour l'IKB (sauf le logement). Veuillez noter la section utilisée, afin de pouvoir expliquer pleinement la valeur IKB de la catégorie choisie à l'auditeur.

#### 6.2 Si une prestation en nature est exigée par la loi, puis-je quand même l'inclure dans le calcul de l'écart salarial décent ?

La règle générale est que la valeur des prestations en nature exigées par la loi ne peut être incluse comme rémunération dans le calcul. La raison en est que les estimations du salaire vital prennent généralement en compte ces valeurs en réduisant le coût de la vie. Par exemple, si la loi exige que les employeurs fournissent des soins de santé gratuits, l'estimation du salaire vital ne prendra pas en compte les dépenses de santé comme un coût d'un niveau de vie décent, réduisant ainsi l'estimation.

Cependant, si l'estimation du salaire vital ne prend pas en compte la prestation – par exemple, parce que la prestation n'est requise par la loi que dans certaines conditions – alors la prestation pourrait potentiellement être incluse dans le calcul de l'écart salarial décent.

#### 6.3 Est-il nécessaire d'accorder des avantages en nature à tous les employés pour qu'ils soient inclus dans la matrice salariale ?

Non. Des avantages en nature offerts uniquement à certains employés peuvent être inclus. Cependant, les travailleurs qui bénéficient de l'avantage en nature doivent appartenir à des catégories d'emploi distinctes de ceux qui ne bénéficient pas de l'avantage en nature.

#### 6.4  Que devons-nous faire lorsqu'une prestation en nature est accordée dans un mois précis et que le travailleur a rejoint après ou est parti avant ? Devons-nous l'inclure quand même puisque les prestations en nature doivent être ajustées à ce que le travailleur recevrait s'il avait travaillé toute l'année ?

Non. Les prestations en nature doivent être inscrites uniquement pour les travailleurs qui les ont perçues (le montant total ou une partie proportionnelle). Seuls les avantages en nature dont le travailleur ne recevait que la partie proportionnelle du temps travaillé (par exemple le repas gratuit) devaient être ajustés à temps plein.

#### 6.5 Puis-je inclure des équipements de protection individuelle ou des uniformes comme avantage en nature ?

Non. L'équipement de travail tel que les uniformes ou les équipements de protection individuelle n'est pas inclus car il ne réduit pas directement le coût de la vie pour un travailleur et sa famille.

#### 6.6 Peut-on inclure en nature un équipement de protection et un gel hydroalcoolique pour prévenir la transmission des maladies ?

Non. Bien que ces dispositions soient importantes fournies par l'établissement, elles sont des coûts variables et imprévus qui n'auraient pas été inclus dans les coûts de la vie de base utilisés pour déterminer les estimations du salaire vital.

#### 6.7  Les bons peuvent-ils être inclus en tant que bénéfices en nature ?

Les bons peuvent être inclus en tant que prestations en nature s'ils appartiennent à l'une des catégories d'avantages en nature listées dans l'outil et remplissent toutes les autres conditions pour les prestations en nature.

#### 6.8 Si les prestations en nature ne sont pas autorisées à être ajoutées au calcul de l'écart salarial décent, pourquoi devrais-je les accorder à mes travailleurs ?

La matrice salariale ne détermine pas quelles prestations fournies par les établissements ont de la valeur pour les travailleurs et l'exclusion de certains avantages en nature des calculs ne signifie pas que les travailleurs ne valorisent pas cette prestation. Les modifications des prestations en nature devraient être effectuées en étroite coordination avec les travailleurs et les représentants des travailleurs.

#### 6.9 La convention collective prévoit une sortie familiale par an. C'est une activité de loisirs qui inclut des activités et des transports. Il est très attendu et apprécié par les travailleurs. Pourquoi ne peut-il pas être inclus si c'est une activité à laquelle toute la famille participe ?

Payer pour des activités récréatives, bien que retenu et valorisé par les travailleurs, ne réduit pas le coût de la vie pour les familles et, par conséquent, selon les principes de la méthodologie® Anker, son coût ne peut pas être pris en compte dans le calcul de la rémunération comparable.

#### 6.10  Nous fournissons une assurance chômage à tous nos travailleurs, ce qui n'est pas exigé par la loi. Peut-on inclure le coût de cette assurance comme un avantage en nature ?

Non. Les coûts de l'assurance chômage ne sont pas inclus dans le calcul des estimations du salaire vital selon la méthodologie® Anker et, par conséquent, le coût de cette assurance ne peut pas non plus être inclus dans les prestations en nature.

#### 6.11 Les achats de vêtements de travail qui ne sont pas nécessairement considérés comme des uniformes sont-ils inclus comme des avantages en nature ? Par exemple, des T-shirts pour les employés de l'atelier.

Non. Si les vêtements sont pour le travail, ils ne peuvent pas être inclus. Ils ne sont pas considérés comme des vêtements pour un usage personnel et, par conséquent, ne réduisent pas le coût d'une vie décente.

#### 6.12 Les coûts de légalisation des immigrés peuvent-ils être inclus dans la matrice, puisque sans elle, le migrant ne pourrait pas travailler ?

Non. La raison pour laquelle ces types de coûts ne peuvent pas être inclus dans la matrice est que l'outil suit les principes internationaux définis par la méthodologie Anker, qui établissent que seuls les® avantages en nature ayant un impact direct sur le coût mensuel d'une vie décente pour les travailleurs et leurs familles, tels que le logement, la nourriture ou les soins de santé, doivent être envisagés.

#### 6.13 Les primes Fairtrade utilisées pour les prestations en nature peuvent-elles être ajoutées à la section des avantages en nature ?

Les primes Fairtrade ne doivent pas être incluses dans les avantages en nature, car ceux-ci dépendent du maintien de la certification et peuvent varier en fonction de la production globale d'une installation. <mark style="color:$primary;">Cependant, le montant total des primes Fairtrade reçues et les montants payés directement aux travailleurs, en espèces ou en bons, peuvent être enregistrés en tant que "Contributions au salaire vital" dans la page "Options supplémetaires". L'outil indiquera, dans le rapport final, le montant total de l'écart de salaire vital dans l'établissement qui est couvert par les paiements directs aux travailleurs.</mark>

#### 6.14 Pouvons-nous inclure le coût des installations sportives et récréatives dans la matrice salariale ? Nous entretenons actuellement ces installations à l’usage des travailleurs et de leurs familles, notamment un terrain de football, une journée sportive annuelle et d’autres espaces de loisirs. Ces installations sont mises à la disposition de tous les travailleurs et sont accessibles en permanence, faute d’autres infrastructures disponibles.

Le coût des installations et journées sportives et récréatives ne peut être inclus car il ne fait généralement pas partie des dépenses prises en compte dans le calcul de l'estimation du salaire vital et, par conséquent, ne contribue pas à réduire le coût d’une vie décente.

</details>

<details>

<summary><strong>7 AVANTAGES EN NATURE: ALIMENTATION</strong></summary>

#### 7.1  Si l'entreprise propose de la nourriture mais que tous les travailleurs n'ont pas accès à cet avantage, peut-il tout de même être considéré comme un bénéfice à salaire vital ?&#x20;

Les travailleurs doivent-ils payer pour la nourriture ? Si oui, il ne peut pas être inclus.

Si le repas est gratuit, alors l'avantage peut s'appliquer à tous les travailleurs qui y ont accès régulièrement. Si certains travailleurs y ont accès et d'autres non, ils doivent être séparés en différentes catégories professionnelles. Seuls les repas complets sont éligibles. La valeur saisie dans l'outil par travailleur doit correspondre au coût pour l'employeur, si ce coût est considéré comme acceptable pour les travailleurs et que la plupart d'entre eux profitent de l'avantage. Si le travailleur paie une partie de la nourriture, cette partie doit être déduite du coût pour l'employeur.

#### 7.2 Le coût de la nourriture fourni aux membres des comités des travailleurs ou à d'autres personnes nourries lors des réunions aux frais de l'entreprise peut-il être inclus dans les avantages en nature ?

Si cette nourriture est fournie régulièrement, par exemple une fois par mois, et est attendue et appréciée par les participants, ce coût ne peut être inclus que pour les personnes ayant participé à ces réunions. Cependant, l'établissement doit tenir des registres de la participation et des dépenses engagées et garantir une allocation appropriée uniquement aux participants de chaque session, et le coût de la tenue de ces registres peut être supérieur à l'avantage d'inclure ces montants dans les calculs.

#### 7.3  Les dons périodiques aux travailleurs de la nourriture produite à la ferme (par exemple, les bananes) peuvent-ils être inclus dans la matrice salariale ?

Le coût pour l'employeur des dons alimentaires produits à la ferme peut être inclus comme un avantage en nature à condition que :&#x20;

* Le type d'alimentation est inclus dans le régime modèle utilisé pour estimer l'estimation du salaire vital de la région,
* les dons et leur valeur monétaire sont convenus dans une convention collective et
* sont appréciés et valorisés par les travailleurs.

#### 7.4 Les contributions de l'entreprise visant à réduire les coûts alimentaires à la cafétéria (par exemple, mise à disposition d'espace, prise en charge des charges telles que l'électricité et l'eau, exonération de loyer, etc.) peuvent-elles être considérées comme un avantage en nature ? Si oui, comment ?

Si les employés paient leurs repas, ces coûts ne doivent pas être inclus.

Si les repas sont considérés comme subventionnés grâce à ces contributions de l'employeur, le montant de la subvention (soit le surcoût pour l'employé si l'entreprise ne contribuait pas) doit être porté à la connaissance des employés et accepté comme un avantage en nature.

</details>

<details>

<summary><strong>8 AVANTAGES EN NATURE:  TRANSPORT</strong></summary>

#### 8.1  L'établissement offre un transport gratuit à tous les travailleurs, mais pas tous les qui l'utilisent, comment puis-je bénéficier de cet avantage en nature ?

Pour qu'un bénéfice en nature soit considéré comme une rémunération, il doit être évalué et accepté par la plupart des travailleurs. Par conséquent, le coût de ce transport gratuit peut être inclus si la plupart des travailleurs l'utilisent et l'apprécient, bien que certains ne l'utilisent pas pour des raisons de commodité.

Deux options sont proposées pour profiter de ce bénéfice en nature :

* Divisez le coût pour l'employeur entre tous les travailleurs ayant accès au transport et attribuez-le à tous.
* Divisez le coût pour l'employeur entre tous les travailleurs qui l'utilisent et ne l'attribuez qu'à ceux qui l'utilisent.

Ce même principe s'applique à tous les avantages en nature, comme les repas.

#### 8.2 Puis-je inclure les vélos comme avantage de transport ?

Oui. La valeur des bicyclettes fournies aux travailleurs comme moyen de transport peut être incluse dans le calcul de l'écart salarial décent s'ils remplissent toutes les conditions requises pour les prestations en nature. Les moyens de transport disponibles uniquement à l'intérieur de l'établissement ne peuvent pas être inclus. Le coût initial du vélo peut être inclus pendant un an ou réparti sur plusieurs années jusqu'à ce que le coût initial soit couvert.

#### 8.3  L'installation se trouve sur une île, et nous avons assuré un transport gratuit de la terre vers l'île. Ce coût de transport peut-il être inclus ?

Non. Le transport de la terre vers l'île doit être considéré comme un moyen de transport pour le travail, sauf si un transport public adéquat est disponible.&#x20;

</details>

<details>

<summary><strong>9 AVANTAGES EN NATURE: SOINS DE SANTE</strong></summary>

#### 9.1 Le savon et d'autres produits sanitaires fournis pour les travailleurs à domicile peuvent-ils être considérés comme un avantage en nature ?

Le savon et autres produits sanitaires fournis sur le lieu de travail pendant les heures de travail ne peuvent pas être inclus. Les paquets de savon et de produits sanitaires fournis aux travailleurs pour qu'ils puissent les emporter à la maison pourraient être inclus dans le cadre de la Care, à condition que toutes les autres exigences pour les prestations en nature (y compris le fait d'être une partie acceptable du paiement salarial par les travailleurs) sont remplies. Cependant, ces forfaits représentent généralement une très petite part des coûts non alimentaires ni logements.

#### 9.2  Les frais logistiques couverts par l'entreprise pour aider le travailleur à recevoir des soins médicaux peuvent-ils être pris en compte ? Par exemple, les frais de transport vers le centre médical et les frais de nourriture pendant leur séjour.

Oui, mais seulement si les soins médicaux requis par le travailleur ne sont pas liés à la santé au travail. Par conséquent, les coûts logistiques liés au traitement des maladies professionnelles ou des accidents du travail doivent être exclus du calcul, et le coût total calculé doit être réparti entre tous les travailleurs de l'établissement.

#### 9.3  Que se passe-t-il lorsque l'employeur couvre la contribution du travailleur à la sécurité sociale ? Cela peut-il être inclus comme rémunération ou non ?

Si l'employeur verse la contribution à la sécurité sociale payable par l'employé, ce montant correspondant peut être considéré comme une prestation en nature pour les soins de santé. Notez toutefois que les cotisations à la sécurité sociale payables par l'employeur ne peuvent pas être incluses.

#### 9.4 Nous prenons en charge les frais de lunettes et subventionnons les consultations psychologiques des employés qui en font la demande. Ces avantages peuvent-ils être considérés comme un avantage en nature ?

Oui, toute assistance sanitaire qui n'est pas fournie par les services publics gratuits peut être sconsiderée un bénéfice d'attention sanitaire, si cela ne découle pas d'un accident ou d'une maladie du travail. Il faut noter que le coût total pour l'employeur pour ces prestations sera divisé entre tous les travailleurs du centre.

</details>

<details>

<summary><strong>10 AVANTAGES EN NATURE: EDUCATION DES ENFANTS</strong></summary>

#### 10.1 L'établissement offre une bourse aux employés ayant des enfants à charge pour soutenir leurs études. Le montant de cette bourse varie selon le nombre d'enfants. Comment ce montant doit-il être comptabilisé ?

Pour les avantages qui ne concernent pas tous les employés, comme les frais de scolarité et de transport, il convient d'utiliser la valeur moyenne pour l'ensemble des employés. Par conséquent, si les frais de scolarité représentent 3 $ par élève et par mois pour l'employeur, et que les deux tiers des employés ont un enfant scolarisé, le coût de cet avantage pour l'employeur est de 2 $ par employé et par mois.

#### 10.2 L'établissement prend en charge le salaire d'un enseignant dans une école publique proche de la ferme, fréquentée non seulement par les enfants des travailleurs. Comment intégrer ce coût ?

Ce coût n'est pas intégré car cette contribution au fonctionnement de l'école ne réduit pas le coût de la vie des travailleurs.

</details>

<details>

<summary><strong>11 AVANTAGES EN NATURE: SOINS DE SANTE</strong></summary>

#### 11.1 Les travailleurs étrangers n'ayant pas accès aux services de santé publics, nous prenons en charge leur assurance maladie privée. Dans ce cas, la contribution de l'employeur peut-elle être intégrée à la rémunération du travailleur ? Si oui, où ?

L'estimation du salaire minimum vital est calculée pour les travailleurs ayant accès au système de santé public et, en principe, ne s'applique pas aux travailleurs étrangers qui n'y ont pas accès. Pour ces derniers, la valeur de référence estimée serait plus élevée, car elle devrait inclure le coût des soins de santé publics ou d'une assurance maladie privée.

Inclure le coût de l'assurance maladie privée comme un avantage en nature reviendrait à dire qu'à accès égal aux soins de santé, les travailleurs étrangers disposeraient de plus de ressources pour leurs dépenses mensuelles que les travailleurs nationaux, ce qui ne correspond pas à la réalité. Proposer une assurance maladie privée permet simplement d'équilibrer la couverture santé des travailleurs migrants et celle des travailleurs locaux, et donc d'utiliser la même valeur de référence estimée pour les deux.

Si les soins de santé privés offrent des prestations supérieures à celles du système de santé public, la valeur des soins non couverts par le système public, incluse dans l'estimation du salaire minimum vital et ajustée en fonction de l'inflation, pourrait être comptabilisée comme un avantage en nature de soins de santé. Par exemple, en République dominicaine, le rapport complet d'Anker considère un coût des soins de santé de 37 USD par mois en 2022, ce qui correspondrait à 39 USD par mois en 2025, sur la base de l'inflation appliquée pour mettre à jour le salaire vital estimé entre 2022 (461 USD) et 2025 (489 USD).

#### <mark style="color:$primary;">11.2 Nous versons une contribution annuelle au compte santé de chaque employé. Les employés peuvent utiliser les fonds déposés, exonéres d'impôts, pour couvrir leurs frais médicaux. Ils peuvent aussi les utiliser pour d'autres si'ls payent les impots correpondantes à la contribution. Comment devons nous comptabiliser cette contribution ?</mark>

<mark style="color:$primary;">Puisque les employés peuvent utiliser les fonds déposés pour couvrir toute dépense, le montant doit être comptabilisé comme une prime. S'il s'agit d'un montant annuel fixe, comptabilisez-le comme une prime non liée au temps de travail. Si le montant varie en fonction du nombre de jours travaillés au cours de l'exercice, comptabilisez-le comme une prime liée au temps de travail ; l'outil la calculera alors automatiquement au prorata du temps plein (ETP).</mark>

</details>

<details>

<summary><strong>12 AVANTAGES EN NATURE: LOGEMENT</strong></summary>

#### 12.2 Pour une allocation de logement, nous donnons aux travailleurs le choix de recevoir de l'argent liquide ou de recevoir un logement. Comment doit-on saisir cela ? Les catégories d'emploi doivent-elles être réparties entre ceux qui reçoivent de l'argent liquide et ceux qui reçoivent un logement ?

Si l'argent peut être utilisé pour n'importe quelle raison choisie par le travailleur, alors des catégories séparées pour les travailleurs recevant une allocation en espèces devraient être créées et l'allocation en espèces inclue dans la section bonus.&#x20;

Pour les travailleurs ou catégories de travailleurs qui reçoivent un logement, ou un bon logement pouvant être utilisé uniquement pour le logement, le coût du logement doit être inclus dans la section des prestations en nature. Dans les deux cas, la valeur de l'avantage en nature ne doit pas dépasser la valeur donnée en espèces.

#### 12.2  Qu'est-ce qui peut être inclus dans la valeur du logement ?

Le coût du logement peut consister en des montants payés pour les réparations, l'entretien, les services publics, l'amortissement, les impôts, la garantie et les remboursements hypothécaires/prêts effectués pour construire ou acheter le logement.

Si le coût de la fourniture de logement par an n'est pas constant d'une année à l'autre, une moyenne d'au moins 3 ans devrait être utilisée.

#### 12.3 L'établissement alloue des ressources à sa fondation afin de financer l'amélioration des infrastructures sanitaires des logements des employés. Ces dons peuvent-ils être comptabilisés comme un avantage en nature pour les bénéficiaires au titre du logement familial ?

Il est déconseillé de les comptabiliser, car il ne s'agit pas d'un versement direct de l'employeur à l'employé. Pour qu'un montant soit comptabilisé comme un avantage en nature, les employés doivent en être informés au préalable et l'accepter, ce qui doit être garanti. De plus, il serait difficile pour les auditeurs de vérifier que la fondation a effectivement investi ce montant dans l'amélioration des infrastructures sanitaires, et cet investissement, soumis à amortissement, ne devrait pas être comptabilisé sur un seul exercice.

</details>

<details>

<summary><strong>13 AVANTAGES EN NATURE: CALCUL DU COÛT POUR L'EMPLOYEUR</strong></summary>

#### **13.1** Comment devons-nous évaluer le coût de l'avantage par travailleur ?

Vous transféreriez le coût d'exploitation à l'employeur et le divisiez par le nombre de travailleurs ayant accès à l'allocation. Dans le cas d'un avantage utilisé par d'autres membres de la communauté (par exemple, écoles ou établissements médicaux), divisez le coût pour l'employeur par le nombre de familles ayant accès à la prestation.&#x20;

Le coût d'un investissement récent (c'est-à-dire le coût d'achat d'un bus, le coût de construction d'un logement familial, etc.) doit être amorti et réparti dans le temps (à partir de l'année de dépense) jusqu'à ce que le coût total soit couvert.&#x20;

Le coût total de chaque prestation individuelle, par travailleur, ne doit pas dépasser la valeur de remplacement de ce travailleur. En d'autres termes, le coût du logement ne peut pas dépasser ce que coûterait à un travailleur et à sa famille de louer un logement de qualité similaire.

#### 13.2 Que devons-nous faire s'il existe plusieurs valeurs pour un bénéfice en nature donné ?

La Matrice Salariale vous permet d'entrer différents montants dans différentes catégories d'emplois. Lorsque des travailleurs d'une même catégorie professionnelle reçoivent des valeurs différentes pour le même avantage en nature, veuillez utiliser la valeur la plus basse qui répond à tous les critères d'acceptation des prestations en nature, et non la moyenne.

#### 13.3  Y a-t-il une limite quant au montant des prestations en nature auxquelles je peux accéder ?

Oui, les prestations en nature sont des prestations non monétaires telles que la nourriture, le transport ou le logement fournies par l'employeur, qui réduisent le montant de revenus en espèces dont les travailleurs ont besoin pour un niveau de vie décent.

Basée sur les principes des prestations en nature énoncés dans la méthodologie® Anker, la matrice salariale limite la contribution des prestations en nature afin de garantir le droit du travailleur à l'autodétermination. La valeur totale combinée des prestations en nature est plafonnée à 30 % de la rémunération totale. Le logement est plafonné à 15 % de la rémunération totale. Tous les autres avantages sont plafonnés à 10 % de la rémunération totale.

Vous n'avez pas besoin de faire ces calculs à l'avance. Il suffit d'entrer la valeur annuelle réelle des prestations en nature par employé et l'outil les plafonnera automatiquement.

</details>

<details>

<summary><strong>14 OPTIONS SUPPLEMENTAIRES</strong></summary>

#### 14.1 Que se passe-t-il si notre certification n'est pas listée dans la section des normes de certification ?

Seules les certifications en durabilité sont incluses dans la liste. Si votre certification en durabilité n'est pas listée, veuillez contacter le service d'assistance à [livingwagematrix@idhtrade.org](mailto:livingwagematrix@idhtrade.org).&#x20;

#### 14.2. Comment devons-nous refléter les primes de certification et les contributions volontaires des parties prenantes de la chaîne d'approvisionnement dans la matrice salariale ?

Seuls les avantages en espèces ou en nature versés par l'employeur et inclus dans les chèques de paie des employés peuvent être saisis dans l'onglet paie. Tout fonds supplémentaire ou bénéfice en nature reçu par des travailleurs hors de leur paie, qu'il s'agisse de contributions volontaires à la chaîne d'approvisionnement ou de primes de certification, ne sera pas considéré comme une rémunération dans le calcul des écarts de salaire vital. Vous pouvez saisir ces contributions dans la section Add-ons/Contributions pour information uniquement.

#### 14.3 Nous avons un client intéressé à contribuer pour réduire l'écart de salaire vital en 2024 ; Ce paiement sera effectué en 2026. Comment gérer ce bénéfice ? Est-il possible de rouvrir les matrices de 2024 pour enregistrer la contribution volontaire qui sera mise en œuvre en 2026 ?

En tenant compte du fait que les contributions à l'écart salarial décent ne sont pas incluses dans le calcul de la rémunération puisqu'elles ne sont pas garanties et que la matrice salariale n'indique que le pourcentage de l'écart total de l'établissement que cette contribution couvrirait, l'IDH recommande de les enregistrer dans l'année de leur réception, c'est-à-dire lorsque le travailleur peut les utiliser pour subvenir à un coût de vie décente. Ainsi, l'outil montrera l'écart salarial décent pour 2026 et comment il sera réduit grâce à l'impact des contributions reçues cette année-là, que ces contributions proviennent ou non de livraisons passées de produits.

</details>

<details>

<summary><strong>15 RAPORT</strong></summary>

#### 15.1  Que signifie un écart en pourcentage (par exemple, 20 %) en termes pratiques, et comment devrait-il l'expliquer ?

Cela signifie que le travailleur (ou les travailleurs de la catégorie professionnelle) auraient reçu un salaire mensuel inférieur de 20 % au salaire nécessaire pour assurer un niveau de vie décent dans la région, s'il avait travaillé à temps plein toute l'année dans les mêmes conditions de travail.

#### 15.2 Je fabrique plusieurs produits dans mon usine avec la même main-d'œuvre. Puis-je mesurer l'écart par unité commerciale pour un produit spécifique ?

La Matrice Salariale est conçue pour calculer l'écart salarial pour un travailleur ou une catégorie de poste, indépendamment des tâches qu'il effectue. Ainsi, si l'installation produit différents produits avec la même main-d'œuvre, il n'est pas possible de calculer indépendamment l'écart par unité commerciale pour chaque produit.

#### 15.3 Je dois apporter des corrections aux données saisies, mais je les ai déjà soumises. Comment puis-je rouvrir le calcul ?

Pour rouvrir un Calcul soumis, accédez à l’onglet 6, « _Rapports_ », puis cliquez sur les trois points en haut à droite pour accéder à la fonction « _Rouvrir pour modifier_ ».

Vous pouvez également rouvrir pour modification à partir de la liste des Calculs en cliquant sur les trois points situés à la fin des calculs déjà soumis.

</details>
