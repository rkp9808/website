<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Links</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        h1 {
            color: #333;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.1);
        }

        .link {
            display: inline-block;
            margin: 10px;
            padding: 15px 30px;
            color: #fff;
            text-decoration: none;
            background-color: #007bff;
            border-radius: 5px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .link:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
        }

        .facebook {
            background-color: #3b5998; /* Facebook blue */
        }

        .instagram {
            background-color: #e1306c; /* Instagram pink */
        }

        .linkedin {
            background-color: #0077b5; /* LinkedIn blue */
        }
    </style>
</head>
<body>

    <h1>Connect with Me</h1>

    <a href="https://www.facebook.com/profile.php?id=100027824941754&mibextid=LQQJ4d" target="_blank" class="link facebook">Facebook</a>
    <a href="https://www.instagram.com/official_r_i_t_i_k_kumar?igsh=MTF1Y2syNjc3YzNydw%3D%3D&utm_source=qr" target="_blank" class="link instagram">Instagram</a>
    <a href="https://www.linkedin.com/in/ritik-kumar-ba7931293?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank" class="link linkedin">LinkedIn</a>

</body>
</html>
