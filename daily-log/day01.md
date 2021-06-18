# 🏁 Dia 01 -  Maratona "Clonando a Netflix com HTML, CSS e GitHub"
##### Data: 14/06/2021

##### [Clique aqui para ver o dia seguinte](./day02.md)

## Tópicos abordados
- UI Design
- Figma
- Componentização
- HTML
- Git/GitHub

## Aprendizados do dia
- Atalhos do Figma 
    - Shift + scroll do mouse: Move-se horizontalmente na tela
    - Clicar no scroll do mouse ou pressionar espaço: Move-se livremente na tela
    - Ctrl + scroll do mouse: Zoom in/Zoom out
- Definição de ***Style Guide***: um **documento visual** (livro de regras) que **estabelece todos os padrões existentes numa determinada interface de usuário** como, a paleta de cores, a tipografia, os ícones e imagens, componentes etc.
- Vantagens do ***Style Guide***
    - Constrói uma identidade visual
    - Mantêm a consistência dos padrões da interface
    - Facilita o desenvolvimento como um todo, além de facilitar o trabalho em equipe
- Definição de **Componente**: é, normalmente, uma **coleção encapsulada de marcação (HTML), estilização (CSS) e lógica (JavaScript)**. São projetados para serem **reutilizáveis** ​​e para servir como os **blocos de construção** a partir dos quais seu aplicativo será criado.<h6>fonte: https://engineering.carsguide.com.au/front-end-component-design-principles-55c5963998c9 </h6>
- Vantagens da **Componentização**
    - Permite a reusabilidade do código
    - Colabora para a manutenção  e escalabilidade do código
    - Facilita a legibilidade do código
    - Padroniza o projeto
- Comumente nomeamos a página principal de **`index.html`**, para que seja roteada como a página do endereço raiz `/`.
- Apenas no primeiro push de commit, deve-se utilizar o comando `git push -u origin main`, para que associe a branch do repositório local com a branch main do repositório remoto. Nos próximos commits pode-se simplesmente utilizar `git push` 

## Desafio Prático #1

<details>
<summary>Instruções do desafio</summary>

 ### 1. Crie um projeto e inicie o versionamento local com o Git

Neste projeto você construirá a interface de um aplicativo de música (playlist) ao decorrer dos próximos dias.

Use a sua criatividade para criar o nome do projeto 😉

### 2. Implemente no projeto a estrutura de diretórios

A estrutura foi apresentada na aula 2 no conteúdo de hoje.

### 3. Adicione conteúdo no seu arquivo index.html

No arquivo index.html insira na tag `<title>` e no `<h1>` o nome do seu projeto.

### 4. Faça o primeiro commit

### 5. Crie um repositório remoto no GitHub

Crie um repositório público para que possa ser compartilhado com nossa equipe e colegas.

### 6. Conecte seu repositório local no remoto e faça um Git Push

Após isso o seu repositório estará na nuvem ☁️  !
</details>

### Minhas observações
Foi inicializado o [repositório do projeto de um aplicativo de música](https://github.com/guilhermeomt/music-player-app), adicionando-se os arquivos iniciais como o [`index.html`](https://github.com/guilhermeomt/music-player-app/blob/main/index.html) e o [`README.md`](https://github.com/guilhermeomt/music-player-app/blob/main/README.md) . O projeto contará com a seguinte estrutura de pastas e arquivos conforme solicitada: 
```
.
├── README.md
├── assets
│   ├── icons
│   └── images
├── index.html
└── styles
    ├── components
    └── pages
```

