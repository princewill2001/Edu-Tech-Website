# Edu-Tech Website 
## Description
Welcome to my project! This is an Educational Tech Website made using HTML, CSS and JavaScript. The Purpose of the website was to test my knowledge around Frontend Web Development, and to also understand the concept behind building multipage websites. I also used SwiperJS CDN to call the Slider feature for the Student Testimonials section. *You can read about the SwiperJS API here:* https://swiperjs.com/swiper-api
### Block Element Modifier; 
Block Element Modifier (BEM) is a methodology and naming convention for writing CSS and HTML code in a way that promotes better organization, maintainability, and scalability in large web projects. BEM was introduced as a solution to the problem of naming CSS classes ambiguously or inconsistently, which can lead to styling conflicts and difficulties in understanding and maintaining code. 
*The BEM methodology divides components into three main parts:*
### Block: A standalone entity that is meaningful on its own. Blocks are the top-level components on a page and represent reusable UI elements. Examples of blocks might include header, button, menu, etc.
### Element: A part of a block that has no standalone meaning and is semantically tied to its block. Elements are typically nested within blocks and represent parts of the block. For example, within a header block, you might have elements like logo, navigation, search, etc.
### Modifier: A flag that alters the appearance or behavior of a block or element. Modifiers are optional and provide variations to blocks or elements without changing their base styles. For example, you might have modifiers like large, small, blue, active, etc.

*Aspects of CSS covered:*
- CSS Grid & Flexbox
- CSS Units for Responsive Design(VH - view height, VW - View Width, FR - Fraction, % - Percentage)
- CSS Transitions and Animations
- CSS Media Queries - For making the Website responsive
- CSS Variables: They act as a pre-set prerequisites for which you can use to customise your website. 

## Contributions
I will welcome any and all contributions. Here is how you can help:
- Report Bugs: If you encounter any bugs or some features are not responsding, let me know.
- Contribute Code: If you are a developer and would love to contribute, I would definitely appreciate it.
- Any New Ideas: 

## Tools Used:
- HTML5
- CSS3
- JavaScript
- SwiperJS CDN - For sliding Features
- Form Submission with Spam Protection

## CSS GRID AND FLEXBOX
### CSS GRID
Imagine you're laying out a floor plan for a house. With CSS Grid, you can think of your web page as a grid of boxes, just like rooms in a house. You can divide your page into rows and columns, creating a layout that's like arranging furniture in those rooms.
*Here's how it works:*
You define a grid container, which is like the blueprint of your house. You specify how many rows and columns you want.
Inside the grid container, you place grid items, which are like pieces of furniture. You can specify where each item goes in the grid by using row and column coordinates.
You can also control the spacing between the rows and columns, making it easy to create a well-organized layout.
For example, if you want a webpage with a header, sidebar, main content area, and footer, you can use CSS Grid to divide the page into rows and columns, and then place each section exactly where you want it.

### CSS FLEXBOX
Now, let's say you're arranging a group of chairs around a table for a dinner party. With Flexbox, you have a lot of flexibility in how you arrange those chairs – you can easily adjust their positions and spacing to make sure everyone has a comfortable seat.
*Here's how it works:*
You have a container, which is like the dining table. Inside the container, you have flex items, which are like the chairs around the table.
Flexbox gives you control over how the flex items are arranged along a single axis – either horizontally or vertically.
You can easily adjust the size of the flex items to make them fill the available space, or to make them shrink or grow as needed.
Flexbox also lets you control the spacing between the flex items, so you can make sure there's enough room for everyone to sit comfortably.
For example, if you have a navigation menu with a list of links, you can use Flexbox to arrange the links horizontally or vertically, and to control the spacing between them.

In summary, CSS Grid is like arranging rooms in a house, with precise control over rows and columns, while Flexbox is like arranging chairs around a table, with flexible control over spacing and alignment. Both are powerful tools for creating layouts in web design, and you can use them together to achieve even more complex designs.

## CSS TRANSITIONS AND ANIMATIONS
### CSS TRANSITIONS
CSS transitions allow you to smoothly change property values over a specified duration. They are triggered by changes in CSS properties, such as hover effects, and provide a way to animate these changes seamlessly.
Here's the basic syntax for setting up a CSS transition:
.element {
    transition-property: property1 property2 ...; /* Specifies which properties to transition */
    transition-duration: time; /* Specifies the duration of the transition */
    transition-timing-function: timing-function; /* Specifies the timing curve of the transition */
    transition-delay: time; /* Specifies a delay before the transition starts */
}

### CSS ANIMATIONS
CSS animations provide more control over the animation process. You can define keyframes that specify the intermediate stages of the animation and customize the timing, duration, and iteration count.
Here's how you would set up a CSS animation:
@keyframes animationName {
    0% { /* Initial state */ }
    50% { /* Intermediate state */ }
    100% { /* Final state */ }
}

.element {
    animation-name: animationName;
    animation-duration: time; /* Specifies the duration of the animation */
    animation-timing-function: timing-function; /* Specifies the timing curve of the animation */
    animation-delay: time; /* Specifies a delay before the animation starts */
    animation-iteration-count: count; /* Specifies the number of times the animation should repeat */
    animation-direction: direction; /* Specifies whether the animation should play in reverse */
    animation-fill-mode: mode; /* Specifies how styles are applied before and after the animation */
    animation-play-state: state; /* Specifies whether the animation is running or paused */
}

In summary, CSS transitions are simpler and best suited for basic animations triggered by changes in CSS properties, while CSS animations offer more control and are ideal for complex animations with predefined keyframes.





