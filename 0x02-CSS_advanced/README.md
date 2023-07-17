# ADVANCED CSS

## This folder looks into the following concepts
- Selectors, properties and values
- The difference between block and inline styling
- Ensuring consistency across all browsers
- Difference between inline, embeded and external CSS
- How grid system works
- Difference between icons webfonts and SVG icons
- Difference between pseudo-classes and pseudo-elements
- Making background gradients
- Animating elements in CSS
- Transforming (2d, 3d) elements
- Vendor prefixes

## Here are the questions
0. The description of the project contains some inspiration for the final look of the project but we’ll have to download some images.

Head to unsplash and download 10 high resolution images that look as close to the final product that you’re going to make. You will be using these same high res images for a project on Responsive Design in the future. Remember to also include the 3 images (the 2 logos and the favicon) linked in the description of the project.

The images should all be representative of category they belong to. Images in the work category should be closely related to work.

1. When scrolling is triggered on the html element itself, we’d like the behavior of the scroll to be as fluid as possible.

2. Based on styles/1-style.css, create the following declarations:

    - For the body, set the foreground color value to #161616
    - For all anchor elements, set the foreground color value to #161616
    - All elements with the class visually-hidden should have their display to none
    - All elements with the class card-category, should have their foreground color set to #D73953
    - All elements with the class section-tagline should have their foreground color set to #D73953

3. Based on styles/2-style.css:

    -Target the root element and define the following custom properties:
        - color-primary set to #d73953
        - color-black set to #090909
        - color-white set to #ffffff
        - color-light-grey set to #f3f3f3
        - color-dark-grey set to #353535
        - text-color set to color-black
    - Revisit the section-tagline and card-category declarations and reset their color to color-primary
    - Revisit the body and anchor declarations and reset their color to text-color
__Does not have to pass w3c__