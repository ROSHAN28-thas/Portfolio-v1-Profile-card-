<!DOCTYPE html>
<html>
<head>
    <title>Profile Card</title>

    <style>
        body {
            background: linear-gradient(to right, #667eea, #764ba2);
            font-family: Arial;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            width: 300px;
            text-align: center;
            box-shadow: 0 0 15px rgba(0,0,0,0.2);
        }

        img {
            width: 100px;
            border-radius: 50%;
        }

        h2 {
            margin: 10px 0;
        }

        p {
            color: gray;
        }

        .skills {
            margin: 10px 0;
        }

        .skills span {
            background: #eee;
            padding: 5px 10px;
            border-radius: 8px;
            margin: 3px;
            display: inline-block;
        }

        button {
            margin-top: 10px;
            padding: 10px;
            border: none;
            background: #667eea;
            color: white;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background: #5a67d8;
        }
    </style>
</head>

<body>

<div class="card">

    <img src="https://via.placeholder.com/100" alt="Profile">

    <h2>Roshan Thaspiha</h2>
    <p>CSE Student | Web Developer</p>

    <div class="skills">
        <span>C</span>
        <span>Python</span>
        <span>Java</span>
        <span>HTML</span>
    </div>

    <button>Contact Me</button>

</div>

</body>
</html>
