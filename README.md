Assignment 1 Checklist 

Create Repository 
Create index.html file and Skeleton
Create README.md file 
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Dorien Parris - Introduction</title>

    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
      }

      header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 16px 24px;
        background-color: #f4f4f4;
      }

      .top-buttons button {
        margin-left: 10px;
        padding: 8px 14px;
        cursor: pointer;
      }

      main {
        padding: 24px;
      }

      .button-group button {
        margin-right: 10px;
        margin-top: 10px;
        padding: 10px 16px;
      }
              table, th, td {
            border: 1px solid black;
            border-collapse: collapse; 
            padding: 8px;
        }
    </style>
  </head>

  <body>
    <header>
      <h1>Hello, I'm Dorien Parris</h1>

      <div class="top-buttons">
        <button>Sign Up</button>
        <button>Register</button>
      </div>
    </header>

    <main>
      <p>
        I’m a senior Information Systems student interested in cybersecurity. I enjoy
        building projects that improve user experiences, and I also work as a barber
        and photographer.
      </p>

      <div class="button-group">
        <button>Filler</button>
        <button>Filler</button>
        <button>Filler</button>
      </div>
    </main>
    <h2 id="events">Cruise Artinerary</h2>
<table id="event-table">
  <thead>
    <tr>
      <th>Event </th>
      <th>Date</th>
      <th>Time</th>
      <th>Location</th>
    </tr>
  </thead>
  <tbody>
<tr>
  <td>Boarding</td>
  <td>January 19th, 2026</td>
  <td> 2:12 pm </td>
  <td> Port Tampa Bay </td>

</tr>

<tr>
  <td> Dinner </td>
  <td>January 19th, 2026</td>
  <td> 5:00pm-8:30pm</td>
  <td> Poop Deck Cafe </td>
</tr>

<tr>
  <td> Sea Sick Sipping (21+) </td>
  <td>January 19th-20th, 2026</td>
  <td>8:45pm-2:00am</td>
  <td>Poop Deck Tikki Bar</td>
</tr>
</tbody>
<tfoot>
 
</tfoot>
</table>


    
  <h2 id="volunteer">Volunteer Sign Up Form</h2>
  <form method="post" action="#">
<div>
  <input type="text" id="Firstname" placeholder="Firstname" required>
  <input type="text" id="Lastname" placeholder="Lastname" required>
</div>
<div>
  <input type="email" id="Email" placeholder="Email" required>
  <input type="password" id="Password" placeholder="Password" required>
  <input type="number" id="Number" placeholder="Number" required>
</div>  

  <input type="datetime-local" id="DOB" placeholder="endter your DOB" required>


<h4> Country of Origan</h4>
<div>
<select id="Browser" name="Select Browser" >
  <option value="MEdge">Microsoft Edge</option>
  <option value="GChrome">Google Chrome</option>
  <option value="FFox">Fire Fox</option>
  <option value="Bing">Bing</option>
  <option value="Safari">Safari</option>
  <option value="other">Others</option>
</select>
</div>
  
   <div> 
    <h4> Are you enjoying your day </h4>
    <input type="radio" id="yes" name="button1" value="value1" >
    <label for="yes"> YES </label>
    
    <input type="radio" id="no" name="button2" value="value2" >
    <label for="no"> NO </label>    
  </div>

    
  <div>
    <h4>How did I do</h4>
    <label>
      <input type="checkbox" name="subscribe" value="yes" >
      Awsome    
      </label>
  </div>

  <div>
       <label>
      <input type="checkbox" name="subscribe" value="yes" >
      Outstanding     
      </label>
  </div>

  <div>
       <label>
      <input type="checkbox" name="subscribe" value="yes" >
      Flawless!
      </label>
</div>
<div>
<button type="submit">Submit</button>
</div>
</form>  
  </body>
</html>
