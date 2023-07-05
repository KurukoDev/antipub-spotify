# antipub-spotify

Salut, tu en as marres des pubs Spotify ? 👋

Il te suffit juste de faire une commande dans un PowerShell, tous simplement, vous avez besoin d'aucune compétences, juste savoir Ctrl c + Ctrl v !

⚠ Il faut savoir que cette commande ne vient pas de moi. ⚠

1. Veuillez ouvrir un PowerShell avec les autorisations Administrateurs
2. Vous copiez cette commande : ```[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iex "& { $((iwr -useb 'https://raw.githubusercontent.com/amd64fox/SpotX/main/Install.ps1').Content) } -new_theme"```
3. Vous allez dans le PowerShell et vous coller cette commande
4. Laissez faire le PowerShell tout seul, il va vous mettre différentes questions (réponse en dessous).
6. Dès que ce message est affiché, laisser faire et ne bouger plus : ```Modification de Spotify...```

Exemple : 

Voulez-vous désactiver les podcasts, épisodes et livres audio de la page d'accueil ? [Y/N]: 
```Vous devez répondre : Y```

Voulez-vous bloquer les Maj Spotify ? [Y/N] :
```Vous devez répondre : Y```
