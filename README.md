# Déguster (Desserts Map)
• Déguster is an original idea for a website revolving around **desserts**, designed for knowledge propagation, <br>
&ensp; &nbsp;interaction, and social sharing among dessert lovers worldwide. <br>
• Here, we emphasize how to creatively use HTML, CSS, and JavaScript for the UI design of Déguster.<br>

# Website Layout Design
**1. Top Navigation Bar Design** <br>
&emsp;The top navigation bar is encapsulated in a CSS custom class menu_bar, with a total width of 100vw and height <br>
&emsp;of 10vh. Namely, it will always occupy 100% of the screen's visible width and 10% of its height, being responsive <br> 
&emsp;to window size. <br>
&emsp;This component includes:<br>
&emsp;&emsp; • An unordered list (\<ul\>) with several embedded anchor links (\<a\>), which facilitate navigation between <br>
&emsp;&emsp;&emsp; different modules of the website.<br>
&emsp;&emsp; • The logo formed by an image (\<img\>) and several spans (\<span\>), positioned on the left to display the <br>
&emsp;&emsp;&emsp; website's name and serve as a trigger for the left-side submenu.<br>
&emsp;&emsp;&emsp; Additionally, the logo uses several /<span/> to create an effect where each letter animates individually with<br> 
&emsp;&emsp;&emsp; a bounce when the mouse hovers over it. <br>

**2. Left-side Submenu Design** <br>
&emsp;We designed a hidden submenu that appears from the left side when the user hovers over the logo. <br>
&emsp;The submenu layout is constructed using an unordered list (\<ul\>) with several embedded anchor links (\<a\>), <br>
&emsp;categorized by region to facilitate navigation to the desired dessert pages.<br>

**3. Main Content Area Design** <br>
&emsp;The main content area has a height set to 90vh and its width adjusts as follows:<br>
&emsp;&emsp; • When the left-side submenu is collapsed, the width is set to 100vw. <br>
&emsp;&emsp; • When the submenu is expanded, the width shrinks to 75vw, with 25vw allocated to the submenu. <br>
&emsp;&emsp;&emsp;This animation is implemented using a custom JavaScript function move_div() with the setInterval() method <br>
&emsp;&emsp;&emsp;to create a smooth transition. <br>

**4. Right-side Progress Bar Design** <br>
&emsp;When the main content exceeds the browser height, a progress bar appears on the right side, animating in  <br>
&emsp;real-time with scroll. <br>
&emsp;This conpenent is implemented using CSS Animation and JavaScript, as follows: <br>
&emsp;• **CSS Animation** : We use the experimental scroll-time value for the animation-timeline property, allowing the <br>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; animation to progress based on the scroll bar's position. <br>
&emsp;• **JavaScript** : We listens to the scrolling event within the content area, calculating and updating the reading <br>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; progress percentage in real time as the user scrolls. <br>
&emsp; <img src="assets(md)/right-side%20progress%20bar.png" width="50%">
