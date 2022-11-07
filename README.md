 # Desafio de projeto sobre Git/GitHub da DIO
 
 😉 Criando meu primeiro repositório no GitHub para o desafio de projeto do curso Orange tech + inter em parceria com a DIO para registrar e compartilhar meu aprendizado e informações sobre o git. 
 
 
 
 
 
  # 💡 O que é Git e GitHub?
  O Git é um sistema de controle de versão de arquivos e tem a função de registrar quaisquer alterações feitas em cima de um código, armazenando essas informações e permitindo que  o programador Através dele possa desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos. e o GitHub é uma plataforma totalmente online onde você pode criar repositórios e hospedar neles seus projetos, colaborar com softwares open source, seguir outros programadores e interagir com códigos de terceiros. Git repositório local e o GitHub repositório remoto.



## 📌 Configurando o Git
1. Instalando o Git na sua máquina:

- faça o download do git para windows aqui (https://git-scm.com/download/win)<br>
- depois de baixado,clique duas vezes no arquivo para iniciar a instalação. Basta seguir as instruções na tela,clicando em next. Ao final, clique em finish para concluir.


2. Configuração inicial do Git:
- Após instalação do git umas das primeiras coisas a serem feitas é a configuração dos  dados do usuário , para poder identificar quem está tomando as ações. Basta abrir o prompt de comando e digitar os seguintes comandos no terminal:

 > git config --global user.name  " digite seu nome"

 > git config --global user.email "digite seu email"
 
 
 

## 📌 Criando um repositório local


- Crie uma pasta no diretório desejado:

      mkdir "Nome-da-pasta"
    
- Acesse a pasta:

      cd Nome-da-pasta
    
- Em seguida inicialize o repositório:

      git init
                  
                  
                              
                              
## 📌 Rastreando os arquivos

-Mostrar o estado atual do seu repositório:

      git status
                                                              
                                                              
- para adicionar arquivos no repositório:
                                                          
      git add "nome do arquivo"
                                                         
                                                         
- Para  adicionar todos os arquivos de uma só vez:

        git add .
                
 *Obs: todos os arquivos adicionados no git devem ser commitados
                                                               
                                                               
## 📌 Enviando alterações

- Para gravarmos as mudanças no repositório (fazer o commit), devemos executar o comando:


      git commit -m "comentários das alterações"
              
              
                                                                               

## 📌 Ligando seu repositório local(Git) para o remoto( GitHub):

- Devemos agora apontar o repositório da nossa máquina para o repositório do GitHub.

                                                 
      git remote add origin url_do_repositório_remoto
            
            
 utilize **$ git remote -v** para mais informações sobre o repositório.
             
                              
                               

## 📌 Enviando as alterações para o GitHub

- Fazer push para o repositório remoto, atualizando-o conforme o seu repositório local:

      git push origin master


Com o comando anterior, enviamos as alterações para o repositório remoto configurado com o nome origin.
Forneça seu usuário e senha do GitHub quando solicitado. Deverá aparecer algo semelhante à seguinte saída:

Username for ’https://github.com’: username
Password for ’https://fulanodasilva@github.com’ 




## 📌 Obtendo um repositório

- Clonar um repositório já existente:

      git clone url_do_repositório
                                                   
                                                   

##### Não esqueça de alterar esse link para o do repositório que pretendes clonar.


  
## 📌 Criando uma branch

- O branch master é o branch “padrão” do repositorio, para criar outra branch utilize o comando:
 
      git checkout -b nomedabranch
                                                             
                                                             
                     
##### Esse comando criará uma branch em seu local de trabalho, Não será exibida nenhuma resposta. Se listarmos as branches com o comando <code>git branch</code>, aparecerá as nossas branches.

- Para fazer o push (algo como enviar) da nova branch para o repositório remoto, você precisa usar o comando a seguir:

      git push -u <local-remoto> <nome-da-branch> 

- para retornar para a branch master:

      git checkout master
               
               


## 📌 Trocando de branch

- Para trocarmos para a branch recentemente criada, devemos executar:

      git checkout <nome-da-branch>
                                                             
                                                             
                
                                                             

## 📌 Deletando uma branch

- Para deletar uma branch, devemos utilizar a opção <code>-d</code> do <code>git branch</code> executando comando:
                                                                       
      git branch -d <nome-da-branch>
                                                                

##### Não é possível remover uma branch enquanto estivermos nela. Por isso, devemos ir para outra branch. Para ir para a branch, devemos executar:

      git checkout nomedobranch
