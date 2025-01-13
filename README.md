# Media-Gallery
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Media Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 10px;
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .media-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        video, audio {
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Media Gallery</h1>
    </header>

    <div class="container">
        <!-- Video Section -->
        <div class="section">
            <h2>Videos</h2>
            <div class="media-grid">
                <video controls>
                    <source src="1.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <video controls>
                    <source src="2.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <video controls>
                    <source src="3.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <video controls>
                    <source src="4.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <video controls>
                    <source src="5.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <video controls>
                    <source src="6.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </div>

        <!-- Audio Section -->
        <div class="section">
            <h2>Audios</h2>
            <div class="media-grid">
                <audio controls>
                    <source src="1.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
                <audio controls>
                    <source src="2.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
                <audio controls>
                    <source src="3.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
                <audio controls>
                    <source src="4.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
                <audio controls>
                    <source src="5.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
                <audio controls>
                    <source src="6.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>
    </div>
</body>
</html>
