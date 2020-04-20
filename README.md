<h1 align="center">
  <img src="/Images/git.png" alt="Git" width="220px" />
</h1>

# Git para iniciantes 
*Este arquivo foi escrito em abril de 2020*


## O que é Controle de Versão?

É uma categoria de ferramentas de software que **ajuda um time de software gerenciar mudanças no código fonte** ao longo do tempo. O software de controle de versão **controla todas as modificações no código** em um tipo especial de banco de dados. **Se um erro for cometido, os desenvolvedores podem voltar no tempo e comparar versões anteriores do código para ajudar a corrigir o erro** e minimizar a interrupção para todos os membros da equipe.

## O que é Git?

De longe, o **sistema de controle de versão moderno** mais usado no mundo hoje é o Git. O Git é um projeto de código aberto maduro, mantido ativamente, originalmente **desenvolvido em 2005 por Linus Torvalds**, o famoso **criador do kernel do sistema operacional Linux**.

Tendo uma arquitetura distribuída, **o Git é um exemplo de DVCS** (portanto, Sistema de Controle de Versão Distribuído). **Em vez de ter apenas um único local para o histórico completo da versão do software**, como é comum em sistemas de controle de versão outrora populares como CVS ou Subversion (também conhecido como SVN), no Git, **a cópia de trabalho de todo desenvolvedor do código também é um repositório** que pode conter o histórico completo de todas as alterações.

## Inciando no Git

### 1. Repositório
<h1 align="center">
  <img src="/Images/git_repository.png" alt="Git" width="420px" />
</h1>
Um repositório git é a pasta `.git/` dentro de um projeto. Este repositório vai mapear todas as mudanças feitas nos arquivos dos seus projetos, contruindo um histórico ao longo do tempo. Isso significa que se você deletarem a pasta `.git/`, vocês deletam todo o histórico de mudanças de seu projeto.

Além disso, existem dois tipos de repositório no `git`, o **local** e o **remoto**:
* O **local** é o repositório que fica na sua máquina de trabalho. Ele é criado utilizando o comando `git init` dentro da pasta do projeto.
* O **remoto** fica em um servidor como GitHub, GitLab, BitBucket, entre outros.
### 2. Branch
<h1 align="center">
  <img src="/Images/git_branching.png" alt="Git" width="220px" />
</h1>
Uma branch é uma `ramificação` do seu projeto. 

Pense no seguinte: você é o desenvolvedor de um site e recebe a tarefa de adicionar uma nova página em um site. 

Para não causar problemas no site que as pessoas utilizam, cria uma ramificação do site `(branch master)` no seu computador `(branch de local de desenvolvimento)` para então adicionar as mudanças. Ao terminar o seu trabalho, você simplesmente envia suas mudanças para o site, devolvendo a sua ramificação de volta para sua origem.
### 3. Stage e Commit
<h1 align="center">
  <img src="/Images/git_stage.png" alt="Git" width="420px" />
</h1>
Colocar um arquivo em **stage** significa que ele esta **pronto para ser enviado ao repositório**. Você faz isso utilizando o comando `git add nome_arquivo`.
O Git permite que você entregue somente as partes de sua alterações que estão prontas. Isso se chama colocar um arquivo em `stage`.
<br>
Após colocar os seus arquivos em **stage** está na hora de fazer o **commit**. Ao fazer um `git commit -m "mensagem_do_commit"` você está enviando todas as mudanças que estão em `stage` para o repositório local.
### 4. Histórico
Como dito anteriormente, podemos voltar no tempo e comparar mudanças. 

### 5. Merge
É o `ato de fundir duas branches` (ramificações). Quando você terminar o seu trabalho, você irá fazer um `git merge` para fundir a sua branch com a branch master.


# Tutorial

0. [Instalando e Configurando o **Git**]()
1. [Criando um **Repositório Git**]()
2. [Fazendo modificações]()
3. [Conferindo o **Status** do repositório]()
4. [Adicionando modificações ao **Stage**]()
5. [Fazendo **Commit** das modificações]()
6. 

# Desafio

Agora está na hora de colocar tudo o que você aprendeu em prática. Criamos um desafio simples, porém irá exigir que você clone um repositório localmente, altere um arquivo, adicione esse arquivo em stage, utilize o commit e por fim o push para enviar as mudanças para o servidor.

O objetivo é adicionar o seu nome no seguinte arquivo: [NAMES.md](https://github.com/Go-Horse-Coding/Git/blob/master/NAMES.md).

Boa sorte :)

## Instalando o Git Bash para versionamento de software

<img src="/Images/git_bash.png" alt="Git" width="50px" /> 

1. Baixe o [Git Bash ](https://git-scm.com/downloads)
2. Após o download execute o arquivo.
3. Aperte **Next** para todas as opções.

## Comandos [WIP]

* git status
* git add .
* git commit -m "mensagem"
* git push

## Usando o Git Bash [WIP]

TO DO

## Tarefa [WIP]

Vamos agora utlizar o Git para alterar o arquivo [NAMES.md](https://github.com/Go-Horse-Coding/Git/blob/master/NAMES.md)



Para concluir esta tarefa você deve adicionar seu nome no seguinte arquivo:

[Lista Nomes](https://github.com/Go-Horse-Coding/Git/blob/master/NAMES.md)

# Autores
* [Felipe Almeida](https://github.com/felipe-allmeida) - Criador do GoHorse Coding e Engenheiro de Software

# Referências
* https://help.github.com/en/github/getting-started-with-github/quickstart
* https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control
* https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud
* https://medium.com/@programadriano/git-para-iniciantes-3b38fa5d4ddf
* https://githowto.com/pt-BR
* https://guide.freecodecamp.org/git
