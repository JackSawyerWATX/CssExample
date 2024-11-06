## CSS Positioning Examples

This project demonstrates the four basic CSS positioning types in CSS: static, relative, absolute, and fixed positioning. By viewing the index.html file in a web browser, you can see how each positioning type affects the placement of HTML elements on the page.
Table of Contents

    Overview
    Positioning Types
        Static Positioning
        Relative Positioning
        Absolute Positioning
        Fixed Positioning
    Usage
    Technologies Used
    License

# Overview

This simple HTML and CSS project is designed to illustrate how different CSS position values affect the layout and positioning of elements on a web page. By experimenting with the code and observing the output, you can gain a better understanding of how to use these positioning techniques in your own web development projects.
Positioning Types
Static Positioning

    Class: .static

    CSS:

    .static {
        position: static;
        /* No positioning adjustments */
        border: 3px solid #4AFF82;
    }

    Description: This is the default positioning for HTML elements. Elements with position: static are placed according to the normal flow of the page, and the top, right, bottom, and left properties have no effect.

# Relative Positioning

    Class: .relative

    CSS:

    .relative {
        position: relative;
        /* Move element from normal position */
        top: 30px;
        /* Moves the element 30px down from its original position */
        left: 20px;
        /* Moves the element 20px to the right of its original position */
        border: 3px solid #F98404;
    }

    Description: Elements with position: relative are positioned relative to their normal position in the document flow. The top, right, bottom, and left properties adjust the element's position away from where it would have been.

# Absolute Positioning

    Class: .absolute

    CSS:

    .absolute {
        position: absolute;
        /* Positioned relative to the nearest positioned ancestor */
        top: 60px;
        /* Positions the element 60px from the top edge of its nearest positioned ancestor */
        right: 0;
        /* Positions the element at the right edge of the nearest positioned ancestor */
        border: 3px solid #0275D8;
    }

    Description: Elements with position: absolute are removed from the normal flow and positioned relative to their nearest positioned ancestor (an ancestor with a position other than static). If no such ancestor exists, it is positioned relative to the initial containing block (often the browser window). The top, right, bottom, and left properties specify the exact position.

# Fixed Positioning

    Class: .fixed

    CSS:

    .fixed {
        position: fixed;
        /* Element is fixed in the viewport */
        bottom: 0;
        /* Positions the element at the very bottom of the viewport */
        border: 3px solid #7034A3;
    }

    Description: Elements with position: fixed are positioned relative to the viewport, which means they stay in the same place even when the page is scrolled. The top, right, bottom, and left properties specify the position relative to the viewport edges.

# Usage

    Download or Clone the Repository

    Save the provided HTML file or clone the repository if available.

    Open the HTML File

    Open the index.html file in a web browser such as Chrome, Firefox, or Safari.

    Observe the Positioning
        Static Element: The "Static" div will appear where it normally would in the document flow.
        Relative Element: The "Relative" div will be shifted 30px down and 20px right from its normal position.
        Absolute Element: The "Absolute" div will be positioned 60px from the top and aligned to the right edge of its nearest positioned ancestor (in this case, the <body> element).
        Fixed Element: The "Fixed" div will be anchored to the bottom of the viewport and remain visible even when scrolling.

    Experiment

    Feel free to modify the CSS properties to see how changes affect each element's positioning.

# Technologies Used

    HTML5: Markup language for structuring the content.
    CSS3: Stylesheet language for describing the presentation of the document.

License

This project is released under the MIT License. You are free to use, modify, and distribute this code as you see fit.