# Carrinho de Compras 🛒

## Simulação de carrinho de compras que calcula o preço total a ser pago

Depois de darmos uma passadinha pelo site da **Shópi**, vimos alguns itens interessantes.

### Objetivo:
Criar uma lista composta por vários **dicionários** (`dict`). Cada dicionário deve representar um item do carrinho de compras.

---

### Requisitos:
1. Cada dicionário deve conter, no mínimo, as seguintes chaves:
   - **`nome`**: Nome do item.
   - **`quantidade`**: Quantidade desejada do item (deve ter pelo menos **2 unidades**)
   - **`preco_unitario`**: Preço de cada unidade do item.

2. A lista final deve ser composta por pelo menos **3 itens diferentes**.

---

### Exemplo:
```python
carrinho = [
    {"nome": "Calça Bege", "quantidade": 3, "preco_unitario": 52.50},
    {"nome": "Chapéu de Marinheiro", "quantidade": 10, "preco_unitario": 42.10},
    {"nome": "Mochila de Capivara", "quantidade": 5, "preco_unitario": 120.00}
]
```

---

## Remover o Primeiro Item 🗑️

### O que aconteceu? 🤔

Durante nossa aventura de compras, percebemos que adicionamos o primeiro item **por engano**. Talvez tenha sido o entusiasmo de ver tantas promoções, mas agora é hora de corrigir isso e remover o item errado do nosso carrinho!

---

### Passos para Remover o Primeiro Item:

1. Use o método `pop(0)` para remover o item no índice 0 (o primeiro da lista).
2. Armazene o item removido em uma variável para verificarmos qual foi excluído.
3. Atualize o carrinho para refletir a mudança.

---

## Adicionar um Novo Item 🛍️

### O que aconteceu agora? 🤔

Depois de corrigir o engano e remover o item errado, lembramos que ainda precisamos adicionar um novo item ao carrinho — agora o item **certo**! Vamos garantir que nossa lista fique completa para finalizar a compra.

---

### Passos para Adicionar um Novo Item:

1. Use o método `append()` para adicionar um novo dicionário ao final da lista do carrinho.
2. Certifique-se de que o dicionário contenha as informações básicas do item:
   - **`nome`**: Nome do produto.
   - **`quantidade`**: Quantidade desejada.
   - **`preco_unitario`**: Preço de cada unidade do item.

---

## Checkout 🧾

Agora que já montamos nosso **carrinho de compras**, vamos calcular o **preço final** diretamente, usando variáveis para cada cálculo e arredondando os valores com `round`.

---
