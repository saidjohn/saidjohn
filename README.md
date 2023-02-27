<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" integrity="sha512-kxM+lxwHXEiKkZhpv36mt8yhFy9f+s2c9hTdQ+Z2ASAc7cLwUmKocJgFq3y/xCXDL6HsU6ylsG6YlvFk/PrN3A==" crossorigin="anonymous" />
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 50px;
            background-color: white;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 {
            font-size: 48px;
            margin-bottom: 20px;
            position: relative;
        }

        h1:before {
            content: "";
            width: 60px;
            height: 60px;
            background-color: #f7f7f7;
            border-radius: 50%;
            position: absolute;
            left: -80px;
            top: -30px;
            animation: animate 2s linear infinite;
        }

        @keyframes animate {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }

        p {
            font-size: 24px;
            line-height: 1.5;
            margin-bottom: 20px;
        }

        .info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .info-item {
            width: 25%;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

        .info-item:hover {
            transform: translateY(-10px);
        }

        .info-item h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #555;
        }

        .info-item p {
            font-size: 18px;
            line-height: 1.5;
            color: #777;
        }

        .icon {
            font-size: 48px;
            margin-bottom: 10px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1
