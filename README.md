# Spotify webapp replica

<p>The assignment was to recreate the Spotify webapp and make it responsive, as the <a href="#ref-image">reference images</a> attached at the bottom of this readme </p>

<p>The goal was to be able to do it using only Html and CSS knowledges, without any JS, libraries, or frameworks.
What I used were instead: 
<ul>
    <li>
        My knowledges of basics html tags.
    </li>
    <li>
        CSS classes, advanced selectors and pseudoselectors.
    </li>
    <li>
        Flexbox.
    </li>
    <li>
        Position absolute and relative.
    </li>
    <li>
        Hover effects
    </li>
    <li>
        Media queries
    </li>
</ul>
 
The original website font is a closed copyright one, so I used Montserrat instead.

I did the project in this way:

<ul>
    <li>
        At first I made the main block structure of the webapp. Understanding how to positionate the header and the main app block and how to make the footer float over all the other parts of the web app. I achieved this goal using vw and vh for dimensioning the elements and giving {overflow-y: scroll;} to the main block of the app, so I would be able to scroll the page and not cover the footer.
    </li>
    <li>
        Secondly I Added the main contents, giving a more defined structure to the main elements.
        I did it always keeping in my mind that some of these elements would change with the viewport width becaming bigger or smaller.
        So I simultaneously made the media queries for m, s, and xs screens.
    </li>
    <li>
        I then made some refinements, adding font styles, weight, colors, margins exc...
    </li>
    <li>
        Finally, after I achieved a good result on copying the reference I added some hover effects, to get a better User Experience.
    </li>
</ul>

</p>

<section id="ref-image">
<h2>Desktop reference</h2>
<img src="https://github.com/EmanuelaPau/html-css-spotifyweb/blob/main/references/spotify-lg.png"></img>

<h2>Low-definition screen reference</h2>
<img src="https://github.com/EmanuelaPau/html-css-spotifyweb/blob/main/references/spotify-md.png"></img>

<h2>Tablet reference</h2>
<img src="https://github.com/EmanuelaPau/html-css-spotifyweb/blob/main/references/spotify-s.png"></img>

<h2>Mobile reference</h2>
<img src="https://github.com/EmanuelaPau/html-css-spotifyweb/blob/main/references/spotify-xs.png"></img>

<h2>Footer behavior reference</h2>
<img src="https://github.com/EmanuelaPau/html-css-spotifyweb/blob/main/references/spotify-height-350.png"></img>

</section>
