- Git é um sistema de versionamento, onde posso criar versões dos meus projetos. 

- Este arquivo foi criado para me lembrar os comandos básicos do git/github

  

  Paulo Henrique Letro

  **Linkedin:** https://www.linkedin.com/in/pauloletro/

  

- [x] Crio Arquivo git.txt

  

- [x] Utilizando CMD para navegar ate a pagina onde se encontra o arquivo **git.txt** para mudar o nome dele utilizando o comando ren git.txt .gitignore (caso precise: No caso do C# ele ignora arquivos onde o repositório não precisa controlar versão)

  

- [x] Colocar instruções dentro do arquivo .gitignore para o repositorio .git saber quais arquivos ele nao precisa controlar versão.

  

- [x] Configurar usuario e email:

   **git config --global user.name** "Nome"

   **git config --global user.email** "email@email.com"

   

- [x] Iniciando o Repositorio Git(.git)

   **git init**

   

- [x] Salvando Versão do Projeto: 

   * Para ver como os arquivos estão, os estados dos arquivos:

     **git status**

     

   * Colocar o arquivo no staged (Isso quer dizer que o arquivo estará pronto para "comitar" ou ser inserido no repositório local **.*git***:

     **git add .** ou **git add *** (Ambos comandos servem para adicionar os arquivos no stage, assim os arquivos ficam verde quando damos um novo git status)

     **git commit -m** "Mensagem qualquer" (Esse Comando pega o arquivo antes no staged e o coloca no repositório local **.git**)

     

     untracket ------>>> Stage

     

     (Caso esqueçamos de colocar a mensagem, o editor vim será aberto, para fechar é só digitar esc e depois escrever :q! e é só fazer o commit de novo)

     ![coomit](C:\Users\paulo\Desktop\coomit.PNG)

     - Para verificar todos os meus commits:

     **git log**    ou      **git log --oneline**(Esse comando mostra um resumo dos commit)





- [x] Associando nosso repositório local ao repositório remoto:

   ​	**git remote add origin**  <URL do repositorio>	

   ​	**git remote set-url origin** <URL do repositorio> (Esse comando é utilizado quando queremos trocar o repositório remoto)

   

   * Subindo o repositório local (do computador) para o github:

     **git push -u origin master**   (origin é o apelido que demos para o repositório local)

     **git push**  (Caso queira subis arquivos alterados depois apenas o git push é preciso)

     

   * Clonando repositorio do github para o repositório local:

     **git clone <URL do repositorio>	**

   

- [x] Manipulando Commits:

    

   * Voltar ao estado do ultimo commit:

     **git clean -df**

     **git checkout -- .**

   

   * Desfazer o commit mantendo as alterações dos arquivos no STAGE:

     **git reset --soft  HEAD~1**

   

   * Remover os arquivos e voltar ao commit anterior:

     **git reset  --hard HEAD~1**

   

   * Olhar uma Versão anterior:

     **git checkout** <Codigo do commit>	

   

   * Voltando para o ultimo commit:

     **git checkout master**

   

   - Lista as configurações User name e meial
     **git config --list**

   

   - Para saber quais repositórios remotos meu repositório local está linkado

     **git remote -v**

   

   - [x] Manipulando branchs:

   - Para verificar em qual branch estamos

     **git branch**

   

   - Para criar arquivos na linha de comando

     **echo > nomeDoArquivo.extensão**

   

   - Para mudar de branch e criar uma branch nova

     **git checkout -b nomeDaBranch**

   

   - Apenar mover de Branch

     **git checkout nomeDaBranch**

   

   - Juntar as duas Branch

     **git merge nomeDaBranchNova(aquela por exemplo que pode ter se originado da master)**
    
    
    
  - Criando Tag
  
    git tag -a <nome da tag> -m <comentário>
    
    
  
  - Publicando Tag
  
     **git push origin --tags**
  
    
  
  - Mostrando Tag
  
      **git show <nome da tag>**
  
  
  
  - [x] Executando o Merge e resolvendo conflitos
  
  
  - ```
    git merge <nome da branch que você quer adicionar a outra que você esta em checkout no momento> - Resolvemos o conflito - Damos o git add . - git commit -m "nome do commit" - git push origin <nome da branch atual em checkout>
    
    ```
  

  - [x] Atualizando com todas as branch criadas

  - **git fetch**

  

  - **:q sai da tela do VIM**

  

  

  

  

  

  

  

  

  

  

  
  
  
  
  
  
  
  
  
  
  
  
  
   ​	

​    

   

   

   

   

   

   

   

   

   

   

   

