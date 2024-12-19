<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Carl G. Aloro - Portfolio</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
      color: #333;
    }

    h1, h2 {
      font-family: 'Arial', sans-serif;
      color: #333;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header Styles */
    header {
      background-color: #2C3E50;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3em;
    }

    /* Container Styles */
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 20px auto;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    /* Profile Image */
    .profile-img {
      display: block;
      margin: 20px auto;
      border-radius: 50%;
      width: 200px;
      height: 200px;
      object-fit: cover;
    }

    /* Sections */
    section {
      margin: 40px 0;
    }

    h2 {
      font-size: 2em;
      margin-bottom: 10px;
      color: #2C3E50;
    }

    p {
      font-size: 1.1em;
      line-height: 1.6;
      margin-bottom: 20px;
    }

    /* List of Hobbies */
    ul {
      list-style-type: none;
      padding: 0;
    }

    ul li {
      background-color: #ecf0f1;
      padding: 12px;
      margin: 8px 0;
      border-radius: 8px;
      font-size: 1.1em;
    }

    /* Family Table Styles */
    table {
      width: 100%;
      margin-top: 20px;
      border-collapse: collapse;
    }

    table th, table td {
      padding: 12px;
      text-align: left;
      border: 1px solid #ddd;
    }

    table th {
      background-color: #2C3E50;
      color: white;
    }

    table tr:nth-child(even) {
      background-color: #ecf0f1;
    }

    /* Footer Styles */
    footer {
      background-color: #34495E;
      color: white;
      padding: 20px;
      text-align: center;
    }

    footer a {
      color: #1abc9c;
    }

    /* Responsive Styles */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5em;
      }

      .container {
        padding: 15px;
      }

      ul li {
        font-size: 1em;
      }

      table th, table td {
        font-size: 0.9em;
      }

      .profile-img {
        width: 150px;
        height: 150px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>John Carl G. Aloro</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
  </header>

  <div class="container">
    <img src="hihihi.jpg" alt="Profile Picture" class="profile-img">

    <section>
      <p>Hello! My name is John Carl G. Aloro, and I'm passionate about web development and design. I love exploring new technologies and bonding with my friends and family. I also enjoy traveling, hiking, biking, and playing online games.</p>
    </section>

    <section>
      <h2>My Hobbies</h2>
      <ul>
        <li>Biking</li>
        <li>Traveling</li>
        <li>Hiking</li>
        <li>Playing sports</li>
        <li>Visiting calming places</li>
        <li>Playing online games</li>
        <li>Watching Anime</li>
      </ul>
    </section>

    <section>
      <h2>My Family</h2>
      <table>
        <thead>
          <tr>
            <th>Name</th>
            <th>Relationship</th>
            <th>Age</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>John Carl Aloro</td>
            <td>Student</td>
            <td>23</td>
          </tr>
          <tr>
            <td>Geraldine Aloro</td>
            <td>Mother</td>
            <td>43</td>
          </tr>
          <tr>
            <td>Roel Quirol</td>
            <td>Father</td>
            <td>47</td>
          </tr>
          <tr>
            <td>Zyreen A. Cotoner</td>
            <td>Step Brother</td>
            <td>15</td>
          </tr>
          <tr>
            <td>Kelvin Clyde A. Cotoner</td>
            <td>Step Brother</td>
            <td>12</td>
          </tr>
        </tbody>
      </table>
    </section>
  </div>

  <footer>
    <p>&copy; 2024 John Carl G. Aloro | <a href="https://github.com/Cidiyey" target="_blank">Visit my GitHub</a></p>
  </footer>

</body>
</html>
