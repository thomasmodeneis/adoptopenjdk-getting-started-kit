# Desenvolvedores experientes - Manual de passos para executar antes do HackDay 

##### Crie sua VM

Nota: Você vai precisar banda larga para efetuar o download dos arquivos, e bastante tempo para compilar os arquivos. **Não recomendado para conexões wifi.**

<br/>
[Faca sua propria VM](../virtual-machines/build_your_own_vm.md) <br/>
[Faca sua propria light-weight VM](../virtual-machines/build_your_own_lightweight_vm.md)

<br/>
##### Check VM
- Instale a VM no VirtualBox
- Inicie a VM
- Execute qualquer programa dentro da VM
- Desligue a VM

<br/>
##### Efetue o Download das Imagens Docker
Uma vez que as imagens do Docker finalizarem o downloaded elas podem ser copiadas de um local para outro, veja seção [Copiar Imagens](../docker-images/copy-images.md).
  
<br/>
##### Efetue o Build das Images
Checkout [Build Images](../docker-images/build-images.md).

<br/>
##### Verifique a consistencia das Imagens
Veja [Checando Imagens](../docker-images/check-images.md).

<br/>
##### Verifique a instalação e o ambiente
Inicie a VM ou o Docker Container, navigar para o diretorio do jdk8 ou do jdk9, e executr o comando abaixo:

```
bash configure
make clean images
```

Se um desses comandos falhar, significa que o ambiente do OpenJDK nao foi corretamente criado. Verifique os passos e tente novamente, ou chame-nos em nossas listas caso desconfie que seja um problema no OpenJDK.

<br/>
##### Finalmente
Apos executar todos os passos, se tudo correr bem, recomendamos [Como listar diretorios e progredir rapidamente?](how-to-navigate-and-make-progress.md)