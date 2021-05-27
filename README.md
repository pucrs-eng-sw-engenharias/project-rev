# Exercícios sobre os conceitos e comandos do Git


Hoje vamos fazer um estudo dirigido, praticando algumas operações do Git. Para cada operação, leia o material de apoio para entender o que está acontecendo.


## Passos
#### As passos a seguir devem ser executados em dupla, em uma única máquina.
1. Clone este repositório em uma pasta do seu computar. Neste momento, será criado um projeto com um repositório do Git (pasta .git).
   * Dica: git clone
1. Verifique seu user name e seu email.
   * Dica: git config user.name e git config user.email
1. Crie alguns arquivos na pasta do projeto.
1. Adicione estes arquivos na área de stage.
   * Dica: git add
1. Coloque seus arquivos sob gerenciamento da configuração.
   * Dica: git commit
1. Atualize este repositório no Github, enviando seu projeto para o repositório remoto.
   * Dica: git push
1. Crie um programa em C/C++ que imprima "Hello, World". Quando pronto, faça novo commit.
#### A partir daqui, cada membro do grupo deve executar os passos na sua máquina.
1. Crie uma nova branch, para uma nova linha de desenvolvimento. Chame-a de "dev-req1-SeuNome"
    * Dica: git checkout -b
1. Compartilhe o repositório (todas as branches) no seu repositório remoto. 
    * DICA: pode haver um conflito entre o repositório local e o remoto, após todas estas alterações. Resolva o conflito trazendo o repositório remoto (git pull) e mesclando-o com o local
1. Altere seu código, colocando um novo print com o seu nome e o nome da branch.
1. Faça o *merge* das branches na branch principal. 
    * DICA: git merge
1. Atualize o repositório remoto
