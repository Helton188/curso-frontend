# curso-frontend
#### EBAC

# GIT
## versionamento
 - Histórico
 - Controle de versõa
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua

 Arquivo A | Versão 1 | Versão 2
 Arquibo B | Versão 1 | Versão 2

 ## Intalação do Git
 https://www.git-scm.com/

 Windows: https://www.git-scm.com/download/win
 Linux (apt-get): sudo apt-get install git
 Mac (brew): brew install git

 ## Criar conta no GitHub

 ## Clonar o projeto
 git clone https://github.com/Helton188/curso-frontend.git

 ## Commits
 Informação de alteração
 - após testado todo seu código
 - git add *
 - git commit -m "mensagem"
 - git push (enviar alterações para o repositório)
 - git pull (puxar / trazer alterações do GitHub para sua máquina)

## GitFlow
Fluxo do Git

### Branchs
São ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop
- DOD Definition of Done: critério de aceite
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)


### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente

git merge main

### Pull Requests
Mescla de branchs no repositório
Permite code review
O respositório resolve os conflitos automaticamente


### configura o GitFlow
git flow init
git flow feature start {nome-da-feature}
