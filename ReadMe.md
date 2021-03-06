# CSS Pseudo Class Selectors
### HTML and CSS

This lesson will introduce the concept of CSS pseudo class selectors by demonstrating the use of the following example selectors to style and control display of content on a page:

* `:focus`
* `:focus-within`
* `:hover`
* `:not`

The material will be presented as a lecture and demonstration, with opportunities for questions.  It assumes prior instruction in HTML and CSS, and a good understanding of the use of basic CSS selector classes.

##### Lessons:
[Lesson 1](ex1/demo.md): How to hide content by styling text

[Lesson 2](ex2/demo.md): The `:focus-within` selector 

[Lesson 3](ex3/demo.md): Focus within `:focus-within`

[Lesson 4](ex4/demo.md): Moving elements around

[Lesson 5](ex5/demo.md): Some more moves

[Lesson 6](ex6/demo.md): Really letting the pseudo trick shine

[Lesson 7](ex7/demo.md): The final touches

[Bonus](ex99/demo.md): Making It Work vs. Making It Clean

![screenshot](./septafares-2.JPG)

##### Next:

The following lesson should cover presence attribute selectors – `[attr]` –  and value attribute selectors `[attr=val]` in similar detail.

##### Further exploration:

* https://css-tricks.com/pseudo-class-selectors/
* https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes


##### About:

This lesson was inspired by an earlier project, [SEPTA Fare Optimizer](https://github.com/NotTheDBA/septa-fare-optimizer), which uses a small JavaScript helper class to switch styles.  A pure CSS solution had been my original intention, but I ended up using the JavaScript helper to get to the design I wanted at the time.


Keeping in mind that my goal for this project was to present a lesson example, I chose to re-work the original project to focus only on using CSS.  I was able to achieve a pure CSS solution by applying pseudo class selectors to the HTML content.