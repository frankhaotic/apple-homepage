# Apple Kanban Breakdown


## Why the Apple Homepage?

Large company who would diligently make sure that the developers were following the design that they were accurately. I thought that this was a good standard to aim for, and something that it would be valuable for an employer to know that I cared about and that I could achieve.

Because they're a technology company, I thought that they would find it in their interests to have a well-designed website, and so I wanted to know what it felt like to code a good website - there's this great anecdote about... Joan Didion maybe... who rewrote Fitzgerald or Hemingway etc. so that they could feel what it was like to write a masterpiece.

---

## Considerations

The layout and decoration of the page is fundamentally different depending on the screen-size of the device accessing it.

Beyond the layout changing, there are also a number of changes to the size of the elements on the page as we move through different screen sizes, which will optimise the viewing experience for the user depending on specific size of the viewport, and not just the broad size-range that it falls into.

---

## Site Overview

- Header
    - Navbar
        - Links
            - Link Functionality
                - Hamburger
        - Blur Effect on Navbar
    - CONFLICT Under-Navbar Message
- Main Content
    - Products
        - Primary 3 Products
            - Grid (3 x 1)
        - Secondary 6 Products
            - Mobile (6 x 1)
            - Tablet & Desktop (3 x 2)
        - Text Overlays on all Products
        - Product Images/Src
            - Changing Images as function of screen size
- Footer
    - Legal text
    - Links to Services
        - (Mobile) Dropdown menus under headers
        - (Desktop) Lists of services under headers
    - Copyright text and general logistical links
- List of Animations
    - Header
        - (Mobile) Hamburger
            - Activation
                - '=' hamburger icon changes into an 'X'
                - Dropdown spans the whole screen
                    - The colour of the navbar fades into a darker colour
                        - By the time the dropdown list appears, it's already the final colour of the navbar
                - The cart icon fades into background downwards
                - The items in the dropdown, including the searchbar, increase in height as the dropdown animation progresses
                - Searchbar
                    - Activation
                        - 'X' icon and Apple icon move upwards and shrink slightly
                        - Right side of searchbar decreases in length from the right hand side
                            - Cancel button appears in the space made (Bug)
                        - List items fade out quickly
                        - "quick links" quickly fade in from the top - they move downwards
                    - Deactivation
                        - Cancel button disappears
                        - 'X' and Apple icon come back down
                        - Searchbar increases in size to the right
                        - "Quick links" fades up and out
                        - List of Items fades in from bottom
            - Deactivation
                - The 'X' changes back into a '='
                - The bottom of the dropdown folds back upwards
                - The items in the dropdown list decrease in height as the list is folding back upwards
                - The original navbar colour begins to change the lighter dark colour when the dropdown fold reaches the line beneath the searchbar
        - (Desktop) Searchbar
            - Activation
                - Navbar icons get smaller and vanish into the navbar from right-to-left
                - Dropdown containing "quick links" appears in place
                    - The "quick links" themselves slide into place from right
                - Searchbar appears
                    - Rest of the screen/background dims subtly
                    - 'X' appears slightly to right of its final place
                    - <Mag glass icon, "Search apple.com"> slides into place from the right of where it finally ends up
            - Deactivation
                - Dropdown fades away subtly
                - Searchbar disappears
                    - Rest of screen brightens subtly
                - Icons on navbar subtly fade back into, from left-to-right this time
        - Cart
            - (Desktop)
                - Small, dropdown - rounded edges. Drops immediately
            - (Mobile)
                - Navbar fades into a darker black
                    - Not quite as dark as the Hamburger dropdown menu
                - Loading symbol shows up while the cart is being checked for items
                - Dropdown that takes up half of the screen height
    - Main
        - <None>
    - Footer
        - Dropdown Menus
            - Activation
                - '+' icon rotates into an 'x'
                - List slowly unfolds
            - Deactivation
                - 'x' rotates back to '+'
                - List folds up immediately
