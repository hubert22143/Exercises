# Exercises
In this repository, I will write the things I've learned, which doesn't contain any html, js, or any other files than txt.


8/18/2023   5:49PM
<br>
Today I've learned about emmet syntaxes as well as some usefull cheat sites
https://docs.emmet.io/cheat-sheet/
https://htmlcheatsheet.com/css/
I've learned that, we can improve our type speed in html drastically, by using emmet syntaxes. Emmet syntaxes are built-in extension, in the VS code, which allows us
to create the elements way faster.
The example for implementation emmet syntaxes is following if we wish to create div, which contains 3 p elements, with their own class:
syntax > is saying that, the p element is the child of div. So basically the div contains 3 p elements as we wish.
syntax $ describes the item numbering, from 1 to x
syntax * describe exactly what you think it's doing, it simply works as multiplier, we want it to contain 3 elements, so we're multyplying by 3.
div>p.class$*3

<hr>
8/18/2023   6:38
<br>
I've learned some info about what are svg's.
While I confidently don't know a larger part of what svg's are more in advanced meaning but I surely get them in their basic meaning.

The svg(Scalable Vector Graphics) itself is scalable image format, which means we can format them as we wish, and they won't lose of their quality.
SVG's are defined by xmls markup language, which gives us some benefits at the first step. Thankfully to that, they are formated by xml's,
they are human-readable and machine-readable as well,which means we can understand them, but they are kinda confusing at the first glance.

The svg format looks like:
The xmlns is a global format(svg standard rather should I said) for svg files, it let us knows, that basically this is the svg file. The value is the standard formula for the svg.
In the viewbox we've got four variables following indicating:
min-x="" dependly of our usage it will shift x units to the right, or to the left if the value is negative,
min-y="" same as above, it will shift x units, but this time vertically, to the up or bottom if the value is negative,
max-width="" defining the max width of the created box
max-height="" same as above, bud the height of created box.
"<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"></svg>"

By defining all those values, we are certain that the browsers and software, will correctly understand that the content is svg, and within the box will be created elements
dependingly of the given viewBox values.
<hr>
<br>
8/19/2023 2:08 PM
<br>
Today I've recapped some basic, but meaningfull things about creating the table in html.
The syntax for creating table is following:
This is a basic table structure. The "table" indicates that we are starting and ending the table.
The "caption" indicates what the table is writting about.
The "theader" is a thing which helps recognize the structure of table for screen readers even betters, we should indicate it always.
It also improves the readability and make it more accessible and comprehensible for all users. Overall it is recommended to always include those things in the 
table html property.
The thing with tbody, and tfooter is the same. In tbody, we're indicating the main data of our table, the footer is basically the last row in the table. 
It is also worth to mention, that whenever we apply the tfooter, no matter where the table row will sit, it will always be pushed to the down due to tfooter functionality.
"
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
"
<hr>
<br>
