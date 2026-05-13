# Convert Dollar

Aplicação web simples para converter valores de moedas estrangeiras para real brasileiro.

O projeto foi desenvolvido com HTML, CSS e JavaScript puro, sem dependências externas de build ou execução. A interface permite informar um valor, selecionar a moeda e visualizar o resultado formatado BRL.

## Funcionalidades

- Conversão de Dólar Americano (USD), Euro (EUR) e Libra Esterlina (GBP) para Real (BRL)
- Exibição da cotação usada no cálculo
- Resultado formatado no padrão brasileiro
- Validação do campo de valor para aceitar apenas números
- Interface simples e responsiva para uso no navegador

## Tecnologias

- HTML5
- CSS3
- JavaScript

## Como executar

Como este é um projeto estático, basta abrir o arquivo `index.html` no navegador.

### Opção 1

- Dê duplo clique no arquivo `index.html`

### Opção 2

- Abra a pasta do projeto no VS Code
- Use uma extensão como Live Server para iniciar um servidor local

## Estrutura do projeto

```text
convert-dollar/
├── img/
├── index.html
├── script.js
├── styles.css
└── README.md
```

## Lógica de conversão

As cotações estão definidas diretamente no arquivo `script.js`:

- USD = 5.01
- EUR = 5.77
- GBP = 6.67

O valor informado é multiplicado pela cotação da moeda selecionada, e o resultado é exibido no formato de moeda brasileira.

## Observações

- As cotações são fixas e estão codificadas no JavaScript
- O campo de valor atualmente aceita apenas números inteiros
- Não há integração com API de câmbio em tempo real

## Possíveis melhorias

- Permitir valores decimais
- Buscar cotações atualizadas em uma API
- Adicionar tratamento visual para erros de entrada
- Exibir mensagem inicial orientando o preenchimento do formulário

## Licença

Este projeto pode ser usado para fins de estudo e prática.