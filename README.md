[Techdegree Project 3 - Accessible Online Registration Form](https://gracemarsh.github.io/accessible-form/)

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
