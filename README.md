# Deliverable Design-System Specimen

Documentation Requirements
Documentation may appear directly on the specimen page, in the repository README, or in a clearly labeled supporting document. It must explain:

the intended project context and audience;
    - Inform new or prospective ball python owners about basic care for their snake
the reset strategy and at least two reset decisions;
    - Box sizing for better element size, font inherit for input/form/button so that the font matches
the purpose of the major token groups and the naming approach;
    - color groups, spacing groups, radius groups, and grid bc theyre all used multiple times. content justify so i can change the theme. kept the names simple for me to remember when I wanted to use a certain one
the font source, license, available weights/styles, and fallback plan;
    - sourced from google fonts, licence will go here, no alt weights, fallback in place
how the alternate theme is scoped without duplicating component rules;
    - changed the values for some of the color, spacing, radius, and content tokens
important accessibility and contrast decisions;
at least one change made because of testing; and
    - took out the nav as it seemed unecisary for a page that isn't very long and was having issues at 320px
meaningful AI assistance and how it was verified, or the statement 
    - “No generative AI was used.”
Required Tests and Evidence
Record the condition, expected result, observed result, and any resulting revision for each test. Screenshots may support the record, but a screenshot by itself is not a complete test record.

Responsive: Test at 320, 768, and 1280 CSS-pixel viewport widths.
Zoom: Test the page at 200% browser zoom.
Keyboard: Navigate through every link, button, and control without using a mouse.
Contrast: Check essential text, actions, focus indicators, and controls in both themes.
Font fallback: Block, rename, or temporarily remove the preferred font and record what changes.
Validation: Validate the final HTML and CSS and resolve errors caused by your code.
Publication: Open the published URL in a private or signed-out browser window and verify that styles, fonts, media, links, and controls load correctly.