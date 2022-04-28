# TAGS

<br>

Tags are fundamental building blocks of a HTML document which tell the webpage somehow how the content should appear or how the content should work or even howthe page should behave.
<br>
ex: &lt;p&gt; tag
<br>
&lt;div&gt; tag

## &lt;a&gt;: The Anchor element

<br>

The &lt;a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

## &lt;img&gt; Tag

<br>

The &lt;img&gt; tag is used to embed an image in an HTML page. The &lt;img> tag creates a holding space for the referenced image.

The &lt;img&gt; tag has two required attributes:

**src** - Specifies the path to the image
<br>
**alt** - Specifies an alternate text for the image, if the image for some reason cannot be displayed

&lt;img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600"&gt;

## &lt;video&gt; Tag

<br>

The &lt;video> tag is used to embed video content in a document, such as a movie clip or other video streams. The text between the &lt;video> and &lt;/video> tags will only be displayed in browsers that do not support the &lt;video> element.

&lt;video width="320" height="240" controls&gt;
&lt;source src="movie.mp4" type="video/mp4"&gt;
Your browser does not support the video tag.
&lt;/video&gt;

<br>

# HTML Tables

<br>

HTML tables allow web developers to arrange data into rows and columns.

- **Table Cells**

Each table cell is defined by a **&lt;td&gt;** and a **&lt;/td&gt;** tag.
td stands for table data.
Everything between **&lt;td&gt;** and **&lt;/td&gt;** are the content of the table cell.

- **Table Headers**

Sometimes you want your cells to be headers, in those cases use the **&lt;th&gt;** tag instead of the **&lt;td&gt;** tag.

- **Table Rows**

Each table row starts with a **&lt;tr** and end with a **&lt;/tr&gt;** tag.
tr stands for table row.

## HTML Table Tags:

<br>
Tag Description
<br>

- **&lt;table&gt;** Defines a table
  <br>
- **&lt;th&gt;** Defines a header cell in a table
  <br>
- **&lt;tr&gt;** Defines a row in a table
  <br>
- **&lt;td&gt;** Defines a cell in a table
  <br>
- **&lt;caption&gt;** Defines a table caption
  <br>
- **&lt;colgroup&gt;** Specifies a group of one or more columns in a table for formatting
  <br>
- **&lt;col&gt;** Specifies column properties for each column within a &lt;colgroup&gt; element
  <br>
- **&lt;thead&gt;** Groups the header content in a table
  <br>
- **&lt;tbody&gt;** Groups the body content in a table
  <br>
- **&lt;tfoot&gt;** Groups the footer content in a table

 <br>

## Html Head and body tags

<br>

The **&lt;body&gt;** tag defines the document’s body.
The **&lt;body&gt;** element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc.

The **&lt;head&gt;** element is a container for all the head elements.
The **&lt;head&gt;** element must include a title for the document, and can include scripts, styles, meta information, and more.

<br>

# CSS POSITION

The position property specifies the type of positioning method used for an element.

There are _five_ different position values:

<br>

- **_Static_**: Static positioned elements are not affected by the top, bottom, left, and right properties.
  An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

- **_Relative_**: An element with position: relative; is positioned relative to its normal position.
  Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position.

- **_Fixed_**: An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

- **_Absolute_**: An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).Absolute positioned elements are removed from the normal flow, and can overlap elements.

- **_Sticky_**: An element with position: sticky; is positioned based on the user's scroll position.
  A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).
  Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first.

<br>

# FLEXBOX

- **_display_**
  This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

- **_Flex-wrap_**

- **_nowrap_** (default): all flex items will be on one line.

- **_wrap_**: flex items will wrap onto multiple lines, from top to bottom.

- **_wrap-reverse_**: flex items will wrap onto multiple lines from bottom to top.
  <br>

## JUSTIFTY-CONTENT

<br>
This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size.

<br>

- **_flex-start_** (default): items are packed toward the start of the flex-direction.

- **_flex-end_**: items are packed toward the end of the flex-direction.

- **_start_**: items are packed toward the start of the writing-mode direction.

- **_end_**: items are packed toward the end of the writing-mode direction.

- **_left_**: items are packed toward left edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like start.

- **_right_**: items are packed toward right edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like end.

- **_center_**: items are centered along the line

- **_space-between_**: items are evenly distributed in the line; first item is on the start line, last item on the end line

- **_space-around_**: items are evenly distributed in the line with equal space around them. Note that visually the spaces aren’t equal, since all the items have equal space on both sides. The first item will have one unit of space against the container edge, but two units of space between the next item because that next item has its own spacing that applies.

- **_space-evenly_**: items are distributed so that the spacing between any two items (and the space to the edges) is equal.

<br>

## ALIGN-ITEMS

<br>

This defines the default behavior for how flex items are laid out along the cross axis on the current line.

<br>

- stretch (default): stretch to fill the container (still respect min-width/max-width)

- flex-start / start / self-start: items are placed at the start of the cross axis.

- flex-end / end / self-end: items are placed at the end of the cross axis.

- center: items are centered in the cross-axis

  <br>

## ALIGN-CONTENT

<br>

This aligns a flex container’s lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.

<br>

- **_normal_** (default): items are packed in their default position as if no value was set.

- **_flex-start / start_**: items packed to the start of the container.

- **_flex-end / end_**: items packed to the end of the container.

- **_center_**: items centered in the container

- **_space-between_**: items evenly distributed; the first line is at the start of the container while the last one is at the end

- **_space-around_**: items evenly distributed with equal space around each line

- **_space-evenly_**: items are evenly distributed with equal space around them

- **_stretch_**: lines stretch to take up the remaining space
