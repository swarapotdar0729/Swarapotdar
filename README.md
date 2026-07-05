# Swarapotdar<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swara Pradip Potdar - Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f7f9fa;
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Header Style */
        header {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: white;
            text-align: center;
            padding: 40px 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-size: 2.8rem;
            letter-spacing: 1px;
        }

        /* Main Layout */
        .container {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            align-items: center;
        }

        /* Left Side: Image Profile */
        .profile-side {
            flex: 1;
            min-width: 250px;
            display: flex;
            justify-content: center;
        }

        .profile-img {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #2575fc;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
        }

        /* Right Side: Information */
        .info-side {
            flex: 1.5;
            min-width: 280px;
        }

        .info-side h2 {
            color: #2575fc;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        .info-side p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #555;
        }

        /* Footer Style */
        footer {
            margin-top: auto;
            background-color: #222;
            color: #bbb;
            text-align: center;
            padding: 20px;
            font-size: 0.95rem;
            letter-spacing: 0.5px;
        }

        /* Responsive adjustments */
        @media (max-width: 600px) {
            .container {
                flex-direction: column;
                text-align: center;
                margin: 20px;
                padding: 20px;
            }
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Swara Pradip Potdar</h1>
    </header>

    <div class="container">
        <div class="profile-side">
            <img src="https://via.placeholder.com/220" alt="Swara Pradip Potdar" class="profile-img">
        </div>

        <div class="info-side">
            <h2>About Me</h2>
            <p>
                I am Swara Pradip Potdar. I am 13 years old. My hobbies are drawing, 
                dancing, and learning new skills. I am currently studying in the 8th standard. 
                My favourite subject is science.
            </p>
        </div>
    </div>

    <footer>
        My self Swara Potdar
    </footer>

</body>
</html>
