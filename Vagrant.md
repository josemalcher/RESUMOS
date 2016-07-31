#Resumo - Comandos - Referências sobre Vagrant

O Vagrant é um gerenciador de VMs (máquinas virtuais). Através dele é possível definir o ambiente de desenvolvimento onde seu projeto irá rodar. Com suporte para Mac OSX, Linux e Windows, consegue atender boa parte dos desenvolvedores. Ele utiliza providers, boxes e se necessário provisioners.

**Providers**

O Vagrant precisa ter um provider instalado. Ele será onde a máquina virtual contendo seu ambiente irá rodar. O Vagrant dá suporte a providers como VirtualBox, VMware e AWS.

**Boxes**

Afim de evitar o processo tedioso de criar uma VM do zero, o Vagrant trabalha com boxes. Elas são imagens base para ele clonar uma VM. Definir uma box para seu ambiente é o primeiro passo a ser feito na configuração do seu Vagrantfile. Caso a box selecionada já tenha tudo o que você precisa, não é necessário se preocupar com provisioners.

**Provisioners**

Com provisioners é possível pré-instalar aplicações, definir configurações e realizar toda a parte de ajuste fino de uma box para atender as suas necessidades. É possível utilizar desde shell scripts básicos até sistemas de gerenciamento de configurações como o Chef, Puppet e Docker.

##Referências
[Site oficial](https://www.vagrantup.com/)

[Vagrantbox.es](http://www.vagrantbox.es/)

[Configurando um ambiente de desenvolvimento com Vagrant](http://shipit.resultadosdigitais.com.br/blog/configurando-um-ambiente-de-desenvolvimento-com-vagrant/)