---
nav_title: Décembre
page_order: 1
noindex: true
page_type: update
description: "Cet article contient les notes de version de décembre 2021."
---
# Décembre 2021

## Métrique de rapport « Taux de Click-to-Open »
Braze a ajouté une nouvelle métrique d’e-mail « Taux de Click-to-Open » disponible dans le [Créateur de rapports]({{site.baseurl}}/user_guide/data_and_analytics/reporting/report_builder/). Cette mesure représente le pourcentage d’e-mails ouverts qui ont été cliqués.

## Métrique de rapport « Ouverture machine »

Une nouvelle métrique, [Machine Opens]({{site.baseurl}}/user_guide/message_building_by_channel/email/reporting_and_analytics/analytics_glossary/#machine-opens) (Ouverture machine), est disponible sur les pages Canvas et Campaign Analytics (Analyse de campagne) pour les e-mails. Cette mesure identifie les ouvertures d’e-mails qui sont non humaines (c.-à-d. ouverts par les serveurs d’Apple), affichées en tant que sous-ensemble des ouvertures totales.

## aléatoire_compartiment_nombre variable Liquid
Une variable `random_bucket_number` a été ajoutée à la liste des [variables Liquid prises en charge]({{site.baseurl}}/user_guide/personalization_and_dynamic_content/liquid/supported_personalization_tags/#supported-personalization-tags) pour la personnalisation des messages. 

## Recommandations pour les notifications push riches sur iOS 15
Des nouvelles [Recommandations pour les notifications push sur iOS]({{site.baseurl}}/user_guide/message_building_by_channel/push/ios/rich_notifications/) ont été ajoutées aux documents riches iOS, y compris des informations sur les états de notification et une description détaillée des variables de troncature de texte.

## Adresses IP supplémentaires à whitelister pour l’UE pour les webhooks et le Contenu connecté
Des adresses IP supplémentaires à whitelister pour l’UE pour les webhooks et le contenu connecté ont été ajoutées à notre article sur les [webhooks]({{site.baseurl}}/user_guide/message_building_by_channel/webhooks/creating_a_webhook/) et le[Contenu connecté]({{site.baseurl}}/user_guide/personalization_and_dynamic_content/connected_content/making_an_api_call/). Ces nouvelles adresses IP incluent `18.157.135.97`, `3.123.166.46`, `3.64.27.36`, `3.65.88.25`, `3.68.144.188` et `3.70.107.88`.

## Endpoint d’exportation des achats
Un nouvel endpoint [GET : `/purchases/product_list`]({{site.baseurl}}/api/endpoints/export/purchases/get_list_product_id/) a été ajouté à Braze. Ce enpoint renvoie des listes pagées d’ID Produit.

## Nouveaux partenariats Braze

### Adobe - Plateforme de données client
L’intégration entre Braze et [Adobe]({{site.baseurl}}/partners/data_and_infrastructure_agility/customer_data_platform/adobe/#adobe) permet aux marques de connecter et de mapper leurs données Adobe (segments et attributs personnalisés) vers Braze en temps réel. Les marques peuvent ensuite se servir de ces données pour offrir des expériences personnalisées et ciblées à ces utilisateurs. 

### BlueConic - Plateforme de données client
Avec [Blueconic]({{site.baseurl}}/partners/data_and_infrastructure_agility/customer_data_platform/blueconic/#blueconic), les utilisateurs de Braze peuvent unifier les données en profils individuels persistants, puis les synchroniser sur les points de contact et systèmes des clients pour soutenir une large gamme d’initiatives axées sur la croissance, notamment l’orchestration du cycle de vie des clients, la modélisation et l’analyse, les produits numériques et les expériences, la monétisation basée sur le public, etc.

### Worthy - Contenu dynamique
L’intégration entre [Worthy]({{site.baseurl}}/partners/message_personalization/dynamic_content/worthy/#worthy) et Braze vous permet de créer facilement des expériences in-app riches et personnalisées avec l’éditeur de contenu dynamique de Worthy, et de les diffuser ensuite via Braze.

### Judo - Contenu dynamique
L’intégration entre [Judo]({{site.baseurl}}/partners/message_personalization/dynamic_content/judo/#judo) et Braze vous permet d’écraser les composantes de votre campagne et de les remplacer par des expériences Judo. Les données Braze peuvent également fournir du contenu personnalisé dans une expérience Judo. Les événements et les données des utilisateurs de l’expérience peuvent faire l’objet d’un retour dans Braze pour l’attribution et le ciblage.

### Line - Messagerie
L’intégration entre Braze et [Line]({{site.baseurl}}/partners/message_orchestration/additional_channels/messaging/line/#line) vous permet d’exploiter les webhooks, la segmentation avancée, la personnalisation et les fonctions de déclenchement de Braze pour envoyer des messages à vos utilisateurs dans Line via l’[API de messagerie de Line](https://developers.line.biz/en/docs/messaging-api/overview/).

### RevenueCat - Paiements
L’intégration entre [RevenueCat]({{site.baseurl}}/partners/data_and_infrastructure_agility/payments/revenuecat/#revenuecat) et Braze permet de synchroniser automatiquement les événements d’achat et d’abonnement de vos clients sur plusieurs plateformes. Cela vous permet de créer des campagnes qui réagissent en fonction de l’étape du cycle de vie d’abonnement de vos clients, par exemple pour communiquer avec des clients qui se sont désinscrits pendant leur essai gratuit ou envoyer des rappels aux clients en défaut de paiement.

### Punchh - Fidélisation
[Punchh]({{site.baseurl}}/partners/message_orchestration/channel_extensions/loyalty/punchh/#punchh) s’est associé à Braze pour synchroniser les données entre les deux plateformes à des fins de cadeaux et de fidélisation. Les données utilisateur publiées dans Braze seront disponibles pour la segmentation et peuvent être synchronisées dans Punchh via des modèles de webhooks configurés dans Braze.   