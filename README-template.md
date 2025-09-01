# Frontend Mentor - Social links profile solution

Esta é a minha solução para o desafio [Social Links Profile no Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Os desafios do Frontend Mentor ajudam a melhorar as habilidades de código construindo projetos realistas.

## Table of contents

- [Visão geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que aprendi](#o-que-aprendi)
  - [Próximos passos](#próximos-passos)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)

## Visão geral

### O desafio

Usuários devem ser capazes de:

- Ver os estados de hover e foco em todos os elementos interativos da página

### Screenshot

![](./screenshot.jpg)

### Links

- Solução URL: [Adicionar link aqui](https://your-solution-url.com)
- Live Site URL: [Adicionar link aqui](https://your-live-site-url.com)

## Meu processo

### Construído com

- HTML5 semântico
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### O que aprendi

Esse projeto me ajudou a reforçar conceitos básicos de CSS, principalmente na parte de **estados de interação** (hover/focus) e centralização de layout com Flexbox.

```css
button:hover,
button:focus {
  background-color: var(--clr-accent);
  color: white;
}
```

Também pratiquei o alinhamento central de elementos com Flexbox:

```css
.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```

### Próximos passos

- Aprimorar responsividade em telas grandes
- Trabalhar mais acessibilidade (uso de aria-labels nos links sociais)
- Testar uma versão do projeto apenas com Grid

### Recursos úteis

- [MDN Web Docs](https://developer.mozilla.org/pt-BR/) – Documentação essencial para revisar seletores e pseudo-classes
- [Frontend Mentor Solutions](https://www.frontendmentor.io/solutions) – Inspirar-se em outras soluções me ajudou a melhorar a estrutura do CSS

## Autor

- Frontend Mentor - [@seu-usuario](https://www.frontendmentor.io/profile/seu-usuario)
- GitHub - [@seu-usuario](https://github.com/seu-usuario)
