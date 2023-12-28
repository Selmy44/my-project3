<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InshutiGarage</title>
    <link rel="icon" href="/pictures/IG.jpg" type="image/x-icon">
    <style>
        body{
            background-color: skyblue;
            margin: 70px;
        }
        .rose{
            color: darkred;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
    </style>
</head>
<body>
    <div class="rose">
        <h1>Inshuti Garage</h1>
        <h3>Fill the names and Adress</h3>
    </div>
    <div>
        <h3>Fill the names and Adress</h3>
        <label for="fname">First Name</label><br>
        <input type="text" name="fistname" id="fname" placeholder="Fist Name"><br><br>
        <label for="lname">Last Name</label><br>
        <input type="text" name="lastname" id="lname" placeholder="Last Name"><br><br>
        <label for="tel">Tel</label><br>
        <input list="code" name="country code" size="3" placeholder="+1">
        <datalist id="code">
            <option value="+250">+250</option>
            <option value="+256">+256</option>
            <option value="+44">+44</option>
            <option value="+1">+1</option>
            <option value="+254">+254</option>
        </datalist>
        <input type="tel" name="phone" id="tel" placeholder="781674354"><br><br>
        <label for="email">Email</label><br>
        <input type="email" name="email" id="email" placeholder="email@gmail.com"><br><br>
    </div>
    <div>
        <h3>Your Gender:</h3>
        <input type="radio" name="gender" id="male">
        <label for="male">Male</label><br>
        <input type="radio" name="gender" id="female">
        <label for="female">Female</label>
    </div>
    <div>
        <h3>Select your favorite Car:</h3>
        <input type="checkbox" name="car1" id="rangerover">
        <label for="rangerover">Ranger Rover</label><br>
        <input type="checkbox" name="car2" id="rollsroyce">
        <label for="rollsroyce">Rolls Royce</label><br>
        <input type="checkbox" name="car3" id="lamborghini">
        <label for="lamborghini">Lamborghini</label><br>
        <input type="checkbox" name="car4" id="cadilac">
        <label for="cadilac">Cadilac Escalade</label><br><br>
        <label for="year">Year:</label>
        <select name="select year" id="year">
            <option value="2020">2020</option>
            <option value="2021">2021</option>
            <option value="2022">2022</option>
            <option value="2023">2023</option>
        </select>
    </div>
    <div>
        <h3>Delivery Address:</h3>
        <label for="country">Select Country</label>
        <select name="name of country" id="country">
            <option value="Antartic">Antartic</option>
            <option value="Bahamas">Bahamas</option>
            <option value="Colombia">Colombia</option>
            <option value="Rwanda">Rwanda</option>
            <option value="USA">USA</option>
        </select>
        <label for="state">State</label>
        <select name="name of state" id="state">
            <option value="California">California</option>
            <option value="Florida">Florida</option>
            <option value="Nevada">Nevada</option>
            <option value="New York">New York</option>
        </select>
        <label for="city">City</label>
        <select name="name of city" id="city">
            <option value="Los Angels">Los Angels</option>
            <option value="Santa Monica">Santa Monica</option>
            <option value="San Francisco">San Francisco</option>
            <option value="Miami">Miami</option>
            <option value="Las Vegas">Las Vegas</option>
            <option value="Manhattan">Manhattan</option>
            <option value="New York City">New York City</option>
        </select><br><br>
        <input type="submit" value="submit">
        <a href="https://github.com/Selmy44" target="_blank"><input type="button" onclick="alert(Welcome to logins)" value="Click Me!"></a>
    </div>
</body>
</html>
