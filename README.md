# Ex.06 Book Front Cover Page Design
## Date:17/12/2025
## Ref no: 25017622

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
<html>
    <head>
        <title>Cascading Style Sheet</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="book">
            <div class="heading">
            <h1>About the Book</h1>
            <hr>
            </div>
            <div class="content">
                <p>TMachine Learning (ML) is a branch of AI that teaches computers to learn from data, find patterns, and make decisions or predictions without being explicitly programmed for every task, relying on algorithms trained on large datasets. It's the power behind personalized recommendations, fraud detection, and self-driving cars, enabling systems to improve with experience and become more accurate over time by identifying correlations and trends. </p>
            </div>
            <div class="quote-box">
            "Some people call this artificial intelligence, but the reality is this technology will enhance us. So, instead of artificial intelligence, I think we'll augment our intelligence."
            </div>
            <div class="author-box">
                 <div class="author-img"></div>

                <div class="author-text">
                     <div class="author-name">About Auther</div>
                    <img src="my pic.jpg" width="100" height="100"> <p>
                        Ak gowthaman 1st year B.tech AIML from saveetha engeering college thandalam kanchipuram district
                
                     </p>
                     
                     
                </div>
            </div>
            
            <div class="footer">
                <div class="footer-left">
                    <strong>SEC Publishers</strong>
                    <br>
                    <div class="printed">printed in India</div>
                </div>
                <div class="price">Price = 599rs</div>
            </div>
        </div>
    </body>
</html>
## style.css
body
{
    background: url('cover.jpg') center / contain no-repeat fixed;
    min-height: 100vh;
    display: flex;
    justify-content: center;
}
.book
{
    padding-left: 700px;
    padding-right: 700px;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.heading
{
    padding-top: 20px;
    font-style: Montserrat;
    color: rgb(157, 210, 246);
    padding-left: 25px;
}
.content
{
    font-size: 16px;
     color: rgb(255, 0, 136);
    text-align: center;
    text-align: justify;
    padding-left: 25px;
    font-style:inherit
}
span
{
    background-color: rgb(62, 194, 161);
}
.quote-box
{
    margin: 15px 0;
    padding: 15px 15px;
    background: rgb(173, 115, 115);
    border-left: 6px solid rgb(65, 68, 56);
    font-style: italic;
}
.author-text 
{
    
    display: flex;
    flex-direction: column;
    font-size: 15px;
    
}

.author-box 
{
    display: flex;
    gap: 8px;
    background: cyan;
    padding: 8px;
    border-radius: 8px;
    margin-top: 15px;
    text-align: justify;
    align-items: center;
}
.author-img 
{
    width: 400px;
    height: 100px;
    border-radius: 8px;
    background-image: url('');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.author-name 
{
    color: blue;
    font-weight: bold;
    font-size: 15px;
}
.footer
{
    margin-top: auto;
    background-color:rgb(54, 139, 158);
    color: rgb(38, 37, 36);
    padding: 5px 5px;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer-left 
{
    display: flex;
    flex-direction: column;
}
.printed
{
    font-size: 14px;
}
.price 
{
    font-weight: bold;
    color: rgb(168, 236, 33);
    font-size: 18px;
}
## OUTPUT:
![alt text](<Screenshot 2025-12-19 160809.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
