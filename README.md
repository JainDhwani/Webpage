<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Internship Task 1 - Level 1</title>
    <link rel="stylesheet" href="style.css" />
</head>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: #fef9f8;
        color: #4a4a4a;
        line-height: 1.8;
    }

    /* Navbar Styles */
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #f6d6d6;
        padding: 10px 30px;
        border-bottom: 2px solid #f3c1c1;
    }

    .logo-container {
        display: flex;
        align-items: center;
    }

    .logo-img {
        width: 40px;
        height: 40px;
        margin-right: 10px;
    }

    .logo-text {
        font-size: 22px;
        color: #b44c4c;
    }

    .nav-links {
        list-style: none;
        display: flex;
    }

    .nav-links li {
        margin-left: 20px;
    }

    .nav-links a {
        text-decoration: none;
        color: #b44c4c;
        font-weight: bold;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #e68a8a;
    }

    /* Main Image */
    .main-image {
        padding: 20px 30px;
    }

    .main-image img {
        max-width: 300px;
        width: 100%;
        border-radius: 10px;
    }

    /* About Section */
    .about {
        padding: 30px;
        background-color: #fff0f3;
        border-radius: 12px;
        margin: 30px auto;
        max-width: 900px;
        text-align: center;
    }

    .about h2 {
        color: #b44c4c;
        margin-bottom: 15px;
    }

    /* Info Section */
    .info-section {
        padding: 30px;
        background-color: #e5eaf5;
        border-radius: 12px;
        margin: 30px auto;
        max-width: 900px;
    }

    .info-section h2 {
        text-align: center;
        margin-bottom: 20px;
        color: #3f4c6b;
    }

    .info-section p {
        margin-bottom: 12px;
        text-align: justify;
    }

    /* Comment Section */
    .comment-section {
        padding: 30px;
        background-color: #fef6e4;
        border-radius: 12px;
        margin: 30px auto;
        max-width: 900px;
        text-align: center;
    }

    .comment-section h2 {
        color: #c17c2f;
        margin-bottom: 20px;
    }

    form input[type="text"] {
        padding: 12px;
        width: 60%;
        max-width: 350px;
        border: 1px solid #ddd;
        border-radius: 6px;
        font-size: 16px;
    }

    form button {
        padding: 12px 20px;
        margin-left: 10px;
        background-color: #c17c2f;
        color: white;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    form button:hover {
        background-color: #a9641c;
    }
</style>


<body>

    <!-- Header with logo -->
    <header>
        <nav class="navbar">
            <div class="logo-container">
                <img src="cognifyz-1.png" alt="Cognifyz Logo" class="logo-img" />
                <h1 class="logo-text">Cognifyz Technologies</h1>
            </div>
            <ul class="nav-links">
                <li><a href="https://cognifyz.com/">Website</a></li>
                <li><a href="https://www.linkedin.com/company/cognifyz-techonologies/">LinkedIn</a></li>
                <li><a href="https://t.me/cognifyz_technologies">Telegram</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Image -->
    <div class="main-image">
        <img src="cognifyz-1.png" alt="Sample Image" />
    </div>

    <!-- About Message -->
    <section class="about" id="about">
        <h2>Welcome to My Webpage</h2>
        <p>
            I am truly overwhelmed and grateful for the opportunity to work with such an innovative and inspiring
            company
            like Cognifyz Technologies. Being a part of this internship has not only enhanced my technical skills but
            also
            boosted my confidence and creativity. The supportive environment and meaningful tasks have made this journey
            incredibly fulfilling. I’m genuinely honored to contribute and learn from such a talented team, and I would
            love
            to continue being a part of this amazing organization. Thank you, Cognifyz, for this wonderful experience!
        </p>
    </section>

    <!-- What is Cognifyz Section -->
    <section class="info-section">
        <h2>What is Cognifyz Technologies?</h2>
        <p>
            Cognifyz Technologies is a technology company that provides software solutions for businesses. The company
            offers a range of products and services, including artificial intelligence (AI), machine learning (ML), and
            data analytics tools.
        </p>
        <p>
            One of the main offerings of Cognifyz Technologies is their AI-powered chatbot platform, which can be
            integrated with various communication channels such as websites, social media, and messaging apps. The
            chatbot platform allows businesses to automate their customer support and engagement, reduce response time,
            and improve customer satisfaction.
        </p>
        <p>
            Cognifyz Technologies also provides ML-based solutions for predictive analytics, fraud detection, and
            recommendation engines. These tools help businesses to analyze large amounts of data and make data-driven
            decisions in real-time.
        </p>
    </section>

    <!-- Comment Section -->
    <section class="comment-section" id="contact">
        <h2>Comment Section</h2>
        <form>
            <input type="text" placeholder="Write your comment..." required />
            <button type="submit">Comment</button>
        </form>
    </section>

</body>

</html>
