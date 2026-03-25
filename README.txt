HTML Presentation Template
==========================

Files in this package
---------------------
- presentation_template.html
- slide_starter_block.html
- kfold_kernel_cv_demo_fit_button.html  (example embedded demo)

How to use
----------
1. Keep the files in the same folder.
2. Open presentation_template.html in a browser.
3. Duplicate an entire <section class="slide">...</section> block to add a slide.
4. Paste your slide HTML into the marked "SLIDE BODY START / END" area.
5. For optional reference links, add them inside the hidden .slide-references block.
   They only appear if the viewer clicks the References button or presses R.
6. To embed a full external demo, add an iframe slide and set iframe src to another HTML file.
7. For a small self-contained demo, paste the HTML inside the inline demo box area.

Keyboard controls
-----------------
- Right arrow or Space: next slide
- Left arrow: previous slide
- Home / End: first / last slide
- T: open slide list
- R: open references for current slide
- F: fullscreen
- Esc: close the drawers

Notes
-----
- The included presentation already contains an example slide that embeds the k-fold demo.
- If you move the presentation file somewhere else, move the demo HTML files with it too,
  or update the iframe src paths.
