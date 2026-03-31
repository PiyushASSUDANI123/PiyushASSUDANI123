<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assudani Group | Loyalto</title>
    <style>
        :root {
            --bg: #0f172a;
            --card-bg: #1e293b;
            --accent: #38bdf8;
            --text-main: #f8fafc;
            --text-dim: #94a3b8;
        }

        body {
            font-family: 'Inter', -apple-system, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg);
            color: var(--text-main);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
            padding: 4rem 2rem;
            text-align: center;
            border-bottom: 1px solid #334155;
        }

        h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: -1px;
            color: var(--accent);
        }

        .tagline {
            color: var(--text-dim);
            font-size: 1.1rem;
            margin-top: 0.5rem;
        }

        .container {
            max-width: 900px;
            margin: -3rem auto 4rem auto;
            padding: 2.5rem;
            background-color: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3);
            border: 1px solid #334155;
        }

        h2 {
            color: var(--accent);
            border-left: 4px solid var(--accent);
            padding-left: 1rem;
            margin-top: 2rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .skill-tag {
            background: #334155;
            padding: 0.5rem 1rem;
            border-radius: 6px;
            font-size: 0.9rem;
            display: inline-block;
            margin: 0.2rem;
        }

        .contact-list {
            list-style: none;
            padding: 0;
        }

        .contact-list li {
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
        }

        .contact-list strong {
            width: 100px;
            color: var(--accent);
        }

        a {
            color: var(--accent);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 2rem;
            font-size: 0.8rem;
            color: var(--text-dim);
        }
    </style>
</head>
<body>

    <header>
        <h1>Assudani Group</h1>
        <p class="tagline">Engineering Digital Solutions | Founded by Piyush Assudani</p>
    </header>

    <div class="container">
        <h2>About Loyalto</h2>
        <p>
            Assudani Group is a high-performance tech collective focused on <strong>Loyalto</strong> and <strong>Assudani Developers</strong>. We specialize in building scalable web architectures, 3D immersive experiences, and AI-driven automation. With a proven track record of delivering professional software for local institutions and international clients, we bridge the gap between code and commerce.
        </p>

        <h2>Core Expertise</h2>
        <div class="grid">
            <div>
                <strong>Development</strong><br>
                <span class="skill-tag">Next.js</span>
                <span class="skill-tag">React</span>
                <span class="skill-tag">Three.js</span>
                <span class="skill-tag">Python</span>
            </div>
            <div>
                <strong>Security & AI</strong><br>
                <span class="skill-tag">Ethical Hacking</span>
                <span class="skill-tag">NLP</span>
                <span class="skill-tag">Automation</span>
            </div>
        </div>

        <h2>Contact Channels</h2>
        <ul class="contact-list">
            <li><strong>Email:</strong> <a href="mailto:piyushassudani96@gmail.com">piyushassudani96@gmail.com</a></li>
            <li><strong>GitHub:</strong> <a href="https://github.com/Piyush-Assudani">github.com/Piyush-Assudani</a></li>
            <li><strong>Location:</strong> Barmer / Jodhpur, Rajasthan</li>
        </ul>
    </div>

    <footer>
        &copy; 2026 Assudani Group. All rights reserved.
    </footer>

</body>
</html>
