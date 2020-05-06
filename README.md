# Spookyportfolio

This is a responsive html website.

# Objectives

- Build on your knowledge of HTML & CSS
- Use flexbox and grid techniques layout pages.
- Implement, from scratch, a given design
- Understand HTML/CSS Layout
- Be able to place elements on a page where you want them.

# Includes

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [FLEXBOX](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [GRID](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)

# Featured Code

## CSS Grid

```JSX
main {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    grid-column-gap: 2rem;
  }

  .grid-left {
    grid-column-start: 1;
    grid-column-end: 4;
    height: 98vh;
  }

  .grid-right {
    grid-column-start: 4;
    grid-column-end: 7;
    height: 98vh;
  }

  .grid-mid-left {
    grid-column-start: 1;
    grid-column-end: 3;
    height: 98vh;
  }

  .grid-mid {
    grid-column-start: 3;
    grid-column-end: 5;
    height: 98vh;
  }

  .grid-mid-right {
    grid-column-start: 5;
    grid-column-end: 7;
    height: 98vh;
  }

  .grid-full {
    grid-column-start: 1;
    grid-column-end: 7;
    height: 98vh;
  }
```

# Live Site

- [LIVE SITE](https://spookyportfolio-sam.netlify.app/)
