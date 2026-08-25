# tristache.github.io

Racine du domaine GitHub Pages. Ce dépôt sert les liens profonds des
applications **Ramio (Rami Chinois)** et **Meldfall** :

- `.well-known/assetlinks.json` — vérification des liens profonds
  Android (App Links) : empreintes de la clé de signature Google Play,
  de la clé d'upload et de la clé de débogage pour `com.ramio` ; clé
  d'upload pour `com.meldfall` (la clé Play App Signing de Meldfall
  reste à ajouter dès qu'elle est lue dans la Play Console) ;
- `.well-known/apple-app-site-association` — équivalent iOS
  (Universal Links, Team 3SL5ZC838T) : `/rejoindre*` pour Ramio,
  `/meldfall*` pour Meldfall ;
- `rejoindre.html` — page de repli des invitations Ramio
  (`https://tristache.github.io/rejoindre?code=XXXXXX`) quand l'app
  n'est pas installée ;
- `meldfall.html` — page de repli des liens Meldfall
  (`/meldfall?jour=...`, `?graine=...`, `?salon=...`) ;
- `index.html` — redirection vers le site
  [ramio-site](https://tristache.github.io/ramio-site/).

Géré depuis le projet privé `rami-chinois` (voir son CLAUDE.md).
