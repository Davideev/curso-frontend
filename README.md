
# GIT
## versionamento
- Histórico
- Controle de Versão
- Quem alterou 
- O que alterou 
- Quando alterou
- Todos os arquivos
- Evolução continua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do Git
https://git-scm.com/

For Windows: https://git-scm.com/download/win <br>
Linux (apt-get): sudo apt-get install git <br>
Mac (brew): brew install git

## Criar conta no GitHub

## Clonar o projeto
git clone https://github.com/Davideev/curso-frontend.git

## Commits 
Informação de alteração
- após testado todo seu código
- git add * 
- git commit  - m "mensagem"
- git push (enviar alterações para o repositório GitHub)
- git pull (puxar / trazer alterações do Github para minha máquina)

## Gitflow
Fluxo do Git

## Branchs

São ramificações / versões paralelas
-main / master (v ai para produção,quando o projeto é publicado)
-develop
-DOD Definition of Done: Critérios de aceite
versinamento 1.0.0

-git checkout -b dev (cria um branch)
-git checkout master (mudar de  branch)

### Merge 

Mesclas de Branchs
Você pode precisar resolver  conflitos manualmente 

git merge main

### Pull Request 

Mescla  de branchs  no repositório
Permite code review
o repositório  resolve  os conflitos  automaticamente 

### Configuração GitFlow 

git flow  init
git flwo  feature star {nome-da-feature}
## Comandos Config Global
git config --global user.name "David Ferreira" <br>
git config --global user.email dferreira02@live.com <br>
git config ( options )<br>
