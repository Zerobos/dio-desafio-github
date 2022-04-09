# DIO - Desafio GitHub
Desafio de Projeto sobre Git/GitHub

Primeiramente, é necessário baixar o Git, então aqui vai alguns links para começarmos:

[Para Windows](https://windows.github.com)

[Para Mac](https://mac.github.com)

Distribuições do Git para Linux e sistemas POSIX são disponíveis no 
site [oficial](http://git-scm.com)



## Configurando o Git
Como configurar as informações de usuário para todos os repositórios locais.


###### __git config --global user.name "[*e seu nome*]"__
Configura o nome que você quer vinculado aos seus arquivos de 
commit

###### __git config --global user.email "[*e seu email*]"__
Configura o email que você quer ligado as suas transações de commit

######  __git config --global color.ui auto__
Essa é a variável mestre para cores do Git. Definir a variável como false desabilita todas as saídas de terminal coloridas do Git.


## Criando repositórios
Iniciando um novo repositório ou obtendo através de uma URL.


###### __git init [*e o nome do projeto*]__
Irá criar um novo repositório local com um nome específico

###### __ git clone [*e a URL ou SSH*]__
Fará o download do projeto e seu histórico de versão

## Fazendo Alterações
Estes comandos são para revisar edições e criar uma troca de commit.


###### __git status__
Faz uma lista com todos os arquivos novos ou modificados para serem commitados

###### __git diff__
Mostra diferenças no arquivo que não foram realizadas

###### __git diff --staged__
Mostra a diferença entre arquivos selecionados e a suas últimas 
versões

###### __git add [*nome do arquivo*]__
Faz o snapshot de um arquivo na preparação para versionamento

###### __git commit -m "[*mensagem de descrição*]"__
Grava o snapshot permanentemente do arquivo no histórico de versão

## Mudando Grupos
