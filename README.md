### Axios

Axios é um cliente HTTP baseado em **promessa** para node.js e o navegador.

É isomórfico - pode ser executado no navegador e no nodejs com a mesma base de código.

No lado do servidor, ele usa o módulo http para node.js nativo, enquanto o cliente (navegador) usa o **XMLHttpRequests**.

#### Principais Funcionalidades

- XMLHttpRequests a partir do navegador (ajax);
- Requisições Http no node.js;
- Suporta a API Promise;
- Intercepta requisições e resposta;
- Cancelamento de requisições;
- Transformação de dados da requisição e resposta;
- Transformações automáticas para dados JSON;
- Suporte do lado do cliente para proteção contra XSRF

#### O que é promessa (Promise)

Quando o cliente faz uma **requisição** ao servidor, a **resposta** pode chegar como **positiva** ou **negativa**, enquanto isso o **estado** está em **pendente**.
