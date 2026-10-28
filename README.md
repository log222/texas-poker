# Texas Poker 🎰

Jogo de cassino multiplayer 3D para Android e iOS, desenvolvido por inteiro por mim: cliente, servidor, loja e infraestrutura.

> Este repositório é uma vitrine do projeto. O código-fonte é proprietário e não está publicado aqui.

## O que o jogo tem

- Poker Texas Hold'em com mesas de 6 níveis de aposta
- Blackjack em grupo (até 5 jogadores na mesma mesa) e vídeo poker
- Torneios Sit & Go e agendados, ranking, missões e passe de níveis
- Coleção de avatares, molduras e versos de carta
- Loja web com pagamento real (Pix e cartão, via Mercado Pago)

## Stack

| Camada | Tecnologia |
| --- | --- |
| Cliente | Unity 6 (C#), arte e interface geradas por código |
| Servidor | Nakama + TypeScript, servidor autoritativo |
| Loja | Node.js, Express, SQLite |
| Infra | Docker, PostgreSQL, Caddy (HTTPS automático) |
| Testes | Vitest e testes e2e contra o servidor real |

## Destaques técnicos

- **Servidor autoritativo:** todas as regras e o dinheiro ficam no servidor, o cliente só exibe.
- **Pagamentos seguros:** entrega de fichas idempotente, confirmada na API do Mercado Pago (status, moeda e valor).
- **Segurança:** 3 auditorias, com testes de regressão automatizados para cada falha corrigida.
- **Produção:** deploy em Docker com backup diário, limites de requisição por IP e HTTPS.
- **Qualidade:** mais de 170 testes unitários e suítes e2e que apagam as contas de teste no fim.

## Contato

Francisco Brazao Neto, Uberlândia, MG.
LinkedIn: https://www.linkedin.com/in/francisco-brazao-neto-97946327a/
