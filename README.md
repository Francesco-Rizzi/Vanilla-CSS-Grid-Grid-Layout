# Vanilla CSS-Grid Grid layout
## An highly customizable grid layout based on the native `CSS-Grid` specifications.

#### Basic Q&A:
**Q**: What the heck is `CSS-Grid`?

**A**: Discover the basic concepts [here (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout)!

**Q**: What is available by default?

**A**: This library is fully working out-of-the-box and it ships with the Bootstrap 4 configuration ([more here](https://getbootstrap.com/docs/4.0/layout/grid/#grid-options))!

**Q**: How could this help me?

**A**: Here some reasons:
- It's (hopefully) simple and straightforward
- It's **based on native CSS specs created for the purpose** `===` no CSS 'hacks' used!
- It's **highly customizable**. Need to change the breakpoints or the class-names? It's just a matter of seconds
- It's ultra-light-weight, **just ~3KB** (uncompressed)!
- It's just the good old grid, nothings else that you *may* not need ;)

<br/><br/>
![CSS-Grid image](assets/css-grid-image.png?raw=true "CSS-Grid image")
<p align="center"><i>show me the stuff</i></p><br/><br/>

#### How-to customize:
- You can customize breakpoints, spacings, number of columns, class-names, and more!
- Just change the SASS configuration variables in the `_grid.scss` source file.

#### How-to import in your flow:
- Just add this to your main .SCSS file: `@import /path/to/_grid.scss`.

#### How-to compile standalone:
- Just run `sass _grid.scss:grid.css` in the file directory. (SASS CLI required, [how to install SASS](http://sass-lang.com/install))
- If you don't need any additional change to the default configuration, just import the already-compiled `grid.css` file.