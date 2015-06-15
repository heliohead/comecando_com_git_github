!SLIDE center
## Começando com:
# ![GIT](git.png) ![GitHub](github.png)
por Helio Oliveira
<div class="shivs">Grupo de estudo HTML5</div>

!SLIDE center bullets incremental transition=fade
# About Me:
* Usuário Unix desde 2000
* Amante de Técnologia
* Cursando Análise e Desenvolvimento de Sistemas
* ![github](github-icon.png)heliohead
* ![twitter](twitter-icon.png)heliohead

!SLIDE bullets incremental transition=wipe
# Preferências
* ![Ruby](ruby.png)
* ![JavaScript](javascript.png)
* Sinatra, Rails, Node

!SLIDE bullets  incremental transition=curtainX
# Iremos aprender:
* O que é, e para que serve o Git
* Como instalar o GIT
* Comandos básicos
* O que é GitHub e um overview do serviço

!SLIDE bullets  incremental transition=curtainY
# ![git-bg](git-bg.jpg)

!SLIDE bullets  incremental transition=scrollUp
# O que é, e para que serve o Git

Git é um [VCS](https://en.wikipedia.org/wiki/Revision_control) = Version Control System, Sistema de controle versão, existem dois tipos de VCS, os centralizados e os distribuídos, o [Subversion ou SVN](https://subversion.apache.org/) é centralizado enquanto [GIT](https://git-scm.com/) e
[Mercurial](https://mercurial.selenic.com/) são distribuídos, isso quer dizer que nos VCS centralizados um servidor central é requirido e todos os commits são enviados para este repositório central, nos sistemas distribuídos cada desenvolvedor tem uma cópia (clone) do projeto inteiro e comita em sua cópia local, e pode enviar para um servidor remoto suas alterações que por sua vez é compartilhada com outros desenvolvedores.

!SLIDE bullets  incremental transition=fadeZoom
![linus](linus.png)

Git foi escrito em 2005 por [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds) por conta de sua insatisfação com o [CVS](http://www.nongnu.org/cvs/) e [BitKeeper](http://www.bitkeeper.com/), no versionamento do kernel do Linux, [este](https://www.youtube.com/watch?v=4XpnKHJAok8) é o link para um talk do Linus explicando do jeito Linus de ser suas motivações para começar este novo projeto.

O nome GIT é uma gíria Inglesa para cabeça dura ツ
>Eu sou um egoísta degenerado, batizo todos os meus projetos com meu nome. Primeiro Linux, agora Git.
>"Linus Torvalds"

!SLIDE bullets  incremental transition=shuffle
# Como instalar o Git

* No Windows <br />
<br />
Eu indico [msysgit](http://msysgit.github.io/) que prove um emulador BASH para melhor utilizaçao do command line <3

* No Lixux <br />
<br />
É só utilizar os pacotes de sua distro favorita [apt](http://linux.die.net/man/8/apt-get), [rpm](http://www.rpm.org/max-rpm/ch-rpm-install.html), [pacman](https://wiki.archlinux.org/index.php/Pacman)

* No OSX <br/>
<br />
```
$ brew install git
```
* Ou baixar do site [oficial](https://git-scm.com/downloads)

!SLIDE bullets  incremental transition=toss
# Como funciona o Git
![git-beyond](git-beyond.jpg)

!SLIDE bullets  incremental transition=toss
# Stage
![stage](stage.png)

* Git funciona com o conceito de stage, um aquivo novo inserido no diretório iniciado com com Git, precisa ser colocado em stage antes de ser commitado efetivamente, se não, o Git não vai se importar com ele e as alterção não serão contabilizadas, do mesmo modo você pode retirar um arquivo da área de stage que não deseja mais ser monitorado.


!SLIDE bullets  incremental transition=toss
# Branches
![branches](branches.png)

* Git trabalha com conceito de [branches](https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-B%C3%A1sico-de-Branch-e-Merge), como uma árvore com vários galhos, um commit seria como uma folha, no galho, sendo que você pode unir os galhos com um [merge](https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-B%C3%A1sico-de-Branch-e-Merge) as folhas passam a pertencer ao mesmo galho e também alterar a ordem das folhas com um [rebase](https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-Rebasing).



!SLIDE commandline incremental
	$ git init


!SLIDE center bullets incremental
* # That's it!

* # for you!

!SLIDE center bullets incremental
# Obrigado!
* Espero que tenham gostado

!SLIDE center bullets
# Links 
* Meu [blog](http://blog.lio.pw)

!SLIDE center bullets
# Perguntas?
