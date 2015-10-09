# Frontend Exercise
In this exercise you will have build a responsive site navigation.

## Here are the guidelines for this exercise
* It must be developed using only css, js & HTML 5.
* No frameworks or libraries (e.g. Bootstrap, jQuery, Angular, React...).
* Nav menu must be responsive.

### Nice to haves:
* The code must be clear and legible.
* Documentation.

## Design Specifications
The site will have two main states, Desktop and Mobile; these will be shown in the folder wireframes, any detail about measurements, colors or actions that no be especificate in wireframes or below, should be asumed.

##### General
* The background must be fixed in center of screen, cover all content, and it should not be deformed on screen resize.
* The background should have a slight translucent mask, that allow visualize better all texts.
* On hover, active or focus, all buttons or links in nav menu will change clearly his state.
* On click, if item menu contains a URL, the browser will navigate to a new page.
* Facebook & linkedIn buttons don't have events associated.
* On click in register button, the field inputs will validate and his state should change clearly if have error.
* On click in nav item with sub-menu, sub-menu will appear below.
* Only one sub-menu will appear at time, if other sub-menu is active, should be hide.
* When a submenu is displayed or hidden, arrow icon should rotate with ease animation 180 degrees.

##### Desktop (> 768px)
* The nav menu will display as a horizontal nav. Nav items will display sub-nav items when clicked. No hamburger will be shown.
* If a sub-menu is active, on click outside should be hidden.

#### Mobile (<=767px)
* Nav menu will disappear and hamburger icon will display in the top-right of the page; clicking the hamburguer will cause appear a responsive nav menu.
* When responsive nav menu appear:
    * The menu should “pull” from right to left with ease animation all content.
    * Translucent mask appears over content.
    * On click in translucent mask or close button in responsive menu, should "pull" from left to right with ease animation all content, and the translucent mask should be hidden.