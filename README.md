# QUARTZ — distribution

Ce dépôt ne porte pas de code : il porte les **versions publiées** de QUARTZ et
le manifeste signé qui les décrit.

- **Télécharger la dernière version :**
  [Releases](https://github.com/Shadxxxw/Quartz-releases/releases/latest)
- Décompressez, puis lancez `quartz.exe`.

## Les mises à jour

Le programme se met à jour seul. Chaque version est décrite par un manifeste
signé (Ed25519) ; le programme refuse toute archive dont la signature, la
taille ou l'empreinte ne correspond pas — et refuse également de revenir à une
version antérieure.

La vérification ne repose pas sur TLS seul. TLS fait confiance à cent cinquante
autorités de certification et à l'hébergeur ; la signature ne fait confiance
qu'à une seule clé. Les deux, jamais l'un ou l'autre.

## Avertissement

QUARTZ tient un portefeuille **de papier**. Aucune clé d'échange n'est
demandée, aucun ordre n'est envoyé. Les rendements affichés sont des mesures,
pas des promesses : le verdict livré avec le programme porte ses réserves, et
il faut les lire.
