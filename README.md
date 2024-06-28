<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Prefectorial Board</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #004080;
            color: white;
            padding: 10px 0;
            text-align: center;
            position: relative;
        }
        .header img {
            width: 50px;
            position: absolute;
            top: 10px;
        }
        .header .logo-left {
            left: 10px;
        }
        .header .logo-right {
            right: 10px;
        }
        .nav {
            background-color: #003366;
            overflow: hidden;
        }
        .nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        .nav a:hover {
            background-color: #575757;
        }
        .dropdown {
            float: left;
            overflow: hidden;
        }
        .dropdown .dropbtn {
            font-size: 16px;  
            border: none;
            outline: none;
            color: white;
            padding: 14px 16px;
            background-color: inherit;
            font-family: inherit;
            margin: 0;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
        }
        .dropdown-content a {
            float: none;
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: left;
        }
        .dropdown-content a:hover {
            background-color: #ddd;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
        .main {
            padding: 20px;
            margin: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<div class="header">
    <img src="logo1.png" alt="Logo 1" class="logo-left">
    <h1>School Prefectorial Board</h1>
    <img src="logo2.png" alt="Logo 2" class="logo-right">
</div>

<div class="nav">
    <a href="#home">Home</a>
    <div class="dropdown">
        <button class="dropbtn">About Us 
            <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content">
            <a href="#our-mission">Our Mission</a>
            <a href="#team">Team</a>
        </div>
    </div> 
    <div class="dropdown">
        <button class="dropbtn">Events 
            <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content">
            <a href="#upcoming-events">Upcoming Events</a>
            <a href="#past-events">Past Events</a>
        </div>
    </div> 
    <a href="#contact">Contact</a>
</div>

<div class="main">
    <h2>Welcome to the School Prefectorial Board Website</h2>
    <p>This is where you can find all the latest information about our school's prefectorial board, upcoming events, our mission, and much more.</p>
</div>

<div class="footer">
    <p>&copy; 2024 School Prefectorial Board. All rights reserved.</p>
</div>

</body>
</html>
