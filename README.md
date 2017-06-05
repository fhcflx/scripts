# README #

Pequenos scripts (\<nome\>-i-repo) para criar novos repositórios no Github, Gitlab, Bitbucket e Gogs usando a CLI.

### Para que é este repositório? ###

* Use os scripts para configurar novos projetos remotamente no seu servidor Git preferido a partir de um terminal. É necessário ter uma conta e os dados de segurança (senha, segredo, etc) para o servidor.
* Versão alfa - 0.3 - traduzido para português do Brasil
* [Aprenda Markdown](https://bitbucket.org/tutorials/markdowndemo) - muito útil!
* Também tem scripts (git-\<nome\>) para adicionar arquivos e realizar envios em massa com a mesma mensagem padronizada (vários repositórios ao mesmo tempo). __Evite usá-los o máximo possível!__ A melhor prática de envios (commits) com o Git continua sendo _faça envios frequentes, melhore depois e publique de uma vez só._   

### Como eu configuro? ###

* Os scripts tem que ser executados da pasta onde estão. Alternativamente, faça symlinks no seu PATH.
* Nenhuma configuração necessária.

```git
$ github-i-repo
```

* Sem dependências.
* O script do gitlab precisa ser editado para colocar seus grupos de projetos (estão descritos os meus).
* Testado no macOs Sierra e no git bash para Windows, todavia deve funcionar em qualquer sistema unix; não foi testado no terminal do Windows (command ou power shell) (sinto)
* Instruções de instalação: apenas coloque em qualquer pasta e execute

### Problemas conhecidos ###

* O script do Github não vai funcionar com autenticação de duas etapas.

### Como contribuir ###

* Testando e relatando
* Revisando código
* O que quiser, na verdade

### Contato ###

* fhcflx@outlook.com
* twitter: @fhcflx
