<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>À propos - Blog Bento</title>
    <link rel="stylesheet" href="/static/app.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">DERAMANE Waren</div>
            <nav>
                <ul>
                    <li><a href="/">Accueil</a></li>
                    <li><a href="/articlesa">Articles</a></li>
                    <li><a href="/about" class="active">À propos</a></li>
                    <li><a href="/contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section class="about-section">
            <!-- Section Profil -->
            <article class="bento-item featured">
                <div class="bento-content">
                    <div class="profile-wrapper">
                        <img src="static/pdp-waren.webp" alt="Portrait de Waren Deramane" class="profile-image">
                    </div>    
                    <h1>Bonjour, je suis Waren 👋</h1>
                    <p class="lead">Étudiant en Licence d'Informatique à l’Université de la Nouvelle-Calédonie (UNC) et passionné par l’innovation technologique, je consacre mon temps à explorer les multiples facettes de la programmation. Mon univers s’articule autour de trois axes principaux : la création de jeux vidéo, où je mets en scène des mécaniques interactives ; la robotique, terrain d’expérimentation pour concrétiser des idées en systèmes tangibles ; et l’Impression 3D, ou je mets en pratique mes connaissances en conception et fabrication 3D.</p>

                    <p>Avec 8 ans d'expérience dans la création d'interfaces web innovantes, je partage ici mes découvertes et réflexions sur l'évolution du design numérique.</p>
                </div>
            </article>

            <!-- Section Parcours -->
            <article class="bento-item timeline">
                <div class="bento-content">
                    <h2>Mon Parcours</h2>
                    <div class="timeline-item">
                        <h3>2023-Présent</h3>
                        <p>Lead Designer chez WebInnov</p>
                    </div>
                    <div class="timeline-item">
                        <h3>2020-2023</h3>
                        <p>Développeur front-end chez DigitalCraft</p>
                    </div>
                    <div class="timeline-item">
                        <h3>2018-2020</h3>
                        <p>Formation autodidacte en design d'interface</p>
                    </div>
                </div>
            </article>

            <!-- Section Expertise -->
            <article class="bento-item skills">
                <div class="bento-content">
                    <h2>Expertises</h2>
                    <div class="skills-grid">
                        <div class="skill-item">
                            <h3>UI/UX Design</h3>
                            <p>Création de prototypes interactifs</p>
                        </div>
                        <div class="skill-item">
                            <h3>Développement Web</h3>
                            <p>Stack technique : React, Node.js, Python</p>
                        </div>
                        <div class="skill-item">
                            <h3>Accessibilité</h3>
                            <p>Conception inclusive WCAG 2.1</p>
                        </div>
                    </div>
                </div>
            </article>

            <!-- Philosophie -->
            <article class="bento-item philosophy">
                <div class="bento-content">
                    <h2>Ma Philosophie</h2>
                    <blockquote>
                        "Le bon design est invisible. Il apparaît quand forme et fonction trouvent leur équilibre parfait."
                    </blockquote>
                    <p>Je m'applique à créer des expériences numériques qui marient élégance visuelle et performance technique, toujours centrées sur les besoins utilisateurs.</p>
                </div>
            </article>

            <!-- CTA Contact -->
            <section class="bento-item cta">
                <div class="bento-content">
                    <h2>Travaillons ensemble</h2>
                    <p>Vous avez un projet ou une question ?</p>
                    <a href="/contact" class="button">Me contacter</a>
                </div>
            </section>
        </section>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <!-- Conserver le même footer que la page d'accueil -->
                <!-- ... -->
            </div>
        </div>
    </footer>
</body>
</html>