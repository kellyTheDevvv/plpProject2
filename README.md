<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>My Webpage</h1>
    <section>
     <h2>Web apps</h2>
     <ol type="i">
        <li>Instagram</li>
        <li>Facebook</li>
        <li>Twitter</li>
     </ol>  
    </section>    
        <br><br><br>

    <section>   
        <img src="https://images.pexels.com/photos/30906509/pexels-photo-30906509/free-photo-of-majestic-snow-covered-mountains-in-banff-canada.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Ice Mountains" height="350" width="400">
    </section>     
    
       <br><br>
    <section> 
      <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>George Kelly</td>
                <td>P.O Box 123,</td>
                <td>0746576835</td>
                <td>kellyochi12349@gmail.com</td>

            </tr>
            <tr>
                <td>Faith Guta</td>
                <td>P.O Box 444,</td>
                <td>0723685379</td>
                <td>fayguta12@gmail.com</td>
            </tr>
            <tr>
                <td>Denzel Omondi</td>
                <td>P.O Box 223,</td>
                <td>0798436756</td>
                <td>denzomondi22@gmail.com</td>
            </tr>
        </tbody>
        <tfoot>

        </tfoot>
      </table>
    </section>
       <br><br>

    <section>
      <form action="" method="">
        <label for="name">Name :</label>
        <input type="text" name="student_name" id="student_name" placeholder="Enter your name" required>
         <br><br>
        <label for="email">Email :</label>
        <input type="email" name="email" id="email" placeholder="Enter your email address" required>
         <br><br>
        <label for="password">Password :</label>
        <input type="password" name="password" id="password" required>
         <br><br>
        <label for="date">Date :</label>
        <input type="number" name="date" id="date" required>
          <br><br>
        <label for="favourite web app">Favourite Web App :</label>
        <input type="radio" name="instagram" id="instagram" value="instagram">Instagram
        <input type="radio" name="facebook" id="facebook" value="facebook">Facebook
        <input type="radio" name="twitter" id="twitter" value="twitter">Twitter
          <br><br>
        <label for="gender">Gender :</label>
        <input type="checkbox" name="male" id="male" value="male" required>Male
        <input type="checkbox" name="female" id="female" value="female" required>Female
        <input type="checkbox" name="rather not say" id="rather not say" value="rather not say" required>Rather not say
          <br><br>
        <select name="continent" id="continent">
            <option>--Select Continent--</option>
            <option value="Africa">Africa</option>
            <option value="America">America</option>
            <option value="Europe">Europe</option>
        </select>  

      </form>
    </section>
    <footer>
        
    </footer>    
</body>
</html>
