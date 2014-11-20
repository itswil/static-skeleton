Static Skeleton
===============

A file structure for the static files portion of your website.
Saving you 1 minute of your life.


### File structure for CSS, JS and Images
```
static
    css
        lib
            normalize.scss
            slick.css
        src
            // page specific CSS
            about.scss
            contacts.scss
            homepage.scss
            styleguide
                components
                    // styling for visual components ONLY
                    blockquotes.scss
                    flashcard.scss
                    ...
                    popup.scss
                    variables.scss
                styleguide.scss // this just pulls in all the components
    js
        lib
            backbone.js
            jquery.js
            slick.js
            underscore.js
        src
            // page specific JS
            about.js
            contacts.js
            homepage.js
            styleguide
                // JS that is SPECIFIC to visual compponents
                flashcard.js
                popup.js
    img
        homepage
        hosts
        partners
```
