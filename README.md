<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Creative Corner | Art & Craft Gallery</title>
    <style>
        /* Artistic Cherry Red & White Theme */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #D2143A 0%, #FFFFFF 100%);
            background-attachment: fixed;
            color: #333;
        }

        header {
            background-color: #D2143A; /* Cherry Red */
            color: white;
            text-align: center;
            padding: 3rem 1rem;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        header p {
            font-style: italic;
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 30px;
            background: rgba(255, 255, 255, 0.97); /* Bright white card area */
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border-radius: 15px;
        }

        h2 {
            color: #D2143A;
            border-bottom: 3px solid #D2143A;
            padding-bottom: 8px;
            font-size: 2rem;
        }

        /* Layout for the Art Grid */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }

        .art-card {
            background: #fff;
            border: 2px solid #f0f0f0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .art-card:hover {
            transform: translateY(-5px); /* Makes the card lift up nicely when hovered */
            border-color: #D2143A;
        }

        /* Placeholder for Art Images */
        .art-image-placeholder {
            background-color: #ffebee;
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #D2143A;
            font-weight: bold;
            font-size: 1.1rem;
            border-bottom: 1px solid #f0f0f0;
        }

        .art-info {
            padding: 15px;
        }

        .art-info h3 {
            margin: 0 0 10px 0;
            color: #D2143A;
        }

        .art-info p {
            margin: 0;
            font-size: 0.95rem;
            color: #666;
        }

        /* Contact Box styling */
        .contact-box {
            background-color: #ffebee;
            border-left: 5px solid #D2143A;
            padding: 20px;
            border-radius: 4px;
            margin-top: 30px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1a1a1a;
            color: white;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>THE CREATIVE CORNER</h1>
        <p>A Beautiful Gallery of Handmade Art & Crafts</p>
    </header>

    <!-- Main Website Content -->
    <div class="container">

        <!-- Welcome Section -->
        <section>
            <h2>Welcome to our Gallery</h2>
            <p>Explore a collection of wonderful drawings, sketches, paintings, and creative craft ideas. Everything here is created with passion, imagination, and a lot of bright colors!</p>
        </section>

        <!-- Art Gallery Section -->
        <section>
            <h2>Featured Art & Crafts</h2>
            <div class="gallery-grid">

                <!-- Art Item 1 -->
                <div class="art-card">
                    <div class="art-image-placeholder">🎨 Colorful Painting</div>
                    <div class="art-info">
                        <h3>Canvas Canvas Painting</h3>
                        <p>Beautiful watercolor scenery created using mixing and shading techniques.</p>
                    </div>
                </div>

                <!-- Art Item 2 -->
                <div class="art-card">
                    <div class="art-image-placeholder">✂️ Paper Craft</div>
                    <div class="art-info">
                        <h3>Origami & Paper Flowers</h3>
                        <p>Creative handmade flowers made completely out of colorful craft sheets.</p>
                    </div>
                </div>

                <!-- Art Item 3 -->
                <div class="art-card">
                    <div class="art-image-placeholder">✏️ Pencil Sketch</div>
                    <div class="art-info">
                        <h3>Portrait Sketching</h3>
                        <p>Detailed black and white pencil shading portrait displaying realistic expressions.</p>
                    </div>
                </div>

            </div>
        </section>

        <!-- Contact Section -->
        <section>
            <h2>Join Our Art Classes</h2>
            <div class="contact-box">
                <p><strong>Want to learn how to make these?</strong> We organize weekly hobby drawing and creative craft sessions for beginners!</p>
                <p>📧 <strong>Email Us:</strong> princesspadmaraje@gmail.com</p>
            </div>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 The Creative Corner. Made with Love & Art.</p>
    </footer>

</body>
</html>
