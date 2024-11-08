# Four Card Feature Section

This project is a solution to the [Frontend Mentor Four Card Feature Section challenge](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). It involves creating a responsive layout that displays four feature cards in a diamond formation on desktop screens and a column layout on mobile screens.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![Desktop Design](./images/desktop-design.jpg)
![Mobile Design](./images/mobile-design.jpg)

### Links

- Solution URL: [Add your solution URL here](https://your-solution-url.com)
- Live Site URL: [Add your live site URL here](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

In this project, I learned how to use CSS Grid to create complex layouts, including a diamond formation for the feature cards on desktop screens. I also practiced using media queries to create a responsive design that adapts to different screen sizes.

```css
/* Example of CSS Grid for diamond formation */
.card-section {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(4, 1fr);
  gap: 2rem;
}

.supervisor-card {
  grid-column: 2 / 3;
  grid-row: 2 / 4;
}

.team-builder-card {
  grid-column: 3 / 4;
  grid-row: 1 / 3;
}

.karma-card {
  grid-column: 3 / 4;
  grid-row: 3 / 5;
}

.calculator-card {
  grid-column: 4 / 5;
  grid-row: 2 / 4;
}

Sure! Here is a sample `README.md` file for your 4 card preview project:

```markdown
# Four Card Feature Section

This project is a solution to the [Frontend Mentor Four Card Feature Section challenge](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). It involves creating a responsive layout that displays four feature cards in a diamond formation on desktop screens and a column layout on mobile screens.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![Desktop Design](./images/desktop-design.jpg)
![Mobile Design](./images/mobile-design.jpg)

### Links

- Solution URL: [Add your solution URL here](https://your-solution-url.com)
- Live Site URL: [Add your live site URL here](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

In this project, I learned how to use CSS Grid to create complex layouts, including a diamond formation for the feature cards on desktop screens. I also practiced using media queries to create a responsive design that adapts to different screen sizes.

```css
/* Example of CSS Grid for diamond formation */
.card-section {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(4, 1fr);
  gap: 2rem;
}

.supervisor-card {
  grid-column: 2 / 3;
  grid-row: 2 / 4;
}

.team-builder-card {
  grid-column: 3 / 4;
  grid-row: 1 / 3;
}

.karma-card {
  grid-column: 3 / 4;
  grid-row: 3 / 5;
}

.calculator-card {
  grid-column: 4 / 5;
  grid-row: 2 / 4;
}
```

### Continued Development

In future projects, I plan to continue improving my skills in CSS Grid and Flexbox to create more complex and responsive layouts. I also want to explore using CSS frameworks like Tailwind CSS to speed up my development process.


