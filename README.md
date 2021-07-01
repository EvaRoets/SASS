# SASS
## Objectives
- understand what a CSS preprocessor is, and why it exists
- generate some CSS from your CSS preprocessor (the industry standard is SASS/SCSS)
- be able to combine multiple SASS files into a single final CSS file
- be able to minify your CSS output

## Specifications
Use the following SASS features:
- Variables
- Mixins (think functions)
- Nesting
- Partials & Import
- Extend/Inheritance
- Operators (math)

### Part 0
Copy the files `index.html` and `style.css` in your new repo. Rename your `style.css` to `style.scss` to be able to make use of all scss features. The info above will help you compile it back to css, as a browser cannot read scss.

### Part 1 - a lot of possibilities
Don't rush for the solution here. Take your time to try out the different possibilities SASS is granting you.
- A. _Nest_ the styling rules of grouped elements, like the `section`s in the `article`.
- B. Make one _mixin_ for the 3 lines of the box-shadow styling.
- C. Use one _variable_ for the general padding value that you see in multiple places (Note: the footer `h6` has double the padding of the other elements. Use _math operations_ to calculate it).
- D. Make use of _extend_ to re-use the same CSS for the "success", "error" and "warning" messages.

### Part 2 - an extra challenge!
- In the HTML, add 2 links called "blue" & "red".
- Clicking one of the 2 links should change the text to red/blue with a good matching background (keep it readable)!  
  Note: the rest of the CSS should be the same and should not be repeated, to do this you will have to use SASS variables and file imports.

Take some time to think how to do the structure of this second part (you will probably need additional files _wink wink_). It might be good to discuss this with your fellow juniors!

### Part 3 (optional)

- Add an option to your compilation script to minify your stylesheet!  
  Mine was below 1.6k, can you do better? Do you still remember the option to `ls` to make the filesize Human readable?
