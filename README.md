# Campeonato de Futebol

Projeto em dupla — CRUD no terminal com JavaScript e `@inquirer/prompts`.

- **Integrantes:** Luan Feitoza de Lima e Junior
- **Tema sorteado:** 14
- **Elemento escolhido:** Campeonato de futebol (times, jogadores e partidas)

## Funcionalidades

- **Times:** cadastrar, listar, atualizar e remover (cada time tem um `id`).
- **Jogadores:** cadastrar, listar, atualizar e remover, com `id`, posição (Goleiro, Zagueiro, Lateral, Volante, Meio-campista, Atacante) e time.
- **Partidas:** registrar, listar, atualizar placar e remover.
- **Pontuação:** classificação calculada automaticamente (vitória = 3 pontos, empate = 1, derrota = 0; desempate por saldo de gols e gols pró).

Os dados ficam apenas na memória: ao fechar o programa, tudo é apagado.

## Como executar

```bash
npm install
node crud.js
```
