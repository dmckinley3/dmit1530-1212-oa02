# Box Sizing

## Demo Instructions
You can follow along with your instructor to complete this build and/or you can use this document as a guide in completing the demo build.

## Steps
1. Download the **demo-box-sizing.zip** file from Moodle and extract its contents to a folder named **demo-box-sizing**.
2. Open index.html in your browser to see something like:<br>
![box-sizing-1](images/box-sizing-1.png)
3. In your code editor you will see the following code:<br>
![box-code-1](images/box-code-1.png)
4. Uncomment the `.border-box` class, save and refresh the browser to see:<br>
![box-sizing-2](images/box-sizing-2.png)<br>
**Question**: What happened?
5. Add the following code to the top of your stylesheet:<br>
![box-code-2](images/box-code-2.png)
6. There may not be a big change but you should see:<br>
![box-sizing-3](images/box-sizing-3.png)
7. Now you need to use the developer tools to see the difference in the two boxes:
    1. `box-sizing: content-box;`<br>
    ![content-box](images/content-box.png)
    2. `box-sizing: border-box;`<br>
    ![border-box](images/border-box.png)
8. **Question**: If you want all your blocks on your web page to have the same width, which box-sizing would you use?