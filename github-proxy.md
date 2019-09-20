Pour passer le proxy de Lille1 avec connection ssh:

Ajoute cette portion dans ~/.ssh/config (chemin par défaut)

```
Host github.com
  Hostname ssh.github.com
  Port 443
```

