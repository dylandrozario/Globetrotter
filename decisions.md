# Globetrotter — Decisions Log

## Milestone 0: Setup and Planning
- Destination chosen: Chicago
- Primary audience: Gen-Z
- One design decision that reflects the destination: using chicagos flag colors as color scheme and its stars as bullets
- Wireframe format used (hand-drawn / Figma / other): hand-drawn

## Milestone 1: HTML Structure
I decided to make the individual cards using the article tag. I made this deicison because article tags are used for content that explains itself. As it is explaing the image in the same row. Also article tag tells the browser, search engines, and screen readers this is one distinct item, which is better for accessibility and SEO.

Claude generated some text that was not the correct naming conventions I was using so I had to change it to match the projects desciprition and  make it concise as it generate the same textual mistake each time. These were present in the nav bar and footer.

One place where the wire frame was used was for the main content part of the pages. You can see this in the alternating image and description design I made. Where you either have an image card on one side and the textual card on the other side of the same row. This was mirroed from my wire frame.

## Milestone 2: CSS Styling
One color or font choice you made, and why it serves your destination.
I decided to use the colors of red, light blue and white on my page as those are the colors of the chicago flag so my website has a visual connection to the city

One Claude suggestion you rejected, and why.
One claude suggestion I rejected was a glow hover effect over my cards and I rejected it because I found it did not fit in the asethetic of my website and the cohesion as well.

One style that didn't look right at first, and what you changed.
One style that did not look right at first was the header as the overlaying text was not aligned in the center and the dimensions of the background image did not look right, so I had to manually fix these issues within the css of the header and header img.

## Milestone 3: Flexbox Layout

One Flexbox property choice you made deliberately, and why.

I  used flex-direction: row-reverse on the --reverse rows so the image/text cards alternate sides without duplicating any markup — it keeps the zig-zag layout from my wireframe.

One place where Claude generated a layout that didn't match your plan, and what you changed.

Claude generated nav/footer labels like "Food & Events" and "PhotoGallery" that didn't match my naming, and it filled the homepage cards with attraction content. I changed the labels to Top Attractions / Food Guide / Photo Gallery and swapped the homepage cards related to first-timer info.

One layout challenge that required adjusting your HTML structure, and why.

To overlay text on the hero image, I had to wrap the heading, subtitle, and button in a separate .hero-overlay div inside the <header>, because Flexbox/positioning needs a dedicated container to center the text on top of the image rather than letting it stack below.

## Milestone 4: Responsive Design
_Add entries after implementing media queries._

## Stretch Features
_Add entries if you implement any stretch features.