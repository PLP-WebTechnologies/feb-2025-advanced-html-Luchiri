<!DOCTYPE html>
<html>
 <head>
  <meta charste="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML5 Elements and Forms</title>
 </head>
 <body>
  <!--header-->
  <header>
   <h1>Welcome</h1>
  </header>
  <!--Ordered list with roman numerals-->
  <section>
   <h2>Objectives</h2>
   <ol type="i">
    <li>Implement HTML5 elements</li>
    <li>Use form validation attributes</li>
    <li>Apply multimedia elements</li>
   </ol>
  </section>
  <!--external image-->
  <section>
   <h2>Featured Image</h2>
   <img src="https://images.pexels.com/photos/14107/pexels-photo-14107.jpeg" alt="Red Rose Flower" width="600">
  </section>
  <!--contacts table-->
  <section>
   <h2>Contact List</h2>
   <table border="1">
    <tr>
     <th>Name</th>
     <th>Address</th>
     <th>Mobile</th>
     <th>Email</th>
    </tr>
    <tr>
     <td>Catherine Luchiri</td>
     <td>501 Nairobi</td>
     <td>+254799907656</td>
     <td>catherine.luchiri@gmail.com</td>
    </tr>
    <tr>
     <td>Bill Vincent</td>
     <td>38 Busia</td>
     <td>+254710771564</td>
     <td>vincent@gmail.com</td>
    </tr>
    <tr>
     <td>Mary Auma</td>
     <td>57 Narok</td>
     <td>+254720571484</td>
     <td>auma@gmail.com</td>
    </tr>
   </table>
  </section>
  <!--registration form-->
  <section>
   <h2>Registration Form</h2>
   <form>
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required><br><br>
    <label>Gender:</label><br>
    <input type="radio" id="male" name="gender" value="male" required>
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="female" required>
    <label for="female">Female</label><br><br>
    <label for="country">Country:</label><br>
    <select id="country" name="country" required>
     <option value="">Select a country</option>
     <option value="usa">USA</option>
     <option value="uk">UK</option>
     <option value="kenya">Kenya</option>
    </select>
    <br><br>
    <label>Interests:</label>
    <input type="checkbox" id="sports" name="interests[]" value="sports"><label for="sports">Sports</label>
    <input type="checkbox" id="music" name="interests[]" value="music"> <label for="music">Music</label>
    <input type="checkbox" id="tech" name="interests[]" value="tech">
  <label for="tech">Technology</label>
    <br><br>
    <button type="submit">Register</button>
   </form>
  </section>
 </body>
</html>
