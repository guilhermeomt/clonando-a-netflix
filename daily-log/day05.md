# 🏁 Dia 05 -  Maratona "Clonando a Netflix com HTML, CSS e GitHub"
##### Data: 18/06/2021

##### [Clique aqui para ver o dia anterior](./day04.md)
##### [Clique aqui para ver o dia seguinte](./day06.md) 

## Tópicos abordados
- CSS
  - Grid Layout
  - Transições e Animações

## Aprendizados do dia
- Características do CSS Grid Layout:
  - O CSS Grid Layout (ou simplesmente CSS Grid) oferece um sistema de construção de layout baseado em grid, ou seja, permite trabalhar em duas dimensões: linhas e colunas. 
  - Para tornar um elemento em um grid container basta atribuí-lo o par de propriedade e valor `display: grid`. 
  - A propriedade `grid-template-columns` permite estabelecer o número de colunas que . Por exemplo, `grid-template-columns: 50px 50px 50px` cria 3 colunas de 50px de comprimento cada. O mesmo valeria para `grid-template-rows`, só que, neste caso, para as linhas.
  - A propriedade `grid-gap` permite definir um espaçamento entre os elementos-filhos de um grid container
- Para aplicar um efeito de transição em determinadas mudanças de propriedades (como, por exemplo, a mudança do `background-color` em um hover), usa-se a propriedade `transition`. Nela passamos como valor a propriedade que deseja-se adicionar a transição e a duração desta transição. Exemplo: `transition: background-color 0.3s` 
- Para criar animações no CSS, utiliza-se a *at rule* `@keyframes`, sendo necessário especificar os pontos de animação (keyframes) para que seja criada uma sequência de animação. [Mais informações aqui](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Animations/Using_CSS_animations#definindo_a_sequ%C3%AAncia_de_anima%C3%A7%C3%A3o_usando_keyframes) (Página sobre animações CSS da MDN Web Docs).

## Desafio Prático #5

<details>
<summary>Instruções do desafio</summary>

### Passo 1

Analise a interface, os componentes, seções...

### Passo 2

Inicie um novo projeto com o git Git e crie um repositório remoto no GitHub.

### Passo 2

Mão na massa! Crie os componentes que identifica...

### Passo 3

Construa a página no arquivo index.html , inserindo os conteúdos (textos, imagens...)

<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fd21357c8-84b8-431f-b896-ce324269ed04%2FScreen_Shot_2021-06-18_at_8.37.12_PM.png?table=block&id=f0c13332-1f02-4f9f-8140-e5da5c7476b1&spaceId=438dc476-1641-4f49-b41f-31fdb65996b8&width=3070&userId=3c80e409-2dcb-4846-9a14-b043cc70da31&cache=v2" />

### Pass 4 -  EXTRA (opcional)

Você também pode criar a página de descrição de um projeto do portfolio.

<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F89a1b9a0-357e-49de-ad63-09509190a1b5%2FScreen_Shot_2021-06-18_at_8.37.30_PM.png?table=block&id=eab77fe5-606a-4247-b1c7-418a715d6f7b&spaceId=438dc476-1641-4f49-b41f-31fdb65996b8&width=470&userId=3c80e409-2dcb-4846-9a14-b043cc70da31&cache=v2" />

</details>

### Minhas observações

Basicamente foi construída uma página de portfólio pessoal com base no design que foi entregue. Na minha opinião, o resultado ficou muito bom para uma página web simples de HTML e CSS. Aliás, pretendo utilizá-la como meu site de portfólio. [Clique aqui](https://guilhermeomt.github.io/portfolio-page/) para acessar a página desenvolvida ou [aqui](https://github.com/guilhermeomt/portfolio-page) para ver o repositório com o código fonte.