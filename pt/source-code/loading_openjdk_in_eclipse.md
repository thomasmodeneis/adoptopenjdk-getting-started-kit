# Eclipse

Para ver / editar fontes Java no Eclipse:
 - Criar um novo projeto Java "New Java Project"
 - Desmarcar a opção "Use default location"
 - Procure polo diretorio jdk/, que contenha o src, make e test. Example /home/openjdk/dev/jdk9/jdk no Ubuntu VM, or smb://server/user/dev/jdk9/jdk se voce estiver usando a opção de vm compartida com a[host machine](../virtual-machines/sharing_host_folder_with_guest_vm.md). Aperte OK e espere. Seja paciente, pode tardar um pouquinho.
 - Outra alternativa é escolher um sub-diretorio descrito acima, por exemplo java.base/share/classes e trabalhar apenas com ele, seria um sub-set dos sources e deve carregar mais rapidamente.
 
Desmarcar a opção Eclipse's **Build automatically** para prevenir erros no build e largas respostas do Eclipse.

