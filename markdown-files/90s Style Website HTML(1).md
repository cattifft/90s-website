# 90s Style Website HTML

## PROMPT 1

Give me HTML code (with NO javascript or CSS) for a generic, 90s style personal website. 
1. Header with title
2. Teal three columned table with one column containing a list of links, one containing an about me with a photo, and one containing a simple email form.
3. Another header
4. A three column, four row table
5. Another header
6. Another three column, four row table
7. A footer with a link back to the top
NO CSS!

## RESPONSE 1

Here's your HTML code for a 90s-style personal website with the specifications you requested:

## RESPONSE 2

This code gives you a classic 90s website structure with no CSS or JavaScript, relying entirely on HTML for styling and layout. You can save it as an `.html` file and open it in a browser to view the result.

## PROMPT 2

what is the tag for superscript

## RESPONSE 3

The HTML tag for superscript is `<sup>`. It is used to display text slightly above the baseline. Here's an example:

`<p>This is an example of superscript: x<sup>2</sup>.</p>`

This would render as:

> This is an example of superscript: x².

## PROMPT 3

what are the common html entities?


## RESPONSE 4

HTML entities are used to display reserved characters or characters that cannot easily be typed on a keyboard. Here are some of the most common HTML entities:

### Reserved Characters

*   `&amp;` → `&` (Ampersand)
*   `&lt;` → `<` (Less than)
*   `&gt;` → `>` (Greater than)
*   `&quot;` → `"` (Double quote)
*   `&apos;` → `'` (Single quote, not widely supported in older HTML versions)

* * *

### Non-breaking Space

*   `&nbsp;` → Non-breaking space (used to prevent line breaks)

* * *

### Mathematical Symbols

*   `&plus;` → `+` (Plus sign)
*   `&minus;` → `−` (Minus sign)
*   `&times;` → `×` (Multiplication sign)
*   `&divide;` → `÷` (Division sign)

* * *

### Currency Symbols

*   `&cent;` → `¢` (Cent)
*   `&pound;` → `£` (Pound)
*   `&yen;` → `¥` (Yen)
*   `&euro;` → `€` (Euro)
*   `&dollar;` → `$` (Dollar)

* * *

### Punctuation

*   `&copy;` → `©` (Copyright)
*   `&reg;` → `®` (Registered trademark)
*   `&trade;` → `™` (Trademark)
*   `&hellip;` → `…` (Ellipsis)

* * *

### Arrows

*   `&larr;` → `←` (Left arrow)
*   `&rarr;` → `→` (Right arrow)
*   `&uarr;` → `↑` (Up arrow)
*   `&darr;` → `↓` (Down arrow)

* * *

### Miscellaneous

*   `&deg;` → `°` (Degree symbol)
*   `&para;` → `¶` (Pilcrow/Paragraph symbol)
*   `&sect;` → `§` (Section symbol)
*   `&bull;` → `•` (Bullet)

* * *

### Example Usage

`<p>5 &lt; 10 &amp; 20 &gt; 15</p> <p>Temperature: 25&deg;C</p> <p>Price: &pound;50 or &dollar;60</p>`

This would render as:

> 5 < 10 & 20 > 15  
> Temperature: 25°C  
> Price: £50 or $60

## PROMPT 4

How can I set a background color

## RESPONSE 5

To set a background color in HTML, you use the `bgcolor` attribute for specific elements like `<body>` or `<table>` (commonly used in older HTML), or the `style` attribute with the `background-color` property (recommended in modern HTML).

### Using the `bgcolor` Attribute (Deprecated but Simple)

`<body bgcolor="lightblue">     <p>This page has a light blue background.</p> </body>`

### Using the `style` Attribute (Modern Approach)

`<body style="background-color: lightblue;">     <p>This page has a light blue background.</p> </body>`

### Applying to Other Elements

You can set the background color for specific elements as well:

#### Table

`<table border="1" style="background-color: teal;">     <tr>         <td>Cell 1</td>         <td>Cell 2</td>     </tr> </table>`

#### Paragraph

`<p style="background-color: yellow;">This paragraph has a yellow background.</p>`

### Notes

*   The `bgcolor` attribute is considered outdated. Use the `style` attribute or external CSS for modern, maintainable HTML.
*   Background colors can be specified using color names (e.g., `red`), hexadecimal codes (e.g., `#FF0000`), RGB values (e.g., `rgb(255, 0, 0)`), or HSL (e.g., `hsl(0, 100%, 50%)`).

## PROMPT 5

How do I make the tables not stretch to the edge of the page?

## RESPONSE 6

To prevent tables from stretching to the edges of the page in HTML, you can specify the `width` of the table as a percentage or fixed value using the `width` attribute or the `style` attribute.

Here are some examples:

* * *

### 1\. **Using the `width` Attribute**

Set a fixed width or a percentage width for the table:

`<table border="1" width="80%">     <tr>         <td>Cell 1</td>         <td>Cell 2</td>     </tr> </table>`

This will make the table occupy 80% of the page width.

* * *

### 2\. **Using the `style` Attribute (Modern Approach)**

Define the width in pixels or percentages:

`<table border="1" style="width: 600px;">     <tr>         <td>Cell 1</td>         <td>Cell 2</td>     </tr> </table>`

This sets the table width to 600 pixels.

* * *

### 3\. **Centering the Table (Optional)**

To center the table on the page, wrap it in a `<div>` with `text-align: center` or use the `margin` property:

`<div style="text-align: center;">     <table border="1" style="width: 80%; margin: auto;">         <tr>             <td>Cell 1</td>             <td>Cell 2</td>         </tr>     </table> </div>`

* * *

### 4\. **Remove `width="100%"` (if present)**

If your table stretches to the edges due to `width="100%"`, remove or replace it with a smaller value:

`<table border="1" width="80%">     <tr>         <td>Cell 1</td>         <td>Cell 2</td>     </tr> </table>`

* * *

By setting the width explicitly and optionally centering the table, you can control how much space it occupies on the page.

