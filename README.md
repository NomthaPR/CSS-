# CSS-
Building HTML Tables
To create an HTML table, you use several different HTML elements in just the right combination. Table, TR, TH, and TD. 

Table Element
<Table></Table>

Table row element 
<tr></tr>

Table headear Element 
<tb></tb>

Table data
<td></td>

Here is an example of an HTML table. The table element wraps around the whole table, around all our content and markup for that table, marking the beginning and end of the table itself. The TR element stands for table row and wraps around a set of elements, defining them as belonging to the same row. The TH element stands for table header and defines a header for a column. The TD element stands for table data and marks up the cells of data. 

We start with a table element to mark the beginning of the table and close it at the end. This table has six rows, five rows about five different birds, and a top row which contains the header for each column. In the HTML we use the TR element to markup each row. Six pairs of TR opening and closing tags make six rows. Then put the content inside of each row. Start with the American goldfinch. 
Use the TD element to wrap a cell of content, American goldfinch, yellow, eats mostly seeds, and the image with an image element. You can put any HTML markup inside of these cells e.g. paragraphs, videos and headlines. There are four columns in this table, which means four cells of data in each row. Fill in all the rest of the birds. 
Include a bit of styling and CSS to make the table look more like a table of your choice instead of the default styling that a browser uses. But what about that header? Well, we put the content for the header in the first row, wrapping each one in a TH element instead of a TD element. TD stands for table data, while TH stands for table header. Bird, color, diet, photo. 

In the reference document, the header is typeset in all caps, but we do not want the words to actually be in all caps. They are not acronyms, so place them into HTML as normal words, and use CSS to change how they look. That will ensure they are spoken aloud properly and if we want to change how the table is styled, it will be easy to do so using CSS. 
Those are the basics of table markup. There is a lot more that can be done to create a complex HTML table, ways to have content span multiple rows, or multiple columns. We could define a header, body, and footer for the table, or add a caption. There are many courses readily available that go deeper into HTML tables, including how to make an HTML email template. For this course, what is covered is the basics of an HTML table, the table element, TR for table rows, TH to mark content that is in a header, and TD for marking up the content of each table cell.

