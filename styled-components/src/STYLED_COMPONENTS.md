# Styled components

1. Let's start by creating a new folder and a new file called StyledComponents.js which should encapsulate all our new styled components

2. Let's start by creating a component called Square which should be of 100 x 100 and should have a background-color of blue.

    2.1. When finished console.log this component and see how it looks like in HTML

3. Let's create another component called Rectangle which accepts width and height as props. The background-color should be orange. The component should resize based on the passed props.

4. Let's create a component which extends React.Component called CurvedSquare which displays the outcome of addition of two props x and y.

5. Let's create a new component called Button which should accept onClick and type as props. type should determine how the Button should be colored. ( 'success', 'warning', 'danger' )

6. Let's create a new component called BigButton which should be just like a regular Button only bigger. Use extensions to implement it.

7. Let's create an animation called yoyo which should yo-yo a component back and forth. Let's create a component which only contains an icon ☺ which should yo-yo.

8. Let's create a new component called MobileMenu which should only be visible when the width of the browser is max 400px

9. Let's create a new theme which holds on to base size for square along with success, warning, danger and a base color. Wrap all the components within the ThemeProvider and change hard-coded data to use the theme-provided data instead

10. Refactor all code to separate files
