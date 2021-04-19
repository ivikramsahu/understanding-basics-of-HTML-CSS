# understanding-basics-of-HTML-CSS

HTML is a markup language that uses a special syntax or notation to describe the structure of a webpage to the browser. HTML elements usually have opening and closing tags that surround and give meaning to content. For example, different elements can describe text as a heading, paragraph, or list item.

```html
<!DOCTYPE html>
<html>
<head>
    <title>
        This is Start of Frontend Development
    </title>
</head>

<body>                      <!--start of HTML body consists of actual web page data-->
    <h1>Vikram Sahu</h1>    <!--heading of the HTML file followed by h1,h2,h3...h6 -->
    <hr>                    <!--breaks the page by adding an horizontal line in the webpage-->
    <h2>Developer Advocate</h2>

    <!--Image tag : allows you to add image within the HTML page-->
    <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/Geek_logi_-low_res.png"><br>
    
    <!--wrapping image to link-->
    <a href="#"><img src="" alt="Src is blank so displaying this text"> </a>
    
    <!--paragraph tag use to write a paragraph within the HTML page-->
    <p>                     
        A Computer Science portal for geeks
        <br>                <!--br tag to add new line in the HTML-->
        Hello world
    </p><br>

    <!--Dead links-->
    <a href="#">Hello Dead link </a><br>
    <a href="https://www.geeksforgeeks.org/">Click to open in the same tab</a><br> <!--link to xyz using a tag-->

    <div>
        This is division part/section for HTML webpage        
    </div>
    <!-- unordered Lists-->
    <ul>
        <li>milk</li>
        <li>coffee</li>
        <li>cookies</li>
    </ul>

    <!--ordered list-->
    <ol>
        <li>dogs</li>
        <li>Bones</li>
        <li>peanut butter</li>
    </ol>

    <!--Form elements-->
    <form action="/submitted URL">
        <input type="text" required placeholder="email/phone number">
        <label>
            <input type="radio" name="indoor-outdoor" checked >Indoor 
        </label>
        <label> 
            <input type="radio" name="indoor-outdoor">outdoor 
        </label>
        <label for="loving">
            <input id="loving" type="checkbox" name="personality" checked> kind
        </label>
        <button type="submit">Submit</button>
    </form>
    
</body>

</html>
```
