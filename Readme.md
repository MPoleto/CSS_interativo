# 🤿 Site interativo com CSS

Este projeto, desenvolvido para praticar CSS, é um site que escolhi como tema uma operadora de mergulhos devido ao efeito criado pela animação em CSS, que lembrar o movimento de água. 
<br/>

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Site interativo com CSS**
| :label: Tecnologias | HTML e CSS
| :rocket: URL         | https://mpoleto.github.io/CSS_interativo/

<br/><br/>

![](./assets/img/header_readme.gif#vitrinedev)

## Detalhes do projeto

- O projeto inicial foi feito seguindo as orientações da Gabriela Pinheiro em um curso na plataforma da DIO.
- Atualizei o projeto para aplicar o que foi ensinado nas formações *A partir do zero: Iniciante em programação* e *A partir do zero: HTML e CSS para projetos web* na plataforma de ensino da Alura.
  - Visualmente não houve muitas alterações da versão anterior, pois a intenção foi de melhorar os códigos de HTML e CSS.

### HTML
- Uso de tags semânticas
- Nomenclatura das classes seguindo o padrão BEM (`Block Element Modifier`)
- `input` do `tipo checkbox` para poder aplicar o efeito de abrir/fechar no menu-hamburguer

### CSS
- Arquivo de reset CSS
- Separação do CSS em vários arquivos
- Página responsiva com aplicação de `@media` queries, seguindo a abordagem mobile-first
- Uso preferencial de unidades de medida relativa (`em`, `rem`, `%`, `vw`, `vh`)
- Uso de variáveis
- `Flexbox`
- `transition` para suaviar as animações aplicadas
- O header foi estilizado usando `@keyframes`, para fazer a animação do background
- Menu-hamburguer quando aberto:
  - ocupa toda a tela e exibe o menu (`z-index`, `opacity`, `visibility`)
  - o desenho do menu-hamburguer transforma-se em um `X` usando a propriedade `transform`
- Pseudo-classes:
  - `:root` para declarar as variáveis
  - Para criar os efeitos nos links foi usado `:active` para mobile e `:hover` para telas maiores
  - `:nth-child()` e `:checked` para criar e animar o menu-hamburguer
- Cada seção do conteúdo principal da página possui um link, que foi estilizado no formato de um card com uma imagem de fundo.
  - Para adicionar efeito aos cards foi usado as pseudo-classes e o pseudo-elemento `::before`

