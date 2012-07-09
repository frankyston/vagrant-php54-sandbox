# pt_BR - Português do Brasil

Fork do [ricbra](https://github.com/ricbra/php54-sandbox).

Um exemplo simples de máquina virtual baseada no Debian Linux, com Apache
e PHP 5.4.

A documentação do Vagrant está disponível
[em português](http://vagrant.rogeriopradoj.com/)
e [em inglês](http://vagrantup.com/).

## Requisitos:

1. instale o [Ruby](http://www.ruby-lang.org/en/)
2. instale o [VirtualBox](https://www.virtualbox.org/)
3. instale o [Vagrant](http://vagrantup.com/)

## Como usar essa máquina:

1. clone esse repositório
2. no terminal, execute `vagrant up`
3. pronto!

O webroot do Apache será a pasta `www` da raiz do seu projeto. Essa pasta é
compartilhada com a máquina virtual, e você cria e edita os arquivos a partir
da sua máquina local (não é preciso entrar na VM para ver as coisas
acontecendo).

Mesmo assim, se precisar, você pode acessar a máquina das seguintes formas:

* Via SSH, usando o comando `vagrant ssh`, e fazer tudo a partir do seu
  terminal
* Acessando a VM pela tela, usuário `vagrant` e senha `vagrant`, e usar o
  terminal da própria VM


#en - English
Forked from [ricbra](https://github.com/ricbra/php54-sandbox).

A simple example of VM based on Debian Linux, that comes with Apache and
PHP 5.4.

Documentation of Vagrant is available
[in Brazilian Portuguese](http://vagrantup.com/)
and [in English](http://vagrant.rogeriopradoj.com/).

## Requirements

1. install [Ruby](http://www.ruby-lang.org/en/)
2. install [VirtualBox](https://www.virtualbox.org/)
3. install [Vagrant](http://vagrantup.com/)

## How to use this VM

The Apache webroot points to www directory in your project root. This folder
is shared with VM and you can create and edit your files directly on your
local/host machine (you don't need to access the VM for seeing things working).

Nevertheless, if you need, you can access the VM in this ways:

* Via SSH, running `vagrant ssh`, doing everything you need from your terminal
* Accessing the VM via "gui", user `vagrant` and password `vagrant`, and working
  on VM terminal
