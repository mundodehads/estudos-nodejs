# estudos-nodejs
[PT-BR] Conteudo de estudos sobre node.js

## Aprendendo ensinando node.js

Este titulo e usado na minha live na [twitch](https://www.twitch.tv/mundodehads) onde estou re-estudando o nodejs, como ele funciona e suas principais bibliotecas para trazer conteudo teorico sobre partes nao mutio exploradas do node.js. Alem da teoria pegamos temas solicitados pela live e trazemos trabalhos praticos que serao organizados neste repositorio.

## Nodejs

Node.js e um `runtime javascript` desenvolvido com a [V8](https://v8.dev/) (V8 tambem e utilizada no Chrome), onde voce utiliza linguagem de programacao javascript (ou typescript) e ao enviar para o node.js ele transpila a mesma para a linguagem da `V8`, que e interpretada e transformada em C++, que por sua vez, e compilada no compilador [LLVM](https://llvm.org/) e executada.

O fato do node.js usar a V8 e a mesma ser usada pelo Chrome faz com que o programador que "aprenda" node.js possa aplicar seu conhecimento tanto para desenvolvimento backend quanto para frontend. O aprendizado de teorias/praticas (Object, array methods, promises) sao utilizados em ambas aplicacoes.

As versoes estaveis do node.js utilizam como base o javascript definido pela [ECMA-262](https://tc39.es/ecma262/) porem para questoes de testes de features, possui versoes atualizas que podem conter novas features tanto do node.js quanto do javascript, estas podem ser encontradas no [github da TC39](https://github.com/tc39/proposals). O site [Node.green](https://node.green/) tambem oferece uma visualizacao mais detalhada das features que estao habilidas por cada versao.

O node.js dispoe de bibliotecas para auxiliar e complementar o javascript, em sua [documentacao](https://nodejs.org/dist/latest-v16.x/docs/api/documentation.html) e possivel encontrar uma lista extensa e cada uma possui um objetivo unico, normalmente relacionado a integracao com elementos da `OS`.

## Bibliotecas nativas node.js

### HTTP

- [http.Server](https://nodejs.org/dist/latest-v16.x/docs/api/http.html#class-httpserver)

### NET

- [net.CreateServer](https://nodejs.org/dist/latest-v16.x/docs/api/net.html#class-netserver)
- [net.CreateConnection](https://nodejs.org/dist/latest-v16.x/docs/api/net.html#netcreateconnectionoptions-connectlistener)
- [net.Socket](https://nodejs.org/dist/latest-v16.x/docs/api/net.html#class-netsocket)

## Aprendizado

### 1:

- Bibliotecas nativas nodejs.
  - HTTP: Criando um servidor http para entrega de arquivos estaticos (SSR);
  - NET: Criando um socket nativo em node.js com net.Socket;
  - NET: Criando um servidor backend node.js, producer e consumer com net.CreateServer e net.CreateConnection.

## Glossario

- `runtime`: software designed to support the execution of computer programs.
- `os`: operational system.
