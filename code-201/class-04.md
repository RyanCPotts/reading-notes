# Class 4

Tese topics are critical for understanding basic programming.

### To create a basic link, we wrap text or other content inside what element?
`<a>` (anchor)

### The href attribute contains what information?
The href attribute contains the URL "https://example.com". When the link is clicked, the browser will navigate to the URL or destination address to which the hyperlink points.

### What are some ways we can ensure links on our pages are accessible to all readers?
Descriptive Link Text: Use descriptive and meaningful text for link anchors. Avoid using vague terms like "click here" or "read more." Instead, provide context about the linked content.

Title Attribute: Utilize the title attribute to provide additional information about the link. Screen readers can announce this information to users, aiding in understanding the purpose of the link.

Clear Link Styling: Ensure that links are visually distinct from surrounding text and are easily recognizable as interactive elements. Consistent and intuitive styling, such as underlining or color changes, can help users identify links.

Focus Styles: Implement clear focus styles for links to ensure that keyboard users can easily navigate and interact with them. Highlighting the focused link with a border or background color can improve accessibility.

Keyboard Accessibility: Ensure that links are accessible via keyboard navigation. Users should be able to tab through links in a logical order and activate them using the Enter key.

Skip Navigation Links: Include skip navigation links at the beginning of long documents or complex web pages. These links allow keyboard users to bypass repetitive navigation and go directly to the main content.

ARIA Roles and Attributes: Use ARIA (Accessible Rich Internet Applications) roles and attributes to enhance the accessibility of links, especially for dynamic or interactive content. For example, use role="button" for links that act like buttons.

Testing with Assistive Technologies: Test your web pages with screen reader software and other assistive technologies to ensure that links are announced correctly and that users can navigate them effectively.

###What is meant by “normal flow” in CSS?
In CSS, "normal flow" refers to the default layout behavior of HTML elements on a web page without any positioning or floating applied. In the normal flow, elements are laid out in the order they appear in the HTML document, one after another, following the document's structure.

### What are a few differences between block-level and inline elements?
Block-level elements:

Start on a new line.
Occupy the full width available.
Create line breaks before and after themselves.
Can have a defined height.
Accept margin, padding, and border properties.
Can contain both block-level and inline elements within them.

Inline elements:

Do not start on a new line.
Only occupy the width necessary for their content.
Do not create line breaks.
Do not have a defined height.
Accept margin and padding properties.
Cannot contain block-level elements but can contain other inline elements.

### ___ positioning is the default for every html element.
Static positioning

### Name a few advantages to using absolute positioning on an element.
Using absolute positioning on an element offers several advantages:

Precise Placement: Absolute positioning allows you to precisely position an element relative to its nearest positioned ancestor or the initial containing block. This enables pixel-perfect positioning of elements on a webpage.

Layering: Absolute positioning allows elements to be layered on top of each other, which is useful for creating complex layouts and overlay effects.

Floating Over Content: Absolute positioning removes elements from the normal document flow, allowing them to float over other elements without affecting their layout. This is commonly used for creating modal dialogs, tooltips, or dropdown menus.

Responsive Design: Absolute positioning can be beneficial for responsive design when used judiciously. By setting specific coordinates for an element, you can ensure its position remains consistent across different screen sizes and resolutions.

Dynamic Position ents that need to be repositioned based on user actions or viewport changes.

Accessibility: When used appropriately, absolute positioning can improve accessibility by allowing assistive technologies to focus on relevant content without being distracted by visually hidden elements.

Easy to Implement: Absolute positioning is straightforward to implement and understand, making it a convenient choice for developers who need precise control over element positioning without complex layout calculations.

While absolute positioning offers these advantages, it's essential to use it judiciously and consider its impact on the overall layout and responsiveness of the webpage. Overuse of absolute positioning can lead to maintenance challenges and accessibility issues.

### What is a key difference between fixed positioning and absolute positioning?
A key difference between fixed positioning and absolute positioning is how they relate to the viewport:

Fixed Positioning: Elements with fixed positioning are positioned relative to the viewport, meaning they remain fixed in their position even when the page is scrolled. This behavior is useful for elements like navigation bars, headers, or banners that need to stay in a fixed position regardless of the user's scrolling activity.

Absolute Positioning: On the other hand, elements with absolute positioning are positioned relative to their closest positioned ancestor or the initial containing block. They are typically removed from the normal document flow and are not affected by scrolling. Absolute positioning is commonly used for overlaying elements or positioning them precisely within a parent container.

In summary, the main difference is that fixed positioning is relative to the viewport and remains fixed even when scrolling, while absolute positioning is relative to the nearest positioned ancestor and does not necessarily stay fixed during scrolling.

### Describe the difference between a function declaration and a function invocation.
Function Declaration:

A function declaration is a statement that defines a named function.
It consists of the function keyword followed by the function name, a list of parameters (enclosed in parentheses), and the function body (enclosed in curly braces).
Function declarations are hoisted, which means they are processed before any code execution, allowing you to call the function anywhere in your code, even before the actual declaration.

Function Invocation:

Function invocation, also known as calling or executing a function, involves using the function name followed by parentheses containing any arguments the function requires (if any).
It triggers the execution of the function's code block with the specified arguments.
Functions can be invoked multiple times throughout the code, each time performing the defined operations.

### What is the difference between a parameter and an argument?

The terms "parameter" and "argument" are often used interchangeably, but they have different meanings in the context of functions:

Parameter:

A parameter is a variable listed as part of the function declaration.
It acts as a placeholder for the value that will be provided when the function is called or invoked.
Parameters are defined within the parentheses following the function name and are separated by commas if there are multiple parameters.
Parameters are used to specify what information a function needs to perform its task.

An argument is the actual value or expression that is passed to the function when it is called or invoked.
Arguments are supplied within the parentheses when calling the function and are passed in the same order as the parameters in the function declaration.
Functions can have zero or more arguments, depending on the number of parameters they expect.
Arguments provide the actual data that the function will work with when it executes.

### What is the difference between a parameter and an argument?

Driver-Navigator Pairing:

In this approach, one team member assumes the role of the "driver" who writes the code, while the other team member takes on the role of the "navigator" who observes, reviews, and guides the driver.
The driver focuses on implementing the code logic, writing tests, and translating high-level design into code.
The navigator focuses on reviewing the code in real-time, spotting errors, suggesting improvements, conducting research, and thinking ahead about design and architecture.
Benefits:
Enhanced Code Quality: Pairing allows for continuous code review, leading to higher quality code with fewer bugs and issues.
Knowledge Sharing: Both team members actively participate in problem-solving and decision-making, leading to mutual learning and knowledge sharing.
Reduced Debugging Time: Issues and bugs are identified and resolved in real-time, reducing the time spent on debugging later in the development process.
Increased Collaboration: Pair programming fosters collaboration and communication between team members, resulting in better team cohesion and alignment on project goals.
Ping-Pong Pairing:

In this approach, team members take turns assuming the role of the driver and navigator in short intervals, often following a strict time frame (e.g., every 5-10 minutes).
The driver starts by writing a failing test case. Then, the navigator guides the driver in implementing the code to make the test pass.
Once the test passes, the roles switch, and the navigator becomes the driver who writes the next failing test case, and the process repeats.
Benefits:
Test-Driven Development (TDD): Ping-pong pairing naturally lends itself to test-driven development (TDD), as it encourages the creation of tests before writing code to fulfill those tests.
Continuous Feedback Loop: The iterative nature of ping-pong pairing promotes a continuous feedback loop, where each team member provides immediate feedback to the other, leading to rapid iterations and improvements.
Cross-Pollination of Ideas: Switching roles allows team members to gain exposure to different perspectives and coding styles, fostering creativity and innovation.
Reduced Fatigue: The frequent role-switching helps prevent burnout and fatigue by allowing team members to periodically rest their minds and switch tasks.
Overall, both driver-navigator pairing and ping-pong pairing are effective strategies for improving code quality, fostering collaboration, and enhancing team productivity in software development projects.
