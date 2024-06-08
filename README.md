<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>React Challenge</title>

  <link rel="stylesheet" href="https://unpkg.com/sanitize.css@11.0.0/sanitize.css">
  <link rel="stylesheet" href="css/style.processed.css">
</head>

<body>
  
  <!-- Challenge Description -->
  <h1>Welcome to the React Challenge</h1>
  <p>Taken the html structure in the example below (index.html), <br>
    write a simple React calculator (adder) su that has the following mandatory functionalities:<p>
  <ul>
    <li>rows can be added and removed</li>
    <li>each row have a sign (minus or plus)</li>
    <li>each row can be enabled or disabled by a dedicated control button. Disabled rows must be excluded from the addition.</li>
    <li>The result must be updated "live" while the user is writing</li>
  </ul>
  <p>Feel free to add libraries if needed.</p>
  <p>Structure and quality of the code, are matter of evaluation</p>
  <p>ES6+ Javascript knowledge is matter of evaluation</p>
  <p>Look and feel of the solution is a plus</p>
  <!-- END Challeng Description -->
  
  <!-- REMOVE ME -->
  <h2>Example below</h2>
  <div class="wrapper">
    <div>
      <button>Add row</button>
    </div>
    <ul>
      <li>
        <select>
          <option selected>+</option>
          <option>-</option>
        </select>
        <input type="text" value="100"/>
        <button>Delete</button>
        <button>Disable</button>
      </li>
      <li>
        <select>
          <option selected>+</option>
          <option>-</option>
        </select>
        <input type="text" value="30"/>
        <button>Delete</button>
        <button>Disable</button>
      </li>
      <li>
        <select>
          <option>+</option>
          <option selected>-</option>
        </select>
        <input type="text" value="7"/>
        <button>Delete</button>
        <button>Disable</button>
      </li>
    </ul>
    <div>
      Result: 123
    </div>
  </div>
  <!-- END REMOVE ME -->
  
  <!-- React App Container -->
  <div id="app"></div>
  
  <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
  <script src="js/app.processed.js"></script>

</body>

</html>
