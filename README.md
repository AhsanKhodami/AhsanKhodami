<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahsan Khodami's GitHub</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #2C3E50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        h1 {
            font-size: 2.5rem;
        }
        h2 {
            font-size: 1.75rem;
            color: #2980B9;
        }
        .content {
            padding: 40px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            border-bottom: 2px solid #2980B9;
            padding-bottom: 5px;
            margin-bottom: 20px;
        }
        .projects, .contributions, .facts {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .card h3 {
            margin-top: 0;
        }
        .card p {
            color: #555;
        }
        .contact {
            text-align: center;
            background-color: #2980B9;
            color: white;
            padding: 20px;
            border-radius: 8px;
        }
        .contact a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #2C3E50;
            color: white;
        }
        footer p {
            margin: 0;
        }
        footer a {
            color: #2980B9;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My GitHub 👨‍🔬✨</h1>
</header>

<div class="content">
    <section class="section">
        <h2>🧠 About My Work</h2>
        <p>Hello, I am <strong>Ahsan Khodami</strong>, a <strong>Marie Curie Fellow</strong> at the University of Padua, with a deep passion for unraveling the mysteries of visual processing and neural mechanisms. My work integrates cutting-edge techniques in <strong>EEG</strong>, <strong>eye-tracking</strong>, and computational models to explore phenomena such as <strong>hemianopia</strong> and predictive coding in visual tasks.</p>
    </section>

    <section class="section">
        <h2>🔬 Key Projects</h2>
        <div class="projects">
            <div class="card">
                <h3>1. Temporal Processing in Hemianopia</h3>
                <p>Exploring visual processing speed in individuals with hemianopia using eye-tracking and EEG data, modeling temporal resolution and spatial cue impacts on visual tasks.</p>
            </div>
            <div class="card">
                <h3>2. Aperiodic EEG in Visual Tasks</h3>
                <p>Research on aperiodic EEG correlates with variability in visual temporal processing, enhancing our understanding of neural dynamics during visual tasks.</p>
            </div>
            <div class="card">
                <h3>3. Pupil Size & Blink Dynamics</h3>
                <p>Developed models to detect blink intervals and reconstruct pupil size during occlusions, using physiological dynamics and noise simulations to simulate natural recovery patterns.</p>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>📦 Open Source Contributions</h2>
        <div class="contributions">
            <div class="card">
                <h3><a href="https://pypi.org/project/asc2csv/" target="_blank">asc2csv</a></h3>
                <p>A Python package for converting EyeLink `.asc` files to `.csv` format, facilitating data analysis in eye-tracking studies.</p>
            </div>
            <div class="card">
                <h3><a href="https://pypi.org/project/prpip/" target="_blank">prpip</a></h3>
                <p>An automated pipeline manager that integrates version control and deployment through GitHub Actions, streamlining the development process.</p>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>🌟 Fun Facts</h2>
        <div class="facts">
            <div class="card">
                <h3>🐾 Proud Cat Dad</h3>
                <p>I am the proud owner of a playful cat named <strong>Kiki</strong>.</p>
            </div>
            <div class="card">
                <h3>💬 Fluent in Russian</h3>
                <p>Not only am I passionate about science, but I also speak Russian and enjoy both academic discussions and casual conversations.</p>
            </div>
            <div class="card">
                <h3>📚 Interdisciplinary Approach</h3>
                <p>My work combines neuroscience, data science, and psychophysics, bridging these disciplines to uncover novel insights into human cognition and perception.</p>
            </div>
        </div>
    </section>
</div>

<section class="contact">
    <h2>📫 Let's Connect</h2>
    <p>Feel free to explore my research and get in touch:</p>
    <p><a href="https://www.khodami.site" target="_blank">My Research Portfolio</a> | <a href="mailto:ahsan.khodami@gmail.com">Email Me</a></p>
</section>

<footer>
    <p>📈 *"Science is not only a discipline of reason but, also, one of romance and passion." – Stephen Hawking*</p>
    <p>Made with ❤️ by Ahsan Khodami</p>
</footer>

</body>
</html>
