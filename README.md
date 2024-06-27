### HTML CODE:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DAY_1 TASK</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>NAME:P.DHANUSH</h1>
        <img src="https://gratisography.com/wp-content/uploads/2024/01/gratisography-cyber-kitty-800x525.jpg" alt="Cyber Kitty">
        <div class="content">
            <h2>Familiar topics with Web Development</h2>
            <ol>
                <li>Basic HTML Structure</li>
                <li>Few tags and elements</li>
                <li>Basic CSS</li>
                <li>Basic MySQL</li>
            </ol>
            <h2>Unfamiliar topics with Web Development</h2>
            <ul>
                <li>JavaScript</li>
                <li>Launching the website</li>
                <li>Maintenance of website</li>
            </ul>
        </div>
        <div class="contact">
            <h2>Contact Us</h2>
            <h3>Website Link:<a href="http://www.youtube.com" target="_blank">YouTube</a></h3>
            
            <p>Address: Boys Hostel, SEC, Chennai.</p>
        </div>
    </div>
</body>
</html>

```
### CSSS CODE:
```
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: #abafaf;
    padding: 20px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    max-width: 600px;
    width: 100%;
    text-align: center;
}

h1 {
    color: #77de5a;
    margin-bottom: 10px;
}

img {
    width: 100%;
    max-width: 300px; /* Set the maximum width of the image */
    height: auto;
    border-radius: 10px;
    margin-bottom: 20px;
}

.content {
    text-align: left;
    margin-bottom: 20px;
}
h1 {
    color: #dc21ad;
    border-bottom: 2px solid #4CAF50;
    padding-bottom: 5px;
    margin-bottom: 10px;
}
h2 {
    color: #c37a20;
    border-bottom: 2px solid #4CAF50;
    padding-bottom: 5px;
    margin-bottom: 10px;
}

ol, ul {
    padding-left: 20px;
    margin-bottom: 20px;
}

ol li, ul li {
    margin-bottom: 10px;
}

.contact {
    text-align: left;
}

.contact h2 {
    text-align: center;
}

a {
    display: inline-block;
    margin-bottom: 10px;
    color: #2196F3;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
}

p {
    margin: 0;
}
```