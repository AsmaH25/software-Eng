<!DOCTYPE html>
<html>
<head>
    <title>My Profile</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            background-color: #e0f7fa;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        .profile-card {
            background: white;
            max-width: 400px;
            margin: 20px auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        h2 {
            color: #00796b;
        }
        p {
            color: #455a64;
        }
        button {
            background-color: #00796b;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #004d40;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img src="https://via.placeholder.com/100" alt="Profile Picture">
        <h2>Your Name</h2>
        <p>Web Developer & Designer</p>
        <button onclick="alert('Thank you for visiting!')">Say Hello</button>
    </div>
</body>
</html>

