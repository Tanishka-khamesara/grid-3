# grid-3



![Screenshot (98)](https://github.com/Tanishka-khamesara/grid-3/assets/127411985/1a34c073-b30b-4a6b-8e65-a6e82db7c30b)
![Screenshot (99)](https://github.com/Tanishka-khamesara/grid-3/assets/127411985/2f861444-deb2-4626-b9dd-ac697c4198dd)
![Screenshot (100)](https://github.com/Tanishka-khamesara/grid-3/assets/127411985/c4befea1-ded2-4598-9a26-850ac7576cbc)
Html explaination-->
i used div for making a container.
another div for navbar.
img tag for inserting image.
![Screenshot (101)](https://github.com/Tanishka-khamesara/grid-3/assets/127411985/f00250fb-47b0-4739-92c8-f8c3f67170aa)
![Screenshot (102)](https://github.com/Tanishka-khamesara/grid-3/assets/127411985/cda5add1-4aab-4243-82ef-4f6e51e45471)
![Screenshot (103)](https://github.com/Tanishka-khamesara/grid-3/assets/127411985/f4e64931-60f2-4b2c-a298-85e75e977c70)
*: This selector selects all HTML elements on the page.

margin: 0%;: This sets the margin of all elements to 0%. This is typically done to remove any default margins that browsers apply to elements.

box-sizing: border-box;: This property changes the box model used by the browser. When box-sizing is set to border-box, the width and height of an element include its padding and border, but not its margin. This can help with consistent sizing and layout.

.container: This is a class selector that selects elements with the class name "container."

display: grid;: This sets the display property of the selected element to "grid," indicating that it will be treated as a grid container.

grid-template-rows and grid-template-columns: These properties define the size and number of rows and columns in the grid. In this case, it's creating a grid with 6 rows, each 6rem tall, and 16 columns, each 6.25% wide.

grid-template-areas: This property defines the layout of the grid by specifying which grid areas contain which elements. It uses a grid template string to map out the areas.

.container > img: This is a selector targeting <img> elements that are direct children of elements with the class "container."

padding: 3px;: Adds 3 pixels of padding around the images.

border: 3px solid #000;: Adds a 3-pixel-wide solid black border around the images.

.navbar: This is a class selector for elements with the class "navbar."

grid-area: nav;: This property assigns the "navbar" element to the "nav" grid area defined in the grid template.
.img-1, .img-2, .img-3, ... .img-9: These are class selectors for elements with class names "img-1" through "img-9." They are used to position various images within the grid.

grid-area: These properties assign the elements to specific grid areas, allowing them to be placed in the layout defined by the grid template.
img: This selector targets all <img> elements on the page.

width: 100%; and height: 100%;: These properties set the width and height of the images to 100% of their container, ensuring that they fill the available space while maintaining their aspect ratio.
.navbar img: This selector targets <img> elements within elements with the class "navbar."

width: 80px; and height: 80px;: These properties set a fixed width and height of 80 pixels for the images within the navbar.
.navbar: This selector targets elements with the class "navbar" again.

border: 3px solid #000;: Adds a 3-pixel-wide solid black border around the navbar.

margin-top: 1px;: Adds 1 pixel of margin to the top of the navbar.

display: grid;: Specifies that the navbar should use grid layout.

grid-auto-flow: column;: Sets the grid auto-flow to "column," which means that the child elements will be placed in columns within the grid.

justify-content: center; and align-items: center;: These properties center the child elements (in this case, the images) both horizontally and vertically within the navbar.

gap: 8rem;: Specifies an 8-rem gap between the columns in the grid.

button: This selector targets all <button> elements on the page.
background-color: #000;: Sets the background color of the buttons to black (#000).

color: #fff;: Sets the text color of the buttons to white (#fff).

padding: 0.1rem 1rem;: Adds padding to the buttons, with 0.1rem padding on the top and bottom and 1rem padding on the left and right.

border-radius: 8px;: Adds a border-radius of 8 pixels, giving the buttons rounded corners.

These CSS properties and selectors are used to style and layout the HTML elements in the provided code, creating a grid-based layout with images, a navbar, and buttons.




