# 🎯 GameRadar

**🇫🇷 Français** · [🇬🇧 English below](#english)

Des recommandations de jeux **d'après ce que tu as vraiment joué** : tes succès, tes platines, ton temps de jeu sur **Xbox**, **Steam** et **PlayStation**. GameRadar te propose des jeux de **ton palier Game Pass** ou du **catalogue Steam** qui devraient te plaire. En français et en anglais.

## ⬇️ Télécharger

👉 [**Dernière version**](../../releases/latest) → télécharge `GameRadar.exe`.

- Windows 10 ou 11, 64 bits.
- Rien à installer : un seul fichier, à lancer directement.
- GameRadar t'avertit tout seul quand une nouvelle version sort.

## 🛡️ Premier lancement : l'écran bleu de Windows

L'application n'est pas signée (un certificat coûte 150 à 300 $ par an, et ne supprimerait même pas cet avertissement tout de suite). Au premier lancement, Windows affiche donc **« Windows a protégé votre ordinateur »** :

1. clique sur **Informations complémentaires** ;
2. puis sur **Exécuter quand même**.

Ça ne se fait qu'une fois. Le premier démarrage est un peu plus lent : l'appli prépare ses fichiers.

## 🔌 Se connecter (Réglages › Comptes)

- **Xbox** : bouton « Se connecter avec Microsoft ». La page de connexion s'ouvre dans ton navigateur : GameRadar ne voit jamais ton mot de passe. Microsoft y indique « éditeur non vérifié » : c'est normal pour un projet perso (la vérification est réservée aux entreprises), et GameRadar ne se sert de cet accès que pour lire ton historique de jeux. Juste en dessous, choisis ton palier **Game Pass** (Essential, Premium, Ultimate ou PC Game Pass).
- **Steam** (si tu y joues) : colle l'adresse de ton profil et ta clé API personnelle.
  - Ton profil doit montrer ses jeux : Steam › Modifier le profil › Confidentialité › « Détails des jeux » : **Public**.
  - La clé s'obtient sur [steamcommunity.com/dev/apikey](https://steamcommunity.com/dev/apikey) (nom de domaine : `localhost`). Garde-la pour toi.
- **PlayStation** (si tu y joues) : connecte-toi sur playstation.com, ouvre la page de ton jeton depuis l'appli et colle ce qu'elle affiche. Ce jeton ouvre ta session Sony : garde-le pour toi. GameRadar le garde chiffré sur ton PC.
- Pas de compte, ou un jeu joué ailleurs (Switch…) ? Ajoute-le à la main : **Historique › « Ajouter un jeu »**.

## 🧠 Comment il choisit

- **Ta progression compte, pas le lancement** : un jeu fini, platiné ou poncé des dizaines d'heures pèse lourd ; un jeu lancé 10 minutes ne compte pas.
- **Il compare le style des jeux**, grâce aux tags des joueurs Steam (« looter-shooter », « souls-like »…). Aimer *Warframe* mène vers *Borderlands* ou *The Division 2*, pas vers *Call of Duty*.
- **Des sections « Parce que tu as aimé X »**, et en tête **les jeux qui quittent bientôt ton Game Pass**. Clique sur une carte pour ouvrir la page du jeu.
- Dans l'**Historique**, tu peux cocher « Histoire finie » ou retirer un jeu de tes goûts (un platine fait juste pour le gamerscore, par exemple).

## 🔒 Tes données

Tout reste **sur ton PC**, dans `%LOCALAPPDATA%\GameRadar` : sessions chiffrées par Windows, caches, réglages. GameRadar n'a aucun serveur et ne partage rien. **Réglages › Confidentialité** explique le détail, donne les liens pour retirer son accès à tes comptes Microsoft, Steam et PlayStation, et un bouton pour tout effacer.

## 🐞 Un souci ?

**Réglages › À propos › « Journal des erreurs »** ouvre le dossier du journal (sans aucun secret : ni mot de passe, ni jeton, ni clé). Envoie le fichier du jour avec ta description, ou ouvre une [issue](../../issues).

## 📜 Conditions et licences

- En utilisant GameRadar, tu acceptes ses [**conditions d'utilisation**](LICENSE.txt) : gratuit pour un usage personnel, partage libre du fichier non modifié, **fourni tel quel, sans garantie**.
- GameRadar contient des composants open source (Avalonia, .NET, SkiaSharp…) : leurs licences sont dans [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
- Les deux textes sont aussi dans l'appli : **Réglages › À propos**.

## ⚠️ À savoir

- Windows uniquement.
- GameRadar utilise des services non documentés (historique Xbox Live, PlayStation Network, catalogue Game Pass) qui peuvent changer sans prévenir.
- GameRadar est un projet indépendant, non affilié à Microsoft Corporation, Valve Corporation ni Sony Interactive Entertainment, et approuvé par aucune d'elles. Xbox et Game Pass sont des marques de Microsoft Corporation ; Steam est une marque de Valve Corporation ; PlayStation est une marque de Sony Interactive Entertainment. Les jaquettes et noms des jeux appartiennent à leurs éditeurs.

---

<a id="english"></a>
## 🇬🇧 English

Game recommendations **based on what you really played**: your achievements, your 100% completions, your playtime on **Xbox**, **Steam** and **PlayStation**. GameRadar suggests games from **your Game Pass plan** or the **Steam catalog** that you should enjoy. In English and French.

### ⬇️ Download

👉 [**Latest version**](../../releases/latest) → download `GameRadar.exe`.

- Windows 10 or 11, 64-bit.
- Nothing to install: a single file, run it directly.
- GameRadar tells you by itself when a new version comes out.

### 🛡️ First launch: the blue Windows screen

The app is not signed (a certificate costs $150 to $300 a year, and would not even remove this warning right away). On first launch, Windows shows **"Windows protected your PC"**:

1. click **More info**;
2. then **Run anyway**.

Only once. The first start is a bit slower: the app prepares its files.

### 🔌 Signing in (Settings › Accounts)

- **Xbox**: "Sign in with Microsoft" button. The sign-in page opens in your browser: GameRadar never sees your password. Microsoft shows "unverified publisher" there: normal for a personal project (verification is only open to companies), and GameRadar only uses this access to read your game history. Right below, choose your **Game Pass** plan (Essential, Premium, Ultimate or PC Game Pass).
- **Steam** (if you play there): paste your profile address and your personal API key.
  - Your profile must show its games: Steam › Edit Profile › Privacy Settings › "Game details": **Public**.
  - Get the key at [steamcommunity.com/dev/apikey](https://steamcommunity.com/dev/apikey) (domain name: `localhost`). Keep it to yourself.
- **PlayStation** (if you play there): sign in on playstation.com, open the page of your token from the app and paste what it shows. This token opens your Sony session: keep it to yourself. GameRadar keeps it encrypted on your PC.
- No account, or a game played elsewhere (Switch…)? Add it by hand: **History › "Add a game"**.
- To switch the language: Settings › Preferences › Language.

### 🧠 How it picks

- **Your progress counts, not launching a game**: a game finished, completed at 100% or played for dozens of hours weighs a lot; a game launched for 10 minutes does not count.
- **It compares the style of games**, using the Steam players' tags ("looter shooter", "souls-like"…). Liking *Warframe* leads to *Borderlands* or *The Division 2*, not to *Call of Duty*.
- **"Because you liked X" sections**, and at the top **the games leaving your Game Pass soon**. Click a card to open the game's page.
- In the **History**, you can tick "Story finished" or remove a game from your taste (a 100% done just for the gamerscore, for example).

### 🔒 Your data

Everything stays **on your PC**, in `%LOCALAPPDATA%\GameRadar`: sessions encrypted by Windows, caches, settings. GameRadar has no server and shares nothing. **Settings › Privacy** gives the details, the links to remove its access to your Microsoft, Steam and PlayStation accounts, and a button to erase everything.

### 🐞 Something wrong?

**Settings › About › "Error log"** opens the log folder (free of any secret: no password, token or key). Send today's file with your description, or open an [issue](../../issues).

### 📜 Terms and licenses

- By using GameRadar, you accept its [**terms of use**](LICENSE.txt): free for personal use, free sharing of the unmodified file, **provided as is, without warranty**.
- GameRadar contains open-source components (Avalonia, .NET, SkiaSharp…): their licenses are in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
- Both texts are also in the app: **Settings › About**.

### ⚠️ Good to know

- Windows only.
- GameRadar uses undocumented services (Xbox Live history, PlayStation Network, Game Pass catalog) that may change without notice.
- GameRadar is an independent project, not affiliated with nor endorsed by Microsoft Corporation, Valve Corporation or Sony Interactive Entertainment. Xbox and Game Pass are trademarks of Microsoft Corporation; Steam is a trademark of Valve Corporation; PlayStation is a trademark of Sony Interactive Entertainment. Game covers and names belong to their publishers.
