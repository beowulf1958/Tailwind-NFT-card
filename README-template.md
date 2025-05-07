# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot](./images/Screenshot%202025-05-07%20at%2015-21-44%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)



### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/nft-preview-card-using-tailwind-css-P860cmTj6j)
- Live Site URL: [Add live site URL here](https://tailwind-nft-preview-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- [TailwindCSS](https://tailwindcss.com/docs/installation/tailwind-cli) - CSS framework


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This is a re-do of the nft preview challenge using tailwind CSS. The original project had a complicated overlay using :before pseudo-eleemnt. After reviewing others solutions, I came up with this simplier solution.

```html
<div class="overlay absolute top-0 left-0 w-full h-full bg-myCyan-400 bg-[url(./images/icon-view.svg)] bg-no-repeat bg-center opacity-0 hover:opacity-50"></div>
```


### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
