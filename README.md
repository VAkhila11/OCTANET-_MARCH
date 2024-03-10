# OCTANET_MARCH
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project Landing Page</title>
    <style>
        /* Reset default margin and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        /* Set background image */
        body {
            background-image: url(https://wallpaperset.com/w/full/0/7/b/259757.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            opacity: 1;
            backdrop-filter: blur(4px);
        }

        /* Style the header */
        header {
            color: #be2bbe;
            padding: 25px;
            text-align: center;
            font-size: 25px;
        }
        marquee{
            color: darkblue;
        }

        /* Style the main content */
        main {
            padding: 25px;
            border:none;
        }

        /* Style the hero section */
        .hero {
            text-align: center;
            rmargin-top: 50px;
        }

        .hero h2 {
            font-size: 35px;
            margin-bottom: 20px;
            margin-top: 20px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        /* Style the call-to-action button */
        .cta-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #3d45e1;
            color:black;
            text-decoration: none;
            border-radius: 50px;
            cursor: pointer;
        }

        .cta-button:hover {
            background-color: #dce1af;
            color:rgb(20, 12, 106);
        }

        footer {
            margin-top: 400px;
            text-align: center;
            color: white;
        }

        /* Style the navigation */
        nav ul {
            list-style-type: none;
            text-align: center;
        }

        nav ul li {
            display: inline-block;
            margin: 0 10px;
        }

        nav a {
            color: rgb(188, 21, 113);
            text-decoration: none;
        }

        nav a:hover {
            color:rgb(43, 15, 126);
        }
    </style>
</head>
<body>
    <header>
        <h1><strong>My Project</strong></h1>
        <marquee direction="left" ><i>!!!!About My Project!!!!</i></marquee>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Blog</a></li> 
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Sign Up</a></li>
            <li><a href="#">Login</a></li>
        </ul>
    </nav>
    <main>
        <section class="hero">
            <h2>Welcome to My Project</h2><br><br>
            <p><i>Discover how our project can solve your problems.</i></p>
            <button class="cta-button" onclick="showAlert()">Get Started</button>
            <script>
                function showAlert() {
                    alert("Thank You For Visiting.");
                }
            </script>
        </section>
    </main>
    <footer>
        <p>&copy; <i>All Rights are Reserved</i></p>
    </footer>
</body>
</html>
