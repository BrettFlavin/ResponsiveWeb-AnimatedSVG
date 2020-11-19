<!--------------------->
<!-- PROJECT SHIELDS -->
<!--------------------->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]

<!-------------------------->
<!-- PROJECT HEADING/LOGO -->
<!-------------------------->
<br />
  <h1 align="center">Animated SVG using CSS</h1>
  <h3 align="center">README</h3>
  <p align="center">    
    <a href="https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG/issues">Report Bug</a>
    ·
    <a href="https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG/issues">Request Feature</a>
  </p>

<!----------------------->
<!-- TABLE OF CONTENTS -->
<!----------------------->

## Table of Contents

- [About the Project](#about-the-project)
- [Built With](#built-with)
- [Usage](#usage)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!----------------------->
<!-- ABOUT THE PROJECT -->
<!----------------------->

## About The Project

This just started off as a joke, but the intent was to learn more about responsive web design, CSS, and animations in particular.

To do this, I first located an open-source illustration and downloaded it as an SVG. Next, I took this SVG image and opened it up in Figma where changes can be made to the individual shapes, paths, colors, etc that make up the image. After making changes, group together and name the sections of the SVG to be animated with CSS, and export the file from Figma as an SVG. In Figma, you must ensure to click the checkbox 'include id attribute' before exporting the SVG. Now, each section of the image has an id tag that can be accessed with CSS and animated.

After the SVG is copied into the project folder and opened in VS code, you can see all the path and fill information that makes up the SVG image, and also the ids created in Figma. Copy/Paste all of this and embed it directly into the HTML file with the inline svg tag. The different paths of the image can now be accessed and animated by the CSS through their unique ids. 

The animation I created simply moves the saucer down onto the page when it's loaded, and then fades the opacity properties of the top saucer lights and it's bottom green lights back and forth from 0 to 1 in an infinite loop, which gives the twinkling effect. The top saucer dome and the front of the saucer also have unique ids for animation although they were not used here.

<!---------------->
<!-- BUILT WITH -->
<!---------------->

### Built With

This application was created in VS Code using HTML and CSS. The alien image was found online and edited using Figma. A CDN was used to import the font awesome reddit alien icon. This project was created in the style of a landing-page or single page website and been made responsive for different size devices.

Some of the techniques I used here include CSS flexbox and grid, CSS animations, and animation delays to animate individual paths of an SVG image. CSS Media queries were then used to make the page responsive between a laptop and a smaller mobile device.

<!-------------------->
<!-- USAGE EXAMPLES -->
<!-------------------->

## Usage

<h4>the animated SVG image:</h4>

<img src="mars-alien.gif" width="75%">
<br>
<br>

<h4>responsive web design for laptop and mobile devices:</h4>

<img src="mars-alien2.gif" width="70%">
<br>
<br>

<!------------->
<!-- CONTACT -->
<!------------->

## Contact

Author:
<br />
Brett R. Flavin - brettflavin@yahoo.com

Project Link: [https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG](https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG)

<!---------------------->
<!-- ACKNOWLEDGEMENTS -->
<!---------------------->

## Acknowledgements

- [othneildrew - readme template](https://github.com/othneildrew/Best-README-Template)
- [unDraw](https://undraw.co/illustrations)
- [Figma](https://figma.com)
- [Font-Awesome](https://fontawesome.com)

  <!-------------------->
  <!-- MARKDOWN LINKS -->
  <!-------------------->

[contributors-shield]: https://img.shields.io/github/contributors/BrettFlavin/ResponsiveWeb-AnimatedSVG?style=plastic
[contributors-url]: https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/BrettFlavin/ResponsiveWeb-AnimatedSVG?style=plastic
[forks-url]: https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG/network/members
[stars-shield]: https://img.shields.io/github/stars/BrettFlavin/ResponsiveWeb-AnimatedSVG?style=plastic
[stars-url]: https://github.com/BrettFlavin/ResponsiveWeb-AnimatedSVG/stargazers
