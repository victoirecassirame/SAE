# Comment utiliser ce projet

## Configurer l'environnement : 

### Installer git

 ```bash
 sudo apt install git`
```

### Télécharger le fichier

Se placer dans un nouveau dossier et entrer la commande
```bash
https://github.com/victoirecassirame/SAE.git
```

### Installer [asdf](https://github.com/asdf-vm/asdf) 

```bash
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.10.2
echo '
. $HOME/.asdf/asdf.sh
. $HOME/.asdf/completions/asdf.bash
' >>~/.bashrc
```

**ATTENTION**: Il est nécessaire de fermer le terminal en cours et d'en ouvrir un nouveau pour continuer

### Installer le plugin node


```bash
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
```

### Installer node

```bash
asdf install nodejs latest:16
asdf global nodejs latest:16
```

### Installer les dépendances

```bash
npm install
```

### Lancer le projet

```bash
npm run dev
```

Le site est à présent disponible sur [http://localhost:1234/page2.html](http://localhost:1234/page2.html)
