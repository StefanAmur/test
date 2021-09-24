## Requirements

---

### Perfection is not a detail

- [x] All buttons and links work
- [x] All elements work and are complete (menu, lists, images, ...)
- [x] Everything on the page has a function, a reason to be there
- [] No dead links - go to project link goes back to top
- [x] English and dutch are not mixed
- [x] No spelling errors
- [x] No grammar errors
- [x] The website is deployed somewhere
- [x] Everything is relevant (no image of a barber on the website of a baker)

### Content

- [x] Opening hours (if needed)
- [x] Address (if needed)
- [x] Clickable email

### Text life matters aka typography is real

- [x] Some words are bolded
- [] Some words are italic - did not see any italic words
- [x] Some words have a different color
- [x] We aren't using a default font, cause it's not 2004
- [x] Contrast is not too low
- [x] Typographic hierarchy is correct
- [x] Text has a clear intro, middle, conclusion
- [x] Intro, middle, conclusion is style correctly
- [x] Headline font is a headline font
- [x] Body text font is a body text font
- [x] The text on the page has a good flow

### Style

- [] Black is almost black but not #000 - black is #000 in a few cases, especially navbar links, they are rgb 0,0,0,.55
- [] White is almost white but not #fff - white is white in projects page. 
- [x] The website is not an ugly color mess
- [x] The styling is consistent
- [x] It is not four totally different pages thrown together
- [x] Everything works even if you are colorblind

### Not everyone has free 4G aka speed matters

- [x] Pictures are not too heavy - !!good for desktop, not so good for mobile especially 5Mb video
- [x] Pictures are not pixilated

### A company wants to be found/SEO

- [x] All the keywords this company wants to be found on are on the page
- [x] Page has an H1 tag
- [x] Page has keyword meta tags
- [x] Page has a title with the keywords in
- [x] Page loads fast - !!on desktop, not mobile

### Keep your workspace clean

- [x] No unused files in the repo - apart for dstore
- [x] All files have a good, clear name
- [x] Good folder structure
- [x] The CSS folder does not have an image folder
- [x] Not too many files in the root folder

### Git(hub) is what you make it

- [x] All commits use a good comment
- [x] A github description has been filled in
- [x] A github website has been filled in

### Readme but also write me

- [x] The readme says who made it
- [x] The readme says why they made it
- [x] The readme explains what this repo/project is
- [x] The readme links to a preview (screenshot)
- [x] The readme contains a nice image
- [x] The readme has a markdown title
- [x] The readme is divided in sections
- [x] The readme is fun to read
- [x] The readme looks good
- [x] The readme is clear, even for someone that has no idea what is going on

### I'm So Meta, Even This Acronym

- [x] Keywords meta tag
- [x] Description meta tag
- [x] Title of the page is included
- [x] Favicon is included
- [x] Responsive meta tag is included
- [x] Charset is defined
- [x] Author is defined

### Data is the new oil

- [x] Implement (Google) analytics - did not see it

### Perform all the tests

- [x] Lighthouse - !!not too great results for Mobile: Performance, Accessibility  and SEO | Desktop: Accesibility, SEO
- [x] W3C validator - !!validator reports some errors on all pages

### Putting the antics back in semantics (but only for the html)

- [x] The html is semantically correct
- [x] Navigation is in a nav
- [x] Lists use list tags
- [x] H tags are used to signal importance
- [x] No div is used where another element is available
- [x] No span is used where another element is available
- [x] No inline styling is put on any element
- [x] Id's are only used once
- [x] The same 'type' of elements have the same classes
- [] All images have an alt attribute and a title - at least 'works' page doesn't

### Just kidding CSS deserves some love too

- [x] CSS follows the DRY principle
- [x] The CSS does not contain conflicting selectors (multiple definition for the same class/id)
- [x] There is no use of !important where it can be avoided - !!some !important is used but I suspect it's for Bootstrap
- [] The page is responsive - 'about' page is not responsive

### Thermometer goes WHERE???

- [x] Your own style is included after the style of frameworks
- [x] Script tags are put at the end of the body or in the head with async/defer if possible

### Errors are to be avoided

- [x] No http resources are used on an https website
- [x] The console shows no errors
