<h1 align="center"> Desafio de projeto sobre Git/GitHub da DIO </h1>
Criando meu primeiro repositório no GitHub para o desafio de projeto do curso Orange tech + inter em parceria com a DIO para registrar e compartilhar meu aprendizado e informações sobre o git.


## Site para baixar o Git
- faça o download do git para windows aqui (https://git-scm.com/download/win)<br>
- depois de baixado,clique duas vezes no arquivo para iniciar a instalação.Basta seguir as instruções na tela,clicando em next. Ao final, clique em finish para concluir.

## Configurações básicas do Git
Após instalação do git umas das primeiras coisas a serem feitas é a configuração dos  dados do usuário , para poder identificar quem está tomando as ações. Basta abrir o prompt de comando e digitar os seguintes comandos no terminal:

 > git config --global user.name  " digite seu nome"

 > git config --global user.email "digite seu email"

## Criando um repositório 
Crie uma pasta, a pasta criada, será a pasta raiz do seu projeto,onde você criará seu repositorio  local com o comando:

                               git init
                              
                              
## Atualizando repositório local
Busca sicronizar o conteúdo do repositório remoto ao seu repositório local, para isso utilize o comando:

                               git pull


## Baixando um repositório do github 
Clona um repositório do servidor com o seguinte comando:

                              git clone  https://url-no-github/ /caminho/que/deseja/baixar

## Gravando alterações
Dentro do seu repositório, após feitas as alterações desejadas, você deve grava-las, para então "commita-las". O comando é o:

                              git add "nome do arquivo" 
                        
 caso queira gravar todas as alterações, utilize * no lugar do nome do arquivo do exemplo acima.
 
 ## Verificando status dos arquivos
 Após gravadas as alterações, você pode verificar o status dos arquivos, em qual branch você se encontra e todos os arquivos que tiveram e não tiveram alterações. com o comando:
 
                             git status
                             
 Commit
 Para que sejam confirmadas as mudanças feitas em seu códigos será necessario "commitar" o código com o seguinte comando:
 
 
                             git commit -m "comentário de alterações"
                             
É possivel também verificar todos os commits, com o comando:

                             git log


                        

                              

