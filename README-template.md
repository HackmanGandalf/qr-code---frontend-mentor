# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- First I created the bright blue background
- Then I created the white card and added the qr code
- Then I added the text under the qr code
- Next I completed the styling of the card (font, appropriate padding distance, centering of text etc)
- Then I used flex to center the webpage.
- When I added the footnote that contained my name, it was placed (by default) side by side with the card. So I had to add the flex-direction and set it 'column'.
- Lastly, I changed the colour of the footnote to darkgray. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flex

### What I learned

This challenge was a great refresher on using CSS Flex. I relearnt how to center a div on the webpage.

Upon adding the flex styling, the webpage contents still did not center. I asked ChatGPT and it suggested I add these lines of code to my css.

```css
html, body {
  height: 100%;
  margin: 0;
}
```


### Useful resources

- (https://stackoverflow.com/questions/44621094/css-flex-stacking-items-on-top-of-each-other) - This helped me with the flex-direction styling in the css.

## Author

- Website - [Solomon Onah](https://gandalf.up.railway.app/)
- Frontend Mentor - [@HackmanGandalf](https://www.frontendmentor.io/profile/HackmanGandalf)
- Twitter - [@SoloOnah](https://twitter.com/SoloOnah)
