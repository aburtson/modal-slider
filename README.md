#Modal slider

This plugin adds a modal with slider functionality. Each slide of the modal corresponds to a list item on the site.

This can be used as a list of team members or categories, where you'd want to use a modal for more detailed descriptions.

####Dependencies

* jQuery
* Bootstrap (3.3.7+) 
* Slick (slick-carousel) (1.6.0+)
    * To get Slick, run *npm install slick-carousel* in terminal, then include *slick.min.css*, *slick-theme.min.css*, and *slick.min.js* in your gulpfile.
    * Or, use these CDNs:
        * https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.min.css
        * https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick-theme.min.css
        * https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.min.js

####Getting started

1. Verify that the jQuery, Bootstrap, and Slick dependencies are included in the project.
2. Include *modal-selector.js* in your js directory. Make sure it runs after the dependencies in your gulpfile.
3. Include *modal-selector.sass* or *modal-selector.css* in your stylesheets.
4. Open up *modal-selector.html* and copy the code over to your html page.

Refer to *modal-selector_annotated.html* for notes on how to add/remove slides and make other modifications to this plugin.