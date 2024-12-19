<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of John Carl G. Aloro">
    <title>My Personal Webpage</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('background-image.jpg') no-repeat center center fixed, linear-gradient(to bottom, #6a11cb, #2575fc); /* Gradient + Image */
            background-size: cover;
            color: #333;
            position: relative;
        }

        /* Add an overlay */
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5); /* Dark overlay */
            z-index: -1; /* Behind the content */
        }

        h1, h2 {
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header Styles */
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        /* Navigation Styles */
        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Container Styles */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
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
            color: #333;
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
            background-color: #333;
            color: white;
        }

        table tr:nth-child(even) {
            background-color: #ecf0f1;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
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
    <h1>John Carl G. Aloro's Portfolio</h1>
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#hobbies">Hobbies</a></li>
            <li><a href="#family">Family</a></li>
        </ul>
    </nav>
</header>

<div class="container">
    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="profile.jpg" alt="Profile Picture of John Carl G. Aloro" class="profile-img">
        <p>Hello! My name is John Carl G. Aloro, and I'm passionate about web development and design. I love exploring new technologies and bonding with my friends and family. I also enjoy traveling, hiking, biking, and playing online games.</p>
    </section>

    <!-- Hobbies Section -->
    <section id="hobbies">
        <h2>My Hobbies</h2>
        <ul>
            <li>Biking</li>
            <li>Traveling</li>
            <li>Hiking</li>
            <li>Playing Sports</li>
            <li>Visiting peaceful places</li>
            <li>Playing online games</li>
            <li>Watching Anime</li>
        </ul>
    </section>

    <!-- Family Section -->
    <section id="family">
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
                    <td>Self</td>
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
    <p>&copy; 2024 John Carl G. Aloro. All Rights Reserved. | <a href="https://github.com/Cidiyey" target="_blank">Visit my GitHub</a></p>
</footer>

</body>
</html>
