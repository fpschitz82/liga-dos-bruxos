# Regras de Negócio - Liga dos Bruxos

## 1. Confirmação de Presença

- O jogador deve confirmar presença antes do jogo.
- Estados possíveis:
  - Confirmado
  - Não vai
  - Aguardando vaga
  - Não respondeu

- Caso o número máximo de jogadores seja atingido:
  - Os demais entram como "Aguardando vaga"

---

## 2. Formação de Times

- O sistema deve gerar automaticamente dois times equilibrados.
- O Administrador pode ajustar manualmente os times antes do início do jogo.

---

## 3. Controle de Pagamentos

- Modalidades:
  - Pagamento por jogo
  - Pagamento mensal

- O jogador só será considerado confirmado após validação do pagamento pelo Administrador.

---

## 4. Avaliação dos Jogadores

- Todos os jogadores participantes podem avaliar os demais.
- A regra de cálculo da nota será:
  - Remover a maior nota
  - Remover a menor nota
  - Calcular a média das restantes

---

## 5. Pontuação e Ranking

- Critérios de classificação:
  1. Pontos
  2. Número de vitórias
  3. Presença nos jogos
  4. Média das avaliações
  5. Ordem alfabética

---

## 6. Convocações

- O Administrador pode criar convocações específicas para:
  - Jogos externos
  - Campeonatos
  - Eventos

---

## 7. Campeonatos e Torneios

- Devem ser separados dos jogos semanais.
- Devem conter:
  - Tabela de jogos
  - Resultados
  - Estatísticas completas

---

## 8. Controle Administrativo

- O Administrador pode delegar funções para outros administradores:
  - Responsável financeiro
  - Responsável pelo jogo

---

## 9. Avaliação Interna vs Pública

- Notas dos jogadores:
  - Visíveis para todos

- Notas da administração:
  - Restritas aos administradores

---

---

## 10. Processamento Automático de Encerramento de Jogo

- Ao encerrar um jogo, o sistema deve executar automaticamente as seguintes ações:

1. Bloquear edição do jogo.
2. Calcular o resultado da partida.
3. Identificar jogadores vencedores, empatados e derrotados.
4. Atualizar pontuação individual:
   - Vitória: 3 pontos
   - Empate: 1 ponto
   - Derrota: 0 pontos
5. Registrar presença dos jogadores participantes.
6. Atualizar estatísticas individuais:
   - Gols
   - Assistências
7. Atualizar ranking geral automaticamente.
8. Liberar sistema de avaliação para os participantes.

- O sistema deve permitir edição dos dados do jogo apenas antes do encerramento.
- Após encerrado, somente administradores com permissão especial poderão reabrir o jogo.