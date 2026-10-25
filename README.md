# Deliverable Design-System Specimen Code Defense/Documentation and Tests and Evidence


Code Defense/Documentation 

The intended project context and audience:
    - This website is intended to inform new or prospective ball python owners about basic care for their snake.
The reset strategy and at least two reset decisions:
    - I used box-sizing: border-box so elements could be more easily sized
    - all margins set to 0 to have more control on element spacing
    - I had the font inherit for input, form, and button so that the font matches the main font instead of using the default browsers'.
The purpose of the major token groups and the naming approach:
    - I made tokens for color groups, spacing groups, radius groups, and grid because they're all used multiple times. I also made a token for content justify so I can use it to change the theme. I kept all the token the names simple and easy to understand to make it easier to remember which was which.
The font source, license, available weights/styles, and fallback plan:
    - https://fonts.google.com/specimen/Coiny: Copyright 2015 Marcelo Magalhaes (marcelommp@gmail.com @marcelommp) This Font Software is licensed under the SIL Open Font License, Version 1.1 . This license is available with a FAQ at: https://openfontlicense.org
    - https://fonts.google.com/specimen/Sniglet?preview.script=Latn: Copyright (c) 2008, Haley Fiege (haley@kingdomofawesome.com), Copyright (c) 2012, Brenda Gallo (gbrenda1987@gmail.com), Copyright (c) 2013, Pablo Impallari (www.impallari.com|impallari@gmail.com) This Font Software is licensed under the SIL Open Font License, Version 1.1 . This license is available with a FAQ at: https://openfontlicense.org
    - I didn't use any alternate weights for this specimen. There are two fallback fonts for both the main body font and the header font.
How the alternate theme is scoped without duplicating component rules:
    - I changed the values for some of the color, spacing, radius, and content tokens.
Important accessibility and contrast decisions:
    - I made sure the alt text for the images properly conveys their contents. All interactive elements visually indicate that they are clickable and change upon hover. All background and foreground colors properly contrast.
At least one change made because of testing:
    - I had originally made a nav for this page but I took it out as it seemed unnecessary for a page of this length and it was having issues displaying properly at 320px.
Meaningful AI assistance and how it was verified:
    - No generative AI was used.


Required Tests and Evidence

320px test
    - Expected result: for all elements to dynamically shrink to fit the very small viewport
    - Observed result: Cards didn't shrink past around 350px and overflowed off the screen edge.
    - Revision: Adjusted the card padding and margins to be smaller
    - Observed result after revision: All elements shrunk and fit properly 
    - Evidence: evidence1.png in assets folder
768px test:
    - Expected result: for all elements to dynamically shrink to fit the smaller viewport
    - Observed result: All elements shrunk and fit properly.
    - Revision: none
    - Evidence: evidence2.png in assets folder
1280px test:
    - Expected result: for all elements to dynamically adjust to fit this viewport
    - Observed result: All elements fit properly.
    - Revision: none
    - Evidence: evidence3.png in assets folder
200% browser zoom test: 
    - Expected result: for the text size and images to get bigger, but all elements still fit properly without overflow
    - Observed result: All elements fit properly.
    - Revision: none
    - Evidence: evidence4.png in assets folder
Keyboard navigation test:
    - Expected result: for all interactive elements, such as links and forms, to highlight and interact properly
    - Observed result: All elements interact properly.
    - Revision: none
    - Evidence: evidence5.png in assets folder
Contrast test:
    - Expected result: All elements, in both the standard and alternate themes, are distinct from one another and visually convey their purpose. This includes interactive elements appearing 'clickable' and alt text displaying correctly.
    - Observed result: All interactive elements have visual indicators and alt text correctly displays
    - Revision: none
    - Evidence: evidence6.png in assets folder
Font fallback test:
    - Expected result: After disabling the main fonts, the fallback fonts will be used
    - Observed result: After disabling the main fonts, the fallback fonts were used
    - Revision: none
    - Evidence: evidence7.png in assets folder
Validation:
    - HTML: on first submission there were 3 duplicate ID errors. After fixing this there were no more remaining errors.
    - CSS: No errors were found.
    - Evidence: evidence8.png and evidence9.png in assets folder
Publication:
    - https://hmgroves.github.io/Deliverable-Design-System-Specimen/ 
