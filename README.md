# Seminário de APIs — Engenharia de Software II

**Tema sorteado:** APIs (REST, SOAP)
**Título da apresentação:** *APIs — Como pedir comida para um servidor sem invadir a cozinha*

A aula usa a analogia de um restaurante (cliente, cardápio, atendimento, cozinha) para explicar que uma API é um **contrato**, e fecha com uma atividade desplugada, o **Bingo das APIs**.



| # | Entregável do enunciado | Onde está |
| --- | --- | --- |
| 1 | Nome e matrícula dos integrantes | Seção [Integrantes](#integrantes) |
| 2 | Tema do seminário | APIs (REST, SOAP) — este README e o plano de aula |
| 3 | Material da apresentação | [`seminario2.pptx`](seminario2.pptx) e [`seminario2.pdf`](seminario2.pdf) (63 slides) |
| 4 | Plano de aula | [`Plano de Aula - Seminario de APIs.docx.pdf`](Plano%20de%20Aula%20-%20Seminario%20de%20APIs.docx.pdf) |
| 5 | Atividade desplugada e como executá-la | [`bingo-das-apis_3.pdf`](bingo-das-apis_3.pdf) e a seção [Bingo das APIs](#atividade-desplugada-bingo-das-apis) |
| 6 | Gabarito da atividade | Respostas no rodapé de cada papeizinho e folha do apresentador, ambos no [`bingo-das-apis_3.pdf`](bingo-das-apis_3.pdf) |
| 7 | Como a atividade é avaliada | Seção [Avaliação da atividade](#avaliação-da-atividade) |


## O que a apresentação cobre

- **História:** EDSAC (1949), RPC (1984), Web (1989–1991), XML-RPC, SOAP e REST (1998–2000), WebSocket, GraphQL, gRPC e OpenAPI (2011–2015).
- **Conceito:** significado de API, o ABC (abstração, baixo acoplamento, contrato), tipos de API e endpoints.
- **HTTP:** requisição e resposta, métodos e idempotência, status, JSON e XML, HTTPS e tokens, exemplos com GitHub e ViaCEP.
- **Tecnologias:** REST, SOAP, gRPC, GraphQL, WebSocket e Webhook, e quando usar polling, WebSocket ou Webhook.
- **Contrato e engenharia:** REST × GraphQL, OpenAPI e Swagger UI, schema, versionamento, segurança (BOLA), timeout, retry, `Idempotency-Key`, fluxo de pagamento com Stripe e arquiteturas com gateway e BFF.

## Atividade desplugada: Bingo das APIs

Os colegas ouvem uma definição, descobrem o termo e o marcam na cartela. O objetivo é revisar os conceitos da aula sem computador, só com papel e caneta ou lápis.

**Material** (tudo em [`bingo-das-apis_3.pdf`](bingo-das-apis_3.pdf)):

- 20 cartelas numeradas (01 a 20), grade 5×5 com colunas B-I-N-G-O, 24 termos diferentes por cartela e a casa central "LIVRE".
- 53 papeizinhos de definição para recortar e sortear, cada um com a resposta no rodapé, mais 2 cartas especiais "O servidor caiu! Todo mundo desmarca um termo".
- Folha do apresentador, com a lista dos 53 termos e os termos de cada cartela, para conferir se um BINGO é válido.

**Como executar:**

1. Cada colega recebe uma cartela e escreve o nome no topo.
2. O apresentador sorteia um papeizinho e lê só a definição, sem dizer a resposta.
3. Quem tem o termo na cartela o marca. O apresentador marca o termo na folha dele.
4. Se sair uma carta especial, todos desmarcam um termo (nao foi utilizado na apresentacao).
5. Quem completa uma linha, coluna ou diagonal grita **BINGO** e explica um dos termos marcados. Errou = `400 Bad Request`.
6. Os 3 primeiros a completar um BINGO válido ganham um prêmio.

**Termos por assunto:**

| Assunto | Termos |
| --- | --- |
| História e conceito | API, Contrato, Cliente, Implementação, EDSAC, RPC |
| Tecnologias e canais | REST, SOAP, GraphQL, gRPC, WebSocket, Webhook, Polling, HTTP |
| Métodos HTTP | GET, POST, PUT, PATCH, DELETE, Idempotência |
| Partes e formatos | Body, Query, Authorization, Content-Type, Location, JSON, XML |
| Status HTTP | 200 OK, 201 Created, 204 No Content, 400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 422 Unprocessable, 429 Too Many, 500 Server Error |
| Contrato e boas práticas | Stateless, Cache, Schema, OpenAPI, Swagger UI, Mock, Versionamento, Timeout, Retry, Idempotency-Key, BOLA, HTTPS, Gateway, BFF, DevTools, ViaCEP |

## Avaliação da atividade

O próprio grupo corrige o bingo durante o jogo, sem recolher cartelas depois:

- **Durante o jogo:** o apresentador marca na folha dele cada termo sorteado. Quando alguém grita BINGO, ele lê os termos da linha, coluna ou diagonal e confere se todos já foram sorteados e se nenhum foi desmarcado por uma carta especial.
- **Compreensão:** quem completa o BINGO precisa explicar um dos termos marcados. Se o BINGO estiver errado, vale o aviso `400 Bad Request` da cartela.
- **Resultado:** os 3 primeiros a completar um BINGO válido ganham um prêmio.
- **Gabarito:** a resposta de cada definição está no rodapé do papeizinho, e a folha do apresentador lista todos os termos e as cartelas.

## Bibliografia

A bibliografia completa está no [plano de aula](Plano%20de%20Aula%20-%20Seminario%20de%20APIs.docx.pdf). As principais referências são a tese de Roy Fielding sobre REST (2000), o artigo de Birrell e Nelson sobre RPC (1984), as RFCs 9110 (HTTP) e 6455 (WebSocket), as especificações OpenAPI e GraphQL e o OWASP API Security Top 10.
