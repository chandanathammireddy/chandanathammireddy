<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Customer Information Form</title>
</head>
<body>
<h1>html form to take the information of a customer</h1>
<form action="#" method="post">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name" placeholder="Enter your name" required>
<br><br>

  <label for="phone">Phone No:</label><br>
  <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required><br>
<br>
  <label for="days">Preferred Days of Purchasing:</label><br>
  <input type="text" id="days" name="days" placeholder="Enter your preferred days" required><br>
<br>
  <label for="item">Favourite Item:</label><br>
  <select id="item" name="item" required>
    <option value="" disabled selected>Select your favourite item</option>
    <option value="Groceries">Groceries</option>
    <option value="Electronics">Electronics</option>
    <option value="Clothing">Clothing</option>
    <option value="Home Appliances">Home Appliances</option>
  </select><br>
<br>
  <label for="suggestions">Suggestions:</label><br>
  <textarea id="suggestions" name="suggestions" placeholder="Enter your suggestions"></textarea><br>
<br>
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
</form>

</body>
</html>
