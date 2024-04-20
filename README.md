# Ex.08 Design of a Standard Calculator
## Date:

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>CALCULATOR</title>
    <script>
        function fn(e) {
            if (e.innerHTML == '=') {
                output.value = eval(output.value);
            }
            else if (e.id == 'back') {
                v = output.value;
                output.value = v.substring(0, v.length - 1);
            }
            else if (e.innerHTML == 'C') {
                output.value = '';
            }
            else if (e.id == '9') {
                output.value = '9';
            }
            else if (e.id == '8') {
                output.value = '8';
            }else if (e.id == '7') {
                output.value = '7';
            }else if (e.id == '6') {
                output.value = '6';
            }else if (e.id == '5') {
                output.value = '5';
            }
            else if (e.id == '2') {
                output.value = '2';
            }else if (e.id == '3') {
                output.value = '3';
            }
            else {
                output.value += e.innerHTML;
            }
        }
    </script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <div class=" bg-dark mx-auto m-3 text-center text-white" style="width: 24rem;">naresh (212223240104)</div>
    <div class="bg-dark row mx-auto text-center" style="width: 24rem;">
        <div class="col-12 my-4"><input type="text" name="" id="output"
                style="width: 100%;height: 50px;border-radius: 25px;"></div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">(</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div>
        <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div>
        <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i>
        </div>
        
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="7" ><i class="bi bi-7-square"> </i></div>
        
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="8" ><i class="bi bi-8-square"> </i></div>

        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="9" ><i class="bi bi-9-square"> </i></div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">*</div>
        
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="4" ><i class="bi bi-4-square"> </i></div>
 
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="5" ><i class="bi bi-5-square"> </i></div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="6" ><i class="bi bi-6-square"> </i></div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">-</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="1" ><i class="bi bi-1-square"> </i></div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="2" ><i class="bi bi-2-square"> </i></div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)" id="3" ><i class="bi bi-3-square"> </i></div>

        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">+</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
        <div class="m-3 col-2 btn btn-success rounded-4" btn-success onclick="fn(this)">.</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">%</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">/</div>
        <div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)">=</div>
    </div>
</body>

</html>
```
## OUTPUT:
![Screenshot 2024-04-20 120357](https://github.com/feryjfgkuyfgewjfgew/Calc/assets/150319377/1d35ae8e-a4d8-4d74-98f8-e5b55560cb56)



## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
