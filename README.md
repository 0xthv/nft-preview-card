# nft-preview-card
Frontend challange

# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

### Screenshot

![](./screenshot.png)

### Links

- [My Solution](https://genuine-lily-5e558c.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- CSS variables
- Mobile-first workflow

### What I learned

How to use the pseudo class nth-child, different strategies on grid columns (fit-content, grid-column-start/end), revised relative/absolute positioning. 

```css
.card-price :last-child {
  grid-column-start: 10;
  grid-column-end: -1;
  color: var(--white);
}
```
```css
  grid-template-columns: fit-content(18%) 1fr;
```

### Continued development

The background image with the fixed color is not right as we're able to see the borders with different colors. Not entirely satisfied with this solution yet. 


### Useful resources

- [Example resource 1](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_opacity) - Example i've used to get the proper hover effect 

## Author

- Frontend Mentor - [0xthv](https://www.frontendmentor.io/profile/0xthv)
