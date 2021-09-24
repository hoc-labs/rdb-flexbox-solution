
# Flexbox Review

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img1.png)

Setting display:flex will orient the immediate child elements with a flex-direction:row (flow from left->right)

Below is the layout of both the desktop and mobile designs.

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img2.png)

## Overall Layout

For this page we only need a single container because there are not different background colors that span the different sections.

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img3.png)

The pink background now represents the .container element.

Now we want to create a div for each row that will contain the columns. A good name might be row or columns...

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img4.png)

And within each of the rows, we want to create divs for each column.

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img5.png)

Here is the detailed spec for the styling..

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img6.png)

Work on getting the basic content with the container styles we reviewed above.
* remember to center the title at the top.
* use a `<span>`, and a compound style, to target the text within the title.
* add the display:flex to flex the 2nd and 3rd rows.
* create a modifier class (a class used in addition to the main .col class) to set the background color on the two divs that need a dark background color.
* create modifier classes to set the widths of the different columns.

If you take a look at the image below, you can see the naming convention used for the modifier columns. 

* col-bg: set the dark background-color
* col, col-2, col-3: how many columns the column takes up. we can then use this to set the column width as a percentage of the total number of columns:
  * col: 25%
  * col-2: 50%
  * col-3: 75%;

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img7.png)

Use justify-content property to add space between the columns. Experiment with different options:
* space-between
* space-around
* flex-start
* flex-end
* center

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-flexbox-img8.png)

## Mobile Version

Add media queries to stack all of the content vertically when the width is less than 600px.

You only need a single media query to make them all stack. But you will need to deal with the widths that are being set on the desktop version for each of the columns so that the mobile version has the content extend across the entire width.





