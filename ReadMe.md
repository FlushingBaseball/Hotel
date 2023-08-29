## clear out default margin and padding
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

## background considerations
background #333 url('https://source.unsplash.com/daily)
no-repeat center center/cover



Responsive Design
## em
em is relatvie to the font size of its parent container, theres some weird edge cases which
make them less usefull

## rem
rem is relative to the root html element 

a common practice is to set the

html {
    font-size: 10px;
}
so you know what your multiplisties are instead of doing mental math based on the default which is 16px

its great for assessibility! 

## links
by default links are inline

## MEDIA QUERIES

you can conditionally load a different css file based on a media query but it should be below the main css link in html
<link rel="stylesheet" media="screen and (max-width:768px)" href="mobile.css">


so this would make everything red on screens up to 500px wide
most smart phones are below 500px wide

@media(max-width: 500px) {
    body{
    background: red;

    }
}

tablets are around 768 px

@media(min-width: 501px) and (max-width: 768px) {
    body{
    background: red;

    }
}

@media(min-width: 769px) and (max-width: 1200px) {
    body{
    background: red;

    }
}

super wide
@media(min-width: 12o1px) {
    body{
    background: red;

    }
}



## Important factors
Viewport, fludi widths as oppose to fixed
media queries, different css styling for different screen sizes

## rem over px
Font size

# ctrl - d  
highlight next instance
lorem
. and #

## mobile first method  
less content on mobile devices? 


 # images
 images are by default displayed inline, so change them to block
 make them 100% of their container? 

## utility classes
Are css classes you make so you can use anywhere

like container, or text-primary



# border box
if you set things to border box then padding wont add to the width