# training
Let's review what you've learned so far:

    You can add headings of different sizes using the different headings elements: <h1> through <h6>.
    Paragraphs are added with the <p> element.
    Unordered lists are created with the <ul> element and list items are added using the <li> element.
    Ordered lists are created with the <ol> element and list items are added using the <li> element.
    You can add links to your web page using the <a> element - don't forget the href attribute!
    Images can be added with the <img> element - don't forget the src attribute!
    Images help support visually impaired users when <img> elements include the alt attribute.
    You can turn anything into a link by wrapping it with an <a> element.
    White space in the HTML file does not affect the positioning of elements in the browser.
    The W3C recommends 2 spaces of indentation for nested HTML elements.
    Comments are used to take notes inside of an HTML file. You can add a comment with <!-- This is a comment -->.

Let's review what you've learned so far:

1. A CSS selector targets an HTML element.

2. CSS declarations style HTML elements. Declarations must contain the following two things:

    property - the property you want to style.
    value - the value for the property you are styling.

3. CSS declarations must end in a semicolon (;)

4. A CSS rule consists of a CSS selector and the declarations inside of the selector.

5. Multiple element selectors can be used to style multiple elements at once.

6. Comments keep code easy to read and allow you to experiment with new code without having to remove old code.

7. CSS follows certain best practices for spacing and indentation:

    One line of spacing between a selector and the opening curly brace.
    No spacing between CSS declarations and the opening and closing curly braces of the CSS rule.
    Two spaces of indentation for CSS declarations.
    One line of spacing between CSS rules.

Let's review what you've learned so far:

    The font-family property changes the typeface of text.
    Serif fonts have extra details on the ends of each letter. Sans-Serif fonts do not.
    Fallback fonts are used when a certain font is not installed on a user's computer.
    Google Fonts provides free fonts that can be used in an HTML file with the <link> element.
    Font size can be specified using pixels, ems, or percentages.
    The vertical spacing between lines of text can be modified with the line-spacing property.
    The horizontal spacing between words can be modified with the word-spacing property.
    The spacing between letters, the kernel, can be modified with the letter-spacing property.
    Text can appear bold with the font-weight property.
    Text can appear in italics with the font-style property.
    Text can appear in all uppercase or all lowercase with the text-transform property.
    Text can be aligned with the text-align property.

Let's review what you've learned so far:

    Code is a lot more readable when it is organized using IDs, classes, and divs.
    IDs label HTML elements that are unique to the web page (an element that appears only once).
    Classes label elements that will share the same styling. They make styling more efficient.
    The <div> groups elements together. It makes the HTML file easier to read by organizing the web page into logical sections.
    HTML elements can be labeled with multiple classes.
    Divs are one of the most commonly used HTML elements. Understanding how they are used is a critical skill for web developers.

    It's not possible to view a box's border if the border's style has not been set. A border's style can be set with the border-style property. This property can take on one of the following values:

        solid - border is a solid line.
        dashed - border is a series of lines or dashes.
        dotted - border is a series of square dots.
        double - border is two solid black lines.
        groove - border is a groove (or carving).
        inset - border appears to cut into the screen.
        outset - border appears to pop out of the screen.
        ridge - border appears as a picture frame.
        hidden or none - no border.

        p {
          border-style: solid;
          border-width: 3px 1px 2px 1px;
        }
        The values in the example above refer to the border width in clockwise order (top: 3 pixels, right: 1 pixel, bottom: 2 pixels, left: 1 pixel).

    Let's review what you learned:

        You can style the borders of an element's box.
        The border-width property allows you to set the thickness, or width, of a border.
        The border-style property allows you to change the style of border used.
        The border-color property allows you to change the color of a border.
        Individually setting the style, thickness, and color of a border can bloat code. It's more efficient to use the shorthand border property and specify all three properties at once, in that order.
        Box borders don't have to be square. Their corners can be rounded with the border-radius property.

    So far, we've focused on two aspects of the box: dimensions and borders. In the next unit, we'll focus on the content within the box and the space outside of the box.




