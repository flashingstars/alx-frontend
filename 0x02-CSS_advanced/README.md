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

    - Head to unsplash and download 10 high resolution images that look as close to the final product that you’re going to make. You will be using these same high res images for a project on Responsive Design in the future. Remember to also include the 3 images (the 2 logos and the favicon) linked in the description of the project.

    - The images should all be representative of category they belong to. Images in the work category should be closely related to work.

1. When scrolling is triggered on the html element itself, we’d like the behavior of the scroll to be as fluid as possible.

2. Based on _styles/1-style.css_, create the following declarations:

- For the body, set the foreground color value to #161616

- For all anchor elements, set the foreground color value to #161616

- All elements with the class visually-hidden should have their display to none

- All elements with the class card-category, should have their foreground color set to #D73953

- All elements with the class section-tagline should have their foreground color set to #D73953

3. Based on _styles/2-style.css_:

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

4. Based on _styles/3-style.css_:

- Targeting the root element, create 2 custom font-family properties font-family-base and font-family-title with the same list of fonts:

    - set the first choice font as Helvetica Neue

    - set the second choice font as Helvetica

    - set the third choice font as Arial

    - set the last choice font as sans-serif

    - Set body‘s font-family to font-family-base
        
- Create a new declaration targeting all 6 levels of section headings, positioned before the links declaration

    - set its font-family to font-family-title

__Does not need to pass W3C__

5. Based on _styles/4-style.css_:

- Targeting the root selector, create the following custom properties:
    - font-size-small set to 1.2rem

    - font-size-medium set to 1.6rem

    - font-size-large set to 1.8rem

    - font-size-x-large set to 2.3rem

    - font-size-xx-large set to 4.8rem

- All fonts in the html element should be at 62.5% of their normal size

- Any fonts in the body should have their sizes set to font-size-medium

__Does not need to pass W3C__