# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

# Results Summary Component

This project contains HTML and CSS code for a results summary component. This component is designed to display a user's test results in a visually appealing and user-friendly manner.

## Table of Contents

- [Global Styles](#global-styles)
- [Mobile Styles](#mobile-styles)
- [Desktop Styles (1440px)](#desktop-styles-1440px)
- [HTML Structure](#html-structure)
- [Attribution](#attribution)

---

## Global Styles

```css
/* Global styles */

/* Set font family and size for the entire document */
body {
    font-family: 'Hanken Grotesk', sans-serif;
    font-size: 18px;
}

/* Set color for h4 and p elements */
h4, p {
    color: hsl(241, 100%, 89%);
}

/* Set color for elements with class 'big' */
.big {
    color: hsl(0, 0%, 100%);
}

/* Set color for h4 elements within .side-2 section */
.side-2 h4 {
    color: hsl(224, 30%, 27%);
}

/* Styles for score element */
.score {
    padding: 50px;
    width: 80px;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin: 0 auto;
    border-radius: 100%;
    background: linear-gradient(hsla(256, 72%, 46%, 1), hsla(241, 72%, 46%, 0));
}

/* Styles for elements with class 'big' */
.big {
    font-weight: bold;
    font-size: 60px;
}

/* Styles for .side-2 section */
.side-2 {
    padding: 20px;
    border-radius: 20px;
}

/* Styles for list elements */
.list {
    display: flex;
    flex-direction: column;
}

/* Styles for list1, list2, list3, list4 elements */
.list1, .list2, .list3, .list4 {
    display: flex;
    justify-content: space-around;
    background: hsla(0, 100%, 67%, 0.1);
    color: hsl(0, 100%, 67%);
    margin-bottom: 15px;
    padding: 10px 0;
    border-radius: 10px;
}

/* Styles for .list2 element */
.list2 {
    background: hsla(39, 100%, 56%, 0.1);
    color: hsl(39, 100%, 56%);
}

/* Styles for .list3 element */
.list3 {
    background: hsla(166, 100%, 37%, 0.1);
    color: hsl(166, 100%, 37%);
}

/* Styles for .list4 element */
.list4 {
    background: hsla(234, 85%, 45%, 0.1);
    color: hsl(234, 85%, 45%);
    border-style: none;
}

/* Styles for elements with class 'black' */
.black {
    font-weight: bold;
    color: hsl(224, 30%, 27%);
}

/* Styles for elements with class 'light' */
.light {
    font-weight: 400;
    color: grey;
}

/* Styles for buttons */
button {
    border-radius: 40px;
    font-size: 20px;
    padding: 20px;
    margin-top: 20px;
    font-weight: bold;
    background: hsl(224, 30%, 27%);
    color: hsl(0, 0%, 100%);
}

/* Hover styles for buttons */
button:hover {
    cursor: pointer;
    background: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    transition: 0.5s;
}

/* Styles for footer */
footer {
    margin: 20px;
    font-size: 50px;
}

/* Styles for attribution */
.attribution {
    font-size: 11px;
    text-align: center;
}

.attribution a {
    color: hsl(228, 45%, 44%);
}
```

## Mobile Styles

```css
/* Mobile styles */

/* Reset padding and margin for body */
body {
    padding: 0;
    margin: 0;
}

/* Styles for .side-1 section on mobile */
.side-1 {
    color: hsl(0, 0%, 100%);
    background: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    padding: 20px;
    border-radius: 0 0 20px 20px;
    margin: 0;
    text-align: center;
}
```

## Desktop Styles (1440px)

```css
/* Desktop styles (1440px) */

@media (min-width: 630px) {

    /* Flexbox styles for body */
    body {
        display: flex;
        flex-flow: column wrap;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
    }

    /* Styles for main section */
    main {
        display: flex;
        width: 600px;
        justify-content: center;
        border-radius: 20px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    /* Styles for .side-1 section on desktop */
    .side-1 {
        color: hsl(0, 0%, 100%);
        background: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
        padding: 20px;
        border-radius: 20px;
        width: 50%;
        text-align: center;
    }

    /* Styles for .side-2 section on desktop */
    .side-2 {
        width: 50%;
        padding: 20px;
        border-radius: 20px;
    }
}
```

## HTML Structure

The HTML structure includes sections for displaying the user's result and a summary of the scores.

## Attribution

This project was created as a challenge from [Frontend Mentor](https://www.frontendmentor.io?ref=challenge). Coded by [Tobi Adekunle (kerdaino dev)](https://kerdaino.github.io/portfolio/).