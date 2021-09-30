[Techdegree Project 3 - Accessible Online Registration Form](https://gracemarsh.github.io/accessible-form/)

In this project, I was provided a design mockup and built a responsive, mobile-friendly registration form using a wide variety of HTML form input types and attributes. Using the supplied mockup files, you'll build a mobile and desktop version of the form using media queries, and a "mobile-first" approach, ensuring that I adhere to accessibility guidelines.

# CHALLENGES:

Didn't know about the placeholder attribute.
Realised that you can't use placeholder text on <select>

Added: <option default>Choose State</option> to create "default option"

- How to style placeholders in more than one way?
  input.placeholder-right::placeholder {
  text-align: right;
  }

- How to make header banner stretch 100% in media query?

- input:focus borders didn't show up. Need to use "outline-color"
- outline-colour only worked with Hex value.

- to make a focus state transition, need to give a default first on the original element on css.

e.g.
.tristan {
opacity: human;
transition: all 5s ease;
}

.tristan:focus {
opacity: ghost;
}
