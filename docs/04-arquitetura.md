# Arquitetura do Sistema - Liga dos Bruxos

## 1. Visão Geral

O aplicativo será desenvolvido utilizando React Native com Expo, permitindo execução em dispositivos Android.

A arquitetura seguirá o modelo de separação por camadas:

- Interface (Frontend)
- Lógica de Negócio
- Armazenamento de Dados

---

## 2. Tecnologias Utilizadas

- React Native
- Expo
- JavaScript
- Firebase (armazenamento e autenticação)
- Git e GitHub para versionamento

---

## 3. Estrutura de Pastas

/app
  /components
  /screens
  /services
  /utils

/docs
/assets

---

## 4. Modelo de Dados (Visão Inicial)

Principais entidades:

- Usuário
  - id
  - nome
  - email
  - tipo (Administrador ou Jogador)
  - pontuação
  - presença
  - média de avaliação

- Jogo
  - id
  - data
  - local
  - status (Aberto ou Encerrado)
  - placar
  - lista de participantes

- Estatísticas
  - gols
  - assistências
  - vitórias
  - derrotas
  - empates

---

## 5. Processamento de Encerramento

O encerramento de jogo executará regras automatizadas de:

- Cálculo de resultado
- Distribuição de pontos
- Atualização de ranking
- Liberação de avaliações

---

## 6. Escalabilidade Futura

O sistema será projetado para permitir:

- Múltiplas ligas
- Integração entre ligas por região
- Torneios anuais organizados pela plataforma