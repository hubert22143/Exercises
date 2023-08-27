# Blog? Treat this repository as something I use to say about the things i've learned.
In this repository, I will write the things I've learned, which doesn't contain any html, js, or any other files than txt. <br>

This repository is intented to help me to recap the most informations i've gathered at the end of the day. Though it might not be really helpfull and understandable for you, it is for me. <br>


8/18/2023   5:49PM
<br>
Today I've learned about emmet syntaxes as well as some usefull cheat sites
<br>
https://docs.emmet.io/cheat-sheet/
<br>
https://htmlcheatsheet.com/css/
<br>
I've learned that, we can improve our type speed in html drastically, by using emmet syntaxes. Emmet syntaxes are built-in extension, in the VS code, which allows us
<br>
to create the elements way faster.
<br>
The example for implementation emmet syntaxes is following if we wish to create div, which contains 3 p elements, with their own class:
<br>
syntax > is saying that, the p element is the child of div. So basically the div contains 3 p elements as we wish.
<br>
syntax $ describes the item numbering, from 1 to x
<br>
syntax * describe exactly what you think it's doing, it simply works as multiplier, we want it to contain 3 elements, so we're multyplying by 3.
<br>
div>p.class$*3

<hr>
8/18/2023   6:38
<br>
I've learned some info about what are svg's.
<br>
While I confidently don't know a larger part of what svg's are more in advanced meaning but I surely get them in their basic meaning.
<br>
The svg(Scalable Vector Graphics) itself is scalable image format, which means we can format them as we wish, and they won't lose of their quality.
<br>

SVG's are defined by xmls markup language, which gives us some benefits at the first step. Thankfully to that, they are formated by xml's,
<br>
they are human-readable and machine-readable as well,which means we can understand them, but they are kinda confusing at the first glance.
<br>
The svg format looks like:
<br>
The xmlns is a global format(svg standard rather should I said) for svg files, it let us knows, that basically this is the svg file. The value is the standard formula for the svg.
<br>
In the viewbox we've got four variables following indicating:
<br>
min-x="" dependly of our usage it will shift x units to the right, or to the left if the value is negative,
<br>
min-y="" same as above, it will shift x units, but this time vertically, to the up or bottom if the value is negative,
<br>
max-width="" defining the max width of the created box
<br>
max-height="" same as above, bud the height of created box.
<br>
"<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"></svg>"
<br>
By defining all those values, we are certain that the browsers and software, will correctly understand that the content is svg, and within the box will be created elements
<br>
dependingly of the given viewBox values.
<hr>
<br>
8/19/2023 2:08 PM
<br>
Today I've recapped some basic, but meaningfull things about creating the table in html.
<br>
The syntax for creating table is following:
<br>
This is a basic table structure. The "table" indicates that we are starting and ending the table.
<br>
The "caption" indicates what the table is writting about.
<br>
The "theader" is a thing which helps recognize the structure of table for screen readers even betters, we should indicate it always.
<br>
It also improves the readability and make it more accessible and comprehensible for all users. Overall it is recommended to always include those things in the 
<br>
table html property.
<br>
The thing with `tbody`, and `tfooter` is the same. In `tbody`, we're indicating the main data of our table, the footer is basically the last row in the table. 
<br>
It is also worth to mention, that whenever we apply the `tfooter`, no matter where the table row will sit, it will always be pushed to the down due to tfooter functionality.
<table>
  <caption>Table Caption</caption>
  <thead>
    <tr>
      <th>Column Header 1</th>
     <th>Column Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data Cell 1</td>
      <td>Data Cell 2</td>
    </tr>
    <!-- Additional rows and data cells go here -->
  </tbody>
  <tfoot>
    <tr>
      <td>Footer Cell 1</td>
      <td>Footer Cell 2</td>
   </tr>
  </tfoot>
</table>

<hr>
<br>
8/20/2023 2:26 PM

Today I've learned some about the responsive units.
<br>
It's mostly about using the rem or em to the font-size's of our's body.<br>
By basic, the default font-size on body is 16px(1rem/em === 16px). If you want to care about the user settings, and want your font-size to be responsive on the site then you shall use one of those.<br>
The em units works following: <br>
If we set font-size on the parent for 1em, the child will get font-size doubled from before so 2em, so the font-size is basically nesting through elements. <br>
That's why personally I choosed that, I will use the rem property, which doesn't nest through the elements. If the font size on the body equals 16, and you set for example on some element <br>
font size which equals to 0,875rem, it will equals 14px.

I've also been learning about some hard concept for me, which are viewports properties. <br>
While I certainly understand the usage of viewport heigth, which would be in case: <br>
We have declared the header, and footer, and both of their min-heigth equals to 60, if we would like to <br>
It is also worth of mentioning, we should always define the heigth of element using min-height, by doing so, <br>
we assure that the responsive styling will be applied, and overall it is recomended to use that value instead of basic heigth <br>
Make the body heigth to appear in the rest of available space(then we substract the header, and the footer heigth from the total viewport height, so total available - our usage from header and footer), we would just use calc(100vh - 120px) <br>
And that's the usage in case that I would use it.

I would rather not using vw 100% to declare the width of our elements, because of the unnecessary scroll showing at <br>
the bottom of the site. I know that I can esaily hide it by using overflow-x: hidden;, but still it doesn't appeal to me <br>
that's why I would stick with the default usage, of width 100%. But I can see the usage of this, in case we would need that <br>
flow-x, then it is certainly usefull in those scenarios.
<br>
<hr>
8/21/2023 8:01 PM
Today I've recapped some properties in css, such as: background shorthand, and the properties, margin,padding and the overflow aswell, and many other<br>
properties. I've also realized how important it is, to use header,sections and the footer itself as well. Very simple things, but how much important they are.<br.

<hr>
<br>
8/22/2023 4:34 PM<br>
Today i've worked on css properties, and done a lot of example exercises which are including properties like : [attribute="value"]($^properties), [last-child],[first-child],[nth-child], and others not included in the exercises like : [::selection] , [::marker] , [:link] , [:visited] , [:focus] , [:active]. <br>
Examples I am talking about you can see at the site: https://flukeout.github.io/

I've learned also about top element called :root, there we will place our global variables and properties such as box-sizing:border-box, which would mean that any border or padding will be included into the box, which will maintain prefered stylisation. So for example if you set width and heigth equal to 100px, it will be added to the actual width and heigth.

<br>
<hr>
7:25 PM 8/23/2023<br>
Today I was learning about complex selectors. While there the common way to refer to some element is setting them up class or id we can also do it other way.<br>
The descendant selector is the most common, it matches an indentified ancestor. For example:<br>
article h2{}, <br>
In this example only elements in article which include h2 element would be selected. <br>
The Direct Child Selector is a bit different. <br>
The syntax for it is following : article > p {}, <br>
It means that the every p element in the article will be selected, but it can't be nested. For example if there was article, and inside it div, and inside the div element p, it wouldn't be selected. <br>
The next thing is General Sibling selector, they are created by using the tilde character ~,<br>
For example : h2 ~ p {}, that means, the p selector will be selected, if they will share the same parent. <br>
Adjacent Sibling Selector, <br>
For Example : h2 + p, it will only work for the p element which is written after the h2. <br>
Attribute present selector, <br>
In order to use this one, we need to use square brackets, for example:<br>
html<br>
"<a href="#" target="_blank">...</a>"<br>
css<br>
"a[href="http://google.com/"] {...}"<br>

Attribute contains selector <br>
This one we use when we need to find element based on part of an attribute, <br>
The attributes we can use are : * , ^ , $ <br>
The * means, that it must appear, or be contained within attribute value, for example: <br>
"a[href*="login"] {...}"<br>
and html: <br>
"<a href="/login.php">...</a>" <br>
The ^ means, that it must start with stated value, <br>
And the $ means, that it must end with the certain value. <br>

In case that, that the attribute is spaced, we need to use ~, and while it is hyphenated, we need to use =. <br>

Some infos about User Interface State Pseudo-Classes. <br>
Pseudo-Classes, are element state which include somewhich of those elements : :enabled, :disabled, :checked, :indeterminate, and some other which already mentioned in some other way.<br>
The element indeterminate, means the checkbox or radio button that has been not selected, or unselected. <br>
<br>
The important things to know about css, are also childs.<br>
:first-child , :last-child , :only-child <br>
:first-child - Selects the first child of an element, for example: li:first-child{}, will select the first child of li,<br>
:last-child - Will select the last child of an element,<br>
:only-child - div:only-child will lok for a division that is the single child of a parent element, without any other siblings. <br>
Childreens of parent are pretty helpfull, and it is aften used. But sometimes you need to select the first, last, or only child of a specific type of element, there are where those comes handfull: <br>
:first-of-type, :last-of-type, :only-of-type,
The main difference between them is that, we select the certain element of type, so for example<br>
When the :first-child would select the first child of some element, the :first-of-type, would select certain first type of element.<br>

The very handfull in styling comes also :nth-child(n) & :nth-last-child(n) <br>
Their usage comes very handfull, when we want to select certain elements in some group of for example li. <br>
Lets say we have ul, and inside we have 6 li. And we want to only select the third, and sixth li. <br>
In order to do that, we can use li:nth-child(3n){}, which means it will selects every third character of li. It works like that: 3x0 , 3x1 , 3x2 , ... <br>

We can also select the "base position" of which we want to come further, for example li:nth-child(2n+3){}, it means that, we will start from third li element, and keep adding 2 till there's no more li to stylize. <br>
We could also select the negative number for n, which would mean that we're starting from 0 position. So basically if I wrote like li:nth-child(-n+4), it would start from position 0, and add those four li which will be styled. <br>

The :nth-last-child(n) simply changes the direction of counting, so I won't give any examples for this, since it's just doing that, and the logic, and everything is the same, just from the back. <br>
We can also select it for types : :nth-of-type(n) & :nth-last-of-type(n) , the logic and everything stays the same. <br>

Pseudo-Classes: <br>
:target - In order to this property to work, we must give the id for section, and the same id for the hyperlink we want to refer the section with. <br>
:empty - It will select element which do not contain childreens, or text nodes to be selected. <br>
:not(x) - It will select every class, that does not contain the x(class) element.<br>

Pseudo-Elements: <br>
:first-letter - As you think, it select the first letter of certain element <br>
:first-line : As you think, it selects the first line of an element. <br>
:before - it creates some not signitificant content to our element before the text,<br>
:after - Same as upper, but after the text.<br>
::selection - Have you ever played with tab on some site? The selection is exactly for that to style the selected the part of document, or highlitghted by tab action. <br>
<hr>
<br>
7:11 PM 8/24/2023
Today I've learned about Positioning. There are a few positioning of elements which are very usefull, and worth of mentioning, they includes: <br>
- position: static - That positioning is by default on every element, the rules about it is very simple, you simply can not use top, bot, right, and left properties, they won't affect your element. <br>
- position: absolute - This positioning is pretty usefull if we want to put the element to stay in the same position even when other element might occur, and move it, it simply won't because of that. For example,<br>
if we want to put position absolute, within the parent, we need to use position:relative for the parent, in other case the element we've used absolute on, will move to the full up,bottom,right or left due to default position static for the parent container, overall it is very usefull position, but we should avoid it in cases we are creating the layouts - it isn't made for that. <br>
- position: relative - This positioning is often misussed, the main reason why you would use it, is that it simply allows you to use the properties top, right, bot and left. <br>
- position: sticky - This positioning is working like relative by default, once you scroll down, it will act as fixed so it will appear dependingly of which properties we set, the thing worth of mentioning is that, it won't act as fixed once it passes it's parent heigth <br>
- position: fixed - This is very usefull for nav section, it helps our nav to stay at the top of the site, and provide fast accesibility to it. 
<br>
<hr>
7:15 PM 8/25/2023 
Today I've learned about four really important properties for making our website responsive. <br>
We use those properties in order to make our site fluid and responsive. <br>
clamp(min,preffered,max) - This property is used mostly to font-sizes, it takes the preffered value as default, and while u shrink the page it won't get narrower than the min value, also it won't get wider than max value. <br>
calc(1rem + 2vh) - We can use this property in case to calculate something with different units. <br>
width: min(300px,50%) - We specify the two values, by default it's gonna be the 300px, but if we go shrinker that that, then it will become the 50%<br>
width: max(300px,50%) - We specify the two values, then we basically set the width to 50%, unless the available space drops to 300px. <br>
<hr>
<br>
12:21 PM 8/26/2023
Today I've learned about custom properties. <br>
A custom properties is, a custom, choosen by the user wishen property. The syntax from custom property is following : --name:value; <br>
We should define the custom properties in the :root of html, which is the highest available level. This allows us to have access to the custom property on every level of html, root has more significance than html. <br>
To access the custom property we write following syntax, for example: background-color: var(--name); where --name equals the --name of custom property described in our root level. <br>
This approach simplifi the management of consistent values throughout your stylesheets, enancing maintainability and making it easier to apply changes across multiple elements. <br>
<hr>
<br>
Today I've learned the importance of compatibility on various browsers. The most important thing to remember while working on your project is to check if every, or most of browsers are compatible with the new features. We also should give special meaning to Ios browser which is safari. Though the users are available to install other browsers, it's all running by safari engine, due to 'security reasons', we certainly want to check if user get it's designed output on most of browsers. 
<br>
<hr>
<br>

