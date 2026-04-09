<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Letter</title>
    <style>
        body {
            margin: 0;
            background: #f7b5c8;
            overflow: hidden;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #333;
        }

        /* Card container for better responsiveness */
        .card-container {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            box-sizing: border-box;
        }

        /* Card styling */
        .card {
            max-width: 600px;
            width: 100%;
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: left;
            opacity: 0;
            transform: translateY(50px);
            transition: opacity 1.5s ease, transform 1.5s ease;
            position: relative;
            z-index: 10;
        }

        /* Revealed state */
        .card.show {
            opacity: 1;
            transform: translateY(0);
        }

        /* Card title */
        .card-title {
            text-align: center;
            font-size: 1.8em;
            margin-bottom: 20px;
            color: #e94e77;
        }

        /* Card content */
        .card-content {
            line-height: 1.6;
            font-size: 1.1em;
        }

        /* Click prompt text */
        #clickText {
            text-align: center;
            font-size: 1.2em;
            position: fixed;
            bottom: 180px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 1000;
            color: #fff;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
            transition: opacity 0.5s ease;
        }

        /* Main clickable heart */
        #mainHeart {
            font-size: 100px;
            cursor: pointer;
            position: fixed;
            bottom: 80px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 1000;
            transition: transform 1.2s ease-in-out, bottom 1.2s ease-in-out, opacity 0.8s ease-out;
        }

        /* Floating background hearts */
        .floating-heart {
            position: fixed;
            bottom: -60px;
            opacity: 0.8;
            pointer-events: none;
            animation: floatUp 10s linear infinite;
            z-index: 1;
            filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.1));
        }

        @keyframes floatUp {
            0% {
                transform: translateY(0) rotate(0deg) scale(1);
                opacity: 0.8;
            }
            100% {
                transform: translateY(-120vh) rotate(360deg) scale(1.5);
                opacity: 0;
            }
        }

        /* Media queries for responsiveness */
        @media (max-width: 600px) {
            .card {
                padding: 20px;
            }
            .card-title {
                font-size: 1.5em;
            }
            .card-content {
                font-size: 1em;
            }
            #mainHeart {
                font-size: 80px;
                bottom: 60px;
            }
            #clickText {
                font-size: 1em;
                bottom: 140px;
            }
        }
    </style>
</head>
<body>

    <div class="card-container">
        <div class="card" id="card">
            <h2 class="card-title">HII, CRUSHIIIEEE :>></h2>
            <p class="card-content">
               IF I LOVE YOU LESS WILL YOU LOVE ME MORE?
                <br><br>
               (Ooh-ooh)
(Ooh-ooh)
Ooh-ooh
Ooh-ooh
Keep gettin' less of you
When I give you the best of me
Maybe my love is just too much
Can't get enough of you, no, no
But you won't set me free
You want me the more I don't show up
When I'm ready, you're not ready
Tryna carry this love and it's heavy, yeah
I'm obsessed, you're not sure
If I love you less, will you love me more?
I pull back, you come forward (Ooh-ooh)
If I love you less, will you love me more? (Ooh-ooh)
Ooh-ooh
Ooh-ooh
                <br><br>
                Wastin' my breath
'Cause you like it better when there's none left
When I'm not in your bed
Only time you want me there
But I want you so bad
Wanna give you everything that I have
This is how you should love me, yeah
I'm obsessed, you're not sure
If I love you less, will you love me more?
I pull back, you come forward (Ooh-ooh)
If I love you less, will you love me more? (Ooh-ooh)
Ooh-ooh
Ooh-ooh
                <br><br>
                When I'm ready, you're not ready (Ooh-ooh)
Tryna carry this love and it's heavy, yeah (Ooh-ooh)
Ooh-ooh
If I love you less, will you love me more? (Ooh-ooh)
Ooh-ooh
If I love you less, will you love me more?
                <br><br>
                RELAPSE KA MUNA ATE KYYY.
