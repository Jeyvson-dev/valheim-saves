# valheim_world
Git para compartilhar o servidor/mundo de Valheim

Clonar esse repo dentro da pasta de mundos do Valheim:
WINDOWS + R -> cola esse caminho
```%appdata%/../LocalLow/IronGate/Valheim/worlds_local```

Agora clona o repo:
```git clone https://github.com/lucasframoon/valheim_world.git```

Quando for abrir o servidor, SEMPRE executar:
```
git pull origin master
```

Quando fechar o servidor:
```
git commit -a -m "update world"
git push origin master
```

