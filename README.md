# Déguster (Desserts Map)
• Déguster is an original idea for a website revolving around **desserts**, designed for knowledge propagation, <br>
&ensp; &nbsp;interaction, and social sharing among dessert lovers worldwide. <br>
• Here, we emphasize how to creatively use HTML, CSS, and JavaScript for the UI design of Déguster.<br>

# Website Layout Design
**1. Top Navigation Bar Design** <br>
&emsp;The top navigation bar is encapsulated in a CSS custom class menu_bar, with a total width of 100vw and height of 10vh.<br>
&emsp;Namely, it will always occupy 100% of the screen's visible width and 10% of its height, being responsive to window size.<br> 
&emsp;This component includes:<br>
&emsp;&emsp; • An unordered list (\<ul\>) with several embedded anchor links (\<a\>), which facilitate navigation between different modules of the website.<br>
&emsp;&emsp; • The logo formed by an image (\<img\>) and several spans (\<span\>), positioned on the left to display the website's name and serve as a trigger for the left-side submenu.<br>

**2. Left-side Submenu Design** <br>
&emsp;A hidden submenu appears when the user hovers over the website name. <br>
&emsp;The submenu layout is constructed using an unordered list (\<ul\>) with several embedded anchor links (\<a\>), categorized by region to facilitate navigation to the desired dessert pages.<br>

**3. Main Content Area Design** <br>
&emsp;The main content area has a height set to 90vh and its width adjusts as follows:<br>
&emsp;&emsp; • When the left-side submenu is collapsed, the width is set to 100vw. <br>
&emsp;&emsp; • When the submenu is expanded, the width shrinks to 75vw, with 25vw allocated to the submenu. <br>
&emsp;&emsp;&emsp;This animation is implemented using a custom JavaScript function move_div() with the setInterval() method to create a smooth transition. <br>

**4. Right-side Progress Bar Design** <br>
&emsp;When the main content area exceeds the visible browser height, a progress bar appears on the right side, implemented using CSS Animation and JavaScript. <br>
&emsp;The progress bar's animation is controlled by the scroll position of the page, updating in real-time. <br>
