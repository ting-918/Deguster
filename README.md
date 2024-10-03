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
&emsp;&emsp;&emsp; Additionally, the logo uses several \<span\> to create an effect where each letter animates individually with<br> 
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
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; animation to progress based on the scroll bar's position. <br>
&emsp;• **JavaScript** : We listens to the scrolling event within the content area, calculating and updating the reading <br>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; progress percentage in real time as the user scrolls. <br>
<div align="center"><img src="assets(md)/right-side%20progress%20bar.png" width="50%"></div>

# Function Description
**1. Homepage Carousel** <br>
The homepage features an interactive carousel displaying popular content such as the world overview, the top-ten trending desserts of the week, and daily recommendations. <br>
<div align="center"><img src="assets(md)/Homepage%20Carousel.png" width="50%"></div><br>

**2. Desserts Map Overview** <br>
This page provides users with a visual world map, allowing them to conveniently and quickly explore desserts from each area. <br>
When users hover over a specific continent, the icon of classic desserts in this area will appear. By clicking on it, users are directed to the relevant page to find more details.<br>
<div align="center"><img src="assets(md)/hover%20over%20desserts%20map.png" width="50%"></div><br>

**3. Browsing and Favorites List** <br>
After selecting a dessert from the map or side menu, users are taken to a list-style page showcasing each dessert with its title, introduction, favorite button (star icon), and post button (red landmark icon). <br>
<div align="center"><img src="assets(md)/listp.png" width="50%"></div><br>

**4. Post Creation** <br>
Users can create posts related to specific desserts by clicking on the post button in the list. The popup window allows users to edit the post content, select tags, and upload images, providing a user-friendly interface for content creation. <br>
<div align="center"><img src="assets(md)/Post%20Creation.png" width="50%"></div><br>

**5. Post Management**  <br>
The "Memories" module enables users to manage previously published posts, including viewing comments and likes from other users. <br> 
It also includes a feature for deleting the post with a confirmation prompt to prevent accidental deletions. <br>
<div align="center"><img src="assets(md)/Post%20Management.png" width="50%"></div><br>

**6. Community Interaction**  <br>
The "Community" module serves as a platform for dessert enthusiasts worldwide to share posts, engage in comments, and like each other’s content, fostering interaction and enhancing the social aspect of the website. <br>
<div align="center"><img src="assets(md)/Community%20Interaction.png" width="50%"></div><br>

**7. Account Management**  <br>
This module allows users to conveniently modify their personal account information, including profile picture, username, account details, and password. Additionally, users can log out and return to the login page through this module. <br>


