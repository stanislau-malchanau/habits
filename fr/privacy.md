---
title: Politique de confidentialité de Habit Tracker
lang: fr
---

# Politique de confidentialité de Habit Tracker: Game & Friends

*Ceci est une traduction. En cas de divergence avec la [version anglaise](../privacy), la version anglaise prévaut.*

Date d'entrée en vigueur : 2026-10-23

La présente politique explique comment Habit Tracker: Game & Friends (affichée « Habitudes » sur votre écran d'accueil, l'« App »), créée par Stanislau Malchanau (« nous »), traite vos informations. En bref : **nous ne collectons, ne vendons ni ne partageons vos données personnelles. Vos habitudes restent sur votre appareil et dans votre propre compte iCloud.**

## 1. Données stockées par l'App

L'App stocke les éléments suivants sur votre appareil : vos habitudes (nom, icône, couleur, type, calendrier, objectif et heures de rappel), vos validations de chaque jour, les pauses et les jours de repos, votre village (le terrain sur lequel se trouve la maison de chaque habitude et son degré de croissance) et vos réglages. Votre Apple Watch conserve une copie des mêmes données pour afficher et valider vos habitudes.

Nous n'exploitons aucun serveur qui reçoit ces données, et nous n'y avons pas accès. Les exceptions sont le calendrier d'une activité en direct en cours (section 5) et les signaux d'utilisation anonymes (section 8).

## 2. Synchronisation iCloud

Si vous êtes connecté à iCloud, l'App synchronise vos données via CloudKit d'Apple, dans la base de données privée de votre propre compte iCloud, afin que votre iPhone, votre iPad et votre Apple Watch affichent les mêmes habitudes. Ces données sont stockées et protégées par Apple conformément à l'Engagement de confidentialité d'Apple (https://www.apple.com/legal/privacy/). Nous ne pouvons ni les voir, ni les lire, ni les exporter. Vous pouvez désactiver la synchronisation dans iOS, sous Réglages > [votre nom] > iCloud.

## 3. Habitudes partagées avec des amis

Vous pouvez inviter des amis à une habitude partagée. Une habitude partagée est conservée dans une zone partagée de votre compte iCloud grâce au partage CloudKit d'Apple. Les personnes que vous invitez, et elles seules, voient le nom, l'icône, le calendrier et les validations de cette habitude, ainsi que le nom de chaque participant dans iCloud. Vos autres habitudes ne sont jamais partagées. Un participant peut quitter une habitude partagée à tout moment, et son propriétaire peut retirer un participant ou arrêter le partage ; leurs copies cessent alors d'être mises à jour. Nous ne pouvons voir ni les habitudes partagées ni les personnes qui y participent.

## 4. Mouvements des écouteurs et son spatial

Avec des AirPods ou d'autres écouteurs compatibles, l'App peut utiliser les mouvements de votre tête pour maintenir les sons du village à leur place lorsque vous vous tournez. Ces données de mouvement sont traitées sur votre appareil en temps réel, ne sont jamais stockées et ne quittent jamais votre appareil.

## 5. Notifications, activité en direct et widgets

Les rappels, le résumé du matin et le rappel qui précède la fin d'un essai gratuit sont créés sur votre appareil. Les widgets et les complications de l'Apple Watch lisent vos habitudes sur votre appareil.

L'App peut afficher une activité en direct pour votre routine du matin sur l'écran verrouillé et dans la Dynamic Island. Pour qu'elle puisse démarrer à l'heure de la routine et continuer d'avancer pendant que l'App est en veille, l'App envoie à notre petit serveur relais les jetons de notification push qu'Apple lui fournit pour les activités en direct (l'un pour démarrer l'activité en direct de la routine, l'autre pour l'activité en direct en cours) ainsi que le calendrier : les heures, des identifiants aléatoires des habitudes qui la composent et leurs chiffres (combien sont faites, un compteur et son objectif). Aucun nom d'habitude, aucun texte que vous avez saisi, aucun nom, aucune adresse e-mail ni aucun identifiant de compte ou d'appareil n'est envoyé. À chaque moment du calendrier, le serveur demande au service de notifications push d'Apple de démarrer ou de mettre à jour l'activité en direct, et il supprime ce qu'il conserve dès que la notification prévue est envoyée ou que l'activité en direct se termine. Le serveur fonctionne sur Cloudflare Workers ; comme tout service Internet, Cloudflare voit l'adresse IP de la requête pendant son acheminement, et nous ne la conservons pas. Si vous désactivez les activités en direct pour l'App dans iOS, sous Réglages, rien n'est envoyé.

## 6. Game Center

Si vous êtes connecté à Game Center, vos succès sont transmis à Game Center d'Apple et traités conformément à l'Engagement de confidentialité d'Apple. Nous ne recevons pas votre identité Game Center.

## 7. Achats

Les abonnements sont vendus et traités par Apple via l'App Store. Nous ne recevons pas vos informations de paiement. Apple indique uniquement à l'App si votre abonnement est actif.

## 8. Analyse d'utilisation et rapports de plantage

Pour savoir quelles fonctionnalités sont utiles et où l'App vous gêne, l'App envoie des signaux d'utilisation anonymes à TelemetryDeck, un service d'analyse de TelemetryDeck GmbH (Augsbourg, Allemagne) dont les serveurs sont situés dans l'UE. Un signal désigne une action dans l'App : par exemple, qu'une étape du premier lancement a été terminée, que l'écran d'abonnement a été affiché ou qu'un abonnement a commencé, que l'App a demandé une évaluation, ou que la synchronisation iCloud a échoué. Il est accompagné d'un horodatage arrondi à l'heure et d'informations techniques générales : les versions de l'App et d'iOS, le modèle de l'appareil, la langue, la région et le fuseau horaire, ainsi que les réglages d'affichage et d'accessibilité, comme le mode sombre ou la taille du texte.

Un signal ne contient jamais le nom de vos habitudes ni tout autre texte que vous saisissez, ni votre nom, votre adresse e-mail, votre Compte Apple, vos amis ou votre position. Votre installation n'est identifiée que par un identifiant aléatoire que l'App sale puis hache avant l'envoi, de sorte que les signaux ne permettent pas de remonter jusqu'à vous et ne peuvent pas être suivis d'une app à l'autre. TelemetryDeck ne stocke aucune adresse IP et n'utilise aucun cookie. Nous n'examinons ces signaux que sous forme de statistiques, pour améliorer l'App ; nous ne les vendons pas, ne les partageons pas avec des annonceurs et ne les utilisons pas pour vous suivre. L'App ne contient aucun code de publicité ou de suivi, et elle ne vous suit pas à travers d'autres apps ou sites web.

Par ailleurs, si vous choisissez de partager des données d'analyse avec les développeurs d'apps dans iOS, sous Réglages > Confidentialité et sécurité > Analyse et améliorations, Apple peut nous fournir des statistiques d'utilisation agrégées et anonymes ainsi que des rapports de plantage. Ces données ne permettent pas de vous identifier.

## 9. Ce que l'App n'utilise pas

L'App ne demande pas l'accès à votre position, à vos contacts, à vos photos, à l'appareil photo, au micro ni à vos données de santé. Le jour et la nuit du village suivent l'horloge et le fuseau horaire de votre téléphone.

## 10. Enfants

L'App convient à tous les âges et ne collecte sciemment aucune information personnelle auprès de quiconque, y compris auprès des enfants de moins de 13 ans (ou de l'âge équivalent dans votre pays).

## 11. Conservation et suppression des données

Les données sont conservées aussi longtemps que vous les gardez. Vous pouvez supprimer à tout moment une habitude et ses validations dans l'App, et tout supprimer en supprimant l'App et, pour les données synchronisées, dans iOS, sous Réglages > [votre nom] > iCloud > Gérer le stockage du compte > Habitudes. Comme nous n'en détenons aucune copie, nous n'avons rien d'autre à supprimer. Le serveur relais ne conserve les jetons et le calendrier d'une activité en direct que jusqu'à l'envoi de la notification prévue ou la fin de cette activité en direct. Les signaux d'utilisation sont anonymes et ne peuvent pas être rattachés à vous ; il n'existe donc aucun enregistrement personnel les concernant à consulter ou à supprimer.

## 12. Vos droits

Selon votre lieu de résidence (par exemple en vertu du GDPR dans l'UE, du UK GDPR, du CCPA/CPRA en Californie, de l'APPI au Japon, du PIPA en Corée ou de la LGPD au Brésil), vous pouvez avoir le droit d'accéder à vos données personnelles, de les rectifier, de les effacer ou d'en obtenir la portabilité, ainsi que de vous opposer à leur traitement ou d'en demander la limitation. Comme nous ne détenons pas vos données, vous pouvez exercer ces droits directement sur votre appareil et dans iCloud, comme décrit ci-dessus. Vous pouvez également nous contacter pour toute demande ou question, et vous pouvez introduire une réclamation auprès de votre autorité locale de protection des données.

Nous ne vendons ni ne partageons d'informations personnelles au sens du CCPA/CPRA.

## 13. Modifications

Si la présente politique change, nous mettrons à jour la date d'entrée en vigueur ci-dessus et, en cas de modification substantielle, nous vous en informerons dans l'App.

## 14. Contact

Stanislau Malchanau, Bélarus
E-mail : 7tam.official@gmail.com
