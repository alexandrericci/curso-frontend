# curso-frontend


# Git
## Conceitos de versionamento
 - Histórico
 - Controle da versão
 - Quem alterou
 - O que alterou
 - Quando alterou
 - Todos os arquvos
 - Evolução quantina

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2 

## Instalação do Git
https://git-scn.com/

- Windows: https://git-scn.com/downlod/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew intall git

## Criar conta no GitHub

## Clonar o projeto
git clone https://github.com/alexandrericci/curso-frontend.git

## comits
 Informação de alteração
 - após testado todo seu código
 - git add *
 - git commit -m "mensagem"
 - git push (enviar alterações para o repositório)
 - git pull (puxar / trazer alterações do GitHub para a minha máquina)

## GitFlow
Fluxo do Git

### Branchs
são ramificações / paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop 
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

git checkout -b dev (criar uma branch)
git checkout master (mudar de branch)


### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente


git merge main

### Pull Requests
Mescla de branchs no repositório
Permite code review
O repositóri resolve os conflitos automaticamente 

### configurar o GitFlow
git flow init
git flow feature start {nome-da-feature}
