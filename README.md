<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> JS functions </h2>
    <button onclick="sayHi()"> Say Hi </button>
    <button onclick="addNumbers()"> Addition </button>
    <button onclick="showtime()"> Time </button>
    <div id="output"></div>
    <script>
        function sayHi(){
            document.getElementById("output").innerText = "Hello!! How are you?!";
        }
        function addNumbers(){
            let a=100,b=200;
            let sum = a+b;
            document.getElementById("output").innerText = "Sum of "+a+" and "+b+" is "+sum;
        }
        function showtime(){
            let now = new Date();
            document.getElementById("output").innerText = "Current time"+now.toLocaleTimeString();
        }
    </script>
</body>
</html>
