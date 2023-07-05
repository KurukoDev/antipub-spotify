# antipub-spotify

Hey, tu en a marres des pubs Spotify ? 👋
Il te suffit juste de faire une commande dans un PowerShell, tous simplement, sa néccesite aucune competences, juste savoir ctrl c + ctrl v !

⚠ Il faut savoir que cette commande ne vient pas de moi. ⚠

1. Veuillez ouvrir un PowerShell avec les autorisations Administrateurs
2. Vous copiez cette commande : ```[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iex "& { $((iwr -useb 'https://raw.githubusercontent.com/amd64fox/SpotX/main/Install.ps1').Content) } -new_theme"```
3. Vous allez dans le PowerShell et vous coller cette commande
4. Laissez faire le PowerShell tous seul, il va vous mettre différentes questions.

Exemple : 

Voulez-vous désactiver les podcasts, épisodes et livres audio de la page d'accueil ? [Y/N]: 
```Vous devez répondre : Y```
Voulez-vous bloquer les MàJ Spotify ? [Y/N]:
```Vous devez répondre : Y```
