# Paymentform

<!--Form making-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment</title>
   
</head>
<body>
    <form action="">
        <h1>Payment Form</h1>
        <p>Require field are followed by *</p>
        <h2>Contact information</h2>
        <p>Name *<input type="text"name="name" required></p>
    <fieldset>
        <legend>Gender</legend>
        <p>
           Male<input type="radio"name="gender" id="Male">   <!--if we didnt write name attribute same it will asuume as both as different-->
           Female<input type="radio"name="gender" id="Female">
        </p>
    </fieldset>
    <p>Address:<textarea name="Address"id="Address"cols="100"rows="8"></textarea></p>
    <p>Email: *<input type="email" name="email" id="email"required></p>
    <p>Pincode: *<input type="number" name="Pincode" id="Pincode"required></p>
    <h2>Payment information</h2>
    <p>Card type:
        <select name="Card_type" id="Card_type" >
            <option value="">--Select the card type</option>
            <option value="Visa">Visa</option>
            <option value="Rupay">rupay</option>
            <option value="Mastercard">Mastercard</option>
        </select>

    </p>
    <p>
        Card Number *<input type="number" name="Card_number" id="Card_number"required>

    </p>
    <p>
       Expiration Date *<input type="date" name="exp_date" id="exp_date" required>
    </p>
    <p>
        CVV *<input type="password" name="Cvv" id="Cvv"required>
    </p>
    <input type="submit" value="Pay now">
       
    </form>
    
</body>
</html>
