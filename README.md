# Introdução ao controle de versão de código com Git, GitHub e TortoiseGit

---

### Configuração Inicial do Git

Com o [Git](https://git-scm.com/downloads) instalado no seu computador, você precisa personalizar o ambiente Git para sincronizar sua conta do [Github](https://github.com/) ou do [Gitlab](https://about.gitlab.com/) com o seu ambiente de trabalho local. 

Para configurar seu nome de usário e endereço de e-mail, basta abrir o `Git Bash Here` em alguma pasta e digitar

````
git config --global user.name "Fulano de Tal"
````

para definir o nome de usuário que aparecerá como `marcação` quando realizar `commmits` em sua máquina e 

````
git config --global user.email fulanodetal@exemplo.br
````

para definir o seu e-mail do [Github](https://github.com/) ou do [Gitlab](https://about.gitlab.com/).

> Esse procedimento é necessário apenas uma vez e, caso precise alterar o usuário, basta realizá-lo para a conta que deseja.

### Verificando as configuração do ambiente Git

Uma vez que as configurações de ambiente são definidas, você pode verificá-las por meio do seguinte comando

````
git config --list
````
