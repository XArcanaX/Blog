<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Bento</title>
    <link rel="stylesheet" href="/static/app.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">DERAMANE Waren</div>
            <nav>
                <ul>
                    <li><a href="/">Accueil</a></li>
                    <li><a href="/articlesa" class="active">Articles</a></li>
                    <li><a href="/about">À propos</a></li>
                    <li><a href="/contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">


        <div class="bento-grid">
            <!-- Articles réguliers -->
            <article class="bento-item">
                <img src="/optimisation-performance.webp" alt="Graphique de performance web">
                <div class="bento-content">
                    <span class="category">Développement</span>
                    <h3>Optimisation de performance web</h3>
                    <p>Les meilleures pratiques pour améliorer la vitesse de chargement de votre site.</p>
                    <div class="article-meta">
                        <time datetime="2025-05-12">12 mai 2025</time>
                        <span class="read-time">4 min</span>
                    </div>
                </div>
            </article>

                        <article class="bento-item">
                <img src="/optimisation-performance.webp" alt="Graphique de performance web">
                <div class="bento-content">
                    <span class="category">Développement</span>
                    <h3>Optimisation de performance web</h3>
                    <p>Les meilleures pratiques pour améliorer la vitesse de chargement de votre site.</p>
                    <div class="article-meta">
                        <time datetime="2025-05-12">12 mai 2025</time>
                        <span class="read-time">4 min</span>
                    </div>
                </div>
            </article>

            <!-- Newsletter -->
            <section class="bento-item newsletter" aria-label="Inscription à la newsletter">
                <div class="bento-content">
                    <h3>Restez informé</h3>
                    <form id="newsletter-form">
                        <label for="email">Abonnez-vous à notre newsletter :</label>
                        <input type="email" id="email" placeholder="Votre adresse email" required>
                        <button type="submit">S'abonner</button>
                    </form>
                </div>
            </section>

            <!-- Nuage de tags -->
            <nav class="bento-item tags" aria-label="Navigation par tags">
                <div class="bento-content">
                    <h3>Explorez par tags</h3>
                    <div class="tags-cloud">
                        <a href="/tags/design" class="tag">Design</a>
                        <a href="/tags/javascript" class="tag">JavaScript</a>
                        <a href="/tags/css" class="tag">CSS</a>
                    </div>
                </div>
            </nav>
        </div>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>À propos</h3>
                    <p>Un blog minimaliste au design Bento, dédié aux tendances du web et du design.</p>
                </div>
                <div class="footer-section">
                    <h3>Liens utiles</h3>
                    <ul>
                        <li><a href="/archives">Archives</a></li>
                        <li><a href="/confidentialite">Confidentialité</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Réseaux sociaux</h3>
                    <div class="social-links">
                        <a href="https://twitter.com" aria-label="Notre Twitter">
                            <svg aria-hidden="true">...</svg>
                        </a>
                        <a href="https://linkedin.com" aria-label="Notre LinkedIn">
                            <svg aria-hidden="true">...</svg>
                        </a>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Minimal Blog. Tous droits réservés.</p>
            </div>
        </div>
    </footer>
</body>
</html>