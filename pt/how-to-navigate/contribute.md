# Como contribuir para este livro?

## Contribua pelo GitBook

Cria sua conta no [Gitbook.com](http://www.gitbook.com/login) e [efetue o pedido para tornar-se um colaborador](https://www.gitbook.com/book/adoptopenjdk/adoptopenjdk-getting-started-kit/contact) Do projeto [Adopt OpenJDK GitBook](http://adoptopenjdk.gitbooks.io/adoptopenjdk-getting-started-kit/)

Verifique a [documentação](http://help.gitbook.com/) e [como instalar o GitBook em sua maquina](https://github.com/GitbookIO/gitbook).

## Contribua no GitHub

1. Crie um fork
Visite este website e crie um fork: **https://github.com/adoptopenjdk/adoptopenjdk-getting-started-kit#fork-destination-box** 

2. Execute o comando abaixo para clonar o projeto no seu workspace <br/>
```git clone git@github.com:{YOUR_GITHUB_ACCOUNT}/adoptopenjdk-getting-started-kit.git```

3. Adicione o repositorio principal no Upstream do seu fork <br/>
```git remote add --track master upstream git://github.com/adoptopenjdk/adoptopenjdk-getting-started-kit.git```

Efetue o update do seu fork com o upstream, isso fara com que os updates sejam carregados:
```git fetch upstream``` 

Efetue o merge das informacoes carregadas do upstream com o seu repositorio local:
```git merge upstream/master```

4. Efetue o commit dos arquivos alterados <br/>
```git add <changes files / wild-card pattern>```<br/>
```git commit -am "meaningful description about your changes"```

5. Efetue o Push dos arquivos. Isso fara com que o seu commit seja enviado para o seu fork :D
```git push```

6. Efetue a criação de uma Pull Request, ou seja um pedido de envio de arquivos para o repositorio principal. 
Visite o site https://github.com/adoptopenjdk/adoptopenjdk-getting-started-kit/pulls e clique no botao "New Pull Request" e efetue os passos para realizar a criação.

## Como identificar mudancas no livro ?

Dois [scripts](https://github.com/adoptopenjdk/adoptopenjdk-getting-started-kit) na raiz do repositorio sao responsaveis por efetuarem a criacao da pagina <b>O Que mudou?</b>, [Exemplo](http://adoptopenjdk.gitbooks.io/adoptopenjdk-getting-started-kit/content/en/whatsChanged.html).

Os scripts responsaveis pela criacao da pagina [O Que mudou?](http://adoptopenjdk.gitbooks.io/adoptopenjdk-getting-started-kit/content/en/whatsChanged.html) sao chamados [whatsChanged.sh](https://github.com/adoptopenjdk/adoptopenjdk-getting-started-kit/blob/master/whatsChangedFor.sh) and [whatsChangedForAllLanguages.sh](https://github.com/adoptopenjdk/adoptopenjdk-getting-started-kit/blob/master/whatsChangedFor.sh).

Fique a-vontade para re-escrever os algoritmos ou efetuar mudancas, contanto que os algoritmos continuem fazendo o que fazem atualmente e mais.

Veja também [Feedback](../feedback.md), e [Como contribuir para o Adopt OpenJDK and OpenJDK ?](how_to_contribute_to_adopt_openjdk_and_openjdk.md)