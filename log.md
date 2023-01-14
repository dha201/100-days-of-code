#100 Days Of Code - Log

## Day 2 - December 29, 2022

### Today's Progress:
- focus today was on the ZTM "CSS and Advanced CSS: The Complete Developer's Guide" course
- Walked through and refresh on the basics on CSS: 
  > Selector, Properties, how to use IMG and text/fonts elements, Box Model, px vs rem vs rem

### Thoughts:
- So far, everything sticks pretty well. The only thing is that there are so many selector and attributes out there needed to be learned.
- My biggest weakness right now with CSS is understanding how "parents, child" correlate with each other.

### Link to Work:
- not going to bother pushing the project work from the course out to GitHub.  I'll reserve that for when I make something unique that leverages what I've learned. 
- Link to CSS cheatsheet: https://htmlcheatsheet.com/css/
- Link to CSS Flexbox Cheatsheeet: https://darekkay.com/flexbox-cheatsheet/

---

# Day 3 - December 30, 2022

## Today's Progress:
  (The Complete Developer's Guide" course)<br>
  ✅Flexbox<br>
  ✅CSS Transitions and Transforms<br>
  
### __What are the advantages of using flex ?__ 
    > The reason why you would want to use flexbox is to *lay out the collection of items in one direction or another*. when you lay out the items, you might want to use flexbox to control the spacing between the items, as well as the dimension of the items. 
  
### __What are the pros and cons of flexbox ?__
    -Elements can be compressed and stretched according to specified rules, occupying the necessary space.
    -Aligning vertically and horizontally, the baseline of the text works great.
    -The location of elements in html is not critical. It can be changed in CSS. This is especially important for some aspects of responsive layout.
    -Elements can be automatically lined up in several rows / columns, taking up all the space provided.
    -Many languages in the world use right-to-left spelling rtl (right-to-left), in contrast to the usual ltr (left-to-right). Flexbox is adapted for this. It has a concept of beginning and end, not right and left. Those. in browsers with the rtl locale, all elements will be automatically arranged in reverse order.
    -The syntax of CSS rules is very simple and is learned quite quickly.


### Thoughts:
- [x] Practice css selector
- Why use Flexbox over other layout methods like Grid?

### Link to Work/Resources:
- [link for FLexbox cheatsheet](https://darekkay.com/flexbox-cheatsheet/)
- [link for CSS Transitions and Transforms](https://thoughtbot.com/blog/transitions-and-transforms)
- [A demo for how transitions and transform work](https://codepen.io/david1ha/pen/XWBdOwr)


-----

# Day 4 - January 4, 2023

## Today's Progress:
  (The Complete Developer's Guide" course)<br>
  ✅Bootstrap + exercise (Start-Up page) <br>
  ✅Bootstrap Grid <br>
  ✅How to create an email campaign landing page w/ Mailchimp
  ✅How to publish your website online w/ Github
### Thoughts:
- So far, Bootstrap seems like a very useful library, especially for creating a website in a timely manner. There are a lot of tools and utilities in there that I was able to test around in the project like Grid, Flex, Button and special hover before and after effects. However, tbh I still had a difficult time with figuring out how to align all the contents. I'm not sure if this was due to me missing some part from the tutorial or the new updated version of Bootstrap requires different methods to align some elements like a line breaker. Which, I had to include some extra utilities and element that wasn't a part of the tutorial. Otherwise, everything went pretty smoothly, I was able to add some additional features, but nothing to brag about.


-----

# Day 5- January 5-6, 2023

## Today's Progress:
  (The Complete Developer's Guide" course)<br>
  ✅Personal Project (Landing page for a donut shop)
### Thoughts:
- In this project, I learned much more about how to use CSS and the grid/column features from bootstrap. As well as learning how to research and find solutions without having to ask anyone for help.
- When runnning into a problem, I would first, search what I can find on google especially stackoverflow. If that wouldn't work, I would go onto websites that I know that has a similar layout as what I try to replicate. Then just inspect the codes from it, more like copy and paste, but it works.
- Things I learned regarding coding knowledges:
1. Use __(transform: translate();)__ to move an img on the plane
2. How to hover over one element and affect a different element by 
 
   >If the cube is directly inside the container:
    #container:hover > #cube { background-color: yellow; }

   >If cube is next to (after containers closing tag) the container:
    #container:hover + #cube { background-color: yellow; }

   >If the cube is somewhere inside the container:
    #container:hover #cube { background-color: yellow; }

   >If the cube is a sibling of the container:
    #container:hover ~ #cube { background-color: yellow; }

### Link to Work/Resources:

-----

# Day 6- January 9, 2023

## Today's Progress:
  (The Complete Developer's Guide" course  20% -> 26% )<br>
  ✅CSS Grid + Layout
### Thoughts:
This section seems pretty simple and straight forward. The practice example that was given in this section was lowkey difficult as first, but I slowly got the hang of it. 

Things I learn today:
- How to create columns and rows through the use of grid and its templates, as well as aligning items with align-items and justify-contents. 
- Comparing Flexbox to the Grid system. It seems that grid is much more flexible and has better ultilities compare to flex. With grid, you can quickly create the layout and then place items into it. As well as aligning the contents much faster and more efficient compare to other methods. What better about it as well is the responsive factors that come from using it. 

-----

# Day 7->8- January 10-11, 2023

## Today's Progress:
  (The Complete Developer's Guide" course  20% -> 26% )<br>
  ✅CSS Grid + Layout Project
### Thoughts:
Trying to replicate the website within the project wasn't so bad as I thought it would be. However, I did run into a couple of problems such as:
#### Nav Bar:
- How to get rid of the white space around the containers. 
> The solution to this was setting the margin = 0 . By doing this, It will set all the containers margin to the default setting. 

- I forgot that when create a nav bar, you should use the listing atrribute for the different sections such as About page, Home, Service, Contact, etc. 
- Also with creating the nav-bar, I discovered 2 things:
- "@media only screen and (max-width: 600px)" allows you to create different layouts depending on the size of the viewport, but they can also be used to detect other things about the environment your site is running. The @media query, it is super helpful when it comes to making a responsive website, it's almost an essentials for any websites. The reason is that with this atrribute, you can reduce the dimension or switch device and the website would auto adjust to the dimension that you set to.
-  "margin-left: auto;" allows you auto adjust the margin to the left of an element base on the width of the container.
#### Cover:
-The body section wasn't so hard to replicate, but one new thing I learned was the unit "vh". This unit allows you to set the height automatically base on the viewport. So lets say if the height of the body is set to 100vh, this means that the body would show 100% of the screen size depending on the dimension. 

#### Blue Zone:
This was definitely the hardest part of all. However, there are three biggest things that I took out of it
1) {grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    grid-gap: 20px;} With this 2 lines of codes, you can easily create a box layout within a container nicely. The best thing about it too is that it's responsive. 
2) .box {
    background-color: black;
    padding: 130px;
    margin: 20px;
}
 img {
    width: 100%;
}
As you can see here, the width of the img is 100%, which means it would take up the entire space within the parent container. But the reason it is nicely stay within the black box is from the correct padding and margin that were created around it. So the img would adjust to the padding and margin instead of the entire width of the box. 


-----

# Day 9- January 12, 2023

## Today's Progress:
  (The Complete Developer's Guide" course  20% -> 26% )<br>
  ✅CSS Grid + Layout Project
### Thoughts:
Things I learned:
- Sticky nav bar
> .sticky { position: fixed: ( keep in mind this might change the width of your container or element)
            top: 0;
            width:100%
            }
