# Amazon-webpage


Hosted Link:-  https://lok-ii.github.io/Amazon-webpage/


![Screenshot 2023-08-20 180713](https://github.com/Lok-ii/Amazon-webpage/assets/129180844/aff59d50-220f-40d1-b60d-50a11f04cd27)
![Screenshot 2023-08-20 180721](https://github.com/Lok-ii/Amazon-webpage/assets/129180844/4a2d7e9b-a2ef-4a21-97e6-28d2107349a9)

    Header Section:

        The <header> element represents the header section of the webpage.
        It encapsulates the navigation menu and other header-related content.
        Within the <header>, the navigation structure is defined using a <nav> element.
        Navigation items are created using <a> elements, making them clickable links.
        The Amazon logo is visually presented using an <img> tag with its src attribute pointing to the Amazon logo image file.
        The "Deliver" link is created as an <a> element with the class deliver for styling.
        The delivery location and country icon are included using Google Fonts' Material Icons, presented as an <i> element with the class material-icons place.
        The search functionality is implemented through a <form> element that consists of:
        A <select> dropdown providing various categories.
        An <input> field for users to input search queries.
        A <button> element that allows users to submit their search.
        The "Hello, Sign In" and "Returns & Orders" links are created using <a> tags.
        The shopping cart link is represented using an <a> element with an icon from Material Icons for visual indication.
    
    CSS for Header:
        
        The header selector targets the <header> element.
        A minimum width and background color are set for the header section.
        The nav selector is used to style the navigation container:
        Flexbox (display: flex) is employed for flexible layout behavior.
        Alignment and spacing are configured using properties like justify-content and align-items.
        The Amazon logo (img) is adjusted with margin and width properties to ensure spacing and sizing.
        The "Deliver" link with class deliver is designed to appear as a column flex container:
        This arrangement stacks the content vertically within the link.
        The delivery country icon is positioned using padding and a span for text:
        This creates visual separation between the icon and the text content.
        The search form (form) is configured as a flex container:
        Flex properties dictate alignment and width behavior.
        Styling for dropdown (select) and input (input) elements includes padding and border settings for consistent appearance.
        The search button (button) is styled with a background color and no border for clarity.
        Properties like color, font-size, and font-weight are used to control text and icon colors for a cohesive design.


![Screenshot 2023-08-20 180729](https://github.com/Lok-ii/Amazon-webpage/assets/129180844/b1390578-8561-4c5c-9902-d62b784ea752)

    Prime Day Section:

        The .prime-day section represents a dedicated space for the Prime Day event.
        It utilizes a background image to enhance visual appeal and branding.
        The section's height is defined using the height property.
        The background image's positioning and size are controlled through CSS.


![Screenshot 2023-08-20 180740](https://github.com/Lok-ii/Amazon-webpage/assets/129180844/b4ff144e-6b13-46d3-ab1f-8f0e46127420)

    Shop Now Section:
        
        The .shop-now section serves as a container for the "Shop Now" items.
        Flexbox (display: flex) is utilized to manage the layout.
        .shop-items contains individual .shop elements, representing shop items.
        Each .shop encompasses the following components:
            A heading (<h3>) describing the product.
            An image (<img>) showcasing the product.
            A "Shop Now" link (<a>) that guides users to the product page.
        
    CSS: 
        
        Layout is achieved through flex properties, such as justify-content and align-items.
        Media queries are employed to ensure responsiveness and adapt to different screen sizes.
        Hover pseudo property is also used on the .shop container to enlarge it a little bit when the cursor is moved on it.




![Screenshot 2023-08-20 180748](https://github.com/Lok-ii/Amazon-webpage/assets/129180844/055bfd6c-d10b-43d3-a0fb-a36ad8cea861)
![Screenshot 2023-08-20 180755](https://github.com/Lok-ii/Amazon-webpage/assets/129180844/ea465c6a-9918-438c-9638-dd2f81169c5c)


    Footer Section:

        The <footer> element is dedicated to footer content.
        .backtotop offers a "Back to top" link, allowing users to navigate back to the top of the page.
        .all-links encompasses several .about sections that provide various sets of links.
        Each .about section is comprised of:
        A heading (<h4>) indicating the section's purpose.
        An unordered list (<ul>) containing individual links (<li>) within anchor tags (<a>).
        Footer links are styled with colors, font sizes, and text decorations to match the overall design.
    
    CSS for Footer:
    
        .backtotop is styled with a background color and center-aligned content.
        Links within .backtotop are colored and have no text decoration.
        .all-links contains all .about sections, with space evenly distributed:
        This section aligns links in a uniform manner.
        .about sections are styled for layout and alignment consistency.
        Links within .about sections are styled with font sizes and colors to match the theme.
        Hover pseudo property is also used on all the hyperlink in the lists to change it's text decoration to 'underline' when the cursor is moved on it.
    
    
    



