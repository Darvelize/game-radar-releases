# 🎯 GameRadar

Des recommandations de jeux **d'après ce que tu as vraiment joué** : tes succès, tes platines, ton temps de jeu sur **Xbox** et **Steam**. GameRadar te propose des jeux de **ton palier Game Pass** ou de la **boutique Steam** qui devraient te plaire.

## ⬇️ Télécharger

👉 [**Dernière version**](../../releases/latest) → télécharge `GameRadar.exe`.

- Windows 10 ou 11, 64 bits.
- Rien à installer : un seul fichier, à lancer directement.

## 🛡️ Premier lancement : l'écran bleu de Windows

L'application n'est pas signée (un certificat coûte 150 à 300 $ par an, et ne supprimerait même pas cet avertissement tout de suite). Au premier lancement, Windows affiche donc **« Windows a protégé votre ordinateur »** :

1. clique sur **Informations complémentaires** ;
2. puis sur **Exécuter quand même**.

Ça ne se fait qu'une fois. Le premier démarrage est un peu plus lent : l'appli prépare ses fichiers.

## 🔌 Se connecter

- **Xbox** : bouton « Se connecter avec Microsoft ». La page de connexion s'ouvre dans ton navigateur : GameRadar ne voit jamais ton mot de passe.
- **Steam** (si tu y joues) : dans les Réglages, colle l'adresse de ton profil et ta clé API personnelle.
  - Ton profil doit montrer ses jeux : Steam › Modifier le profil › Confidentialité › « Détails des jeux » : **Public**.
  - La clé s'obtient sur [steamcommunity.com/dev/apikey](https://steamcommunity.com/dev/apikey) (nom de domaine : `localhost`). Garde-la pour toi.
- **Game Pass** : dans les Réglages, choisis ton palier (Essential, Premium, Ultimate ou PC Game Pass).

## 🧠 Comment il choisit

- **Ta progression compte, pas le lancement** : un jeu fini, platiné ou poncé des dizaines d'heures pèse lourd ; un jeu lancé 10 minutes ne compte pas.
- **Il compare le style des jeux**, grâce aux tags des joueurs Steam (« looter-shooter », « souls-like »…). Aimer *Warframe* mène vers *Borderlands* ou *The Division 2*, pas vers *Call of Duty*.
- **Des sections « Parce que tu as aimé X »**, et en tête **les jeux qui quittent bientôt ton Game Pass**.
- Dans l'**Historique**, tu peux cocher « Histoire finie » ou retirer un jeu de tes goûts (un platine fait juste pour le gamerscore, par exemple).

## 🔒 Tes données

Tout reste **sur ton PC** : sessions chiffrées par Windows, caches et réglages dans `%APPDATA%\GameRadar` et `%LOCALAPPDATA%\GameRadar`. GameRadar n'a aucun serveur et ne partage rien. Pour tout effacer, supprime ces deux dossiers.

## ⚠️ À savoir

- Windows uniquement.
- GameRadar utilise des services non officiels (historique Xbox Live, catalogue Game Pass) qui peuvent changer sans prévenir.
- Usage personnel uniquement. GameRadar n'est affilié ni à Microsoft ni à Valve ; Xbox et Steam sont leurs marques.

Un souci, une idée ? Ouvre une [issue](../../issues).
