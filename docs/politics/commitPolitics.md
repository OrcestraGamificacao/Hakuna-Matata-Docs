# Política de Commits

Os commits devem seguir o seguinte padrão:

* Devem ser escritos em inglês na forma infinitiva, e ainda conter uma breve descrição.

**Exemplo:**


    Create a new document.

* A issue em questão deve ser citada no commit, para isso, basta adicionar 
``` #<numero_da_issue>. ```

**Exemplo:**

    #5 Create a new document.

<b>Observação:</b> Por padrão, o caracter # define uma linha de comentário no arquivo da mensagem do commit. Para resolver este problema, use o commando:

    git config --local core.commentChar '!'

* Para que ambos envolvidos no commit sejam incluídos como contribuintes no gráfico de commits do GitHub, basta incluir a instrução ```Co-authored-by:``` na mensagem após escrever a mensagem do commit e der 2 enter's:

**Exemplo:**


    #5 Create a new document.


    Co-authored-by: Brian Pina <brian.pina2001@gmail.com>
    Co-authored-by: Paulo Henrique <ph.hr.001@gmail.com"


* Para commits que encerram a resolução de uma issue, deve-se iniciar a mensagem do commit com Fix ```#<numero_da_issue> <mensagem>```, para que a issue seja encerrada automaticamente quando mesclada na ```main```.

**Exemplo:**

    Fix #5 Create a new document.

* Para commits que incluem uma pequena mudança em uma issue que já teve sua resolução encerrada, deve-se iniciar a mensagem do commit com HOTFIX ```#<numero_da_issue> <mensagem>```

**Exemplo:**

    HOTFIX #5 Add new anwser.

## Comando de Commit

**Exemplo:**

    git commit -m '#<numero da issue> <texto>'
