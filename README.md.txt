# 🔫🎒 Desafio Código da Ilha – Edição Free Fire  
Sistema de Mochila Virtual em C  

Bem-vindo ao **Desafio Código da Ilha – Edição Free Fire**, um projeto desenvolvido para treinar habilidades essenciais em programação com a linguagem **C**, passando por três níveis de dificuldade: **Novato**, **Aventureiro** e **Mestre**.

Este sistema simula uma **mochila virtual de sobrevivência**, permitindo ao jogador gerenciar itens enquanto tenta escapar de uma ilha misteriosa.

---

# 🏝️ Funcionalidades por Nível

---

## 🥉 Nível Novato – Inventário Básico
O jogador pode:

- ➕ Adicionar itens (nome, tipo, quantidade)  
- ➖ Remover itens pelo nome  
- 📋 Listar todos os itens cadastrados  

### Conceitos Utilizados
- `struct`  
- Vetor estático com tamanho máximo de 10 itens  
- Menu interativo com `switch` + `do-while`  
- Entrada e saída usando `scanf` e `printf`  

---

## 🥈 Nível Aventureiro – Inventário com Busca
Além das funções do nível Novato, agora é possível:

- 🔍 Buscar um item pelo nome usando **busca sequencial**

### Conceitos Adicionados
- Comparação de strings com `strcmp`  
- Busca sequencial  
- Controle com flag para item encontrado  

---

## 🥇 Nível Mestre – Ordenação e Busca Binária
A mochila evolui com novos recursos:

- ⭐ Adição do campo **prioridade** (1 a 5)  
- 🔄 Ordenação por:
  - Nome  
  - Tipo  
  - Prioridade  
- 🚀 Busca binária por nome  
- 📊 Contador de comparações da ordenação  
- Validação obrigatória: lista deve estar ordenada por nome para usar busca binária  

### Conceitos Avançados
- `enum` para critérios de ordenação  
- Insertion Sort  
- Busca Binária  
- Booleanos (`bool`)  
- Análise de desempenho  

---

# 📦 Estrutura do Projeto

