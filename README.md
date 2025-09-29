<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MONI Official Website</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #f5a623, #f76b1c);
            color: #fff;
            text-align: center;
        }

        h1 {
            font-size: 3em;
            text-transform: uppercase;
            margin-bottom: 40px;
            animation: fadeInSlide 2s ease-in-out infinite alternate;
        }

        @keyframes fadeInSlide {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .social-links {
            display: flex;
            flex-direction: column;
            gap: 15px;
            font-size: 1.2em;
        }

        .social-links a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s;
        }

        .social-links a:hover {
            color: #000;
        }

        /* Responsive */
        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }

            .social-links {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <h1>WELCOME MONI OFFICIAL WEBSITE</h1>

    <div class="social-links">
        <a href="https://www.facebook.com/share/16AYJ56VaJ/" target="_blank">Facebook Page 1</a>
        <a href="https://www.facebook.com/share/19gYB3BXwJ/" target="_blank">Facebook Page 2</a>
        <a href="https://www.tiktok.com/@screenartisty?_t=ZS-908CnrAhqDf&_r=1" target="_blank">TikTok</a>
        <a href="https://whatsapp.com/channel/0029Vb6MftA7T8bS4GNpzf30" target="_blank">WhatsApp Channel</a>
    </div>
</body>
</html>



