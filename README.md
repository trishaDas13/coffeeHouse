# coffeeHouse
Hosted link -- https://trishadas13.github.io/coffeeHouse/

![1](https://github.com/trishaDas13/coffeeHouse/assets/126088849/d93f17cb-ee2c-4446-a26c-c40e17a3e110)
![1a](https://github.com/trishaDas13/coffeeHouse/assets/126088849/77b5a9d8-ca0d-4f2b-a09e-7eeddc1e12fb)

Inside a "div" with the class "coffee," I've included an "img" tag. This image, sourced from a URL, depicts a coffee cup. If the image fails to load, there's an alternate "error" text. The image is set to 150x150 pixels.

Next, within the same "div," there's an "h4" tag containing "Cappuccino." This serves as a title for the showcased coffee type.

Moving to the next section, there's another "div" with the class "coffee." Inside it, another "img" tag shows a different coffee image. It also has an alternate "error" text and shares the 150x150 pixel dimensions.

Below the image, an "h4" tag reads "Espresso," serving as a title for this distinct coffee variety.

Collectively, these HTML elements present two types of coffee: "Cappuccino" and "Espresso," with corresponding images and titles for each.

![1b](https://github.com/trishaDas13/coffeeHouse/assets/126088849/b770bb34-b491-4d3f-b059-f014bb39bdbb)
For .container:

height: 240vh;
I've set the height of the element with the class .container to be 240 viewport heights (vh). This will make the container considerably taller than the visible screen area.

width: 100%;
I've set the width of the .container element to occupy the full width of its containing element, ensuring it spans the entire available horizontal space.

background-color: rgb(237,212,212);
I've chosen a background color with the RGB values rgb(237,212,212) for the .container. This background color gives the container a light and soft appearance.

For #header:

width: 100%;
I've set the width of the element with the ID header to 100% of its containing element's width. This ensures that the header spans the entire width of the available space.

height: 300px;
I've set the height of the #header element to 300 pixels. This height creates a fixed space for the header content.

background-image: url("https://i.pinimg.com/736x/e1/c2/3a/e1c23ac34847740f672717c89a62ae37.jpg");
I've added a background image to the #header element using the provided URL. The image will be displayed as the background of the header.

background-size: cover;
I've set the background size to cover, ensuring the background image covers the entire header area without distortion.

background-position: center;
I've positioned the background image at the center of the #header element.

box-shadow: 0 0 8px 1px rgba(0, 0, 0, 0.7);
I've added a box shadow to the #header element, creating a subtle shadow effect. The shadow is 8 pixels wide and has a slight offset, with a slightly transparent black color (rgba(0, 0, 0, 0.7)).

For input:

I've styled the input elements as text fields, enhancing their visual appearance.

width: 944px;
I've set the width of the input elements to 944 pixels, ensuring they are wide enough to accommodate text.

height: 60px;
I've set the height of the input elements to 60 pixels, providing a taller input field.

border-radius: 10px;
I've added a border-radius of 10 pixels, giving the input fields rounded corners.

background-color: rgb(99,18,18);
I've set a background color with the RGB values rgb(99,18,18) for the input elements, giving them a dark red background.

position: sticky;
I've set the position of the input elements to sticky, allowing them to stick to the top of the viewport when scrolling.

top: 56px;
I've positioned the input elements 56 pixels down from the top edge of their containing element. This ensures they appear below the header.

left:204px;
I've positioned the input elements 204 pixels from the left edge of their containing element. This creates a consistent horizontal positioning.

color: white;
I've set the text color of the input fields to white, ensuring good contrast against the dark background.

padding-left: 10px;
I've added left padding of 10 pixels to create space between the text input and the input field's left edge.

border: none;
I've removed the default border of the input fields.

For input:focus:

I've defined styles for when the input elements are focused (clicked or selected):

background-color: rgba(99,18,18, 0.9);
I've set a slightly transparent background color with the same RGB values for the input elements when focused. This provides a visual indication that the input is active.

outline: none;
I've removed the default browser outline that appears around focused elements, creating a cleaner appearance.


![1](https://github.com/trishaDas13/coffeeHouse/assets/126088849/fa4ca3c8-3340-4c2b-9226-119cef738e69)

Within a "div" container, there's another nested "div" with the class "coffee." This inner "div" contains an "img" tag, which is linked to an image URL showcasing a coffee cup. In case the image can't be displayed, there's an alternative "error" text. The image has been constrained to dimensions of 150x150 pixels.

Beneath the image, there's an "h4" tag displaying the text "Latte." This title serves to identify the type of coffee being presented.

To summarize, the HTML elements work together to present a "Latte" coffee option. The image and title combine to provide a visual and textual representation of this particular coffee variety.

![1b](https://github.com/trishaDas13/coffeeHouse/assets/126088849/273fb507-f5c6-43a4-9e9c-c94891685eb1)

For .coffee_main:

display: flex;
I've set the display property of elements with the class .coffee_main to flex. This creates a flex container for its child elements, allowing for flexible layout options.

justify-content: space-evenly;
I'm distributing the child elements evenly along the main axis (horizontal axis) within .coffee_main. This ensures equal space between the child elements.

vertical-align: middle;
I've applied vertical alignment to the middle for the content within .coffee_main. This centers the content vertically within the flex container.

padding: 40px 0;
I've added 40 pixels of padding on the top and bottom sides of .coffee_main. This creates spacing around the content within the container.

margin-bottom: 2rem;
I've added a margin of 2 rems (root em units) at the bottom of .coffee_main. This provides some separation between .coffee_main and other content below it.

For .coffee_main > div (child elements of .coffee_main):

display: flex;
I've set the display property of child div elements within .coffee_main to flex. This creates a flex container for these child elements.

flex-direction: column;
I'm arranging the child elements in a column direction within their parent div. This stacks the child elements vertically.

align-items: center;
I've aligned the child elements' content to the center along the cross axis (vertical axis). This centers the content horizontally within each child element.

For h4:

margin-top: 15px;
I've added a top margin of 15 pixels to h4 elements. This creates some space between the h4 text and the elements above it.

opacity: 0.8;
I've reduced the opacity of h4 elements to 0.8. This creates a slightly faded appearance for the text, giving it a subdued look.

For img:hover:

box-shadow: 0 18px 20px rgb(0, 0, 0);
I've added a box shadow to images when hovered over. This shadow appears with an offset of 0 pixels horizontally and 18 pixels vertically, along with a blur radius of 20 pixels. The shadow color is a dark shade of black.

height: 152px;
I've set the height of images to 152 pixels when hovered over. This increases the image's height on hover, providing an interactive effect.

width: 152px;
Similarly, I've set the width of images to 152 pixels when hovered over. This increases the image's width on hover, maintaining its aspect ratio.

![1](https://github.com/trishaDas13/coffeeHouse/assets/126088849/c72ac62a-20b3-4257-ad4b-d2b92059de4f)

![2](https://github.com/trishaDas13/coffeeHouse/assets/126088849/62cc0120-9eff-494b-aef4-c75ab1efd9b2)

![1a](https://github.com/trishaDas13/coffeeHouse/assets/126088849/115be640-387a-4707-861a-bdf7ec282025)

![1a1](https://github.com/trishaDas13/coffeeHouse/assets/126088849/2254d589-fe36-4248-a811-bb9e29dce782)


![1a2](https://github.com/trishaDas13/coffeeHouse/assets/126088849/fdcfb512-b202-4a6c-bc21-04682d9fb5cb)


![1b](https://github.com/trishaDas13/coffeeHouse/assets/126088849/ccddd4e3-47e4-4898-b1be-b6071168758e)

For .section1 and .section2:

width: 90%;
I've set the width of elements with the classes .section1 and .section2 to 90% of their containing element's width. This width percentage ensures that these sections occupy most of the available horizontal space.

margin: auto;
I've centered both .section1 and .section2 horizontally using margin: auto;. This creates equal margins on the left and right sides, effectively centering the sections.

background-color: rgb(215,161,161);
I've chosen a background color with the RGB values rgb(215,161,161) for both sections. This color gives the sections a light pinkish appearance.

border-radius: 12px;
I've applied a border-radius of 12 pixels to both .section1 and .section2. This gives the sections rounded corners, softening their appearance.

box-shadow: 0 0 6px 2px rgb(194, 93, 93);
I've added a box shadow to both sections. The shadow is positioned with no horizontal or vertical offset (0 0), has a blur radius of 6 pixels, and a spread radius of 2 pixels. The shadow color is a shade of red.

padding: 2%;
I've applied a padding of 2% to both sections. This creates spacing between the content and the edges of the sections, enhancing the visual appearance.

color: rgb(165, 42, 42);
I've set the text color within both sections to a shade of red (#a52a2a). This color provides a contrasting text color against the background.

vertical-align: baseline;
I've aligned the text vertically within both sections to the baseline of the text. This ensures consistent vertical alignment of text content.

font-size: 16px;
I've set the font size of the text content within both sections to 16 pixels. This maintains a readable and consistent text size.

line-height: 20px;
I've set the line height of the text content within both sections to 20 pixels. This provides adequate spacing between lines of text for readability.

For #list:

line-height: 28px;
I've set the line height of text content within the element with the ID list to 28 pixels. This increases the spacing between lines of text, enhancing readability and making the text more readable.
