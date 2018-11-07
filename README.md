# Forge UK default WordPress Styles
Boilerplate scss files including WordPress default classes output by the framework which base styling can be added to.

For use inline with the Forge UK WordPress development process

## Usage

* Download or clone the repository
* Strip out and remove specific sheets if they're not required e.g. Widgets, comments
* Remove classes from within the stylesheets that you have no need for.
* Inside of the theme where your file structure is for your other scss files include the classes you require inside of a wordpress directory e.g. `src/styles/wordpress/body-classes.scss`
* Compile these classes first in case of specific use cases which require a higher priority for a style to display

#### Notes
* Don't write specific styles that make any additional markup inflexible e.g. adding a specific body class that doesn't work for all pages, posts, templates that use it.
* Try to imagine this as a WordPress specific reset where by you set general styling properties which will allow content generated dynamically by WordPress to display correctly and in line with the theme
 