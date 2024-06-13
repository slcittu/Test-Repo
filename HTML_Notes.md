# HTML Notes

## Basic Structure of HTML

    <!DOCTYPE html>
    <html>
        <head>
            <title>Enter Title</title>
        </head>
        <body>
            Contents 
        </body>
    </html> 

## HTML Tags

     <p> - Paragraph tag
     <strong> - To display text as bold
     <em> - To display text as italics
     <small> - To display text as slightly small than normal

## Headings
    <h1> - Large text
    <h2> - Smaller than <h1>
    <h3> - Smaller than <h2>
    <h4> - Smaller than <h3>
    <h5> - Smaller than <h4>
    <h6> - Smallest

## Lists
### Unoredred list
    <ul>
        <li>Yoshi</li>
        <li>Ram</li>
    </ul>

### Output
- Yoshi
- Ram
### Oredred list
    <ol>
        <li>Yoshi</li>
        <li>Ram</li>
    </ol>

### Output
1. Yoshi
2. Ram

### Span Tag
    <span>This is a span tag </span>
-Used to add Css/Javascript to a text
***
    <br> - Line break
    <hr> - Horizontal rule
    <img src="logo.png alt="Logo icon">
### Links
    <a href="https://www.youtube.com">Youtube</a>
    <a href="about.html">About Us</a>
### Blockquote
    <blockquote cite="https://www.oscarwildesite.com">
    We are all in the gutter, but some of us are looking at the stars
    </blockquote>
- Gives a tab space before displayig the text
---     
        <p style="color:orange;">Style Me:)</p>
<p style="color:orange;">Style Me:)</p>

## HTML Forms
    <form>
### Type="text"    
        <label for="username">Enter Username</label>
        <input type="text" id="username" name="username">
        <label for="email">Enter Email id:</label>
        <input type="text" id="email" name="email" placeholder="Email-id" required>
        <label for="Password">Enter Password:</label>
        <input type="password" id="Password" name="Password" placeholder="Enter your Password" required>
### Type="radio" 
        <p>Select your age:</p>
        <input type="radio" name="age" value="0-25" id="Option-1">
        <label for="Option-1">0-25</label>
        <input type="radio" name="age" value="26-50" id="Option-2">
        <label for="Option-2">26-50</label>
        <input type="radio" name="age" value="50+" id="Option-3">
        <label for="Option-3">50+</label>

        <br> <br>
### Dropdown list 
        <label for="states" name="states">States:</label>
        <select name="states" id="states">
            <option value="Kerala">Kerala</option>
            <option value="Tamil Nadu">Tamil Nadu</option>
            <option value="Karnataka">Karnataka</option>
        </select>
        <br>
        <br>
        <label for="bio" name="bio">Enter your Bio</label> <br>
### Textarea 
        <textarea name="bio" id="bio" cols="30" rows="10">Type here</textarea>

        <br>
        <br>
        <label for="story" name="story">Enter your Story </label> <br>
        <textarea name="story" id="story" cols="30" rows="10" placeholder="Begin your story"></textarea>
        <br> <br>
### Type="submit" 
        <input type="submit" value="Upload">

      </form> 
### Required attribute - used for mandatory fields
    <input type="password" id="Password" name="Password" placeholder="Enter your Password" required>
### placeholder - Auto clears the textarea
---
    <textarea>Test</textarea> - We have to delete it before typin g text

## HTML Input Types
    <input type="button">
    <input type="checkbox">
    <input type="color">
    <input type="date">
    <input type="datetime-local">
    <input type="email">
    <input type="file">
    <input type="hidden">
    <input type="image">
    <input type="month">
    <input type="number">
    <input type="password">
    <input type="radio">
    <input type="range">
    <input type="reset">
    <input type="search">
    <input type="submit">
    <input type="tel">
    <input type="text">
    <input type="time">
    <input type="url">
    <input type="week">

## HTML Buttons
    <input type="button" onclick="alert('Helo World')" value="Click Me!">