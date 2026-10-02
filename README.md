# ♡ Teste de Caixa Branca – Sistema de Pedidos

## ୨୧ Sobre o projeto

Este projeto foi desenvolvido como parte da atividade acadêmica **Teste de Caixa Branca – Sistema de Pedidos**, utilizando HTML, CSS e JavaScript.

O sistema simula uma loja virtual na qual o usuário pode selecionar um produto, informar a quantidade desejada, aplicar cupons de desconto e escolher a modalidade de frete.

Ao realizar o cálculo, são apresentados:

- Subtotal do pedido;
- Desconto aplicado;
- Valor do frete;
- Total da compra;
- Mensagem de classificação do pedido.

## 🎀 Objetivo

O objetivo da atividade foi analisar a estrutura interna do código por meio de técnicas de **Teste de Caixa Branca**, identificando falhas na lógica de execução e realizando as devidas correções.

Durante a análise, foram utilizadas as seguintes técnicas:

- Análise de valores-limite;
- Cobertura de decisões;
- Análise de caminhos;
- Rastreamento de variáveis;
- Análise de condições.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## 📁 Estrutura do projeto

```text
Sistema-de-Pedidos/
│
├── index.html
├── style.css
├── script.js
├── scriptnovo.js
└── README.md
```

## 💻 Funcionalidades

O sistema apresenta as seguintes funcionalidades:

- Seleção de produtos;
- Controle de estoque;
- Validação da quantidade informada;
- Aplicação de cupons de desconto;
- Cálculo de descontos por quantidade;
- Desconto para pedidos de alto valor;
- Cálculo de frete normal e expresso;
- Opção de retirada;
- Classificação do pedido;
- Exibição dos valores calculados na tela.

## 🎟️ Cupons de desconto

| Cupom | Condição | Desconto |
|---|---|---:|
| `SENAI10` | Aplicável sobre o subtotal | 10% |
| `SENAI20` | Subtotal igual ou superior a R$ 1.000,00 | 20% |

## 🚚 Modalidades de frete

O sistema disponibiliza três opções de entrega:

| Modalidade | Valor |
|---|---:|
| Retirada | R$ 0,00 |
| Expresso | R$ 60,00 |
| Normal | R$ 30,00 |
| Normal com subtotal a partir de R$ 500,00 | Grátis |

## 📦 Produtos disponíveis

| Produto | Preço | Estoque |
|---|---:|---:|
| Notebook | R$ 3.000,00 | 5 unidades |
| Mouse | R$ 80,00 | 20 unidades |
| Teclado | R$ 150,00 | 10 unidades |

## 🧪 Testes realizados

Durante a atividade, foram realizados testes com diferentes entradas e caminhos de execução para analisar o comportamento do sistema.

A análise foi conduzida inicialmente no código original e, posteriormente, após a implementação das correções.

Entre os cenários avaliados, destacam-se:

- Quantidade igual a zero;
- Compra da quantidade máxima disponível em estoque;
- Quantidades nos limites de aplicação de descontos;
- Pedido exatamente no limite de alto valor;
- Utilização dos diferentes cupons;
- Seleção das modalidades de frete;
- Verificação das condições de classificação do pedido.

## 🔧 Versão corrigida

O arquivo `scriptnovo.js` contém a versão corrigida do código, desenvolvida após a identificação dos problemas encontrados durante os testes.

As alterações foram realizadas principalmente nas condições de validação, nos limites de estoque, nas regras de desconto e na classificação dos pedidos.

## ▶️ Como executar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Selecione um produto.
4. Informe a quantidade desejada.
5. Insira um cupom de desconto, caso queira.
6. Escolha a modalidade de frete.
7. Clique em **Calcular pedido** para visualizar o resultado.

## 📚 Informações acadêmicas

| Informação | Descrição |
|---|---|
| Atividade | Teste de Caixa Branca – Sistema de Pedidos |
| Curso | Técnico em Desenvolvimento de Sistemas |
| Turma | 3º ano B |
| Aluna | Alice ♡ |
| Data | 02/10/2026 |

---

## ♡ Autora

<p align="center">
  <strong>Made with love by Alice ♡</strong><br>
  <em>An academic project developed as part of the Technical Course in Systems Development.</em>
  <br><br>
  ୨୧
</p>
