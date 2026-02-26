# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

A simple, clean QR code component built with semantic HTML and CSS. The card displays a QR code image with descriptive text about Frontend Mentor, centered on the page with a modern design aesthetic.

## Screenshot of solution

./screenshot.jpg

### Links

- Solution URL: [GitHub Repository](https://github.com/Dguaicha/challenges-and-more)

## My process

### Built with

- Semantic HTML5 markup
- CSS styling with flexbox layout
- Mobile-first responsive design
- Google Fonts (Outfit font family)
- CSS box-shadow for depth and visual hierarchy

### What I learned

This project deepened my understanding of HTML and CSS fundamentals:

**HTML Structure & Semantic Markup:**
```html
<div id="qr-container">
  <div class="qr-code-image">
    <img src="images/image-qr-code.png" alt="frontend mentor qr code">
  </div>
  <h2>Improve your front-end skills by building projects</h2>
  <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
```

Using semantic containers and meaningful class names makes the code more maintainable and accessible. The proper use of heading hierarchy ensures good SEO and screen reader support.

**CSS Styling & Layout:**
```css
#qr-container {
  width: 350px;
  height: 520px;
  background-color: white;
  border-radius: 20px;
  margin-top: 7rem;
  margin-left: auto;
  margin-right: auto;
  box-shadow: 0px 10px 20px rgba(0,0,0,0.2);
}
```

I learned how to leverage CSS properties effectively:
- **Box-shadow** creates depth and makes the card stand out
- **Border-radius** for modern rounded corners
- **Auto margins** for horizontal centering
- **Flexbox & spacing** for proper alignment of content
- **Color psychology** using subtle grays and contrasting text colors for readability

### Continued development

Areas to focus on in future projects:
- Advanced CSS techniques (Grid layouts, custom properties/variables, animations)
- Responsive design patterns (media queries, mobile-first approach refinement)
- Accessibility improvements (ARIA labels, focus states, keyboard navigation)
- CSS preprocessors (SCSS/SASS) for more maintainable stylesheets
- JavaScript interactivity and dynamic content

### Useful resources

- [MDN Web Docs - CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model) - Helped me understand spacing and layout
- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) - Essential for modern layouts
- [Frontend Mentor](https://www.frontendmentor.io/) - Excellent platform for building real-world projects
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Great visual reference for flexbox properties

### AI Collaboration

I used GitHub Copilot and Claude during this project:

- **Copilot** helped with code completion and generating CSS boilerplate quickly
- **Claude** provided detailed explanations of HTML structure best practices and CSS alignment techniques
- Both tools accelerated the development process by providing instant suggestions and explanations
- Working with AI assistants reinforced the importance of writing clear, semantic code that's easy for both humans and AI to understand

## Author

- Frontend Mentor - [@Dguaicha](https://www.frontendmentor.io/profile/Dguaicha)
- GitHub - [@Dguaicha](https://github.com/Dguaicha)

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
