A maquina virtal é um programa que simula o sistema de um computador que você pode usar programas como se fosse um computador real. Permite a criação de de multiplos ambientes no mesmo disco rigido.

Segui o conselho do subject, pois ele é mais amigavel para uso e mais fácil de configurar, instalar e manipular.

Debian é uma das distribuições mais antigas de linux, lançada em 1993. É mantida pelos usuários e não tem suporte comercial. Ela é escolhida por sua estabilidade, segurança e uma grande comunidade de usuarios.

Rocky linux é uma distribuição voltada para empresas, feita 100% para competir com as melhores distribuições empresariais. Não tem uma GUI tão fácil igual ao debian.

O objetivo da máquina virtual é prover um ambiente de execução com hardware e sistema independente do seu sistema atual.

Aptitude é uma versão melhorada do apt. 
Apt é um gerenciador de pacotes de baixo nível e o aptitude é um gerenciador de pacotes de alto nível.
Aptitude oferece melhores funcionalidades e desempenho.

AppArmor é um módulo de segurança que permite o administrador do sistema restringir as permissões dos programas.

LVM é gerenciador de volume lógico (partições). Você consegue alocar e gerenciar memória do seu hd/ssd. E é mais flexível do que os métodos convencionais de particionamento.

usermod -aG groups user
getent group groupname
passwd username
groupadd groupname

etc/sudoers

ufw status verbose | grep 4242
ufw app list 
ufw allow port
ufw delete port (ufw status numbered para ver o número na lista)

ssh -V
