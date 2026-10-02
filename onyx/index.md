---
layout: default
title: "Politique de confidentialité — Onyx"
---

# Politique de confidentialité — Onyx

_Dernière mise à jour : 2 octobre 2026 · Éditeur : Loffay_

## En une phrase

**Onyx garde tout sur ton téléphone.** L'application ne crée aucun compte,
n'envoie aucune donnée à Loffay ni à un tiers, et ton tracé GPS ne quitte
jamais l'appareil.

## Données enregistrées, toutes locales

Tout est écrit dans le stockage privé de l'application et ne sort pas du
téléphone.

- **Profil** : prénom, date de naissance, sexe, taille, niveau d'expérience,
  langue de lecture. Servent à estimer les dépenses et à calibrer les
  programmes. Tous facultatifs — l'app fonctionne sans.
- **Mensurations**, si tu les saisis : poids, tour de taille, tour de bras,
  pourcentage de masse grasse, à la date que tu choisis.
- **Séances de musculation** : exercices, séries, charges, répétitions,
  temps de repos, ressenti, notes.
- **Sorties de course** : distance, durée, allure, dénivelé, découpe par
  kilomètre, et **le tracé GPS** quand la sortie a lieu dehors.
- **Journal d'activité** commun aux sports : ce que tu as fait, quand,
  combien de temps, l'effort ressenti.
- **Partenaires d'entraînement**, si tu en ajoutes : le prénom que tu tapes,
  une couleur, et les séances qu'ils ont faites avec toi sur ce téléphone.
  Ce sont des données sur d'autres personnes : rien ne leur est demandé ni
  envoyé, et tu peux les retirer quand tu veux.

## La localisation

C'est la donnée la plus sensible de l'app, alors soyons précis.

- Elle n'est lue que **pendant une sortie que tu as démarrée**, et l'app le
  montre en continu : un écran de séance, une notification qui reste, et un
  point sur ta barre d'état posé par Android lui-même.
- **Onyx ne demande pas la localisation en arrière-plan**
  (`ACCESS_BACKGROUND_LOCATION` n'est pas déclarée). L'app ne peut donc pas
  te suivre quand tu ne cours pas, ni te suivre sans le dire.
- Le tracé est enregistré **avec la sortie, sur le téléphone**. Il n'est
  envoyé nulle part. Il part si tu partages une séance en image — et c'est
  toi qui choisis l'application de destination, à ce moment-là.
- Couper la permission n'empêche pas d'utiliser Onyx : la musculation, la
  piste et le tapis n'en ont pas besoin.

## La connexion internet

Onyx déclare la permission `INTERNET`, et il faut dire pourquoi.

Elle sert à une seule chose : rattraper une mise à jour du **contenu** de
l'app — la liste des exercices, des muscles, du matériel. C'est du contenu
qui descend, jamais des données qui remontent.

**Dans la version publiée, aucune adresse de serveur n'est configurée :
l'application se contente du contenu qu'elle embarque et ne contacte rien.**
Le jour où un compte sera proposé, il sera explicite, facultatif, et cette
page changera avant.

## Permissions et pourquoi

| Permission | Usage |
|---|---|
| Localisation précise et approximative | Mesurer une sortie dehors : distance, allure, tracé. Pendant la sortie uniquement. |
| Service de premier plan (localisation) | Continuer à mesurer quand l'écran est éteint et le téléphone dans la poche. |
| Service de premier plan (santé) | Le type que demande Android pour un suivi d'activité. |
| Capteurs à haute fréquence | Prérequis technique du précédent. |
| Notifications | Afficher la séance en cours et prévenir de la fin d'un repos. |
| Notifications remontées | Afficher cette même séance dans la pilule de la barre d'état. |
| Réveil du processeur | Faire tomber la vibration de fin de repos à la bonne seconde, écran éteint. |
| Vibreur | Signaler une fin de repos, un kilomètre. |
| Internet | Rattraper une mise à jour du contenu. Cf. ci-dessus. |

## Pas de…

- Aucun compte, aucune inscription.
- Aucune publicité, aucun traceur, aucune mesure d'audience.
- Aucun partage ni vente de données, à personne.
- Aucune sauvegarde automatique vers le cloud (`allowBackup` est désactivé
  exprès, pour que rien ne parte chez Google sans que tu le demandes).

## Conservation et suppression

- Les données restent jusqu'à ce que **tu** les effaces, ou que tu
  désinstalles l'application. Désinstaller efface tout.
- L'app sait exporter une sauvegarde dans un fichier, que tu ranges où tu
  veux. Ce fichier t'appartient : Loffay n'y a pas accès.
- Comme rien n'est envoyé, il n'y a rien à nous demander d'effacer.

## Enfants

Onyx n'est pas destinée aux enfants de moins de 13 ans et ne leur demande
rien de particulier.

## Contact

Une question, une demande : parfait.ianis@gmail.com
