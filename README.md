# horiseon

A refactoring exercise - to reformat an existing webpage with proper semantic html and alt tags to increase accessibility.

I started by consolidating the classes, there was a lot of unneeded repetition as each section was defined as its own class.

I added alt tags to all the images to make the website accessible.

I fixed the links by adding id tags to the articles.

I made a lot of classes no longer classes, but changed them to elements (i.e. < header > tag instead of < div class="header" >, changing generic divs to main, aside, etc.), thereby making the html semantic.

I rearranged the style.css file so the elements/classes fell in the order they would appear in the html file and were grouped together, to make it more readable.


```
GIVEN a webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements  

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title
```

Deployed page can be found at: liztownd.github.io/horiseon