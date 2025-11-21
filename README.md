# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

```
<html>

<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>POWER OF LAMP IN INCANDESCENT BULD</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style type="text/css">
        .box {
            display: block;
            width: 500px;
            min-height: 300px;
            font-size: 20px;
            background: rgb(21, 208, 215);
            background: linear-gradient(90deg, rgb(99, 237, 118) 9%, rgb(193, 166, 202) 56%);
            border-radius: 10px;
            box-shadow: rgba(239, 5, 24, 0.35) 0px 5px 15px;
        }
       </style>
</head>
<body>
  <center>
    <div>
        <div class="box">
            <h1>POWER OF LAMP IN INCANDESCENT BULB</h1>
            <form method="POST">
                {% csrf_token %}
                <div>
                    INTENSITY : <input type="text" name="Intensity" value="{{I}}"></input>(in A)<br />
                </div>
                <div >
                    RESISITANCE : <input type="text" name="Resistence" value="{{R}}"></input>(in Ω)<br />
                </div>
                <div >
                    <input type="submit" value="Calculate"></input><br />
                </div>
                <div>
                    POWER : <input type="text" name="Power" value="{{Power}}"></input>W<br />
                </div>
            </form>
        </div>
    </div>
    </center>
</body>

</html>
```
## SERVER SIDE PROCESSING:
<img width="1920" height="1080" alt="1 (1)" src="https://github.com/user-attachments/assets/cf5c76aa-09a8-481a-8f51-7b0f5384d0d9" />


## HOMEPAGE:
<img width="1920" height="1080" alt="2 (1)" src="https://github.com/user-attachments/assets/e1a640dd-20a3-4375-90fc-f6977f0cbcfd" />


## RESULT:
The program for performing server side processing is completed successfully.
