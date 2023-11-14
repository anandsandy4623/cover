# Ex.06 Book Front Cover Page Design
## Date:14.11.2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:

## HTML CODE:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="cover.css">
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>SANDY</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```
## CSS CODE:

```css
body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url('https://th.bing.com/th/id/R.671f161d141466cdcf83db28cb0f3a9c?rik=chK%2bVFNfy9d5yQ&riu=http%3a%2f%2fwww.textronic.com%2fblog%2fwp-content%2fuploads%2f2017%2f10%2fJARVIS.png&ehk=ZeD47puFibIuEgnTFLJ0EvR0pvMX2F4jcL4rRn2y4EU%3d&risl=1&pid=ImgRaw&r=0');
    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f47027;
}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f47027;
    padding-top:10px;
    width:726px;
}
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
```


## OUTPUT:
![Screenshot 2023-11-14 090255](https://github.com/anandsandy4623/cover/assets/135193077/5b4f5177-1776-4a65-af13-1cfb39f57936)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
