# Politique de confidentialité — Eora

_Dernière mise à jour : 30 juin 2026 · Éditeur : Loffay_

## En une phrase

**Eora fonctionne 100 % sur ton téléphone.** L'application n'a aucune
connexion internet, ne crée aucun compte, et n'envoie **aucune** donnée à
Loffay ni à un tiers. Tes données de sommeil ne quittent jamais l'appareil.

## Données traitées (toutes locales)

Tout est stocké localement (Android DataStore) et ne sort jamais du
téléphone :

- **Réglages** : heure maximale de réveil, heure de coucher, jours
  d'alarme, sons choisis, volume/vibration, thème, options de pré-réveil.
- **Historique de réveil** : pour chaque nuit, l'heure d'endormissement
  estimée, l'heure de déclenchement, ton ressenti (note 1–5) et le cycle
  utilisé. Sert à personnaliser le réveil et à afficher tes statistiques.
- **Transitions de phases de sommeil** détectées (éveillé / endormi /
  micro-réveil…), pour la transparence et les stats.

## Capteurs lus (à la volée, pour détecter le sommeil)

Échantillonnés périodiquement pendant la nuit pour estimer si tu dors,
puis **non conservés** en tant que tels :

- Accéléromètre (mouvement), capteur de lumière, état de charge, état de
  l'écran (allumé/éteint).
- **Statistiques d'usage** (permission « accès aux données d'usage ») :
  uniquement l'horodatage de ta dernière interaction avec le téléphone,
  pour deviner ton sommeil léger. Aucune liste d'applications n'est
  stockée ni transmise.

## Permissions et pourquoi

| Permission | Usage |
|---|---|
| Alarmes exactes | Déclencher le réveil à l'heure pile, même en veille (Doze). |
| Démarrage au boot | Reprogrammer ton alarme après un redémarrage. |
| Notification plein écran | Afficher l'écran de réveil par-dessus l'écran verrouillé. |
| Service au premier plan (lecture) | Sonner l'alarme et lire les sons Détente en arrière-plan. |
| Notifications | Afficher l'alarme, le pré-réveil, la lecture audio. |
| Vibreur | Vibration du réveil. |
| Accès aux données d'usage | Détecter ton inactivité pour estimer l'endormissement. |
| Ignorer l'optimisation batterie | Éviter que le système ne retarde l'alarme. |
| Accès à la politique de notifications | Sonner malgré le mode « Ne pas déranger ». |

## Pas de…

- ❌ Aucune connexion internet (l'app n'a pas la permission `INTERNET`).
- ❌ Aucun compte, aucune inscription.
- ❌ Aucune publicité, aucun traceur, aucune analytics.
- ❌ Aucun partage ni vente de données.

## Conservation et suppression

- Les données restent jusqu'à ce que **tu** les effaces (réinitialisation
  dans l'app) ou que tu **désinstalles** l'application.
- La **sauvegarde cloud est désactivée** (`allowBackup=false`) : par choix
  de confidentialité, rien n'est copié vers ton compte Google. Conséquence
  assumée : en changeant de téléphone, l'historique ne suit pas.

## Contact

Pour toute question : parfait.ianis@gmail.com
