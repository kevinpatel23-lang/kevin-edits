# kevin-edits
for editing 
Here is the updated code with a sleek dark background image, clean styling, and expressive emojis added throughout to match your vibe! 🚀✨

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🎬 Video Editor Portfolio & Gallery</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }
        body {
            /* Background photo overlayed with a dark gradient so text stands out */
            background: linear-gradient(rgba(15, 15, 15, 0.85), rgba(15, 15, 15, 0.92)), 
                        url('https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
            background-size: cover;
            color: #ffffff;
            line-height: 1.6;
        }
        header {
            text-align: center;
            padding: 60px 20px 20px;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #3ea6ff;
        }
        header p {
            color: #ccc;
            font-size: 1.1rem;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }
        .video-card {
            background: rgba(31, 31, 31, 0.85);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease;
        }
        .video-card:hover {
            transform: translateY(-5px);
        }
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
        }
        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
        .video-info {
            padding: 15px;
        }
        .video-info h3 {
            font-size: 1.1rem;
            margin-bottom: 5px;
        }
        .contact-section {
            margin-top: 80px;
            background: rgba(24, 24, 24, 0.85);
            backdrop-filter: blur(10px);
            padding: 40px 20px;
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            text-align: center;
        }
        .contact-section h2 {
            margin-bottom: 15px;
            font-size: 1.8rem;
        }
        .form-container {
            max-width: 600px;
            margin: 0 auto;
        }
        iframe.contact-form {
            width: 100%;
            height: 450px;
            border: none;
            background: transparent;
        }
        footer {
            text-align: center;
            padding: 40px;
            color: #888;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>⚡ Video Editing Portfolio 🎥</h1>
        <p>🔥 High-Retention Short-Form & Cinematic Cuts 🎬</p>
    </header>

    <div class="container">
        <!-- Video Grid Gallery -->
        <div class="gallery-grid">
            
            <!-- Video Item 1 -->
            <div class="video-card">
                <div class="video-wrapper">
                    <!-- Replace YOUR_YOUTUBE_ID_1 with your unlisted YouTube video ID -->
                    <iframe src="https://www.youtube.com/embed/YOUR_YOUTUBE_ID_1" allowfullscreen></iframe>
                </div>
                <div class="video-info">
                    <h3>⚡ Reel Edit Style 01 - Fast Pacing & Captions 🚀</h3>
                </div>
            </div>

            <!-- Video Item 2 -->
            <div class="video-card">
                <div class="video-wrapper">
                    <!-- Replace YOUR_YOUTUBE_ID_2 with your unlisted YouTube video ID -->
                    <iframe src="https://www.youtube.com/embed/YOUR_YOUTUBE_ID_2" allowfullscreen></iframe>
                </div>
                <div class="video-info">
                    <h3>🎙️ Podcast Highlight - Sound Design & Zoom Cuts 🔥</h3>
                </div>
            </div>

            <!-- Video Item 3 -->
            <div class="video-card">
                <div class="video-wrapper">
                    <!-- Replace YOUR_YOUTUBE_ID_3 with your unlisted YouTube video ID -->
                    <iframe src="https://www.youtube.com/embed/YOUR_YOUTUBE_ID_3" allowfullscreen></iframe>
                </div>
                <div class="video-info">
                    <h3>💪 Gym & Fitness Promo - Dynamic Transitions 💯</h3>
                </div>
            </div>

        </div>

        <!-- Contact Section with Embedded Form -->
        <div class="contact-section">
            <h2>🤝 Let's Work Together 💬</h2>
            <p style="color: #ccc; margin-bottom: 25px;">📥 Drop your contact details below to discuss your next project! 👇</p>
            
            <div class="form-container">
                <!-- Paste your Tally.so or Google Form embed code below -->
                <iframe class="contact-form" src="https://tally.so/embed/YOUR_TALLY_FORM_ID?transparentBackground=1" title="Contact Form"></iframe>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2026 Video Editor Portfolio. All rights reserved. 🌟</p>
    </footer>

</body>
</html>

```
