1 verificar se estamos no obuntu    
2 file -> open folder 
2.1 apaga o conteudo 
2.2 informa o caminho /var/www/html
2.3 abre a pasta ( com enteder ou clic com mouse em html )
3 - terminal, novo terminal 
4 - no terminal executa o comando : git clone  LINK DO REPOSITORIO ( GITHUB) 
5 -informa o caminho : var/www/html/php_23
5.1 - abre essa pasta (com enter ou click no mouse em html


6 configurar o git ( git email e git name da pag 4 da apostila) 
7 - verificar se o apache esta rodando/ executando 
7.1 acessar o navegador com localhost ou 127.0.0.1 ( deve aparecer a configuração do apache )
7.2 sudo service apache2 status ( apache is running) 
7.3 sudo service apache2 start .
7.4 executar novamente os passos 7.1 e 7.2 


## para salvar no Github
1 - git add . ( . = todos os arquivos ou especificar por nome ex.: git add index.php
2 - git commit -m " DESCREVER O QUE FOI FEITO "
3 - git push 
4 - verificar no github se focou salvo.

### para o merge
1 git checout  NOME BRANCH
2 git pull ( obter atualizações )
3 git merge  NOME DA BRANCH DE TRAZER AS MUDANÇAS 

EX:
      estamos na branch * Develop* e queremos levar as mudanças para master 
      1  git checkout * master*
      2  git pull ( master ) 
      3 gir merge * Develop *
      4 resolver conflitos se houver
      4.1 com conflito : git add . e git commit -m ' .... '
      4.2 sem conflito so git merge e git push 
      

      estamos na black * master * e queremos levar para Develop

      1 git checout * master * 
      2 git pull ( Develop )
      3 git merge * master * 
      4 resolve conflitos se houver 
      5 git push 

