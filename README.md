# MS1-resub

## Table of Contents

1. [Overview](#overview)

2. [Site Goals](#sitegoals)
    1. [UX Goals](#ux-goals)
    2. [Siteowners Goals](#siteowners-goals)
    3. [User Stories](#user-stories)
    4. [Siteowner Stories](#siteowner-stories)

3. [About the Site](#about-the-site)
    1.[Target Audience](#target-audience)

4. [Code Used](#code-used)
    1. [Frameworks](#frameworks)
    2. [Files Made](#files-made)
  
5. [Design](#design)
    1. [Typography](#typography)
    2. [Colors](#colors)
    3. [Images](#images)

6. [Bugs](#bugs)

7. [Code Features](#code-features)

8. [Features to be Added](#features-to-be-added)

9. [Testing](#testing)
    1. [HTML Validation](#html-validation)
    2. [CSS Validation](#css-validation)
    3. [Python Validation](#python-validation)
    4. [Browser Compatibility](#browser-compatibility)
    5. [Devices Tested On](#devices-tested-on)

10. [Credits](#credits)
     1. [Icons](#icons)
     2. [Imagery](#imagery)
     3. [CSS Framework](#css-framework)
     4. [JQuery Framework](#jquery-framework)



## **Overview**
  - This site was created for MS1 for Code Institute, and is a work of fiction. Any name or place that is used is made up, and any relation to
  any real places is entirely coincidental.
  - The site's name is "Monson Swimming Club"
  - The source code for this site can be found on GitHub [here](https://github.com/AJWest22/MS1-resub).
  - The purpose for this site is to advertise for a successful swimming club in an area called Monson, and entise people to learn to swim as well
  as try to draw already successful swimmers to a new club. 
  - This site draws upon my experiences as a swimmer, and uses similar training elements to clubs I used to swim for and against.


## **Site Goals**

### **UX Goals**

   - Users must be able to find out about the club
   - What type of swimmers the club caters for
   - How many hours the club offers
   - Users can contact the club owners for more information and with any questions they may have.

### **Siteowner's Goals**

   - Provide information on a swimming club, like its achievements, its ambitions, and timetables.
   - Ensure it is user friendly, and easy to use
   - Ensure the site leaves the user feeling positive after interacting with it



  

https://images.pexels.com/photos/863988/pexels-photo-863988.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260


BUGS:

In the navbar sometimes when you click the site jumps but doesn't scroll for some reaosn.

<details><summary>Screenshot of where excess sppacing has come from just below the hero image:</summary>
  <img src="images/excess-spacing.png">
</details>

<details><summary>Screenshot of Performance Squads text can be seen out of its section:</summary> (margin and padding and posiitoning were used to  attempt to correct it)
  <img src="images/squad-text-bug.png">
</details>

<details><summary>Screenshot of Performance Squads text can be seen out of its section:</summary> (margin and padding and posiitoning were used to  attempt to correct it)
  <img src="images/squad-text-bug.png">
</details>

<details><summary>Screenshot of the navbar on mobile prior to bug fix:</summary> (The navbar has moved from it original position along and the container it is in has also been moved I am unsure why this is, as I hadn't touched any code in the header)
  <img src="images/original-spacing-error.png">
</details>

<details><summary>Screenshot of the nav bar after some padding was added and overflow was added</summary>
  <img src="images/partially-fixed--spacing-error.png">
</details>


Toggle menu not centered on mobile: Overflow x and y were used to corect it and margin and padding. As well as align-content: center, and content-align: center on the div, and nav. Using overflow-x and setting it to hidden was the preferred option, as it closed the spacing significantly, however the navar wasn't viewable at all on phones in portrait mode, as it was still to far off screen. So for functionality it was considered best to have the overflow turned on so users could access the menu on portrait mode. 

Instagram not centered in div in footer, not sure why this is, its something to do with the padding mentioned in the #footer h2 in the css on desktop, but it is set to "text-align: center" in both, so should be centered but isn't.

Text not centered on mobile, not sure why this is.

Mention why fitness squads was rmeoved (it was placed below the red squad text and image, z-index, position relative and static where used to try to correct it.)