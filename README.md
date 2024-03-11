# Frontend Mentor - Ping coming soon page solution

This is a solution to the [Ping coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ping-single-column-coming-soon-page-5cadd051fec04111f7b848da). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Project start date: 09 March 2024
- Project Duration: 04 Hours

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Submit their email address using an `input` field
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty. The message for this error should say _"Whoops! It looks like you forgot to add your email"_
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say _"Please provide a valid email address"_

### Screenshot

| Desktop Version                         | Mobile Version                         |
| --------------------------------------- | -------------------------------------- |
| ![](./screenshots/desktop-version.jpeg) | ![](./screenshots/mobile-version.jpeg) |

### Links

- [Solution URL:](https://github.com/akmtasdikulislam/ping-coming-soon-page)
- [Live Site URL:](https://akmtasdikulislam.github.io/ping-coming-soon-page/)

## My process

- At first, I linked the `style.css` file , **Google Fonts CDN** and also with **FontAwesome Icons Kit CDN** `index.html`.
- Then, imported the colors from `style-guide.md` into the `style.css` file. After that, I initialized the css file and set necessary parameters (such as, font-families, colours, font-sizes, page backgound etc.) for this project.
- Then, I wrote necessary code to reach the given _UI Design Sample_ and also added necessary css styles to match it with the _UI Design Sample_.
- After that, I wrote the necessary CSS MEDIA QUERIES for mobile device view of this project.
- Finally, I wrote necessary `javascript` codes to validate email address when `Notify Me` button is **clicked**.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Usage of javascript `Regular Expression` to validate email address.

```js
// Email validating Regular Expression
const emailValidationRegex =
  /^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/;
if (emailValidationRegex.test(emailInputField.value) == false) {
  // ... rest of the code
  // Here emailValidationRegex.test(emailInputField.value) is validating by testing (matching) the input email address with the standard email address format (name@host.tld)
}
```

### Useful resources

- [How to Do an Email Validation in JavaScript?](https://www.simplilearn.com/tutorials/javascript-tutorial/email-validation-in-javascript) - I got the email validation javascript `Regular Expression` here.

- [Understanding Sibling Selectors in CSS](https://www.browserstack.com/guide/sibling-selectors-in-css) - Here I learnt about the _Sibling Selectors in CSS_

- [100 CSS Box Shadow Examples](https://htmlcssfreebies.com/css-box-shadow-examples/) - Here I got the _box-shadow_ that I have used for the _Notify Me_ button

- [PerfectPixel by WellDoneCode](https://www.welldonecode.com/) - This helped me to match with the _UI Design Sample_.

## Author

- Frontend Mentor - [@akmtasdikulislam](https://www.frontendmentor.io/profile/akmtasdikulislam)
- Twitter - [@Akm_Tasdikul](https://www.twitter.com/Akm_Tasdikul)
