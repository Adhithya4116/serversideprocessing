# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

Step 1:
Crete new Project And App in Django.

Step 2:
Type the code in views and urls files

Step 3:
Create the Html files

Step 4:
Run The server

## PROGRAM :
```

<!DOCTYPE html>
<html>
    <head>
        <title>
            www.volume.html
        </title>
    </head>
<style>
    *{
        box-sizing: border-box;
         }

    body{
    background-color;
    color: black;
    }

   .container{
    width: 1080px;
    height: 350px;
    margin-top: 100px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 25px;
    border: 10px solid black;
    
    
    }
    h1{
        color: rgb(0, 0, 0);
        text-align: center;
    }
    .calculate{
        padding-top: 10px;
        padding-bottom: 10px;
        padding-left: 10px;
        padding-right:10px;
        text-align: center;
        font-size: 20px;
        padding-top: 7px;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
</style>
    <body>
        <div class="container">
        <h1>TO CALCULATE VOLUME</h1>
        <form method="POST">
            {% csrf_token %}
            <div class="calculate"> 
                Height:<input type="text" name="height" value={{h}}></input><br/>
            </div>
            <div class="calculate">
                Length:<input type="text" name="length" value={{l}}></input><br/>
            </div>
            <div class="calculate">
                Width:<input type="text" name="width" value={{w}}></input><br/>
            </div>
            <div class="calculate">
                <input type="submit" value="Calculate Volume"></input><br/>
            </div>
            <div class="calculate">
                Volume:<input type="text" name="volume" value={{volume}}></input>
            </div>
        </form>
    </div>
    </body>
</html>

```
## OUTPUT:

### Home Page:

![212553386-ce23fb8f-983a-4b8b-90b2-1412e24d763b](https://user-images.githubusercontent.com/118707079/215283387-a309c8b7-05d8-4cb6-82f4-7448606e2467.png)





## Result:
Thus the experiment was executed successfully.

