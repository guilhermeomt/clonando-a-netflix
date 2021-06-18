# 🏁 Dia 03 -  Maratona "Clonando a Netflix com HTML, CSS e GitHub"
##### Data: 16/06/2021

##### [Clique aqui para ver o dia anterior](./day02.md)
##### [Clique aqui para ver o dia seguinte](./day04.md)

## Tópicos abordados
- CSS
- Metodologia BEM (Block Element Modifier)

## Aprendizados do dia
- Resumo de regras da metodologia BEM:
    - Block (Bloco)
      - É um componente em si, ou seja, Blocks são independentes, reutilizáveis e possuem significado próprio.
      - Exemplos: `.navbar`, `.product-card`
    - Element (Elemento)
        - São como partes (subdivisões) de um Block e não possuem significado quando estão sozinhos.
        - Elements seguem a seguinte estrutura de nomeação: Block + __ + Element.  
        - Exemplos: `.card__description`, `.form__button`
    - Modifier (Modificador)
        - Utilizado para alterar o estilo, comportamento ou estado de um Block ou Element.
        -  Para criar um modifier, basta seguir essa regra de nomeação: Block/Element + -- + Modifier
        - Exemplos: `.button--big`, `.photo__img--rounded`
- A propriedade `object-fit` do CSS permite controlar o preenchimento de tags `img` (imagens) dentro do espaço disponibilizado pelo seu container. Para mais informações, [clique aqui](https://developer.mozilla.org/pt-BR/docs/Web/CSS/object-fit) (Página do `object-fit` na MDN Web Docs)

## Desafio Prático #3

<details>
<summary>Instruções do desafio</summary>

### 1. Analise o componente de Playlists

Analise bem ele, veja que existe 2 variações de tamanho...

### 2. Agora crie os componentes

Já pode por a mão no código e criar a estilização dos componentes.

Não se esqueça que no conteúdo da Maratona de hoje o Daniel também criou o componente "Filme" da Netflix  - estude o conteúdo ;)

Crie os componentes usando a metodologia **BEM CSS** (aula 1 do dia de hoje).

### 3. Crie a página Playlists

Agora você já pode montar  página que lista todas as Playlists e também tem componentes que você criou no dia de ontem. O Design da página está no Figma.

Você pode usar suas playlits e conteúdos que mais gosta :D seja criativo no seu App!
Coloque as instruções aqui
</details>

### Minhas observações

Foi implementado os componentes aproveitando-se das regras de nomenclatura de classes da metodologia BEM. Assim que todos componentes necessários foram criados e estilizados, foi possível construir a página inicial. O resultado final da interface pode ser conferido [clicando aqui](https://guilhermeomt.github.io/music-player-app/). Caso queira ver o repositório referente a este desafio, [clique aqui](https://github.com/guilhermeomt/music-player-app).