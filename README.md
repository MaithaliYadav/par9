!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive CSS3 Webpage</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        /* CSS Variables for easy theme management */
        :root {
            --primary-bg: #333;
            --text-light: #fff;
            --accent-color: #007bff;
            --body-bg: #f4f4f9;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--body-bg);
            line-height: 1.6;
        }

        header {
            background-color: var(--primary-bg);
            color: var(--text-light);
            padding: 2rem 1rem;
            text-align: center;
        }

        main {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1.5rem;
            background: white;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            border-radius: 8px;
        }

        /* Mobile adjustment */
        @media (max-width: 600px) {
            main {
                margin: 1rem;
            }
            header h1 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Responsive Webpage</h1>
    </header>
    <main>
        <p>This is a sample responsive webpage using HTML5 and CSS3. The layout adjusts automatically based on the screen size.</p>
    </main>
</body>
</html># par9
