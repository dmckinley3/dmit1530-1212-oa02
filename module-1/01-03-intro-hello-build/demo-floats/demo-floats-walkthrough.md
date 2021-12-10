# Demo Floats – Walkthrough Instructions
You can follow along with your instructor to complete this build and/or you can use this document as a guide in completing the demo build.

## Steps
These steps do not mirror the walkthrough document, but only outline the code needed to produce the correct output.
1. In the `<style>` area of the web page you will see:<br>

```html
<style>
  body{
    width: 600px;
    margin: 0 auto;
  }

  img{
    /* floating the image causes the text to wrap */
    /* float: left;
    margin-right: 10px; */
  }
</style>
```

2. Uncomment the `float` and `margin` rules.
3. Now change the `float` rule to:<br>

```css
img{
  /* floating the image causes the text to wrap */
  float: right;
  margin-right: 10px;
}
```

4. Fix the margins on the iamge:<br>

```css
img{
  /* floating the image causes the text to wrap */
  float: right;
  margin-left: 10px;
}
```