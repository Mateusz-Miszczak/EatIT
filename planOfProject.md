# EatIT

## Assumptions

Knowledge consolidation:

    - Fundamentals of modern and semantic HTML and CSS
    - Building layouts with CSS Grid and Flexbox
    - Creating well-established website components
    - Respecting the principles of responsive design
    - Website: Planning, sketching, designing, building, testing, optimizing and launching
    - Fixing errors by reading documentation
    - Using web development tools

Responsive design assumptions:

    1. Fluid layouts:
        - To allow webpage to adapt to the current viewport width ( or even height)
        - Use % ( or vh/ vw) unit instead of px for elements
        - Use max-width instead of width

    2. Responsive units:
        - Use rem unit instead of px for most lengths
        - To make it easy to scale the entire layout down ( or up) automatically
        - Helpful trick: setting 1rem to 10px for easy calculations

    3. Flexible images:
        - By default, images don't scale automatically as I change the viewport so I need to fix that
        - Always use % for image dimensions together with the max-width property

    4. Media queries:
        - Bring responsive sites to life
        - To change CSS styles on certain viewport widths ( called breakpoints)
        - WITHOUT 1, 2 and 3 above they are complitely useless

### Tasks:

Header:

    - Logo as img
    - Nav bar

Hero section:

    1st column:

    - The biggest header on a webpage
    - Some description
    - Buttons
    - Images with clients
    - Number of delivered meals description

    2nd column:

    - 2 to 4 images one on another with food/ people eating

Featured section:

    - Images of the biggest featured in companies that use this website

How it works section:

    - Create headings
    - Z pattern with description and img

Meals section:

    - Create smaller and bit bigger header
    - Create 2 to 4 carts of products/ diets with images

Testimonial section:

    - Blocks with img, description and blockquote of a person
    - Create gallery of food photos

Pricing section:

    - 2 or 3 carts with pricings and distinctive styling for the best offer

Features section:

    - Description of features in few columns

Call to action section:

    - Create section that user will be able to put in data into forms

Footer:

    - Create footer using CSS Grid
    - Each column should have different links that guide to other section of page or to other website
