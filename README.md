# cs-carbonfootprint
cs 2022 apr 18
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carbon footprint</title>
    <script src="carbon_footprint.js"></script>
</head>
<body>
    <h1>Meat eating</h1>
    <br>
    <img src="https://britishop.com/webpimg/L3N0b3JhZ2UvaW1nY2FjaGUvY293LWluLW1lYWRvdy1CSFZNOUtaX18xMDAweDYwMHhhdXRvLmpwZw==" alt="cow">
    <h2>Meat eating</h2>
    <br>
    <br>

    <form>
        <input type="radio" name="meat_amount" id="heavy_eater" value="heavy meat eater">
        <label for="heavy_eater">More than 100g</label>
        <br>
        <input type="radio" name="meat_amount" id="medium_eater" value="medium meat eater">
        <label for="medium_eater">Between 50g and 99g</label>
        <br>
        <input type="radio" name="meat_amount" id="low_eater" value="low meat eater">
        <label for="low_eater">Less than 50g</label>
        <br>
        <input type="radio" name="meat_amount" id="pescatarian" value="pescatarian">
        <label for="pescatarian">I'm pescatarian</label>
        <br>
        <input type="radio" name="meat_amount" id="vegetarian" value="vegetarian">
        <label for="vegetarian">I'm vegetarian</label>
        <br>
        <input type="radio" name="meat_amount" id="vegan" value="vegan">
        <label for="vegan">I'm vegan</label>
        <br>
        <button type="submit">Submit</button>
    </form>

    <script>document.querySelector("form").addEventListener("submit", function(e){
        if(document.getElementById("vegan").checked == true)
        {   
            document.write("2.89 kgCO2e/day");
        }
        else if(document.getElementById("vegetarian").checked == true)
        {  
            document.write("2.89 kgCO2e/day");
        }
        else if(document.getElementById("pescatarian").checked == true)
        {  
            document.write("3.81 kgCO2e/day");
        }
        else if(document.getElementById("low_eater").checked == true)
        {  
            document.write("4.67 kgCO2e/day");
        }
        else if(document.getElementById("medium_eater").checked == true)
        {  
            document.write("5.63 kgCO2e/day");
        }
        else if(document.getElementById("heavy_eater").checked == true)
        {  
            document.write("7.19 kgCO2e/day");
        }
    })</script>
<link rel="stylesheet" href="style.css">
</body>
</html>
