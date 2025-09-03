## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL:

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- position
- pseudo-elements
- hover effect

### What I learned

In this project, I used some CSS properties to help with responsive font size, such as @media
and pseudo-elements and hover effect

To see how you can add code snippets, see below:

main {
width: 100vw;
height: 100vh;
display: flex !important;
flex-direction: column;
justify-content: center;
align-items: center;
position: relative;
}
main::before {
content: "";
width: 100%;
height: 40vh;
background-image: url(../images/pattern-background-desktop.svg);
background-size: contain;
background-repeat: no-repeat;
background-position: 0 10%;
position: absolute;
top: 0;
}
@media (max-width: 768px) {
main::before {
transform: scale(2);
background-position: 0 35%;
}
}
section .change a {
display: inline-block;
position: absolute;
right: 15px;
color: var(--buttom_color);
font-size: 11px;
font-weight: 600;
}
section .change a:hover {
text-decoration: none;
color: #756cf2;
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements and hover effect

### Useful resources

- [w3schools] https://www.w3schools.com/cssref/sel_hover.php
- [w3schools] https://www.w3schools.com/css/css_pseudo_elements.asp

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
