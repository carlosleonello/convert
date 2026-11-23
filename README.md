# Convert

Conversor de moedas que transforma valores em dólar americano, euro e libra esterlina em reais.

Projeto educacional desenvolvido a partir de uma atividade da [Rocketseat](https://www.rocketseat.com.br/), com foco na prática de JavaScript e manipulação do DOM.

## Funcionalidades

- Conversão de USD, EUR e GBP para BRL.
- Exibição da cotação utilizada e do valor convertido.
- Formatação de valores no padrão brasileiro.
- Remoção automática de caracteres que não sejam dígitos no campo de valor.
- Atualização do resultado na página, sem recarregamento.

## Tecnologias

- **HTML** — estrutura da página e do formulário.
- **CSS** — estilização da interface.
- **JavaScript** — eventos, cálculos e atualização dos elementos.

## Conceitos praticados

- Seleção e manipulação de elementos do DOM.
- Eventos `input` e `submit`.
- Controle do envio do formulário com `preventDefault()`.
- Estrutura condicional `switch`.
- Funções, parâmetros e retorno de valores.
- Expressões regulares e uso de `replace()`.
- Formatação monetária com `toLocaleString()`.
- Manipulação de classes CSS com `classList`.
- Tratamento de erros com `try...catch`.

## Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/carlosleonello/convert.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd convert
   ```

3. Abra o arquivo `index.html` no navegador.

Você também pode abrir a pasta no VS Code e utilizar a extensão **Live Server**. O projeto dispensa instalação de dependências e etapa de build.

## Como usar

1. Informe o valor inteiro que deseja converter.
2. Selecione a moeda de origem.
3. Clique em **Converter em reais**.
4. Confira a cotação utilizada e o resultado.

Por exemplo, ao informar **100** e selecionar **Dólar Americano**, o resultado será **600,00 reais**, considerando a cotação fixa definida no código.

## Cotações utilizadas

As cotações são valores fixos definidos no arquivo `script.js`, para fins de aprendizado.

| Moeda de origem | Código | Valor de 1 unidade em reais |
| --- | --- | --- |
| Dólar americano | USD | R$ 6,00 |
| Euro | EUR | R$ 6,52 |
| Libra esterlina | GBP | R$ 7,80 |

**Não há consulta a uma API de câmbio nem atualização automática das cotações.**

Na implementação atual, o campo de entrada aceita somente dígitos de `0` a `9`. Separadores decimais e sinais são removidos: por exemplo, `12,50` passa a ser `1250`.

## Estrutura do projeto

| Caminho | Conteúdo |
| --- | --- |
| `index.html` | Estrutura da página e formulário de conversão |
| `styles.css` | Estilos da interface |
| `script.js` | Eventos, lógica de conversão e formatação |
| `img/` | Imagens e ícones da interface |

## Créditos

Projeto desenvolvido por [Carlos Leonello](https://github.com/carlosleonello) durante os estudos na [Rocketseat](https://www.rocketseat.com.br/).

Os créditos pela proposta e pelo material didático do projeto são da Rocketseat.
