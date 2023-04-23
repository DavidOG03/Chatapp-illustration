# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshots

![chatapp illustration screenshot](https://user-images.githubusercontent.com/107545464/233866569-31df1338-b052-4de0-8a46-e4befcdc53de.png)
![chatapp illustration screenshot desktop](https://user-images.githubusercontent.com/107545464/233866662-a7637c86-b159-43f9-b8c7-fe3a53055a96.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [click here](https://chatapp-illustration-david-og.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass/Scss
- BEM

### What I learned

To see how you can add code snippets, see below:

```html
 <fieldset class="choice">
                       
                            <label for="minutes" class="radio">
                                <input type="radio" id="minutes" name="minutes/hour">
                                
                                <p>30 minute walk</p>
                                <strong>$29</strong>
                            </label>
                           
                    
                        
                            <label for="hour" class="radio">
                                <input type="radio" id="hour" name="minutes/hour">
                                <p>1 hour walk</p>
                            <strong>$49</strong>
                            </label>
                           
                        
                    </fieldset>
```
```css
 input[type="radio"] {
                            appearance: none;
                            background-color: transparent;
                            margin: 0;
                            font: inherit;
                            color: currentColor;
                            width: 12px;
                            height: 12px;
                            border: 0.15em solid $Very-Light-Magenta;
                            border-radius: 50%;
                            display: grid;
                            place-content: center;
                            cursor: pointer;
                        }

                        input[type="radio"]::before {
                            content: "";
                            width: 8px;
                            height: 8px;
                            border-radius: 50%;
                            transform: scale(0);
                            transition: 120ms transform ease-in-out;
                            background-color: $Dark-Grayish-Violet;
                          }
                          
                          input[type="radio"]:checked::before {
                            transform: scale(1);
                          }
}
```

### Continued development

I will continue to develop beautiful inputs customization 

## Author

- Frontend Mentor - [@DavidOG03](https://www.frontendmentor.io/profile/DavidOG03)
- Twitter - [@David Ogungbemi](https://www.twitter.com/Deiveed03)
