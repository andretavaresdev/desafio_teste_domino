# Dominó

## Especificação do desafio

Partida de dominó para dois jogadores com conjunto duplo-seis (28 peças). Cada participante recebe sete peças e o restante fica no monte. As jogadas devem combinar com as pontas da mesa. O programa trata início da partida, compras, passes, batida e partida trancada.

## Funcionamento dos casos de teste

Os testes são escritos em JavaScript e executados com Jest. Cada teste verifica o resultado esperado de uma operação. Os casos também cobrem erros de entrada e situações nos limites das regras.

| Arquivo | Verificação |
|---|---|
| `tests/peca.test.js` | Criação e validação das peças. |
| `tests/baralho.test.js` | Conjunto de peças e distribuição das mãos. |
| `tests/partida.test.js` | Início, vez dos jogadores, jogadas válidas e inválidas, compra, passe e fim da partida. |
| `tests/personalizacao.test.js` | Verificações adicionais de limites e consistência. |

## Como executar

```bash
npm ci
npm test
```

## Colaborador

- André Tavares (RA: 24066498-2)
