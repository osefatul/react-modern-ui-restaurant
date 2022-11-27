# Gericht Modern_ui_ux_restaurant

### Intro
This is a modern web application made in react. we have used advanced and production ready file structure along with some great ways of writing complex css.

### Live
Click [here](https://gericht-restaurant-modern-ui-project.netlify.app/) for directing to our project domain.

## Libraries:
    [React-icons](https://react-icons.github.io/react-icons/)

## Project Structure:
  #### Components: 
  This is for all small components
    1 - Navbar
    2 - Sub Heading
    3 - Menu Item
    4 - Footer
  #### Assets:
    Only pictures and video have been kept here
  #### Constants:
  This is going to be the imports of all of the files we are constantly use.
    1 - Data - all data have been objectified here.  
    2 - Images: All images and videos from assets have been linked here in an object.
  #### Containers:
  Containers are the real layout of the project, mean these are for bigger components, means components containing multiple components.
    1 - About Us: Descripton of the restaurant owners and the contact info.
    2 - Chef: Chef intro
    3 - Find Us: where you can find us - the location.
    4 - Gallery: All images gallery container.
    5 - Header:
    6 - Intro:
    7 - Laurels: Acheivements.
    8 - Menu: the menu and prices.

  
- use this web for [educational purpose- BEM](https://sparkbox.com/foundry/bem_by_example)
- Just as a reminder some of the CSS classes are defined in app.js and index.js

- the shortcut way of using overlay (one div upon another) that we used in Intro.css
  - Both div should be under same parent div.
  - prent div should be positioned relative (position:relativ)
  - the div which will be overlay on another must be positioned:
    - position: absolute
    - inset: 0
- using [nth-child](https://www.techonthenet.com/css/selectors/nth_child.php) in css. we used one in the footer container.
