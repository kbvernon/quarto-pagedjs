
# quarto-pagedjs

<!-- badges: start -->
<!-- badges: end -->

Just trying to get Paged.js working with Quarto's html format. I guess I could put this into an extension, but I don't have time to figure out all the ends and outs of that. Plus, the folks at Quarto are supposedly building out support already, and they're way smarter than I am!  

A couple of things to note: 

1. Would be nice to use `pagedown::chrome_print()` but it keeps hanging on this for reasons that I'm too tired to explore.  
2. There's something weird happening with Chromium's print adding an extra page at the end, so the pdf example is the result of me manually removing that page (in the print settings).  

Example here: [kbvernon.github.io/quarto-pagedjs/](https://kbvernon.github.io/quarto-pagedjs/)