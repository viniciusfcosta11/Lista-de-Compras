# 🛒 Lista de Compras

Já foi ao supermercado, esqueceu-se do que precisava de comprar e acabou por voltar para casa sem o ingrediente principal do jantar? O **Lista de Compras** nasceu exatamente para resolver esse problema!

Trata-se de uma aplicação *mobile* moderna, leve e extremamente intuitiva, desenvolvida para manter o seu dia a dia organizado e garantir que nunca mais deixa nada para trás.

---

## 🌟 O que torna esta aplicação especial?

A proposta do projeto é entregar uma experiência simples, limpa e direta ao ponto, focando no que realmente importa durante as suas compras:

- **Adição rápida e sem complicações:** Adicione qualquer produto à sua lista em poucos segundos, definindo o nome e a quantidade necessária.
- **Controlo total no carrinho:** Conforme vai colocando os produtos no carrinho físico, pode removê-los da lista digital com apenas um toque.
- **Feedback visual imediato:** O rodapé da aplicação atualiza-se em tempo real para mostrar exatamente quantos itens ainda faltam comprar.
- **Ecrã inteligente para lista vazia:** Quando a sua lista estiver totalmente limpa, o aplicativo exibe uma mensagem amigável a avisar que está tudo pronto.

---

## 🛠️ Tecnologias por trás do projeto

Para garantir um desempenho fluido, código limpo e facilidade de manutenção, o projeto foi construído com as melhores ferramentas do ecossistema *mobile*:

- **React Native:** Framework que permite criar aplicações nativas de alta performance.
- **Expo:** Facilita todo o fluxo de desenvolvimento, testes e execução em dispositivos reais.
- **TypeScript:** Garante segurança de tipos nos dados, prevenindo erros durante o desenvolvimento e tornando a estrutura do projeto muito mais sólida.

---

## 📂 Organização dos Componentes

O código foi pensado de forma modular, onde cada parte da interface tem a sua responsabilidade bem definida:

- **`App.tsx`**: O cérebro da aplicação, responsável por gerir o estado global da lista de compras (adicionar e remover itens).
- **`Cabecalho.tsx`**: O topo visual que identifica a aplicação de forma elegante.
- **`FormularioItem.tsx`**: O formulário onde o utilizador digita o nome e a quantidade do novo item.
- **`ListaCompras.tsx`**: Responsável por renderizar a lista otimizada (`FlatList`) com scroll suave.
- **`ItemCompra.tsx`**: O cartão individual de cada produto, com o nome, quantidade e o botão para apagar.

---

## 🚀 Como testar no seu telemóvel

Quer ver a aplicação a funcionar na prática? Siga estes passos simples:

### 1. Pré-requisitos
Asegure-se de que tem instalado na sua máquina:
- **Node.js** (versão `>= 20.19.4`).
- A aplicação **Expo Go** instalada no seu telemóvel (disponível gratuitamente na Play Store e App Store).

### 2. Passo a passo

1. **Abra o terminal na pasta do projeto e instale as dependências:**
   ```bash
   npm install
