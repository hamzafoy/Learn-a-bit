## What I learned. . .

In this *Learn-a-Bit*, I demonstrated my ability to create a UI with **HTML** & **CSS**.

In the following table, I will comment on some considerations with my code choices:


| Line in Code | Comments |
| ----------- | ----------- |
| Line 14, 34, 36, etc in `index.html` | [A](#id-1) Comments in Code |
| Line 17-21, 59 in `index.html` | [B](#id-2) Picking HTML tags |
| Line 9-12 in `styles.css` | [C](#id-3) Whitespace Issue |
| Line 65 in `styles.css` | [D](#id-4) Adding color to SVGs |
| Throughout `styles.css` | [E](#id-5) `em` v. `px` |



<div id='id-1'/> 

- #1: Comments are an effective way of communicating what you intend with your<br>
code & a useful way to partition your structures & stylings for easier reading.

<div id='id-2'/>

- #2: Choosing your HTML tags can be both an exercise in ensuring the tag describes<br>
the reason you are using it and in taking advantage of its default inline or block behavior.<br> There is often a concern for overusing `<div>` tags as well.

<div id='id-3'/>

- #3: It can be a common occurrence that you'll need to clear the margins/padding of the<br> `body` to avoid the whitespace along the edges.

<div id='id-4'/>

- #4: A workaround when coloring `.svg` files is to use the `filter{}` property.<br> Credit to Barrett Sonntag for this easy-to-use hex-to-filter generator!<br> [Find it here!](https://codepen.io/sosuke/pen/Pjoqqp)

<div id='id-5'/>

- #5: I am not the best in describing the contention between using `em` vs. `px`,<br>
but I know that `em` is a relative measurement that is affected by the parent element <br> whereas `px` is unaffected by elements around it.

<br>
<br>

## Changes based on Feedback from Emsad Ahmetasevic

### HTML
   - Should use semantic tags &#10004;
   - Should use less `<div>` &#10004;
   - Should use <link> to import fonts &#10004;

### CSS
   - Reset - Needs improvement &#10004;
   - Should use class instead id &#10004;
   - Should not put bg image to body :: *Noted in codebase*
   - Should not target html tags &#10004;
   - Should use declaration order :: *Noted in codebase*

### Other
   - Folder structure - Should use separated folders for files &#10004;