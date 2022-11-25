# Comment utiliser ce projet

## Configurer l'environnement : 

### Installer git

 ```bash
 sudo apt install git`
```

### 

### Installer [asdf](https://github.com/asdf-vm/asdf) 

```bash
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.10.2
echo '
. $HOME/.asdf/asdf.sh
. $HOME/.asdf/completions/asdf.bash
' >>~/.bashrc
```

### Installer le plugin node


```bash
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
```

### Installer node

```bash
asdf install nodejs latest:16
asdf global nodejs latest:16
```

