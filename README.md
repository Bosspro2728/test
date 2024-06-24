# test

## Phase 1
- [X] First I wrote the Html structure(I split it into header 4 sections and footer)
- [x] Then i started to write the styles for desktop
- [X] Used grid css for the three images 
- [X] Used flex for the row of images below as well as the header and footer
      
## Phase 2
- [X] I checked the glide js doocumentation and applyed it to the website (I needed the styles and the js files do I used npm to install them, since there weren't many files in the node_modules I did not use a gitignore for it)
- [X] Than I cleanded up my css and also applyed some js to make it look better(like if you click the retail on the header the css clsss will toggle to it)
- [X] than I wrote a script for the number of pictures shown on the carusel based on the width of the screen
      
## Phase 3
- [X] I saw that I would have to remove and add a lot of Html elements when we change the width for mobile so I used media query for fixing the size of the css
- [X] Since I had to remove and add html elements I used a hidden vlass ad using js based on the width applyed it to the proper elements
- [X] I used a mobile and desktop class to destinguish the elements needed on mobile and on desktop(This solution is similar to conditional rendering, it is a little slow but it works, and the time it takes it is barely visible)
- [X] Than I added  eventListener listening to the screen resize and based on the widht adding and removing the hidden class but there was a problem that when the resize event happened, after one two resizes it would show both mobile elements and desktop elements so to fix that  we would have to refresh every time, so we called the function twice to not need reloding and fixes this problem.
- [X] Than I adedd some other media queries beaacuse at a certain width the desktop styles would break. 
- [X] At last I adedd some js for toggeling the elements in the footer(Helping links and Shopping)
