##What is muscle?
Muscle is a responsive CSS Framework that serves a 960 pixel wide 12 column grid by default that flexes up to fit perfect into the 1140 pixel wide threshold. On smaller screens it will make intelligent jumps to adapt to the width of the browser, as well as fit perfectly among the most popular handheld devices.  

Stop being held back by little frameworks that don't carry their own weight; step up and show off your muscles.


##Why was it made?
There is by no means a lack of CSS Frameworks to be found out there, so what makes this one any different?  It's awesome.  You design once, and your work is done.  Muscle works by optimizing the newest technologies and uses media queries to make intelligent jumps that we combined with a little bit of our lazy personalities to create a framework that allows you to spend as little time as possible bringing your design to the web, and ensuring your webpage looks good in every possible viewport. 

##What does it have?
We provide you with a reset and with that we include a base set of minimal typography initializers in which we highly suggest you override, or delete all together depending on your projects needs. 

You have a fancy smart phone? You have a fancy tablet?  You like things to be fancy?  Muscle is fancy; it simply works. Fancy.


##HOW DO I GET STRONG?
The markup

`<div class="container">
    <div class="row">
        <div class="col4">
            <p>Column 1</p>
        </div>
        <div class="col4">
            <p>Column 2</p>
        </div>
        <div class="col4 last">
            <p>Column 3</p>
        </div>
    </div>
    <div class="row">
        <div class="col5 suffix5">
            <p>Column 1 -- Suffix 5</p>
        </div>
        <div class="col3 last">
            <p>Column 2</p>
        </div>
    </div>
    <div class="row">
        <div class="col6">
            <p>Column 6</p>
            <div class="col3 alpha">First nested div</div>
            <div class="col3 omega">Second nested div</div>
        </div>
        <div class="col6 last">
            <p>Column 6</p>
            <div class="col3 alpha">First nested div</div>
            <div class="col3 omega">Second nested div</div>
        </div>
    </div>
    <div class="row">
        <div class="col6 push6">
            <p>This div is actually first in the markup</p>
        </div>
        <div class="col6 pull6">
            <p>As where this div is second</p>
        </div>
    </div>
    <footer class="row bottom">
        <p>That's all folks.  If you have any more questions feel free to contact us at @GoGoGarrett or @VertJustin</p>
    </footer>
</div>`


##What means it?!
**.container**
Is a class that allows the div to expand to the full width of the browser, and has padding on both side to separate the content from the window as it is resized.  This class is ideal for background images or colors that expand beyond the wrapper and span the full width of the browser.  You can use multiple of these on your page to divide the content of your page up into different sections.

**.row**
Is a what you encapsulate your columns within.  It centers them and defines the width as well as add a margin bottom to separate the contents of your rows.  

**.col1, .col2, .col3, .col4, .col5, .col6, .col7, .col7, .col9, .col10, .col11, .col12**
Are the classes for each column.  They are to be used to layout the page in any combination you desire within a row that adds up to be twelve. 

**.prefix1, .prefix2, .prefix3, .prefix4, .prefix5, .prefix6, .prefix7, .prefix8, .prefix9, .prefix10, .prefix11,**
**.suffix1, .suffix2, .suffix3, .suffix4, .suffix5, .suffix6, .suffix7, .suffix8, .suffix9, .suffix10, .suffix11**
These are classes to help you shimmy stuff where you need it.  You can add space before or after and maintain your layout by using these helpers.

**.push1, .push2, .push3, .push4, .push5, .push6, .push7, .push8, .push9, .push10, .push11** 
**.pull1, .pull2, .pull3, .pull4, .pull5, .pull6, .pull7, .pull8, .pull9, .pull10, .pull11**
These are classes to help you rearrange positions of elements regardless of where they lie in the markup.  They use relative and left positioning that allows you to push and pull elements to where you see fit. 

**.alpha, .omega**
Are two helper classes that assist you with nesting children divs within parent divs by eliminating margins.  alpha - left margin, and omega - right margin.  

**.last**
The last column within a row needs the class to ensure there is no right margin and that all columns fit within the row 

**.bottom**
This class functions similarly to .last as it is required for the very last row if you want to ensure that it sits flush to the bottom of the page.  It eliminates all margin bottom.
