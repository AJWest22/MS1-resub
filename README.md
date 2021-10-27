# MS1-resub


https://images.pexels.com/photos/863988/pexels-photo-863988.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260


BUGS:
HEADER IMAGE MAY NOT ALWAYS SHOW AND EXCESS SPACING IN HEADER ON MOBILE
<details><summary>Screenshot of header image displaying on the deployed website:</summary>
  <img src="images/header-image-on-deployed.png">
</details>

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