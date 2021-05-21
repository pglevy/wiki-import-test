## Principles for CodePen templates
* As little styling as possible
* Stick to utility classes; avoid overriding CSS
* Always realistic content
* Start with responsiveness and accessibility
  * Account for multiple widths
  * Keep content structured
  * Use plain-language
  * Do the non-interactive basics: alt text, labels, typography, contrast, etc.
* Include a link to the content source.

## Principles for Figma templates
* Let's stick with the "desktop lg" and "mobile lg" sizes. Tablet is just more work, and something that we can communicate better in code anyway. 
* The grid is your friend. Since everything in the code uses the grid, let's use the one provided by the preset frames/screens. 
* It's difficult to manage the preset text styles in Figma and have them match up correctly in CodePen. To ensure consistency, refer to the ‘Font sizes’ frame in USWDS Components page in Figma or [theme tokens](https://designsystem.digital.gov/design-tokens/typesetting/font-size/) in USWDS.
* Use whole numbers (based on the Truss Lib font sizes) for setting type size (not fractional sizes).

## FAQs
* Is it standard practice to place an id(#) with H2 tag(s)?
  * Good question: that is typically done automatically by site generators like Jekyll. It allows you to more easily link to specific points on a page. [This typically is] going to be all headings (except H1s), not just H2s. I think it's good for us to manually enter them in our CodePens for now, because it can be helpful to test the link functionality and see spacing issues on real devices. On GitHub readmes, they do something similar, though they use an anchor inside the heading element instead of adding an id to the heading itself. 
