# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/HaiyingLiao/Recipe-Page](https://github.com/HaiyingLiao/Recipe-Page)
- Live Site URL: [https://recipe-page-tau-nine.vercel.app/](https://recipe-page-tau-nine.vercel.app/)

## My process

### Built with

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCss](https://tailwindcss.com/)
- Semantic HTML5 markup

### What I learned

Learnt how to use multiple fonts in nextJS 14.

```js
//make a separate font.ts file
import { Outfit, Young_Serif } from 'next/font/google';

export const outfit = Outfit({
  subsets: ['latin'],
  weight: ['400', '600', '700'],
});

export const young_serif = Young_Serif({ subsets: ['latin'], weight: ['400'] });
```

```js
// use fonts in any pages
import { young_serif } from './fonts';

export default function Home() {
  return <h1 className={young_serif.className}>Content</h1>;
}
```

### Useful resources

- [Stackoverflow answer](https://stackoverflow.com/questions/75674866/adding-favicon-to-nextjs-app-router-application) - The most voted answer here helped me solve how to change favicon in next14.
- [NextJs Doc](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) - This explained how to use multiuple fonts in next14. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Haiying Liao](https://haiying-liao.vercel.app/)
- Frontend Mentor - [@HaiyingLiao](https://www.frontendmentor.io/profile/HaiyingLiao)
- X - [@Haiyig_Liao](https://x.com/Haiying_Liao)
