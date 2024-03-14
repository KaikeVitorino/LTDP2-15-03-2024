- - -

## 1. Pesquise, execute e explique o que significa o comando Git abaixo:
* $ git remote add origin https://gitlab.com/grupo/myproject.git
#### Explicação: Esse comando adiciona um repositorio remoto na sua maquina local com o nome de origin. O link mostrado eh do repositorio que esta no gitlab.
- - -

## 2. Pesquise, execute e explique o que significa os comandos Git abaixo:
#### Explicação: Cria uma branch nova com o nome que vc colocou.
    $ git branch [nome-da-branch]
    
#### Explicação: Deleta a branch que vc especificou.
    $ git branch -d [nome-da-branch]
    
#### Explicação: Muda para a branch que vc quer do repositorio.
    $ git checkout [nome-da-branch]
    
#### Explicação: mostra uma lista com todas as branches que existem.
    $ git branch -a

#### Explicação: Alem de criar uma nova branch com o nome que vc colocou, ele muda para ela.
    $ git checkout -b [nome-da-branch]
- - -

## 3. Pesquise, execute e explique o que significa o comando Git abaixo. Adicione na sua explicação as variações desse comando utilizando o nome de branches.. 
#### Explicação: Ele pega as atualizações mais recentes do repositório remoto para o a sua maquina local e junta automaticamente com a sua branch atual. Pelo que entendi, ele combina o git fetch, que busca atualizacoes e o git merge que junta na sua branch.
    $ git pull

### Variações e suas explicações:

#### Explicação: Isso pega e junta as alterações de todas as branches do repositório remoto chamado origin na sua branch local.
    $ git pull origin

#### Explicação: Isso pega e junta as alterações da branch remota específica, identificada por <nome-da-branch-remota>, no repositório remoto origin para a sua branch local.
    $ git pull origin <nome-da-branch-remota>

#### Explicação: Isso pega e junta as alterações de todas as branches do repositório remoto especificado "<nome-do-remoto>" na sua branch local.
    $ git pull <nome-do-remoto>

#### Explicação: Isso pega e junta as alterações da branch remota específica, identificada por <nome-da-branch-remota>, no repositório remoto especificado por <nome-do-remoto> para a sua branch local.
    $ git pull <nome-do-remoto> <nome-da-branch-remota>

- - -
