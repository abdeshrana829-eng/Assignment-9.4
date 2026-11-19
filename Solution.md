1. Project folder structure
Create a folder named Assignment-9.4 with this structure:


text
Assignment-9.4/
│
├── index.html
├── style.css
│
└── images/
    ├── hero-image.png
    ├── feature-1.png
    ├── feature-2.png
    └── feature-3.png
2. What your landing page should contain
SaaS website design :: Behance
 
Navbar

Website logo

Navigation links

Login or Sign Up button

Clean Website Hero Image Design by Husnain Jaleel on Dribbble
 
Hero section

Main headline

Short description

Call-to-action buttons

Hero image or illustration

SiteCraft: Website Builder Saas Landing Page - Features Section by Keitoto  on Dribbble
 
Feature cards

Three feature cards

Icons or images

Feature titles

Short descriptions

3. Starter HTML (index.html)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Landing Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navbar -->
    <header>
        <nav class="navbar">
            <h2 class="logo">BrandName</h2>

            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Features</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>

            <a href="#" class="nav-btn">Get Started</a>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero">
            <div class="hero-content">
                <h1>Build Something Amazing</h1>
                <p>
                    Discover new possibilities with our
                    simple and powerful platform.
                </p>

                <div class="hero-buttons">
                    <a href="#" class="primary-btn">Get Started</a>
                    <a href="#" class="secondary-btn">Learn More</a>
                </div>
            </div>

            <div class="hero-image">
                <img src="images/hero-image.png"
                     alt="Landing page illustration">
            </div>
        </section>

        <!-- Features Section -->
        <section class="features">
            <h2>Our Features</h2>

            <div class="feature-container">

                <article class="feature-card">
                    <h3>Easy to Use</h3>
                    <p>Simple and user-friendly experience.</p>
                </article>

                <article class="feature-card">
                    <h3>Fast Performance</h3>
                    <p>Enjoy smooth and fast performance.</p>
                </article>

                <article class="feature-card">
                    <h3>Modern Design</h3>
                    <p>Beautiful and modern user interface.</p>
                </article>

            </div>
        </section>
    </main>

    <footer>
        <p>© 2026 BrandName. All rights reserved.</p>
    </footer>

</body>
</html>
4. Starter CSS (style.css)

css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #222;
    background-color: #ffffff;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 25px 8%;
}

.logo {
    color: #4f46e5;
}

.nav-links {
    display: flex;
    gap: 30px;
    list-style: none;
}

.nav-links a {
    text-decoration: none;
    color: #333;
}

.nav-btn,
.primary-btn {
    background: #4f46e5;
    color: white;
    padding: 12px 24px;
    border-radius: 8px;
    text-decoration: none;
}

/* Hero */
.hero {
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    gap: 40px;
    padding: 80px 8%;
}

.hero-content h1 {
    font-size: 52px;
    margin-bottom: 20px;
}

.hero-content p {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 30px;
    color: #666;
}

.hero-buttons {
    display: flex;
    gap: 15px;
}

.secondary-btn {
    border: 1px solid #4f46e5;
    color: #4f46e5;
    padding: 12px 24px;
    border-radius: 8px;
    text-decoration: none;
}

.hero-image img {
    width: 100%;
}

/* Features */
.features {
    padding: 70px 8%;
    text-align: center;
    background: #f8f9ff;
}

.features h2 {
    font-size: 36px;
    margin-bottom: 40px;
}

.feature-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.feature-card {
    background: white;
    padding: 35px 25px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.06);
}

.feature-card h3 {
    margin-bottom: 15px;
}

.feature-card p {
    color: #666;
    line-height: 1.6;
}

/* Footer */
footer {
    text-align: center;
    padding: 25px;
    color: #666;
}
5. GitHub submission
After completing your project, run these commands in your project folder:


bash
git init
git add .
git commit -m "Assignment 9.4 Landing Page"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
6. Assignment checklist

Create index.html.

Create style.css.

Create an images folder.

Build the navbar.

Build the hero section.

Add buttons and feature cards.

Use CSS Grid and Flexbox.

Match the reference design's colors and typography.

Test the desktop layout.

Upload the project to GitHub.
One important thing
Your assignment says based on a given reference design. The code above is only a starter template, not an exact reproduction.

Please upload the reference design screenshot.

I can then help you create the actual landing page matching its:

Colors and fonts

Navbar and spacing

Hero image and text

Buttons and feature cards

Desktop layout