# CSS Guidelines

### Formatting

#### Declaration Order

Declarations within a block should be consistently ordered, clustering related
properties (e.g. positioning, box model) together.

```css
.selector {
    /* Positioning */
    position: absolute;
    z-index: 10;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;

    /* Display & Box Model */
    display: inline-block;
    overflow: hidden;
    box-sizing: border-box;
    width: 100px;
    height: 100px;
    padding: 10px;
    border: 10px solid #333;
    margin: 10px;

    /* Other */
    background: #000;
    color: #fff;
    font-family: sans-serif;
    font-size: 16px;
    text-align: right;
}
```


#### External Links

[Scalable and Modular Architecture for CSS](http://smacss.com/)  
[General CSS notes, advice and guidelines](https://github.com/csswizardry/CSS-Guidelines)  
[Principles of writing consistent, idiomatic CSS](https://github.com/necolas/idiomatic-css)
