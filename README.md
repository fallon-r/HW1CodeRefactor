# HW1CodeRefactor

This Readme contains some of the changes made. I have been periodically pushing things to the repo, but the readme will contain more info. 

1. First thing is the obvious thing: title. The title was website. It is now named after this company.
2. The Second thing I did was remove extraneous divs. A lot of them had the semantic as the class. These were removed, and the CSS was adjusted accordingly.  One such example: 
    ```
   <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
    <div>
    ``` Some of them were in devs, but were not necessarily semantic , like the unordered list in the header not being a nav.
    Content was swapped for article etc. 
3. The third thing, the hero image was nested in an unnecessary div. 
3. The Third thing I did was add alt text to all of the images. This was done with the help of an FOSS applet developed by the [Social Security agency](https://www.ssa.gov/accessibility/andi/help/install.html)
