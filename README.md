# HTML / CSS Project

This was a take home exercise to develop a front end page from a design template.

I used flexbox for a bit of responsive legwork, and tested cross browser (besides lower IE versions, 10 and below).

Improvements I would make to a production version would be:
- Vectorize the graphics, consider svg sprites if performance is a focus
- I put styles in the header for ease of development, but of course, I'd probably split that off and minify
- I was coding on the fly, referencing the source for pixel / color / size and all those details, so the definitions are a bit fragmented.  In a more formal setting, I would define some general standards for fonts and sections, for more modularity and reusability (headers, links, generalize the form / input / button definitions, main body layout are a few off the top of my head).
- Font sizes, I should have probably used rems instead of ems
- Of course the file upload buttons will have to have js magic so as to trigger file browse and not submit form
