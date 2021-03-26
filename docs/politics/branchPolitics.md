# Política de Branches

Sempre que for criar uma nova branch, verifique-se que você está na devel e crie a branch a partir dela.

As _branches_ devem seguir o seguinte padrão:

* O nome da branch deve ser abstraído do nome da história de usuário a qual se refere.

**Exemplo:**

    CriarLogin #3


* O nome da _branch_ deve possuir uma 'tag' que é o número da issue a qual se refere e deve estar em CamelCase ```x-NomeDaBranch ```, em que o 'x' é o número da issue.

**Exemplo:**

    3-CriarLogin


* Caso a _branch_ não esteja associada a alguma issue, não é necessario a adição da 'tag'.

**Exemplo:**

    RefatorarLogin
